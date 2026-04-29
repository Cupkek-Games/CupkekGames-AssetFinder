# CupkekGames AssetFinder

Editor toolbar that auto-populates `List<>` / `KeyValueDatabase<>` fields with assets matching attribute filters. Extracted from `com.cupkekgames.core`.

## What's inside

**Runtime** (`CupkekGames.AssetFinder.asmdef`)
- `AssetFinderAttribute` — apply to fields to surface a populate toolbar in the inspector
- `AssetFinderFilterConfig` — abstract filter base + name/label/path/exclude variants

**Editor** (`CupkekGames.AssetFinder.Editor.asmdef`)
- `AssetFinder` — populator engine
- `AssetFinderAttributeDrawer` — inspector drawer that adds the toolbar
- `AssetFinderToolbar` — UI Toolkit toolbar
- Filter drawers: `NameFilterConfigDrawer`, `LabelFilterConfigDrawer`, `PathFilterConfigDrawer`, `ExcludeNameFilterConfigDrawer`

## Dependencies

- `com.cupkekgames.keyvaluedatabases`
