# Roblox API Tracker (Development)

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.493.0.4930373` |
| **Version Hash** | `version-04c0166b90104f00` |
| **Official Release Notes** | [Release Notes 493](https://create.roblox.com/docs/release-notes/release-notes-493) |

---

## API Changelog

* Update Class [Instance](https://create.roblox.com/docs/reference/engine/classes/Instance) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Add Property [ClassName](https://create.roblox.com/docs/reference/engine/classes/Instance#ClassName): string [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [className](https://create.roblox.com/docs/reference/engine/classes/Instance#className): string [🏷️ ReadOnly] [🏷️ NotReplicated] [🏷️ Deprecated]
  * Changed the return-type of Function [ClearAllChildren](https://create.roblox.com/docs/reference/engine/classes/Instance#ClearAllChildren) from null to void
  * Changed the return-type of Function [Destroy](https://create.roblox.com/docs/reference/engine/classes/Instance#Destroy) from null to void
  * Changed the return-type of Function [GetChildren](https://create.roblox.com/docs/reference/engine/classes/Instance#GetChildren) from Instances to Objects
  * Changed the return-type of Function [GetDescendants](https://create.roblox.com/docs/reference/engine/classes/Instance#GetDescendants) from Instances to Array [🏷️ CustomLuaState]
  * Add Function [GetPropertyChangedSignal](https://create.roblox.com/docs/reference/engine/classes/Instance#GetPropertyChangedSignal) (property: string) -> RBXScriptSignal
  * Add Function [IsA](https://create.roblox.com/docs/reference/engine/classes/Instance#IsA) (className: string) -> bool [🏷️ CustomLuaState]
  * Changed the return-type of Function [Remove](https://create.roblox.com/docs/reference/engine/classes/Instance#Remove) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetAttribute](https://create.roblox.com/docs/reference/engine/classes/Instance#SetAttribute) from null to void
  * Changed the return-type of Function [children](https://create.roblox.com/docs/reference/engine/classes/Instance#children) from Instances to Objects [🏷️ Deprecated]
  * Changed the return-type of Function [destroy](https://create.roblox.com/docs/reference/engine/classes/Instance#destroy) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [getChildren](https://create.roblox.com/docs/reference/engine/classes/Instance#getChildren) from Instances to Objects [🏷️ Deprecated]
  * Add Function [isA](https://create.roblox.com/docs/reference/engine/classes/Instance#isA) (className: string) -> bool [🏷️ Deprecated] [🏷️ CustomLuaState]
  * Changed the return-type of Function [remove](https://create.roblox.com/docs/reference/engine/classes/Instance#remove) from null to void [🏷️ Deprecated]
  * Add Event [Changed](https://create.roblox.com/docs/reference/engine/classes/Instance#Changed)
  * Removed Property Capabilities
  * Removed Property IsInSandbox
  * Removed Property PredictionMode
  * Removed Property Sandboxed
  * Removed Property UniqueId
  * Removed Function AddTag
  * Removed Function GetStyled
  * Removed Function GetStyledPropertyChangedSignal
  * Removed Function GetTags
  * Removed Function HasTag
  * Removed Function IsPropertyModified
  * Removed Function QueryDescendants
  * Removed Function RemoveTag
  * Removed Function ResetPropertyToDefault
  * Removed Event Destroying
  * Removed Event StyledPropertiesChanged
* Add Class [ABTestService](https://create.roblox.com/docs/reference/engine/classes/ABTestService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Function [ClearUserVariations](https://create.roblox.com/docs/reference/engine/classes/ABTestService#ClearUserVariations) () -> void [🔒 LocalUserSecurity]
  * Add Function [GetBrowserTrackerABTestLoadingStatus](https://create.roblox.com/docs/reference/engine/classes/ABTestService#GetBrowserTrackerABTestLoadingStatus) () -> ABTestLoadingStatus [🔒 LocalUserSecurity]
  * Add Function [GetPendingOrInitializedUserId](https://create.roblox.com/docs/reference/engine/classes/ABTestService#GetPendingOrInitializedUserId) () -> int64 [🔒 LocalUserSecurity]
  * Add Function [GetUserABTestLoadingStatus](https://create.roblox.com/docs/reference/engine/classes/ABTestService#GetUserABTestLoadingStatus) () -> ABTestLoadingStatus [🔒 LocalUserSecurity]
  * Add Function [GetVariant](https://create.roblox.com/docs/reference/engine/classes/ABTestService#GetVariant) (name: string) -> string [🔒 LocalUserSecurity]
  * Add Function [InitializeForUserId](https://create.roblox.com/docs/reference/engine/classes/ABTestService#InitializeForUserId) (userId: int64) -> void [🔒 LocalUserSecurity]
  * Add Function [WaitUntilBrowserTrackerABTestsInitialized](https://create.roblox.com/docs/reference/engine/classes/ABTestService#WaitUntilBrowserTrackerABTestsInitialized) () -> void [🔒 LocalUserSecurity] [🏷️ Yields]
  * Add Function [WaitUntilUserABTestsInitialized](https://create.roblox.com/docs/reference/engine/classes/ABTestService#WaitUntilUserABTestsInitialized) () -> void [🔒 LocalUserSecurity] [🏷️ Yields]
  * Add Event [OnBrowserTrackerABTestLoadingStatusChanged](https://create.roblox.com/docs/reference/engine/classes/ABTestService#OnBrowserTrackerABTestLoadingStatusChanged) [🔒 LocalUserSecurity]
  * Add Event [OnUserABTestLoadingStatusChanged](https://create.roblox.com/docs/reference/engine/classes/ABTestService#OnUserABTestLoadingStatusChanged) [🔒 LocalUserSecurity]
* Update Class [AdService](https://create.roblox.com/docs/reference/engine/classes/AdService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [ShowVideoAd](https://create.roblox.com/docs/reference/engine/classes/AdService#ShowVideoAd) from null to void [🏷️ Deprecated]
  * Removed Function CreateAdRewardFromDevProductId
  * Removed Function GetAdTeleportInfo
  * Removed Function GetReportAdInfo
  * Removed Function GetUniversalAppAdsEligibility
  * Removed Function HandleWhyThisAdClicked
  * Removed Function HideEudsaDisclosure
  * Removed Function IsAdLoaded
  * Removed Function OnDemandVideoCompleteFromUI
  * Removed Function RegisterDisclosureButton
  * Removed Function ReturnToPublisherExperience
  * Removed Function SetAdGuiInteractivityHandlerInitialized
  * Removed Function SubmitAdNotification
  * Removed Function UnregisterAdOpportunity
  * Removed Function GetAdAvailabilityNowAsync
  * Removed Function GetAdAvailabilityNowForUniverseAsync
  * Removed Function GetCampaignEligibilityAsync
  * Removed Function RegisterAdOpportunityAsync
  * Removed Function ShowRewardedVideoAdAsync
  * Removed Function ShowRewardedVideoAdAtClientAsync
  * Removed Event AdTeleportEnded
  * Removed Event AdTeleportInitiated
  * Removed Event RewardedVideoAdEnded
  * Removed Event RewardedVideoAdStarted
  * Removed Event ShowDynamicEudsaDisclosure
  * Removed Event ShowReportAdPopup
  * Removed Event adGuiRegisterUI
  * Removed Callback OnImmersiveBrandedAdDisclosureButtonActivated
  * Removed Callback onDemandVideoPlayInUI
* Update Class [AnalyticsService](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService) [🏷️ Service]
  * Changed the return-type of Function [FireCustomEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireCustomEvent) from null to void
  * Changed the return-type of Function [FireEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireEvent) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [FireInGameEconomyEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireInGameEconomyEvent) from null to void
  * Changed the return-type of Function [FireLogEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireLogEvent) from null to void
  * Changed the return-type of Function [FirePlayerProgressionEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FirePlayerProgressionEvent) from null to void
  * Removed Function GetDurationLoggerTimestamp
  * Removed Function LogCustomEvent
  * Removed Function LogEconomyEvent
  * Removed Function LogFunnelStepEvent
  * Removed Function LogJourneyEvent
  * Removed Function LogOnboardingFunnelStepEvent
  * Removed Function LogProgressionCompleteEvent
  * Removed Function LogProgressionEvent
  * Removed Function LogProgressionFailEvent
  * Removed Function LogProgressionStartEvent
  * Removed Function GetPlayerSegmentsAsync
* Update Class [Animation](https://create.roblox.com/docs/reference/engine/classes/Animation)
  * Changed the ValueType of Property [AnimationId](https://create.roblox.com/docs/reference/engine/classes/Animation#AnimationId) from ContentId to Content
  * Removed Property AnimationContent
* Update Class [AnimationTrack](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack) [🏷️ NotCreatable]
  * Changed the return-type of Function [AdjustSpeed](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#AdjustSpeed) from null to void
  * Changed the return-type of Function [AdjustWeight](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#AdjustWeight) from null to void
  * Changed the return-type of Function [Play](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Play) from null to void
  * Changed the return-type of Function [Stop](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Stop) from null to void
  * Removed Function GetDebugData
  * Removed Function GetParameter
  * Removed Function GetParameterDefaults
  * Removed Function GetTargetInstance
  * Removed Function GetTargetNames
  * Removed Function ResetGraph
  * Removed Function SetParameter
  * Removed Function SetTargetInstance
  * Removed Function UpdateGraphNodeProperty
  * Removed Event Ended
  * Removed Event ParameterChanged
* Update Class [Animator](https://create.roblox.com/docs/reference/engine/classes/Animator)
  * Changed the return-type of Function [ApplyJointVelocities](https://create.roblox.com/docs/reference/engine/classes/Animator#ApplyJointVelocities) from null to void
  * Changed the return-type of Function [StepAnimations](https://create.roblox.com/docs/reference/engine/classes/Animator#StepAnimations) from null to void [🔒 PluginSecurity]
  * Removed Property EvaluationThrottled
  * Removed Property PreferLodEnabled
  * Removed Property RootMotion
  * Removed Property RootMotionWeight
  * Removed Function GetPlayingAnimationTracksCoreScript
  * Removed Function GetTrackByAnimationId
  * Removed Function LoadAnimationCoreScript
  * Removed Function LoadStreamAnimation
  * Removed Function LoadStreamAnimationForSelfieView_deprecated
  * Removed Function LoadStreamAnimationV2
  * Removed Function RegisterEvaluationParallelCallback
  * Removed Function StepAnimationsInternal
  * Removed Function SynchronizeWith
  * Removed Event AnimationPlayedCoreScript
  * Removed Event AnimationStreamTrackPlayed
* Update Class [AppUpdateService](https://create.roblox.com/docs/reference/engine/classes/AppUpdateService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [CheckForUpdate](https://create.roblox.com/docs/reference/engine/classes/AppUpdateService#CheckForUpdate) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [DisableDUAR](https://create.roblox.com/docs/reference/engine/classes/AppUpdateService#DisableDUAR) () -> void [🔒 RobloxScriptSecurity]
  * Add Function [DisableDUARAndOpenSurvey](https://create.roblox.com/docs/reference/engine/classes/AppUpdateService#DisableDUARAndOpenSurvey) (surveyUrl: string) -> void [🔒 RobloxScriptSecurity]
  * Removed Function CanPerformBinaryUpdate
  * Removed Function GetProtocolLaunchUpdateName
  * Removed Function GetProtocolLaunchUpdateType
* Update Class [AssetDeliveryProxy](https://create.roblox.com/docs/reference/engine/classes/AssetDeliveryProxy) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property Interface
  * Removed Property Port
  * Removed Property StartServer
* Update Class [AssetImportService](https://create.roblox.com/docs/reference/engine/classes/AssetImportService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Function [GetCurrentImportMap](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#GetCurrentImportMap) () -> Dictionary [🔒 RobloxScriptSecurity]
  * Add Function [ImportMesh](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#ImportMesh) (fileName: string) -> Tuple [🔒 RobloxScriptSecurity]
  * Add Function [UploadCurrentMesh](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#UploadCurrentMesh) () -> void [🔒 RobloxScriptSecurity]
  * Add Function [ImportMeshWithPrompt](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#ImportMeshWithPrompt) () -> Tuple [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Removed Function GetAllPresets
  * Removed Function GetPreset
  * Removed Function RemovePreset
  * Removed Function SavePreset
  * Removed Function StartSessionWithPath
  * Removed Function StartSingleFileWatch
  * Removed Function StopSingleFileWatch
  * Removed Function GetFilesInDirAsync
  * Removed Function PickFileWithPromptAsync
  * Removed Function PickImageFileWithPrompt
  * Removed Function PickMeshFileWithPrompt
  * Removed Function PickMultipleFilesWithPrompt
  * Removed Function StartSessionWithPathAsync
  * Removed Function UploadAssetFromContentAsync
  * Removed Function UploadAssetFromPathAsync
  * Removed Function UploadVersionedAssetFromContentAsync
  * Removed Function UploadVersionedAssetFromPathAsync
  * Removed Event SingleFileChanged
  * Removed Event StartSingleMeshImport
* Update Class [AssetManagerService](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Function [GetMeshId](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#GetMeshId) (aliasName: string) -> int64 [🔒 RobloxScriptSecurity]
  * Add Function [GetTextureId](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#GetTextureId) (aliasName: string) -> int64 [🔒 RobloxScriptSecurity]
  * Add Function [HasUnpublishedChangesForLinkedSource](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#HasUnpublishedChangesForLinkedSource) (aliasName: string) -> bool [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [InsertAudio](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertAudio) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [InsertImage](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertImage) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [InsertLinkedSourceAsLocalScript](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertLinkedSourceAsLocalScript) (aliasName: string) -> void [🔒 RobloxScriptSecurity]
  * Add Function [InsertLinkedSourceAsModuleScript](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertLinkedSourceAsModuleScript) (aliasName: string) -> void [🔒 RobloxScriptSecurity]
  * Add Function [InsertLinkedSourceAsScript](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertLinkedSourceAsScript) (aliasName: string) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [InsertMesh](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertMesh) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [InsertMesh](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertMesh)
    from: (aliasName: string, insertWithLocation: bool, sourceAssetId: int64)
    to: (aliasName: string, insertWithLocation: bool) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [InsertMeshesWithLocation](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertMeshesWithLocation) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [InsertMeshesWithLocation](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertMeshesWithLocation)
    from: (aliasNames: Array, meshIds: Array)
    to: (aliasNames: Array) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [InsertModel](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertModel) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [InsertPackage](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertPackage) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [OpenLinkedSource](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#OpenLinkedSource) (aliasName: string) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [OpenPlace](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#OpenPlace) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [RefreshLinkedSource](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RefreshLinkedSource) (aliasName: string) -> void [🔒 RobloxScriptSecurity]
  * Add Function [RevertLinkedSourceToLastPublishedVersion](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RevertLinkedSourceToLastPublishedVersion) (aliasName: string) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ShowPackageDetails](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#ShowPackageDetails) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [UpdateAllPackages](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#UpdateAllPackages) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ViewPackageOnWebsite](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#ViewPackageOnWebsite) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [DeleteAlias](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#DeleteAlias) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Add Function [PublishLinkedSource](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#PublishLinkedSource) (assetId: int64, aliasName: string) -> void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [RemovePlace](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RemovePlace) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [RenameAlias](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RenameAlias) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [RenameModel](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RenameModel) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [RenamePlace](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RenamePlace) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Add Event [MayBeLinkedSourceModified](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#MayBeLinkedSourceModified) [🔒 RobloxScriptSecurity]
  * Removed Function GetMeshIdFromAliasName
  * Removed Function GetMeshIdFromAssetId
  * Removed Function GetTextureIdFromAliasName
  * Removed Function GetTextureIdFromAssetId
  * Removed Function InsertImages
  * Removed Function InsertVideo
  * Removed Function CreateAlias
  * Removed Event AssetImportedSignal
  * Removed Event ImportSessionFinished
  * Removed Event ImportSessionStarted
* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [🏷️ NotCreatable] [🏷️ Service]
  * Add Function [GetBundleDetailsSync](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetBundleDetailsSync) (bundleId: int64) -> Dictionary [🔒 RobloxScriptSecurity]
  * Add Function [GetAssetThumbnailAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetAssetThumbnailAsync) (assetId: int64, thumbnailSize: Vector2, assetType: int = 0) -> Tuple [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [SavePlaceAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#SavePlaceAsync) from null to void [🏷️ Yields]
  * Changed the parameters of Function [SavePlaceAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#SavePlaceAsync)
    from: (requestParameters: Dictionary?)
    to: () [🏷️ Yields]
  * Removed Property AllowInsertFreeAssets
  * Removed Function CreateEditableImage
  * Removed Function CreateEditableMesh
  * Removed Function DeserializeInstance
  * Removed Function GetOpaqueContentMetadataMap
  * Removed Function CachePartOperationsAsync
  * Removed Function CanEditAssetAsync
  * Removed Function ComposeDecalAsync
  * Removed Function CreateAssetAsync
  * Removed Function CreateAssetVersionAsync
  * Removed Function CreateDataModelContentAsync
  * Removed Function CreateEditableImageAsync
  * Removed Function CreateEditableImageFromDownloadAsync
  * Removed Function CreateEditableMeshAsync
  * Removed Function CreateMeshPartAsync
  * Removed Function CreateSurfaceAppearanceAsync
  * Removed Function GetAssetIdsForPackageAsync
  * Removed Function GetAudioMetadataAsync
  * Removed Function LoadAssetAsync
  * Removed Function PromptCreateAssetAsync
  * Removed Function PromptImportAnimationClipFromVideoAsync
  * Removed Function SearchAudio
  * Removed Function SearchAudioAsync
  * Removed Event AudioMetadataFailedResponse
  * Removed Event AudioMetadataRequest
  * Removed Event AudioMetadataResponse
  * Removed Event OpenCreateResultModal
  * Removed Event OpenPublishResultModal
* Update Class [Attachment](https://create.roblox.com/docs/reference/engine/classes/Attachment)
  * Changed the return-type of Function [SetAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SetAxis) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetSecondaryAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SetSecondaryAxis) from null to void [🏷️ Deprecated]
  * Removed Function GetConstraints
* Update Class [Bone](https://create.roblox.com/docs/reference/engine/classes/Bone)
  * Add Property [IsCFrameDriven](https://create.roblox.com/docs/reference/engine/classes/Bone#IsCFrameDriven): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated]
* Update Class [AvatarEditorService](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [NoPromptCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#NoPromptCreateOutfit)
    from: (humanoidDescription: HumanoidDescription, rigType: HumanoidRigType, name: string, gearAssetId: int64 = 0, outfitOptions: Dictionary = nil, outfitType: Variant)
    to: (humanoidDescription: HumanoidDescription, rigType: HumanoidRigType, name: string) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [NoPromptSaveAvatar](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#NoPromptSaveAvatar)
    from: (humanoidDescription: HumanoidDescription, rigType: HumanoidRigType, saveDict: Dictionary, gearAssetId: int64 = 0, profileConfiguration: Dictionary = nil)
    to: (humanoidDescription: HumanoidDescription, rigType: HumanoidRigType, saveDict: Dictionary, gearAssetId: int64 = 0) [🔒 RobloxScriptSecurity]
  * Add Function [PerformCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformCreateOutfit) (name: string) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PerformCreateOutfitWithDescription](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformCreateOutfitWithDescription) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [PerformCreateOutfitWithDescription](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformCreateOutfitWithDescription)
    from: (humanoidDescription: HumanoidDescription, name: string, profileConfiguration: Dictionary = nil)
    to: (humanoidDescription: HumanoidDescription, name: string) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PerformDeleteOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformDeleteOutfit) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [PerformSaveAvatar](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformSaveAvatar) () -> void [🔒 RobloxScriptSecurity]
  * Add Function [PerformSaveAvatarNew](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformSaveAvatarNew) (addedAssets: Array, removedAssets: Array) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PerformSaveAvatarWithDescription](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformSaveAvatarWithDescription) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PerformSetFavorite](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformSetFavorite) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PromptAllowInventoryReadAccess](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptAllowInventoryReadAccess) from null to void
  * Changed the return-type of Function [PromptCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptCreateOutfit) from null to void
  * Changed the parameters of Function [PromptCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptCreateOutfit)
    from: (outfit: HumanoidDescription, rigType: HumanoidRigType, outfitOptions: Dictionary = nil, outfitType: Variant)
    to: (outfit: HumanoidDescription, rigType: HumanoidRigType)
  * Changed the return-type of Function [PromptDeleteOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptDeleteOutfit) from null to void
  * Changed the return-type of Function [PromptSaveAvatar](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptSaveAvatar) from null to void
  * Changed the return-type of Function [PromptSetFavorite](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptSetFavorite) from null to void
  * Changed the return-type of Function [SetAllowInventoryReadAccess](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SetAllowInventoryReadAccess) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalCreateOutfitFailed](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalCreateOutfitFailed) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalCreateOutfitPermissionDenied](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalCreateOutfitPermissionDenied) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalDeleteOutfitFailed](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalDeleteOutfitFailed) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalDeleteOutfitPermissionDenied](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalDeleteOutfitPermissionDenied) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalSaveAvatarFailed](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalSaveAvatarFailed) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalSaveAvatarPermissionDenied](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalSaveAvatarPermissionDenied) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalSetFavoriteFailed](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalSetFavoriteFailed) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalSetFavoritePermissionDenied](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalSetFavoritePermissionDenied) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [GetOutfits](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetOutfits)
    from: (outfitSource: OutfitSource = All, outfitType: OutfitType = All)
    to: (outfitSource: OutfitSource = All) [🏷️ Yields]
  * Removed Function BustAvatarFetchCache
  * Removed Function GetAccessoryType
  * Removed Function NoPromptApplyProfileConfiguration
  * Removed Function NoPromptRenameOutfit
  * Removed Function NoPromptSaveAvatarThumbnailCustomization
  * Removed Function NoPromptUpdateOutfit
  * Removed Function PerformRenameOutfit
  * Removed Function PerformUpdateOutfit
  * Removed Function PromptRenameOutfit
  * Removed Function PromptUpdateOutfit
  * Removed Function SignalRenameOutfitFailed
  * Removed Function SignalRenameOutfitPermissionDenied
  * Removed Function SignalUpdateOutfitFailed
  * Removed Function SignalUpdateOutfitPermissionDenied
  * Removed Function refreshAvatarThumbnails
  * Removed Function CheckApplyDefaultClothingAsync
  * Removed Function ConformToAvatarRulesAsync
  * Removed Function GetAvatarRulesAsync
  * Removed Function GetBatchItemDetailsAsync
  * Removed Function GetBundlesByAssetIdAsync
  * Removed Function GetFavoriteAsync
  * Removed Function GetHeadShapesAsync
  * Removed Function GetInventoryAsync
  * Removed Function GetItemDetailsAsync
  * Removed Function GetOutfitDetails
  * Removed Function GetOutfitDetailsAsync
  * Removed Function GetOutfitsAsync
  * Removed Function GetRecommendedAssetsAsync
  * Removed Function GetRecommendedBundlesAsync
  * Removed Function SearchCatalogAsync
  * Removed Event OpenPromptRenameOutfit
  * Removed Event OpenPromptUpdateOutfit
  * Removed Event PromptApplyProfileConfigurationCompleted
  * Removed Event PromptRenameOutfitCompleted
  * Removed Event PromptSaveAvatarThumbnailCustomizationCompleted
  * Removed Event PromptUpdateOutfitCompleted
* Update Class [AvatarImportService](https://create.roblox.com/docs/reference/engine/classes/AvatarImportService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function ImportFBXAnimationFromFilePathUserMayChooseModel
* Update Class [BackpackItem](https://create.roblox.com/docs/reference/engine/classes/BackpackItem) [🏷️ NotCreatable]
  * Changed the ValueType of Property [TextureId](https://create.roblox.com/docs/reference/engine/classes/BackpackItem#TextureId) from ContentId to Content
  * Removed Property TextureContent
* Update Class [HopperBin](https://create.roblox.com/docs/reference/engine/classes/HopperBin) [🏷️ Deprecated]
  * Changed the return-type of Function [Disable](https://create.roblox.com/docs/reference/engine/classes/HopperBin#Disable) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ToggleSelect](https://create.roblox.com/docs/reference/engine/classes/HopperBin#ToggleSelect) from null to void [🔒 RobloxScriptSecurity]
* Update Class [Tool](https://create.roblox.com/docs/reference/engine/classes/Tool)
  * Changed the return-type of Function [Activate](https://create.roblox.com/docs/reference/engine/classes/Tool#Activate) from null to void
  * Changed the return-type of Function [Deactivate](https://create.roblox.com/docs/reference/engine/classes/Tool#Deactivate) from null to void
* Update Class [BadgeService](https://create.roblox.com/docs/reference/engine/classes/BadgeService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the parameters of Function [AwardBadge](https://create.roblox.com/docs/reference/engine/classes/BadgeService#AwardBadge)
    from: (userId: User, badgeId: int64)
    to: (userId: int64, badgeId: int64) [🏷️ Yields]
  * Changed the parameters of Function [UserHasBadge](https://create.roblox.com/docs/reference/engine/classes/BadgeService#UserHasBadge)
    from: (userId: User, badgeId: int64)
    to: (userId: int64, badgeId: int64) [🏷️ Yields] [🏷️ Deprecated]
  * Changed the parameters of Function [UserHasBadgeAsync](https://create.roblox.com/docs/reference/engine/classes/BadgeService#UserHasBadgeAsync)
    from: (userId: User, badgeId: int64)
    to: (userId: int64, badgeId: int64) [🏷️ Yields]
  * Removed Function AwardBadgeAsync
  * Removed Function CheckUserBadgesAsync
  * Removed Function GetUserBadgesAsync
* Update Class [BasePlayerGui](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui) [🏷️ NotCreatable]
  * Changed the return-type of Function [GetGuiObjectsAtPosition](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui#GetGuiObjectsAtPosition) from Instances to Objects
  * Changed the return-type of Function [GetGuiObjectsInCircle](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui#GetGuiObjectsInCircle) from Instances to Objects [🔒 RobloxScriptSecurity]
* Update Class [CoreGui](https://create.roblox.com/docs/reference/engine/classes/CoreGui) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [SetUserGuiRendering](https://create.roblox.com/docs/reference/engine/classes/CoreGui#SetUserGuiRendering) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [SetUserGuiRendering](https://create.roblox.com/docs/reference/engine/classes/CoreGui#SetUserGuiRendering)
    from: (enabled: bool, guiAdornee: Instance, faceId: NormalId, horizontalCurvature: float = 0)
    to: (enabled: bool, guiAdornee: Instance, faceId: NormalId) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [TakeScreenshot](https://create.roblox.com/docs/reference/engine/classes/CoreGui#TakeScreenshot) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ToggleRecording](https://create.roblox.com/docs/reference/engine/classes/CoreGui#ToggleRecording) from null to void [🔒 RobloxScriptSecurity]
  * Removed Event UserGuiRenderingChanged
* Update Class [PlayerGui](https://create.roblox.com/docs/reference/engine/classes/PlayerGui) [🏷️ NotCreatable] [🏷️ PlayerReplicated]
  * Changed the return-type of Function [SetTopbarTransparency](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#SetTopbarTransparency) from null to void [🏷️ Deprecated]
* Update Class [StarterGui](https://create.roblox.com/docs/reference/engine/classes/StarterGui) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [RegisterGetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#RegisterGetCore) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RegisterSetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#RegisterSetCore) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#SetCore) from null to void
  * Changed the return-type of Function [SetCoreGuiEnabled](https://create.roblox.com/docs/reference/engine/classes/StarterGui#SetCoreGuiEnabled) from null to void
  * Removed Property ClipsDescendantsSupportsRotation
  * Removed Property RtlTextSupport
  * Removed Property StudioDefaultStyleSheet
  * Removed Property StudioInsertWidgetLayerCollectorAutoLinkStyleSheet
* Update Class [BaseWrap](https://create.roblox.com/docs/reference/engine/classes/BaseWrap) [🏷️ NotCreatable]
  * Changed the ValueType of Property [CageMeshId](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageMeshId) from ContentId to Content [🔒 Read:None, Write:PluginSecurity]
  * Changed the return-type of Function [ModifyVertices](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#ModifyVertices) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property CageMeshContent
  * Removed Property HSRAssetId
  * Removed Property HSRContent
  * Removed Function GetCageOffset
  * Removed Function GetUVs
  * Removed Function IsHSRReady
  * Removed Event VerticesModified
* Update Class [WrapLayer](https://create.roblox.com/docs/reference/engine/classes/WrapLayer)
  * Changed the ValueType of Property [ReferenceMeshId](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceMeshId) from ContentId to Content [🔒 Read:None, Write:PluginSecurity]
  * Removed Property AutoSkin
  * Removed Property MaxSize
  * Removed Property Offset
  * Removed Property ReferenceMeshContent
* Update Class [Beam](https://create.roblox.com/docs/reference/engine/classes/Beam)
  * Changed the ValueType of Property [Texture](https://create.roblox.com/docs/reference/engine/classes/Beam#Texture) from ContentId to Content
  * Changed the return-type of Function [SetTextureOffset](https://create.roblox.com/docs/reference/engine/classes/Beam#SetTextureOffset) from null to void
  * Removed Property Brightness
  * Removed Property LocalTransparencyModifier
  * Removed Property TextureContent
* Update Class [BindableEvent](https://create.roblox.com/docs/reference/engine/classes/BindableEvent)
  * Changed the return-type of Function [Fire](https://create.roblox.com/docs/reference/engine/classes/BindableEvent#Fire) from null to void
* Update Class [RocketPropulsion](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion)
  * Changed the return-type of Function [Abort](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#Abort) from null to void
  * Changed the return-type of Function [Fire](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#Fire) from null to void
  * Changed the return-type of Function [fire](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#fire) from null to void [🏷️ Deprecated]
* Update Class [Breakpoint](https://create.roblox.com/docs/reference/engine/classes/Breakpoint) [🏷️ NotReplicated]
  * Changed the ValueType of Property [Script](https://create.roblox.com/docs/reference/engine/classes/Breakpoint#Script) from string to ScriptRef [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Removed Property ContinueExecution
  * Removed Property MetaBreakpointId
  * Removed Property RemoveOnHit
  * Removed Property Valid
* Update Class [BrowserService](https://create.roblox.com/docs/reference/engine/classes/BrowserService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [CloseBrowserWindow](https://create.roblox.com/docs/reference/engine/classes/BrowserService#CloseBrowserWindow) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [CopyAuthCookieFromBrowserToEngine](https://create.roblox.com/docs/reference/engine/classes/BrowserService#CopyAuthCookieFromBrowserToEngine) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [EmitHybridEvent](https://create.roblox.com/docs/reference/engine/classes/BrowserService#EmitHybridEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ExecuteJavaScript](https://create.roblox.com/docs/reference/engine/classes/BrowserService#ExecuteJavaScript) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [OpenBrowserWindow](https://create.roblox.com/docs/reference/engine/classes/BrowserService#OpenBrowserWindow) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [OpenNativeOverlay](https://create.roblox.com/docs/reference/engine/classes/BrowserService#OpenNativeOverlay) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [OpenWeChatAuthWindow](https://create.roblox.com/docs/reference/engine/classes/BrowserService#OpenWeChatAuthWindow) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ReturnToJavaScript](https://create.roblox.com/docs/reference/engine/classes/BrowserService#ReturnToJavaScript) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendCommand](https://create.roblox.com/docs/reference/engine/classes/BrowserService#SendCommand) from null to void [🔒 RobloxScriptSecurity]
* Update Class [BulkImportService](https://create.roblox.com/docs/reference/engine/classes/BulkImportService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [LaunchBulkImport](https://create.roblox.com/docs/reference/engine/classes/BulkImportService#LaunchBulkImport) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ShowBulkImportView](https://create.roblox.com/docs/reference/engine/classes/BulkImportService#ShowBulkImportView) from null to void [🔒 RobloxScriptSecurity]
* Update Class [CalloutService](https://create.roblox.com/docs/reference/engine/classes/CalloutService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [AttachCallout](https://create.roblox.com/docs/reference/engine/classes/CalloutService#AttachCallout) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [DefineCallout](https://create.roblox.com/docs/reference/engine/classes/CalloutService#DefineCallout) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [DetachCalloutsByDefinitionId](https://create.roblox.com/docs/reference/engine/classes/CalloutService#DetachCalloutsByDefinitionId) from null to void [🔒 RobloxScriptSecurity]
* Update Class [Camera](https://create.roblox.com/docs/reference/engine/classes/Camera) [🏷️ NotReplicated]
  * Changed the parameters of Function [GetLargestCutoffDistance](https://create.roblox.com/docs/reference/engine/classes/Camera#GetLargestCutoffDistance)
    from: (ignoreList: Instances)
    to: (ignoreList: Objects) [🏷️ Deprecated]
  * Changed the return-type of Function [GetPartsObscuringTarget](https://create.roblox.com/docs/reference/engine/classes/Camera#GetPartsObscuringTarget) from Instances to Objects
  * Changed the parameters of Function [GetPartsObscuringTarget](https://create.roblox.com/docs/reference/engine/classes/Camera#GetPartsObscuringTarget)
    from: (castPoints: Array, ignoreList: Instances)
    to: (castPoints: Array, ignoreList: Objects)
  * Changed the return-type of Function [Interpolate](https://create.roblox.com/docs/reference/engine/classes/Camera#Interpolate) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [PanUnits](https://create.roblox.com/docs/reference/engine/classes/Camera#PanUnits) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetCameraPanMode](https://create.roblox.com/docs/reference/engine/classes/Camera#SetCameraPanMode) from null to void
  * Changed the return-type of Function [SetImageServerView](https://create.roblox.com/docs/reference/engine/classes/Camera#SetImageServerView) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetRoll](https://create.roblox.com/docs/reference/engine/classes/Camera#SetRoll) from null to void
  * Removed Property VRTiltAndRollEnabled
  * Removed Function ZoomToExtents
* Update Class [ChangeHistoryService](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [Redo](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#Redo) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [ResetWaypoints](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#ResetWaypoints) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [SetEnabled](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#SetEnabled) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [SetWaypoint](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#SetWaypoint) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [Undo](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#Undo) from null to void [🔒 PluginSecurity]
  * Removed Function FinishRecording
  * Removed Function IsRecordingInProgress
  * Removed Function TryBeginRecording
  * Removed Event OnRecordingFinished
  * Removed Event OnRecordingStarted
* Update Class [CharacterMesh](https://create.roblox.com/docs/reference/engine/classes/CharacterMesh)
  * Removed Property BaseTextureContent
  * Removed Property MeshContent
  * Removed Property OverlayTextureContent
* Update Class [Pants](https://create.roblox.com/docs/reference/engine/classes/Pants)
  * Changed the ValueType of Property [PantsTemplate](https://create.roblox.com/docs/reference/engine/classes/Pants#PantsTemplate) from ContentId to Content
  * Removed Property PantsTemplateContent
* Update Class [Shirt](https://create.roblox.com/docs/reference/engine/classes/Shirt)
  * Changed the ValueType of Property [ShirtTemplate](https://create.roblox.com/docs/reference/engine/classes/Shirt#ShirtTemplate) from ContentId to Content
  * Removed Property ShirtTemplateContent
* Update Class [ShirtGraphic](https://create.roblox.com/docs/reference/engine/classes/ShirtGraphic)
  * Changed the ValueType of Property [Graphic](https://create.roblox.com/docs/reference/engine/classes/ShirtGraphic#Graphic) from ContentId to Content
  * Removed Property TextureContent
* Update Class [Chat](https://create.roblox.com/docs/reference/engine/classes/Chat) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [Chat](https://create.roblox.com/docs/reference/engine/classes/Chat#Chat) from null to void
  * Changed the return-type of Function [ChatLocal](https://create.roblox.com/docs/reference/engine/classes/Chat#ChatLocal) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RegisterChatCallback](https://create.roblox.com/docs/reference/engine/classes/Chat#RegisterChatCallback) from null to void
  * Changed the return-type of Function [SetBubbleChatSettings](https://create.roblox.com/docs/reference/engine/classes/Chat#SetBubbleChatSettings) from null to void
  * Removed Property IsAutoMigrated
  * Removed Property ModerationMode
  * Removed Function ReconcileCommunicationAccess
  * Removed Function RequestModerationModeEnabled
  * Removed Event PlayerChatAvailabilityStatusChanged
  * Removed Event ReconcileCommunicationAccessCompleted
  * Removed Event TimeoutChatAttempt
* Update Class [ClickDetector](https://create.roblox.com/docs/reference/engine/classes/ClickDetector)
  * Changed the ValueType of Property [CursorIcon](https://create.roblox.com/docs/reference/engine/classes/ClickDetector#CursorIcon) from ContentId to Content
  * Removed Property CursorIconContent
* Update Class [CollectionService](https://create.roblox.com/docs/reference/engine/classes/CollectionService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [AddTag](https://create.roblox.com/docs/reference/engine/classes/CollectionService#AddTag) from null to void
  * Changed the return-type of Function [GetCollection](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetCollection) from Instances to Objects [🏷️ Deprecated]
  * Changed the return-type of Function [GetTagged](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetTagged) from Instances to Objects
  * Changed the return-type of Function [RemoveTag](https://create.roblox.com/docs/reference/engine/classes/CollectionService#RemoveTag) from null to void
  * Removed Function GetAllTags
  * Removed Function GetTagAddedSignal
  * Removed Function GetTagRemovedSignal
  * Removed Event TagAdded
  * Removed Event TagRemoved
* Add Class [CommandInstance](https://create.roblox.com/docs/reference/engine/classes/CommandInstance) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Add Property [AllowGUIAccessPoints](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#AllowGUIAccessPoints): bool [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [Checked](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Checked): bool [🔒 RobloxScriptSecurity] [🏷️ NotReplicated]
  * Add Property [DefaultShortcut](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#DefaultShortcut): string [🔒 RobloxScriptSecurity] [🏷️ NotReplicated]
  * Add Property [Enabled](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Enabled): bool [🔒 RobloxScriptSecurity] [🏷️ NotReplicated]
  * Add Property [Icon](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Icon): string [🔒 RobloxScriptSecurity] [🏷️ NotReplicated]
  * Add Property [Name](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Name): string [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [Permission](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Permission): CommandPermission [🔒 RobloxScriptSecurity] [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [StatusTip](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#StatusTip): string [🔒 RobloxScriptSecurity] [🏷️ NotReplicated]
  * Add Property [Text](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Text): string [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Function [RegisterExecutionCallback](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#RegisterExecutionCallback) (callbackFunction: Function) -> void [🔒 RobloxScriptSecurity]
* Add Class [CommandService](https://create.roblox.com/docs/reference/engine/classes/CommandService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Function [Execute](https://create.roblox.com/docs/reference/engine/classes/CommandService#Execute) (name: string, params: Variant) -> Variant [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Add Function [RegisterCommand](https://create.roblox.com/docs/reference/engine/classes/CommandService#RegisterCommand) (plugin: Plugin, name: string, description: string) -> CommandInstance [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Add Event [CommandExecuting](https://create.roblox.com/docs/reference/engine/classes/CommandService#CommandExecuting) [🔒 RobloxScriptSecurity]
* Update Class [Constraint](https://create.roblox.com/docs/reference/engine/classes/Constraint) [🏷️ NotCreatable]
  * Removed Function GetDebugAppliedForce
  * Removed Function GetDebugAppliedTorque
* Update Class [AlignOrientation](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation)
  * Removed Property CFrame
  * Removed Property LookAtPosition
  * Removed Property Mode
  * Removed Property PrimaryAxis
  * Removed Property SecondaryAxis
* Update Class [AlignPosition](https://create.roblox.com/docs/reference/engine/classes/AlignPosition)
  * Removed Property ForceLimitMode
  * Removed Property ForceRelativeTo
  * Removed Property MaxAxesForce
  * Removed Property Mode
  * Removed Property Position
* Update Class [BallSocketConstraint](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint)
  * Removed Property EnableSkinning
* Update Class [HingeConstraint](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint)
  * Removed Property SoftlockServoUponReachingTarget
* Add Class [LinearVelocityConstraint](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint)
  * Add Property [LineDirection](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#LineDirection): Vector3
  * Add Property [LineVelocity](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#LineVelocity): float
  * Add Property [MaxForce](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#MaxForce): float
  * Add Property [PlaneVelocity](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#PlaneVelocity): Vector2
  * Add Property [PrimaryTangentAxis](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#PrimaryTangentAxis): Vector3
  * Add Property [RelativeTo](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#RelativeTo): ActuatorRelativeTo
  * Add Property [SecondaryTangentAxis](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#SecondaryTangentAxis): Vector3
  * Add Property [VectorVelocity](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#VectorVelocity): Vector3
  * Add Property [VelocityConstraintMode](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#VelocityConstraintMode): VelocityConstraintMode
* Update Class [SlidingBallConstraint](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint) [🏷️ NotCreatable]
  * Removed Property SoftlockServoUponReachingTarget
* Update Class [CylindricalConstraint](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint)
  * Removed Property SoftlockAngularServoUponReachingTarget
* Update Class [ContentProvider](https://create.roblox.com/docs/reference/engine/classes/ContentProvider) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Function [CalculateNumTrianglesInMeshSync](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#CalculateNumTrianglesInMeshSync) (meshId: string) -> int [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [Preload](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#Preload) from null to void [🏷️ Deprecated]
  * Changed the parameters of Function [Preload](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#Preload)
    from: (contentId: ContentId)
    to: (contentId: Content) [🏷️ Deprecated]
  * Changed the return-type of Function [RegisterDefaultEncryptionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterDefaultEncryptionKey) from null to void
  * Changed the return-type of Function [RegisterDefaultSessionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterDefaultSessionKey) from null to void
  * Changed the return-type of Function [RegisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterEncryptedAsset) from null to void
  * Changed the parameters of Function [RegisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterEncryptedAsset)
    from: (assetId: ContentId, encryptionKey: string)
    to: (assetId: Content, encryptionKey: string)
  * Changed the return-type of Function [RegisterSessionEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterSessionEncryptedAsset) from null to void
  * Changed the parameters of Function [RegisterSessionEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterSessionEncryptedAsset)
    from: (contentId: ContentId, sessionKey: string)
    to: (contentId: Content, sessionKey: string)
  * Changed the return-type of Function [SetBaseUrl](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#SetBaseUrl) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [UnregisterDefaultEncryptionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#UnregisterDefaultEncryptionKey) from null to void
  * Changed the return-type of Function [UnregisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#UnregisterEncryptedAsset) from null to void
  * Changed the parameters of Function [UnregisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#UnregisterEncryptedAsset)
    from: (assetId: ContentId)
    to: (assetId: Content)
  * Add Function [CalculateNumTrianglesInMesh](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#CalculateNumTrianglesInMesh) (meshId: string) -> int [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [PreloadAsync](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#PreloadAsync) from null to void [🏷️ Yields]
  * Changed the parameters of Event [AssetFetchFailed](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#AssetFetchFailed)
    from: (assetId: ContentId)
    to: (assetId: Content)
  * Removed Function GetAssetFetchStatus
  * Removed Function GetAssetFetchStatusChangedSignal
  * Removed Function GetDependencyContentIds
  * Removed Function GetDetailedFailedRequests
* Update Class [ContextActionService](https://create.roblox.com/docs/reference/engine/classes/ContextActionService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [BindAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindAction) from null to void
  * Changed the return-type of Function [BindActionAtPriority](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActionAtPriority) from null to void
  * Changed the return-type of Function [BindActionToInputTypes](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActionToInputTypes) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [BindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActivate) from null to void
  * Changed the parameters of Function [BindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActivate)
    from: (userInputTypeForActivation: UserInputType, keyCodesForActivation: Tuple)
    to: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = Unknown)
  * Changed the return-type of Function [BindCoreAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindCoreAction) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [BindCoreActionAtPriority](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindCoreActionAtPriority) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [FireActionButtonFoundSignal](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#FireActionButtonFoundSignal) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetDescription](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetDescription) from null to void
  * Changed the return-type of Function [SetImage](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetImage) from null to void
  * Changed the return-type of Function [SetPosition](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetPosition) from null to void
  * Changed the return-type of Function [SetTitle](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetTitle) from null to void
  * Changed the return-type of Function [UnbindAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindAction) from null to void
  * Changed the return-type of Function [UnbindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindActivate) from null to void
  * Changed the parameters of Function [UnbindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindActivate)
    from: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = None)
    to: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = Unknown)
  * Changed the return-type of Function [UnbindAllActions](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindAllActions) from null to void
  * Changed the return-type of Function [UnbindCoreAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindCoreAction) from null to void [🔒 RobloxScriptSecurity]
  * Removed Function BindCoreActivate
  * Removed Function GetInputContexts
  * Removed Function GetInputSchemaKeyCodeTree
  * Removed Function UnbindCoreActivate
  * Removed Event InputContextsChanged
* Update Class [Controller](https://create.roblox.com/docs/reference/engine/classes/Controller) [🏷️ NotCreatable]
  * Changed the return-type of Function [BindButton](https://create.roblox.com/docs/reference/engine/classes/Controller#BindButton) from null to void
  * Changed the return-type of Function [UnbindButton](https://create.roblox.com/docs/reference/engine/classes/Controller#UnbindButton) from null to void
  * Changed the return-type of Function [bindButton](https://create.roblox.com/docs/reference/engine/classes/Controller#bindButton) from null to void [🏷️ Deprecated]
* Update Class [CustomEvent](https://create.roblox.com/docs/reference/engine/classes/CustomEvent) [🏷️ Deprecated]
  * Changed the return-type of Function [GetAttachedReceivers](https://create.roblox.com/docs/reference/engine/classes/CustomEvent#GetAttachedReceivers) from Instances to Objects
  * Changed the return-type of Function [SetValue](https://create.roblox.com/docs/reference/engine/classes/CustomEvent#SetValue) from null to void
* Update Class [FileMesh](https://create.roblox.com/docs/reference/engine/classes/FileMesh)
  * Changed the ValueType of Property [MeshId](https://create.roblox.com/docs/reference/engine/classes/FileMesh#MeshId) from ContentId to Content
  * Changed the ValueType of Property [TextureId](https://create.roblox.com/docs/reference/engine/classes/FileMesh#TextureId) from ContentId to Content
  * Removed Property MeshContent
  * Removed Property TextureContent
* Update Class [DataModelSession](https://create.roblox.com/docs/reference/engine/classes/DataModelSession) [🏷️ NotCreatable]
  * Add Event [DataModelCreated](https://create.roblox.com/docs/reference/engine/classes/DataModelSession#DataModelCreated) [🔒 RobloxScriptSecurity]
  * Add Event [DataModelWillBeDestroyed](https://create.roblox.com/docs/reference/engine/classes/DataModelSession#DataModelWillBeDestroyed) [🔒 RobloxScriptSecurity]
* Update Class [DataStoreIncrementOptions](https://create.roblox.com/docs/reference/engine/classes/DataStoreIncrementOptions) [🏷️ NotReplicated]
  * Changed the return-type of Function [SetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreIncrementOptions#SetMetadata) from null to void
* Update Class [DataStoreOptions](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions) [🏷️ NotReplicated]
  * Changed the return-type of Function [SetExperimentalFeatures](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions#SetExperimentalFeatures) from null to void
* Update Class [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [GetDataStore](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#GetDataStore) from DataStore to GlobalDataStore
  * Changed the return-type of Function [GetGlobalDataStore](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#GetGlobalDataStore) from DataStore to GlobalDataStore
  * Changed the parameters of Function [ListDataStoresAsync](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#ListDataStoresAsync)
    from: (prefix: string = , pageSize: int = 0, cursor: string = )
    to: (prefix: string = , pageSize: int = 0) [🏷️ Yields]
  * Removed Function SetRateLimitForRequestType
* Update Class [DataStoreSetOptions](https://create.roblox.com/docs/reference/engine/classes/DataStoreSetOptions) [🏷️ NotReplicated]
  * Changed the return-type of Function [SetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreSetOptions#SetMetadata) from null to void
* Update Class [Debris](https://create.roblox.com/docs/reference/engine/classes/Debris) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [AddItem](https://create.roblox.com/docs/reference/engine/classes/Debris#AddItem) from null to void
  * Changed the return-type of Function [SetLegacyMaxItems](https://create.roblox.com/docs/reference/engine/classes/Debris#SetLegacyMaxItems) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [addItem](https://create.roblox.com/docs/reference/engine/classes/Debris#addItem) from null to void [🏷️ Deprecated]
* Update Class [DebuggerConnection](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [AddBreakpoint](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#AddBreakpoint) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [AddBreakpoint](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#AddBreakpoint)
    from: (script: string, line: int, breakpoint: Breakpoint)
    to: (script: Instance, line: int, breakpoint: Instance) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [GetSource](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#GetSource)
    from: (scriptRef: string, status: Function)
    to: (scriptRef: Instance, status: Function) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [Pause](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Pause)
    from: (thread: ThreadState, status: Function)
    to: (status: Function) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RemoveBreakpoint](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#RemoveBreakpoint) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [RemoveBreakpoint](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#RemoveBreakpoint)
    from: (breakpoint: Breakpoint)
    to: (breakpoint: Instance) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [Resume](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Resume)
    from: (thread: ThreadState, status: Function)
    to: (status: Function) [🔒 RobloxScriptSecurity]
  * Add Function [Terminate](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Terminate) (status: Function) -> int [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [BreakpointAdded](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#BreakpointAdded)
    from: (breakpoint: Breakpoint)
    to: (breakpoint: Instance) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [BreakpointChanged](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#BreakpointChanged)
    from: (breakpoint: Breakpoint)
    to: (breakpoint: Instance) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [BreakpointRemoved](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#BreakpointRemoved)
    from: (breakpoint: Breakpoint, reason: BreakpointRemoveReason)
    to: (breakpoint: Instance, reason: BreakpointRemoveReason) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [Paused](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Paused)
    from: (pausedState: PausedState, reason: DebuggerPauseReason)
    to: (pausedState: Instance, reason: DebuggerPauseReason) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [Resumed](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Resumed)
    from: (pausedState: PausedState)
    to: (pausedState: Instance) [🔒 RobloxScriptSecurity]
  * Removed Property ErrorMessage
  * Removed Property HasError
  * Removed Function Close
  * Removed Function EvaluateWatch
  * Removed Function GetFrameById
  * Removed Function GetThreadById
  * Removed Function GetThreads
  * Removed Function GetVariableById
  * Removed Function Populate
  * Removed Function SetExceptionBreakMode
  * Removed Function SetVariable
  * Removed Function Step
  * Removed Function StepIn
  * Removed Function StepOut
  * Removed Function UpdateSelectedFrame
* Update Class [DebuggerConnectionManager](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [ConnectLocal](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#ConnectLocal)
    from: (dataModel: DataModel)
    to: (dataModel: Instance) [🔒 RobloxScriptSecurity]
  * Add Function [ConnectRemote](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#ConnectRemote) (host: string, port: int) -> int [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [FocusConnection](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#FocusConnection) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [FocusConnection](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#FocusConnection)
    from: (connection: DebuggerConnection)
    to: (connection: Instance) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [ConnectionEnded](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#ConnectionEnded)
    from: (connection: DebuggerConnection, reason: DebuggerEndReason)
    to: (connection: Instance, reason: DebuggerEndReason) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [ConnectionStarted](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#ConnectionStarted)
    from: (connection: DebuggerConnection)
    to: (connection: Instance) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [FocusChanged](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#FocusChanged)
    from: (connection: DebuggerConnection)
    to: (connection: Instance) [🔒 RobloxScriptSecurity]
  * Removed Function GetAvailableConnection
  * Removed Function GetConnectionById
* Update Class [DebuggerManager](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [EnableDebugging](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#EnableDebugging) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [GetDebuggers](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#GetDebuggers) from Instances to Objects
  * Changed the return-type of Function [Resume](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#Resume) from null to void
  * Changed the return-type of Function [StepIn](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#StepIn) from null to void
  * Changed the return-type of Function [StepOut](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#StepOut) from null to void
  * Changed the return-type of Function [StepOver](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#StepOver) from null to void
* Update Class [Dialog](https://create.roblox.com/docs/reference/engine/classes/Dialog)
  * Changed the return-type of Function [GetCurrentPlayers](https://create.roblox.com/docs/reference/engine/classes/Dialog#GetCurrentPlayers) from Instances to Objects
  * Changed the return-type of Function [SetPlayerIsUsing](https://create.roblox.com/docs/reference/engine/classes/Dialog#SetPlayerIsUsing) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalDialogChoiceSelected](https://create.roblox.com/docs/reference/engine/classes/Dialog#SignalDialogChoiceSelected) from null to void [🔒 RobloxScriptSecurity]
  * Removed Function SetGuiObject
* Update Class [DraftsService](https://create.roblox.com/docs/reference/engine/classes/DraftsService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [DiscardEdits](https://create.roblox.com/docs/reference/engine/classes/DraftsService#DiscardEdits) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [DiscardEdits](https://create.roblox.com/docs/reference/engine/classes/DraftsService#DiscardEdits)
    from: (scripts: Instances)
    to: (scripts: Objects) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [GetEditors](https://create.roblox.com/docs/reference/engine/classes/DraftsService#GetEditors) from Instances to Objects [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RestoreScripts](https://create.roblox.com/docs/reference/engine/classes/DraftsService#RestoreScripts) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [RestoreScripts](https://create.roblox.com/docs/reference/engine/classes/DraftsService#RestoreScripts)
    from: (scripts: Instances)
    to: (scripts: Objects) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ShowDiffsAgainstBase](https://create.roblox.com/docs/reference/engine/classes/DraftsService#ShowDiffsAgainstBase) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [ShowDiffsAgainstBase](https://create.roblox.com/docs/reference/engine/classes/DraftsService#ShowDiffsAgainstBase)
    from: (scripts: Instances)
    to: (scripts: Objects) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ShowDiffsAgainstServer](https://create.roblox.com/docs/reference/engine/classes/DraftsService#ShowDiffsAgainstServer) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [ShowDiffsAgainstServer](https://create.roblox.com/docs/reference/engine/classes/DraftsService#ShowDiffsAgainstServer)
    from: (scripts: Instances)
    to: (scripts: Objects) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [CommitEdits](https://create.roblox.com/docs/reference/engine/classes/DraftsService#CommitEdits) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the parameters of Function [CommitEdits](https://create.roblox.com/docs/reference/engine/classes/DraftsService#CommitEdits)
    from: (scripts: Instances)
    to: (scripts: Objects) [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [GetDrafts](https://create.roblox.com/docs/reference/engine/classes/DraftsService#GetDrafts) from Instances to Objects [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [UpdateToLatestVersion](https://create.roblox.com/docs/reference/engine/classes/DraftsService#UpdateToLatestVersion) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the parameters of Function [UpdateToLatestVersion](https://create.roblox.com/docs/reference/engine/classes/DraftsService#UpdateToLatestVersion)
    from: (scripts: Instances)
    to: (scripts: Objects) [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Removed Function ShowSourceDiffsAgainstCurrent
* Update Class [Dragger](https://create.roblox.com/docs/reference/engine/classes/Dragger)
  * Changed the return-type of Function [AxisRotate](https://create.roblox.com/docs/reference/engine/classes/Dragger#AxisRotate) from null to void
  * Changed the return-type of Function [MouseDown](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseDown) from null to void
  * Changed the parameters of Function [MouseDown](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseDown)
    from: (mousePart: Instance, pointOnMousePart: Vector3, parts: Instances)
    to: (mousePart: Instance, pointOnMousePart: Vector3, parts: Objects)
  * Changed the return-type of Function [MouseMove](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseMove) from null to void
  * Changed the return-type of Function [MouseUp](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseUp) from null to void
* Update Class [DraggerService](https://create.roblox.com/docs/reference/engine/classes/DraggerService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property HoverLineThickness
  * Removed Property PartSnapEnabled
  * Removed Property UseBoundingBoxes
* Update Class [EventIngestService](https://create.roblox.com/docs/reference/engine/classes/EventIngestService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [SendEventDeferred](https://create.roblox.com/docs/reference/engine/classes/EventIngestService#SendEventDeferred) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendEventImmediately](https://create.roblox.com/docs/reference/engine/classes/EventIngestService#SendEventImmediately) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetRBXEvent](https://create.roblox.com/docs/reference/engine/classes/EventIngestService#SetRBXEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetRBXEventStream](https://create.roblox.com/docs/reference/engine/classes/EventIngestService#SetRBXEventStream) from null to void [🔒 RobloxScriptSecurity]
* Update Class [Explosion](https://create.roblox.com/docs/reference/engine/classes/Explosion)
  * Changed the parameters of Event [Hit](https://create.roblox.com/docs/reference/engine/classes/Explosion#Hit)
    from: (part: BasePart, distance: float)
    to: (part: Instance, distance: float)
  * Removed Property LocalTransparencyModifier
  * Removed Property TimeScale
* Update Class [FaceControls](https://create.roblox.com/docs/reference/engine/classes/FaceControls) [🏷️ NotBrowsable]
  * Removed Function HasOverrideFACSData
  * Removed Event InternalFacsOverrideChanged
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal)
  * Changed the ValueType of Property [Texture](https://create.roblox.com/docs/reference/engine/classes/Decal#Texture) from ContentId to Content
  * Removed Property AutoLocalize
  * Removed Property ColorMap
  * Removed Property ColorMapContent
  * Removed Property MetalnessMap
  * Removed Property MetalnessMapContent
  * Removed Property NormalMap
  * Removed Property NormalMapContent
  * Removed Property Rotation
  * Removed Property RoughnessMap
  * Removed Property RoughnessMapContent
  * Removed Property TextureContent
  * Removed Property TexturePack
  * Removed Property TexturePackContent
  * Removed Property UVOffset
  * Removed Property UVScale
* Update Class [File](https://create.roblox.com/docs/reference/engine/classes/File) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [GetTemporaryId](https://create.roblox.com/docs/reference/engine/classes/File#GetTemporaryId) from ContentId to Content [🔒 PluginSecurity]
* Update Class [Fire](https://create.roblox.com/docs/reference/engine/classes/Fire)
  * Removed Property LocalTransparencyModifier
  * Removed Property TimeScale
  * Removed Function FastForward
* Update Class [FunctionalTest](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest) [🏷️ Deprecated]
  * Changed the return-type of Function [Error](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Error) from null to void
  * Changed the return-type of Function [Failed](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Failed) from null to void
  * Changed the return-type of Function [Pass](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Pass) from null to void
  * Changed the return-type of Function [Passed](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Passed) from null to void
  * Changed the return-type of Function [Warn](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Warn) from null to void
* Update Class [GameSettings](https://create.roblox.com/docs/reference/engine/classes/GameSettings) [🏷️ NotCreatable] [🏷️ Settings] [🏷️ NotBrowsable]
  * Add Property [AdditionalCoreIncludeDirs](https://create.roblox.com/docs/reference/engine/classes/GameSettings#AdditionalCoreIncludeDirs): string [🔒 Read:None, Write:RobloxScriptSecurity]
  * Add Property [OverrideStarterScript](https://create.roblox.com/docs/reference/engine/classes/GameSettings#OverrideStarterScript): string [🔒 Read:None, Write:RobloxScriptSecurity]
  * Add Property [VideoRecording](https://create.roblox.com/docs/reference/engine/classes/GameSettings#VideoRecording): bool [🔒 Read:RobloxScriptSecurity, Write:RobloxSecurity] [🏷️ NotReplicated]
* Update Class [GamepadService](https://create.roblox.com/docs/reference/engine/classes/GamepadService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [SetGamepadCursorPosition](https://create.roblox.com/docs/reference/engine/classes/GamepadService#SetGamepadCursorPosition) from null to void [🔒 RobloxScriptSecurity]
  * Removed Function AutoSelectGui
  * Removed Function DisableGamepadCursor
  * Removed Function EnableGamepadCursor
  * Removed Event GamepadThumbstick1Changed
* Update Class [GlobalDataStore](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the parameters of Function [GetAsync](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#GetAsync)
    from: (key: string, options: DataStoreGetOptions = nil)
    to: (key: string) [🏷️ Yields]
  * Removed Function BatchGetAsync
* Update Class [DataStore](https://create.roblox.com/docs/reference/engine/classes/DataStore) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the parameters of Function [ListKeysAsync](https://create.roblox.com/docs/reference/engine/classes/DataStore#ListKeysAsync)
    from: (prefix: string = , pageSize: int = 0, cursor: string = , excludeDeleted: bool = false)
    to: (prefix: string = , pageSize: int = 0) [🏷️ Yields]
  * Changed the return-type of Function [RemoveVersionAsync](https://create.roblox.com/docs/reference/engine/classes/DataStore#RemoveVersionAsync) from null to void [🏷️ Yields]
  * Removed Function GetVersionAtTimeAsync
* Update Class [OrderedDataStore](https://create.roblox.com/docs/reference/engine/classes/OrderedDataStore) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [GetSortedAsync](https://create.roblox.com/docs/reference/engine/classes/OrderedDataStore#GetSortedAsync) from DataStorePages to Instance [🏷️ Yields]
* Add Class [GoogleAnalyticsConfiguration](https://create.roblox.com/docs/reference/engine/classes/GoogleAnalyticsConfiguration) [🏷️ NotCreatable] [🏷️ Service]
* Update Class [GroupService](https://create.roblox.com/docs/reference/engine/classes/GroupService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [GetGroupsAsync](https://create.roblox.com/docs/reference/engine/classes/GroupService#GetGroupsAsync)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Removed Function PromptJoinCompleted
  * Removed Function GetRolesInGroupAsync
  * Removed Function PromptJoinAsync
  * Removed Event ShowJoinPrompt
* Update Class [GuiBase2d](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Removed Property SelectionBehaviorDown
  * Removed Property SelectionBehaviorLeft
  * Removed Property SelectionBehaviorRight
  * Removed Property SelectionBehaviorUp
  * Removed Property SelectionGroup
  * Removed Event SelectionChanged
* Update Class [GuiObject](https://create.roblox.com/docs/reference/engine/classes/GuiObject) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Removed Property GuiState
  * Removed Property InputSink
  * Removed Property Interactable
  * Removed Property SelectionOrder
  * Removed Property SelectionRect2D
  * Removed Function TweenPositionInternal
  * Removed Function TweenSizeAndPositionInternal
  * Removed Function TweenSizeInternal
* Update Class [GuiButton](https://create.roblox.com/docs/reference/engine/classes/GuiButton) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Removed Property HoverHapticEffect
  * Removed Property PressHapticEffect
  * Removed Event SecondaryActivated
* Update Class [ImageButton](https://create.roblox.com/docs/reference/engine/classes/ImageButton)
  * Changed the ValueType of Property [HoverImage](https://create.roblox.com/docs/reference/engine/classes/ImageButton#HoverImage) from ContentId to Content
  * Changed the ValueType of Property [Image](https://create.roblox.com/docs/reference/engine/classes/ImageButton#Image) from ContentId to Content
  * Changed the ValueType of Property [PressedImage](https://create.roblox.com/docs/reference/engine/classes/ImageButton#PressedImage) from ContentId to Content
  * Removed Property ContentImageSize
  * Removed Property HoverImageContent
  * Removed Property ImageContent
  * Removed Property PressedImageContent
  * Removed Function SetEnableContentImageSizeChangedEvents
* Update Class [TextButton](https://create.roblox.com/docs/reference/engine/classes/TextButton)
  * Changed the return-type of Function [SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextButton#SetTextFromInput) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property ContentText
  * Removed Property FontFace
  * Removed Property LocalizationMatchIdentifier
  * Removed Property LocalizationMatchedSourceText
  * Removed Property OpenTypeFeatures
  * Removed Property OpenTypeFeaturesError
  * Removed Property TextDirection
* Update Class [ImageLabel](https://create.roblox.com/docs/reference/engine/classes/ImageLabel)
  * Changed the ValueType of Property [Image](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#Image) from ContentId to Content
  * Removed Property ContentImageSize
  * Removed Property ImageContent
  * Removed Function SetEnableContentImageSizeChangedEvents
* Update Class [TextLabel](https://create.roblox.com/docs/reference/engine/classes/TextLabel)
  * Changed the return-type of Function [SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextLabel#SetTextFromInput) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property ContentText
  * Removed Property FontFace
  * Removed Property LocalizationMatchIdentifier
  * Removed Property LocalizationMatchedSourceText
  * Removed Property OpenTypeFeatures
  * Removed Property OpenTypeFeaturesError
  * Removed Property TextDirection
* Update Class [ScrollingFrame](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame)
  * Changed the ValueType of Property [BottomImage](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#BottomImage) from ContentId to Content
  * Changed the ValueType of Property [MidImage](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#MidImage) from ContentId to Content
  * Changed the ValueType of Property [TopImage](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#TopImage) from ContentId to Content
  * Changed the return-type of Function [ClearInertialScrolling](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ClearInertialScrolling) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ScrollToTop](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ScrollToTop) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property BottomImageContent
  * Removed Property DraggingScrollBar
  * Removed Property MidImageContent
  * Removed Property ScrollRate
  * Removed Property ScrollVelocity
  * Removed Property SmoothScroll
  * Removed Property TopImageContent
  * Removed Function GetScrollVelocity
  * Removed Function ResetScrollVelocity
* Update Class [TextBox](https://create.roblox.com/docs/reference/engine/classes/TextBox)
  * Add Property [EnableRealtimeFilteringHints](https://create.roblox.com/docs/reference/engine/classes/TextBox#EnableRealtimeFilteringHints): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
  * Changed the return-type of Function [CaptureFocus](https://create.roblox.com/docs/reference/engine/classes/TextBox#CaptureFocus) from null to void
  * Changed the return-type of Function [ReleaseFocus](https://create.roblox.com/docs/reference/engine/classes/TextBox#ReleaseFocus) from null to void
  * Changed the return-type of Function [ResetKeyboardMode](https://create.roblox.com/docs/reference/engine/classes/TextBox#ResetKeyboardMode) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextBox#SetTextFromInput) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property ContentText
  * Removed Property FontFace
  * Removed Property LocalizationMatchIdentifier
  * Removed Property LocalizationMatchedSourceText
  * Removed Property OpenTypeFeatures
  * Removed Property OpenTypeFeaturesError
  * Removed Property ShouldEmitReturnEvents
  * Removed Property ShouldEmitTabEvents
  * Removed Property ShouldEmitUpAndDownArrowEvents
  * Removed Property TextDirection
* Update Class [VideoFrame](https://create.roblox.com/docs/reference/engine/classes/VideoFrame)
  * Changed the ValueType of Property [Video](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Video) from ContentId to Content
  * Changed the return-type of Function [Pause](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Pause) from null to void
  * Changed the return-type of Function [Play](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Play) from null to void
  * Removed Property InternalVideoUsage
  * Removed Property MaximumResolution
  * Removed Property RollOffMaxDistance
  * Removed Property RollOffMinDistance
  * Removed Property RollOffMode
  * Removed Property VideoContent
  * Removed Function SetStudioPreview
* Update Class [ViewportFrame](https://create.roblox.com/docs/reference/engine/classes/ViewportFrame)
  * Removed Property IsMirrored
  * Removed Function CaptureSnapshotAsync
* Update Class [LayerCollector](https://create.roblox.com/docs/reference/engine/classes/LayerCollector) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Removed Property TabKeyboardNavigation
  * Removed Function GetGuiObjectsAtPosition
* Update Class [PluginGui](https://create.roblox.com/docs/reference/engine/classes/PluginGui) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [BindToClose](https://create.roblox.com/docs/reference/engine/classes/PluginGui#BindToClose) from null to void
  * Removed Property Plugin
  * Removed Function OverrideStudioAction
  * Removed Event InputBegan
  * Removed Event InputChanged
  * Removed Event InputEnded
  * Removed Event MouseEnter
  * Removed Event MouseLeave
  * Removed Event PointerAction
* Update Class [DockWidgetPluginGui](https://create.roblox.com/docs/reference/engine/classes/DockWidgetPluginGui) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Function RequestRaise
* Update Class [ScreenGui](https://create.roblox.com/docs/reference/engine/classes/ScreenGui)
  * Removed Property ClipToDeviceSafeArea
  * Removed Property SafeAreaCompatibility
  * Removed Property ScreenInsets
* Update Class [SurfaceGui](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui)
  * Add Property [Active](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#Active): bool
  * Add Property [Adornee](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#Adornee): Instance
  * Add Property [Face](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#Face): NormalId
  * Removed Property HorizontalCurvature
  * Removed Property MaxDistance
  * Removed Property Shape
* Update Class [FloorWire](https://create.roblox.com/docs/reference/engine/classes/FloorWire) [🏷️ Deprecated]
  * Changed the ValueType of Property [Texture](https://create.roblox.com/docs/reference/engine/classes/FloorWire#Texture) from ContentId to Content
* Update Class [SelectionBox](https://create.roblox.com/docs/reference/engine/classes/SelectionBox)
  * Removed Property StudioSelectionBox
* Update Class [HandleAdornment](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment) [🏷️ NotCreatable]
  * Removed Property GizmoReference
* Update Class [BoxHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/BoxHandleAdornment)
  * Removed Property Shading
* Update Class [ConeHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/ConeHandleAdornment)
  * Removed Property Hollow
  * Removed Property Shading
* Update Class [CylinderHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment)
  * Removed Property Shading
* Update Class [ImageHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment)
  * Changed the ValueType of Property [Image](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment#Image) from ContentId to Content
  * Removed Property ImageContent
* Update Class [SphereHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/SphereHandleAdornment)
  * Removed Property Shading
* Update Class [ParabolaAdornment](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment)
  * Changed the parameters of Function [FindPartOnParabola](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment#FindPartOnParabola)
    from: (ignoreDescendentsTable: Instances)
    to: (ignoreDescendentsTable: Objects) [🔒 RobloxScriptSecurity]
* Update Class [GuiService](https://create.roblox.com/docs/reference/engine/classes/GuiService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [AddCenterDialog](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddCenterDialog) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [AddKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddKey) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [AddSelectionParent](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSelectionParent) from null to void
  * Changed the return-type of Function [AddSelectionTuple](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSelectionTuple) from null to void
  * Changed the return-type of Function [AddSpecialKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSpecialKey) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [BroadcastNotification](https://create.roblox.com/docs/reference/engine/classes/GuiService#BroadcastNotification) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ClearError](https://create.roblox.com/docs/reference/engine/classes/GuiService#ClearError) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [CloseInspectMenu](https://create.roblox.com/docs/reference/engine/classes/GuiService#CloseInspectMenu) from null to void
  * Changed the return-type of Function [ForceTenFootInterface](https://create.roblox.com/docs/reference/engine/classes/GuiService#ForceTenFootInterface) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [InspectPlayerFromHumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromHumanoidDescription) from null to void
  * Changed the return-type of Function [InspectPlayerFromUserId](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserId) from null to void
  * Changed the parameters of Function [InspectPlayerFromUserId](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserId)
    from: (userId: User)
    to: (userId: int64)
  * Changed the return-type of Function [InspectPlayerFromUserIdWithCtx](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserIdWithCtx) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [InspectPlayerFromUserIdWithCtx](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserIdWithCtx)
    from: (userId: User, ctx: string)
    to: (userId: int64, ctx: string) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [OpenBrowserWindow](https://create.roblox.com/docs/reference/engine/classes/GuiService#OpenBrowserWindow) from null to void [🔒 RobloxScriptSecurity] [🏷️ Deprecated]
  * Changed the return-type of Function [OpenNativeOverlay](https://create.roblox.com/docs/reference/engine/classes/GuiService#OpenNativeOverlay) from null to void [🔒 RobloxScriptSecurity] [🏷️ Deprecated]
  * Changed the return-type of Function [RemoveCenterDialog](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveCenterDialog) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RemoveKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveKey) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RemoveSelectionGroup](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveSelectionGroup) from null to void
  * Changed the return-type of Function [RemoveSpecialKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveSpecialKey) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetEmotesMenuOpen](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetEmotesMenuOpen) from null to void
  * Changed the return-type of Function [SetGameplayPausedNotificationEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetGameplayPausedNotificationEnabled) from null to void
  * Changed the return-type of Function [SetGlobalGuiInset](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetGlobalGuiInset) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetInspectMenuEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetInspectMenuEnabled) from null to void
  * Changed the return-type of Function [SetMenuIsOpen](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetMenuIsOpen) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetSafeZoneOffsets](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetSafeZoneOffsets) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetUiMessage](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetUiMessage) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [ToggleFullscreen](https://create.roblox.com/docs/reference/engine/classes/GuiService#ToggleFullscreen) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Callback [SendCoreUiNotification](https://create.roblox.com/docs/reference/engine/classes/GuiService#SendCoreUiNotification) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property DisplayScalingMode
  * Removed Property PreferredTextSize
  * Removed Property PreferredTransparency
  * Removed Property ReducedMotionEnabled
  * Removed Property TopbarInset
  * Removed Property ViewportDisplaySize
  * Removed Property ViewportSizeInMM
  * Removed Function DismissNotification
  * Removed Function GetClosestVisibleDialogToPosition
  * Removed Function GetErrorDetails
  * Removed Function GetGuiIsVisible
  * Removed Function GetHardwareSafeViewport
  * Removed Function GetInsetArea
  * Removed Function GetRawScreenScale
  * Removed Function OnNotificationDisplayed
  * Removed Function OnNotificationInteraction
  * Removed Function Select
  * Removed Function SendNotification
  * Removed Function SendUIOcclusionMetricsForQueryRegion
  * Removed Function SetHardwareSafeAreaInsets
  * Removed Function SetPurchasePromptIsShown
  * Removed Function SetTopbarInset
  * Removed Function ToggleGuiIsVisibleForCaptures
  * Removed Function ToggleGuiIsVisibleIfAllowed
  * Removed Event GuiVisibilityChangedSignal
  * Removed Event OpenStyleEditor
  * Removed Event PurchasePromptShown
* Update Class [HapticService](https://create.roblox.com/docs/reference/engine/classes/HapticService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [SetMotor](https://create.roblox.com/docs/reference/engine/classes/HapticService#SetMotor) from null to void
* Update Class [HeightmapImporterService](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService) [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [CancelImportHeightmap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#CancelImportHeightmap) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [IsValidColormap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#IsValidColormap)
    from: (colormapAssetId: ContentId)
    to: (colormapAssetId: Content) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [IsValidHeightmap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#IsValidHeightmap)
    from: (heightmapAssetId: ContentId)
    to: (heightmapAssetId: Content) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetImportHeightmapPaused](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#SetImportHeightmapPaused) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [GetHeightmapPreviewAsync](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#GetHeightmapPreviewAsync)
    from: (heightmapAssetId: ContentId)
    to: (heightmapAssetId: Content) [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [ImportHeightmap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#ImportHeightmap) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the parameters of Function [ImportHeightmap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#ImportHeightmap)
    from: (region: Region3, heightmapAssetId: ContentId, colormapAssetId: ContentId, defaultMaterial: Material)
    to: (region: Region3, heightmapAssetId: Content, colormapAssetId: Content, defaultMaterial: Material) [🔒 RobloxScriptSecurity] [🏷️ Yields]
* Update Class [HttpRequest](https://create.roblox.com/docs/reference/engine/classes/HttpRequest) [🏷️ NotCreatable]
  * Changed the return-type of Function [Cancel](https://create.roblox.com/docs/reference/engine/classes/HttpRequest#Cancel) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [Start](https://create.roblox.com/docs/reference/engine/classes/HttpRequest#Start) from null to void [🔒 RobloxScriptSecurity]
* Update Class [HttpService](https://create.roblox.com/docs/reference/engine/classes/HttpService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [SetHttpEnabled](https://create.roblox.com/docs/reference/engine/classes/HttpService#SetHttpEnabled) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [GetAsync](https://create.roblox.com/docs/reference/engine/classes/HttpService#GetAsync)
    from: (url: Variant, nocache: bool = false, headers: Variant)
    to: (url: string, nocache: bool = false, headers: Variant) [🏷️ Yields]
  * Changed the parameters of Function [PostAsync](https://create.roblox.com/docs/reference/engine/classes/HttpService#PostAsync)
    from: (url: Variant, data: string, content_type: HttpContentType = ApplicationJson, compress: bool = false, headers: Variant)
    to: (url: string, data: string, content_type: HttpContentType = ApplicationJson, compress: bool = false, headers: Variant) [🏷️ Yields]
  * Removed Function CreateWebStreamClient
  * Removed Function CreateWebStreamClientInternal
  * Removed Function GetSecret
  * Removed Function JSONDecodeAsync
  * Removed Function JSONEncodeAsync
  * Removed Function RequestAccessTokenScopesAsync
* Update Class [Humanoid](https://create.roblox.com/docs/reference/engine/classes/Humanoid)
  * Changed the return-type of Function [AddAccessory](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AddAccessory) from null to void
  * Add Function [ApplyDescriptionBlocking](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyDescriptionBlocking) (humanoidDescription: HumanoidDescription) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [BuildRigFromAttachments](https://create.roblox.com/docs/reference/engine/classes/Humanoid#BuildRigFromAttachments) from null to void
  * Changed the return-type of Function [CacheDefaults](https://create.roblox.com/docs/reference/engine/classes/Humanoid#CacheDefaults) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ChangeState](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ChangeState) from null to void
  * Changed the return-type of Function [EquipTool](https://create.roblox.com/docs/reference/engine/classes/Humanoid#EquipTool) from null to void
  * Changed the return-type of Function [Move](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Move) from null to void
  * Changed the return-type of Function [MoveTo](https://create.roblox.com/docs/reference/engine/classes/Humanoid#MoveTo) from null to void
  * Changed the return-type of Function [RemoveAccessories](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RemoveAccessories) from null to void
  * Changed the return-type of Function [SetClickToWalkEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#SetClickToWalkEnabled) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetStateEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#SetStateEnabled) from null to void
  * Changed the return-type of Function [TakeDamage](https://create.roblox.com/docs/reference/engine/classes/Humanoid#TakeDamage) from null to void
  * Changed the return-type of Function [UnequipTools](https://create.roblox.com/docs/reference/engine/classes/Humanoid#UnequipTools) from null to void
  * Changed the return-type of Function [takeDamage](https://create.roblox.com/docs/reference/engine/classes/Humanoid#takeDamage) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [ApplyDescription](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyDescription) from null to void [🏷️ Yields]
  * Add Function [ApplyDescriptionClientServer](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyDescriptionClientServer) (humanoidDescription: HumanoidDescription) -> void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Removed Property EvaluateStateMachine
  * Removed Property InternalDisplayName
  * Removed Function ComputeOriginalSizeForPart
  * Removed Function ComputeR15BodyBoundingBox
  * Removed Function GetAccessoryHandleScale
  * Removed Function GetMoveVelocity
  * Removed Function GetRelativeVelocityAtFloor
  * Removed Function ApplyAvatarRules
  * Removed Function ApplyDescriptionAsync
  * Removed Function ApplyDescriptionReset
  * Removed Function ApplyDescriptionResetAsync
  * Removed Function PlayEmoteAsync
  * Removed Event ApplyDescriptionFinished
  * Removed Event EmoteTriggered
* Update Class [HumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription)
  * Changed the return-type of Function [AddEmote](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#AddEmote) from null to void
  * Changed the return-type of Function [RemoveEmote](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RemoveEmote) from null to void
  * Changed the return-type of Function [SetAccessories](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetAccessories) from null to void
  * Changed the return-type of Function [SetEmotes](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetEmotes) from null to void
  * Changed the return-type of Function [SetEquippedEmotes](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetEquippedEmotes) from null to void
  * Removed Property MoodAnimation
  * Removed Property ResetIncludesBodyParts
  * Removed Property StaticFacialAnimation
  * Removed Property UseAvatarSettings
* Update Class [IXPService](https://create.roblox.com/docs/reference/engine/classes/IXPService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [ClearUserLayers](https://create.roblox.com/docs/reference/engine/classes/IXPService#ClearUserLayers) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [InitializeUserLayers](https://create.roblox.com/docs/reference/engine/classes/IXPService#InitializeUserLayers) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [RegisterUserLayers](https://create.roblox.com/docs/reference/engine/classes/IXPService#RegisterUserLayers) from null to void [🔒 LocalUserSecurity]
  * Removed Function ClearCreatorLayers
  * Removed Function GetBrowserTrackerStatusForLayer
  * Removed Function GetCreatorLayerLoadingStatus
  * Removed Function GetCreatorLayerVariables
  * Removed Function GetCreatorStatusForLayer
  * Removed Function GetRegisteredCreatorLayersToStatus
  * Removed Function GetRegisteredUserLayersToStatus
  * Removed Function GetUserStatusForLayer
  * Removed Function InitializeCreatorLayers
  * Removed Function LogBrowserTrackerLayerExposure
  * Removed Function LogCreatorLayerExposure
  * Removed Function LogFlagLinkedUserLayerExposure
  * Removed Function LogUserLayerExposure
  * Removed Function RegisterCreatorLayers
  * Removed Event OnCreatorLayerLoadingStatusChanged
* Add Class [ImporterBaseSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterBaseSettings) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Add Property [Id](https://create.roblox.com/docs/reference/engine/classes/ImporterBaseSettings#Id): string [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [ImportName](https://create.roblox.com/docs/reference/engine/classes/ImporterBaseSettings#ImportName): string
  * Add Property [ShouldImport](https://create.roblox.com/docs/reference/engine/classes/ImporterBaseSettings#ShouldImport): bool
* Add Class [ImporterGroupSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterGroupSettings) [🏷️ NotCreatable] [🏷️ NotReplicated]
* Add Class [ImporterJointSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterJointSettings) [🏷️ NotCreatable] [🏷️ NotReplicated]
* Add Class [ImporterMeshSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterMeshSettings) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Add Property [DoubleSided](https://create.roblox.com/docs/reference/engine/classes/ImporterMeshSettings#DoubleSided): bool
* Add Class [ImporterRootSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Add Property [FileDimensions](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#FileDimensions): Vector3 [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [FlattenAll](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#FlattenAll): bool
  * Add Property [PolygonCount](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#PolygonCount): float [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [ScaleUnit](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#ScaleUnit): MeshScaleUnit
  * Add Property [WorldForward](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#WorldForward): NormalId
  * Add Property [WorldUp](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#WorldUp): NormalId
  * Add Property [ZeroOrigin](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#ZeroOrigin): bool
* Add Class [ImporterTextureSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterTextureSettings) [🏷️ NotCreatable] [🏷️ NotReplicated]
* Update Class [IncrementalPatchBuilder](https://create.roblox.com/docs/reference/engine/classes/IncrementalPatchBuilder) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property AddPathsToBundle
  * Removed Property BuildDebouncePeriod
  * Removed Property HighCompression
  * Removed Property SerializePatch
  * Removed Property UseFileLevelCompressionInsteadOfChunk
  * Removed Property ZstdCompression
* Update Class [InsertService](https://create.roblox.com/docs/reference/engine/classes/InsertService) [🏷️ NotCreatable] [🏷️ Service]
  * Add Property [AllowClientInsertModels](https://create.roblox.com/docs/reference/engine/classes/InsertService#AllowClientInsertModels): bool [🏷️ NotScriptable]
  * Changed the return-type of Function [ApproveAssetId](https://create.roblox.com/docs/reference/engine/classes/InsertService#ApproveAssetId) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [ApproveAssetVersionId](https://create.roblox.com/docs/reference/engine/classes/InsertService#ApproveAssetVersionId) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Insert](https://create.roblox.com/docs/reference/engine/classes/InsertService#Insert) from null to void [🏷️ Deprecated]
  * Add Function [LoadPackageAsset](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadPackageAsset) (url: Content) -> Objects [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [CreateMeshPartAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#CreateMeshPartAsync)
    from: (meshId: ContentId, collisionFidelity: CollisionFidelity, renderFidelity: RenderFidelity)
    to: (meshId: Content, collisionFidelity: CollisionFidelity, renderFidelity: RenderFidelity) [🔒 PluginSecurity] [🏷️ Yields]
  * Changed the parameters of Function [GetUserCategories](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetUserCategories)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields] [🏷️ Deprecated]
  * Changed the parameters of Function [GetUserSets](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetUserSets)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the return-type of Function [LoadPackageAssetAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadPackageAssetAsync) from Instances to Objects [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the parameters of Function [LoadPackageAssetAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadPackageAssetAsync)
    from: (url: ContentId)
    to: (url: Content) [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Removed Function GetLocalFileContents
  * Removed Function GetFreeDecalsAsync
  * Removed Function GetFreeModelsAsync
  * Removed Function LoadAssetWithBytecodeAsync
  * Removed Function LoadAssetWithFormat
* Add Class [InternalContainer](https://create.roblox.com/docs/reference/engine/classes/InternalContainer) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Update Class [Motor](https://create.roblox.com/docs/reference/engine/classes/Motor)
  * Changed the return-type of Function [SetDesiredAngle](https://create.roblox.com/docs/reference/engine/classes/Motor#SetDesiredAngle) from null to void
* Update Class [Motor6D](https://create.roblox.com/docs/reference/engine/classes/Motor6D)
  * Removed Property EnableSkinning
* Update Class [Weld](https://create.roblox.com/docs/reference/engine/classes/Weld)
  * Removed Property EnableSkinning
* Update Class [JointsService](https://create.roblox.com/docs/reference/engine/classes/JointsService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ Deprecated]
  * Changed the return-type of Function [ClearJoinAfterMoveJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#ClearJoinAfterMoveJoints) from null to void
  * Changed the return-type of Function [CreateJoinAfterMoveJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#CreateJoinAfterMoveJoints) from null to void
  * Changed the return-type of Function [SetJoinAfterMoveInstance](https://create.roblox.com/docs/reference/engine/classes/JointsService#SetJoinAfterMoveInstance) from null to void
  * Changed the return-type of Function [SetJoinAfterMoveTarget](https://create.roblox.com/docs/reference/engine/classes/JointsService#SetJoinAfterMoveTarget) from null to void
  * Changed the return-type of Function [ShowPermissibleJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#ShowPermissibleJoints) from null to void
* Update Class [Keyframe](https://create.roblox.com/docs/reference/engine/classes/Keyframe)
  * Changed the return-type of Function [AddMarker](https://create.roblox.com/docs/reference/engine/classes/Keyframe#AddMarker) from null to void
  * Changed the return-type of Function [AddPose](https://create.roblox.com/docs/reference/engine/classes/Keyframe#AddPose) from null to void
  * Changed the return-type of Function [GetMarkers](https://create.roblox.com/docs/reference/engine/classes/Keyframe#GetMarkers) from Instances to Objects
  * Changed the return-type of Function [GetPoses](https://create.roblox.com/docs/reference/engine/classes/Keyframe#GetPoses) from Instances to Objects
  * Changed the return-type of Function [RemoveMarker](https://create.roblox.com/docs/reference/engine/classes/Keyframe#RemoveMarker) from null to void
  * Changed the return-type of Function [RemovePose](https://create.roblox.com/docs/reference/engine/classes/Keyframe#RemovePose) from null to void
* Update Class [KeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence)
  * Add Property [Loop](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#Loop): bool
  * Add Property [Priority](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#Priority): AnimationPriority
  * Changed the return-type of Function [AddKeyframe](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#AddKeyframe) from null to void
  * Changed the return-type of Function [GetKeyframes](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#GetKeyframes) from Instances to Objects
  * Changed the return-type of Function [RemoveKeyframe](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#RemoveKeyframe) from null to void
* Update Class [KeyframeSequenceProvider](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [GetKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequence)
    from: (assetId: ContentId)
    to: (assetId: Content) [🔒 PluginSecurity] [🏷️ Deprecated]
  * Changed the return-type of Function [RegisterActiveKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#RegisterActiveKeyframeSequence) from ContentId to Content
  * Changed the return-type of Function [RegisterKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#RegisterKeyframeSequence) from ContentId to Content
  * Changed the parameters of Function [GetAnimations](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetAnimations)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the parameters of Function [GetKeyframeSequenceAsync](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequenceAsync)
    from: (assetId: ContentId)
    to: (assetId: Content) [🏷️ Yields]
  * Removed Function GetAnimationsAsync
* Update Class [LanguageService](https://create.roblox.com/docs/reference/engine/classes/LanguageService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function GetCapabilitiesUsedInPackageAsync
* Update Class [Lighting](https://create.roblox.com/docs/reference/engine/classes/Lighting) [🏷️ NotCreatable] [🏷️ Service]
  * Add Property [TempUseNewSkyRemovalBehaviour](https://create.roblox.com/docs/reference/engine/classes/Lighting#TempUseNewSkyRemovalBehaviour): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
  * Changed the return-type of Function [SetMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#SetMinutesAfterMidnight) from null to void
  * Changed the return-type of Function [setMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#setMinutesAfterMidnight) from null to void [🏷️ Deprecated]
  * Removed Property ExtendLightRangeTo120
  * Removed Property LightingStyle
  * Removed Property PrioritizeLightingQuality
* Update Class [LocalStorageService](https://create.roblox.com/docs/reference/engine/classes/LocalStorageService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [Flush](https://create.roblox.com/docs/reference/engine/classes/LocalStorageService#Flush) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetItem](https://create.roblox.com/docs/reference/engine/classes/LocalStorageService#SetItem) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [WhenLoaded](https://create.roblox.com/docs/reference/engine/classes/LocalStorageService#WhenLoaded) from null to void [🔒 RobloxScriptSecurity]
* Update Class [LocalizationService](https://create.roblox.com/docs/reference/engine/classes/LocalizationService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [GetCorescriptLocalizations](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#GetCorescriptLocalizations) from Instances to Objects
  * Changed the return-type of Function [SetRobloxLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#SetRobloxLocaleId) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [StartTextScraper](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#StartTextScraper) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [StopTextScraper](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#StopTextScraper) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PromptDownloadGameTableToCSV](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptDownloadGameTableToCSV) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [PromptExportToCSVs](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptExportToCSVs) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [PromptImportFromCSVs](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptImportFromCSVs) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Removed Function GetIsLoadingInternalTranslations
  * Removed Function IsLoadingInternalTranslationsSettingChanged
* Update Class [LocalizationTable](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable)
  * Changed the return-type of Function [RemoveEntry](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveEntry) from null to void
  * Changed the return-type of Function [RemoveEntryValue](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveEntryValue) from null to void
  * Changed the return-type of Function [RemoveKey](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveKey) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [RemoveTargetLocale](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveTargetLocale) from null to void
  * Changed the return-type of Function [SetContents](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetContents) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetEntries](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntries) from null to void
  * Changed the return-type of Function [SetEntry](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntry) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetEntryContext](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryContext) from null to void
  * Changed the return-type of Function [SetEntryExample](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryExample) from null to void
  * Changed the return-type of Function [SetEntryKey](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryKey) from null to void
  * Changed the return-type of Function [SetEntrySource](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntrySource) from null to void
  * Changed the return-type of Function [SetEntryValue](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryValue) from null to void
  * Changed the return-type of Function [SetIsExemptFromUGCAnalytics](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetIsExemptFromUGCAnalytics) from null to void [🔒 RobloxScriptSecurity]
* Update Class [LogService](https://create.roblox.com/docs/reference/engine/classes/LogService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [ExecuteScript](https://create.roblox.com/docs/reference/engine/classes/LogService#ExecuteScript) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RequestHttpResultApproved](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestHttpResultApproved) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RequestServerHttpResult](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestServerHttpResult) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RequestServerOutput](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestServerOutput) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [MessageOut](https://create.roblox.com/docs/reference/engine/classes/LogService#MessageOut)
    from: (message: string, messageType: MessageType, context: Dictionary)
    to: (message: string, messageType: MessageType)
  * Changed the parameters of Event [ServerMessageOut](https://create.roblox.com/docs/reference/engine/classes/LogService#ServerMessageOut)
    from: (message: string, messageType: MessageType, timestamp: double)
    to: (message: string, messageType: MessageType, timestamp: int) [🔒 RobloxScriptSecurity]
  * Removed Function ClearOutput
  * Removed Function Error
  * Removed Function Info
  * Removed Function Log
  * Removed Function Output
  * Removed Function Warn
  * Removed Event ServerContextOut
* Update Class [LoginService](https://create.roblox.com/docs/reference/engine/classes/LoginService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [Logout](https://create.roblox.com/docs/reference/engine/classes/LoginService#Logout) from null to void [🔒 RobloxSecurity]
  * Changed the return-type of Function [PromptLogin](https://create.roblox.com/docs/reference/engine/classes/LoginService#PromptLogin) from null to void [🔒 RobloxSecurity]
* Update Class [LuaSourceContainer](https://create.roblox.com/docs/reference/engine/classes/LuaSourceContainer) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Add Property [CurrentEditor](https://create.roblox.com/docs/reference/engine/classes/LuaSourceContainer#CurrentEditor): Instance [🏷️ NotScriptable]
* Update Class [BaseScript](https://create.roblox.com/docs/reference/engine/classes/BaseScript) [🏷️ NotCreatable]
  * Changed the ValueType of Property [LinkedSource](https://create.roblox.com/docs/reference/engine/classes/BaseScript#LinkedSource) from ContentId to Content
  * Removed Property Enabled
  * Removed Property RunContext
* Update Class [ModuleScript](https://create.roblox.com/docs/reference/engine/classes/ModuleScript)
  * Changed the ValueType of Property [LinkedSource](https://create.roblox.com/docs/reference/engine/classes/ModuleScript#LinkedSource) from ContentId to Content
* Update Class [MarketplaceService](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [PromptBundlePurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptBundlePurchase) from null to void
  * Changed the return-type of Function [PromptGamePassPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptGamePassPurchase) from null to void
  * Changed the return-type of Function [PromptNativePurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptNativePurchase) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PromptPremiumPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptPremiumPurchase) from null to void
  * Changed the return-type of Function [PromptProductPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptProductPurchase) from null to void
  * Changed the return-type of Function [PromptPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptPurchase) from null to void
  * Changed the return-type of Function [PromptRobloxPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptRobloxPurchase) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [PromptSubscriptionCancellation](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionCancellation) (player: Instance, subscriptionId: int64) -> void
  * Changed the return-type of Function [PromptSubscriptionPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchase) from null to void
  * Changed the parameters of Function [PromptSubscriptionPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchase)
    from: (user: Player, subscriptionId: string)
    to: (player: Instance, subscriptionId: int64)
  * Changed the return-type of Function [PromptThirdPartyPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptThirdPartyPurchase) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [ReportAssetSale](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#ReportAssetSale) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ReportRobuxUpsellStarted](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#ReportRobuxUpsellStarted) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalAssetTypePurchased](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalAssetTypePurchased) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalClientPurchaseSuccess](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalClientPurchaseSuccess) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalMockPurchasePremium](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalMockPurchasePremium) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalPromptBundlePurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptBundlePurchaseFinished) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalPromptGamePassPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptGamePassPurchaseFinished) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalPromptPremiumPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptPremiumPurchaseFinished) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalPromptProductPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptProductPurchaseFinished) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalPromptPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptPurchaseFinished) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [SignalPromptSubscriptionCancellationFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptSubscriptionCancellationFinished) (player: Instance, subscriptionId: int64, wasCanceled: bool) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalPromptSubscriptionPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptSubscriptionPurchaseFinished) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [SignalPromptSubscriptionPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptSubscriptionPurchaseFinished)
    from: (subscriptionId: string, didTryPurchasing: bool)
    to: (player: Instance, subscriptionId: int64, wasPurchased: bool) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SignalServerLuaDialogClosed](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalServerLuaDialogClosed) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [IsPlayerSubscribed](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#IsPlayerSubscribed) (player: Instance, subscriptionId: int64) -> bool [🏷️ Yields]
  * Changed the parameters of Function [PerformPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PerformPurchase)
    from: (infoType: InfoType, productId: int64, expectedPrice: int, requestId: string, isRobloxPurchase: bool, collectibleItemId: string = , collectibleProductId: string = , idempotencyKey: string = , purchaseAuthToken: string = , timedOptionsDays: int64 = 0, purchasePayload: string = , purchaseOptions: Dictionary = nil)
    to: (infoType: InfoType, productId: int64, expectedPrice: int, requestId: string, isRobloxPurchase: bool) [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the parameters of Function [UserOwnsGamePassAsync](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#UserOwnsGamePassAsync)
    from: (userId: User, gamePassId: int64)
    to: (userId: int64, gamePassId: int64) [🏷️ Yields]
  * Add Event [PromptSubscriptionCancellationFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionCancellationFinished)
  * Add Event [PromptSubscriptionCancellationRequested](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionCancellationRequested) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [PromptSubscriptionPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchaseFinished)
    from: (user: Player, subscriptionId: string, didTryPurchasing: bool)
    to: (player: Instance, subscriptionId: int64, wasPurchased: bool)
  * Changed the parameters of Event [PromptSubscriptionPurchaseRequested](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchaseRequested)
    from: (subscriptionId: string)
    to: (player: Instance, subscriptionId: int64) [🔒 RobloxScriptSecurity]
  * Removed Function BindReceiptHandler
  * Removed Function ClearProductInfoCaches
  * Removed Function IsPurchaseSimulated
  * Removed Function OpenShop
  * Removed Function PrepareCollectiblesPurchase
  * Removed Function PromptBulkPurchase
  * Removed Function PromptCancelSubscription
  * Removed Function PromptCollectiblesPurchase
  * Removed Function PromptNativePurchaseWithLocalPlayer
  * Removed Function PromptNativePurchaseWithLocalPlayerWithPaymentSessionId
  * Removed Function PromptNativePurchaseWithPaymentSessionId
  * Removed Function PromptRobloxSubscriptionPurchase
  * Removed Function SignalCheckPlayerHasRobloxSubscription
  * Removed Function SignalMockPurchaseRobloxSubscription
  * Removed Function SignalPromptBulkPurchaseFinished
  * Removed Function SignalPromptRobloxSubscriptionPurchaseFinished
  * Removed Function SignalRobuxTransferCompleted
  * Removed Function SignalUserSubscriptionStatusChanged
  * Removed Function GetAvailableSubscriptionProductsAsync
  * Removed Function GetProductInfoAsync
  * Removed Function GetRobloxSubscriptionDetailsAsync
  * Removed Function GetSubscriptionProductInfoAsync
  * Removed Function GetSubscriptionPurchaseInfoAsync
  * Removed Function GetUserSubscriptionDetailsAsync
  * Removed Function GetUserSubscriptionDetailsInternalAsync
  * Removed Function GetUserSubscriptionPaymentHistoryAsync
  * Removed Function GetUserSubscriptionStatusAsync
  * Removed Function GetUsersPriceLevelsAsync
  * Removed Function PerformBulkPurchase
  * Removed Function PerformCancelSubscription
  * Removed Function PerformPurchaseV2
  * Removed Function PerformSubscriptionPurchase
  * Removed Function PerformSubscriptionPurchaseV2
  * Removed Function PerformSubscriptionPurchaseV3Async
  * Removed Function PerformSubscriptionPurchaseWithRobuxAsync
  * Removed Function PlayerOwnsAssetAsync
  * Removed Function PlayerOwnsBundle
  * Removed Function PlayerOwnsBundleAsync
  * Removed Function PromptRobuxTransferAsync
  * Removed Function RankProductsAsync
  * Removed Function RecommendTopProductsAsync
  * Removed Event NativePurchaseFinishedV2
  * Removed Event NativePurchaseFinishedWithLocalPlayer
  * Removed Event NativePurchaseFinishedWithLocalPlayerV2
  * Removed Event OpenShopRequested
  * Removed Event PrepareCollectiblesPurchaseRequested
  * Removed Event PromptBulkPurchaseFinished
  * Removed Event PromptBulkPurchaseRequested
  * Removed Event PromptBulkPurchaseRequestedV2
  * Removed Event PromptCancelSubscriptionRequested
  * Removed Event PromptCollectibleBundlePurchaseRequested
  * Removed Event PromptCollectiblesPurchaseRequested
  * Removed Event PromptPurchaseRequestedV2
  * Removed Event PromptRobloxSubscriptionPurchaseFinished
  * Removed Event PromptRobloxSubscriptionPurchaseRequested
  * Removed Event PromptRobuxTransferRequested
  * Removed Event PromptRobuxTransferSubscriptionUpsellRequested
  * Removed Event RobuxTransferCompleted
  * Removed Event UserSubscriptionStatusChanged
* Update Class [MemStorageConnection](https://create.roblox.com/docs/reference/engine/classes/MemStorageConnection) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [Disconnect](https://create.roblox.com/docs/reference/engine/classes/MemStorageConnection#Disconnect) from null to void [🔒 PluginSecurity]
* Update Class [MemStorageService](https://create.roblox.com/docs/reference/engine/classes/MemStorageService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [Fire](https://create.roblox.com/docs/reference/engine/classes/MemStorageService#Fire) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetItem](https://create.roblox.com/docs/reference/engine/classes/MemStorageService#SetItem) from null to void [🔒 RobloxScriptSecurity]
* Update Class [MemoryStoreQueue](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [AddAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue#AddAsync) from null to void [🏷️ Yields]
  * Changed the return-type of Function [RemoveAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue#RemoveAsync) from null to void [🏷️ Yields]
  * Removed Function GetSizeAsync
* Update Class [MemoryStoreService](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreService) [🏷️ Service]
  * Removed Function GetHashMap
* Update Class [MemoryStoreSortedMap](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [GetAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#GetAsync) from Tuple to Variant [🏷️ Yields]
  * Changed the parameters of Function [GetRangeAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#GetRangeAsync)
    from: (direction: SortDirection, count: int, exclusiveLowerBound: Variant, exclusiveUpperBound: Variant)
    to: (direction: SortDirection, count: int, exclusiveLowerBound: string = , exclusiveUpperBound: string = ) [🏷️ Yields]
  * Changed the return-type of Function [RemoveAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#RemoveAsync) from null to void [🏷️ Yields]
  * Changed the parameters of Function [SetAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#SetAsync)
    from: (key: string, value: Variant, expiration: int64, sortKey: Variant)
    to: (key: string, value: Variant, expiration: int64) [🏷️ Yields]
  * Changed the return-type of Function [UpdateAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#UpdateAsync) from Tuple to Variant [🏷️ Yields]
  * Removed Function GetSizeAsync
* Update Class [MessageBusConnection](https://create.roblox.com/docs/reference/engine/classes/MessageBusConnection) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [Disconnect](https://create.roblox.com/docs/reference/engine/classes/MessageBusConnection#Disconnect) from null to void [🔒 RobloxScriptSecurity]
* Update Class [MessageBusService](https://create.roblox.com/docs/reference/engine/classes/MessageBusService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [Publish](https://create.roblox.com/docs/reference/engine/classes/MessageBusService#Publish) from null to void [🔒 RobloxScriptSecurity]
  * Removed Function GetProtocolMethodRequestMessageId
  * Removed Function GetProtocolMethodResponseMessageId
  * Removed Function MakeRequest
  * Removed Function PublishProtocolMethodRequest
  * Removed Function PublishProtocolMethodResponse
  * Removed Function SetRequestHandler
  * Removed Function SubscribeToProtocolMethodRequest
  * Removed Function SubscribeToProtocolMethodResponse
* Update Class [MessagingService](https://create.roblox.com/docs/reference/engine/classes/MessagingService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [PublishAsync](https://create.roblox.com/docs/reference/engine/classes/MessagingService#PublishAsync) from null to void [🏷️ Yields]
* Update Class [Mouse](https://create.roblox.com/docs/reference/engine/classes/Mouse) [🏷️ NotCreatable]
  * Changed the ValueType of Property [Icon](https://create.roblox.com/docs/reference/engine/classes/Mouse#Icon) from ContentId to Content
  * Removed Property IconContent
* Update Class [PluginMouse](https://create.roblox.com/docs/reference/engine/classes/PluginMouse) [🏷️ NotCreatable]
  * Changed the parameters of Event [DragEnter](https://create.roblox.com/docs/reference/engine/classes/PluginMouse#DragEnter)
    from: (instances: Instances)
    to: (instances: Objects) [🔒 PluginSecurity]
* Update Class [MouseService](https://create.roblox.com/docs/reference/engine/classes/MouseService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Event MouseEnterStudioViewport
  * Removed Event MouseLeaveStudioViewport
* Update Class [MultipleDocumentInterfaceInstance](https://create.roblox.com/docs/reference/engine/classes/MultipleDocumentInterfaceInstance) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the ValueType of Property [FocusedDataModelSession](https://create.roblox.com/docs/reference/engine/classes/MultipleDocumentInterfaceInstance#FocusedDataModelSession) from DataModelSession to Instance [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated]
* Update Class [NetworkPeer](https://create.roblox.com/docs/reference/engine/classes/NetworkPeer) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the return-type of Function [SetOutgoingKBPSLimit](https://create.roblox.com/docs/reference/engine/classes/NetworkPeer#SetOutgoingKBPSLimit) from null to void [🔒 PluginSecurity]
  * Removed Function InitializeRemoteAllowList
* Update Class [NetworkClient](https://create.roblox.com/docs/reference/engine/classes/NetworkClient) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Event [ConnectionFailed](https://create.roblox.com/docs/reference/engine/classes/NetworkClient#ConnectionFailed)
    from: (peer: string, code: int)
    to: (peer: string, code: int, reason: string)
* Update Class [ClientReplicator](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [RequestRCCProfilerData](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator#RequestRCCProfilerData) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RequestServerStats](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator#RequestServerStats) from null to void [🔒 RobloxScriptSecurity]
  * Removed Function IsStreamedOut
* Update Class [NetworkSettings](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotBrowsable]
  * Add Property [TrackDataTypes](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#TrackDataTypes): bool
  * Add Property [TrackPhysicsDetails](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#TrackPhysicsDetails): bool
  * Removed Property InboundNetworkJitterMs
  * Removed Property InboundNetworkLossPercent
  * Removed Property InboundNetworkMinDelayMs
  * Removed Property OutboundNetworkJitterMs
  * Removed Property OutboundNetworkLossPercent
  * Removed Property OutboundNetworkMinDelayMs
* Update Class [NotificationService](https://create.roblox.com/docs/reference/engine/classes/NotificationService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [ActionEnabled](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ActionEnabled) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ActionTaken](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ActionTaken) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [CancelAllNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#CancelAllNotification) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [CancelNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#CancelNotification) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [ScheduleNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ScheduleNotification) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [SwitchedToAppShellFeature](https://create.roblox.com/docs/reference/engine/classes/NotificationService#SwitchedToAppShellFeature) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property IsConnected
  * Removed Function SubscribeToRccEventNamespace
  * Removed Event RccConnectionChanged
  * Removed Event RccEventReceived
* Update Class [PVInstance](https://create.roblox.com/docs/reference/engine/classes/PVInstance) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Add Property [Origin Orientation](https://create.roblox.com/docs/reference/engine/classes/PVInstance#Origin%20Orientation): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable]
  * Add Property [Origin Position](https://create.roblox.com/docs/reference/engine/classes/PVInstance#Origin%20Position): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable]
  * Add Property [Pivot Offset Orientation](https://create.roblox.com/docs/reference/engine/classes/PVInstance#Pivot%20Offset%20Orientation): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable]
  * Add Property [Pivot Offset Position](https://create.roblox.com/docs/reference/engine/classes/PVInstance#Pivot%20Offset%20Position): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable]
  * Changed the return-type of Function [PivotTo](https://create.roblox.com/docs/reference/engine/classes/PVInstance#PivotTo) from null to void
  * Removed Property Origin
  * Removed Property Pivot Offset
* Update Class [BasePart](https://create.roblox.com/docs/reference/engine/classes/BasePart) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the return-type of Function [ApplyAngularImpulse](https://create.roblox.com/docs/reference/engine/classes/BasePart#ApplyAngularImpulse) from null to void
  * Changed the return-type of Function [ApplyImpulse](https://create.roblox.com/docs/reference/engine/classes/BasePart#ApplyImpulse) from null to void
  * Changed the return-type of Function [ApplyImpulseAtPosition](https://create.roblox.com/docs/reference/engine/classes/BasePart#ApplyImpulseAtPosition) from null to void
  * Changed the return-type of Function [BreakJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#BreakJoints) from null to void
  * Changed the parameters of Function [CanCollideWith](https://create.roblox.com/docs/reference/engine/classes/BasePart#CanCollideWith)
    from: (part: BasePart)
    to: (part: Instance)
  * Changed the return-type of Function [GetConnectedParts](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetConnectedParts) from Instances to Objects
  * Changed the return-type of Function [GetJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetJoints) from Instances to Objects
  * Changed the return-type of Function [GetTouchingParts](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetTouchingParts) from Instances to Objects
  * Changed the return-type of Function [MakeJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#MakeJoints) from null to void
  * Changed the return-type of Function [SetNetworkOwner](https://create.roblox.com/docs/reference/engine/classes/BasePart#SetNetworkOwner) from null to void
  * Changed the return-type of Function [SetNetworkOwnershipAuto](https://create.roblox.com/docs/reference/engine/classes/BasePart#SetNetworkOwnershipAuto) from null to void
  * Changed the return-type of Function [breakJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#breakJoints) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [makeJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#makeJoints) from null to void [🏷️ Deprecated]
  * Changed the parameters of Function [SubtractAsync](https://create.roblox.com/docs/reference/engine/classes/BasePart#SubtractAsync)
    from: (parts: Instances, collisionfidelity: CollisionFidelity = Default, renderFidelity: RenderFidelity = Automatic)
    to: (parts: Objects, collisionfidelity: CollisionFidelity = Default, renderFidelity: RenderFidelity = Automatic) [🏷️ Yields]
  * Changed the parameters of Function [UnionAsync](https://create.roblox.com/docs/reference/engine/classes/BasePart#UnionAsync)
    from: (parts: Instances, collisionfidelity: CollisionFidelity = Default, renderFidelity: RenderFidelity = Automatic)
    to: (parts: Objects, collisionfidelity: CollisionFidelity = Default, renderFidelity: RenderFidelity = Automatic) [🏷️ Yields]
  * Removed Property AudioCanCollide
  * Removed Property CollisionGroup
  * Removed Property CurrentPhysicalProperties
  * Removed Property EnableFluidForces
  * Removed Property ExtentsCFrame
  * Removed Property ExtentsSize
  * Removed Property MaterialVariant
  * Removed Function AngularAccelerationToTorque
  * Removed Function GetClosestPointOnSurface
  * Removed Function GetNoCollisionConstraints
  * Removed Function GetPhysicsCost
  * Removed Function TorqueToAngularAcceleration
  * Removed Function IntersectAsync
* Update Class [Seat](https://create.roblox.com/docs/reference/engine/classes/Seat)
  * Changed the return-type of Function [Sit](https://create.roblox.com/docs/reference/engine/classes/Seat#Sit) from null to void
* Update Class [SkateboardPlatform](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform) [🏷️ Deprecated]
  * Changed the return-type of Function [ApplySpecificImpulse](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#ApplySpecificImpulse) from null to void
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [🏷️ NotCreatable]
  * Changed the return-type of Function [AutowedgeCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#AutowedgeCells) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Clear](https://create.roblox.com/docs/reference/engine/classes/Terrain#Clear) from null to void
  * Changed the return-type of Function [ConvertToSmooth](https://create.roblox.com/docs/reference/engine/classes/Terrain#ConvertToSmooth) from null to void [🔒 PluginSecurity] [🏷️ Deprecated]
  * Changed the return-type of Function [CopyRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#CopyRegion) from TerrainRegion to Instance
  * Changed the return-type of Function [FillBall](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillBall) from null to void
  * Changed the return-type of Function [FillBlock](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillBlock) from null to void
  * Changed the return-type of Function [FillCylinder](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillCylinder) from null to void
  * Changed the return-type of Function [FillRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillRegion) from null to void
  * Changed the return-type of Function [FillWedge](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillWedge) from null to void
  * Changed the return-type of Function [PasteRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#PasteRegion) from null to void
  * Changed the parameters of Function [PasteRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#PasteRegion)
    from: (region: TerrainRegion, corner: Vector3int16, pasteEmptyCells: bool)
    to: (region: Instance, corner: Vector3int16, pasteEmptyCells: bool)
  * Changed the return-type of Function [ReplaceMaterial](https://create.roblox.com/docs/reference/engine/classes/Terrain#ReplaceMaterial) from null to void
  * Changed the return-type of Function [SetCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetCell) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetCells) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetMaterialColor](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetMaterialColor) from null to void
  * Changed the return-type of Function [SetWaterCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetWaterCell) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [WriteVoxels](https://create.roblox.com/docs/reference/engine/classes/Terrain#WriteVoxels) from null to void [🏷️ CustomLuaState]
  * Removed Property GrassLength
  * Removed Property SmoothVoxelsUpgraded
  * Removed Function CanSmoothVoxelsBeUpgraded
  * Removed Function ClearVoxelsAsync_beta
  * Removed Function CreateVoxelBuffer_beta
  * Removed Function FillBallSlot
  * Removed Function FillBlockSlot
  * Removed Function FillCylinderSlot
  * Removed Function FillRegionSlot
  * Removed Function FillWedgeSlot
  * Removed Function GetMaterialSlot
  * Removed Function GetTerrainWireframe
  * Removed Function IterateVoxelsAsync_beta
  * Removed Function ModifyVoxelsAsync_beta
  * Removed Function ReadVoxelChannels
  * Removed Function ReadVoxelsAsync_beta
  * Removed Function ReplaceMaterialInTransform
  * Removed Function ReplaceMaterialInTransformSubregion
  * Removed Function ResetMaterialSlot
  * Removed Function SetMaterialInTransform
  * Removed Function SetMaterialInTransformSubregion
  * Removed Function SetMaterialSlot
  * Removed Function SmoothRegion
  * Removed Function WriteVoxelChannels
  * Removed Function WriteVoxelsAsync_beta
  * Removed Function DrawBufferAsync
  * Removed Function ReadBufferAsync
* Update Class [TriangleMeshPart](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart) [🏷️ NotCreatable]
  * Removed Property FluidFidelity
  * Removed Property MeshSize
  * Removed Property UnscaledCofm
  * Removed Property UnscaledVolInertiaDiags
  * Removed Property UnscaledVolInertiaOffDiags
  * Removed Property UnscaledVolume
* Update Class [MeshPart](https://create.roblox.com/docs/reference/engine/classes/MeshPart)
  * Add Property [MeshID](https://create.roblox.com/docs/reference/engine/classes/MeshPart#MeshID): Content [🏷️ NotScriptable] [🏷️ Deprecated]
  * Changed the ValueType of Property [MeshId](https://create.roblox.com/docs/reference/engine/classes/MeshPart#MeshId) from ContentId to Content [🔒 Read:None, Write:NotAccessibleSecurity]
  * Add Property [MeshSize](https://create.roblox.com/docs/reference/engine/classes/MeshPart#MeshSize): Vector3 [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Changed the ValueType of Property [TextureID](https://create.roblox.com/docs/reference/engine/classes/MeshPart#TextureID) from ContentId to Content
  * Changed the return-type of Function [ApplyMesh](https://create.roblox.com/docs/reference/engine/classes/MeshPart#ApplyMesh) from null to void
  * Removed Property MeshContent
  * Removed Property TextureContent
* Update Class [PartOperation](https://create.roblox.com/docs/reference/engine/classes/PartOperation)
  * Removed Function SubstituteGeometry
* Update Class [VehicleSeat](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat)
  * Changed the return-type of Function [Sit](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#Sit) from null to void
* Update Class [Model](https://create.roblox.com/docs/reference/engine/classes/Model)
  * Add Property [World Pivot Orientation](https://create.roblox.com/docs/reference/engine/classes/Model#World%20Pivot%20Orientation): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable]
  * Add Property [World Pivot Position](https://create.roblox.com/docs/reference/engine/classes/Model#World%20Pivot%20Position): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable]
  * Changed the return-type of Function [BreakJoints](https://create.roblox.com/docs/reference/engine/classes/Model#BreakJoints) from null to void
  * Changed the return-type of Function [GetBoundingBox](https://create.roblox.com/docs/reference/engine/classes/Model#GetBoundingBox) from any to Tuple
  * Changed the return-type of Function [MakeJoints](https://create.roblox.com/docs/reference/engine/classes/Model#MakeJoints) from null to void
  * Changed the return-type of Function [MoveTo](https://create.roblox.com/docs/reference/engine/classes/Model#MoveTo) from null to void
  * Changed the return-type of Function [ResetOrientationToIdentity](https://create.roblox.com/docs/reference/engine/classes/Model#ResetOrientationToIdentity) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetIdentityOrientation](https://create.roblox.com/docs/reference/engine/classes/Model#SetIdentityOrientation) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetPrimaryPartCFrame](https://create.roblox.com/docs/reference/engine/classes/Model#SetPrimaryPartCFrame) from null to void
  * Changed the return-type of Function [TranslateBy](https://create.roblox.com/docs/reference/engine/classes/Model#TranslateBy) from null to void
  * Changed the return-type of Function [breakJoints](https://create.roblox.com/docs/reference/engine/classes/Model#breakJoints) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [makeJoints](https://create.roblox.com/docs/reference/engine/classes/Model#makeJoints) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [move](https://create.roblox.com/docs/reference/engine/classes/Model#move) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [moveTo](https://create.roblox.com/docs/reference/engine/classes/Model#moveTo) from null to void [🏷️ Deprecated]
  * Removed Property ModelStreamingMode
  * Removed Property Scale
  * Removed Function AddPersistentPlayer
  * Removed Function GetPersistentPlayers
  * Removed Function GetScale
  * Removed Function RemovePersistentPlayer
  * Removed Function ScaleTo
* Update Class [Actor](https://create.roblox.com/docs/reference/engine/classes/Actor)
  * Removed Function BindToMessage
  * Removed Function BindToMessageParallel
  * Removed Function SendMessage
* Update Class [WorldRoot](https://create.roblox.com/docs/reference/engine/classes/WorldRoot) [🏷️ NotCreatable]
  * Changed the parameters of Function [ArePartsTouchingOthers](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#ArePartsTouchingOthers)
    from: (partList: Instances, overlapIgnored: float = 0.000199999995)
    to: (partList: Objects, overlapIgnored: float = 0.000199999995)
  * Changed the return-type of Function [BulkMoveTo](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#BulkMoveTo) from null to void
  * Changed the parameters of Function [BulkMoveTo](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#BulkMoveTo)
    from: (partList: Instances, cframeList: Array, eventMode: BulkMoveMode = FireAllEvents)
    to: (partList: Objects, cframeList: Array, eventMode: BulkMoveMode = FireAllEvents)
  * Changed the parameters of Function [FindPartOnRayWithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartOnRayWithIgnoreList)
    from: (ray: Ray, ignoreDescendantsTable: Instances, terrainCellsAreCubes: bool = false, ignoreWater: bool = false)
    to: (ray: Ray, ignoreDescendantsTable: Objects, terrainCellsAreCubes: bool = false, ignoreWater: bool = false) [🏷️ Deprecated]
  * Changed the parameters of Function [FindPartOnRayWithWhitelist](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartOnRayWithWhitelist)
    from: (ray: Ray, whitelistDescendantsTable: Instances, ignoreWater: bool = false)
    to: (ray: Ray, whitelistDescendantsTable: Objects, ignoreWater: bool = false) [🏷️ Deprecated]
  * Changed the return-type of Function [FindPartsInRegion3](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3) from Instances to Objects
  * Changed the return-type of Function [FindPartsInRegion3WithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithIgnoreList) from Instances to Objects
  * Changed the parameters of Function [FindPartsInRegion3WithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithIgnoreList)
    from: (region: Region3, ignoreDescendantsTable: Instances, maxParts: int = 20)
    to: (region: Region3, ignoreDescendantsTable: Objects, maxParts: int = 20)
  * Changed the return-type of Function [FindPartsInRegion3WithWhiteList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithWhiteList) from Instances to Objects
  * Changed the parameters of Function [FindPartsInRegion3WithWhiteList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithWhiteList)
    from: (region: Region3, whitelistDescendantsTable: Instances, maxParts: int = 20)
    to: (region: Region3, whitelistDescendantsTable: Objects, maxParts: int = 20)
  * Changed the return-type of Function [GetPartBoundsInBox](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox) from Instances to Objects
  * Changed the parameters of Function [GetPartBoundsInBox](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox)
    from: (cframe: CFrame, size: Vector3, overlapParams: OverlapParams = OverlapParams{MaxParts=0, Tolerance=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (cframe: CFrame, size: Vector3, overlapParams: OverlapParams = OverlapParams{MaxParts=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed the return-type of Function [GetPartBoundsInRadius](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInRadius) from Instances to Objects
  * Changed the parameters of Function [GetPartBoundsInRadius](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInRadius)
    from: (position: Vector3, radius: float, overlapParams: OverlapParams = OverlapParams{MaxParts=0, Tolerance=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (position: Vector3, radius: float, overlapParams: OverlapParams = OverlapParams{MaxParts=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed the return-type of Function [GetPartsInPart](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartsInPart) from Instances to Objects
  * Changed the parameters of Function [GetPartsInPart](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartsInPart)
    from: (part: BasePart, overlapParams: OverlapParams = OverlapParams{MaxParts=0, Tolerance=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (part: BasePart, overlapParams: OverlapParams = OverlapParams{MaxParts=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed the return-type of Function [IKMoveTo](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#IKMoveTo) from null to void [🔒 PluginSecurity]
  * Changed the parameters of Function [IsRegion3EmptyWithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#IsRegion3EmptyWithIgnoreList)
    from: (region: Region3, ignoreDescendentsTable: Instances)
    to: (region: Region3, ignoreDescendentsTable: Objects)
  * Changed the return-type of Function [Raycast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Raycast) from RaycastResult? to RaycastResult
  * Changed the parameters of Function [Raycast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Raycast)
    from: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed the return-type of Function [SetInsertPoint](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#SetInsertPoint) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [SetInsertPoint](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#SetInsertPoint)
    from: (point: Vector3)
    to: (point: Vector3, ignoreGrid: bool = false) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [findPartsInRegion3](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#findPartsInRegion3) from Instances to Objects [🏷️ Deprecated]
  * Removed Property PhysicsStepTime
  * Removed Function Blockcast
  * Removed Function CacheCurrentTerrain
  * Removed Function ClearCachedTerrain
  * Removed Function GetAwakeContactNormals
  * Removed Function GetAwakeContactParts
  * Removed Function GetAwakeContactPositions
  * Removed Function GetAwakeRootParts
  * Removed Function RaycastCachedTerrain
  * Removed Function Shapecast
  * Removed Function Spherecast
  * Removed Function StepPhysics
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [🏷️ NotCreatable] [🏷️ Service]
  * Add Property [AnimationWeightedBlendFix](https://create.roblox.com/docs/reference/engine/classes/Workspace#AnimationWeightedBlendFix): NewAnimationRuntimeSetting [🏷️ NotScriptable]
  * Add Property [HumanoidOnlySetCollisionsOnStateChange](https://create.roblox.com/docs/reference/engine/classes/Workspace#HumanoidOnlySetCollisionsOnStateChange): HumanoidOnlySetCollisionsOnStateChange [🏷️ NotScriptable]
  * Add Property [PhysicsSimulationRate](https://create.roblox.com/docs/reference/engine/classes/Workspace#PhysicsSimulationRate): PhysicsSimulationRate [🏷️ Hidden] [🏷️ NotReplicated]
  * Add Property [StreamingPauseMode](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamingPauseMode): StreamingPauseMode [🏷️ NotScriptable]
  * Changed the return-type of Function [BreakJoints](https://create.roblox.com/docs/reference/engine/classes/Workspace#BreakJoints) from null to void [🔒 PluginSecurity]
  * Changed the parameters of Function [BreakJoints](https://create.roblox.com/docs/reference/engine/classes/Workspace#BreakJoints)
    from: (objects: Instances)
    to: (objects: Objects) [🔒 PluginSecurity]
  * Changed the return-type of Function [JoinToOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#JoinToOutsiders) from null to void
  * Changed the parameters of Function [JoinToOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#JoinToOutsiders)
    from: (objects: Instances, jointType: JointCreationMode)
    to: (objects: Objects, jointType: JointCreationMode)
  * Changed the return-type of Function [MakeJoints](https://create.roblox.com/docs/reference/engine/classes/Workspace#MakeJoints) from null to void [🔒 PluginSecurity]
  * Changed the parameters of Function [MakeJoints](https://create.roblox.com/docs/reference/engine/classes/Workspace#MakeJoints)
    from: (objects: Instances)
    to: (objects: Objects) [🔒 PluginSecurity]
  * Changed the return-type of Function [SetMeshPartHeadsAndAccessories](https://create.roblox.com/docs/reference/engine/classes/Workspace#SetMeshPartHeadsAndAccessories) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetPhysicsThrottleEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#SetPhysicsThrottleEnabled) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [UnjoinFromOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#UnjoinFromOutsiders) from null to void
  * Changed the parameters of Function [UnjoinFromOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#UnjoinFromOutsiders)
    from: (objects: Instances)
    to: (objects: Objects)
  * Changed the return-type of Function [ZoomToExtents](https://create.roblox.com/docs/reference/engine/classes/Workspace#ZoomToExtents) from null to void [🔒 PluginSecurity]
  * Removed Property AirDensity
  * Removed Property AirTurbulenceIntensity
  * Removed Property AuthorityMode
  * Removed Property AvatarUnificationMode
  * Removed Property EnableSLIMAvatars
  * Removed Property FallHeightEnabled
  * Removed Property FluidForces
  * Removed Property GlobalWind
  * Removed Property IKControlConstraintSupport
  * Removed Property ImprovedAnimationConstraint
  * Removed Property ImprovedPhysicsReplication
  * Removed Property InsertPoint
  * Removed Property LayeredClothingCacheOptimizations
  * Removed Property LuauTypeCheckMode
  * Removed Property MeshStreamingAndImprovedLods
  * Removed Property ModelStreamingBehavior
  * Removed Property NextGenerationReplication
  * Removed Property NextGenerationReplicationAlias
  * Removed Property PathfindingUseImprovedSearch
  * Removed Property PlayerCharacterDestroyBehavior
  * Removed Property PlayerScriptsUseInputActionSystem
  * Removed Property PlayerScriptsUseInputActionSystemAlias
  * Removed Property PredictiveStreamingMode
  * Removed Property PrimalPhysicsSolver
  * Removed Property RejectCharacterDeletions
  * Removed Property RenderingCacheOptimizations
  * Removed Property ReplicateInstanceDestroySetting
  * Removed Property Retargeting
  * Removed Property SandboxedInstanceMode
  * Removed Property SignalBehaviorAlias
  * Removed Property StreamingEnabledAlias
  * Removed Property StreamingIntegrityMode
  * Removed Property TouchEventsUseCollisionGroups
  * Removed Property UseFixedSimulation
  * Removed Property UseFixedSimulationAlias
  * Removed Property UseNewLuauTypeSolver
  * Removed Property ValidateEnabledProximityPrompt
  * Removed Function ApplyRecommendedStreamingSettings
  * Removed Function SetAvatarUnificationMode
  * Removed Event PersistentLoaded
* Update Class [WorldModel](https://create.roblox.com/docs/reference/engine/classes/WorldModel)
  * Removed Property UseWorkspaceCollisionGroups
* Update Class [PackageLink](https://create.roblox.com/docs/reference/engine/classes/PackageLink) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the ValueType of Property [PackageId](https://create.roblox.com/docs/reference/engine/classes/PackageLink#PackageId) from ContentId to Content [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Removed Property DefaultName
  * Removed Property HasNewVersion
  * Removed Property ModifiedState
  * Removed Property PackageContent
  * Removed Property SerializedDefaultAttributes
* Update Class [PackageService](https://create.roblox.com/docs/reference/engine/classes/PackageService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function UpdateAsync
* Update Class [Pages](https://create.roblox.com/docs/reference/engine/classes/Pages) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [AdvanceToNextPageAsync](https://create.roblox.com/docs/reference/engine/classes/Pages#AdvanceToNextPageAsync) from null to void [🏷️ Yields]
* Update Class [DataStoreKeyPages](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyPages) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Property Cursor
* Update Class [DataStoreListingPages](https://create.roblox.com/docs/reference/engine/classes/DataStoreListingPages) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Property Cursor
* Add Class [EmotesPages](https://create.roblox.com/docs/reference/engine/classes/EmotesPages) [🏷️ NotCreatable] [🏷️ NotReplicated]
* Update Class [ParticleEmitter](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter)
  * Changed the ValueType of Property [Texture](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Texture) from ContentId to Content
  * Changed the return-type of Function [Clear](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Clear) from null to void
  * Changed the return-type of Function [Emit](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Emit) from null to void
  * Removed Property Brightness
  * Removed Property FlipbookBlendFrames
  * Removed Property FlipbookFramerate
  * Removed Property FlipbookIncompatible
  * Removed Property FlipbookLayout
  * Removed Property FlipbookMode
  * Removed Property FlipbookSizeX
  * Removed Property FlipbookSizeY
  * Removed Property FlipbookStartRandom
  * Removed Property LocalTransparencyModifier
  * Removed Property Shape
  * Removed Property ShapeInOut
  * Removed Property ShapePartial
  * Removed Property ShapeStyle
  * Removed Property Squash
  * Removed Property TextureContent
  * Removed Property WindAffectsDrag
  * Removed Function FastForward
* Update Class [Path](https://create.roblox.com/docs/reference/engine/classes/Path) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [ComputeAsync](https://create.roblox.com/docs/reference/engine/classes/Path#ComputeAsync) from null to void [🏷️ Yields]
* Update Class [PathfindingModifier](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier)
  * Add Property [ModifierId](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier#ModifierId): string
  * Removed Property Label
* Update Class [PathfindingService](https://create.roblox.com/docs/reference/engine/classes/PathfindingService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [CreatePath](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#CreatePath) from Path to Instance
  * Changed the return-type of Function [ComputeRawPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#ComputeRawPathAsync) from Path to Instance [🏷️ Yields] [🏷️ Deprecated]
  * Changed the return-type of Function [ComputeSmoothPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#ComputeSmoothPathAsync) from Path to Instance [🏷️ Yields] [🏷️ Deprecated]
  * Changed the return-type of Function [FindPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#FindPathAsync) from Path to Instance [🏷️ Yields]
* Update Class [PausedState](https://create.roblox.com/docs/reference/engine/classes/PausedState) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Add Property [IsValid](https://create.roblox.com/docs/reference/engine/classes/PausedState#IsValid): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [ThreadCount](https://create.roblox.com/docs/reference/engine/classes/PausedState#ThreadCount): int [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Function [GetThread](https://create.roblox.com/docs/reference/engine/classes/PausedState#GetThread) (index: int) -> Instance [🔒 RobloxScriptSecurity]
  * Removed Property AllThreadsPaused
  * Removed Property ThreadId
* Update Class [PausedStateBreakpoint](https://create.roblox.com/docs/reference/engine/classes/PausedStateBreakpoint) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Add Property [BreakpointThread](https://create.roblox.com/docs/reference/engine/classes/PausedStateBreakpoint#BreakpointThread): ThreadState [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated]
* Update Class [PausedStateException](https://create.roblox.com/docs/reference/engine/classes/PausedStateException) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Add Property [ExceptionThread](https://create.roblox.com/docs/reference/engine/classes/PausedStateException#ExceptionThread): ThreadState [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated]
* Update Class [PermissionsService](https://create.roblox.com/docs/reference/engine/classes/PermissionsService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [SetPermissions](https://create.roblox.com/docs/reference/engine/classes/PermissionsService#SetPermissions) from null to void [🔒 RobloxScriptSecurity]
* Update Class [PhysicsService](https://create.roblox.com/docs/reference/engine/classes/PhysicsService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [CollisionGroupSetCollidable](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#CollisionGroupSetCollidable) from null to void
  * Changed the return-type of Function [IkSolve](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#IkSolve) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [LocalIkSolve](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#LocalIkSolve) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [RemoveCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#RemoveCollisionGroup) from null to void
  * Changed the return-type of Function [RenameCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#RenameCollisionGroup) from null to void
  * Changed the return-type of Function [SetPartCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#SetPartCollisionGroup) from null to void
  * Removed Function GetRegisteredCollisionGroups
  * Removed Function IsCollisionGroupRegistered
  * Removed Function RegisterCollisionGroup
  * Removed Function UnregisterCollisionGroup
* Update Class [PhysicsSettings](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings) [🏷️ NotCreatable] [🏷️ Settings]
  * Removed Property AreAssemblyCentersOfMassShown
  * Removed Property AreCollisionCostsShown
  * Removed Property AreConstraintForcesShownForSelectedOrHoveredInstances
  * Removed Property AreConstraintTorquesShownForSelectedOrHoveredInstances
  * Removed Property AreContactForcesShownForSelectedOrHoveredAssemblies
  * Removed Property AreGravityForcesShownForSelectedOrHoveredAssemblies
  * Removed Property AreMagnitudesShownForDrawnForcesAndTorques
  * Removed Property AreNonAnchorsShown
  * Removed Property AreSolverIslandsShown
  * Removed Property DisableCSGv3ForPlugins
  * Removed Property DrawConstraintsNetForce
  * Removed Property DrawContactsNetForce
  * Removed Property DrawTotalNetForce
  * Removed Property EnableForceVisualizationSmoothing
  * Removed Property FluidForceDrawScale
  * Removed Property ForceDrawScale
  * Removed Property ForceVisualizationSmoothingSteps
  * Removed Property ShowFluidForcesForSelectedOrHoveredMechanisms
  * Removed Property ShowInstanceNamesForDrawnForcesAndTorques
  * Removed Property SolverConvergenceMetricType
  * Removed Property SolverConvergenceVisualizationMode
  * Removed Property TorqueDrawScale
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player)
  * Changed the return-type of Function [AddToBlockList](https://create.roblox.com/docs/reference/engine/classes/Player#AddToBlockList) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ClearCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#ClearCharacterAppearance) from null to void
  * Add Function [IsUserAvailableForExperiment](https://create.roblox.com/docs/reference/engine/classes/Player#IsUserAvailableForExperiment) () -> bool [🏷️ Deprecated]
  * Changed the return-type of Function [Kick](https://create.roblox.com/docs/reference/engine/classes/Player#Kick) from null to void
  * Changed the return-type of Function [LoadCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterAppearance) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [LoadData](https://create.roblox.com/docs/reference/engine/classes/Player#LoadData) from null to void [🔒 LocalUserSecurity] [🏷️ Deprecated]
  * Changed the return-type of Function [Move](https://create.roblox.com/docs/reference/engine/classes/Player#Move) from null to void
  * Changed the return-type of Function [RemoveCharacter](https://create.roblox.com/docs/reference/engine/classes/Player#RemoveCharacter) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [RequestFriendship](https://create.roblox.com/docs/reference/engine/classes/Player#RequestFriendship) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RevokeFriendship](https://create.roblox.com/docs/reference/engine/classes/Player#RevokeFriendship) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SaveBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#SaveBoolean) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SaveData](https://create.roblox.com/docs/reference/engine/classes/Player#SaveData) from null to void [🔒 LocalUserSecurity] [🏷️ Deprecated]
  * Changed the return-type of Function [SaveInstance](https://create.roblox.com/docs/reference/engine/classes/Player#SaveInstance) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SaveNumber](https://create.roblox.com/docs/reference/engine/classes/Player#SaveNumber) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SaveString](https://create.roblox.com/docs/reference/engine/classes/Player#SaveString) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetAccountAge](https://create.roblox.com/docs/reference/engine/classes/Player#SetAccountAge) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [SetCharacterAppearanceJson](https://create.roblox.com/docs/reference/engine/classes/Player#SetCharacterAppearanceJson) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetMembershipType](https://create.roblox.com/docs/reference/engine/classes/Player#SetMembershipType) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetSuperSafeChat](https://create.roblox.com/docs/reference/engine/classes/Player#SetSuperSafeChat) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [SetUnder13](https://create.roblox.com/docs/reference/engine/classes/Player#SetUnder13) from null to void [🔒 RobloxSecurity] [🏷️ Deprecated]
  * Changed the return-type of Function [UpdatePlayerBlocked](https://create.roblox.com/docs/reference/engine/classes/Player#UpdatePlayerBlocked) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [saveBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#saveBoolean) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [saveInstance](https://create.roblox.com/docs/reference/engine/classes/Player#saveInstance) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [saveNumber](https://create.roblox.com/docs/reference/engine/classes/Player#saveNumber) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [saveString](https://create.roblox.com/docs/reference/engine/classes/Player#saveString) from null to void [🏷️ Deprecated]
  * Changed the parameters of Function [IsBestFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#IsBestFriendsWith)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields] [🏷️ Deprecated]
  * Changed the parameters of Function [IsFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#IsFriendsWith)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the return-type of Function [LoadCharacter](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacter) from null to void [🏷️ Yields]
  * Changed the return-type of Function [LoadCharacterBlocking](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterBlocking) from null to void [🔒 LocalUserSecurity] [🏷️ Yields]
  * Changed the return-type of Function [LoadCharacterWithHumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithHumanoidDescription) from null to void [🏷️ Yields]
  * Changed the parameters of Function [LoadCharacterWithHumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithHumanoidDescription)
    from: (humanoidDescription: HumanoidDescription, assetTypeVerification: AssetTypeVerification = Default)
    to: (humanoidDescription: HumanoidDescription) [🏷️ Yields]
  * Changed the return-type of Function [RequestStreamAroundAsync](https://create.roblox.com/docs/reference/engine/classes/Player#RequestStreamAroundAsync) from null to void [🏷️ Yields]
  * Changed the parameters of Function [isFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#isFriendsWith)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields] [🏷️ Deprecated]
  * Removed Property AgeChecked
  * Removed Property ChatAvailabilityStatus
  * Removed Property HasRobloxSubscription
  * Removed Property HasVerifiedBadge
  * Removed Property InputLatency
  * Removed Property PartyId
  * Removed Property StepIdOffset
  * Removed Property ThirdPartyTextChatRestrictionStatus
  * Removed Property UnfilteredChat
  * Removed Property User
  * Removed Property VREnabled
  * Removed Property VoiceChatVolume
  * Removed Function AddReplicationFocus
  * Removed Function AddReplicationFocusPosition
  * Removed Function ClearCachedAvatarAppearance
  * Removed Function GetBlockListInitialized
  * Removed Function GetCameraState
  * Removed Function GetData
  * Removed Function GetSeatRequested
  * Removed Function GetToolRequested
  * Removed Function HasBlockedPlayer
  * Removed Function IsVerified
  * Removed Function NotifyAgeCheckPassed
  * Removed Function OverrideStreamingRadii
  * Removed Function PinStreamingForInstance
  * Removed Function PinStreamingForInstanceByUniqueId
  * Removed Function PromptAgeCheck
  * Removed Function RemoveReplicationFocus
  * Removed Function RemoveReplicationFocusPosition
  * Removed Function RequestSeat
  * Removed Function RequestTool
  * Removed Function SetBlockListInitialized
  * Removed Function SetChatTranslationSettingsLocaleId
  * Removed Function SetExperienceSettingsLocaleId
  * Removed Function SetHasRobloxSubscription
  * Removed Function SetModerationAccessKey
  * Removed Function UnpinStreamingForInstance
  * Removed Function GetCanManageAsync
  * Removed Function GetFriendsOnlineAsync
  * Removed Function GetFriendsWhoPlayedAsync
  * Removed Function GetRankInGroupAsync
  * Removed Function GetRoleInGroupAsync
  * Removed Function IsFriendsWithAsync
  * Removed Function IsInGroupAsync
  * Removed Function LoadCharacterAsync
  * Removed Function LoadCharacterWithAvatarRules
  * Removed Function LoadCharacterWithHumanoidDescriptionAsync
  * Removed Function PromptSecurityChallengeAsync
  * Removed Event BlockListChanged
  * Removed Event CloudEditSelectionChanged
  * Removed Event InstancePinned
  * Removed Event InstanceUnpinned
  * Removed Event StreamingPinComplete
* Update Class [PlayerEmulatorService](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService) [🏷️ NotCreatable] [🏷️ Service]
  * Add Property [DEPRECATED_SerializedEmulatedPolicyInfo](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#DEPRECATED_SerializedEmulatedPolicyInfo): string [🔒 RobloxScriptSecurity] [🏷️ Hidden]
  * Add Property [PlayerEmulationEnabled_deprecated](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#PlayerEmulationEnabled_deprecated): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
  * Add Property [StudioEmulatedCountryRegionCode](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#StudioEmulatedCountryRegionCode): string [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
  * Changed the return-type of Function [SetEmulatedPolicyInfo](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#SetEmulatedPolicyInfo) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property PseudolocalizationEnabled
  * Removed Property TextElongationFactor
  * Removed Function RegionCodeWillHaveAutomaticNonCustomPolicies
* Update Class [PlayerScripts](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [ClearComputerCameraMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearComputerCameraMovementModes) from null to void
  * Changed the return-type of Function [ClearComputerMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearComputerMovementModes) from null to void
  * Changed the return-type of Function [ClearTouchCameraMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearTouchCameraMovementModes) from null to void
  * Changed the return-type of Function [ClearTouchMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearTouchMovementModes) from null to void
  * Changed the return-type of Function [RegisterComputerCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterComputerCameraMovementMode) from null to void
  * Changed the return-type of Function [RegisterComputerMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterComputerMovementMode) from null to void
  * Changed the return-type of Function [RegisterTouchCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterTouchCameraMovementMode) from null to void
  * Changed the return-type of Function [RegisterTouchMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterTouchMovementMode) from null to void
* Update Class [Players](https://create.roblox.com/docs/reference/engine/classes/Players) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [Chat](https://create.roblox.com/docs/reference/engine/classes/Players#Chat) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [CreateLocalPlayer](https://create.roblox.com/docs/reference/engine/classes/Players#CreateLocalPlayer) from Player to Instance [🔒 LocalUserSecurity]
  * Changed the parameters of Function [GetPlayerByUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayerByUserId)
    from: (userId: User)
    to: (userId: int64)
  * Changed the return-type of Function [GetPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayers) from Instances to Objects
  * Changed the return-type of Function [ReportAbuse](https://create.roblox.com/docs/reference/engine/classes/Players#ReportAbuse) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [ReportAbuse](https://create.roblox.com/docs/reference/engine/classes/Players#ReportAbuse)
    from: (player: Player, reason: string, optionalMessage: string)
    to: (player: Instance, reason: string, optionalMessage: string) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [SetChatStyle](https://create.roblox.com/docs/reference/engine/classes/Players#SetChatStyle) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [SetLocalPlayerInfo](https://create.roblox.com/docs/reference/engine/classes/Players#SetLocalPlayerInfo) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [SetLocalPlayerInfo](https://create.roblox.com/docs/reference/engine/classes/Players#SetLocalPlayerInfo)
    from: (userId: int64, userName: string, displayName: string, membershipType: MembershipType, isUnder13: bool, hasRobloxSubscription: bool = false, ageCheckedStatus: AgeCheckStatus = Unchecked)
    to: (userId: int64, userName: string, displayName: string, membershipType: MembershipType, isUnder13: bool) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [TeamChat](https://create.roblox.com/docs/reference/engine/classes/Players#TeamChat) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [WhisperChat](https://create.roblox.com/docs/reference/engine/classes/Players#WhisperChat) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [getPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#getPlayers) from Instances to Objects [🏷️ Deprecated]
  * Changed the return-type of Function [players](https://create.roblox.com/docs/reference/engine/classes/Players#players) from Instances to Objects [🏷️ Deprecated]
  * Changed the return-type of Function [CreateHumanoidModelFromDescription](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromDescription) from Model to Instance [🏷️ Yields]
  * Changed the parameters of Function [CreateHumanoidModelFromDescription](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromDescription)
    from: (description: HumanoidDescription, rigType: HumanoidRigType, assetTypeVerification: AssetTypeVerification = Default)
    to: (description: Instance, rigType: HumanoidRigType, assetTypeVerification: AssetTypeVerification = Default) [🏷️ Yields]
  * Changed the return-type of Function [CreateHumanoidModelFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromUserId) from Model to Instance [🏷️ Yields]
  * Changed the parameters of Function [CreateHumanoidModelFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromUserId)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the return-type of Function [GetCharacterAppearanceAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceAsync) from Model to Instance [🏷️ Yields] [🏷️ Deprecated]
  * Changed the parameters of Function [GetCharacterAppearanceAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceAsync)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields] [🏷️ Deprecated]
  * Changed the parameters of Function [GetCharacterAppearanceInfoAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceInfoAsync)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the return-type of Function [GetFriendsAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetFriendsAsync) from FriendPages to Instance [🏷️ Yields]
  * Changed the parameters of Function [GetFriendsAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetFriendsAsync)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the return-type of Function [GetHumanoidDescriptionFromOutfitId](https://create.roblox.com/docs/reference/engine/classes/Players#GetHumanoidDescriptionFromOutfitId) from HumanoidDescription to Instance [🏷️ Yields]
  * Changed the return-type of Function [GetHumanoidDescriptionFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetHumanoidDescriptionFromUserId) from HumanoidDescription to Instance [🏷️ Yields]
  * Changed the parameters of Function [GetHumanoidDescriptionFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetHumanoidDescriptionFromUserId)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the parameters of Function [GetNameFromUserIdAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetNameFromUserIdAsync)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the parameters of Function [GetUserThumbnailAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetUserThumbnailAsync)
    from: (userId: User, thumbnailType: ThumbnailType, thumbnailSize: ThumbnailSize)
    to: (userId: int64, thumbnailType: ThumbnailType, thumbnailSize: ThumbnailSize) [🏷️ Yields]
  * Add Event [GameAnnounce](https://create.roblox.com/docs/reference/engine/classes/Players#GameAnnounce) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [PlayerChatted](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerChatted)
    from: (chatType: PlayerChatType, player: Player, message: string, targetPlayer: Player)
    to: (chatType: PlayerChatType, player: Instance, message: string, targetPlayer: Instance) [🔒 LocalUserSecurity]
  * Changed the parameters of Event [PlayerConnecting](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerConnecting)
    from: (player: Player)
    to: (player: Instance) [🔒 LocalUserSecurity]
  * Changed the parameters of Event [PlayerDisconnecting](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerDisconnecting)
    from: (player: Player)
    to: (player: Instance) [🔒 LocalUserSecurity]
  * Changed the parameters of Event [PlayerMembershipChanged](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerMembershipChanged)
    from: (player: Player)
    to: (player: Instance)
  * Changed the parameters of Event [PlayerRejoining](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerRejoining)
    from: (player: Player)
    to: (player: Instance) [🔒 LocalUserSecurity]
  * Changed the parameters of Event [PlayerRemoving](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerRemoving)
    from: (player: Player, reason: PlayerExitReason)
    to: (player: Player)
  * Removed Property BanningEnabled
  * Removed Property UseStrafingAnimations
  * Removed Function CreateThumbnailPlayer
  * Removed Function ReportAbuseV3
  * Removed Function ReportAvatarAbuse
  * Removed Function ReportChatAbuse
  * Removed Function ResetLocalPlayer
  * Removed Function BanAsync
  * Removed Function CreateHumanoidModelFromDescriptionAsync
  * Removed Function CreateHumanoidModelFromUserIdAsync
  * Removed Function GetBanHistoryAsync
  * Removed Function GetHumanoidDescriptionFromOutfitIdAsync
  * Removed Function GetHumanoidDescriptionFromUserIdAsync
  * Removed Function GetProfileConfigurationFromUserIdAsync
  * Removed Function UnbanAsync
  * Removed Event PromptAgeCheckRequested
  * Removed Event UserSubscriptionStatusChanged
* Update Class [Plugin](https://create.roblox.com/docs/reference/engine/classes/Plugin) [🏷️ NotCreatable]
  * Changed the return-type of Function [Activate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Activate) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [Deactivate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Deactivate) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [Invoke](https://create.roblox.com/docs/reference/engine/classes/Plugin#Invoke) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [Negate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Negate) from Instances to Objects [🔒 PluginSecurity]
  * Changed the parameters of Function [Negate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Negate)
    from: (objects: Instances)
    to: (objects: Objects) [🔒 PluginSecurity]
  * Changed the return-type of Function [OpenScript](https://create.roblox.com/docs/reference/engine/classes/Plugin#OpenScript) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [OpenWikiPage](https://create.roblox.com/docs/reference/engine/classes/Plugin#OpenWikiPage) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [PauseSound](https://create.roblox.com/docs/reference/engine/classes/Plugin#PauseSound) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PlaySound](https://create.roblox.com/docs/reference/engine/classes/Plugin#PlaySound) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ResumeSound](https://create.roblox.com/docs/reference/engine/classes/Plugin#ResumeSound) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SaveSelectedToRoblox](https://create.roblox.com/docs/reference/engine/classes/Plugin#SaveSelectedToRoblox) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [SelectRibbonTool](https://create.roblox.com/docs/reference/engine/classes/Plugin#SelectRibbonTool) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [Separate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Separate) from Instances to Objects [🔒 PluginSecurity]
  * Changed the parameters of Function [Separate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Separate)
    from: (objects: Instances)
    to: (objects: Objects) [🔒 PluginSecurity]
  * Changed the return-type of Function [SetItem](https://create.roblox.com/docs/reference/engine/classes/Plugin#SetItem) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetReady](https://create.roblox.com/docs/reference/engine/classes/Plugin#SetReady) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetSetting](https://create.roblox.com/docs/reference/engine/classes/Plugin#SetSetting) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [StartDecalDrag](https://create.roblox.com/docs/reference/engine/classes/Plugin#StartDecalDrag) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [StartDrag](https://create.roblox.com/docs/reference/engine/classes/Plugin#StartDrag) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [StopAllSounds](https://create.roblox.com/docs/reference/engine/classes/Plugin#StopAllSounds) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [Union](https://create.roblox.com/docs/reference/engine/classes/Plugin#Union)
    from: (objects: Instances)
    to: (objects: Objects) [🔒 PluginSecurity]
  * Removed Property DisableUIDragDetectorDrags
  * Removed Property IsDebuggable
  * Removed Function FinishFullLoading
  * Removed Function GetPluginComponent
  * Removed Function GetUri
  * Removed Function Intersect
  * Removed Function IsLoadedFromProject
  * Removed Function OnInvokeSuspendOverride
  * Removed Function CreateDockWidgetPluginGuiAsync
  * Removed Function ImportFbxAnimationAsync
  * Removed Function ImportFbxRigAsync
  * Removed Function PromptForExistingAssetIdAsync
  * Removed Function PromptSaveSelectionAsync
  * Removed Event ViewportDragDropped
  * Removed Event ViewportDragEntered
  * Removed Event ViewportDragLeft
  * Removed Callback ProcessAssetInsertionDrag
  * Removed Callback ProcessAssetInsertionDrop
* Update Class [PluginAction](https://create.roblox.com/docs/reference/engine/classes/PluginAction) [🏷️ NotReplicated]
  * Removed Property Visible
* Update Class [PluginManager](https://create.roblox.com/docs/reference/engine/classes/PluginManager) [🏷️ NotCreatable]
  * Changed the return-type of Function [ExportPlace](https://create.roblox.com/docs/reference/engine/classes/PluginManager#ExportPlace) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [ExportSelection](https://create.roblox.com/docs/reference/engine/classes/PluginManager#ExportSelection) from null to void [🔒 PluginSecurity]
* Update Class [PluginManagerInterface](https://create.roblox.com/docs/reference/engine/classes/PluginManagerInterface) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [ExportPlace](https://create.roblox.com/docs/reference/engine/classes/PluginManagerInterface#ExportPlace) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [ExportSelection](https://create.roblox.com/docs/reference/engine/classes/PluginManagerInterface#ExportSelection) from null to void [🔒 PluginSecurity]
* Update Class [PluginMenu](https://create.roblox.com/docs/reference/engine/classes/PluginMenu) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [AddAction](https://create.roblox.com/docs/reference/engine/classes/PluginMenu#AddAction) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [AddMenu](https://create.roblox.com/docs/reference/engine/classes/PluginMenu#AddMenu) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [AddSeparator](https://create.roblox.com/docs/reference/engine/classes/PluginMenu#AddSeparator) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [Clear](https://create.roblox.com/docs/reference/engine/classes/PluginMenu#Clear) from null to void [🔒 PluginSecurity]
  * Removed Property Visible
* Update Class [PluginToolbar](https://create.roblox.com/docs/reference/engine/classes/PluginToolbar) [🏷️ NotCreatable]
  * Changed the return-type of Function [CreateButton](https://create.roblox.com/docs/reference/engine/classes/PluginToolbar#CreateButton) from PluginToolbarButton to Instance [🔒 PluginSecurity]
  * Removed Function CreatePopupButton
* Update Class [PluginToolbarButton](https://create.roblox.com/docs/reference/engine/classes/PluginToolbarButton) [🏷️ NotCreatable]
  * Changed the ValueType of Property [Icon](https://create.roblox.com/docs/reference/engine/classes/PluginToolbarButton#Icon) from ContentId to Content [🏷️ NotReplicated]
  * Changed the return-type of Function [SetActive](https://create.roblox.com/docs/reference/engine/classes/PluginToolbarButton#SetActive) from null to void [🔒 PluginSecurity]
  * Removed Property IconContent
  * Removed Function SetDropdownActive
  * Removed Event DropdownClick
* Update Class [PolicyService](https://create.roblox.com/docs/reference/engine/classes/PolicyService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function CanViewBrandProjectAsync
* Update Class [Pose](https://create.roblox.com/docs/reference/engine/classes/Pose)
  * Changed the return-type of Function [AddSubPose](https://create.roblox.com/docs/reference/engine/classes/Pose#AddSubPose) from null to void
  * Changed the return-type of Function [GetSubPoses](https://create.roblox.com/docs/reference/engine/classes/Pose#GetSubPoses) from Instances to Objects
  * Changed the return-type of Function [RemoveSubPose](https://create.roblox.com/docs/reference/engine/classes/Pose#RemoveSubPose) from null to void
* Update Class [ProximityPrompt](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt)
  * Changed the return-type of Function [InputHoldBegin](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#InputHoldBegin) from null to void
  * Changed the return-type of Function [InputHoldEnd](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#InputHoldEnd) from null to void
  * Removed Property MaxIndicatorDistance
  * Removed Event IndicatorHidden
  * Removed Event IndicatorShown
* Update Class [ProximityPromptService](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService) [🏷️ Service] [🏷️ NotBrowsable]
  * Removed Property MaxIndicatorsVisible
  * Removed Event IndicatorHidden
  * Removed Event IndicatorShown
* Update Class [PublishService](https://create.roblox.com/docs/reference/engine/classes/PublishService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [PublishCageMeshAsync](https://create.roblox.com/docs/reference/engine/classes/PublishService#PublishCageMeshAsync) from ContentId to Content [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Removed Function PublishDescendantAssets
  * Removed Function CreateAssetAndWaitForAssetId
  * Removed Function CreateAssetOrAssetVersionAndPollAssetWithTelemetryAsync
  * Removed Function CreateAssetOrAssetVersionAndPollAssetWithTelemetryAsyncWithAddParam
  * Removed Function CreateAssetOrAssetVersionAndPollAssetWithTelemetryAsyncWithAddParamErrorJson
  * Removed Function PublishDescendantAssetsAsync
* Update Class [RbxAnalyticsService](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [AddGlobalPointsField](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#AddGlobalPointsField) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [AddGlobalPointsTag](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#AddGlobalPointsTag) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ReleaseRBXEventStream](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReleaseRBXEventStream) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RemoveGlobalPointsField](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#RemoveGlobalPointsField) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RemoveGlobalPointsTag](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#RemoveGlobalPointsTag) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ReportCounter](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReportCounter) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ReportInfluxSeries](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReportInfluxSeries) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ReportStats](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReportStats) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ReportToDiagByCountryCode](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReportToDiagByCountryCode) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendEventDeferred](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#SendEventDeferred) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendEventImmediately](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#SendEventImmediately) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetRBXEvent](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#SetRBXEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetRBXEventStream](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#SetRBXEventStream) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [TrackEvent](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#TrackEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [TrackEventWithArgs](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#TrackEventWithArgs) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [UpdateHeartbeatObject](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#UpdateHeartbeatObject) from null to void [🔒 RobloxScriptSecurity]
  * Removed Function DEPRECATED_TrackEvent
  * Removed Function DEPRECATED_TrackEventWithArgs
  * Removed Function GetPlaySessionId
* Update Class [ReflectionMetadataItem](https://create.roblox.com/docs/reference/engine/classes/ReflectionMetadataItem) [🏷️ NotCreatable]
  * Removed Property SliderScaling
* Update Class [ReflectionMetadataClass](https://create.roblox.com/docs/reference/engine/classes/ReflectionMetadataClass)
  * Removed Property ServiceVisibility
* Update Class [RemoteEvent](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent)
  * Changed the return-type of Function [FireAllClients](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireAllClients) from null to void
  * Changed the return-type of Function [FireClient](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireClient) from null to void
  * Changed the return-type of Function [FireServer](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireServer) from null to void
* Update Class [RemoteFunction](https://create.roblox.com/docs/reference/engine/classes/RemoteFunction)
  * Changed the parameters of Callback [OnServerInvoke](https://create.roblox.com/docs/reference/engine/classes/RemoteFunction#OnServerInvoke)
    from: (player: Player, arguments: Tuple)
    to: (player: Instance, arguments: Tuple)
* Update Class [RenderSettings](https://create.roblox.com/docs/reference/engine/classes/RenderSettings) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotBrowsable]
  * Removed Property Enable VR Mode
  * Removed Property ViewMode
* Update Class [RenderingTest](https://create.roblox.com/docs/reference/engine/classes/RenderingTest)
  * Changed the return-type of Function [RenderdocTriggerCapture](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#RenderdocTriggerCapture) from null to void
  * Removed Property PerfTest
  * Removed Property QualityAuto
  * Removed Property RenderingTestFrameCount
  * Removed Property Timeout
  * Removed Event TestFramesCountdownAboutToStart
* Update Class [ReplicatedFirst](https://create.roblox.com/docs/reference/engine/classes/ReplicatedFirst) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [RemoveDefaultLoadingScreen](https://create.roblox.com/docs/reference/engine/classes/ReplicatedFirst#RemoveDefaultLoadingScreen) from null to void
  * Changed the return-type of Function [SetDefaultLoadingGuiRemoved](https://create.roblox.com/docs/reference/engine/classes/ReplicatedFirst#SetDefaultLoadingGuiRemoved) from null to void [🔒 RobloxScriptSecurity]
* Add Class [ReplicatedScriptService](https://create.roblox.com/docs/reference/engine/classes/ReplicatedScriptService) [🏷️ NotCreatable] [🏷️ Service]
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [BindToRenderStep](https://create.roblox.com/docs/reference/engine/classes/RunService#BindToRenderStep) from null to void
  * Changed the return-type of Function [Pause](https://create.roblox.com/docs/reference/engine/classes/RunService#Pause) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [Reset](https://create.roblox.com/docs/reference/engine/classes/RunService#Reset) from null to void [🔒 PluginSecurity] [🏷️ Deprecated]
  * Changed the return-type of Function [Run](https://create.roblox.com/docs/reference/engine/classes/RunService#Run) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [Set3dRenderingEnabled](https://create.roblox.com/docs/reference/engine/classes/RunService#Set3dRenderingEnabled) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetRobloxGuiFocused](https://create.roblox.com/docs/reference/engine/classes/RunService#SetRobloxGuiFocused) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [Stop](https://create.roblox.com/docs/reference/engine/classes/RunService#Stop) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [UnbindFromRenderStep](https://create.roblox.com/docs/reference/engine/classes/RunService#UnbindFromRenderStep) from null to void
  * Changed the return-type of Function [setThrottleFramerateEnabled](https://create.roblox.com/docs/reference/engine/classes/RunService#setThrottleFramerateEnabled) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [PostSimulation](https://create.roblox.com/docs/reference/engine/classes/RunService#PostSimulation)
    from: (deltaTimeSim: double)
    to: (deltaTime: double)
  * Changed the parameters of Event [PreAnimation](https://create.roblox.com/docs/reference/engine/classes/RunService#PreAnimation)
    from: (deltaTimeSim: double)
    to: (deltaTime: double)
  * Changed the parameters of Event [PreRender](https://create.roblox.com/docs/reference/engine/classes/RunService#PreRender)
    from: (deltaTimeRender: double)
    to: (deltaTime: double)
  * Changed the parameters of Event [PreSimulation](https://create.roblox.com/docs/reference/engine/classes/RunService#PreSimulation)
    from: (deltaTimeSim: double)
    to: (deltaTime: double)
  * Removed Property FrameNumber
  * Removed Property RunState
  * Removed Function BindToSimulation
  * Removed Function GetControlAndVariantRolloutFlags
  * Removed Function GetPhysicsStepId
  * Removed Function GetPredictionStatus
  * Removed Function GetRobloxClientChannel
  * Removed Function GetRobloxGuiFocused
  * Removed Function GetTotalScriptPlusExecutionTime
  * Removed Function IsResimulating
  * Removed Function SetPredictionMode
  * Removed Function getThrottleFramerateEnabled
  * Removed Event Misprediction
  * Removed Event RobloxGuiFocusedChanged
  * Removed Event Rollback
* Update Class [ScriptContext](https://create.roblox.com/docs/reference/engine/classes/ScriptContext) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [AddCoreScriptLocal](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#AddCoreScriptLocal) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetTimeout](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#SetTimeout) from null to void [🔒 PluginSecurity]
  * Changed the parameters of Event [ErrorDetailed](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#ErrorDetailed)
    from: (message: string, stackTrace: string, script: Instance, details: string, securityLevel: int, messageId: string)
    to: (message: string, stackTrace: string, script: Instance, details: string, securityLevel: int) [🔒 RobloxScriptSecurity]
  * Removed Function CompressLuaApp
  * Removed Function EnableCoverage
  * Removed Function GetLuauHeapInstanceReferenceReport
  * Removed Function GetLuauHeapMemoryReport
  * Removed Function ReportLuaRequireCount
* Update Class [ScriptDebugger](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger) [🏷️ NotCreatable]
  * Changed the return-type of Function [GetBreakpoints](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#GetBreakpoints) from Instances to Objects
  * Changed the return-type of Function [GetWatches](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#GetWatches) from Instances to Objects
  * Changed the return-type of Function [SetGlobal](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#SetGlobal) from null to void
  * Changed the return-type of Function [SetLocal](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#SetLocal) from null to void
  * Changed the return-type of Function [SetUpvalue](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#SetUpvalue) from null to void
* Add Class [ScriptRef](https://create.roblox.com/docs/reference/engine/classes/ScriptRef) [🏷️ NotCreatable] [🏷️ NotReplicated]
* Add Class [ScriptRefId](https://create.roblox.com/docs/reference/engine/classes/ScriptRefId) [🏷️ NotCreatable] [🏷️ NotReplicated]
* Add Class [ScriptRefPath](https://create.roblox.com/docs/reference/engine/classes/ScriptRefPath) [🏷️ NotCreatable] [🏷️ NotReplicated]
* Update Class [Selection](https://create.roblox.com/docs/reference/engine/classes/Selection) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [Add](https://create.roblox.com/docs/reference/engine/classes/Selection#Add) from null to void [🔒 PluginSecurity]
  * Changed the parameters of Function [Add](https://create.roblox.com/docs/reference/engine/classes/Selection#Add)
    from: (instancesToAdd: Instances)
    to: (instancesToAdd: Objects) [🔒 PluginSecurity]
  * Changed the return-type of Function [ClearTerrainSelectionHack](https://create.roblox.com/docs/reference/engine/classes/Selection#ClearTerrainSelectionHack) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [Get](https://create.roblox.com/docs/reference/engine/classes/Selection#Get) from Instances to Objects [🔒 PluginSecurity]
  * Changed the return-type of Function [Remove](https://create.roblox.com/docs/reference/engine/classes/Selection#Remove) from null to void [🔒 PluginSecurity]
  * Changed the parameters of Function [Remove](https://create.roblox.com/docs/reference/engine/classes/Selection#Remove)
    from: (instancesToRemove: Instances)
    to: (instancesToRemove: Objects) [🔒 PluginSecurity]
  * Changed the return-type of Function [Set](https://create.roblox.com/docs/reference/engine/classes/Selection#Set) from null to void [🔒 PluginSecurity]
  * Changed the parameters of Function [Set](https://create.roblox.com/docs/reference/engine/classes/Selection#Set)
    from: (selection: Instances)
    to: (selection: Objects) [🔒 PluginSecurity]
  * Changed the return-type of Function [SetTerrainSelectionHack](https://create.roblox.com/docs/reference/engine/classes/Selection#SetTerrainSelectionHack) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property RenderMode
  * Removed Property SelectionBoxThickness
  * Removed Property SelectionLineThickness
  * Removed Property ShowActiveInstanceHighlight
  * Removed Function AddFocusCallback
  * Removed Event SelectionChangedThisFrame
* Update Class [DataModel](https://create.roblox.com/docs/reference/engine/classes/DataModel) [🏷️ NotCreatable]
  * Changed the return-type of Function [BindToClose](https://create.roblox.com/docs/reference/engine/classes/DataModel#BindToClose) from null to void
  * Changed the return-type of Function [GetObjects](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetObjects) from Instances to Objects [🔒 PluginSecurity]
  * Changed the parameters of Function [GetObjects](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetObjects)
    from: (url: ContentId)
    to: (url: Content) [🔒 PluginSecurity]
  * Changed the return-type of Function [Load](https://create.roblox.com/docs/reference/engine/classes/DataModel#Load) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [Load](https://create.roblox.com/docs/reference/engine/classes/DataModel#Load)
    from: (url: ContentId)
    to: (url: Content) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [OpenScreenshotsFolder](https://create.roblox.com/docs/reference/engine/classes/DataModel#OpenScreenshotsFolder) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [OpenVideosFolder](https://create.roblox.com/docs/reference/engine/classes/DataModel#OpenVideosFolder) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [ReportInGoogleAnalytics](https://create.roblox.com/docs/reference/engine/classes/DataModel#ReportInGoogleAnalytics) (category: string, action: string = custom, label: string = none, value: int = 0) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetPlaceId](https://create.roblox.com/docs/reference/engine/classes/DataModel#SetPlaceId) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [SetUniverseId](https://create.roblox.com/docs/reference/engine/classes/DataModel#SetUniverseId) from null to void [🔒 PluginSecurity]
  * Changed the return-type of Function [Shutdown](https://create.roblox.com/docs/reference/engine/classes/DataModel#Shutdown) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [GetObjectsAsync](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetObjectsAsync) from Instances to Objects [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the parameters of Function [GetObjectsAsync](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetObjectsAsync)
    from: (url: ContentId)
    to: (url: Content) [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [InsertObjectsAndJoinIfLegacyAsync](https://create.roblox.com/docs/reference/engine/classes/DataModel#InsertObjectsAndJoinIfLegacyAsync) from Instances to Objects [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the parameters of Function [InsertObjectsAndJoinIfLegacyAsync](https://create.roblox.com/docs/reference/engine/classes/DataModel#InsertObjectsAndJoinIfLegacyAsync)
    from: (url: ContentId)
    to: (url: Content) [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Removed Property Environment
  * Removed Property IsPioneerBuild
  * Removed Property MatchmakingType
  * Removed Property PioneerSource
  * Removed Property RunService
  * Removed Function GetPlaySessionId
  * Removed Function IsContentLoaded
  * Removed Function IsUniverseMetadataLoaded
  * Removed Function OpenLogsFolder
  * Removed Function SetFlagVersion
  * Removed Function SetIsLoaded
  * Removed Function getGameTime
  * Removed Function GetObjectsAllOrNone
  * Removed Event ServerLifecycleChanged
  * Removed Event ServerRestartScheduled
  * Removed Event UniverseMetadataLoaded
* Add Class [AnalysticsSettings](https://create.roblox.com/docs/reference/engine/classes/AnalysticsSettings) [🏷️ NotCreatable]
* Update Class [GlobalSettings](https://create.roblox.com/docs/reference/engine/classes/GlobalSettings) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Removed Function GetFFlagOverrides
  * Removed Function GetFFlags
  * Removed Function SetFFlagOverrides
* Update Class [UserSettings](https://create.roblox.com/docs/reference/engine/classes/UserSettings) [🏷️ NotCreatable]
  * Changed the return-type of Function [Reset](https://create.roblox.com/docs/reference/engine/classes/UserSettings#Reset) from null to void
  * Removed Function SaveState
* Update Class [SessionService](https://create.roblox.com/docs/reference/engine/classes/SessionService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [RemoveMetadata](https://create.roblox.com/docs/reference/engine/classes/SessionService#RemoveMetadata) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [RemoveMetadata](https://create.roblox.com/docs/reference/engine/classes/SessionService#RemoveMetadata)
    from: (sid: string, key: string, context: string = )
    to: (sid: string, key: string) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [RemoveSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#RemoveSession) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [RemoveSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#RemoveSession)
    from: (sid: string, context: string = )
    to: (sid: string) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ReplaceSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#ReplaceSession) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetMetadata](https://create.roblox.com/docs/reference/engine/classes/SessionService#SetMetadata) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [SetMetadata](https://create.roblox.com/docs/reference/engine/classes/SessionService#SetMetadata)
    from: (sid: string, key: string, value: Variant, context: string = )
    to: (sid: string, key: string, value: Variant) [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#SetSession) from null to void [🔒 RobloxScriptSecurity]
  * Changed the parameters of Function [SetSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#SetSession)
    from: (parentSid: string, childSid: string, tag: string, context: string = )
    to: (parentSid: string, childSid: string, tag: string) [🔒 RobloxScriptSecurity]
  * Removed Function AcquireContextFocus
  * Removed Function GenerateSessionInfoString
  * Removed Function GetBreadcrumbs
  * Removed Function GetHistory
  * Removed Function GetSessionID
  * Removed Function GetSessionTag
  * Removed Function IsContextFocused
  * Removed Function ReleaseContextFocus
  * Removed Function RemoveSessionsWithMetadataKey
  * Removed Event SessionChanged
* Update Class [Sky](https://create.roblox.com/docs/reference/engine/classes/Sky)
  * Changed the ValueType of Property [MoonTextureId](https://create.roblox.com/docs/reference/engine/classes/Sky#MoonTextureId) from ContentId to Content
  * Changed the ValueType of Property [SkyboxBk](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxBk) from ContentId to Content
  * Changed the ValueType of Property [SkyboxDn](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxDn) from ContentId to Content
  * Changed the ValueType of Property [SkyboxFt](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxFt) from ContentId to Content
  * Changed the ValueType of Property [SkyboxLf](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxLf) from ContentId to Content
  * Changed the ValueType of Property [SkyboxRt](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxRt) from ContentId to Content
  * Changed the ValueType of Property [SkyboxUp](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxUp) from ContentId to Content
  * Changed the ValueType of Property [SunTextureId](https://create.roblox.com/docs/reference/engine/classes/Sky#SunTextureId) from ContentId to Content
  * Removed Property MoonTextureContent
  * Removed Property SkyboxBackContent
  * Removed Property SkyboxDownContent
  * Removed Property SkyboxFrontContent
  * Removed Property SkyboxLeftContent
  * Removed Property SkyboxOrientation
  * Removed Property SkyboxRightContent
  * Removed Property SkyboxUpContent
  * Removed Property SunTextureContent
* Update Class [Smoke](https://create.roblox.com/docs/reference/engine/classes/Smoke)
  * Removed Property LocalTransparencyModifier
  * Removed Property TimeScale
  * Removed Function FastForward
* Update Class [SocialService](https://create.roblox.com/docs/reference/engine/classes/SocialService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [InvokeGameInvitePromptClosed](https://create.roblox.com/docs/reference/engine/classes/SocialService#InvokeGameInvitePromptClosed) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PromptGameInvite](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptGameInvite) from null to void
  * Changed the parameters of Function [PromptGameInvite](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptGameInvite)
    from: (player: Instance, experienceInviteOptions: Instance = nil)
    to: (player: Instance)
  * Changed the parameters of Function [CanSendGameInviteAsync](https://create.roblox.com/docs/reference/engine/classes/SocialService#CanSendGameInviteAsync)
    from: (player: Instance, recipientId: User = U1.AQAAAAAAAAAAAAAAAAAAAAA)
    to: (player: Instance) [🏷️ Yields]
  * Changed the parameters of Event [PromptInviteRequested](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptInviteRequested)
    from: (player: Instance, experienceInviteOptions: Instance)
    to: (player: Instance) [🔒 RobloxScriptSecurity]
  * Removed Function GetPlayersByPartyId
  * Removed Function HideSelfView
  * Removed Function InvokeIrisInvite
  * Removed Function InvokeIrisInvitePromptClosed
  * Removed Function InvokeShareSheetClosed
  * Removed Function PromptPhoneBook
  * Removed Function PromptRsvpToEventCompleted
  * Removed Function ShowSelfView
  * Removed Function SignalFeedbackSubmissionCompleted
  * Removed Function SignalFeedbackSubmissionPermissionDenied
  * Removed Function UpdatePlayerPartyData
  * Removed Function CanSendCallInviteAsync
  * Removed Function GetEventRsvpStatusAsync
  * Removed Function GetExperienceEventAsync
  * Removed Function GetPartyAsync
  * Removed Function GetUpcomingExperienceEventsAsync
  * Removed Function PromptFeedbackSubmissionAsync
  * Removed Function PromptLinkSharing
  * Removed Function PromptLinkSharingAsync
  * Removed Function PromptRsvpToEventAsync
  * Removed Event CallInviteStateChanged
  * Removed Event OpenShareSheetWithLink
  * Removed Event PhoneBookPromptClosed
  * Removed Event PlayerPartyDataChanged
  * Removed Event PromptIrisInviteRequested
  * Removed Event SelfViewHidden
  * Removed Event SelfViewVisible
  * Removed Event ShareSheetClosed
  * Removed Event ShowPromptFeedbackSubmission
  * Removed Event ShowPromptFeedbackUnavailable
  * Removed Event ShowPromptRsvpToEvent
  * Removed Callback OnCallInviteInvoked
* Update Class [Sound](https://create.roblox.com/docs/reference/engine/classes/Sound)
  * Changed the ValueType of Property [SoundId](https://create.roblox.com/docs/reference/engine/classes/Sound#SoundId) from ContentId to Content
  * Changed the return-type of Function [Pause](https://create.roblox.com/docs/reference/engine/classes/Sound#Pause) from null to void
  * Changed the return-type of Function [Play](https://create.roblox.com/docs/reference/engine/classes/Sound#Play) from null to void
  * Changed the return-type of Function [Resume](https://create.roblox.com/docs/reference/engine/classes/Sound#Resume) from null to void
  * Changed the return-type of Function [Stop](https://create.roblox.com/docs/reference/engine/classes/Sound#Stop) from null to void
  * Changed the return-type of Function [pause](https://create.roblox.com/docs/reference/engine/classes/Sound#pause) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [play](https://create.roblox.com/docs/reference/engine/classes/Sound#play) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [stop](https://create.roblox.com/docs/reference/engine/classes/Sound#stop) from null to void [🏷️ Deprecated]
  * Removed Property AcousticSimulationEnabled
  * Removed Property AssetRepresentation
  * Removed Property AudioContent
  * Removed Property IsSpatial
  * Removed Property LoopRegion
  * Removed Property PlaybackRegion
  * Removed Property PlaybackRegionsEnabled
  * Removed Property RollOffGain
  * Removed Property UsageContextPermission
  * Removed Function GetUnderlyingAudioPlayer
* Update Class [SoundService](https://create.roblox.com/docs/reference/engine/classes/SoundService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [PlayLocalSound](https://create.roblox.com/docs/reference/engine/classes/SoundService#PlayLocalSound) from null to void
  * Changed the return-type of Function [SetListener](https://create.roblox.com/docs/reference/engine/classes/SoundService#SetListener) from null to void
  * Changed the return-type of Function [SetOutputDevice](https://create.roblox.com/docs/reference/engine/classes/SoundService#SetOutputDevice) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property AcousticSimulationEnabled
  * Removed Property AudioApiByDefault
  * Removed Property CharacterSoundsUseNewApi
  * Removed Property DefaultListenerLocation
  * Removed Property DiffractionEnabled
  * Removed Property IsNewExpForAudioApiByDefault
  * Removed Property ListenerCFrame
  * Removed Property ListenerObject
  * Removed Property ListenerType
  * Removed Property OcclusionEnabled
  * Removed Property ReverbEnabled
  * Removed Property VolumetricAudio
  * Removed Function GetAudioApiByDefault
  * Removed Function GetAudioInstances
  * Removed Function GetInputDevice
  * Removed Function GetInputDevices
  * Removed Function GetMixerTime
  * Removed Function InsertAsset
  * Removed Function OpenAttenuationCurveEditor
  * Removed Function OpenDirectionalCurveEditor
  * Removed Function SetAudioApiByDefault
  * Removed Function SetInputDevice
  * Removed Function SetSoundEnabled
  * Removed Event AudioInstanceAdded
  * Removed Event OpenAttenuationCurveEditorSignal
  * Removed Event OpenAudioCompressorEditorSignal
  * Removed Event OpenAudioEqualizerEditorSignal
  * Removed Event OpenDirectionalCurveEditorSignal
* Update Class [Sparkles](https://create.roblox.com/docs/reference/engine/classes/Sparkles)
  * Removed Property LocalTransparencyModifier
  * Removed Property TimeScale
  * Removed Function FastForward
* Add Class [Speaker](https://create.roblox.com/docs/reference/engine/classes/Speaker) [🏷️ Deprecated]
  * Add Property [ChannelCount](https://create.roblox.com/docs/reference/engine/classes/Speaker#ChannelCount): int [🏷️ ReadOnly] [🏷️ NotReplicated] [🏷️ NotBrowsable]
  * Add Property [PlaybackLoudness](https://create.roblox.com/docs/reference/engine/classes/Speaker#PlaybackLoudness): double [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Property [RollOffMaxDistance](https://create.roblox.com/docs/reference/engine/classes/Speaker#RollOffMaxDistance): float [🏷️ NotReplicated]
  * Add Property [RollOffMinDistance](https://create.roblox.com/docs/reference/engine/classes/Speaker#RollOffMinDistance): float [🏷️ NotReplicated]
  * Add Property [RollOffMode](https://create.roblox.com/docs/reference/engine/classes/Speaker#RollOffMode): RollOffMode
  * Add Property [SoundGroup](https://create.roblox.com/docs/reference/engine/classes/Speaker#SoundGroup): SoundGroup
  * Add Property [Source](https://create.roblox.com/docs/reference/engine/classes/Speaker#Source): Instance
  * Add Property [Volume](https://create.roblox.com/docs/reference/engine/classes/Speaker#Volume): float
* Update Class [StarterPlayer](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer) [🏷️ NotCreatable] [🏷️ Service]
  * Add Property [LoadCharacterLayeredClothing](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#LoadCharacterLayeredClothing): LoadCharacterLayeredClothing [🏷️ NotScriptable]
  * Changed the return-type of Function [ClearDefaults](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#ClearDefaults) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property AvatarJointUpgrade
  * Removed Property CharacterBreakJointsOnDeath
  * Removed Property ClassicDeath
  * Removed Property CreateDefaultPlayerModule
  * Removed Property EnableDynamicHeads
  * Removed Property LoadCharacterLayeredClothing 
  * Removed Property LuaCharacterController
  * Removed Property PlayerModuleStatus
* Update Class [Stats](https://create.roblox.com/docs/reference/engine/classes/Stats) [🏷️ NotCreatable] [🏷️ Service]
  * Removed Property FrameTime
  * Removed Property HeartbeatTime
  * Removed Property MemoryTrackingEnabled
  * Removed Property PhysicsStepTime
  * Removed Property RenderCPUFrameTime
  * Removed Property RenderGPUFrameTime
  * Removed Property SceneDrawcallCount
  * Removed Property SceneTriangleCount
  * Removed Property ShadowsDrawcallCount
  * Removed Property ShadowsTriangleCount
  * Removed Property UI2DDrawcallCount
  * Removed Property UI2DTriangleCount
  * Removed Property UI3DDrawcallCount
  * Removed Property UI3DTriangleCount
  * Removed Function GetHarmonyQualityLevel
  * Removed Function GetMemoryCategoryNames
  * Removed Function GetMemoryUsageMbAllCategories
  * Removed Function ResetHarmonyMemoryTarget
  * Removed Function SetHarmonyMemoryTarget
* Update Class [StopWatchReporter](https://create.roblox.com/docs/reference/engine/classes/StopWatchReporter) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [FinishTask](https://create.roblox.com/docs/reference/engine/classes/StopWatchReporter#FinishTask) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendReport](https://create.roblox.com/docs/reference/engine/classes/StopWatchReporter#SendReport) from null to void [🔒 RobloxScriptSecurity]
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Property [Auto-Recovery Path](https://create.roblox.com/docs/reference/engine/classes/Studio#Auto-Recovery%20Path): QDir
  * Add Property [DefaultScriptFileDir](https://create.roblox.com/docs/reference/engine/classes/Studio#DefaultScriptFileDir): QDir
  * Add Property [Drag Multiple Parts As Single Part](https://create.roblox.com/docs/reference/engine/classes/Studio#Drag%20Multiple%20Parts%20As%20Single%20Part): bool
  * Add Property [OverrideCoreScripts](https://create.roblox.com/docs/reference/engine/classes/Studio#OverrideCoreScripts): bool [🔒 Read:None, Write:RobloxScriptSecurity]
  * Add Property [OverrideCoreScriptsDir](https://create.roblox.com/docs/reference/engine/classes/Studio#OverrideCoreScriptsDir): QDir [🔒 Read:None, Write:RobloxScriptSecurity]
  * Add Property [Render Throttle Percentage](https://create.roblox.com/docs/reference/engine/classes/Studio#Render%20Throttle%20Percentage): int
  * Add Property [Search Content For Core Scripts](https://create.roblox.com/docs/reference/engine/classes/Studio#Search%20Content%20For%20Core%20Scripts): bool
  * Add Property [Selection Highlight Thickness](https://create.roblox.com/docs/reference/engine/classes/Studio#Selection%20Highlight%20Thickness): float [🔒 RobloxSecurity]
  * Add Property [Server Audio Behavior](https://create.roblox.com/docs/reference/engine/classes/Studio#Server%20Audio%20Behavior): ServerAudioBehavior
  * Add Property [Show Deployment Warnings](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Deployment%20Warnings): bool
  * Add Property [Show Navigation Areas](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Navigation%20Areas): bool [🔒 RobloxScriptSecurity]
  * Add Property [Show QT warnings in output](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20QT%20warnings%20in%20output): bool
  * Removed Property ActionOnAutoResumeSync
  * Removed Property ActionOnStopSync
  * Removed Property Animation Skeleton Scale
  * Removed Property Animation Skeleton Transparency
  * Removed Property AutoResumeSyncOnPlaceOpen
  * Removed Property AutoUpdateEnabled
  * Removed Property Auto Delete Closing Brackets and Quotes
  * Removed Property AutocompleteAcceptanceBehavior
  * Removed Property Automatically trigger AI Code Completion
  * Removed Property CameraAdaptiveSpeed
  * Removed Property CameraAltLeftMouseToRotate
  * Removed Property CameraMouseMultiplier
  * Removed Property CameraNavigationModel
  * Removed Property CameraOrbitSensitivity
  * Removed Property CameraPanSensitivity
  * Removed Property CameraShiftFactor
  * Removed Property CameraTweenFocus
  * Removed Property CameraZoomSpeed
  * Removed Property CameraZoomToMousePosition
  * Removed Property Camera Pan Speed
  * Removed Property Camera Speed Adjust Binding
  * Removed Property CommandBarEnterExec
  * Removed Property CommandBarFont
  * Removed Property CommandBarHistoryLen
  * Removed Property DefaultInstancesDir
  * Removed Property DefaultScriptSyncFileType
  * Removed Property Doc View Code Background Color
  * Removed Property DraggerActiveColor
  * Removed Property DraggerLengthFactor
  * Removed Property DraggerMajorGridIncrement
  * Removed Property DraggerMaxSoftSnaps
  * Removed Property DraggerPassiveColor
  * Removed Property DraggerScaleFactor
  * Removed Property DraggerShowAxisTicks
  * Removed Property DraggerShowDraggedPoint
  * Removed Property DraggerShowHoverRuler
  * Removed Property DraggerShowMeasurement
  * Removed Property DraggerShowNegativeAxes
  * Removed Property DraggerShowPlanes
  * Removed Property DraggerShowTargetSnap
  * Removed Property DraggerShowTrackball
  * Removed Property DraggerShowWhileDragging
  * Removed Property DraggerSoftSnapMarginFactor
  * Removed Property DraggerSummonMarginFactor
  * Removed Property DraggerTiltRotateDuration
  * Removed Property EnableCodeAssist
  * Removed Property EnableFindOnType
  * Removed Property EnableIndentationRulers
  * Removed Property EnableOvertypeMode
  * Removed Property EnableSelectionTooltips
  * Removed Property EnableStudioStreaming
  * Removed Property Enable Autocomplete Doc View
  * Removed Property Enable Client/Server MDI
  * Removed Property Enable Scrollbar Markers
  * Removed Property Enable Signature Help Doc View
  * Removed Property ExternalEditorMode
  * Removed Property ExternalEditorSelection
  * Removed Property HintColor
  * Removed Property Hover Line Thickness
  * Removed Property IconOverrideDir
  * Removed Property IndentationRulerColor
  * Removed Property InformationColor
  * Removed Property LargeFileLineCountThreshold
  * Removed Property LargeFileThreshold
  * Removed Property LoadAllBuiltinPluginsInRunModes
  * Removed Property LoadInternalPlugins
  * Removed Property LoadUserPluginsInRunModes
  * Removed Property Main Volume
  * Removed Property MaxFindReplaceAllResults
  * Removed Property PreferredTextSize
  * Removed Property ReloadBuiltinPluginsOnChange
  * Removed Property ReloadLocalPluginsOnChange
  * Removed Property Selection Box Thickness
  * Removed Property Selection Line Thickness
  * Removed Property Show Animation Skeleton
  * Removed Property Show Animation Skeleton Attachments
  * Removed Property Show Animation Skeleton Axes
  * Removed Property Show Animation Skeleton Rotations
  * Removed Property Show Animation Skeleton Text
  * Removed Property Show Navigation Labels
  * Removed Property Show Pathfinding Links
  * Removed Property Show Singly Selected Attachment Parent Frame
  * Removed Property TypeColor
  * Removed Property UseDefaultExternalEditor
  * Removed Property Use Bounding Box Move Handles
  * Removed Property VAxisColor
  * Removed Property XAxisColor
  * Removed Property YAxisColor
  * Removed Property ZAxisColor
* Update Class [StudioData](https://create.roblox.com/docs/reference/engine/classes/StudioData) [🏷️ NotCreatable] [🏷️ Service]
  * Add Property [SrcPlaceId](https://create.roblox.com/docs/reference/engine/classes/StudioData#SrcPlaceId): int64 [🔒 RobloxSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
  * Add Property [SrcUniverseId](https://create.roblox.com/docs/reference/engine/classes/StudioData#SrcUniverseId): int64 [🔒 RobloxSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
* Update Class [StudioDeviceEmulatorService](https://create.roblox.com/docs/reference/engine/classes/StudioDeviceEmulatorService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [SetCurrentDeviceId](https://create.roblox.com/docs/reference/engine/classes/StudioDeviceEmulatorService#SetCurrentDeviceId) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the return-type of Function [SetCurrentOrientation](https://create.roblox.com/docs/reference/engine/classes/StudioDeviceEmulatorService#SetCurrentOrientation) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
* Update Class [StudioService](https://create.roblox.com/docs/reference/engine/classes/StudioService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Property [ShowActiveInstanceHighlight](https://create.roblox.com/docs/reference/engine/classes/StudioService#ShowActiveInstanceHighlight): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
  * Changed the return-type of Function [AnimationIdSelected](https://create.roblox.com/docs/reference/engine/classes/StudioService#AnimationIdSelected) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [ConvertToPackageUpload](https://create.roblox.com/docs/reference/engine/classes/StudioService#ConvertToPackageUpload) (uploadUrl: string) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [CopyToClipboard](https://create.roblox.com/docs/reference/engine/classes/StudioService#CopyToClipboard) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [EmitPlacePublishedSignal](https://create.roblox.com/docs/reference/engine/classes/StudioService#EmitPlacePublishedSignal) () -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [GizmoRaycast](https://create.roblox.com/docs/reference/engine/classes/StudioService#GizmoRaycast) from RaycastResult? to RaycastResult [🔒 PluginSecurity]
  * Changed the parameters of Function [GizmoRaycast](https://create.roblox.com/docs/reference/engine/classes/StudioService#GizmoRaycast)
    from: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, CollisionGroup=Default, FilterDescendantsInstances={}}) [🔒 PluginSecurity]
  * Changed the return-type of Function [OpenInBrowser_DONOTUSE](https://create.roblox.com/docs/reference/engine/classes/StudioService#OpenInBrowser_DONOTUSE) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [PromptForLocalSave](https://create.roblox.com/docs/reference/engine/classes/StudioService#PromptForLocalSave) () -> void [🔒 RobloxScriptSecurity]
  * Add Function [PublishAs](https://create.roblox.com/docs/reference/engine/classes/StudioService#PublishAs) (universeId: int64, placeId: int64, groupId: int64) -> void [🔒 RobloxScriptSecurity]
  * Add Function [RequestClose](https://create.roblox.com/docs/reference/engine/classes/StudioService#RequestClose) (closeMode: StudioCloseMode) -> void [🔒 RobloxScriptSecurity]
  * Add Function [SerializeInstances](https://create.roblox.com/docs/reference/engine/classes/StudioService#SerializeInstances) (instances: Objects) -> string [🔒 RobloxScriptSecurity]
  * Add Function [SetDocumentDisplayName](https://create.roblox.com/docs/reference/engine/classes/StudioService#SetDocumentDisplayName) (newName: string) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetPluginEnabled](https://create.roblox.com/docs/reference/engine/classes/StudioService#SetPluginEnabled) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [SetUniverseDisplayName](https://create.roblox.com/docs/reference/engine/classes/StudioService#SetUniverseDisplayName) (newName: string) -> void [🔒 RobloxScriptSecurity]
  * Add Function [ShowPlaceVersionHistoryDialog](https://create.roblox.com/docs/reference/engine/classes/StudioService#ShowPlaceVersionHistoryDialog) (placeId: int64) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ShowPublishToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#ShowPublishToRoblox) from null to void [🔒 RobloxScriptSecurity]
  * Add Function [ShowSaveOrPublishPlaceToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#ShowSaveOrPublishPlaceToRoblox) (showGameSelect: bool, isPublish: bool, closeMode: StudioCloseMode) -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [UninstallPlugin](https://create.roblox.com/docs/reference/engine/classes/StudioService#UninstallPlugin) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [UpdatePluginManagement](https://create.roblox.com/docs/reference/engine/classes/StudioService#UpdatePluginManagement) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [PromptImportFiles](https://create.roblox.com/docs/reference/engine/classes/StudioService#PromptImportFiles) from Instances to Objects [🔒 PluginSecurity] [🏷️ Yields]
  * Changed the return-type of Function [TryInstallPlugin](https://create.roblox.com/docs/reference/engine/classes/StudioService#TryInstallPlugin) from null to void [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Add Event [FirstPublishOfCloudPlace](https://create.roblox.com/docs/reference/engine/classes/StudioService#FirstPublishOfCloudPlace) [🔒 RobloxScriptSecurity]
  * Add Event [GameNameUpdated](https://create.roblox.com/docs/reference/engine/classes/StudioService#GameNameUpdated) [🔒 RobloxScriptSecurity]
  * Add Event [GamePublishFinished](https://create.roblox.com/docs/reference/engine/classes/StudioService#GamePublishFinished) [🔒 RobloxScriptSecurity]
  * Add Event [OnConvertToPackageResult](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnConvertToPackageResult) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [OnImportFromRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnImportFromRoblox)
    from: (assetType: string)
    to: () [🔒 RobloxScriptSecurity]
  * Add Event [OnOpenConvertToPackagePlugin](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnOpenConvertToPackagePlugin) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [OnPublishAsPlugin](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnPublishAsPlugin)
    from: (instances: Instances)
    to: (instances: Objects) [🔒 RobloxScriptSecurity]
  * Add Event [OnPublishPlaceToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnPublishPlaceToRoblox) [🔒 RobloxScriptSecurity]
  * Add Event [OnSaveOrPublishPlaceToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnSaveOrPublishPlaceToRoblox) [🔒 RobloxScriptSecurity]
  * Changed the parameters of Event [OnSaveToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnSaveToRoblox)
    from: (instances: Instances)
    to: (instances: Objects) [🔒 RobloxScriptSecurity]
  * Removed Property Secrets
  * Removed Property ShowWeldDetails
  * Removed Function GetPlaceIsPersistedToCloud
  * Removed Function PromptImportFileAsync
  * Removed Function PromptImportFilesAsync
* Update Class [SurfaceAppearance](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance)
  * Changed the ValueType of Property [ColorMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#ColorMap) from ContentId to Content [🔒 LocalUserSecurity]
  * Changed the ValueType of Property [MetalnessMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#MetalnessMap) from ContentId to Content [🔒 LocalUserSecurity]
  * Changed the ValueType of Property [NormalMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#NormalMap) from ContentId to Content [🔒 LocalUserSecurity]
  * Changed the ValueType of Property [RoughnessMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#RoughnessMap) from ContentId to Content [🔒 LocalUserSecurity]
  * Changed the ValueType of Property [TexturePack](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#TexturePack) from ContentId to Content [🔒 RobloxSecurity] [🏷️ Hidden]
  * Removed Property Color
  * Removed Property ColorMapContent
  * Removed Property EmissiveMaskContent
  * Removed Property EmissiveStrength
  * Removed Property EmissiveTint
  * Removed Property MetalnessMapContent
  * Removed Property NormalMapContent
  * Removed Property ResampleMode
  * Removed Property RoughnessMapContent
  * Removed Property TexturePackContent
* Update Class [Team](https://create.roblox.com/docs/reference/engine/classes/Team)
  * Changed the return-type of Function [GetPlayers](https://create.roblox.com/docs/reference/engine/classes/Team#GetPlayers) from Instances to Objects
  * Changed the parameters of Event [PlayerAdded](https://create.roblox.com/docs/reference/engine/classes/Team#PlayerAdded)
    from: (player: Player)
    to: (player: Instance)
  * Changed the parameters of Event [PlayerRemoved](https://create.roblox.com/docs/reference/engine/classes/Team#PlayerRemoved)
    from: (player: Player)
    to: (player: Instance)
* Update Class [Teams](https://create.roblox.com/docs/reference/engine/classes/Teams) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [GetTeams](https://create.roblox.com/docs/reference/engine/classes/Teams#GetTeams) from Instances to Objects
  * Changed the return-type of Function [RebalanceTeams](https://create.roblox.com/docs/reference/engine/classes/Teams#RebalanceTeams) from null to void [🏷️ Deprecated]
* Update Class [TeleportOptions](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions)
  * Changed the return-type of Function [SetTeleportData](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#SetTeleportData) from null to void
* Update Class [TeleportService](https://create.roblox.com/docs/reference/engine/classes/TeleportService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [SetTeleportGui](https://create.roblox.com/docs/reference/engine/classes/TeleportService#SetTeleportGui) from null to void
  * Changed the return-type of Function [SetTeleportSetting](https://create.roblox.com/docs/reference/engine/classes/TeleportService#SetTeleportSetting) from null to void
  * Changed the return-type of Function [Teleport](https://create.roblox.com/docs/reference/engine/classes/TeleportService#Teleport) from null to void
  * Changed the return-type of Function [TeleportCancel](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportCancel) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [TeleportToPlaceInstance](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToPlaceInstance) from null to void
  * Changed the return-type of Function [TeleportToPrivateServer](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToPrivateServer) from null to void
  * Changed the parameters of Function [TeleportToPrivateServer](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToPrivateServer)
    from: (placeId: int64, reservedServerAccessCode: string, players: Instances, spawnName: string = , teleportData: Variant, customLoadingScreen: Instance = nil)
    to: (placeId: int64, reservedServerAccessCode: string, players: Objects, spawnName: string = , teleportData: Variant, customLoadingScreen: Instance = nil)
  * Changed the return-type of Function [TeleportToSpawnByName](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToSpawnByName) from null to void
  * Changed the parameters of Function [GetPlayerPlaceInstanceAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#GetPlayerPlaceInstanceAsync)
    from: (userId: User)
    to: (userId: int64) [🏷️ Yields]
  * Changed the parameters of Function [TeleportAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportAsync)
    from: (placeId: int64, players: Instances, teleportOptions: Instance = nil)
    to: (placeId: int64, players: Objects, teleportOptions: Instance = nil) [🏷️ Yields]
  * Changed the parameters of Function [TeleportPartyAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportPartyAsync)
    from: (placeId: int64, players: Instances, teleportData: Variant, customLoadingScreen: Instance = nil)
    to: (placeId: int64, players: Objects, teleportData: Variant, customLoadingScreen: Instance = nil) [🏷️ Yields]
  * Changed the parameters of Event [TeleportInitFailed](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportInitFailed)
    from: (player: Instance, teleportResult: TeleportResult, errorMessage: string, placeId: int64, teleportOptions: Instance)
    to: (player: Instance, teleportResult: TeleportResult, errorMessage: string)
  * Removed Function Block
  * Removed Function GetThirdPartyTeleportInfo
  * Removed Function PromptExperienceDetailsCompleted
  * Removed Function TeleportReconnect
  * Removed Function TeleportTrustedBackForth
  * Removed Function TeleportTrustedBackHistory
  * Removed Function TeleportedPlacesBackHistory
  * Removed Function TeleportedUniversesBackHistory
  * Removed Function PromptExperienceDetailsAsync
  * Removed Function ReserveServerAsync
  * Removed Function UnblockAsync
  * Removed Event MenuTeleportAttempt
  * Removed Event OpenExperienceDetailsPrompt
  * Removed Event ReconnectTeleportInitFailed
* Update Class [TerrainRegion](https://create.roblox.com/docs/reference/engine/classes/TerrainRegion)
  * Changed the return-type of Function [ConvertToSmooth](https://create.roblox.com/docs/reference/engine/classes/TerrainRegion#ConvertToSmooth) from null to void [🔒 PluginSecurity] [🏷️ Deprecated]
  * Removed Function ApplyTransform
  * Removed Function ApplyTransformSubregion
  * Removed Function GetRegionWireframe
* Update Class [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) [🏷️ Service]
  * Changed the return-type of Function [Check](https://create.roblox.com/docs/reference/engine/classes/TestService#Check) from null to void
  * Changed the return-type of Function [Checkpoint](https://create.roblox.com/docs/reference/engine/classes/TestService#Checkpoint) from null to void
  * Changed the return-type of Function [Done](https://create.roblox.com/docs/reference/engine/classes/TestService#Done) from null to void
  * Changed the return-type of Function [Error](https://create.roblox.com/docs/reference/engine/classes/TestService#Error) from null to void
  * Changed the return-type of Function [Fail](https://create.roblox.com/docs/reference/engine/classes/TestService#Fail) from null to void
  * Changed the return-type of Function [Message](https://create.roblox.com/docs/reference/engine/classes/TestService#Message) from null to void
  * Changed the return-type of Function [Require](https://create.roblox.com/docs/reference/engine/classes/TestService#Require) from null to void
  * Changed the return-type of Function [Warn](https://create.roblox.com/docs/reference/engine/classes/TestService#Warn) from null to void
  * Changed the return-type of Function [Run](https://create.roblox.com/docs/reference/engine/classes/TestService#Run) from null to void [🔒 PluginSecurity] [🏷️ Yields]
  * Removed Property ThrottlePhysicsToRealtime
  * Removed Function ConvertSlimAcrToObj
  * Removed Function CreateAndSavePropertySet
  * Removed Function CreateExtraAssetsFileFromPropertySet
  * Removed Function FetchExtraAssets
  * Removed Function GetTestControlSchema
  * Removed Function GetTestControls
  * Removed Function RegisterTest
  * Removed Function RegisterTestLegacy
  * Removed Function ResetTestControl
  * Removed Function SetTestControl
  * Removed Function StartTestSession
  * Removed Function StopTestSession
  * Removed Function TakeSnapshot
  * Removed Function TranscodePropertySet
  * Removed Function getTestSessionProviderStats
  * Removed Function CaptureScreenshotAsync
  * Removed Function FetchTestControlsAsync
  * Removed Function RequestValidationAsync
  * Removed Function RunAsync
  * Removed Function StartVideoCaptureAsync
  * Removed Function StopVideoCaptureAsync
* Update Class [TextService](https://create.roblox.com/docs/reference/engine/classes/TextService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [SetResolutionScale](https://create.roblox.com/docs/reference/engine/classes/TextService#SetResolutionScale) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [FilterStringAsync](https://create.roblox.com/docs/reference/engine/classes/TextService#FilterStringAsync) from TextFilterResult to Instance [🏷️ Yields]
  * Removed Function GetFontMemoryData
  * Removed Function FilterAndTranslateStringAsync
  * Removed Function GetFamilyInfoAsync
  * Removed Function GetTextBoundsAsync
  * Removed Function GetTextSizeOffsetAsync
* Update Class [ThirdPartyUserService](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Function [GetUserPlatformId](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#GetUserPlatformId) () -> string [🔒 RobloxScriptSecurity]
  * Add Function [ReturnToEngagement](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#ReturnToEngagement) () -> void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ShowAccountPicker](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#ShowAccountPicker) from null to void [🔒 RobloxScriptSecurity]
  * Add Event [ActiveGamepadAdded](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#ActiveGamepadAdded) [🔒 RobloxScriptSecurity]
  * Add Event [ActiveGamepadRemoved](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#ActiveGamepadRemoved) [🔒 RobloxScriptSecurity]
  * Removed Property FriendCommunicationRestrictionStatus
  * Removed Property HasActiveUser
  * Removed Property VoiceChatRestrictionStatus
  * Removed Function GetVoiceChatRestrictionStatus
  * Removed Function IsAccountSwitchingSupported
  * Removed Function IsChatRestrictionSupported
  * Removed Function IsSingleSignOnSupported
* Update Class [ThreadState](https://create.roblox.com/docs/reference/engine/classes/ThreadState) [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Add Function [GetCallstack](https://create.roblox.com/docs/reference/engine/classes/ThreadState#GetCallstack) () -> Objects [🔒 RobloxScriptSecurity]
  * Add Function [RequestCallstack](https://create.roblox.com/docs/reference/engine/classes/ThreadState#RequestCallstack) (status: Function) -> int [🔒 RobloxScriptSecurity]
  * Removed Property FrameCount
  * Removed Property Populated
  * Removed Property ThreadName
  * Removed Function GetFrame
* Update Class [ToastNotificationService](https://create.roblox.com/docs/reference/engine/classes/ToastNotificationService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [HideNotification](https://create.roblox.com/docs/reference/engine/classes/ToastNotificationService#HideNotification) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [ShowNotification](https://create.roblox.com/docs/reference/engine/classes/ToastNotificationService#ShowNotification) from null to void [🔒 RobloxScriptSecurity]
* Update Class [TracerService](https://create.roblox.com/docs/reference/engine/classes/TracerService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [FinishSpan](https://create.roblox.com/docs/reference/engine/classes/TracerService#FinishSpan) from null to void [🔒 RobloxScriptSecurity]
* Update Class [Trail](https://create.roblox.com/docs/reference/engine/classes/Trail)
  * Changed the ValueType of Property [Texture](https://create.roblox.com/docs/reference/engine/classes/Trail#Texture) from ContentId to Content
  * Changed the return-type of Function [Clear](https://create.roblox.com/docs/reference/engine/classes/Trail#Clear) from null to void
  * Removed Property Brightness
  * Removed Property LocalTransparencyModifier
  * Removed Property TextureContent
* Update Class [TweenBase](https://create.roblox.com/docs/reference/engine/classes/TweenBase) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the return-type of Function [Cancel](https://create.roblox.com/docs/reference/engine/classes/TweenBase#Cancel) from null to void
  * Changed the return-type of Function [Pause](https://create.roblox.com/docs/reference/engine/classes/TweenBase#Pause) from null to void
  * Changed the return-type of Function [Play](https://create.roblox.com/docs/reference/engine/classes/TweenBase#Play) from null to void
* Update Class [TweenService](https://create.roblox.com/docs/reference/engine/classes/TweenService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [Create](https://create.roblox.com/docs/reference/engine/classes/TweenService#Create) from Tween to Instance
  * Removed Function SmoothDamp
* Update Class [UGCValidationService](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Function [GetMeshTriCountSync](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetMeshTriCountSync) (meshId: string) -> int [🔒 RobloxScriptSecurity]
  * Add Function [GetMeshVertsSync](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetMeshVertsSync) (meshId: string) -> Array [🔒 RobloxScriptSecurity]
  * Add Function [GetTextureSizeSync](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetTextureSizeSync) (textureId: string) -> Vector2 [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetMeshIdBlocking](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#SetMeshIdBlocking) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [FetchAssetWithFormat](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#FetchAssetWithFormat) from Instances to Objects [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Changed the parameters of Function [FetchAssetWithFormat](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#FetchAssetWithFormat)
    from: (url: ContentId, assetFormat: string)
    to: (url: Content, assetFormat: string) [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Add Function [GetMeshTriCount](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetMeshTriCount) (meshId: string) -> int [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Add Function [GetMeshVertColors](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetMeshVertColors) (meshId: string) -> Array [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Add Function [GetTextureSize](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetTextureSize) (textureId: string) -> Vector2 [🔒 RobloxScriptSecurity] [🏷️ Yields]
  * Removed Function CalculateAverageEditableCageMeshDistance
  * Removed Function CalculateEditableMeshInsideMeshPercentage
  * Removed Function CalculateEditableMeshModifiedCageBoundingBox
  * Removed Function CalculateEditableMeshNumModifiedCageUVsInSet
  * Removed Function CalculateEditableMeshTotalSurfaceArea
  * Removed Function CalculateEditableMeshUniqueUVCount
  * Removed Function CheckEditableMeshInCameraFrustum
  * Removed Function CreateEditableImageFromBinaryStringRobloxOnly
  * Removed Function CreateEditableMeshFromBinaryStringRobloxOnly
  * Removed Function GetBoundingBoxManipulationData
  * Removed Function GetDynamicHeadEditableMeshInactiveControls
  * Removed Function GetEditableCagingRelevancyMetrics
  * Removed Function GetEditableImageSize
  * Removed Function GetEditableMeshMaxNearbyVerticesCollisions
  * Removed Function GetEditableMeshSkinningTransferJointsInfo
  * Removed Function GetEditableMeshTriCount
  * Removed Function GetEditableMeshVertColors
  * Removed Function GetEditableMeshVerticesSimilarityRate
  * Removed Function GetEditableMeshVerts
  * Removed Function GetExpectedTposeRotation
  * Removed Function GetFacsDrivenJointNamesFromEditableMesh
  * Removed Function GetLayeredClothingPostDeformationSize
  * Removed Function GetMaximalJointDistancesWithinFacs
  * Removed Function GetMinAndMaxMeshSizeAcrossAllFacs
  * Removed Function GetPropertyValue
  * Removed Function GetSkinnedJointNamesFromEditableMesh
  * Removed Function IsEditableMeshNumCoplanarIntersectionsOverLimit
  * Removed Function RegisterAlternateMesh
  * Removed Function RegisterUGCValidationFunction
  * Removed Function ReportUGCValidationCounter
  * Removed Function ReportUGCValidationFailureTelemetry
  * Removed Function ReportUGCValidationTelemetry
  * Removed Function ResetCollisionFidelity
  * Removed Function ResetCollisionFidelityWithEditableMeshDataLua
  * Removed Function ValidateDynamicHeadEditableMesh
  * Removed Function ValidateEditableMeshCageMeshIntersection
  * Removed Function ValidateEditableMeshCageNonManifoldAndHoles
  * Removed Function ValidateEditableMeshCageUVCoincident
  * Removed Function ValidateEditableMeshCageUVTriangleArea
  * Removed Function ValidateEditableMeshFacialBounds
  * Removed Function ValidateEditableMeshFacialExpressiveness
  * Removed Function ValidateEditableMeshFullBodyCageDeletion
  * Removed Function ValidateEditableMeshMisMatchUV
  * Removed Function ValidateEditableMeshOverlappingVertices
  * Removed Function ValidateEditableMeshTriangleArea
  * Removed Function ValidateEditableMeshTriangles
  * Removed Function ValidateEditableMeshUVDuplicates
  * Removed Function ValidateEditableMeshUVSpace
  * Removed Function ValidateEditableMeshUVValuesInReference
  * Removed Function ValidateEditableMeshUniqueUVCount
  * Removed Function ValidateEditableMeshVertColors
  * Removed Function ValidateHSRMeshIds
  * Removed Function ValidateLeaderSkinnedVertsNearCageIslands
  * Removed Function ValidatePartBBoxAfterFullFacs
  * Removed Function ValidatePropertiesSensible
  * Removed Function ValidateSkinnedEditableMesh
  * Removed Function CalculateBodyMaxCageDistance
  * Removed Function CanLoadAsset
  * Removed Function CreateEditableImageOriginalSizeAsync
  * Removed Function DoesMeshHaveSkinningData
  * Removed Function DoesSurfaceAppearanceMatchTexturePackAsync
  * Removed Function GetMeshDataBinaryString
  * Removed Function IsDeformedLayeredClothingOutOfRenderBounds
* Update Class [UICorner](https://create.roblox.com/docs/reference/engine/classes/UICorner)
  * Removed Property BottomLeftRadius
  * Removed Property BottomRightRadius
  * Removed Property TopLeftRadius
  * Removed Property TopRightRadius
* Update Class [UIGradient](https://create.roblox.com/docs/reference/engine/classes/UIGradient)
  * Removed Property Scale
  * Removed Property TileMode
  * Removed Property Type
* Update Class [UIGridStyleLayout](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout) [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the return-type of Function [ApplyLayout](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#ApplyLayout) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [SetCustomSortFunction](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#SetCustomSortFunction) from null to void [🏷️ Deprecated]
* Update Class [UIListLayout](https://create.roblox.com/docs/reference/engine/classes/UIListLayout)
  * Removed Property HorizontalFlex
  * Removed Property ItemLineAlignment
  * Removed Property VerticalFlex
  * Removed Property Wraps
* Update Class [UIPageLayout](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout)
  * Changed the return-type of Function [JumpTo](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#JumpTo) from null to void
  * Changed the return-type of Function [JumpToIndex](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#JumpToIndex) from null to void
  * Changed the return-type of Function [Next](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Next) from null to void
  * Changed the return-type of Function [Previous](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Previous) from null to void
* Update Class [UIStroke](https://create.roblox.com/docs/reference/engine/classes/UIStroke)
  * Removed Property BorderOffset
  * Removed Property BorderStrokePosition
  * Removed Property StrokeSizingMode
  * Removed Property ZIndex
* Update Class [UnvalidatedAssetService](https://create.roblox.com/docs/reference/engine/classes/UnvalidatedAssetService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [AppendTempAssetId](https://create.roblox.com/docs/reference/engine/classes/UnvalidatedAssetService#AppendTempAssetId) from null to void [🔒 RobloxScriptSecurity]
* Update Class [UserGameSettings](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings) [🏷️ NotCreatable] [🏷️ UserSettings]
  * Changed the return-type of Function [ResetOnboardingCompleted](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#ResetOnboardingCompleted) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetCameraYInvertVisible](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetCameraYInvertVisible) from null to void
  * Changed the return-type of Function [SetGamepadCameraSensitivityVisible](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetGamepadCameraSensitivityVisible) from null to void
  * Changed the return-type of Function [SetOnboardingCompleted](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetOnboardingCompleted) from null to void
  * Changed the return-type of Function [SetTutorialState](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetTutorialState) from null to void [🔒 RobloxScriptSecurity]
  * Removed Property BadgeVisible
  * Removed Property ChatTranslationEnabled
  * Removed Property ChatTranslationFTUXShown
  * Removed Property ChatTranslationLocale
  * Removed Property ChatTranslationToggleEnabled
  * Removed Property DefaultCameraID
  * Removed Property FramerateCap
  * Removed Property GraphicsOptimizationMode
  * Removed Property HapticStrength
  * Removed Property MasterVolumeStudio
  * Removed Property MaxQualityEnabled
  * Removed Property PartyVoiceVolume
  * Removed Property PeoplePageLayout
  * Removed Property PlayerHeight
  * Removed Property PlayerListVisible
  * Removed Property PlayerNamesEnabled
  * Removed Property PreferredTextSize
  * Removed Property PreferredTransparency
  * Removed Property QualityResetLevel
  * Removed Property ReadAloud
  * Removed Property ReducedMotion
  * Removed Property StudioPreferredTextSize
  * Removed Property UiNavigationKeyBindEnabled
  * Removed Property VRComfortSetting
  * Removed Property VRSafetyBubbleMode
  * Removed Property VRSmoothRotationEnabled
  * Removed Property VRSmoothRotationEnabledCustomOption
  * Removed Property VRThirdPersonFollowCamEnabled
  * Removed Property VRThirdPersonFollowCamEnabledCustomOption
  * Removed Property VignetteEnabled
  * Removed Property VignetteEnabledCustomOption
  * Removed Property VoiceChatVolume
  * Removed Function GetDefaultFramerateCap
* Update Class [UserInputService](https://create.roblox.com/docs/reference/engine/classes/UserInputService) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Add Property [GazeSelectionEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GazeSelectionEnabled): bool [🔒 RobloxScriptSecurity] [🏷️ Hidden] [🏷️ NotReplicated]
  * Changed the return-type of Function [GetGamepadState](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetGamepadState) from Instances to Array
  * Changed the return-type of Function [GetKeysPressed](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetKeysPressed) from Instances to Array
  * Changed the return-type of Function [GetMouseButtonsPressed](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetMouseButtonsPressed) from Instances to Array
  * Changed the parameters of Function [GetStringForKeyCode](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetStringForKeyCode)
    from: (keyCode: KeyCode, format: KeyCodeStringFormat = Default)
    to: (keyCode: KeyCode)
  * Changed the return-type of Function [RecenterUserHeadCFrame](https://create.roblox.com/docs/reference/engine/classes/UserInputService#RecenterUserHeadCFrame) from null to void
  * Changed the return-type of Function [SendAppUISizes](https://create.roblox.com/docs/reference/engine/classes/UserInputService#SendAppUISizes) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetNavigationGamepad](https://create.roblox.com/docs/reference/engine/classes/UserInputService#SetNavigationGamepad) from null to void
  * Removed Property MouseIcon
  * Removed Property MouseIconContent
  * Removed Property PreferredInput
  * Removed Property TouchScreenEnabled
  * Removed Function CreateVirtualInput
  * Removed Function GetDeviceLevel
  * Removed Function GetImageForKeyCode
  * Removed Function GetPasteText
  * Removed Event TouchDrag
* Update Class [UserService](https://create.roblox.com/docs/reference/engine/classes/UserService) [🏷️ NotCreatable] [🏷️ Service]
  * Removed Function GetUserFromGlobalUserIdAsync
* Update Class [VRService](https://create.roblox.com/docs/reference/engine/classes/VRService) [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [RecenterUserHeadCFrame](https://create.roblox.com/docs/reference/engine/classes/VRService#RecenterUserHeadCFrame) from null to void
  * Changed the return-type of Function [RequestNavigation](https://create.roblox.com/docs/reference/engine/classes/VRService#RequestNavigation) from null to void
  * Changed the return-type of Function [SetTouchpadMode](https://create.roblox.com/docs/reference/engine/classes/VRService#SetTouchpadMode) from null to void
  * Removed Property AutomaticScaling
  * Removed Property AvatarGestures
  * Removed Property ControllerModels
  * Removed Property DidPointerHit
  * Removed Property FadeOutViewOnCollision
  * Removed Property LaserDistance
  * Removed Property LaserPointer
  * Removed Property PointerHitCFrame
  * Removed Property QuestASWState
  * Removed Property QuestDisplayRefreshRate
  * Removed Property ThirdPersonFollowCamEnabled
  * Removed Property VRDeviceAvailable
  * Removed Property VRSessionState
  * Removed Function IsMaquettes
  * Removed Function IsVRAppBuild
  * Removed Event LaserPointerTriggered
* Update Class [VersionControlService](https://create.roblox.com/docs/reference/engine/classes/VersionControlService) [🏷️ NotCreatable] [🏷️ Service]
  * Removed Property ScriptCollabEnabled
* Update Class [VirtualInputManager](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager) [🏷️ Service]
  * Changed the return-type of Function [Dump](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#Dump) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [HandleGamepadAxisInput](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#HandleGamepadAxisInput) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [HandleGamepadButtonInput](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#HandleGamepadButtonInput) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [HandleGamepadConnect](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#HandleGamepadConnect) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [HandleGamepadDisconnect](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#HandleGamepadDisconnect) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendAccelerometerEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendAccelerometerEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendGravityEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendGravityEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendGyroscopeEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendGyroscopeEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendKeyEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendKeyEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendMouseButtonEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendMouseButtonEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendMouseMoveEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendMouseMoveEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendMouseWheelEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendMouseWheelEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendTextInputCharacterEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendTextInputCharacterEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SendTouchEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendTouchEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [SetInputTypesToIgnore](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SetInputTypesToIgnore) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [StartPlaying](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StartPlaying) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [StartPlayingJSON](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StartPlayingJSON) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [StartRecording](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StartRecording) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [StopPlaying](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StopPlaying) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [StopRecording](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StopRecording) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [sendRobloxEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#sendRobloxEvent) from null to void [🔒 RobloxScriptSecurity]
  * Changed the return-type of Function [sendThemeChangeEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#sendThemeChangeEvent) from null to void [🔒 RobloxScriptSecurity]
  * Removed Function SendMouseMoveDeltaEvent
  * Removed Function SendScroll
  * Removed Function WaitForInputEventsProcessed
* Update Class [VirtualUser](https://create.roblox.com/docs/reference/engine/classes/VirtualUser) [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [Button1Down](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button1Down) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [Button1Down](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button1Down)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [Button1Up](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button1Up) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [Button1Up](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button1Up)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [Button2Down](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button2Down) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [Button2Down](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button2Down)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [Button2Up](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button2Up) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [Button2Up](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button2Up)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [CaptureController](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#CaptureController) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [ClickButton1](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#ClickButton1) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [ClickButton1](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#ClickButton1)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [ClickButton2](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#ClickButton2) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [ClickButton2](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#ClickButton2)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [MoveMouse](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#MoveMouse) from null to void [🔒 LocalUserSecurity]
  * Changed the parameters of Function [MoveMouse](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#MoveMouse)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity) [🔒 LocalUserSecurity]
  * Changed the return-type of Function [SetKeyDown](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#SetKeyDown) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [SetKeyUp](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#SetKeyUp) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [StartRecording](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#StartRecording) from null to void [🔒 LocalUserSecurity]
  * Changed the return-type of Function [TypeKey](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#TypeKey) from null to void [🔒 LocalUserSecurity]
* Update Class [VoiceChatService](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService) [🏷️ NotCreatable] [🏷️ Service]
  * Add Property [VoiceChatState](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#VoiceChatState): VoiceChatState [🏷️ ReadOnly] [🏷️ NotReplicated]
  * Add Function [GetAndClearCallFailureMessage](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetAndClearCallFailureMessage) () -> string
  * Add Function [GetAudioProcessingSettings](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetAudioProcessingSettings) () -> Tuple
  * Add Function [GetGroupId](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetGroupId) () -> string [🔒 RobloxScriptSecurity]
  * Add Function [GetMicDevices](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetMicDevices) () -> Tuple
  * Add Function [GetParticipants](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetParticipants) () -> Array
  * Add Function [GetSpeakerDevices](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetSpeakerDevices) () -> Tuple
  * Add Function [GetVoiceChatApiVersion](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetVoiceChatApiVersion) () -> int
  * Add Function [GetVoiceChatAvailable](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetVoiceChatAvailable) () -> int
  * Add Function [IsPublishPaused](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#IsPublishPaused) () -> bool
  * Add Function [IsSubscribePaused](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#IsSubscribePaused) (userId: int64) -> bool
  * Add Function [JoinByGroupId](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#JoinByGroupId) (groupId: string, isMicMuted: bool = false) -> bool
  * Add Function [JoinByGroupIdToken](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#JoinByGroupIdToken) (groupId: string, isMicMuted: bool = false) -> bool
  * Add Function [Leave](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#Leave) () -> void
  * Add Function [PublishPause](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#PublishPause) (paused: bool) -> bool
  * Add Function [SetMicDevice](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#SetMicDevice) (micDeviceName: string, micDeviceGuid: string) -> void
  * Add Function [SetSpeakerDevice](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#SetSpeakerDevice) (speakerDeviceName: string, speakerDeviceGuid: string) -> void
  * Add Function [SubscribePause](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#SubscribePause) (userId: int64, paused: bool) -> bool
  * Add Event [ParticipantsStateChanged](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#ParticipantsStateChanged)
  * Add Event [PlayerMicActivitySignalChange](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#PlayerMicActivitySignalChange)
  * Add Event [StateChanged](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#StateChanged)
  * Removed Property DefaultDistanceAttenuation
  * Removed Property EnableDefaultVoice
  * Removed Property EnableVoiceVolumeControls
  * Removed Property UseAudioApi
  * Removed Property UseNewAudioApi
  * Removed Property UseNewControlPaths
  * Removed Property UseNewJoinFlow
  * Removed Property UseStreamSwitching
  * Removed Property VoiceChatEnabledForPlaceOnRcc
  * Removed Property VoiceChatEnabledForUniverseOnRcc
  * Removed Function getInternalChannelId
  * Removed Function getInternalGroupId
  * Removed Function getInternalPublishPause
  * Removed Function getInternalSessionId
  * Removed Function getInternalSubscribePause
  * Removed Function getInternalSubscribePauseAll
  * Removed Function getInternalVoiceChatApiVersion
  * Removed Function isInternalPublishPaused
  * Removed Function joinVoice
  * Removed Function lastVoiceChatStats
  * Removed Function leaveVoice
  * Removed Function notifyServerACSCleanup
  * Removed Function rejoinVoice
  * Removed Function GetChatGroupsAsync
  * Removed Function IsVoiceEnabledForUserIdAsync
  * Removed Event VoiceChatStatsCollected
* Add Class [VoiceSource](https://create.roblox.com/docs/reference/engine/classes/VoiceSource) [🏷️ NotCreatable] [🏷️ Deprecated]
  * Add Property [UserId](https://create.roblox.com/docs/reference/engine/classes/VoiceSource#UserId): int64 [🏷️ ReadOnly] [🏷️ NotReplicated]
* Removed Class Object
* Removed Class AnimationNode
* Removed Class Capture
* Removed Class ScreenshotCapture
* Removed Class VideoCapture
* Removed Class ConfigSnapshot
* Removed Class EditableImage
* Removed Class EditableMesh
* Removed Class ExecutedRemoteCommand
* Removed Class AccessoryDescription
* Removed Class AccountService
* Removed Class AchievementService
* Removed Class ActivityHistoryEventService
* Removed Class AdPortal
* Removed Class AnimationClip
* Removed Class AnimationGraphDefinition
* Removed Class CurveAnimation
* Removed Class AnimationClipProvider
* Removed Class AnimationFromVideoCreatorService
* Removed Class AnimationFromVideoCreatorStudioService
* Removed Class AnimationNodeDefinition
* Removed Class AnimationRigData
* Removed Class AnimationStreamTrack
* Removed Class Annotation
* Removed Class WorkspaceAnnotation
* Removed Class AnnotationsService
* Removed Class AppAgeSignalsService
* Removed Class AppLifecycleObserverService
* Removed Class AppRatingPromptService
* Removed Class AssetPatchSettings
* Removed Class AssetQualityService
* Removed Class AudioAnalyzer
* Removed Class AudioChannelMixer
* Removed Class AudioChannelSplitter
* Removed Class AudioChorus
* Removed Class AudioCompressor
* Removed Class AudioDeviceInput
* Removed Class AudioDeviceOutput
* Removed Class AudioDistortion
* Removed Class AudioEcho
* Removed Class AudioEmitter
* Removed Class AudioEqualizer
* Removed Class AudioFader
* Removed Class AudioFilter
* Removed Class AudioFlanger
* Removed Class AudioFocusService
* Removed Class AudioGate
* Removed Class AudioLimiter
* Removed Class AudioListener
* Removed Class AudioPitchShifter
* Removed Class AudioPlayer
* Removed Class AudioRecorder
* Removed Class AudioReverb
* Removed Class AudioSearchParams
* Removed Class AudioSpeechToText
* Removed Class AudioTextToSpeech
* Removed Class AudioTremolo
* Removed Class AuroraScriptObject
* Removed Class AvatarAbilityRules
* Removed Class AvatarAccessoryRules
* Removed Class AvatarAnimationRules
* Removed Class AvatarBodyRules
* Removed Class AvatarChatService
* Removed Class AvatarClothingRules
* Removed Class AvatarCollisionRules
* Removed Class AvatarCreationService
* Removed Class AvatarRules
* Removed Class AvatarSettings
* Removed Class BaseCoreGuiConfiguration
* Removed Class CapturesViewConfiguration
* Removed Class PlayerListConfiguration
* Removed Class SelfViewConfiguration
* Removed Class BaseImportData
* Removed Class AnimationImportData
* Removed Class FacsImportData
* Removed Class GroupImportData
* Removed Class JointImportData
* Removed Class MaterialImportData
* Removed Class MeshImportData
* Removed Class RootImportData
* Removed Class BaseRemoteEvent
* Removed Class UnreliableRemoteEvent
* Removed Class WrapDeformer
* Removed Class BodyPartDescription
* Removed Class BugReporterService
* Removed Class HSRDataContentProvider
* Removed Class SlimContentProvider
* Removed Class CaptureService
* Removed Class ChangeHistoryStreamingService
* Removed Class DragDetector
* Removed Class ClientStorageService
* Removed Class CloudCRUDService
* Removed Class CloudExecutionService
* Removed Class Collaborator
* Removed Class CollaboratorsService
* Removed Class CommerceService
* Removed Class CompositeValueCurve
* Removed Class ConfigService
* Removed Class ConfigureServerService
* Removed Class ConnectivityService
* Removed Class AnimationConstraint
* Removed Class LinearVelocity
* Removed Class PlaneConstraint
* Removed Class Plane
* Removed Class RigidConstraint
* Removed Class ControllerBase
* Removed Class AirController
* Removed Class ClimbController
* Removed Class GroundController
* Removed Class SwimController
* Removed Class ControllerManager
* Removed Class CoreGuiConfiguration
* Removed Class CoreScriptDebuggingManagerHelper
* Removed Class CreationDBService
* Removed Class CreatorStoreService
* Removed Class CrossDMScriptChangeListener
* Removed Class CustomLog
* Removed Class DataModelPatchService
* Removed Class DataStoreGetOptions
* Removed Class DebuggablePluginWatcher
* Removed Class LocalDebuggerConnection
* Removed Class DebuggerLuaResponse
* Removed Class DebuggerUIService
* Removed Class DebuggerVariable
* Removed Class DeferredAssetManagerService
* Removed Class DesignFoundationsService
* Removed Class DeviceDisplayService
* Removed Class DeviceIdService
* Removed Class DigitsRigDescription
* Removed Class DisplayWakeLock
* Removed Class EditableService
* Removed Class EditorSourceService
* Removed Class EncodingService
* Removed Class EulerRotationCurve
* Removed Class ExampleV2Service
* Removed Class ExperienceAuthService
* Removed Class ExperienceInviteOptions
* Removed Class ExperienceNotificationService
* Removed Class ExperienceService
* Removed Class ExperienceStateCaptureService
* Removed Class ExperienceStateRecordingService
* Removed Class ExplorerFilter
* Removed Class ExplorerFilterAutocompleter
* Removed Class ExplorerServiceVisibilityService
* Removed Class FaceAnimatorService
* Removed Class FacialAgeEstimationService
* Removed Class FacialAnimationRecordingService
* Removed Class FacialAnimationStreamingServiceStats
* Removed Class FacialAnimationStreamingServiceV2
* Removed Class FacialAnimationStreamingSubsessionStats
* Removed Class FeatureRestrictionManager
* Removed Class FileManagerService
* Removed Class FileSyncReplicationService
* Removed Class FloatCurve
* Removed Class GeneratedFolder
* Removed Class GenerationService
* Removed Class GenericChallengeService
* Removed Class GeometryService
* Removed Class GetTextBoundsParams
* Removed Class GongService
* Removed Class CanvasGroup
* Removed Class InputActionLabel
* Removed Class RelativeGui
* Removed Class TextChannelWindow
* Removed Class VideoDisplay
* Removed Class SurfaceGuiBase
* Removed Class AdGui
* Removed Class PyramidHandleAdornment
* Removed Class WireframeHandleAdornment
* Removed Class Path2D
* Removed Class HapticEffect
* Removed Class HarmonyService
* Removed Class HeapProfilerService
* Removed Class HeatmapQueryService
* Removed Class HeatmapService
* Removed Class HiddenSurfaceRemovalAsset
* Removed Class Highlight
* Removed Class HumanoidRigDescription
* Removed Class IKControl
* Removed Class ImageScreenCaptureService
* Removed Class ImportSession
* Removed Class AssetImportSession
* Removed Class InputAction
* Removed Class InputBinding
* Removed Class InputContext
* Removed Class InstanceExtensionsService
* Removed Class InstanceFileSyncService
* Removed Class InternalMessagingService
* Removed Class InternalMessagingServiceVerifier
* Removed Class LinkingService
* Removed Class LiveScriptingService
* Removed Class LiveSyncService
* Removed Class CloudLocalizationTable
* Removed Class LodDataEntity
* Removed Class LodDataService
* Removed Class LogReporterService
* Removed Class LuauExpressionService
* Removed Class LuauScriptAnalyzerService
* Removed Class MLModelDeliveryService
* Removed Class MLService
* Removed Class MakeupDescription
* Removed Class MarkerCurve
* Removed Class MatchmakingService
* Removed Class MaterialGenerationService
* Removed Class MaterialService
* Removed Class MaterialVariant
* Removed Class MemoryStoreHashMap
* Removed Class MetaBreakpoint
* Removed Class MetaBreakpointContext
* Removed Class MetaBreakpointManager
* Removed Class MicroProfilerService
* Removed Class ModerationService
* Removed Class Noise
* Removed Class OmniRecommendationsService
* Removed Class OpenCloudApiV1
* Removed Class OpenCloudService
* Removed Class OperationGraph
* Removed Class IntersectOperation
* Removed Class ProceduralModel
* Removed Class PackageUIService
* Removed Class Packages
* Removed Class AudioPages
* Removed Class BanHistoryPages
* Removed Class CapturesPages
* Removed Class MemoryStoreHashMapPages
* Removed Class RecommendationPages
* Removed Class PartyEmulatorService
* Removed Class PatchBundlerFileWatch
* Removed Class PatchMapping
* Removed Class Path3D
* Removed Class PathfindingLink
* Removed Class PerformanceControlService
* Removed Class PinShortcutService
* Removed Class PlaceAssetIdsService
* Removed Class PlaceStatsService
* Removed Class PlacesService
* Removed Class PlatformCloudStorageService
* Removed Class PlatformFriendsService
* Removed Class PlatformLibraries
* Removed Class PlayerData
* Removed Class PlayerDataRecord
* Removed Class PlayerDataRecordConfig
* Removed Class PlayerDataService
* Removed Class PlayerHydrationService
* Removed Class PlayerViewService
* Removed Class PluginCapabilities
* Removed Class PluginConnectionService
* Removed Class PluginManagementService
* Removed Class PopLatencyService
* Removed Class ColorGradingEffect
* Removed Class Preloaded
* Removed Class ProceduralBehaviorSchedulerService
* Removed Class ProcessInstancePhysicsService
* Removed Class RTAnimationTracker
* Removed Class RealtimeMedia
* Removed Class RecommendationService
* Removed Class ReflectionService
* Removed Class RemoteCommandService
* Removed Class RemoteCursorService
* Removed Class RequestOrchestratorService
* Removed Class RibbonNotificationService
* Removed Class RobloxSerializableInstance
* Removed Class RobloxServerStorage
* Removed Class RolloutValidation
* Removed Class RolloutValidationService
* Removed Class RomarkRbxAnalyticsService
* Removed Class RomarkService
* Removed Class RotationCurve
* Removed Class RtMessagingService
* Removed Class RuntimeContentService
* Removed Class SafetyService
* Removed Class SceneAnalysisService
* Removed Class ScreenshotHud
* Removed Class ScriptBuilder
* Removed Class SyncScriptBuilder
* Removed Class ScriptChangeService
* Removed Class ScriptCloneWatcher
* Removed Class ScriptCloneWatcherHelper
* Removed Class ScriptCommitService
* Removed Class ScriptDebuggerService
* Removed Class ScriptDocument
* Removed Class ScriptEditorService
* Removed Class ScriptProfilerService
* Removed Class ScriptRegistrationService
* Removed Class ScriptRuntime
* Removed Class SelectionHighlightManager
* Removed Class SensorBase
* Removed Class AtmosphereSensor
* Removed Class BuoyancySensor
* Removed Class ControllerSensor
* Removed Class ControllerPartSensor
* Removed Class FluidForceSensor
* Removed Class SerializationService
* Removed Class ServiceVisibilityService
* Removed Class SessionCheckService
* Removed Class SharedTableRegistry
* Removed Class SlimAnimationDataEntity
* Removed Class SlimAnimationReplicationService
* Removed Class SlimDebugSettings
* Removed Class SlimReplicationService
* Removed Class SlimService
* Removed Class SmoothVoxelsUpgraderService
* Removed Class SnippetService
* Removed Class CustomSoundEffect
* Removed Class AssetSoundEffect
* Removed Class SoundShimService
* Removed Class StackFrame
* Removed Class StartPageService
* Removed Class StartupMessageService
* Removed Class StudioAssetService
* Removed Class StudioAttachment
* Removed Class StudioCallout
* Removed Class StudioCameraService
* Removed Class StudioCaptureService
* Removed Class StudioDeviceSimulatorService
* Removed Class StudioObjectBase
* Removed Class StudioWidget
* Removed Class StudioPublishService
* Removed Class StudioScreenshotCapture
* Removed Class StudioScriptDebugEventListener
* Removed Class StudioSdkService
* Removed Class StudioTestService
* Removed Class StudioUserService
* Removed Class StudioWidgetsService
* Removed Class StyleBase
* Removed Class StyleRule
* Removed Class StyleSheet
* Removed Class StyleDerive
* Removed Class StyleLink
* Removed Class StyleQuery
* Removed Class StylingService
* Removed Class SystemThemeService
* Removed Class TeamCreateData
* Removed Class TeamCreatePublishService
* Removed Class TeamCreateService
* Removed Class TelemetryService
* Removed Class TemporaryCageMeshProvider
* Removed Class TemporaryScriptService
* Removed Class TerrainDetail
* Removed Class TestCase
* Removed Class TextBoxService
* Removed Class TextChannel
* Removed Class TextChatCommand
* Removed Class TextChatConfigurations
* Removed Class BubbleChatConfiguration
* Removed Class ChannelTabsConfiguration
* Removed Class ChatInputBarConfiguration
* Removed Class ChatWindowConfiguration
* Removed Class TextChatMessage
* Removed Class TextChatMessageProperties
* Removed Class BubbleChatMessageProperties
* Removed Class ChatWindowMessageProperties
* Removed Class TextChatService
* Removed Class TextFilterTranslatedResult
* Removed Class TextGenerator
* Removed Class TextSource
* Removed Class TextureGenerationPartGroup
* Removed Class TextureGenerationService
* Removed Class TextureGenerationUnwrappingRequest
* Removed Class TraceRouteService
* Removed Class TrackerLodController
* Removed Class TrackerStreamAnimation
* Removed Class TutorialService
* Removed Class UGCAvatarService
* Removed Class UIDragDetector
* Removed Class UIFlexItem
* Removed Class UIShadow
* Removed Class UIDragDetectorService
* Removed Class UniqueIdLookupService
* Removed Class VRStatusService
* Removed Class ValueCurve
* Removed Class Vector3Curve
* Removed Class VideoCaptureService
* Removed Class VideoDeviceInput
* Removed Class VideoPlayer
* Removed Class VideoScreenCaptureService
* Removed Class VideoService
* Removed Class VisibilityCheckDispatcher
* Removed Class VisualizationMode
* Removed Class VisualizationModeCategory
* Removed Class VisualizationModeService
* Removed Class VoiceChatInternal
* Removed Class WebSocketClient
* Removed Class WebSocketService
* Removed Class WebViewService
* Removed Class WindowProtocolService
* Removed Class Wire
* Removed Class WrapDeformMeshProvider
* Removed Class WrapTextureTransfer
* Removed Class LuauExpression
* Removed Class MLSession
* Removed Class OutputLink
* Removed Class PluginConnection
* Removed Class StudioActionOverride
* Removed Class TerrainIterateOperation
* Removed Class TerrainModifyOperation
* Removed Class TerrainReadOperation
* Removed Class TerrainWriteOperation
* Removed Class VideoSampler
* Removed Class VirtualInput
* Removed Class VoxelBuffer
* Removed Class WebStreamClient
* Add Enum [ABTestLoadingStatus](https://create.roblox.com/docs/reference/engine/enums/ABTestLoadingStatus)
  * Add EnumItem ABTestLoadingStatus.None : 0
  * Add EnumItem ABTestLoadingStatus.Pending : 1
  * Add EnumItem ABTestLoadingStatus.Initialized : 2
  * Add EnumItem ABTestLoadingStatus.Error : 3
  * Add EnumItem ABTestLoadingStatus.TimedOut : 4
  * Add EnumItem ABTestLoadingStatus.ShutOff : 5
* Update Enum [AccessoryType](https://create.roblox.com/docs/reference/engine/enums/AccessoryType)
  * Removed EnumItem AccessoryType.Eyebrow
  * Removed EnumItem AccessoryType.Eyelash
* Update Enum [AlignType](https://create.roblox.com/docs/reference/engine/enums/AlignType)
  * Removed EnumItem AlignType.PrimaryAxisParallel
  * Removed EnumItem AlignType.PrimaryAxisPerpendicular
  * Removed EnumItem AlignType.PrimaryAxisLookAt
  * Removed EnumItem AlignType.AllAxes
* Update Enum [AlphaMode](https://create.roblox.com/docs/reference/engine/enums/AlphaMode)
  * Removed EnumItem AlphaMode.TintMask
  * Removed EnumItem AlphaMode.Opaque
* Update Enum [AnimationPriority](https://create.roblox.com/docs/reference/engine/enums/AnimationPriority)
  * Removed EnumItem AnimationPriority.Action2
  * Removed EnumItem AnimationPriority.Action3
  * Removed EnumItem AnimationPriority.Action4
* Update Enum [AppShellActionType](https://create.roblox.com/docs/reference/engine/enums/AppShellActionType)
  * Removed EnumItem AppShellActionType.HomePageInteractive
* Update Enum [AppShellFeature](https://create.roblox.com/docs/reference/engine/enums/AppShellFeature)
  * Removed EnumItem AppShellFeature.WatchPage
* Update Enum [AppUpdateStatus](https://create.roblox.com/docs/reference/engine/enums/AppUpdateStatus)
  * Removed EnumItem AppUpdateStatus.AvailableBoundChannel
  * Removed EnumItem AppUpdateStatus.AvailableBetaProgram
* Update Enum [AssetFetchStatus](https://create.roblox.com/docs/reference/engine/enums/AssetFetchStatus)
  * Removed EnumItem AssetFetchStatus.None
  * Removed EnumItem AssetFetchStatus.Loading
  * Removed EnumItem AssetFetchStatus.TimedOut
* Update Enum [AssetType](https://create.roblox.com/docs/reference/engine/enums/AssetType)
  * Removed EnumItem AssetType.FontFamily
  * Removed EnumItem AssetType.EyebrowAccessory
  * Removed EnumItem AssetType.EyelashAccessory
  * Removed EnumItem AssetType.MoodAnimation
  * Removed EnumItem AssetType.DynamicHead
  * Removed EnumItem AssetType.FaceMakeup
  * Removed EnumItem AssetType.LipMakeup
  * Removed EnumItem AssetType.EyeMakeup
  * Removed EnumItem AssetType.AvatarBackground
  * Removed EnumItem AssetType.TextDocument
* Update Enum [AvatarAssetType](https://create.roblox.com/docs/reference/engine/enums/AvatarAssetType)
  * Removed EnumItem AvatarAssetType.EyebrowAccessory
  * Removed EnumItem AvatarAssetType.EyelashAccessory
  * Removed EnumItem AvatarAssetType.MoodAnimation
  * Removed EnumItem AvatarAssetType.DynamicHead
  * Removed EnumItem AvatarAssetType.FaceMakeup
  * Removed EnumItem AvatarAssetType.LipMakeup
  * Removed EnumItem AvatarAssetType.EyeMakeup
  * Removed EnumItem AvatarAssetType.AvatarBackground
* Update Enum [BundleType](https://create.roblox.com/docs/reference/engine/enums/BundleType)
  * Removed EnumItem BundleType.Shoes
  * Removed EnumItem BundleType.DynamicHead
  * Removed EnumItem BundleType.DynamicHeadAvatar
* Update Enum [CatalogSortType](https://create.roblox.com/docs/reference/engine/enums/CatalogSortType)
  * Add EnumItem CatalogSortType.RecentlyUpdated : 4
  * Removed EnumItem CatalogSortType.RecentlyCreated
  * Removed EnumItem CatalogSortType.Bestselling
* Update Enum [CollisionFidelity](https://create.roblox.com/docs/reference/engine/enums/CollisionFidelity)
  * Removed EnumItem CollisionFidelity.Scalable
* Update Enum [ConnectionError](https://create.roblox.com/docs/reference/engine/enums/ConnectionError)
  * Removed EnumItem ConnectionError.Unknown
  * Removed EnumItem ConnectionError.ConnectErrors
  * Removed EnumItem ConnectionError.AlreadyConnected
  * Removed EnumItem ConnectionError.NoFreeIncomingConnections
  * Removed EnumItem ConnectionError.ConnectionBanned
  * Removed EnumItem ConnectionError.InvalidPassword
  * Removed EnumItem ConnectionError.IncompatibleProtocolVersion
  * Removed EnumItem ConnectionError.IPRecentlyConnected
  * Removed EnumItem ConnectionError.OurSystemRequiresSecurity
  * Removed EnumItem ConnectionError.SecurityKeyMismatch
  * Removed EnumItem ConnectionError.DisconnectClientRequest
  * Removed EnumItem ConnectionError.DisconnectPrivateServerKickout
  * Removed EnumItem ConnectionError.DisconnectModeratedGame
  * Removed EnumItem ConnectionError.ServerShutdown
  * Removed EnumItem ConnectionError.ReplicatorTimeout
  * Removed EnumItem ConnectionError.PlayerRemoved
  * Removed EnumItem ConnectionError.DisconnectOutOfMemoryKeepPlayingLeave
  * Removed EnumItem ConnectionError.DisconnectRomarkEndOfTest
  * Removed EnumItem ConnectionError.DisconnectCollaboratorPermissionRevoked
  * Removed EnumItem ConnectionError.DisconnectCollaboratorUnderage
  * Removed EnumItem ConnectionError.NetworkInternal
  * Removed EnumItem ConnectionError.NetworkSend
  * Removed EnumItem ConnectionError.NetworkTimeout
  * Removed EnumItem ConnectionError.NetworkMisbehavior
  * Removed EnumItem ConnectionError.NetworkSecurity
  * Removed EnumItem ConnectionError.ReplacementReady
  * Removed EnumItem ConnectionError.ServerEmpty
  * Removed EnumItem ConnectionError.PhantomFreeze
  * Removed EnumItem ConnectionError.AndroidAnticheatKick
  * Removed EnumItem ConnectionError.AndroidEmulatorKick
  * Removed EnumItem ConnectionError.AndroidRootedKick
  * Removed EnumItem ConnectionError.ScreentimeLockoutKick
  * Removed EnumItem ConnectionError.DisconnectionNotification
  * Removed EnumItem ConnectionError.DisconnectVerboselyModeratedGame
  * Removed EnumItem ConnectionError.DisconnectCollaboratorNotAgeVerified
  * Removed EnumItem ConnectionError.DisconnectCollaboratorTrustedConnectionsRequired
  * Removed EnumItem ConnectionError.DisconnectCollaboratorOwnerActionRequired
  * Removed EnumItem ConnectionError.DisconnectCollaboratorTooManyCollaborators
  * Removed EnumItem ConnectionError.DisconnectCollaboratorUnknownError
  * Removed EnumItem ConnectionError.DisconnectCollaboratorRequestedEviction
  * Removed EnumItem ConnectionError.DisconnectCollaboratorTrustedConnectionsRequiredPC
  * Removed EnumItem ConnectionError.DisconnectRemoteAttestationUnsupported
  * Removed EnumItem ConnectionError.DisconnectRemoteAttestationGeneralFailure
  * Removed EnumItem ConnectionError.DisconnectRemoteAttestationTimeout
  * Removed EnumItem ConnectionError.DisconnectRemoteAttestationOSOutOfDate
  * Removed EnumItem ConnectionError.DisconnectRemoteAttestationBootValidationFailure
  * Removed EnumItem ConnectionError.PlacelaunchUserPrivacyUnauthorized
  * Removed EnumItem ConnectionError.PlacelaunchVipOwnerNotPresent
  * Removed EnumItem ConnectionError.PlacelaunchAgeVerificationRequired
  * Removed EnumItem ConnectionError.PlacelaunchParentalApprovalRequired
  * Removed EnumItem ConnectionError.PlacelaunchCoreGated
  * Removed EnumItem ConnectionError.PlacelaunchCollaborationCoreGated
  * Removed EnumItem ConnectionError.PlacelaunchCreatorBan
  * Removed EnumItem ConnectionError.PlacelaunchDeviceBlock
* Update Enum [ContextActionPriority](https://create.roblox.com/docs/reference/engine/enums/ContextActionPriority)
  * Add EnumItem ContextActionPriority.Default : 2000
* Update Enum [CoreGuiType](https://create.roblox.com/docs/reference/engine/enums/CoreGuiType)
  * Removed EnumItem CoreGuiType.SelfView
  * Removed EnumItem CoreGuiType.Captures
  * Removed EnumItem CoreGuiType.AvatarSwitcher
  * Removed EnumItem CoreGuiType.ExperienceShop
* Update Enum [DataStoreRequestType](https://create.roblox.com/docs/reference/engine/enums/DataStoreRequestType)
  * Removed EnumItem DataStoreRequestType.ListAsync
  * Removed EnumItem DataStoreRequestType.GetVersionAsync
  * Removed EnumItem DataStoreRequestType.RemoveVersionAsync
  * Removed EnumItem DataStoreRequestType.StandardRead
  * Removed EnumItem DataStoreRequestType.StandardWrite
  * Removed EnumItem DataStoreRequestType.StandardList
  * Removed EnumItem DataStoreRequestType.StandardRemove
  * Removed EnumItem DataStoreRequestType.OrderedRead
  * Removed EnumItem DataStoreRequestType.OrderedWrite
  * Removed EnumItem DataStoreRequestType.OrderedList
  * Removed EnumItem DataStoreRequestType.OrderedRemove
* Update Enum [DebuggerStatus](https://create.roblox.com/docs/reference/engine/enums/DebuggerStatus)
  * Removed EnumItem DebuggerStatus.ConnectionClosed
* Update Enum [DeveloperMemoryTag](https://create.roblox.com/docs/reference/engine/enums/DeveloperMemoryTag)
  * Add EnumItem DeveloperMemoryTag.PhysicsParts : 7
  * Removed EnumItem DeveloperMemoryTag.BaseParts
  * Removed EnumItem DeveloperMemoryTag.GeometryCSG
  * Removed EnumItem DeveloperMemoryTag.GraphicsSlimModels
* Update Enum [DeviceType](https://create.roblox.com/docs/reference/engine/enums/DeviceType)
  * Removed EnumItem DeviceType.TV
* Update Enum [Font](https://create.roblox.com/docs/reference/engine/enums/Font)
  * Add EnumItem Font.GothamSemibold : 18
  * Removed EnumItem Font.GothamMedium
  * Removed EnumItem Font.BuilderSans
  * Removed EnumItem Font.BuilderSansMedium
  * Removed EnumItem Font.BuilderSansBold
  * Removed EnumItem Font.BuilderSansExtraBold
  * Removed EnumItem Font.Arimo
  * Removed EnumItem Font.ArimoBold
  * Removed EnumItem Font.Unknown
* Update Enum [GraphicsMode](https://create.roblox.com/docs/reference/engine/enums/GraphicsMode)
  * Add EnumItem GraphicsMode.Direct3D9 : 3
* Update Enum [HttpError](https://create.roblox.com/docs/reference/engine/enums/HttpError)
  * Removed EnumItem HttpError.ConnectionClosed
  * Removed EnumItem HttpError.ServerProtocolError
  * Removed EnumItem HttpError.CreatorEnvironmentsNotSupportedByService
  * Removed EnumItem HttpError.InactivityTimeout
  * Removed EnumItem HttpError.TooManyOutstandingRequests
  * Removed EnumItem HttpError.InvalidRangeResponse
* Add Enum [HumanoidOnlySetCollisionsOnStateChange](https://create.roblox.com/docs/reference/engine/enums/HumanoidOnlySetCollisionsOnStateChange)
  * Add EnumItem HumanoidOnlySetCollisionsOnStateChange.Default : 0
  * Add EnumItem HumanoidOnlySetCollisionsOnStateChange.Disabled : 1
  * Add EnumItem HumanoidOnlySetCollisionsOnStateChange.Enabled : 2
* Update Enum [IXPLoadingStatus](https://create.roblox.com/docs/reference/engine/enums/IXPLoadingStatus)
  * Add EnumItem IXPLoadingStatus.ShutOff : 3
* Update Enum [KeyCode](https://create.roblox.com/docs/reference/engine/enums/KeyCode)
  * Add EnumItem KeyCode.Unknown : 0
  * Removed EnumItem KeyCode.None
  * Removed EnumItem KeyCode.Thumbstick1Up
  * Removed EnumItem KeyCode.Thumbstick1Down
  * Removed EnumItem KeyCode.Thumbstick1Left
  * Removed EnumItem KeyCode.Thumbstick1Right
  * Removed EnumItem KeyCode.Thumbstick2Up
  * Removed EnumItem KeyCode.Thumbstick2Down
  * Removed EnumItem KeyCode.Thumbstick2Left
  * Removed EnumItem KeyCode.Thumbstick2Right
  * Removed EnumItem KeyCode.MouseLeftButton
  * Removed EnumItem KeyCode.MouseRightButton
  * Removed EnumItem KeyCode.MouseMiddleButton
  * Removed EnumItem KeyCode.MouseBackButton
  * Removed EnumItem KeyCode.MouseNoButton
  * Removed EnumItem KeyCode.MouseX
  * Removed EnumItem KeyCode.MouseY
  * Removed EnumItem KeyCode.MousePosition
  * Removed EnumItem KeyCode.TouchPosition
  * Removed EnumItem KeyCode.MouseWheel
  * Removed EnumItem KeyCode.TrackpadPan
  * Removed EnumItem KeyCode.TrackpadPinch
  * Removed EnumItem KeyCode.MouseDelta
  * Removed EnumItem KeyCode.TouchDelta
  * Removed EnumItem KeyCode.TouchPinch
  * Removed EnumItem KeyCode.ButtonCenter
  * Removed EnumItem KeyCode.ButtonBack
  * Removed EnumItem KeyCode.ButtonUp
  * Removed EnumItem KeyCode.ButtonDown
  * Removed EnumItem KeyCode.ButtonLeft
  * Removed EnumItem KeyCode.ButtonRight
* Add Enum [LevelOfDetailSetting](https://create.roblox.com/docs/reference/engine/enums/LevelOfDetailSetting)
  * Add EnumItem LevelOfDetailSetting.High : 2
  * Add EnumItem LevelOfDetailSetting.Medium : 1
  * Add EnumItem LevelOfDetailSetting.Low : 0
* Update Enum [Material](https://create.roblox.com/docs/reference/engine/enums/Material)
  * Removed EnumItem Material.Cardboard
  * Removed EnumItem Material.Carpet
  * Removed EnumItem Material.CeramicTiles
  * Removed EnumItem Material.ClayRoofTiles
  * Removed EnumItem Material.RoofShingles
  * Removed EnumItem Material.Leather
  * Removed EnumItem Material.Plaster
  * Removed EnumItem Material.Rubber
* Update Enum [MeshPartDetailLevel](https://create.roblox.com/docs/reference/engine/enums/MeshPartDetailLevel)
  * Removed EnumItem MeshPartDetailLevel.Level00
  * Removed EnumItem MeshPartDetailLevel.Level05
  * Removed EnumItem MeshPartDetailLevel.Level06
  * Removed EnumItem MeshPartDetailLevel.Level07
  * Removed EnumItem MeshPartDetailLevel.Level08
  * Removed EnumItem MeshPartDetailLevel.Level09
* Update Enum [ModelLevelOfDetail](https://create.roblox.com/docs/reference/engine/enums/ModelLevelOfDetail)
  * Removed EnumItem ModelLevelOfDetail.SLIM
* Add Enum [NewAnimationRuntimeSetting](https://create.roblox.com/docs/reference/engine/enums/NewAnimationRuntimeSetting)
  * Add EnumItem NewAnimationRuntimeSetting.Default : 0
  * Add EnumItem NewAnimationRuntimeSetting.Disabled : 1
  * Add EnumItem NewAnimationRuntimeSetting.Enabled : 2
* Add Enum [PacketPriority](https://create.roblox.com/docs/reference/engine/enums/PacketPriority)
  * Add EnumItem PacketPriority.IMMEDIATE_PRIORITY : 0
  * Add EnumItem PacketPriority.HIGH_PRIORITY : 1
  * Add EnumItem PacketPriority.MEDIUM_PRIORITY : 2
  * Add EnumItem PacketPriority.LOW_PRIORITY : 3
* Update Enum [PartType](https://create.roblox.com/docs/reference/engine/enums/PartType)
  * Removed EnumItem PartType.Wedge
  * Removed EnumItem PartType.CornerWedge
* Update Enum [PathWaypointAction](https://create.roblox.com/docs/reference/engine/enums/PathWaypointAction)
  * Removed EnumItem PathWaypointAction.Custom
* Update Enum [Platform](https://create.roblox.com/docs/reference/engine/enums/Platform)
  * Removed EnumItem Platform.PS5
  * Removed EnumItem Platform.MetaOS
  * Removed EnumItem Platform.Web
* Update Enum [PoseEasingStyle](https://create.roblox.com/docs/reference/engine/enums/PoseEasingStyle)
  * Removed EnumItem PoseEasingStyle.CubicV2
* Update Enum [RaycastFilterType](https://create.roblox.com/docs/reference/engine/enums/RaycastFilterType)
  * Add EnumItem RaycastFilterType.Blacklist : 0
  * Add EnumItem RaycastFilterType.Whitelist : 1
  * Removed EnumItem RaycastFilterType.Exclude
  * Removed EnumItem RaycastFilterType.Include
* Update Enum [RibbonTool](https://create.roblox.com/docs/reference/engine/enums/RibbonTool)
  * Removed EnumItem RibbonTool.PivotEditor
* Add Enum [ServerAudioBehavior](https://create.roblox.com/docs/reference/engine/enums/ServerAudioBehavior)
  * Add EnumItem ServerAudioBehavior.Enabled : 0
  * Add EnumItem ServerAudioBehavior.Muted : 1
  * Add EnumItem ServerAudioBehavior.OnlineGame : 2
* Update Enum [SignalBehavior](https://create.roblox.com/docs/reference/engine/enums/SignalBehavior)
  * Removed EnumItem SignalBehavior.AncestryDeferred
* Add Enum [SoundType](https://create.roblox.com/docs/reference/engine/enums/SoundType)
  * Add EnumItem SoundType.NoSound : 0
  * Add EnumItem SoundType.Boing : 1
  * Add EnumItem SoundType.Bomb : 2
  * Add EnumItem SoundType.Break : 3
  * Add EnumItem SoundType.Click : 4
  * Add EnumItem SoundType.Clock : 5
  * Add EnumItem SoundType.Slingshot : 6
  * Add EnumItem SoundType.Page : 7
  * Add EnumItem SoundType.Ping : 8
  * Add EnumItem SoundType.Snap : 9
  * Add EnumItem SoundType.Splat : 10
  * Add EnumItem SoundType.Step : 11
  * Add EnumItem SoundType.StepOn : 12
  * Add EnumItem SoundType.Swoosh : 13
  * Add EnumItem SoundType.Victory : 14
* Update Enum [StudioCloseMode](https://create.roblox.com/docs/reference/engine/enums/StudioCloseMode)
  * Removed EnumItem StudioCloseMode.LogOut
* Update Enum [StudioDataModelType](https://create.roblox.com/docs/reference/engine/enums/StudioDataModelType)
  * Add EnumItem StudioDataModelType.RobloxPlugin : 3
  * Add EnumItem StudioDataModelType.UserPlugin : 4
  * Removed EnumItem StudioDataModelType.Standalone
* Update Enum [StudioScriptEditorColorCategories](https://create.roblox.com/docs/reference/engine/enums/StudioScriptEditorColorCategories)
  * Removed EnumItem StudioScriptEditorColorCategories.Info
  * Removed EnumItem StudioScriptEditorColorCategories.Hint
  * Removed EnumItem StudioScriptEditorColorCategories.Type
  * Removed EnumItem StudioScriptEditorColorCategories.DocViewCodeBackground
  * Removed EnumItem StudioScriptEditorColorCategories.AICOOverlayText
  * Removed EnumItem StudioScriptEditorColorCategories.AICOOverlayButtonBackground
  * Removed EnumItem StudioScriptEditorColorCategories.AICOOverlayButtonBackgroundHover
  * Removed EnumItem StudioScriptEditorColorCategories.AICOOverlayButtonBackgroundPressed
  * Removed EnumItem StudioScriptEditorColorCategories.IndentationRuler
* Update Enum [StudioStyleGuideColor](https://create.roblox.com/docs/reference/engine/enums/StudioStyleGuideColor)
  * Removed EnumItem StudioStyleGuideColor.DropShadow
  * Removed EnumItem StudioStyleGuideColor.ScriptInformation
  * Removed EnumItem StudioStyleGuideColor.ScriptHint
  * Removed EnumItem StudioStyleGuideColor.DocViewCodeBackground
  * Removed EnumItem StudioStyleGuideColor.AICOOverlayText
  * Removed EnumItem StudioStyleGuideColor.AICOOverlayButtonBackground
  * Removed EnumItem StudioStyleGuideColor.AICOOverlayButtonBackgroundHover
  * Removed EnumItem StudioStyleGuideColor.AICOOverlayButtonBackgroundPressed
  * Removed EnumItem StudioStyleGuideColor.OnboardingCover
  * Removed EnumItem StudioStyleGuideColor.OnboardingHighlight
  * Removed EnumItem StudioStyleGuideColor.OnboardingShadow
  * Removed EnumItem StudioStyleGuideColor.BreakpointMarker
  * Removed EnumItem StudioStyleGuideColor.DiffLineNumHover
  * Removed EnumItem StudioStyleGuideColor.DiffLineNumSeparatorBackgroundHover
* Update Enum [Technology](https://create.roblox.com/docs/reference/engine/enums/Technology)
  * Removed EnumItem Technology.Unified
* Update Enum [TeleportMethod](https://create.roblox.com/docs/reference/engine/enums/TeleportMethod)
  * Removed EnumItem TeleportMethod.TeleportToVIPServer
  * Removed EnumItem TeleportMethod.TeleportToInstanceBack
* Update Enum [TeleportType](https://create.roblox.com/docs/reference/engine/enums/TeleportType)
  * Removed EnumItem TeleportType.ToVIPServer
  * Removed EnumItem TeleportType.ToInstanceBack
* Update Enum [TextInputType](https://create.roblox.com/docs/reference/engine/enums/TextInputType)
  * Removed EnumItem TextInputType.NewPassword
  * Removed EnumItem TextInputType.NewPasswordShown
* Update Enum [TextTruncate](https://create.roblox.com/docs/reference/engine/enums/TextTruncate)
  * Removed EnumItem TextTruncate.SplitWord
* Update Enum [UserCFrame](https://create.roblox.com/docs/reference/engine/enums/UserCFrame)
  * Removed EnumItem UserCFrame.Floor
* Update Enum [WrapLayerDebugMode](https://create.roblox.com/docs/reference/engine/enums/WrapLayerDebugMode)
  * Removed EnumItem WrapLayerDebugMode.ReferenceMeshAfterMorph
  * Removed EnumItem WrapLayerDebugMode.HSROuterDetail
  * Removed EnumItem WrapLayerDebugMode.HSROuter
  * Removed EnumItem WrapLayerDebugMode.HSRInner
  * Removed EnumItem WrapLayerDebugMode.HSRInnerReverse
  * Removed EnumItem WrapLayerDebugMode.LayerCageFittedToBase
  * Removed EnumItem WrapLayerDebugMode.LayerCageFittedToPrev
  * Removed EnumItem WrapLayerDebugMode.PreWrapDeformerOuterCage
  * Removed EnumItem WrapLayerDebugMode.SkinningTransfer
* Update Enum [WrapTargetDebugMode](https://create.roblox.com/docs/reference/engine/enums/WrapTargetDebugMode)
  * Removed EnumItem WrapTargetDebugMode.OuterCageDetail
  * Removed EnumItem WrapTargetDebugMode.PreWrapDeformerCage
* Removed Enum AccessModifierType
* Removed Enum ActionOnAutoResumeSync
* Removed Enum ActionOnStopSync
* Removed Enum ActivePayerStatus
* Removed Enum AdAvailabilityResult
* Removed Enum AdEventType
* Removed Enum AdFormat
* Removed Enum AdShape
* Removed Enum AdTeleportMethod
* Removed Enum AdUIEventType
* Removed Enum AdUIType
* Removed Enum AdUnitStatus
* Removed Enum AdornShading
* Removed Enum AgeCheckStatus
* Removed Enum AnalyticsCustomFieldKeys
* Removed Enum AnalyticsEconomyFlowType
* Removed Enum AnalyticsEconomyTransactionType
* Removed Enum AnalyticsProgressionType
* Removed Enum AnimationClipFromVideoStatus
* Removed Enum AnimationNodeBlend2DInputMode
* Removed Enum AnimationNodeInterruptible
* Removed Enum AnimationNodePhaseSync
* Removed Enum AnimationNodePlayMode
* Removed Enum AnimationNodeTransitionType
* Removed Enum AnimationNodeType
* Removed Enum AnimationNodeWaitFor
* Removed Enum AnimatorRetargetingMode
* Removed Enum AnnotationChannelContentPreference
* Removed Enum AnnotationEditingMode
* Removed Enum AnnotationPlaceContentPreference
* Removed Enum AnnotationRequestStatus
* Removed Enum AnnotationRequestType
* Removed Enum AntiAliasing
* Removed Enum AppLifecycleManagerState
* Removed Enum ApplyShadowMode
* Removed Enum AssetCreatorType
* Removed Enum AssetRepresentation
* Removed Enum AudioApiRollout
* Removed Enum AudioCaptureMode
* Removed Enum AudioChannelLayout
* Removed Enum AudioFilterType
* Removed Enum AudioSimulationFidelity
* Removed Enum AudioSubType
* Removed Enum AudioWindowSize
* Removed Enum AuthorityMode
* Removed Enum AvatarChatServiceFeature
* Removed Enum AvatarGenerationError
* Removed Enum AvatarSettingsAccessoryLimitMethod
* Removed Enum AvatarSettingsAccessoryMode
* Removed Enum AvatarSettingsAnimationClipsMode
* Removed Enum AvatarSettingsAnimationPacksMode
* Removed Enum AvatarSettingsAppearanceMode
* Removed Enum AvatarSettingsBuildMode
* Removed Enum AvatarSettingsCharacterControllerMode
* Removed Enum AvatarSettingsClothingMode
* Removed Enum AvatarSettingsCollisionMode
* Removed Enum AvatarSettingsCustomAccessoryMode
* Removed Enum AvatarSettingsCustomBodyType
* Removed Enum AvatarSettingsCustomClothingMode
* Removed Enum AvatarSettingsHitAndTouchDetectionMode
* Removed Enum AvatarSettingsJumpMode
* Removed Enum AvatarSettingsLegacyCollisionMode
* Removed Enum AvatarSettingsScaleMode
* Removed Enum AvatarThumbnailCustomizationType
* Removed Enum AvatarUnificationMode
* Removed Enum BenefitType
* Removed Enum BorderStrokePosition
* Removed Enum CameraNavigationModel
* Removed Enum CameraSpeedAdjustBinding
* Removed Enum CanCollaborateError
* Removed Enum CaptureGalleryPermission
* Removed Enum CaptureType
* Removed Enum CatalogSortAggregation
* Removed Enum CharacterControlMode
* Removed Enum ChatRestrictionStatus
* Removed Enum ChatVersion
* Removed Enum CloseReason
* Removed Enum CollaboratorStatus
* Removed Enum CompileTarget
* Removed Enum CompletionAcceptanceBehavior
* Removed Enum CompletionItemKind
* Removed Enum CompletionItemTag
* Removed Enum CompletionTriggerKind
* Removed Enum CompositeValueCurveType
* Removed Enum CompressionAlgorithm
* Removed Enum ConfigSnapshotErrorState
* Removed Enum ContentSourceType
* Removed Enum CreateAssetResult
* Removed Enum CreateContentResult
* Removed Enum CreatorTypeFilter
* Removed Enum DataModelExtractorFileType
* Removed Enum DebugBreakModeType
* Removed Enum DebuggerExceptionBreakMode
* Removed Enum DebuggerResumeType
* Removed Enum DefaultScriptSyncFileType
* Removed Enum DeviceFeatureType
* Removed Enum DeviceForm
* Removed Enum DeviceLevel
* Removed Enum DeviceSimulatorScalingMode
* Removed Enum DigitsRigDescriptionSide
* Removed Enum DiscountType
* Removed Enum DisplayScalingMode
* Removed Enum DisplaySize
* Removed Enum DistanceAttenuationMode
* Removed Enum DomainType
* Removed Enum DragDetectorDragStyle
* Removed Enum DragDetectorPermissionPolicy
* Removed Enum DragDetectorResponseStyle
* Removed Enum DraggingScrollBar
* Removed Enum EditableStatus
* Removed Enum EmitterPositionType
* Removed Enum EngagementLevel
* Removed Enum EngineFolder
* Removed Enum ExperienceActivationStatus
* Removed Enum ExperienceAuthScope
* Removed Enum ExperienceEventStatus
* Removed Enum ExperienceStateCaptureSelectionMode
* Removed Enum ExperienceStateRecordingLoadMode
* Removed Enum ExperienceStateRecordingLoadSourceType
* Removed Enum ExperienceStateRecordingPlaybackMode
* Removed Enum ExternalEditorMode
* Removed Enum FACSDataLod
* Removed Enum FacialAgeEstimationResultType
* Removed Enum FacialAnimationStreamingState
* Removed Enum FacsActionUnit
* Removed Enum FeatureRestrictionAbuseVector
* Removed Enum FeedbackType
* Removed Enum FilterErrorType
* Removed Enum FilterType
* Removed Enum FinishRecordingOperation
* Removed Enum FluidFidelity
* Removed Enum FluidForces
* Removed Enum FontStyle
* Removed Enum FontWeight
* Removed Enum ForceLimitMode
* Removed Enum GamepadType
* Removed Enum GenerateMomentTextResult
* Removed Enum GradientTileMode
* Removed Enum GradientType
* Removed Enum GraphicsOptimizationMode
* Removed Enum GroupMembershipStatus
* Removed Enum GuiState
* Removed Enum GuiType
* Removed Enum HapticEffectType
* Removed Enum HashAlgorithm
* Removed Enum HighlightDepthMode
* Removed Enum HttpCompression
* Removed Enum IKControlConstraintSupport
* Removed Enum IKControlType
* Removed Enum ImageAlphaType
* Removed Enum ImageCombineType
* Removed Enum InputActionType
* Removed Enum InputBindingType
* Removed Enum InputSink
* Removed Enum InstanceFileSyncStatus
* Removed Enum IntermediateMeshGenerationResult
* Removed Enum InternalVideoUsage
* Removed Enum InviteState
* Removed Enum ItemLineAlignment
* Removed Enum JoinSource
* Removed Enum KeyCodeStringFormat
* Removed Enum KeyInterpolationMode
* Removed Enum KnownWindow
* Removed Enum LexemeType
* Removed Enum LightingStyle
* Removed Enum ListenerLocation
* Removed Enum ListenerPositionType
* Removed Enum LiveEditingAtomicUpdateResponse
* Removed Enum LiveEditingBroadcastMessageType
* Removed Enum LoadDynamicHeads
* Removed Enum LocationType
* Removed Enum LuauTypeCheckMode
* Removed Enum MakeupType
* Removed Enum MarketplaceBulkPurchasePromptStatus
* Removed Enum MarketplaceItemPurchaseStatus
* Removed Enum MarketplaceProductType
* Removed Enum MarkupKind
* Removed Enum MatchmakingType
* Removed Enum MaterialPattern
* Removed Enum MeshAttribute
* Removed Enum ModelStreamingBehavior
* Removed Enum ModelStreamingMode
* Removed Enum ModerationResultCategory
* Removed Enum ModerationResultLabel
* Removed Enum ModerationStatus
* Removed Enum MuteState
* Removed Enum NegateOperationHiddenHistory
* Removed Enum NetworkStatus
* Removed Enum NoiseType
* Removed Enum NotificationButtonType
* Removed Enum OperationType
* Removed Enum OrientationAlignmentMode
* Removed Enum OutfitType
* Removed Enum ParticleEmitterShape
* Removed Enum ParticleEmitterShapeInOut
* Removed Enum ParticleEmitterShapeStyle
* Removed Enum ParticleFlipbookLayout
* Removed Enum ParticleFlipbookMode
* Removed Enum ParticleFlipbookTextureCompatible
* Removed Enum PathfindingUseImprovedSearch
* Removed Enum PeoplePageLayout
* Removed Enum PerformanceOverlayMode
* Removed Enum PhysicalConstraintType
* Removed Enum PioneerSource
* Removed Enum PlaceContentPreference
* Removed Enum PlacePublishType
* Removed Enum PlayerCharacterDestroyBehavior
* Removed Enum PlayerDataErrorState
* Removed Enum PlayerDataLoadFailureBehavior
* Removed Enum PlayerExitReason
* Removed Enum PlayerPlatformActivationStatus
* Removed Enum PlayerPlatformSpenderStatus
* Removed Enum PluginConnectionTargetType
* Removed Enum PositionAlignmentMode
* Removed Enum PredictionMode
* Removed Enum PredictionStatus
* Removed Enum PredictiveStreamingMode
* Removed Enum PreferredInput
* Removed Enum PreferredTextSize
* Removed Enum PrefetchDownloadStatus
* Removed Enum PrimalPhysicsSolver
* Removed Enum PrimitiveType
* Removed Enum ProductPurchaseChannel
* Removed Enum PromptCreateAssetResult
* Removed Enum PromptCreateAvatarResult
* Removed Enum PromptCreateOutfitResult
* Removed Enum PromptExperienceDetailsResult
* Removed Enum PromptLinkSharingResult
* Removed Enum PromptPublishAssetResult
* Removed Enum PropertyStatus
* Removed Enum PurchaseOption
* Removed Enum ReadCapturesFromGalleryResult
* Removed Enum ReceiptDecision
* Removed Enum ReceiptType
* Removed Enum RecommendationActionType
* Removed Enum RecommendationDepartureIntent
* Removed Enum RecommendationImpressionType
* Removed Enum RecommendationItemContentType
* Removed Enum RecommendationItemVisibility
* Removed Enum RecommendationPreferenceTargetType
* Removed Enum RecommendationPreferenceType
* Removed Enum RejectCharacterDeletions
* Removed Enum RenderingCacheOptimizationMode
* Removed Enum ReplicateInstanceDestroySetting
* Removed Enum ReservedHighlightId
* Removed Enum RestPose
* Removed Enum RestPoseModel
* Removed Enum ReviewableContentState
* Removed Enum RigLabel
* Removed Enum RigScale
* Removed Enum RigType
* Removed Enum RolloutState
* Removed Enum RotationOrder
* Removed Enum RsvpStatus
* Removed Enum RtlTextSupport
* Removed Enum RunContext
* Removed Enum RunState
* Removed Enum SafeAreaCompatibility
* Removed Enum SalesTypeFilter
* Removed Enum SandboxedInstanceMode
* Removed Enum SaveAvatarThumbnailCustomizationFailure
* Removed Enum ScopeCheckResult
* Removed Enum ScreenInsets
* Removed Enum ScreenshotCaptureResult
* Removed Enum ScriptStoppedReason
* Removed Enum ScriptVariableScope
* Removed Enum SecurityCapability
* Removed Enum SelectionBehavior
* Removed Enum SelectionRenderMode
* Removed Enum SelfViewPosition
* Removed Enum SensorMode
* Removed Enum SensorUpdateType
* Removed Enum ServerLiveEditingMode
* Removed Enum ServiceVisibility
* Removed Enum Severity
* Removed Enum ShowAdResult
* Removed Enum SimulationMode
* Removed Enum SlimTintMode
* Removed Enum SolidPrimitiveType
* Removed Enum SolverConvergenceMetricType
* Removed Enum SolverConvergenceVisualizationMode
* Removed Enum StateObjectFieldType
* Removed Enum StepFrequency
* Removed Enum StreamingIntegrityMode
* Removed Enum StrokeSizingMode
* Removed Enum StudioAction
* Removed Enum StudioCaptureBufferStatus
* Removed Enum StudioCaptureScreenshotFormat
* Removed Enum StudioPlaceUpdateFailureReason
* Removed Enum SubscriptionExpirationReason
* Removed Enum SubscriptionPaymentStatus
* Removed Enum SubscriptionPeriod
* Removed Enum SubscriptionState
* Removed Enum SurfaceGuiShape
* Removed Enum SystemThemeValue
* Removed Enum TagReplicability
* Removed Enum TeamCreateErrorState
* Removed Enum TelemetryBackend
* Removed Enum TelemetryStandardizedField
* Removed Enum TerrainFace
* Removed Enum TerrainLiquidMergeOperation
* Removed Enum TerrainSolidMergeOperation
* Removed Enum TextChatMessageStatus
* Removed Enum TextDirection
* Removed Enum TitleBarControlsPosition
* Removed Enum TitleBarMode
* Removed Enum TonemapperPreset
* Removed Enum TrackerError
* Removed Enum TrackerExtrapolationFlagMode
* Removed Enum TrackerFaceTrackingStatus
* Removed Enum TrackerLodFlagMode
* Removed Enum TrackerLodValueMode
* Removed Enum TrackerMode
* Removed Enum TrackerPromptEvent
* Removed Enum TrackerType
* Removed Enum UICaptureMode
* Removed Enum UIDragDetectorBoundingBehavior
* Removed Enum UIDragDetectorDragRelativity
* Removed Enum UIDragDetectorDragSpace
* Removed Enum UIDragDetectorDragStyle
* Removed Enum UIDragDetectorResponseStyle
* Removed Enum UIDragSpeedAxisMapping
* Removed Enum UIFlexAlignment
* Removed Enum UIFlexMode
* Removed Enum UpdateState
* Removed Enum UploadCaptureResult
* Removed Enum UsageContext
* Removed Enum UserAcquisitionSource
* Removed Enum UserIdMode
* Removed Enum UserNewReturningStatus
* Removed Enum UserReturnStatus
* Removed Enum VRComfortSetting
* Removed Enum VRControllerModelMode
* Removed Enum VRDeviceType
* Removed Enum VRLaserPointerMode
* Removed Enum VRSafetyBubbleMode
* Removed Enum VRScaling
* Removed Enum VRSessionState
* Removed Enum VideoCaptureResult
* Removed Enum VideoCaptureStartedResult
* Removed Enum VideoDeviceCaptureQuality
* Removed Enum VideoError
* Removed Enum VideoSampleSize
* Removed Enum ViewMode
* Removed Enum VoiceChatDistanceAttenuationType
* Removed Enum VoiceClientLeaveReasons
* Removed Enum VoiceControlPath
* Removed Enum VoiceRccReconnectReason
* Removed Enum VolumetricAudio
* Removed Enum WebSocketState
* Removed Enum WebStreamClientState
* Removed Enum WebStreamClientType
* Removed Enum WeldConstraintPreserve
* Removed Enum WhenUserFirstPlayed
* Removed Enum WhisperChatPrivacyMode
* Removed Enum WindowState
* Removed Enum WrapLayerAutoSkin
