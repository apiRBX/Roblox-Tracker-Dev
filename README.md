# Roblox API Tracker (Development)

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.491.0.4910402` |
| **Version Hash** | `version-5d662fcdd53448c6` |
| **Official Release Notes** | [Release Notes 491](https://create.roblox.com/docs/release-notes/release-notes-491) |

---

## API Changelog

* Update 🔷 [`AssetImportService`](https://create.roblox.com/docs/reference/engine/classes/AssetImportService)
  * Add 🔮 [`GetCurrentImportMap`](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#GetCurrentImportMap)
  * Change ReturnType of 🔮 [`ImportMesh`](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#ImportMesh) from **`AssetImportSettings`** to **`Tuple`**
  * Change ReturnType of 🔮 [`ImportMeshWithPrompt`](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#ImportMeshWithPrompt) from **`AssetImportSettings`** to **`Tuple`**
  * Remove 🔮 `GetInstanceMap`
* Update 🔷 [`AssetManagerService`](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService)
  * Add 🔮 [`InsertModel`](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertModel)
  * Add 🔮 [`RenameModel`](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RenameModel)
* Update 🔷 [`Breakpoint`](https://create.roblox.com/docs/reference/engine/classes/Breakpoint)
  * Change ValueType of 📘 [`Condition`](https://create.roblox.com/docs/reference/engine/classes/Breakpoint#Condition) from **`Expression`** to **`string`**
  * Add 📘 [`Id`](https://create.roblox.com/docs/reference/engine/classes/Breakpoint#Id)
  * Add 📘 [`LogMessage`](https://create.roblox.com/docs/reference/engine/classes/Breakpoint#LogMessage)
  * Add 📘 [`Verified`](https://create.roblox.com/docs/reference/engine/classes/Breakpoint#Verified)
  * Remove 📘 `Valid`
  * Remove 🔮 `Remove`
  * Remove 🔮 `SetCondition`
  * Remove 🔮 `SetEnabled`
  * Remove 🔮 `SetLine`
* Update 🔷 [`DebuggerConnection`](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection)
  * Change ReturnType of 🔮 [`AddBreakpoint`](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#AddBreakpoint) from **`int`** to **`void`**
  * Change Parameters of 🔮 [`AddBreakpoint`](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#AddBreakpoint)
  * Add 🔮 [`RemoveBreakpoint`](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#RemoveBreakpoint)
* Add 🔷 [`ImporterJointSettings`](https://create.roblox.com/docs/reference/engine/classes/ImporterJointSettings)
* Add 🔷 [`MessageBusConnection`](https://create.roblox.com/docs/reference/engine/classes/MessageBusConnection)
  * Add 🔮 [`Disconnect`](https://create.roblox.com/docs/reference/engine/classes/MessageBusConnection#Disconnect)
* Add 🔷 [`MessageBusService`](https://create.roblox.com/docs/reference/engine/classes/MessageBusService)
  * Add 🔮 [`Call`](https://create.roblox.com/docs/reference/engine/classes/MessageBusService#Call)
  * Add 🔮 [`GetLast`](https://create.roblox.com/docs/reference/engine/classes/MessageBusService#GetLast)
  * Add 🔮 [`GetMessageId`](https://create.roblox.com/docs/reference/engine/classes/MessageBusService#GetMessageId)
  * Add 🔮 [`Publish`](https://create.roblox.com/docs/reference/engine/classes/MessageBusService#Publish)
  * Add 🔮 [`Subscribe`](https://create.roblox.com/docs/reference/engine/classes/MessageBusService#Subscribe)
* Update 🔷 [`Workspace`](https://create.roblox.com/docs/reference/engine/classes/Workspace)
  * Add 📘 [`StreamOutBehavior`](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamOutBehavior)
* Update 🔷 [`Path`](https://create.roblox.com/docs/reference/engine/classes/Path)
  * Add ⚡ [`Unblocked`](https://create.roblox.com/docs/reference/engine/classes/Path#Unblocked)
* Update 🔷 [`PolicyService`](https://create.roblox.com/docs/reference/engine/classes/PolicyService)
  * Add 🔮 [`GetPolicyInfoForServerRobloxOnlyAsync`](https://create.roblox.com/docs/reference/engine/classes/PolicyService#GetPolicyInfoForServerRobloxOnlyAsync)
* Update 🔷 [`Sound`](https://create.roblox.com/docs/reference/engine/classes/Sound)
  * Add 📘 [`ChannelCount`](https://create.roblox.com/docs/reference/engine/classes/Sound#ChannelCount)
* Update 🔷 [`Speaker`](https://create.roblox.com/docs/reference/engine/classes/Speaker)
  * Add 📘 [`ChannelCount`](https://create.roblox.com/docs/reference/engine/classes/Speaker#ChannelCount)
* Update 🔷 [`VirtualInputManager`](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager)
  * Remove 🔮 `SetViewportSize`
* Remove 🔷 `AssetImportItemSettings`
* Remove 🔷 `AssetImportMeshSettings`
* Remove 🔷 `AssetImportTextureSettings`
* Remove 🔷 `AssetImportSettings`
* Remove 🔷 `Expression`
* Add 📑 [`StreamOutBehavior`](https://create.roblox.com/docs/reference/engine/enums/StreamOutBehavior)
  * Add 🏷️ `Default` (0)
  * Add 🏷️ `LowMemory` (1)
  * Add 🏷️ `Opportunistic` (2)
