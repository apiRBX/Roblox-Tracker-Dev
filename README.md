# Roblox API Tracker (Development)

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.493.0.4930373` |
| **Version Hash** | `version-04c0166b90104f00` |
| **Official Release Notes** | [Release Notes 493](https://create.roblox.com/docs/release-notes/release-notes-493) |

---

## API Changelog

* Update 🔷 [`AssetImportService`](https://create.roblox.com/docs/reference/engine/classes/AssetImportService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add 🔮 [`UploadCurrentMesh`](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#UploadCurrentMesh)() -> void [🔒 RobloxScriptSecurity]
* Update 🔷 [`GuiService`](https://create.roblox.com/docs/reference/engine/classes/GuiService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add 📘 [`TouchControlsEnabled`](https://create.roblox.com/docs/reference/engine/classes/GuiService#TouchControlsEnabled): bool
* Update 🔷 [`PathfindingModifier`](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier)
  * Add 📘 [`PassThrough`](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier#PassThrough): bool
* Update 🔷 [`PlayerEmulatorService`](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService) [🏷️ NotCreatable] [🏷️ Service]
  * Add 📘 [`CustomPoliciesEnabled`](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#CustomPoliciesEnabled): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden]
* Update 🔷 [`Plugin`](https://create.roblox.com/docs/reference/engine/classes/Plugin) [🏷️ NotCreatable]
  * Add 🔮 [`SetReady`](https://create.roblox.com/docs/reference/engine/classes/Plugin#SetReady)() -> void [🔒 RobloxScriptSecurity]
  * Add ⚡ [`Ready`](https://create.roblox.com/docs/reference/engine/classes/Plugin#Ready) [🔒 RobloxScriptSecurity]
* Update 🔷 [`Selection`](https://create.roblox.com/docs/reference/engine/classes/Selection) [🏷️ NotCreatable] [🏷️ Service]
  * Add 🔮 [`ClearTerrainSelectionHack`](https://create.roblox.com/docs/reference/engine/classes/Selection#ClearTerrainSelectionHack)() -> void [🔒 RobloxScriptSecurity]
  * Add 🔮 [`SetTerrainSelectionHack`](https://create.roblox.com/docs/reference/engine/classes/Selection#SetTerrainSelectionHack)(center: Vector3, size: Vector3) -> void [🔒 RobloxScriptSecurity]
* Update 🔷 [`Studio`](https://create.roblox.com/docs/reference/engine/classes/Studio) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add 📘 [`EnableOnTypeAutocomplete`](https://create.roblox.com/docs/reference/engine/classes/Studio#EnableOnTypeAutocomplete): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
  * Add 📘 [`Set Pivot of Imported Parts`](https://create.roblox.com/docs/reference/engine/classes/Studio#Set Pivot of Imported Parts): bool
* Update 🔷 [`StudioService`](https://create.roblox.com/docs/reference/engine/classes/StudioService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Remove 🔮 `BaseURLHasChineseHost`
