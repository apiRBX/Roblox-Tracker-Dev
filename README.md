# Roblox API Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.489.0.4890336` |
| **Version Hash** | `version-103a34b6ca094f9a` |
| **Dump Timestamp** | `2026-08-04 05:27:45 UTC` |
| **Official Release Notes** | [Release Notes 489](https://create.roblox.com/docs/release-notes/release-notes-489) |

---

## Quick Navigation Links
* [Engine Classes](https://create.roblox.com/docs/reference/engine/classes)
* [Engine Datatypes](https://create.roblox.com/docs/reference/engine/datatypes)
* [Engine Enums](https://create.roblox.com/docs/reference/engine/enums)
* [Engine Globals](https://create.roblox.com/docs/reference/engine/globals)
* [Engine Libraries](https://create.roblox.com/docs/reference/engine/libraries)

---

## Detailed API Changes

* Add 🔷 [`DataStoreKey`](https://create.roblox.com/docs/reference/engine/classes/DataStoreKey)
  * Add 📘 [`KeyName`](https://create.roblox.com/docs/reference/engine/classes/DataStoreKey#KeyName)
* Update 🔷 [`DataStoreKeyInfo`](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo)
  * Add 📘 [`CreatedTime`](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#CreatedTime)
  * Add 📘 [`UpdatedTime`](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#UpdatedTime)
  * Add 📘 [`Version`](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#Version)
  * Add 🔮 [`GetMetadata`](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#GetMetadata)
  * Add 🔮 [`GetUserIds`](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#GetUserIds)
  * Remove 📘 `KeyName`
* Add 🔷 [`DataStoreObjectVersionInfo`](https://create.roblox.com/docs/reference/engine/classes/DataStoreObjectVersionInfo)
  * Add 📘 [`CreatedTime`](https://create.roblox.com/docs/reference/engine/classes/DataStoreObjectVersionInfo#CreatedTime)
  * Add 📘 [`IsDeleted`](https://create.roblox.com/docs/reference/engine/classes/DataStoreObjectVersionInfo#IsDeleted)
  * Add 📘 [`Version`](https://create.roblox.com/docs/reference/engine/classes/DataStoreObjectVersionInfo#Version)
* Add 🔷 [`DataStoreOptions`](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions)
  * Add 📘 [`AllScopes`](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions#AllScopes)
  * Add 🔮 [`SetExperimentalFeatures`](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions#SetExperimentalFeatures)
* Update 🔷 [`DataStoreService`](https://create.roblox.com/docs/reference/engine/classes/DataStoreService)
  * Change ReturnType of 🔮 [`ListDataStoresAsync`](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#ListDataStoresAsync) from **`DataStoreEnumerationPages`** to **`DataStoreListingPages`**
* Update 🔷 [`GuiService`](https://create.roblox.com/docs/reference/engine/classes/GuiService)
  * Add ⚡ [`CoreGuiRenderOverflowed`](https://create.roblox.com/docs/reference/engine/classes/GuiService#CoreGuiRenderOverflowed)
* Add 🔷 [`DataStoreListingPages`](https://create.roblox.com/docs/reference/engine/classes/DataStoreListingPages)
* Add 🔷 [`PathfindingModifier`](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier)
  * Add 📘 [`ModifierId`](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier#ModifierId)
* Update 🔷 [`Studio`](https://create.roblox.com/docs/reference/engine/classes/Studio)
  * Add 📘 [`DEPRECATED_DisableAccuratePlaySolo`](https://create.roblox.com/docs/reference/engine/classes/Studio#DEPRECATED_DisableAccuratePlaySolo)
  * Add 📘 [`Show Navigation Areas`](https://create.roblox.com/docs/reference/engine/classes/Studio#Show Navigation Areas)
  * Remove 📘 `Disable Accurate Play Solo`
* Remove 🔷 `DataStoreKeyVersionInfo`
* Remove 🔷 `GetDataStoreOptions`
* Remove 🔷 `ObjectVersionInfo`
* Remove 🔷 `DataStoreEnumerationPages`
* Update 📑 [`ConnectionError`](https://create.roblox.com/docs/reference/engine/enums/ConnectionError)
  * Add 🏷️ `DisconnectClientFailure` (284)