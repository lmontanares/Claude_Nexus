# Refresh Dependencies

Clear all dependencies from pyproject.toml and re-add them with latest versions using uv.

## Process:
1. **Read current dependencies:** Extract package names from the existing `dependencies` array in pyproject.toml
2. **Read current dev dependencies:** Extract package names from the existing `dev` dependency group or optional dependencies  
3. **Clear dependencies:** Set `dependencies = []` in pyproject.toml
4. **Clear dev dependencies:** Set `dev = []` in the dependency groups or optional dependencies
5. **Re-add production packages:** Use `uv add [package-names]` to install latest versions of the production dependencies
6. **Re-add dev packages:** Use `uv add --dev [package-names]` to install latest versions of the development dependencies
7. **Verify results:** Check that pyproject.toml has the updated package versions

## Benefits:
- ✅ Works with any project's existing dependencies
- ✅ Preserves the same packages but updates to latest versions
- ✅ Maintains proper separation of production vs development dependencies
- ✅ Clean dependency resolution through uv

This ensures clean dependency management with latest versions while preserving your project's specific package choices.