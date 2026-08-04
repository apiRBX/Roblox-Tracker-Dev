# Roblox API Tracker (Development)

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.493.0.4930373` |
| **Version Hash** | `version-04c0166b90104f00` |
| **Official Release Notes** | [Release Notes 493](https://create.roblox.com/docs/release-notes/release-notes-493) |

---

## API Changelog

* Update Class [Instance](https://create.roblox.com/docs/reference/engine/classes/Instance) [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed Superclass of Class [Instance](https://create.roblox.com/docs/reference/engine/classes/Instance) from `Object` to `<<<ROOT>>>`
  * Added Property [Instance.ClassName](https://create.roblox.com/docs/reference/engine/classes/Instance#ClassName): string [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [Instance.className](https://create.roblox.com/docs/reference/engine/classes/Instance#className): string [🏷️ ReadOnly] [🏷️ NotReplicated] [🏷️ Deprecated] [⚡ThreadSafety: ReadSafe]
  * Changed the return-type of Function [Instance.ClearAllChildren](https://create.roblox.com/docs/reference/engine/classes/Instance#ClearAllChildren) from null to void
  * Changed the capabilities of Function [Instance.Clone](https://create.roblox.com/docs/reference/engine/classes/Instance#Clone)
    from: {🚧CreateInstances}
    to: {🚧None}
  * Changed the return-type of Function [Instance.Destroy](https://create.roblox.com/docs/reference/engine/classes/Instance#Destroy) from null to void
  * Changed ThreadSafety of Function [Instance.GetActor](https://create.roblox.com/docs/reference/engine/classes/Instance#GetActor) from `Safe` to `Unsafe`
  * Changed the return-type of Function [Instance.GetChildren](https://create.roblox.com/docs/reference/engine/classes/Instance#GetChildren) from Instances to Objects [⚡ThreadSafety: Safe]
  * Changed the return-type of Function [Instance.GetDescendants](https://create.roblox.com/docs/reference/engine/classes/Instance#GetDescendants) from Instances to Array [🏷️ CustomLuaState] [⚡ThreadSafety: Safe]
  * Added Function [Instance.GetPropertyChangedSignal](https://create.roblox.com/docs/reference/engine/classes/Instance#GetPropertyChangedSignal) (property: string) -> RBXScriptSignal
  * Added Function [Instance.IsA](https://create.roblox.com/docs/reference/engine/classes/Instance#IsA) (className: string) -> bool [🏷️ CustomLuaState] [⚡ThreadSafety: Safe]
  * Changed the return-type of Function [Instance.Remove](https://create.roblox.com/docs/reference/engine/classes/Instance#Remove) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Instance.SetAttribute](https://create.roblox.com/docs/reference/engine/classes/Instance#SetAttribute) from null to void
  * Changed the return-type of Function [Instance.children](https://create.roblox.com/docs/reference/engine/classes/Instance#children) from Instances to Objects [🏷️ Deprecated]
  * Changed the capabilities of Function [Instance.clone](https://create.roblox.com/docs/reference/engine/classes/Instance#clone)
    from: {🚧CreateInstances}
    to: {🚧None}
  * Changed the return-type of Function [Instance.destroy](https://create.roblox.com/docs/reference/engine/classes/Instance#destroy) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Instance.getChildren](https://create.roblox.com/docs/reference/engine/classes/Instance#getChildren) from Instances to Objects [🏷️ Deprecated]
  * Added Function [Instance.isA](https://create.roblox.com/docs/reference/engine/classes/Instance#isA) (className: string) -> bool [🏷️ Deprecated] [🏷️ CustomLuaState]
  * Changed the return-type of Function [Instance.remove](https://create.roblox.com/docs/reference/engine/classes/Instance#remove) from null to void [🏷️ Deprecated]
  * Added Event [Instance.Changed](https://create.roblox.com/docs/reference/engine/classes/Instance#Changed)
  * Removed Property Instance.Capabilities
  * Removed Property Instance.IsInSandbox
  * Removed Property Instance.PredictionMode
  * Removed Property Instance.Sandboxed
  * Removed Property Instance.UniqueId
  * Removed Function Instance.AddTag
  * Removed Function Instance.GetStyled
  * Removed Function Instance.GetStyledPropertyChangedSignal
  * Removed Function Instance.GetTags
  * Removed Function Instance.HasTag
  * Removed Function Instance.IsPropertyModified
  * Removed Function Instance.QueryDescendants
  * Removed Function Instance.RemoveTag
  * Removed Function Instance.ResetPropertyToDefault
  * Removed Event Instance.Destroying
  * Removed Event Instance.StyledPropertiesChanged
* Added Class [ABTestService](https://create.roblox.com/docs/reference/engine/classes/ABTestService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ABTestService.ClearUserVariations](https://create.roblox.com/docs/reference/engine/classes/ABTestService#ClearUserVariations)
  * Added Function [ABTestService.GetBrowserTrackerABTestLoadingStatus](https://create.roblox.com/docs/reference/engine/classes/ABTestService#GetBrowserTrackerABTestLoadingStatus)
  * Added Function [ABTestService.GetPendingOrInitializedUserId](https://create.roblox.com/docs/reference/engine/classes/ABTestService#GetPendingOrInitializedUserId)
  * Added Function [ABTestService.GetUserABTestLoadingStatus](https://create.roblox.com/docs/reference/engine/classes/ABTestService#GetUserABTestLoadingStatus)
  * Added Function [ABTestService.GetVariant](https://create.roblox.com/docs/reference/engine/classes/ABTestService#GetVariant)
  * Added Function [ABTestService.InitializeForUserId](https://create.roblox.com/docs/reference/engine/classes/ABTestService#InitializeForUserId)
  * Added Function [ABTestService.WaitUntilBrowserTrackerABTestsInitialized](https://create.roblox.com/docs/reference/engine/classes/ABTestService#WaitUntilBrowserTrackerABTestsInitialized) [🏷️ Yields]
  * Added Function [ABTestService.WaitUntilUserABTestsInitialized](https://create.roblox.com/docs/reference/engine/classes/ABTestService#WaitUntilUserABTestsInitialized) [🏷️ Yields]
  * Added Event [ABTestService.OnBrowserTrackerABTestLoadingStatusChanged](https://create.roblox.com/docs/reference/engine/classes/ABTestService#OnBrowserTrackerABTestLoadingStatusChanged)
  * Added Event [ABTestService.OnUserABTestLoadingStatusChanged](https://create.roblox.com/docs/reference/engine/classes/ABTestService#OnUserABTestLoadingStatusChanged)
* Update Class [Accoutrement](https://create.roblox.com/docs/reference/engine/classes/Accoutrement) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Accoutrement.AttachmentForward](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentForward)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [Accoutrement.AttachmentForward](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentForward)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Accoutrement.AttachmentPoint](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentPoint)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Accoutrement.AttachmentPos](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentPos)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [Accoutrement.AttachmentPos](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentPos)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Accoutrement.AttachmentRight](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentRight)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [Accoutrement.AttachmentRight](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentRight)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Accoutrement.AttachmentUp](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentUp)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [Accoutrement.AttachmentUp](https://create.roblox.com/docs/reference/engine/classes/Accoutrement#AttachmentUp)
    from: [🚫None]
    to: [📁LoadOnly]
* Update Class [Accessory](https://create.roblox.com/docs/reference/engine/classes/Accessory) [⬆️Extends: Accoutrement] [🧠Memory: Instances]
  * Changed the security of Property [Accessory.AccessoryType](https://create.roblox.com/docs/reference/engine/classes/Accessory#AccessoryType)
    from: {🔒None}
    to: {🔒Read:None, Write:NotAccessibleSecurity}
  * Changed the capabilities of Property [Accessory.AccessoryType](https://create.roblox.com/docs/reference/engine/classes/Accessory#AccessoryType)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
* Update Class [AdService](https://create.roblox.com/docs/reference/engine/classes/AdService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [AdService.ShowVideoAd](https://create.roblox.com/docs/reference/engine/classes/AdService#ShowVideoAd) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [AdService.ShowVideoAd](https://create.roblox.com/docs/reference/engine/classes/AdService#ShowVideoAd)
    from: {🚧Monetization}
    to: {🚧None}
  * Changed the capabilities of Event [AdService.VideoAdClosed](https://create.roblox.com/docs/reference/engine/classes/AdService#VideoAdClosed)
    from: {🚧Monetization}
    to: {🚧None}
  * Removed Function AdService.CreateAdRewardFromDevProductId
  * Removed Function AdService.GetAdTeleportInfo
  * Removed Function AdService.GetReportAdInfo
  * Removed Function AdService.GetUniversalAppAdsEligibility
  * Removed Function AdService.HandleWhyThisAdClicked
  * Removed Function AdService.HideEudsaDisclosure
  * Removed Function AdService.IsAdLoaded
  * Removed Function AdService.OnDemandVideoCompleteFromUI
  * Removed Function AdService.RegisterDisclosureButton
  * Removed Function AdService.ReturnToPublisherExperience
  * Removed Function AdService.SetAdGuiInteractivityHandlerInitialized
  * Removed Function AdService.SubmitAdNotification
  * Removed Function AdService.UnregisterAdOpportunity
  * Removed Function AdService.GetAdAvailabilityNowAsync
  * Removed Function AdService.GetAdAvailabilityNowForUniverseAsync
  * Removed Function AdService.GetCampaignEligibilityAsync
  * Removed Function AdService.RegisterAdOpportunityAsync
  * Removed Function AdService.ShowRewardedVideoAdAsync
  * Removed Function AdService.ShowRewardedVideoAdAtClientAsync
  * Removed Event AdService.AdTeleportEnded
  * Removed Event AdService.AdTeleportInitiated
  * Removed Event AdService.RewardedVideoAdEnded
  * Removed Event AdService.RewardedVideoAdStarted
  * Removed Event AdService.ShowDynamicEudsaDisclosure
  * Removed Event AdService.ShowReportAdPopup
  * Removed Event AdService.adGuiRegisterUI
  * Removed Callback AdService.OnImmersiveBrandedAdDisclosureButtonActivated
  * Removed Callback AdService.onDemandVideoPlayInUI
* Update Class [AnalyticsService](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Changed the capabilities of Property [AnalyticsService.ApiKey](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#ApiKey)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [AnalyticsService.FireCustomEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireCustomEvent) from null to void
  * Changed the capabilities of Function [AnalyticsService.FireCustomEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireCustomEvent)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [AnalyticsService.FireEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireEvent) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [AnalyticsService.FireEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireEvent)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [AnalyticsService.FireInGameEconomyEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireInGameEconomyEvent) from null to void
  * Changed the capabilities of Function [AnalyticsService.FireInGameEconomyEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireInGameEconomyEvent)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [AnalyticsService.FireLogEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireLogEvent) from null to void
  * Changed the capabilities of Function [AnalyticsService.FireLogEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FireLogEvent)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [AnalyticsService.FirePlayerProgressionEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FirePlayerProgressionEvent) from null to void
  * Changed the capabilities of Function [AnalyticsService.FirePlayerProgressionEvent](https://create.roblox.com/docs/reference/engine/classes/AnalyticsService#FirePlayerProgressionEvent)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Function AnalyticsService.GetDurationLoggerTimestamp
  * Removed Function AnalyticsService.LogCustomEvent
  * Removed Function AnalyticsService.LogEconomyEvent
  * Removed Function AnalyticsService.LogFunnelStepEvent
  * Removed Function AnalyticsService.LogJourneyEvent
  * Removed Function AnalyticsService.LogOnboardingFunnelStepEvent
  * Removed Function AnalyticsService.LogProgressionCompleteEvent
  * Removed Function AnalyticsService.LogProgressionEvent
  * Removed Function AnalyticsService.LogProgressionFailEvent
  * Removed Function AnalyticsService.LogProgressionStartEvent
  * Removed Function AnalyticsService.GetPlayerSegmentsAsync
* Update Class [Animation](https://create.roblox.com/docs/reference/engine/classes/Animation) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed the capabilities of Property [Animation.AnimationId](https://create.roblox.com/docs/reference/engine/classes/Animation#AnimationId)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Removed Property Animation.AnimationContent
* Update Class [AnimationController](https://create.roblox.com/docs/reference/engine/classes/AnimationController) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed the capabilities of Function [AnimationController.GetPlayingAnimationTracks](https://create.roblox.com/docs/reference/engine/classes/AnimationController#GetPlayingAnimationTracks)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Function [AnimationController.LoadAnimation](https://create.roblox.com/docs/reference/engine/classes/AnimationController#LoadAnimation)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Event [AnimationController.AnimationPlayed](https://create.roblox.com/docs/reference/engine/classes/AnimationController#AnimationPlayed)
    from: {🚧Animation}
    to: {🚧None}
* Update Class [AnimationTrack](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack) [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotCreatable]
  * Changed the capabilities of Property [AnimationTrack.Animation](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Animation)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [AnimationTrack.IsPlaying](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#IsPlaying)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [AnimationTrack.Length](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Length)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [AnimationTrack.Looped](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Looped)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [AnimationTrack.Priority](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Priority)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [AnimationTrack.Speed](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Speed)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [AnimationTrack.TimePosition](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#TimePosition)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [AnimationTrack.WeightCurrent](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#WeightCurrent)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [AnimationTrack.WeightTarget](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#WeightTarget)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the return-type of Function [AnimationTrack.AdjustSpeed](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#AdjustSpeed) from null to void
  * Changed the capabilities of Function [AnimationTrack.AdjustSpeed](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#AdjustSpeed)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [AnimationTrack.AdjustWeight](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#AdjustWeight) from null to void
  * Changed the capabilities of Function [AnimationTrack.AdjustWeight](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#AdjustWeight)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Function [AnimationTrack.GetMarkerReachedSignal](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#GetMarkerReachedSignal)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Function [AnimationTrack.GetTimeOfKeyframe](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#GetTimeOfKeyframe)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [AnimationTrack.Play](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Play) from null to void
  * Changed the capabilities of Function [AnimationTrack.Play](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Play)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [AnimationTrack.Stop](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Stop) from null to void
  * Changed the capabilities of Function [AnimationTrack.Stop](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Stop)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Event [AnimationTrack.DidLoop](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#DidLoop)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Event [AnimationTrack.KeyframeReached](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#KeyframeReached)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Event [AnimationTrack.Stopped](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#Stopped)
    from: {🚧Animation}
    to: {🚧None}
  * Removed Function AnimationTrack.GetDebugData
  * Removed Function AnimationTrack.GetParameter
  * Removed Function AnimationTrack.GetParameterDefaults
  * Removed Function AnimationTrack.GetTargetInstance
  * Removed Function AnimationTrack.GetTargetNames
  * Removed Function AnimationTrack.ResetGraph
  * Removed Function AnimationTrack.SetParameter
  * Removed Function AnimationTrack.SetTargetInstance
  * Removed Function AnimationTrack.UpdateGraphNodeProperty
  * Removed Event AnimationTrack.Ended
  * Removed Event AnimationTrack.ParameterChanged
* Update Class [Animator](https://create.roblox.com/docs/reference/engine/classes/Animator) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the return-type of Function [Animator.ApplyJointVelocities](https://create.roblox.com/docs/reference/engine/classes/Animator#ApplyJointVelocities) from null to void
  * Changed the capabilities of Function [Animator.ApplyJointVelocities](https://create.roblox.com/docs/reference/engine/classes/Animator#ApplyJointVelocities)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Function [Animator.GetPlayingAnimationTracks](https://create.roblox.com/docs/reference/engine/classes/Animator#GetPlayingAnimationTracks)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Function [Animator.LoadAnimation](https://create.roblox.com/docs/reference/engine/classes/Animator#LoadAnimation)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Animator.StepAnimations](https://create.roblox.com/docs/reference/engine/classes/Animator#StepAnimations) from null to void
  * Changed the capabilities of Function [Animator.StepAnimations](https://create.roblox.com/docs/reference/engine/classes/Animator#StepAnimations)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Event [Animator.AnimationPlayed](https://create.roblox.com/docs/reference/engine/classes/Animator#AnimationPlayed)
    from: {🚧Animation}
    to: {🚧None}
  * Removed Property Animator.EvaluationThrottled
  * Removed Property Animator.PreferLodEnabled
  * Removed Property Animator.RootMotion
  * Removed Property Animator.RootMotionWeight
  * Removed Function Animator.GetPlayingAnimationTracksCoreScript
  * Removed Function Animator.GetTrackByAnimationId
  * Removed Function Animator.LoadAnimationCoreScript
  * Removed Function Animator.LoadStreamAnimation
  * Removed Function Animator.LoadStreamAnimationForSelfieView_deprecated
  * Removed Function Animator.LoadStreamAnimationV2
  * Removed Function Animator.RegisterEvaluationParallelCallback
  * Removed Function Animator.StepAnimationsInternal
  * Removed Function Animator.SynchronizeWith
  * Removed Event Animator.AnimationPlayedCoreScript
  * Removed Event Animator.AnimationStreamTrackPlayed
* Update Class [AppUpdateService](https://create.roblox.com/docs/reference/engine/classes/AppUpdateService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [AppUpdateService.CheckForUpdate](https://create.roblox.com/docs/reference/engine/classes/AppUpdateService#CheckForUpdate) from null to void
  * Added Function [AppUpdateService.DisableDUAR](https://create.roblox.com/docs/reference/engine/classes/AppUpdateService#DisableDUAR) () -> void
  * Added Function [AppUpdateService.DisableDUARAndOpenSurvey](https://create.roblox.com/docs/reference/engine/classes/AppUpdateService#DisableDUARAndOpenSurvey) (surveyUrl: string) -> void
  * Removed Function AppUpdateService.CanPerformBinaryUpdate
  * Removed Function AppUpdateService.GetProtocolLaunchUpdateName
  * Removed Function AppUpdateService.GetProtocolLaunchUpdateType
* Update Class [AssetDeliveryProxy](https://create.roblox.com/docs/reference/engine/classes/AssetDeliveryProxy) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property AssetDeliveryProxy.Interface
  * Removed Property AssetDeliveryProxy.Port
  * Removed Property AssetDeliveryProxy.StartServer
* Update Class [AssetImportService](https://create.roblox.com/docs/reference/engine/classes/AssetImportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AssetImportService.GetCurrentImportMap](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#GetCurrentImportMap) () -> Dictionary
  * Added Function [AssetImportService.ImportMesh](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#ImportMesh) (fileName: string) -> Tuple
  * Added Function [AssetImportService.UploadCurrentMesh](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#UploadCurrentMesh) () -> void
  * Added Function [AssetImportService.ImportMeshWithPrompt](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#ImportMeshWithPrompt) () -> Tuple [🏷️ Yields]
  * Removed Function AssetImportService.GetAllPresets
  * Removed Function AssetImportService.GetPreset
  * Removed Function AssetImportService.RemovePreset
  * Removed Function AssetImportService.SavePreset
  * Removed Function AssetImportService.StartSessionWithPath
  * Removed Function AssetImportService.StartSingleFileWatch
  * Removed Function AssetImportService.StopSingleFileWatch
  * Removed Function AssetImportService.GetFilesInDirAsync
  * Removed Function AssetImportService.PickFileWithPromptAsync
  * Removed Function AssetImportService.PickImageFileWithPrompt
  * Removed Function AssetImportService.PickMeshFileWithPrompt
  * Removed Function AssetImportService.PickMultipleFilesWithPrompt
  * Removed Function AssetImportService.StartSessionWithPathAsync
  * Removed Function AssetImportService.UploadAssetFromContentAsync
  * Removed Function AssetImportService.UploadAssetFromPathAsync
  * Removed Function AssetImportService.UploadVersionedAssetFromContentAsync
  * Removed Function AssetImportService.UploadVersionedAssetFromPathAsync
  * Removed Event AssetImportService.SingleFileChanged
  * Removed Event AssetImportService.StartSingleMeshImport
* Update Class [AssetManagerService](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AssetManagerService.GetMeshId](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#GetMeshId) (aliasName: string) -> int64
  * Added Function [AssetManagerService.GetTextureId](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#GetTextureId) (aliasName: string) -> int64
  * Added Function [AssetManagerService.HasUnpublishedChangesForLinkedSource](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#HasUnpublishedChangesForLinkedSource) (aliasName: string) -> bool
  * Changed the return-type of Function [AssetManagerService.InsertAudio](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertAudio) from null to void
  * Changed the return-type of Function [AssetManagerService.InsertImage](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertImage) from null to void
  * Added Function [AssetManagerService.InsertLinkedSourceAsLocalScript](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertLinkedSourceAsLocalScript) (aliasName: string) -> void
  * Added Function [AssetManagerService.InsertLinkedSourceAsModuleScript](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertLinkedSourceAsModuleScript) (aliasName: string) -> void
  * Added Function [AssetManagerService.InsertLinkedSourceAsScript](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertLinkedSourceAsScript) (aliasName: string) -> void
  * Changed the return-type of Function [AssetManagerService.InsertMesh](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertMesh) from null to void
  * Changed the parameters of Function [AssetManagerService.InsertMesh](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertMesh)
    from: (aliasName: string, insertWithLocation: bool, sourceAssetId: int64)
    to: (aliasName: string, insertWithLocation: bool)
  * Changed the return-type of Function [AssetManagerService.InsertMeshesWithLocation](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertMeshesWithLocation) from null to void
  * Changed the parameters of Function [AssetManagerService.InsertMeshesWithLocation](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertMeshesWithLocation)
    from: (aliasNames: Array, meshIds: Array)
    to: (aliasNames: Array)
  * Changed the return-type of Function [AssetManagerService.InsertModel](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertModel) from null to void
  * Changed the return-type of Function [AssetManagerService.InsertPackage](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#InsertPackage) from null to void
  * Added Function [AssetManagerService.OpenLinkedSource](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#OpenLinkedSource) (aliasName: string) -> void
  * Changed the return-type of Function [AssetManagerService.OpenPlace](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#OpenPlace) from null to void
  * Added Function [AssetManagerService.RefreshLinkedSource](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RefreshLinkedSource) (aliasName: string) -> void
  * Added Function [AssetManagerService.RevertLinkedSourceToLastPublishedVersion](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RevertLinkedSourceToLastPublishedVersion) (aliasName: string) -> void
  * Changed the return-type of Function [AssetManagerService.ShowPackageDetails](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#ShowPackageDetails) from null to void
  * Changed the return-type of Function [AssetManagerService.UpdateAllPackages](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#UpdateAllPackages) from null to void
  * Changed the return-type of Function [AssetManagerService.ViewPackageOnWebsite](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#ViewPackageOnWebsite) from null to void
  * Changed the return-type of Function [AssetManagerService.DeleteAlias](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#DeleteAlias) from null to void [🏷️ Yields]
  * Added Function [AssetManagerService.PublishLinkedSource](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#PublishLinkedSource) (assetId: int64, aliasName: string) -> void [🏷️ Yields]
  * Changed the return-type of Function [AssetManagerService.RemovePlace](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RemovePlace) from null to void [🏷️ Yields]
  * Changed the return-type of Function [AssetManagerService.RenameAlias](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RenameAlias) from null to void [🏷️ Yields]
  * Changed the return-type of Function [AssetManagerService.RenameModel](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RenameModel) from null to void [🏷️ Yields]
  * Changed the return-type of Function [AssetManagerService.RenamePlace](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#RenamePlace) from null to void [🏷️ Yields]
  * Added Event [AssetManagerService.MayBeLinkedSourceModified](https://create.roblox.com/docs/reference/engine/classes/AssetManagerService#MayBeLinkedSourceModified)
  * Removed Function AssetManagerService.GetMeshIdFromAliasName
  * Removed Function AssetManagerService.GetMeshIdFromAssetId
  * Removed Function AssetManagerService.GetTextureIdFromAliasName
  * Removed Function AssetManagerService.GetTextureIdFromAssetId
  * Removed Function AssetManagerService.InsertImages
  * Removed Function AssetManagerService.InsertVideo
  * Removed Function AssetManagerService.CreateAlias
  * Removed Event AssetManagerService.AssetImportedSignal
  * Removed Event AssetManagerService.ImportSessionFinished
  * Removed Event AssetManagerService.ImportSessionStarted
* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AssetService.GetBundleDetailsSync](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetBundleDetailsSync) (bundleId: int64) -> Dictionary
  * Changed the capabilities of Function [AssetService.CreatePlaceAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#CreatePlaceAsync)
    from: {🚧AssetCreateUpdate}
    to: {🚧None}
  * Changed the capabilities of Function [AssetService.CreatePlaceInPlayerInventoryAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#CreatePlaceInPlayerInventoryAsync)
    from: {🚧AssetCreateUpdate}
    to: {🚧None}
  * Changed the capabilities of Function [AssetService.GetAssetIdsForPackage](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetAssetIdsForPackage)
    from: {🚧AssetRead}
    to: {🚧None}
  * Added Function [AssetService.GetAssetThumbnailAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetAssetThumbnailAsync) (assetId: int64, thumbnailSize: Vector2, assetType: int = 0) -> Tuple [🏷️ Yields]
  * Changed the capabilities of Function [AssetService.GetBundleDetailsAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetBundleDetailsAsync)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [AssetService.GetCreatorAssetID](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetCreatorAssetID)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [AssetService.GetGamePlacesAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetGamePlacesAsync)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the return-type of Function [AssetService.SavePlaceAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#SavePlaceAsync) from null to void [🏷️ Yields]
  * Changed the parameters of Function [AssetService.SavePlaceAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#SavePlaceAsync)
    from: (requestParameters: Dictionary?)
    to: ()
  * Changed the capabilities of Function [AssetService.SavePlaceAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#SavePlaceAsync)
    from: {🚧AssetCreateUpdate}
    to: {🚧None}
  * Removed Property AssetService.AllowInsertFreeAssets
  * Removed Function AssetService.CreateEditableImage
  * Removed Function AssetService.CreateEditableMesh
  * Removed Function AssetService.DeserializeInstance
  * Removed Function AssetService.GetOpaqueContentMetadataMap
  * Removed Function AssetService.CachePartOperationsAsync
  * Removed Function AssetService.CanEditAssetAsync
  * Removed Function AssetService.ComposeDecalAsync
  * Removed Function AssetService.CreateAssetAsync
  * Removed Function AssetService.CreateAssetVersionAsync
  * Removed Function AssetService.CreateDataModelContentAsync
  * Removed Function AssetService.CreateEditableImageAsync
  * Removed Function AssetService.CreateEditableImageFromDownloadAsync
  * Removed Function AssetService.CreateEditableMeshAsync
  * Removed Function AssetService.CreateMeshPartAsync
  * Removed Function AssetService.CreateSurfaceAppearanceAsync
  * Removed Function AssetService.GetAssetIdsForPackageAsync
  * Removed Function AssetService.GetAudioMetadataAsync
  * Removed Function AssetService.LoadAssetAsync
  * Removed Function AssetService.PromptCreateAssetAsync
  * Removed Function AssetService.PromptImportAnimationClipFromVideoAsync
  * Removed Function AssetService.SearchAudio
  * Removed Function AssetService.SearchAudioAsync
  * Removed Event AssetService.AudioMetadataFailedResponse
  * Removed Event AssetService.AudioMetadataRequest
  * Removed Event AssetService.AudioMetadataResponse
  * Removed Event AssetService.OpenCreateResultModal
  * Removed Event AssetService.OpenPublishResultModal
* Update Class [Atmosphere](https://create.roblox.com/docs/reference/engine/classes/Atmosphere) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Atmosphere.Color](https://create.roblox.com/docs/reference/engine/classes/Atmosphere#Color)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Atmosphere.Decay](https://create.roblox.com/docs/reference/engine/classes/Atmosphere#Decay)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Atmosphere.Density](https://create.roblox.com/docs/reference/engine/classes/Atmosphere#Density)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Atmosphere.Glare](https://create.roblox.com/docs/reference/engine/classes/Atmosphere#Glare)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Atmosphere.Haze](https://create.roblox.com/docs/reference/engine/classes/Atmosphere#Haze)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Atmosphere.Offset](https://create.roblox.com/docs/reference/engine/classes/Atmosphere#Offset)
    from: {🚧Read: Environment}
    to: {🚧None}
* Update Class [Attachment](https://create.roblox.com/docs/reference/engine/classes/Attachment) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Attachment.Axis](https://create.roblox.com/docs/reference/engine/classes/Attachment#Axis)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Attachment.CFrame](https://create.roblox.com/docs/reference/engine/classes/Attachment#CFrame)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Attachment.Orientation](https://create.roblox.com/docs/reference/engine/classes/Attachment#Orientation)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the serialization of Property [Attachment.Orientation](https://create.roblox.com/docs/reference/engine/classes/Attachment#Orientation)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Attachment.Position](https://create.roblox.com/docs/reference/engine/classes/Attachment#Position)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the serialization of Property [Attachment.Position](https://create.roblox.com/docs/reference/engine/classes/Attachment#Position)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Attachment.Rotation](https://create.roblox.com/docs/reference/engine/classes/Attachment#Rotation)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Attachment.SecondaryAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SecondaryAxis)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Attachment.Visible](https://create.roblox.com/docs/reference/engine/classes/Attachment#Visible)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Attachment.WorldAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#WorldAxis)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Attachment.WorldCFrame](https://create.roblox.com/docs/reference/engine/classes/Attachment#WorldCFrame)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Attachment.WorldOrientation](https://create.roblox.com/docs/reference/engine/classes/Attachment#WorldOrientation)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the serialization of Property [Attachment.WorldOrientation](https://create.roblox.com/docs/reference/engine/classes/Attachment#WorldOrientation)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Attachment.WorldPosition](https://create.roblox.com/docs/reference/engine/classes/Attachment#WorldPosition)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the serialization of Property [Attachment.WorldPosition](https://create.roblox.com/docs/reference/engine/classes/Attachment#WorldPosition)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Attachment.WorldRotation](https://create.roblox.com/docs/reference/engine/classes/Attachment#WorldRotation)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Attachment.WorldSecondaryAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#WorldSecondaryAxis)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Attachment.GetAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#GetAxis)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Attachment.GetSecondaryAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#GetSecondaryAxis)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Attachment.SetAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SetAxis) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Attachment.SetAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SetAxis)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Attachment.SetSecondaryAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SetSecondaryAxis) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Attachment.SetSecondaryAxis](https://create.roblox.com/docs/reference/engine/classes/Attachment#SetSecondaryAxis)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Function Attachment.GetConstraints
* Update Class [Bone](https://create.roblox.com/docs/reference/engine/classes/Bone) [⬆️Extends: Attachment] [🧠Memory: Instances]
  * Added Property [Bone.IsCFrameDriven](https://create.roblox.com/docs/reference/engine/classes/Bone#IsCFrameDriven): bool [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [Bone.Transform](https://create.roblox.com/docs/reference/engine/classes/Bone#Transform)
    from: {🚧Read: Basic, Animation}
    to: {🚧None}
  * Changed the capabilities of Property [Bone.TransformedCFrame](https://create.roblox.com/docs/reference/engine/classes/Bone#TransformedCFrame)
    from: {🚧Read: Basic, Animation}
    to: {🚧None}
  * Changed ThreadSafety of Property [Bone.TransformedWorldCFrame](https://create.roblox.com/docs/reference/engine/classes/Bone#TransformedWorldCFrame) from `Unsafe` to `ReadSafe`
  * Changed the capabilities of Property [Bone.TransformedWorldCFrame](https://create.roblox.com/docs/reference/engine/classes/Bone#TransformedWorldCFrame)
    from: {🚧Read: Basic, Animation}
    to: {🚧None}
* Update Class [AvatarEditorService](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [AvatarEditorService.NoPromptCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#NoPromptCreateOutfit)
    from: (humanoidDescription: HumanoidDescription, rigType: HumanoidRigType, name: string, gearAssetId: int64 = 0, outfitOptions: Dictionary = nil, outfitType: Variant)
    to: (humanoidDescription: HumanoidDescription, rigType: HumanoidRigType, name: string)
  * Changed the parameters of Function [AvatarEditorService.NoPromptSaveAvatar](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#NoPromptSaveAvatar)
    from: (humanoidDescription: HumanoidDescription, rigType: HumanoidRigType, saveDict: Dictionary, gearAssetId: int64 = 0, profileConfiguration: Dictionary = nil)
    to: (humanoidDescription: HumanoidDescription, rigType: HumanoidRigType, saveDict: Dictionary, gearAssetId: int64 = 0)
  * Added Function [AvatarEditorService.PerformCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformCreateOutfit) (name: string) -> void
  * Changed the return-type of Function [AvatarEditorService.PerformCreateOutfitWithDescription](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformCreateOutfitWithDescription) from null to void
  * Changed the parameters of Function [AvatarEditorService.PerformCreateOutfitWithDescription](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformCreateOutfitWithDescription)
    from: (humanoidDescription: HumanoidDescription, name: string, profileConfiguration: Dictionary = nil)
    to: (humanoidDescription: HumanoidDescription, name: string)
  * Changed the return-type of Function [AvatarEditorService.PerformDeleteOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformDeleteOutfit) from null to void
  * Added Function [AvatarEditorService.PerformSaveAvatar](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformSaveAvatar) () -> void
  * Added Function [AvatarEditorService.PerformSaveAvatarNew](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformSaveAvatarNew) (addedAssets: Array, removedAssets: Array) -> void
  * Changed the return-type of Function [AvatarEditorService.PerformSaveAvatarWithDescription](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformSaveAvatarWithDescription) from null to void
  * Changed the return-type of Function [AvatarEditorService.PerformSetFavorite](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PerformSetFavorite) from null to void
  * Changed the return-type of Function [AvatarEditorService.PromptAllowInventoryReadAccess](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptAllowInventoryReadAccess) from null to void
  * Changed the capabilities of Function [AvatarEditorService.PromptAllowInventoryReadAccess](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptAllowInventoryReadAccess)
    from: {🚧Players, AssetRead}
    to: {🚧None}
  * Changed the return-type of Function [AvatarEditorService.PromptCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptCreateOutfit) from null to void
  * Changed the parameters of Function [AvatarEditorService.PromptCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptCreateOutfit)
    from: (outfit: HumanoidDescription, rigType: HumanoidRigType, outfitOptions: Dictionary = nil, outfitType: Variant)
    to: (outfit: HumanoidDescription, rigType: HumanoidRigType)
  * Changed the capabilities of Function [AvatarEditorService.PromptCreateOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptCreateOutfit)
    from: {🚧Players, PlatformAvatarEditing}
    to: {🚧None}
  * Changed the return-type of Function [AvatarEditorService.PromptDeleteOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptDeleteOutfit) from null to void
  * Changed the capabilities of Function [AvatarEditorService.PromptDeleteOutfit](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptDeleteOutfit)
    from: {🚧Players, PlatformAvatarEditing}
    to: {🚧None}
  * Changed the return-type of Function [AvatarEditorService.PromptSaveAvatar](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptSaveAvatar) from null to void
  * Changed the capabilities of Function [AvatarEditorService.PromptSaveAvatar](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptSaveAvatar)
    from: {🚧Players, PlatformAvatarEditing}
    to: {🚧None}
  * Changed the return-type of Function [AvatarEditorService.PromptSetFavorite](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptSetFavorite) from null to void
  * Changed the capabilities of Function [AvatarEditorService.PromptSetFavorite](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptSetFavorite)
    from: {🚧Players, PlatformAvatarEditing}
    to: {🚧None}
  * Changed the return-type of Function [AvatarEditorService.SetAllowInventoryReadAccess](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SetAllowInventoryReadAccess) from null to void
  * Changed the return-type of Function [AvatarEditorService.SignalCreateOutfitFailed](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalCreateOutfitFailed) from null to void
  * Changed the return-type of Function [AvatarEditorService.SignalCreateOutfitPermissionDenied](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalCreateOutfitPermissionDenied) from null to void
  * Changed the return-type of Function [AvatarEditorService.SignalDeleteOutfitFailed](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalDeleteOutfitFailed) from null to void
  * Changed the return-type of Function [AvatarEditorService.SignalDeleteOutfitPermissionDenied](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalDeleteOutfitPermissionDenied) from null to void
  * Changed the return-type of Function [AvatarEditorService.SignalSaveAvatarFailed](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalSaveAvatarFailed) from null to void
  * Changed the return-type of Function [AvatarEditorService.SignalSaveAvatarPermissionDenied](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalSaveAvatarPermissionDenied) from null to void
  * Changed the return-type of Function [AvatarEditorService.SignalSetFavoriteFailed](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalSetFavoriteFailed) from null to void
  * Changed the return-type of Function [AvatarEditorService.SignalSetFavoritePermissionDenied](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SignalSetFavoritePermissionDenied) from null to void
  * Changed the capabilities of Function [AvatarEditorService.CheckApplyDefaultClothing](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#CheckApplyDefaultClothing)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the security of Function [AvatarEditorService.ConformToAvatarRules](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#ConformToAvatarRules)
    from: {🔒None}
    to: {🔒RobloxScriptSecurity}
  * Changed the capabilities of Function [AvatarEditorService.ConformToAvatarRules](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#ConformToAvatarRules)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [AvatarEditorService.GetBatchItemDetails](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetBatchItemDetails)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [AvatarEditorService.GetFavorite](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetFavorite)
    from: {🚧Players, AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [AvatarEditorService.GetInventory](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetInventory)
    from: {🚧Players, AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [AvatarEditorService.GetItemDetails](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetItemDetails)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the parameters of Function [AvatarEditorService.GetOutfits](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetOutfits)
    from: (outfitSource: OutfitSource = All, outfitType: OutfitType = All)
    to: (outfitSource: OutfitSource = All)
  * Changed the capabilities of Function [AvatarEditorService.GetOutfits](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetOutfits)
    from: {🚧Players, AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [AvatarEditorService.GetRecommendedAssets](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetRecommendedAssets)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [AvatarEditorService.GetRecommendedBundles](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#GetRecommendedBundles)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [AvatarEditorService.SearchCatalog](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#SearchCatalog)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Event [AvatarEditorService.PromptAllowInventoryReadAccessCompleted](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptAllowInventoryReadAccessCompleted)
    from: {🚧Players, AssetRead}
    to: {🚧None}
  * Changed the capabilities of Event [AvatarEditorService.PromptCreateOutfitCompleted](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptCreateOutfitCompleted)
    from: {🚧Players, PlatformAvatarEditing}
    to: {🚧None}
  * Changed the capabilities of Event [AvatarEditorService.PromptDeleteOutfitCompleted](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptDeleteOutfitCompleted)
    from: {🚧Players, PlatformAvatarEditing}
    to: {🚧None}
  * Changed the capabilities of Event [AvatarEditorService.PromptSaveAvatarCompleted](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptSaveAvatarCompleted)
    from: {🚧Players, PlatformAvatarEditing}
    to: {🚧None}
  * Changed the capabilities of Event [AvatarEditorService.PromptSetFavoriteCompleted](https://create.roblox.com/docs/reference/engine/classes/AvatarEditorService#PromptSetFavoriteCompleted)
    from: {🚧Players, PlatformAvatarEditing}
    to: {🚧None}
  * Removed Function AvatarEditorService.BustAvatarFetchCache
  * Removed Function AvatarEditorService.GetAccessoryType
  * Removed Function AvatarEditorService.NoPromptApplyProfileConfiguration
  * Removed Function AvatarEditorService.NoPromptRenameOutfit
  * Removed Function AvatarEditorService.NoPromptSaveAvatarThumbnailCustomization
  * Removed Function AvatarEditorService.NoPromptUpdateOutfit
  * Removed Function AvatarEditorService.PerformRenameOutfit
  * Removed Function AvatarEditorService.PerformUpdateOutfit
  * Removed Function AvatarEditorService.PromptRenameOutfit
  * Removed Function AvatarEditorService.PromptUpdateOutfit
  * Removed Function AvatarEditorService.SignalRenameOutfitFailed
  * Removed Function AvatarEditorService.SignalRenameOutfitPermissionDenied
  * Removed Function AvatarEditorService.SignalUpdateOutfitFailed
  * Removed Function AvatarEditorService.SignalUpdateOutfitPermissionDenied
  * Removed Function AvatarEditorService.refreshAvatarThumbnails
  * Removed Function AvatarEditorService.CheckApplyDefaultClothingAsync
  * Removed Function AvatarEditorService.ConformToAvatarRulesAsync
  * Removed Function AvatarEditorService.GetAvatarRulesAsync
  * Removed Function AvatarEditorService.GetBatchItemDetailsAsync
  * Removed Function AvatarEditorService.GetBundlesByAssetIdAsync
  * Removed Function AvatarEditorService.GetFavoriteAsync
  * Removed Function AvatarEditorService.GetHeadShapesAsync
  * Removed Function AvatarEditorService.GetInventoryAsync
  * Removed Function AvatarEditorService.GetItemDetailsAsync
  * Removed Function AvatarEditorService.GetOutfitDetails
  * Removed Function AvatarEditorService.GetOutfitDetailsAsync
  * Removed Function AvatarEditorService.GetOutfitsAsync
  * Removed Function AvatarEditorService.GetRecommendedAssetsAsync
  * Removed Function AvatarEditorService.GetRecommendedBundlesAsync
  * Removed Function AvatarEditorService.SearchCatalogAsync
  * Removed Event AvatarEditorService.OpenPromptRenameOutfit
  * Removed Event AvatarEditorService.OpenPromptUpdateOutfit
  * Removed Event AvatarEditorService.PromptApplyProfileConfigurationCompleted
  * Removed Event AvatarEditorService.PromptRenameOutfitCompleted
  * Removed Event AvatarEditorService.PromptSaveAvatarThumbnailCustomizationCompleted
  * Removed Event AvatarEditorService.PromptUpdateOutfitCompleted
* Update Class [AvatarImportService](https://create.roblox.com/docs/reference/engine/classes/AvatarImportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function AvatarImportService.ImportFBXAnimationFromFilePathUserMayChooseModel
* Update Class [BackpackItem](https://create.roblox.com/docs/reference/engine/classes/BackpackItem) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed Superclass of Class [BackpackItem](https://create.roblox.com/docs/reference/engine/classes/BackpackItem) from `Model` to `Instance`
  * Changed MemoryCategory of Class [BackpackItem](https://create.roblox.com/docs/reference/engine/classes/BackpackItem) from `BaseParts` to `Instances`
  * Removed Property BackpackItem.TextureContent
* Update Class [HopperBin](https://create.roblox.com/docs/reference/engine/classes/HopperBin) [⬆️Extends: BackpackItem] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed MemoryCategory of Class [HopperBin](https://create.roblox.com/docs/reference/engine/classes/HopperBin) from `BaseParts` to `Instances`
  * Changed the capabilities of Property [HopperBin.Active](https://create.roblox.com/docs/reference/engine/classes/HopperBin#Active)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [HopperBin.BinType](https://create.roblox.com/docs/reference/engine/classes/HopperBin#BinType)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the return-type of Function [HopperBin.Disable](https://create.roblox.com/docs/reference/engine/classes/HopperBin#Disable) from null to void
  * Changed the capabilities of Function [HopperBin.Disable](https://create.roblox.com/docs/reference/engine/classes/HopperBin#Disable)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [HopperBin.ToggleSelect](https://create.roblox.com/docs/reference/engine/classes/HopperBin#ToggleSelect) from null to void
  * Changed the capabilities of Function [HopperBin.ToggleSelect](https://create.roblox.com/docs/reference/engine/classes/HopperBin#ToggleSelect)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [HopperBin.Deselected](https://create.roblox.com/docs/reference/engine/classes/HopperBin#Deselected)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [HopperBin.Selected](https://create.roblox.com/docs/reference/engine/classes/HopperBin#Selected)
    from: {🚧Input}
    to: {🚧None}
* Update Class [Tool](https://create.roblox.com/docs/reference/engine/classes/Tool) [⬆️Extends: BackpackItem] [🧠Memory: Instances]
  * Changed MemoryCategory of Class [Tool](https://create.roblox.com/docs/reference/engine/classes/Tool) from `BaseParts` to `Instances`
  * Changed the capabilities of Property [Tool.CanBeDropped](https://create.roblox.com/docs/reference/engine/classes/Tool#CanBeDropped)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Tool.Enabled](https://create.roblox.com/docs/reference/engine/classes/Tool#Enabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Tool.Grip](https://create.roblox.com/docs/reference/engine/classes/Tool#Grip)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Tool.GripForward](https://create.roblox.com/docs/reference/engine/classes/Tool#GripForward)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the serialization of Property [Tool.GripForward](https://create.roblox.com/docs/reference/engine/classes/Tool#GripForward)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Tool.GripPos](https://create.roblox.com/docs/reference/engine/classes/Tool#GripPos)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the serialization of Property [Tool.GripPos](https://create.roblox.com/docs/reference/engine/classes/Tool#GripPos)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Tool.GripRight](https://create.roblox.com/docs/reference/engine/classes/Tool#GripRight)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the serialization of Property [Tool.GripRight](https://create.roblox.com/docs/reference/engine/classes/Tool#GripRight)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Tool.GripUp](https://create.roblox.com/docs/reference/engine/classes/Tool#GripUp)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the serialization of Property [Tool.GripUp](https://create.roblox.com/docs/reference/engine/classes/Tool#GripUp)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [Tool.ManualActivationOnly](https://create.roblox.com/docs/reference/engine/classes/Tool#ManualActivationOnly)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Tool.RequiresHandle](https://create.roblox.com/docs/reference/engine/classes/Tool#RequiresHandle)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Tool.ToolTip](https://create.roblox.com/docs/reference/engine/classes/Tool#ToolTip)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the return-type of Function [Tool.Activate](https://create.roblox.com/docs/reference/engine/classes/Tool#Activate) from null to void
  * Changed the capabilities of Function [Tool.Activate](https://create.roblox.com/docs/reference/engine/classes/Tool#Activate)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [Tool.Deactivate](https://create.roblox.com/docs/reference/engine/classes/Tool#Deactivate) from null to void
  * Changed the capabilities of Function [Tool.Deactivate](https://create.roblox.com/docs/reference/engine/classes/Tool#Deactivate)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Tool.Activated](https://create.roblox.com/docs/reference/engine/classes/Tool#Activated)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Tool.Deactivated](https://create.roblox.com/docs/reference/engine/classes/Tool#Deactivated)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Tool.Equipped](https://create.roblox.com/docs/reference/engine/classes/Tool#Equipped)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Tool.Unequipped](https://create.roblox.com/docs/reference/engine/classes/Tool#Unequipped)
    from: {🚧Input}
    to: {🚧None}
* Update Class [Flag](https://create.roblox.com/docs/reference/engine/classes/Flag) [⬆️Extends: Tool] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed MemoryCategory of Class [Flag](https://create.roblox.com/docs/reference/engine/classes/Flag) from `BaseParts` to `Instances`
  * Changed the capabilities of Property [Flag.TeamColor](https://create.roblox.com/docs/reference/engine/classes/Flag#TeamColor)
    from: {🚧Read: Basic, Input}
    to: {🚧None}
* Update Class [BadgeService](https://create.roblox.com/docs/reference/engine/classes/BadgeService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the parameters of Function [BadgeService.AwardBadge](https://create.roblox.com/docs/reference/engine/classes/BadgeService#AwardBadge)
    from: (userId: User, badgeId: int64)
    to: (userId: int64, badgeId: int64)
  * Changed the capabilities of Function [BadgeService.AwardBadge](https://create.roblox.com/docs/reference/engine/classes/BadgeService#AwardBadge)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the capabilities of Function [BadgeService.GetBadgeInfoAsync](https://create.roblox.com/docs/reference/engine/classes/BadgeService#GetBadgeInfoAsync)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the capabilities of Function [BadgeService.IsDisabled](https://create.roblox.com/docs/reference/engine/classes/BadgeService#IsDisabled)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the capabilities of Function [BadgeService.IsLegal](https://create.roblox.com/docs/reference/engine/classes/BadgeService#IsLegal)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the parameters of Function [BadgeService.UserHasBadge](https://create.roblox.com/docs/reference/engine/classes/BadgeService#UserHasBadge)
    from: (userId: User, badgeId: int64)
    to: (userId: int64, badgeId: int64)
  * Changed the capabilities of Function [BadgeService.UserHasBadge](https://create.roblox.com/docs/reference/engine/classes/BadgeService#UserHasBadge)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the parameters of Function [BadgeService.UserHasBadgeAsync](https://create.roblox.com/docs/reference/engine/classes/BadgeService#UserHasBadgeAsync)
    from: (userId: User, badgeId: int64)
    to: (userId: int64, badgeId: int64)
  * Changed the capabilities of Function [BadgeService.UserHasBadgeAsync](https://create.roblox.com/docs/reference/engine/classes/BadgeService#UserHasBadgeAsync)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the capabilities of Event [BadgeService.BadgeAwarded](https://create.roblox.com/docs/reference/engine/classes/BadgeService#BadgeAwarded)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the capabilities of Event [BadgeService.OnBadgeAwarded](https://create.roblox.com/docs/reference/engine/classes/BadgeService#OnBadgeAwarded)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Removed Function BadgeService.AwardBadgeAsync
  * Removed Function BadgeService.CheckUserBadgesAsync
  * Removed Function BadgeService.GetUserBadgesAsync
* Update Class [BasePlayerGui](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [BasePlayerGui.GetGuiObjectsAtPosition](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui#GetGuiObjectsAtPosition) from Instances to Objects
  * Changed the capabilities of Function [BasePlayerGui.GetGuiObjectsAtPosition](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui#GetGuiObjectsAtPosition)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [BasePlayerGui.GetGuiObjectsInCircle](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui#GetGuiObjectsInCircle) from Instances to Objects
  * Changed the capabilities of Function [BasePlayerGui.GetGuiObjectsInCircle](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui#GetGuiObjectsInCircle)
    from: {🚧UI}
    to: {🚧None}
* Update Class [CoreGui](https://create.roblox.com/docs/reference/engine/classes/CoreGui) [⬆️Extends: BasePlayerGui] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [CoreGui.SelectionImageObject](https://create.roblox.com/docs/reference/engine/classes/CoreGui#SelectionImageObject)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [CoreGui.Version](https://create.roblox.com/docs/reference/engine/classes/CoreGui#Version)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [CoreGui.SetUserGuiRendering](https://create.roblox.com/docs/reference/engine/classes/CoreGui#SetUserGuiRendering) from null to void
  * Changed the parameters of Function [CoreGui.SetUserGuiRendering](https://create.roblox.com/docs/reference/engine/classes/CoreGui#SetUserGuiRendering)
    from: (enabled: bool, guiAdornee: Instance, faceId: NormalId, horizontalCurvature: float = 0)
    to: (enabled: bool, guiAdornee: Instance, faceId: NormalId)
  * Changed the capabilities of Function [CoreGui.SetUserGuiRendering](https://create.roblox.com/docs/reference/engine/classes/CoreGui#SetUserGuiRendering)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [CoreGui.TakeScreenshot](https://create.roblox.com/docs/reference/engine/classes/CoreGui#TakeScreenshot) from null to void
  * Changed the capabilities of Function [CoreGui.TakeScreenshot](https://create.roblox.com/docs/reference/engine/classes/CoreGui#TakeScreenshot)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [CoreGui.ToggleRecording](https://create.roblox.com/docs/reference/engine/classes/CoreGui#ToggleRecording) from null to void
  * Changed the capabilities of Function [CoreGui.ToggleRecording](https://create.roblox.com/docs/reference/engine/classes/CoreGui#ToggleRecording)
    from: {🚧UI}
    to: {🚧None}
  * Removed Event CoreGui.UserGuiRenderingChanged
* Update Class [PlayerGui](https://create.roblox.com/docs/reference/engine/classes/PlayerGui) [⬆️Extends: BasePlayerGui] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ PlayerReplicated]
  * Changed the capabilities of Property [PlayerGui.CurrentScreenOrientation](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#CurrentScreenOrientation)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [PlayerGui.ScreenOrientation](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#ScreenOrientation)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [PlayerGui.SelectionImageObject](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#SelectionImageObject)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Function [PlayerGui.GetTopbarTransparency](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#GetTopbarTransparency)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [PlayerGui.SetTopbarTransparency](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#SetTopbarTransparency) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [PlayerGui.SetTopbarTransparency](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#SetTopbarTransparency)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [PlayerGui.TopbarTransparencyChangedSignal](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#TopbarTransparencyChangedSignal)
    from: {🚧UI}
    to: {🚧None}
* Update Class [StarterGui](https://create.roblox.com/docs/reference/engine/classes/StarterGui) [⬆️Extends: BasePlayerGui] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [StarterGui.ProcessUserInput](https://create.roblox.com/docs/reference/engine/classes/StarterGui#ProcessUserInput)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [StarterGui.ResetPlayerGuiOnSpawn](https://create.roblox.com/docs/reference/engine/classes/StarterGui#ResetPlayerGuiOnSpawn)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [StarterGui.ScreenOrientation](https://create.roblox.com/docs/reference/engine/classes/StarterGui#ScreenOrientation)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [StarterGui.ShowDevelopmentGui](https://create.roblox.com/docs/reference/engine/classes/StarterGui#ShowDevelopmentGui)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [StarterGui.VirtualCursorMode](https://create.roblox.com/docs/reference/engine/classes/StarterGui#VirtualCursorMode)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Function [StarterGui.GetCoreGuiEnabled](https://create.roblox.com/docs/reference/engine/classes/StarterGui#GetCoreGuiEnabled)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [StarterGui.RegisterGetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#RegisterGetCore) from null to void
  * Changed the capabilities of Function [StarterGui.RegisterGetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#RegisterGetCore)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [StarterGui.RegisterSetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#RegisterSetCore) from null to void
  * Changed the capabilities of Function [StarterGui.RegisterSetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#RegisterSetCore)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [StarterGui.SetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#SetCore) from null to void
  * Changed the capabilities of Function [StarterGui.SetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#SetCore)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [StarterGui.SetCoreGuiEnabled](https://create.roblox.com/docs/reference/engine/classes/StarterGui#SetCoreGuiEnabled) from null to void
  * Changed the capabilities of Function [StarterGui.SetCoreGuiEnabled](https://create.roblox.com/docs/reference/engine/classes/StarterGui#SetCoreGuiEnabled)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [StarterGui.GetCore](https://create.roblox.com/docs/reference/engine/classes/StarterGui#GetCore)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [StarterGui.CoreGuiChangedSignal](https://create.roblox.com/docs/reference/engine/classes/StarterGui#CoreGuiChangedSignal)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property StarterGui.ClipsDescendantsSupportsRotation
  * Removed Property StarterGui.RtlTextSupport
  * Removed Property StarterGui.StudioDefaultStyleSheet
  * Removed Property StarterGui.StudioInsertWidgetLayerCollectorAutoLinkStyleSheet
* Update Class [BaseWrap](https://create.roblox.com/docs/reference/engine/classes/BaseWrap) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [BaseWrap.CageMeshId](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageMeshId)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BaseWrap.CageOrigin](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageOrigin)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BaseWrap.CageOriginWorld](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageOriginWorld)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BaseWrap.ImportOrigin](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#ImportOrigin)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BaseWrap.ImportOriginWorld](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#ImportOriginWorld)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [BaseWrap.GetFaces](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#GetFaces)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [BaseWrap.GetVertices](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#GetVertices)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [BaseWrap.ModifyVertices](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#ModifyVertices) from null to void
  * Changed the capabilities of Function [BaseWrap.ModifyVertices](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#ModifyVertices)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Removed Property BaseWrap.CageMeshContent
  * Removed Property BaseWrap.HSRAssetId
  * Removed Property BaseWrap.HSRContent
  * Removed Function BaseWrap.GetCageOffset
  * Removed Function BaseWrap.GetUVs
  * Removed Function BaseWrap.IsHSRReady
  * Removed Event BaseWrap.VerticesModified
* Update Class [WrapLayer](https://create.roblox.com/docs/reference/engine/classes/WrapLayer) [⬆️Extends: BaseWrap] [🧠Memory: Instances]
  * Changed the capabilities of Property [WrapLayer.BindOffset](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#BindOffset)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapLayer.Color](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#Color)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapLayer.DebugMode](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#DebugMode)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapLayer.Enabled](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#Enabled)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the security of Property [WrapLayer.Order](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#Order)
    from: {🔒None}
    to: {🔒Read:None, Write:PluginSecurity}
  * Changed the capabilities of Property [WrapLayer.Order](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#Order)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the security of Property [WrapLayer.Puffiness](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#Puffiness)
    from: {🔒None}
    to: {🔒Read:None, Write:PluginSecurity}
  * Changed the capabilities of Property [WrapLayer.Puffiness](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#Puffiness)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapLayer.ReferenceMeshId](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceMeshId)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapLayer.ReferenceOrigin](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceOrigin)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapLayer.ReferenceOriginWorld](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceOriginWorld)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapLayer.ShrinkFactor](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ShrinkFactor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Removed Property WrapLayer.AutoSkin
  * Removed Property WrapLayer.MaxSize
  * Removed Property WrapLayer.Offset
  * Removed Property WrapLayer.ReferenceMeshContent
* Update Class [WrapTarget](https://create.roblox.com/docs/reference/engine/classes/WrapTarget) [⬆️Extends: BaseWrap] [🧠Memory: Instances]
  * Changed the capabilities of Property [WrapTarget.Color](https://create.roblox.com/docs/reference/engine/classes/WrapTarget#Color)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapTarget.DebugMode](https://create.roblox.com/docs/reference/engine/classes/WrapTarget#DebugMode)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [WrapTarget.Stiffness](https://create.roblox.com/docs/reference/engine/classes/WrapTarget#Stiffness)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
* Update Class [Beam](https://create.roblox.com/docs/reference/engine/classes/Beam) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Beam.Attachment0](https://create.roblox.com/docs/reference/engine/classes/Beam#Attachment0)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.Attachment1](https://create.roblox.com/docs/reference/engine/classes/Beam#Attachment1)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.Color](https://create.roblox.com/docs/reference/engine/classes/Beam#Color)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.CurveSize0](https://create.roblox.com/docs/reference/engine/classes/Beam#CurveSize0)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.CurveSize1](https://create.roblox.com/docs/reference/engine/classes/Beam#CurveSize1)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.Enabled](https://create.roblox.com/docs/reference/engine/classes/Beam#Enabled)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.FaceCamera](https://create.roblox.com/docs/reference/engine/classes/Beam#FaceCamera)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.LightEmission](https://create.roblox.com/docs/reference/engine/classes/Beam#LightEmission)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.LightInfluence](https://create.roblox.com/docs/reference/engine/classes/Beam#LightInfluence)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.Segments](https://create.roblox.com/docs/reference/engine/classes/Beam#Segments)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.Texture](https://create.roblox.com/docs/reference/engine/classes/Beam#Texture)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.TextureLength](https://create.roblox.com/docs/reference/engine/classes/Beam#TextureLength)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.TextureMode](https://create.roblox.com/docs/reference/engine/classes/Beam#TextureMode)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.TextureSpeed](https://create.roblox.com/docs/reference/engine/classes/Beam#TextureSpeed)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.Transparency](https://create.roblox.com/docs/reference/engine/classes/Beam#Transparency)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.Width0](https://create.roblox.com/docs/reference/engine/classes/Beam#Width0)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.Width1](https://create.roblox.com/docs/reference/engine/classes/Beam#Width1)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Beam.ZOffset](https://create.roblox.com/docs/reference/engine/classes/Beam#ZOffset)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [Beam.SetTextureOffset](https://create.roblox.com/docs/reference/engine/classes/Beam#SetTextureOffset) from null to void
  * Changed the capabilities of Function [Beam.SetTextureOffset](https://create.roblox.com/docs/reference/engine/classes/Beam#SetTextureOffset)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Property Beam.Brightness
  * Removed Property Beam.LocalTransparencyModifier
  * Removed Property Beam.TextureContent
* Update Class [BindableEvent](https://create.roblox.com/docs/reference/engine/classes/BindableEvent) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the return-type of Function [BindableEvent.Fire](https://create.roblox.com/docs/reference/engine/classes/BindableEvent#Fire) from null to void [⚡ThreadSafety: Safe]
* Update Class [BodyAngularVelocity](https://create.roblox.com/docs/reference/engine/classes/BodyAngularVelocity) [⬆️Extends: BodyMover] [🧠Memory: Instances]
  * Changed the capabilities of Property [BodyAngularVelocity.AngularVelocity](https://create.roblox.com/docs/reference/engine/classes/BodyAngularVelocity#AngularVelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyAngularVelocity.MaxTorque](https://create.roblox.com/docs/reference/engine/classes/BodyAngularVelocity#MaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyAngularVelocity.P](https://create.roblox.com/docs/reference/engine/classes/BodyAngularVelocity#P)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyAngularVelocity.angularvelocity](https://create.roblox.com/docs/reference/engine/classes/BodyAngularVelocity#angularvelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyAngularVelocity.maxTorque](https://create.roblox.com/docs/reference/engine/classes/BodyAngularVelocity#maxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [BodyForce](https://create.roblox.com/docs/reference/engine/classes/BodyForce) [⬆️Extends: BodyMover] [🧠Memory: Instances]
  * Changed the capabilities of Property [BodyForce.Force](https://create.roblox.com/docs/reference/engine/classes/BodyForce#Force)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyForce.force](https://create.roblox.com/docs/reference/engine/classes/BodyForce#force)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [BodyGyro](https://create.roblox.com/docs/reference/engine/classes/BodyGyro) [⬆️Extends: BodyMover] [🧠Memory: Instances]
  * Changed the capabilities of Property [BodyGyro.CFrame](https://create.roblox.com/docs/reference/engine/classes/BodyGyro#CFrame)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyGyro.D](https://create.roblox.com/docs/reference/engine/classes/BodyGyro#D)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyGyro.MaxTorque](https://create.roblox.com/docs/reference/engine/classes/BodyGyro#MaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyGyro.P](https://create.roblox.com/docs/reference/engine/classes/BodyGyro#P)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyGyro.cframe](https://create.roblox.com/docs/reference/engine/classes/BodyGyro#cframe)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyGyro.maxTorque](https://create.roblox.com/docs/reference/engine/classes/BodyGyro#maxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [BodyPosition](https://create.roblox.com/docs/reference/engine/classes/BodyPosition) [⬆️Extends: BodyMover] [🧠Memory: Instances]
  * Changed the capabilities of Property [BodyPosition.D](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#D)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyPosition.MaxForce](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#MaxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyPosition.P](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#P)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyPosition.Position](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#Position)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyPosition.maxForce](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#maxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyPosition.position](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#position)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Function [BodyPosition.GetLastForce](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#GetLastForce)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Function [BodyPosition.lastForce](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#lastForce)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Event [BodyPosition.ReachedTarget](https://create.roblox.com/docs/reference/engine/classes/BodyPosition#ReachedTarget)
    from: {🚧Physics}
    to: {🚧None}
* Update Class [BodyThrust](https://create.roblox.com/docs/reference/engine/classes/BodyThrust) [⬆️Extends: BodyMover] [🧠Memory: Instances]
  * Changed the capabilities of Property [BodyThrust.Force](https://create.roblox.com/docs/reference/engine/classes/BodyThrust#Force)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyThrust.Location](https://create.roblox.com/docs/reference/engine/classes/BodyThrust#Location)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyThrust.force](https://create.roblox.com/docs/reference/engine/classes/BodyThrust#force)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyThrust.location](https://create.roblox.com/docs/reference/engine/classes/BodyThrust#location)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [BodyVelocity](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity) [⬆️Extends: BodyMover] [🧠Memory: Instances]
  * Changed the capabilities of Property [BodyVelocity.MaxForce](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity#MaxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyVelocity.P](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity#P)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyVelocity.Velocity](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity#Velocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyVelocity.maxForce](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity#maxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BodyVelocity.velocity](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity#velocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Function [BodyVelocity.GetLastForce](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity#GetLastForce)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Function [BodyVelocity.lastForce](https://create.roblox.com/docs/reference/engine/classes/BodyVelocity#lastForce)
    from: {🚧Physics}
    to: {🚧None}
* Update Class [RocketPropulsion](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion) [⬆️Extends: BodyMover] [🧠Memory: Instances]
  * Changed the capabilities of Property [RocketPropulsion.CartoonFactor](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#CartoonFactor)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.MaxSpeed](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#MaxSpeed)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.MaxThrust](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#MaxThrust)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.MaxTorque](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#MaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.Target](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#Target)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.TargetOffset](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#TargetOffset)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.TargetRadius](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#TargetRadius)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.ThrustD](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#ThrustD)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.ThrustP](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#ThrustP)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.TurnD](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#TurnD)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RocketPropulsion.TurnP](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#TurnP)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the return-type of Function [RocketPropulsion.Abort](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#Abort) from null to void
  * Changed the capabilities of Function [RocketPropulsion.Abort](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#Abort)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [RocketPropulsion.Fire](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#Fire) from null to void
  * Changed the capabilities of Function [RocketPropulsion.Fire](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#Fire)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [RocketPropulsion.fire](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#fire) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [RocketPropulsion.fire](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#fire)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Event [RocketPropulsion.ReachedTarget](https://create.roblox.com/docs/reference/engine/classes/RocketPropulsion#ReachedTarget)
    from: {🚧Physics}
    to: {🚧None}
* Update Class [Breakpoint](https://create.roblox.com/docs/reference/engine/classes/Breakpoint) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Removed Property Breakpoint.ContinueExecution
  * Removed Property Breakpoint.MetaBreakpointId
  * Removed Property Breakpoint.RemoveOnHit
  * Removed Property Breakpoint.Valid
* Update Class [BrowserService](https://create.roblox.com/docs/reference/engine/classes/BrowserService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [BrowserService.CloseBrowserWindow](https://create.roblox.com/docs/reference/engine/classes/BrowserService#CloseBrowserWindow) from null to void
  * Changed the return-type of Function [BrowserService.CopyAuthCookieFromBrowserToEngine](https://create.roblox.com/docs/reference/engine/classes/BrowserService#CopyAuthCookieFromBrowserToEngine) from null to void
  * Changed the return-type of Function [BrowserService.EmitHybridEvent](https://create.roblox.com/docs/reference/engine/classes/BrowserService#EmitHybridEvent) from null to void
  * Changed the return-type of Function [BrowserService.ExecuteJavaScript](https://create.roblox.com/docs/reference/engine/classes/BrowserService#ExecuteJavaScript) from null to void
  * Changed the return-type of Function [BrowserService.OpenBrowserWindow](https://create.roblox.com/docs/reference/engine/classes/BrowserService#OpenBrowserWindow) from null to void
  * Changed the return-type of Function [BrowserService.OpenNativeOverlay](https://create.roblox.com/docs/reference/engine/classes/BrowserService#OpenNativeOverlay) from null to void
  * Changed the return-type of Function [BrowserService.OpenWeChatAuthWindow](https://create.roblox.com/docs/reference/engine/classes/BrowserService#OpenWeChatAuthWindow) from null to void
  * Changed the return-type of Function [BrowserService.ReturnToJavaScript](https://create.roblox.com/docs/reference/engine/classes/BrowserService#ReturnToJavaScript) from null to void
  * Changed the return-type of Function [BrowserService.SendCommand](https://create.roblox.com/docs/reference/engine/classes/BrowserService#SendCommand) from null to void
* Update Class [BulkImportService](https://create.roblox.com/docs/reference/engine/classes/BulkImportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [BulkImportService.LaunchBulkImport](https://create.roblox.com/docs/reference/engine/classes/BulkImportService#LaunchBulkImport) from null to void
  * Changed the return-type of Function [BulkImportService.ShowBulkImportView](https://create.roblox.com/docs/reference/engine/classes/BulkImportService#ShowBulkImportView) from null to void
* Update Class [MeshContentProvider](https://create.roblox.com/docs/reference/engine/classes/MeshContentProvider) [⬆️Extends: CacheableContentProvider] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Function [MeshContentProvider.GetContentMemoryData](https://create.roblox.com/docs/reference/engine/classes/MeshContentProvider#GetContentMemoryData)
    from: {🚧AssetManagement}
    to: {🚧None}
* Update Class [CalloutService](https://create.roblox.com/docs/reference/engine/classes/CalloutService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [CalloutService.AttachCallout](https://create.roblox.com/docs/reference/engine/classes/CalloutService#AttachCallout) from null to void
  * Changed the return-type of Function [CalloutService.DefineCallout](https://create.roblox.com/docs/reference/engine/classes/CalloutService#DefineCallout) from null to void
  * Changed the return-type of Function [CalloutService.DetachCalloutsByDefinitionId](https://create.roblox.com/docs/reference/engine/classes/CalloutService#DetachCalloutsByDefinitionId) from null to void
* Update Class [Camera](https://create.roblox.com/docs/reference/engine/classes/Camera) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Changed Superclass of Class [Camera](https://create.roblox.com/docs/reference/engine/classes/Camera) from `PVInstance` to `Instance`
  * Changed the capabilities of Property [Camera.CFrame](https://create.roblox.com/docs/reference/engine/classes/Camera#CFrame)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.CameraSubject](https://create.roblox.com/docs/reference/engine/classes/Camera#CameraSubject)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.CameraType](https://create.roblox.com/docs/reference/engine/classes/Camera#CameraType)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.CoordinateFrame](https://create.roblox.com/docs/reference/engine/classes/Camera#CoordinateFrame)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.DiagonalFieldOfView](https://create.roblox.com/docs/reference/engine/classes/Camera#DiagonalFieldOfView)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.FieldOfView](https://create.roblox.com/docs/reference/engine/classes/Camera#FieldOfView)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.FieldOfViewMode](https://create.roblox.com/docs/reference/engine/classes/Camera#FieldOfViewMode)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.Focus](https://create.roblox.com/docs/reference/engine/classes/Camera#Focus)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.HeadLocked](https://create.roblox.com/docs/reference/engine/classes/Camera#HeadLocked)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.HeadScale](https://create.roblox.com/docs/reference/engine/classes/Camera#HeadScale)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.MaxAxisFieldOfView](https://create.roblox.com/docs/reference/engine/classes/Camera#MaxAxisFieldOfView)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.NearPlaneZ](https://create.roblox.com/docs/reference/engine/classes/Camera#NearPlaneZ)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.ViewportSize](https://create.roblox.com/docs/reference/engine/classes/Camera#ViewportSize)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Camera.focus](https://create.roblox.com/docs/reference/engine/classes/Camera#focus)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the parameters of Function [Camera.GetLargestCutoffDistance](https://create.roblox.com/docs/reference/engine/classes/Camera#GetLargestCutoffDistance)
    from: (ignoreList: Instances)
    to: (ignoreList: Objects)
  * Changed the capabilities of Function [Camera.GetLargestCutoffDistance](https://create.roblox.com/docs/reference/engine/classes/Camera#GetLargestCutoffDistance)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.GetPanSpeed](https://create.roblox.com/docs/reference/engine/classes/Camera#GetPanSpeed)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Camera.GetPartsObscuringTarget](https://create.roblox.com/docs/reference/engine/classes/Camera#GetPartsObscuringTarget) from Instances to Objects
  * Changed the parameters of Function [Camera.GetPartsObscuringTarget](https://create.roblox.com/docs/reference/engine/classes/Camera#GetPartsObscuringTarget)
    from: (castPoints: Array, ignoreList: Instances)
    to: (castPoints: Array, ignoreList: Objects)
  * Changed the capabilities of Function [Camera.GetPartsObscuringTarget](https://create.roblox.com/docs/reference/engine/classes/Camera#GetPartsObscuringTarget)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.GetRenderCFrame](https://create.roblox.com/docs/reference/engine/classes/Camera#GetRenderCFrame)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.GetRoll](https://create.roblox.com/docs/reference/engine/classes/Camera#GetRoll)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.GetTiltSpeed](https://create.roblox.com/docs/reference/engine/classes/Camera#GetTiltSpeed)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Camera.Interpolate](https://create.roblox.com/docs/reference/engine/classes/Camera#Interpolate) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Camera.Interpolate](https://create.roblox.com/docs/reference/engine/classes/Camera#Interpolate)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Camera.PanUnits](https://create.roblox.com/docs/reference/engine/classes/Camera#PanUnits) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Camera.PanUnits](https://create.roblox.com/docs/reference/engine/classes/Camera#PanUnits)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.ScreenPointToRay](https://create.roblox.com/docs/reference/engine/classes/Camera#ScreenPointToRay)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Camera.SetCameraPanMode](https://create.roblox.com/docs/reference/engine/classes/Camera#SetCameraPanMode) from null to void
  * Changed the capabilities of Function [Camera.SetCameraPanMode](https://create.roblox.com/docs/reference/engine/classes/Camera#SetCameraPanMode)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Camera.SetImageServerView](https://create.roblox.com/docs/reference/engine/classes/Camera#SetImageServerView) from null to void
  * Changed the capabilities of Function [Camera.SetImageServerView](https://create.roblox.com/docs/reference/engine/classes/Camera#SetImageServerView)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Camera.SetRoll](https://create.roblox.com/docs/reference/engine/classes/Camera#SetRoll) from null to void
  * Changed the capabilities of Function [Camera.SetRoll](https://create.roblox.com/docs/reference/engine/classes/Camera#SetRoll)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.TiltUnits](https://create.roblox.com/docs/reference/engine/classes/Camera#TiltUnits)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.ViewportPointToRay](https://create.roblox.com/docs/reference/engine/classes/Camera#ViewportPointToRay)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.WorldToScreenPoint](https://create.roblox.com/docs/reference/engine/classes/Camera#WorldToScreenPoint)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.WorldToViewportPoint](https://create.roblox.com/docs/reference/engine/classes/Camera#WorldToViewportPoint)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Camera.Zoom](https://create.roblox.com/docs/reference/engine/classes/Camera#Zoom)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [Camera.FirstPersonTransition](https://create.roblox.com/docs/reference/engine/classes/Camera#FirstPersonTransition)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [Camera.InterpolationFinished](https://create.roblox.com/docs/reference/engine/classes/Camera#InterpolationFinished)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Property Camera.VRTiltAndRollEnabled
  * Removed Function Camera.ZoomToExtents
* Update Class [ChangeHistoryService](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [ChangeHistoryService.Redo](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#Redo) from null to void
  * Changed the return-type of Function [ChangeHistoryService.ResetWaypoints](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#ResetWaypoints) from null to void
  * Changed the return-type of Function [ChangeHistoryService.SetEnabled](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#SetEnabled) from null to void
  * Changed the return-type of Function [ChangeHistoryService.SetWaypoint](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#SetWaypoint) from null to void
  * Changed the return-type of Function [ChangeHistoryService.Undo](https://create.roblox.com/docs/reference/engine/classes/ChangeHistoryService#Undo) from null to void
  * Removed Function ChangeHistoryService.FinishRecording
  * Removed Function ChangeHistoryService.IsRecordingInProgress
  * Removed Function ChangeHistoryService.TryBeginRecording
  * Removed Event ChangeHistoryService.OnRecordingFinished
  * Removed Event ChangeHistoryService.OnRecordingStarted
* Update Class [BodyColors](https://create.roblox.com/docs/reference/engine/classes/BodyColors) [⬆️Extends: CharacterAppearance] [🧠Memory: Instances]
  * Changed the capabilities of Property [BodyColors.HeadColor](https://create.roblox.com/docs/reference/engine/classes/BodyColors#HeadColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.HeadColor3](https://create.roblox.com/docs/reference/engine/classes/BodyColors#HeadColor3)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.LeftArmColor](https://create.roblox.com/docs/reference/engine/classes/BodyColors#LeftArmColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.LeftArmColor3](https://create.roblox.com/docs/reference/engine/classes/BodyColors#LeftArmColor3)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.LeftLegColor](https://create.roblox.com/docs/reference/engine/classes/BodyColors#LeftLegColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.LeftLegColor3](https://create.roblox.com/docs/reference/engine/classes/BodyColors#LeftLegColor3)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.RightArmColor](https://create.roblox.com/docs/reference/engine/classes/BodyColors#RightArmColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.RightArmColor3](https://create.roblox.com/docs/reference/engine/classes/BodyColors#RightArmColor3)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.RightLegColor](https://create.roblox.com/docs/reference/engine/classes/BodyColors#RightLegColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.RightLegColor3](https://create.roblox.com/docs/reference/engine/classes/BodyColors#RightLegColor3)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.TorsoColor](https://create.roblox.com/docs/reference/engine/classes/BodyColors#TorsoColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [BodyColors.TorsoColor3](https://create.roblox.com/docs/reference/engine/classes/BodyColors#TorsoColor3)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
* Update Class [CharacterMesh](https://create.roblox.com/docs/reference/engine/classes/CharacterMesh) [⬆️Extends: CharacterAppearance] [🧠Memory: Instances]
  * Changed the capabilities of Property [CharacterMesh.BaseTextureId](https://create.roblox.com/docs/reference/engine/classes/CharacterMesh#BaseTextureId)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [CharacterMesh.BodyPart](https://create.roblox.com/docs/reference/engine/classes/CharacterMesh#BodyPart)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [CharacterMesh.MeshId](https://create.roblox.com/docs/reference/engine/classes/CharacterMesh#MeshId)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [CharacterMesh.OverlayTextureId](https://create.roblox.com/docs/reference/engine/classes/CharacterMesh#OverlayTextureId)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Removed Property CharacterMesh.BaseTextureContent
  * Removed Property CharacterMesh.MeshContent
  * Removed Property CharacterMesh.OverlayTextureContent
* Update Class [Clothing](https://create.roblox.com/docs/reference/engine/classes/Clothing) [⬆️Extends: CharacterAppearance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [Clothing.Color3](https://create.roblox.com/docs/reference/engine/classes/Clothing#Color3)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
* Update Class [Pants](https://create.roblox.com/docs/reference/engine/classes/Pants) [⬆️Extends: Clothing] [🧠Memory: Instances]
  * Changed the capabilities of Property [Pants.PantsTemplate](https://create.roblox.com/docs/reference/engine/classes/Pants#PantsTemplate)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Removed Property Pants.PantsTemplateContent
* Update Class [Shirt](https://create.roblox.com/docs/reference/engine/classes/Shirt) [⬆️Extends: Clothing] [🧠Memory: Instances]
  * Changed the capabilities of Property [Shirt.ShirtTemplate](https://create.roblox.com/docs/reference/engine/classes/Shirt#ShirtTemplate)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Removed Property Shirt.ShirtTemplateContent
* Update Class [ShirtGraphic](https://create.roblox.com/docs/reference/engine/classes/ShirtGraphic) [⬆️Extends: CharacterAppearance] [🧠Memory: Instances]
  * Changed the capabilities of Property [ShirtGraphic.Color3](https://create.roblox.com/docs/reference/engine/classes/ShirtGraphic#Color3)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [ShirtGraphic.Graphic](https://create.roblox.com/docs/reference/engine/classes/ShirtGraphic#Graphic)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Removed Property ShirtGraphic.TextureContent
* Update Class [Skin](https://create.roblox.com/docs/reference/engine/classes/Skin) [⬆️Extends: CharacterAppearance] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed the capabilities of Property [Skin.SkinColor](https://create.roblox.com/docs/reference/engine/classes/Skin#SkinColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
* Update Class [Chat](https://create.roblox.com/docs/reference/engine/classes/Chat) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [Chat.BubbleChatEnabled](https://create.roblox.com/docs/reference/engine/classes/Chat#BubbleChatEnabled)
    from: {🚧Read: Chat}
    to: {🚧None}
  * Changed the capabilities of Property [Chat.LoadDefaultChat](https://create.roblox.com/docs/reference/engine/classes/Chat#LoadDefaultChat)
    from: {🚧Read: Chat}
    to: {🚧None}
  * Changed the return-type of Function [Chat.Chat](https://create.roblox.com/docs/reference/engine/classes/Chat#Chat) from null to void
  * Changed the capabilities of Function [Chat.Chat](https://create.roblox.com/docs/reference/engine/classes/Chat#Chat)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the return-type of Function [Chat.ChatLocal](https://create.roblox.com/docs/reference/engine/classes/Chat#ChatLocal) from null to void
  * Changed the capabilities of Function [Chat.ChatLocal](https://create.roblox.com/docs/reference/engine/classes/Chat#ChatLocal)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Function [Chat.GetShouldUseLuaChat](https://create.roblox.com/docs/reference/engine/classes/Chat#GetShouldUseLuaChat)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Function [Chat.InvokeChatCallback](https://create.roblox.com/docs/reference/engine/classes/Chat#InvokeChatCallback)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the return-type of Function [Chat.RegisterChatCallback](https://create.roblox.com/docs/reference/engine/classes/Chat#RegisterChatCallback) from null to void
  * Changed the capabilities of Function [Chat.RegisterChatCallback](https://create.roblox.com/docs/reference/engine/classes/Chat#RegisterChatCallback)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the return-type of Function [Chat.SetBubbleChatSettings](https://create.roblox.com/docs/reference/engine/classes/Chat#SetBubbleChatSettings) from null to void
  * Changed the capabilities of Function [Chat.SetBubbleChatSettings](https://create.roblox.com/docs/reference/engine/classes/Chat#SetBubbleChatSettings)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Function [Chat.CanUserChatAsync](https://create.roblox.com/docs/reference/engine/classes/Chat#CanUserChatAsync)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Function [Chat.CanUsersChatAsync](https://create.roblox.com/docs/reference/engine/classes/Chat#CanUsersChatAsync)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Function [Chat.FilterStringAsync](https://create.roblox.com/docs/reference/engine/classes/Chat#FilterStringAsync)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Function [Chat.FilterStringForBroadcast](https://create.roblox.com/docs/reference/engine/classes/Chat#FilterStringForBroadcast)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Function [Chat.FilterStringForPlayerAsync](https://create.roblox.com/docs/reference/engine/classes/Chat#FilterStringForPlayerAsync)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Event [Chat.BubbleChatSettingsChanged](https://create.roblox.com/docs/reference/engine/classes/Chat#BubbleChatSettingsChanged)
    from: {🚧Chat}
    to: {🚧None}
  * Changed the capabilities of Event [Chat.Chatted](https://create.roblox.com/docs/reference/engine/classes/Chat#Chatted)
    from: {🚧Chat}
    to: {🚧None}
  * Removed Property Chat.IsAutoMigrated
  * Removed Property Chat.ModerationMode
  * Removed Function Chat.ReconcileCommunicationAccess
  * Removed Function Chat.RequestModerationModeEnabled
  * Removed Event Chat.PlayerChatAvailabilityStatusChanged
  * Removed Event Chat.ReconcileCommunicationAccessCompleted
  * Removed Event Chat.TimeoutChatAttempt
* Update Class [ClickDetector](https://create.roblox.com/docs/reference/engine/classes/ClickDetector) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [ClickDetector.CursorIcon](https://create.roblox.com/docs/reference/engine/classes/ClickDetector#CursorIcon)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [ClickDetector.MaxActivationDistance](https://create.roblox.com/docs/reference/engine/classes/ClickDetector#MaxActivationDistance)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Event [ClickDetector.MouseClick](https://create.roblox.com/docs/reference/engine/classes/ClickDetector#MouseClick)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ClickDetector.MouseHoverEnter](https://create.roblox.com/docs/reference/engine/classes/ClickDetector#MouseHoverEnter)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ClickDetector.MouseHoverLeave](https://create.roblox.com/docs/reference/engine/classes/ClickDetector#MouseHoverLeave)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ClickDetector.RightMouseClick](https://create.roblox.com/docs/reference/engine/classes/ClickDetector#RightMouseClick)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ClickDetector.mouseClick](https://create.roblox.com/docs/reference/engine/classes/ClickDetector#mouseClick)
    from: {🚧Input}
    to: {🚧None}
  * Removed Property ClickDetector.CursorIconContent
* Update Class [Clouds](https://create.roblox.com/docs/reference/engine/classes/Clouds) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Clouds.Color](https://create.roblox.com/docs/reference/engine/classes/Clouds#Color)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Clouds.Cover](https://create.roblox.com/docs/reference/engine/classes/Clouds#Cover)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Clouds.Density](https://create.roblox.com/docs/reference/engine/classes/Clouds#Density)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Clouds.Enabled](https://create.roblox.com/docs/reference/engine/classes/Clouds#Enabled)
    from: {🚧Read: Environment}
    to: {🚧None}
* Update Class [CollectionService](https://create.roblox.com/docs/reference/engine/classes/CollectionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [CollectionService.AddTag](https://create.roblox.com/docs/reference/engine/classes/CollectionService#AddTag) from null to void
  * Changed the capabilities of Function [CollectionService.AddTag](https://create.roblox.com/docs/reference/engine/classes/CollectionService#AddTag)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [CollectionService.GetCollection](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetCollection) from Instances to Objects [🏷️ Deprecated]
  * Changed the capabilities of Function [CollectionService.GetCollection](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetCollection)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [CollectionService.GetInstanceAddedSignal](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetInstanceAddedSignal)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [CollectionService.GetInstanceRemovedSignal](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetInstanceRemovedSignal)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [CollectionService.GetTagged](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetTagged) from Instances to Objects [⚡ThreadSafety: Safe]
  * Changed the capabilities of Function [CollectionService.GetTagged](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetTagged)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [CollectionService.GetTags](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetTags)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [CollectionService.HasTag](https://create.roblox.com/docs/reference/engine/classes/CollectionService#HasTag)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [CollectionService.RemoveTag](https://create.roblox.com/docs/reference/engine/classes/CollectionService#RemoveTag) from null to void
  * Changed the capabilities of Function [CollectionService.RemoveTag](https://create.roblox.com/docs/reference/engine/classes/CollectionService#RemoveTag)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [CollectionService.ItemAdded](https://create.roblox.com/docs/reference/engine/classes/CollectionService#ItemAdded)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [CollectionService.ItemRemoved](https://create.roblox.com/docs/reference/engine/classes/CollectionService#ItemRemoved)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Function CollectionService.GetAllTags
  * Removed Function CollectionService.GetTagAddedSignal
  * Removed Function CollectionService.GetTagRemovedSignal
  * Removed Event CollectionService.TagAdded
  * Removed Event CollectionService.TagRemoved
* Added Class [CommandInstance](https://create.roblox.com/docs/reference/engine/classes/CommandInstance) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [CommandInstance.AllowGUIAccessPoints](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#AllowGUIAccessPoints) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CommandInstance.Checked](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Checked) [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CommandInstance.DefaultShortcut](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#DefaultShortcut) [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CommandInstance.Enabled](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Enabled) [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CommandInstance.Icon](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Icon) [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CommandInstance.Name](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Name) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CommandInstance.Permission](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Permission) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CommandInstance.StatusTip](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#StatusTip) [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CommandInstance.Text](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#Text) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [CommandInstance.RegisterExecutionCallback](https://create.roblox.com/docs/reference/engine/classes/CommandInstance#RegisterExecutionCallback)
* Added Class [CommandService](https://create.roblox.com/docs/reference/engine/classes/CommandService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [CommandService.Execute](https://create.roblox.com/docs/reference/engine/classes/CommandService#Execute) [🏷️ Yields]
  * Added Function [CommandService.RegisterCommand](https://create.roblox.com/docs/reference/engine/classes/CommandService#RegisterCommand) [🏷️ Yields]
  * Added Event [CommandService.CommandExecuting](https://create.roblox.com/docs/reference/engine/classes/CommandService#CommandExecuting)
* Update Class [Constraint](https://create.roblox.com/docs/reference/engine/classes/Constraint) [⬆️Extends: Instance] [🧠Memory: PhysicsParts] [🏷️ NotCreatable]
  * Changed MemoryCategory of Class [Constraint](https://create.roblox.com/docs/reference/engine/classes/Constraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [Constraint.Active](https://create.roblox.com/docs/reference/engine/classes/Constraint#Active)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Constraint.Attachment0](https://create.roblox.com/docs/reference/engine/classes/Constraint#Attachment0)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Constraint.Attachment1](https://create.roblox.com/docs/reference/engine/classes/Constraint#Attachment1)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Constraint.Color](https://create.roblox.com/docs/reference/engine/classes/Constraint#Color)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Constraint.Enabled](https://create.roblox.com/docs/reference/engine/classes/Constraint#Enabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Constraint.Visible](https://create.roblox.com/docs/reference/engine/classes/Constraint#Visible)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Removed Function Constraint.GetDebugAppliedForce
  * Removed Function Constraint.GetDebugAppliedTorque
* Update Class [AlignOrientation](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [AlignOrientation](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [AlignOrientation.AlignType](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation#AlignType)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignOrientation.MaxAngularVelocity](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation#MaxAngularVelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignOrientation.MaxTorque](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation#MaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignOrientation.PrimaryAxisOnly](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation#PrimaryAxisOnly)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignOrientation.ReactionTorqueEnabled](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation#ReactionTorqueEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignOrientation.Responsiveness](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation#Responsiveness)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignOrientation.RigidityEnabled](https://create.roblox.com/docs/reference/engine/classes/AlignOrientation#RigidityEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Removed Property AlignOrientation.CFrame
  * Removed Property AlignOrientation.LookAtPosition
  * Removed Property AlignOrientation.Mode
  * Removed Property AlignOrientation.PrimaryAxis
  * Removed Property AlignOrientation.SecondaryAxis
* Update Class [AlignPosition](https://create.roblox.com/docs/reference/engine/classes/AlignPosition) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [AlignPosition](https://create.roblox.com/docs/reference/engine/classes/AlignPosition) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [AlignPosition.ApplyAtCenterOfMass](https://create.roblox.com/docs/reference/engine/classes/AlignPosition#ApplyAtCenterOfMass)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignPosition.MaxForce](https://create.roblox.com/docs/reference/engine/classes/AlignPosition#MaxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignPosition.MaxVelocity](https://create.roblox.com/docs/reference/engine/classes/AlignPosition#MaxVelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignPosition.ReactionForceEnabled](https://create.roblox.com/docs/reference/engine/classes/AlignPosition#ReactionForceEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignPosition.Responsiveness](https://create.roblox.com/docs/reference/engine/classes/AlignPosition#Responsiveness)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AlignPosition.RigidityEnabled](https://create.roblox.com/docs/reference/engine/classes/AlignPosition#RigidityEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Removed Property AlignPosition.ForceLimitMode
  * Removed Property AlignPosition.ForceRelativeTo
  * Removed Property AlignPosition.MaxAxesForce
  * Removed Property AlignPosition.Mode
  * Removed Property AlignPosition.Position
* Update Class [AngularVelocity](https://create.roblox.com/docs/reference/engine/classes/AngularVelocity) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [AngularVelocity](https://create.roblox.com/docs/reference/engine/classes/AngularVelocity) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [AngularVelocity.AngularVelocity](https://create.roblox.com/docs/reference/engine/classes/AngularVelocity#AngularVelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AngularVelocity.MaxTorque](https://create.roblox.com/docs/reference/engine/classes/AngularVelocity#MaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AngularVelocity.ReactionTorqueEnabled](https://create.roblox.com/docs/reference/engine/classes/AngularVelocity#ReactionTorqueEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [AngularVelocity.RelativeTo](https://create.roblox.com/docs/reference/engine/classes/AngularVelocity#RelativeTo)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [BallSocketConstraint](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [BallSocketConstraint](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [BallSocketConstraint.LimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint#LimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BallSocketConstraint.MaxFrictionTorque](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint#MaxFrictionTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BallSocketConstraint.Radius](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint#Radius)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BallSocketConstraint.Restitution](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint#Restitution)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BallSocketConstraint.TwistLimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint#TwistLimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BallSocketConstraint.TwistLowerAngle](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint#TwistLowerAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BallSocketConstraint.TwistUpperAngle](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint#TwistUpperAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [BallSocketConstraint.UpperAngle](https://create.roblox.com/docs/reference/engine/classes/BallSocketConstraint#UpperAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Removed Property BallSocketConstraint.EnableSkinning
* Update Class [HingeConstraint](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [HingeConstraint](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [HingeConstraint.ActuatorType](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#ActuatorType)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.AngularResponsiveness](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#AngularResponsiveness)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.AngularSpeed](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#AngularSpeed)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.AngularVelocity](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#AngularVelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.CurrentAngle](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#CurrentAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.LimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#LimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.LowerAngle](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#LowerAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.MotorMaxAcceleration](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#MotorMaxAcceleration)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.MotorMaxTorque](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#MotorMaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.Radius](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#Radius)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.Restitution](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#Restitution)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.ServoMaxTorque](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#ServoMaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.TargetAngle](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#TargetAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [HingeConstraint.UpperAngle](https://create.roblox.com/docs/reference/engine/classes/HingeConstraint#UpperAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Removed Property HingeConstraint.SoftlockServoUponReachingTarget
* Update Class [LineForce](https://create.roblox.com/docs/reference/engine/classes/LineForce) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [LineForce](https://create.roblox.com/docs/reference/engine/classes/LineForce) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [LineForce.ApplyAtCenterOfMass](https://create.roblox.com/docs/reference/engine/classes/LineForce#ApplyAtCenterOfMass)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [LineForce.InverseSquareLaw](https://create.roblox.com/docs/reference/engine/classes/LineForce#InverseSquareLaw)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [LineForce.Magnitude](https://create.roblox.com/docs/reference/engine/classes/LineForce#Magnitude)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [LineForce.MaxForce](https://create.roblox.com/docs/reference/engine/classes/LineForce#MaxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [LineForce.ReactionForceEnabled](https://create.roblox.com/docs/reference/engine/classes/LineForce#ReactionForceEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
* Added Class [LinearVelocityConstraint](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint) {🔒None} [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Added Property [LinearVelocityConstraint.LineDirection](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#LineDirection) [⚡ThreadSafety: ReadSafe]
  * Added Property [LinearVelocityConstraint.LineVelocity](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#LineVelocity) [⚡ThreadSafety: ReadSafe]
  * Added Property [LinearVelocityConstraint.MaxForce](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#MaxForce) [⚡ThreadSafety: ReadSafe]
  * Added Property [LinearVelocityConstraint.PlaneVelocity](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#PlaneVelocity) [⚡ThreadSafety: ReadSafe]
  * Added Property [LinearVelocityConstraint.PrimaryTangentAxis](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#PrimaryTangentAxis) [⚡ThreadSafety: ReadSafe]
  * Added Property [LinearVelocityConstraint.RelativeTo](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#RelativeTo) [⚡ThreadSafety: ReadSafe]
  * Added Property [LinearVelocityConstraint.SecondaryTangentAxis](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#SecondaryTangentAxis) [⚡ThreadSafety: ReadSafe]
  * Added Property [LinearVelocityConstraint.VectorVelocity](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#VectorVelocity) [⚡ThreadSafety: ReadSafe]
  * Added Property [LinearVelocityConstraint.VelocityConstraintMode](https://create.roblox.com/docs/reference/engine/classes/LinearVelocityConstraint#VelocityConstraintMode) [⚡ThreadSafety: ReadSafe]
* Update Class [RodConstraint](https://create.roblox.com/docs/reference/engine/classes/RodConstraint) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [RodConstraint](https://create.roblox.com/docs/reference/engine/classes/RodConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [RodConstraint.CurrentDistance](https://create.roblox.com/docs/reference/engine/classes/RodConstraint#CurrentDistance)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RodConstraint.Length](https://create.roblox.com/docs/reference/engine/classes/RodConstraint#Length)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RodConstraint.LimitAngle0](https://create.roblox.com/docs/reference/engine/classes/RodConstraint#LimitAngle0)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RodConstraint.LimitAngle1](https://create.roblox.com/docs/reference/engine/classes/RodConstraint#LimitAngle1)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RodConstraint.LimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/RodConstraint#LimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RodConstraint.Thickness](https://create.roblox.com/docs/reference/engine/classes/RodConstraint#Thickness)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [RopeConstraint](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [RopeConstraint](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [RopeConstraint.CurrentDistance](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#CurrentDistance)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RopeConstraint.Length](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#Length)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RopeConstraint.Restitution](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#Restitution)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RopeConstraint.Thickness](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#Thickness)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RopeConstraint.WinchEnabled](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#WinchEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RopeConstraint.WinchForce](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#WinchForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RopeConstraint.WinchResponsiveness](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#WinchResponsiveness)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RopeConstraint.WinchSpeed](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#WinchSpeed)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [RopeConstraint.WinchTarget](https://create.roblox.com/docs/reference/engine/classes/RopeConstraint#WinchTarget)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [SlidingBallConstraint](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts] [🏷️ NotCreatable]
  * Changed MemoryCategory of Class [SlidingBallConstraint](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [SlidingBallConstraint.ActuatorType](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#ActuatorType)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.CurrentPosition](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#CurrentPosition)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.LimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#LimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.LinearResponsiveness](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#LinearResponsiveness)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.LowerLimit](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#LowerLimit)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.MotorMaxAcceleration](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#MotorMaxAcceleration)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.MotorMaxForce](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#MotorMaxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.Restitution](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#Restitution)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.ServoMaxForce](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#ServoMaxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.Size](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#Size)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.Speed](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#Speed)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.TargetPosition](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#TargetPosition)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.UpperLimit](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#UpperLimit)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SlidingBallConstraint.Velocity](https://create.roblox.com/docs/reference/engine/classes/SlidingBallConstraint#Velocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Removed Property SlidingBallConstraint.SoftlockServoUponReachingTarget
* Update Class [CylindricalConstraint](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint) [⬆️Extends: SlidingBallConstraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [CylindricalConstraint](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [CylindricalConstraint.AngularActuatorType](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#AngularActuatorType)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.AngularLimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#AngularLimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.AngularResponsiveness](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#AngularResponsiveness)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.AngularRestitution](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#AngularRestitution)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.AngularSpeed](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#AngularSpeed)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.AngularVelocity](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#AngularVelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.CurrentAngle](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#CurrentAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.InclinationAngle](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#InclinationAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.LowerAngle](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#LowerAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.MotorMaxAngularAcceleration](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#MotorMaxAngularAcceleration)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.MotorMaxTorque](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#MotorMaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.RotationAxisVisible](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#RotationAxisVisible)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.ServoMaxTorque](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#ServoMaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.TargetAngle](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#TargetAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.UpperAngle](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#UpperAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [CylindricalConstraint.WorldRotationAxis](https://create.roblox.com/docs/reference/engine/classes/CylindricalConstraint#WorldRotationAxis)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Removed Property CylindricalConstraint.SoftlockAngularServoUponReachingTarget
* Update Class [PrismaticConstraint](https://create.roblox.com/docs/reference/engine/classes/PrismaticConstraint) [⬆️Extends: SlidingBallConstraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [PrismaticConstraint](https://create.roblox.com/docs/reference/engine/classes/PrismaticConstraint) from `BaseParts` to `PhysicsParts`
* Update Class [SpringConstraint](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [SpringConstraint](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [SpringConstraint.Coils](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#Coils)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.CurrentLength](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#CurrentLength)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.Damping](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#Damping)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.FreeLength](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#FreeLength)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.LimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#LimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.MaxForce](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#MaxForce)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.MaxLength](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#MaxLength)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.MinLength](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#MinLength)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.Radius](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#Radius)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.Stiffness](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#Stiffness)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [SpringConstraint.Thickness](https://create.roblox.com/docs/reference/engine/classes/SpringConstraint#Thickness)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [Torque](https://create.roblox.com/docs/reference/engine/classes/Torque) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Torque](https://create.roblox.com/docs/reference/engine/classes/Torque) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [Torque.RelativeTo](https://create.roblox.com/docs/reference/engine/classes/Torque#RelativeTo)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Torque.Torque](https://create.roblox.com/docs/reference/engine/classes/Torque#Torque)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [TorsionSpringConstraint](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [TorsionSpringConstraint](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [TorsionSpringConstraint.Coils](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#Coils)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.CurrentAngle](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#CurrentAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.Damping](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#Damping)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.LimitEnabled](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#LimitEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.LimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#LimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.MaxAngle](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#MaxAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.MaxTorque](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#MaxTorque)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.Radius](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#Radius)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.Restitution](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#Restitution)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [TorsionSpringConstraint.Stiffness](https://create.roblox.com/docs/reference/engine/classes/TorsionSpringConstraint#Stiffness)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [UniversalConstraint](https://create.roblox.com/docs/reference/engine/classes/UniversalConstraint) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [UniversalConstraint](https://create.roblox.com/docs/reference/engine/classes/UniversalConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [UniversalConstraint.LimitsEnabled](https://create.roblox.com/docs/reference/engine/classes/UniversalConstraint#LimitsEnabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [UniversalConstraint.MaxAngle](https://create.roblox.com/docs/reference/engine/classes/UniversalConstraint#MaxAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [UniversalConstraint.Radius](https://create.roblox.com/docs/reference/engine/classes/UniversalConstraint#Radius)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [UniversalConstraint.Restitution](https://create.roblox.com/docs/reference/engine/classes/UniversalConstraint#Restitution)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [VectorForce](https://create.roblox.com/docs/reference/engine/classes/VectorForce) [⬆️Extends: Constraint] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [VectorForce](https://create.roblox.com/docs/reference/engine/classes/VectorForce) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [VectorForce.ApplyAtCenterOfMass](https://create.roblox.com/docs/reference/engine/classes/VectorForce#ApplyAtCenterOfMass)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [VectorForce.Force](https://create.roblox.com/docs/reference/engine/classes/VectorForce#Force)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [VectorForce.RelativeTo](https://create.roblox.com/docs/reference/engine/classes/VectorForce#RelativeTo)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [ContentProvider](https://create.roblox.com/docs/reference/engine/classes/ContentProvider) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [ContentProvider.BaseUrl](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#BaseUrl)
    from: {🚧Read: AssetManagement | Write: AssetManagement}
    to: {🚧None}
  * Changed the capabilities of Property [ContentProvider.RequestQueueSize](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RequestQueueSize)
    from: {🚧Read: AssetManagement | Write: AssetManagement}
    to: {🚧None}
  * Added Function [ContentProvider.CalculateNumTrianglesInMeshSync](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#CalculateNumTrianglesInMeshSync) (meshId: string) -> int
  * Changed the capabilities of Function [ContentProvider.GetFailedRequests](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#GetFailedRequests)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the capabilities of Function [ContentProvider.ListEncryptedAssets](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#ListEncryptedAssets)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the return-type of Function [ContentProvider.Preload](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#Preload) from null to void [🏷️ Deprecated]
  * Changed the parameters of Function [ContentProvider.Preload](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#Preload)
    from: (contentId: ContentId)
    to: (contentId: Content)
  * Changed the capabilities of Function [ContentProvider.Preload](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#Preload)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the return-type of Function [ContentProvider.RegisterDefaultEncryptionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterDefaultEncryptionKey) from null to void
  * Changed the capabilities of Function [ContentProvider.RegisterDefaultEncryptionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterDefaultEncryptionKey)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the return-type of Function [ContentProvider.RegisterDefaultSessionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterDefaultSessionKey) from null to void
  * Changed the capabilities of Function [ContentProvider.RegisterDefaultSessionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterDefaultSessionKey)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the return-type of Function [ContentProvider.RegisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterEncryptedAsset) from null to void
  * Changed the parameters of Function [ContentProvider.RegisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterEncryptedAsset)
    from: (assetId: ContentId, encryptionKey: string)
    to: (assetId: Content, encryptionKey: string)
  * Changed the capabilities of Function [ContentProvider.RegisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterEncryptedAsset)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the return-type of Function [ContentProvider.RegisterSessionEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterSessionEncryptedAsset) from null to void
  * Changed the parameters of Function [ContentProvider.RegisterSessionEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterSessionEncryptedAsset)
    from: (contentId: ContentId, sessionKey: string)
    to: (contentId: Content, sessionKey: string)
  * Changed the capabilities of Function [ContentProvider.RegisterSessionEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#RegisterSessionEncryptedAsset)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the return-type of Function [ContentProvider.SetBaseUrl](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#SetBaseUrl) from null to void
  * Changed the capabilities of Function [ContentProvider.SetBaseUrl](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#SetBaseUrl)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the return-type of Function [ContentProvider.UnregisterDefaultEncryptionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#UnregisterDefaultEncryptionKey) from null to void
  * Changed the capabilities of Function [ContentProvider.UnregisterDefaultEncryptionKey](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#UnregisterDefaultEncryptionKey)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the return-type of Function [ContentProvider.UnregisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#UnregisterEncryptedAsset) from null to void
  * Changed the parameters of Function [ContentProvider.UnregisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#UnregisterEncryptedAsset)
    from: (assetId: ContentId)
    to: (assetId: Content)
  * Changed the capabilities of Function [ContentProvider.UnregisterEncryptedAsset](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#UnregisterEncryptedAsset)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Added Function [ContentProvider.CalculateNumTrianglesInMesh](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#CalculateNumTrianglesInMesh) (meshId: string) -> int [🏷️ Yields]
  * Changed the return-type of Function [ContentProvider.PreloadAsync](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#PreloadAsync) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [ContentProvider.PreloadAsync](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#PreloadAsync)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Changed the parameters of Event [ContentProvider.AssetFetchFailed](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#AssetFetchFailed)
    from: (assetId: ContentId)
    to: (assetId: Content)
  * Changed the capabilities of Event [ContentProvider.AssetFetchFailed](https://create.roblox.com/docs/reference/engine/classes/ContentProvider#AssetFetchFailed)
    from: {🚧AssetManagement}
    to: {🚧None}
  * Removed Function ContentProvider.GetAssetFetchStatus
  * Removed Function ContentProvider.GetAssetFetchStatusChangedSignal
  * Removed Function ContentProvider.GetDependencyContentIds
  * Removed Function ContentProvider.GetDetailedFailedRequests
* Update Class [ContextActionService](https://create.roblox.com/docs/reference/engine/classes/ContextActionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [ContextActionService.BindAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindAction) from null to void
  * Changed the capabilities of Function [ContextActionService.BindAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindAction)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.BindActionAtPriority](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActionAtPriority) from null to void
  * Changed the capabilities of Function [ContextActionService.BindActionAtPriority](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActionAtPriority)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.BindActionToInputTypes](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActionToInputTypes) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [ContextActionService.BindActionToInputTypes](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActionToInputTypes)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.BindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActivate) from null to void
  * Changed the parameters of Function [ContextActionService.BindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActivate)
    from: (userInputTypeForActivation: UserInputType, keyCodesForActivation: Tuple)
    to: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = Unknown)
  * Changed the capabilities of Function [ContextActionService.BindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindActivate)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.BindCoreAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindCoreAction) from null to void
  * Changed the capabilities of Function [ContextActionService.BindCoreAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindCoreAction)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.BindCoreActionAtPriority](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindCoreActionAtPriority) from null to void
  * Changed the capabilities of Function [ContextActionService.BindCoreActionAtPriority](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BindCoreActionAtPriority)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [ContextActionService.CallFunction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#CallFunction)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.FireActionButtonFoundSignal](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#FireActionButtonFoundSignal) from null to void
  * Changed the capabilities of Function [ContextActionService.FireActionButtonFoundSignal](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#FireActionButtonFoundSignal)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [ContextActionService.GetAllBoundActionInfo](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#GetAllBoundActionInfo)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [ContextActionService.GetAllBoundCoreActionInfo](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#GetAllBoundCoreActionInfo)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [ContextActionService.GetBoundActionInfo](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#GetBoundActionInfo)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [ContextActionService.GetBoundCoreActionInfo](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#GetBoundCoreActionInfo)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [ContextActionService.GetCurrentLocalToolIcon](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#GetCurrentLocalToolIcon)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.SetDescription](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetDescription) from null to void
  * Changed the capabilities of Function [ContextActionService.SetDescription](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetDescription)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.SetImage](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetImage) from null to void
  * Changed the capabilities of Function [ContextActionService.SetImage](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetImage)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.SetPosition](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetPosition) from null to void
  * Changed the capabilities of Function [ContextActionService.SetPosition](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetPosition)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.SetTitle](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetTitle) from null to void
  * Changed the capabilities of Function [ContextActionService.SetTitle](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#SetTitle)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.UnbindAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindAction) from null to void
  * Changed the capabilities of Function [ContextActionService.UnbindAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindAction)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.UnbindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindActivate) from null to void
  * Changed the parameters of Function [ContextActionService.UnbindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindActivate)
    from: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = None)
    to: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = Unknown)
  * Changed the capabilities of Function [ContextActionService.UnbindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindActivate)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.UnbindAllActions](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindAllActions) from null to void
  * Changed the capabilities of Function [ContextActionService.UnbindAllActions](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindAllActions)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [ContextActionService.UnbindCoreAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindCoreAction) from null to void
  * Changed the capabilities of Function [ContextActionService.UnbindCoreAction](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindCoreAction)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [ContextActionService.GetButton](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#GetButton)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ContextActionService.BoundActionAdded](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BoundActionAdded)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ContextActionService.BoundActionChanged](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BoundActionChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ContextActionService.BoundActionRemoved](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#BoundActionRemoved)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ContextActionService.GetActionButtonEvent](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#GetActionButtonEvent)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ContextActionService.LocalToolEquipped](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#LocalToolEquipped)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ContextActionService.LocalToolUnequipped](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#LocalToolUnequipped)
    from: {🚧Input}
    to: {🚧None}
  * Removed Function ContextActionService.BindCoreActivate
  * Removed Function ContextActionService.GetInputContexts
  * Removed Function ContextActionService.GetInputSchemaKeyCodeTree
  * Removed Function ContextActionService.UnbindCoreActivate
  * Removed Event ContextActionService.InputContextsChanged
* Update Class [Controller](https://create.roblox.com/docs/reference/engine/classes/Controller) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [Controller.BindButton](https://create.roblox.com/docs/reference/engine/classes/Controller#BindButton) from null to void
  * Changed the return-type of Function [Controller.UnbindButton](https://create.roblox.com/docs/reference/engine/classes/Controller#UnbindButton) from null to void
  * Changed the return-type of Function [Controller.bindButton](https://create.roblox.com/docs/reference/engine/classes/Controller#bindButton) from null to void [🏷️ Deprecated]
* Update Class [SkateboardController](https://create.roblox.com/docs/reference/engine/classes/SkateboardController) [⬆️Extends: Controller] [🧠Memory: Instances]
  * Changed the capabilities of Property [SkateboardController.Steer](https://create.roblox.com/docs/reference/engine/classes/SkateboardController#Steer)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SkateboardController.Throttle](https://create.roblox.com/docs/reference/engine/classes/SkateboardController#Throttle)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Event [SkateboardController.AxisChanged](https://create.roblox.com/docs/reference/engine/classes/SkateboardController#AxisChanged)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [CustomEvent](https://create.roblox.com/docs/reference/engine/classes/CustomEvent) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed the return-type of Function [CustomEvent.GetAttachedReceivers](https://create.roblox.com/docs/reference/engine/classes/CustomEvent#GetAttachedReceivers) from Instances to Objects
  * Changed the return-type of Function [CustomEvent.SetValue](https://create.roblox.com/docs/reference/engine/classes/CustomEvent#SetValue) from null to void
* Update Class [BlockMesh](https://create.roblox.com/docs/reference/engine/classes/BlockMesh) [⬆️Extends: BevelMesh] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [BlockMesh](https://create.roblox.com/docs/reference/engine/classes/BlockMesh) from `BaseParts` to `PhysicsParts`
* Update Class [CylinderMesh](https://create.roblox.com/docs/reference/engine/classes/CylinderMesh) [⬆️Extends: BevelMesh] [🧠Memory: PhysicsParts] [🏷️ Deprecated]
  * Changed MemoryCategory of Class [CylinderMesh](https://create.roblox.com/docs/reference/engine/classes/CylinderMesh) from `BaseParts` to `PhysicsParts`
* Update Class [FileMesh](https://create.roblox.com/docs/reference/engine/classes/FileMesh) [⬆️Extends: DataModelMesh] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [FileMesh](https://create.roblox.com/docs/reference/engine/classes/FileMesh) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [FileMesh.MeshId](https://create.roblox.com/docs/reference/engine/classes/FileMesh#MeshId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [FileMesh.TextureId](https://create.roblox.com/docs/reference/engine/classes/FileMesh#TextureId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Removed Property FileMesh.MeshContent
  * Removed Property FileMesh.TextureContent
* Update Class [SpecialMesh](https://create.roblox.com/docs/reference/engine/classes/SpecialMesh) [⬆️Extends: FileMesh] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [SpecialMesh](https://create.roblox.com/docs/reference/engine/classes/SpecialMesh) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [SpecialMesh.MeshType](https://create.roblox.com/docs/reference/engine/classes/SpecialMesh#MeshType)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [DataModelSession](https://create.roblox.com/docs/reference/engine/classes/DataModelSession) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Event [DataModelSession.DataModelCreated](https://create.roblox.com/docs/reference/engine/classes/DataModelSession#DataModelCreated)
  * Added Event [DataModelSession.DataModelWillBeDestroyed](https://create.roblox.com/docs/reference/engine/classes/DataModelSession#DataModelWillBeDestroyed)
* Update Class [DataStoreIncrementOptions](https://create.roblox.com/docs/reference/engine/classes/DataStoreIncrementOptions) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Changed the capabilities of Function [DataStoreIncrementOptions.GetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreIncrementOptions#GetMetadata)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the return-type of Function [DataStoreIncrementOptions.SetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreIncrementOptions#SetMetadata) from null to void
  * Changed the capabilities of Function [DataStoreIncrementOptions.SetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreIncrementOptions#SetMetadata)
    from: {🚧DataStore}
    to: {🚧None}
* Update Class [DataStoreInfo](https://create.roblox.com/docs/reference/engine/classes/DataStoreInfo) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [DataStoreInfo.CreatedTime](https://create.roblox.com/docs/reference/engine/classes/DataStoreInfo#CreatedTime)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the capabilities of Property [DataStoreInfo.DataStoreName](https://create.roblox.com/docs/reference/engine/classes/DataStoreInfo#DataStoreName)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the capabilities of Property [DataStoreInfo.UpdatedTime](https://create.roblox.com/docs/reference/engine/classes/DataStoreInfo#UpdatedTime)
    from: {🚧Read: DataStore}
    to: {🚧None}
* Update Class [DataStoreKey](https://create.roblox.com/docs/reference/engine/classes/DataStoreKey) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [DataStoreKey.KeyName](https://create.roblox.com/docs/reference/engine/classes/DataStoreKey#KeyName)
    from: {🚧Read: DataStore}
    to: {🚧None}
* Update Class [DataStoreKeyInfo](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [DataStoreKeyInfo.CreatedTime](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#CreatedTime)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the capabilities of Property [DataStoreKeyInfo.UpdatedTime](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#UpdatedTime)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the capabilities of Property [DataStoreKeyInfo.Version](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#Version)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [DataStoreKeyInfo.GetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#GetMetadata)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [DataStoreKeyInfo.GetUserIds](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyInfo#GetUserIds)
    from: {🚧DataStore}
    to: {🚧None}
* Update Class [DataStoreObjectVersionInfo](https://create.roblox.com/docs/reference/engine/classes/DataStoreObjectVersionInfo) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [DataStoreObjectVersionInfo.CreatedTime](https://create.roblox.com/docs/reference/engine/classes/DataStoreObjectVersionInfo#CreatedTime)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the capabilities of Property [DataStoreObjectVersionInfo.IsDeleted](https://create.roblox.com/docs/reference/engine/classes/DataStoreObjectVersionInfo#IsDeleted)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the capabilities of Property [DataStoreObjectVersionInfo.Version](https://create.roblox.com/docs/reference/engine/classes/DataStoreObjectVersionInfo#Version)
    from: {🚧Read: DataStore}
    to: {🚧None}
* Update Class [DataStoreOptions](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Changed the capabilities of Property [DataStoreOptions.AllScopes](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions#AllScopes)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the return-type of Function [DataStoreOptions.SetExperimentalFeatures](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions#SetExperimentalFeatures) from null to void
  * Changed the capabilities of Function [DataStoreOptions.SetExperimentalFeatures](https://create.roblox.com/docs/reference/engine/classes/DataStoreOptions#SetExperimentalFeatures)
    from: {🚧DataStore}
    to: {🚧None}
* Update Class [DataStoreService](https://create.roblox.com/docs/reference/engine/classes/DataStoreService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [DataStoreService.AutomaticRetry](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#AutomaticRetry)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the capabilities of Property [DataStoreService.LegacyNamingScheme](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#LegacyNamingScheme)
    from: {🚧Read: DataStore}
    to: {🚧None}
  * Changed the return-type of Function [DataStoreService.GetDataStore](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#GetDataStore) from DataStore to GlobalDataStore
  * Changed the capabilities of Function [DataStoreService.GetDataStore](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#GetDataStore)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the return-type of Function [DataStoreService.GetGlobalDataStore](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#GetGlobalDataStore) from DataStore to GlobalDataStore
  * Changed the capabilities of Function [DataStoreService.GetGlobalDataStore](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#GetGlobalDataStore)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [DataStoreService.GetOrderedDataStore](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#GetOrderedDataStore)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [DataStoreService.GetRequestBudgetForRequestType](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#GetRequestBudgetForRequestType)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the parameters of Function [DataStoreService.ListDataStoresAsync](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#ListDataStoresAsync)
    from: (prefix: string = , pageSize: int = 0, cursor: string = )
    to: (prefix: string = , pageSize: int = 0)
  * Changed the capabilities of Function [DataStoreService.ListDataStoresAsync](https://create.roblox.com/docs/reference/engine/classes/DataStoreService#ListDataStoresAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Removed Function DataStoreService.SetRateLimitForRequestType
* Update Class [DataStoreSetOptions](https://create.roblox.com/docs/reference/engine/classes/DataStoreSetOptions) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Changed the capabilities of Function [DataStoreSetOptions.GetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreSetOptions#GetMetadata)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the return-type of Function [DataStoreSetOptions.SetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreSetOptions#SetMetadata) from null to void
  * Changed the capabilities of Function [DataStoreSetOptions.SetMetadata](https://create.roblox.com/docs/reference/engine/classes/DataStoreSetOptions#SetMetadata)
    from: {🚧DataStore}
    to: {🚧None}
* Update Class [Debris](https://create.roblox.com/docs/reference/engine/classes/Debris) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [Debris.MaxItems](https://create.roblox.com/docs/reference/engine/classes/Debris#MaxItems)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [Debris.AddItem](https://create.roblox.com/docs/reference/engine/classes/Debris#AddItem) from null to void
  * Changed the capabilities of Function [Debris.AddItem](https://create.roblox.com/docs/reference/engine/classes/Debris#AddItem)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Debris.SetLegacyMaxItems](https://create.roblox.com/docs/reference/engine/classes/Debris#SetLegacyMaxItems) from null to void
  * Changed the capabilities of Function [Debris.SetLegacyMaxItems](https://create.roblox.com/docs/reference/engine/classes/Debris#SetLegacyMaxItems)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Debris.addItem](https://create.roblox.com/docs/reference/engine/classes/Debris#addItem) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Debris.addItem](https://create.roblox.com/docs/reference/engine/classes/Debris#addItem)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [DebugSettings](https://create.roblox.com/docs/reference/engine/classes/DebugSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Settings] [🏷️ NotBrowsable]
  * Changed the security of Property [DebugSettings.DataModel](https://create.roblox.com/docs/reference/engine/classes/DebugSettings#DataModel)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [DebugSettings.InstanceCount](https://create.roblox.com/docs/reference/engine/classes/DebugSettings#InstanceCount)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [DebugSettings.IsScriptStackTracingEnabled](https://create.roblox.com/docs/reference/engine/classes/DebugSettings#IsScriptStackTracingEnabled)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [DebugSettings.JobCount](https://create.roblox.com/docs/reference/engine/classes/DebugSettings#JobCount)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [DebugSettings.PlayerCount](https://create.roblox.com/docs/reference/engine/classes/DebugSettings#PlayerCount)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [DebugSettings.ReportSoundWarnings](https://create.roblox.com/docs/reference/engine/classes/DebugSettings#ReportSoundWarnings)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [DebugSettings.RobloxVersion](https://create.roblox.com/docs/reference/engine/classes/DebugSettings#RobloxVersion)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [DebugSettings.TickCountPreciseOverride](https://create.roblox.com/docs/reference/engine/classes/DebugSettings#TickCountPreciseOverride)
    from: {🔒PluginSecurity}
    to: {🔒None}
* Update Class [DebuggerConnection](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [DebuggerConnection.AddBreakpoint](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#AddBreakpoint) from null to void
  * Changed the parameters of Function [DebuggerConnection.AddBreakpoint](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#AddBreakpoint)
    from: (script: string, line: int, breakpoint: Breakpoint)
    to: (script: Instance, line: int, breakpoint: Instance)
  * Changed the parameters of Function [DebuggerConnection.GetSource](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#GetSource)
    from: (scriptRef: string, status: Function)
    to: (scriptRef: Instance, status: Function)
  * Changed the parameters of Function [DebuggerConnection.Pause](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Pause)
    from: (thread: ThreadState, status: Function)
    to: (status: Function)
  * Changed the return-type of Function [DebuggerConnection.RemoveBreakpoint](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#RemoveBreakpoint) from null to void
  * Changed the parameters of Function [DebuggerConnection.RemoveBreakpoint](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#RemoveBreakpoint)
    from: (breakpoint: Breakpoint)
    to: (breakpoint: Instance)
  * Changed the parameters of Function [DebuggerConnection.Resume](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Resume)
    from: (thread: ThreadState, status: Function)
    to: (status: Function)
  * Added Function [DebuggerConnection.Terminate](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Terminate) (status: Function) -> int
  * Changed the parameters of Event [DebuggerConnection.BreakpointAdded](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#BreakpointAdded)
    from: (breakpoint: Breakpoint)
    to: (breakpoint: Instance)
  * Changed the parameters of Event [DebuggerConnection.BreakpointChanged](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#BreakpointChanged)
    from: (breakpoint: Breakpoint)
    to: (breakpoint: Instance)
  * Changed the parameters of Event [DebuggerConnection.BreakpointRemoved](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#BreakpointRemoved)
    from: (breakpoint: Breakpoint, reason: BreakpointRemoveReason)
    to: (breakpoint: Instance, reason: BreakpointRemoveReason)
  * Changed the parameters of Event [DebuggerConnection.Paused](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Paused)
    from: (pausedState: PausedState, reason: DebuggerPauseReason)
    to: (pausedState: Instance, reason: DebuggerPauseReason)
  * Changed the parameters of Event [DebuggerConnection.Resumed](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnection#Resumed)
    from: (pausedState: PausedState)
    to: (pausedState: Instance)
  * Removed Property DebuggerConnection.ErrorMessage
  * Removed Property DebuggerConnection.HasError
  * Removed Function DebuggerConnection.Close
  * Removed Function DebuggerConnection.EvaluateWatch
  * Removed Function DebuggerConnection.GetFrameById
  * Removed Function DebuggerConnection.GetThreadById
  * Removed Function DebuggerConnection.GetThreads
  * Removed Function DebuggerConnection.GetVariableById
  * Removed Function DebuggerConnection.Populate
  * Removed Function DebuggerConnection.SetExceptionBreakMode
  * Removed Function DebuggerConnection.SetVariable
  * Removed Function DebuggerConnection.Step
  * Removed Function DebuggerConnection.StepIn
  * Removed Function DebuggerConnection.StepOut
  * Removed Function DebuggerConnection.UpdateSelectedFrame
* Update Class [DebuggerConnectionManager](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [DebuggerConnectionManager.ConnectLocal](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#ConnectLocal)
    from: (dataModel: DataModel)
    to: (dataModel: Instance)
  * Added Function [DebuggerConnectionManager.ConnectRemote](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#ConnectRemote) (host: string, port: int) -> int
  * Changed the return-type of Function [DebuggerConnectionManager.FocusConnection](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#FocusConnection) from null to void
  * Changed the parameters of Function [DebuggerConnectionManager.FocusConnection](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#FocusConnection)
    from: (connection: DebuggerConnection)
    to: (connection: Instance)
  * Changed the parameters of Event [DebuggerConnectionManager.ConnectionEnded](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#ConnectionEnded)
    from: (connection: DebuggerConnection, reason: DebuggerEndReason)
    to: (connection: Instance, reason: DebuggerEndReason)
  * Changed the parameters of Event [DebuggerConnectionManager.ConnectionStarted](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#ConnectionStarted)
    from: (connection: DebuggerConnection)
    to: (connection: Instance)
  * Changed the parameters of Event [DebuggerConnectionManager.FocusChanged](https://create.roblox.com/docs/reference/engine/classes/DebuggerConnectionManager#FocusChanged)
    from: (connection: DebuggerConnection)
    to: (connection: Instance)
  * Removed Function DebuggerConnectionManager.GetAvailableConnection
  * Removed Function DebuggerConnectionManager.GetConnectionById
* Update Class [DebuggerManager](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [DebuggerManager.EnableDebugging](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#EnableDebugging) from null to void
  * Changed the return-type of Function [DebuggerManager.GetDebuggers](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#GetDebuggers) from Instances to Objects
  * Changed the return-type of Function [DebuggerManager.Resume](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#Resume) from null to void
  * Changed the return-type of Function [DebuggerManager.StepIn](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#StepIn) from null to void
  * Changed the return-type of Function [DebuggerManager.StepOut](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#StepOut) from null to void
  * Changed the return-type of Function [DebuggerManager.StepOver](https://create.roblox.com/docs/reference/engine/classes/DebuggerManager#StepOver) from null to void
* Update Class [Dialog](https://create.roblox.com/docs/reference/engine/classes/Dialog) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Dialog.BehaviorType](https://create.roblox.com/docs/reference/engine/classes/Dialog#BehaviorType)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.ConversationDistance](https://create.roblox.com/docs/reference/engine/classes/Dialog#ConversationDistance)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.GoodbyeChoiceActive](https://create.roblox.com/docs/reference/engine/classes/Dialog#GoodbyeChoiceActive)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.GoodbyeDialog](https://create.roblox.com/docs/reference/engine/classes/Dialog#GoodbyeDialog)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.InUse](https://create.roblox.com/docs/reference/engine/classes/Dialog#InUse)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.InitialPrompt](https://create.roblox.com/docs/reference/engine/classes/Dialog#InitialPrompt)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.Purpose](https://create.roblox.com/docs/reference/engine/classes/Dialog#Purpose)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.Tone](https://create.roblox.com/docs/reference/engine/classes/Dialog#Tone)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.TriggerDistance](https://create.roblox.com/docs/reference/engine/classes/Dialog#TriggerDistance)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [Dialog.TriggerOffset](https://create.roblox.com/docs/reference/engine/classes/Dialog#TriggerOffset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [Dialog.GetCurrentPlayers](https://create.roblox.com/docs/reference/engine/classes/Dialog#GetCurrentPlayers) from Instances to Objects
  * Changed the capabilities of Function [Dialog.GetCurrentPlayers](https://create.roblox.com/docs/reference/engine/classes/Dialog#GetCurrentPlayers)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [Dialog.SetPlayerIsUsing](https://create.roblox.com/docs/reference/engine/classes/Dialog#SetPlayerIsUsing) from null to void
  * Changed the capabilities of Function [Dialog.SetPlayerIsUsing](https://create.roblox.com/docs/reference/engine/classes/Dialog#SetPlayerIsUsing)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [Dialog.SignalDialogChoiceSelected](https://create.roblox.com/docs/reference/engine/classes/Dialog#SignalDialogChoiceSelected) from null to void
  * Changed the capabilities of Function [Dialog.SignalDialogChoiceSelected](https://create.roblox.com/docs/reference/engine/classes/Dialog#SignalDialogChoiceSelected)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [Dialog.DialogChoiceSelected](https://create.roblox.com/docs/reference/engine/classes/Dialog#DialogChoiceSelected)
    from: {🚧UI}
    to: {🚧None}
  * Removed Function Dialog.SetGuiObject
* Update Class [DialogChoice](https://create.roblox.com/docs/reference/engine/classes/DialogChoice) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [DialogChoice.GoodbyeChoiceActive](https://create.roblox.com/docs/reference/engine/classes/DialogChoice#GoodbyeChoiceActive)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [DialogChoice.GoodbyeDialog](https://create.roblox.com/docs/reference/engine/classes/DialogChoice#GoodbyeDialog)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [DialogChoice.ResponseDialog](https://create.roblox.com/docs/reference/engine/classes/DialogChoice#ResponseDialog)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [DialogChoice.UserDialog](https://create.roblox.com/docs/reference/engine/classes/DialogChoice#UserDialog)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [DraftsService](https://create.roblox.com/docs/reference/engine/classes/DraftsService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [DraftsService.DiscardEdits](https://create.roblox.com/docs/reference/engine/classes/DraftsService#DiscardEdits) from null to void
  * Changed the parameters of Function [DraftsService.DiscardEdits](https://create.roblox.com/docs/reference/engine/classes/DraftsService#DiscardEdits)
    from: (scripts: Instances)
    to: (scripts: Objects)
  * Changed the return-type of Function [DraftsService.GetEditors](https://create.roblox.com/docs/reference/engine/classes/DraftsService#GetEditors) from Instances to Objects
  * Changed the return-type of Function [DraftsService.RestoreScripts](https://create.roblox.com/docs/reference/engine/classes/DraftsService#RestoreScripts) from null to void
  * Changed the parameters of Function [DraftsService.RestoreScripts](https://create.roblox.com/docs/reference/engine/classes/DraftsService#RestoreScripts)
    from: (scripts: Instances)
    to: (scripts: Objects)
  * Changed the return-type of Function [DraftsService.ShowDiffsAgainstBase](https://create.roblox.com/docs/reference/engine/classes/DraftsService#ShowDiffsAgainstBase) from null to void
  * Changed the parameters of Function [DraftsService.ShowDiffsAgainstBase](https://create.roblox.com/docs/reference/engine/classes/DraftsService#ShowDiffsAgainstBase)
    from: (scripts: Instances)
    to: (scripts: Objects)
  * Changed the return-type of Function [DraftsService.ShowDiffsAgainstServer](https://create.roblox.com/docs/reference/engine/classes/DraftsService#ShowDiffsAgainstServer) from null to void
  * Changed the parameters of Function [DraftsService.ShowDiffsAgainstServer](https://create.roblox.com/docs/reference/engine/classes/DraftsService#ShowDiffsAgainstServer)
    from: (scripts: Instances)
    to: (scripts: Objects)
  * Changed the return-type of Function [DraftsService.CommitEdits](https://create.roblox.com/docs/reference/engine/classes/DraftsService#CommitEdits) from null to void [🏷️ Yields]
  * Changed the parameters of Function [DraftsService.CommitEdits](https://create.roblox.com/docs/reference/engine/classes/DraftsService#CommitEdits)
    from: (scripts: Instances)
    to: (scripts: Objects)
  * Changed the return-type of Function [DraftsService.GetDrafts](https://create.roblox.com/docs/reference/engine/classes/DraftsService#GetDrafts) from Instances to Objects [🏷️ Yields]
  * Changed the return-type of Function [DraftsService.UpdateToLatestVersion](https://create.roblox.com/docs/reference/engine/classes/DraftsService#UpdateToLatestVersion) from null to void [🏷️ Yields]
  * Changed the parameters of Function [DraftsService.UpdateToLatestVersion](https://create.roblox.com/docs/reference/engine/classes/DraftsService#UpdateToLatestVersion)
    from: (scripts: Instances)
    to: (scripts: Objects)
  * Removed Function DraftsService.ShowSourceDiffsAgainstCurrent
* Update Class [Dragger](https://create.roblox.com/docs/reference/engine/classes/Dragger) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the return-type of Function [Dragger.AxisRotate](https://create.roblox.com/docs/reference/engine/classes/Dragger#AxisRotate) from null to void
  * Changed the capabilities of Function [Dragger.AxisRotate](https://create.roblox.com/docs/reference/engine/classes/Dragger#AxisRotate)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [Dragger.MouseDown](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseDown) from null to void
  * Changed the parameters of Function [Dragger.MouseDown](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseDown)
    from: (mousePart: Instance, pointOnMousePart: Vector3, parts: Instances)
    to: (mousePart: Instance, pointOnMousePart: Vector3, parts: Objects)
  * Changed the capabilities of Function [Dragger.MouseDown](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseDown)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [Dragger.MouseMove](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseMove) from null to void
  * Changed the capabilities of Function [Dragger.MouseMove](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseMove)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [Dragger.MouseUp](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseUp) from null to void
  * Changed the capabilities of Function [Dragger.MouseUp](https://create.roblox.com/docs/reference/engine/classes/Dragger#MouseUp)
    from: {🚧Physics}
    to: {🚧None}
* Update Class [DraggerService](https://create.roblox.com/docs/reference/engine/classes/DraggerService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property DraggerService.HoverLineThickness
  * Removed Property DraggerService.PartSnapEnabled
  * Removed Property DraggerService.UseBoundingBoxes
* Update Class [EventIngestService](https://create.roblox.com/docs/reference/engine/classes/EventIngestService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [EventIngestService.SendEventDeferred](https://create.roblox.com/docs/reference/engine/classes/EventIngestService#SendEventDeferred) from null to void
  * Changed the return-type of Function [EventIngestService.SendEventImmediately](https://create.roblox.com/docs/reference/engine/classes/EventIngestService#SendEventImmediately) from null to void
  * Changed the return-type of Function [EventIngestService.SetRBXEvent](https://create.roblox.com/docs/reference/engine/classes/EventIngestService#SetRBXEvent) from null to void
  * Changed the return-type of Function [EventIngestService.SetRBXEventStream](https://create.roblox.com/docs/reference/engine/classes/EventIngestService#SetRBXEventStream) from null to void
* Update Class [Explosion](https://create.roblox.com/docs/reference/engine/classes/Explosion) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Explosion.BlastPressure](https://create.roblox.com/docs/reference/engine/classes/Explosion#BlastPressure)
    from: {🚧Read: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Explosion.BlastRadius](https://create.roblox.com/docs/reference/engine/classes/Explosion#BlastRadius)
    from: {🚧Read: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Explosion.DestroyJointRadiusPercent](https://create.roblox.com/docs/reference/engine/classes/Explosion#DestroyJointRadiusPercent)
    from: {🚧Read: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Explosion.ExplosionType](https://create.roblox.com/docs/reference/engine/classes/Explosion#ExplosionType)
    from: {🚧Read: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Explosion.Position](https://create.roblox.com/docs/reference/engine/classes/Explosion#Position)
    from: {🚧Read: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Explosion.Visible](https://create.roblox.com/docs/reference/engine/classes/Explosion#Visible)
    from: {🚧Read: AvatarBehavior}
    to: {🚧None}
  * Changed the parameters of Event [Explosion.Hit](https://create.roblox.com/docs/reference/engine/classes/Explosion#Hit)
    from: (part: BasePart, distance: float)
    to: (part: Instance, distance: float)
  * Changed the capabilities of Event [Explosion.Hit](https://create.roblox.com/docs/reference/engine/classes/Explosion#Hit)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Removed Property Explosion.LocalTransparencyModifier
  * Removed Property Explosion.TimeScale
* Update Class [FaceControls](https://create.roblox.com/docs/reference/engine/classes/FaceControls) [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [FaceControls.ChinRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#ChinRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.ChinRaiserUpperLip](https://create.roblox.com/docs/reference/engine/classes/FaceControls#ChinRaiserUpperLip)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.Corrugator](https://create.roblox.com/docs/reference/engine/classes/FaceControls#Corrugator)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.EyesLookDown](https://create.roblox.com/docs/reference/engine/classes/FaceControls#EyesLookDown)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.EyesLookLeft](https://create.roblox.com/docs/reference/engine/classes/FaceControls#EyesLookLeft)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.EyesLookRight](https://create.roblox.com/docs/reference/engine/classes/FaceControls#EyesLookRight)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.EyesLookUp](https://create.roblox.com/docs/reference/engine/classes/FaceControls#EyesLookUp)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.FlatPucker](https://create.roblox.com/docs/reference/engine/classes/FaceControls#FlatPucker)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.Funneler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#Funneler)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.JawDrop](https://create.roblox.com/docs/reference/engine/classes/FaceControls#JawDrop)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.JawLeft](https://create.roblox.com/docs/reference/engine/classes/FaceControls#JawLeft)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.JawRight](https://create.roblox.com/docs/reference/engine/classes/FaceControls#JawRight)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftBrowLowerer](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftBrowLowerer)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftCheekPuff](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftCheekPuff)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftCheekRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftCheekRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftDimpler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftDimpler)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftEyeClosed](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftEyeClosed)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftEyeUpperLidRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftEyeUpperLidRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftInnerBrowRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftInnerBrowRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftLipCornerDown](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftLipCornerDown)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftLipCornerPuller](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftLipCornerPuller)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftLipStretcher](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftLipStretcher)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftLowerLipDepressor](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftLowerLipDepressor)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftNoseWrinkler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftNoseWrinkler)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftOuterBrowRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftOuterBrowRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LeftUpperLipRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftUpperLipRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LipPresser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LipPresser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LipsTogether](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LipsTogether)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.LowerLipSuck](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LowerLipSuck)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.MouthLeft](https://create.roblox.com/docs/reference/engine/classes/FaceControls#MouthLeft)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.MouthRight](https://create.roblox.com/docs/reference/engine/classes/FaceControls#MouthRight)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.Pucker](https://create.roblox.com/docs/reference/engine/classes/FaceControls#Pucker)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightBrowLowerer](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightBrowLowerer)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightCheekPuff](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightCheekPuff)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightCheekRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightCheekRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightDimpler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightDimpler)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightEyeClosed](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightEyeClosed)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightEyeUpperLidRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightEyeUpperLidRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightInnerBrowRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightInnerBrowRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightLipCornerDown](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightLipCornerDown)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightLipCornerPuller](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightLipCornerPuller)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightLipStretcher](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightLipStretcher)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightLowerLipDepressor](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightLowerLipDepressor)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightNoseWrinkler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightNoseWrinkler)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightOuterBrowRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightOuterBrowRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.RightUpperLipRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightUpperLipRaiser)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.TongueDown](https://create.roblox.com/docs/reference/engine/classes/FaceControls#TongueDown)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.TongueOut](https://create.roblox.com/docs/reference/engine/classes/FaceControls#TongueOut)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.TongueUp](https://create.roblox.com/docs/reference/engine/classes/FaceControls#TongueUp)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [FaceControls.UpperLipSuck](https://create.roblox.com/docs/reference/engine/classes/FaceControls#UpperLipSuck)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Removed Function FaceControls.HasOverrideFACSData
  * Removed Event FaceControls.InternalFacsOverrideChanged
* Update Class [FaceInstance](https://create.roblox.com/docs/reference/engine/classes/FaceInstance) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [FaceInstance.Face](https://create.roblox.com/docs/reference/engine/classes/FaceInstance#Face)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Changed the capabilities of Property [Decal.Color3](https://create.roblox.com/docs/reference/engine/classes/Decal#Color3)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Decal.LocalTransparencyModifier](https://create.roblox.com/docs/reference/engine/classes/Decal#LocalTransparencyModifier)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Decal.Shiny](https://create.roblox.com/docs/reference/engine/classes/Decal#Shiny)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Decal.Specular](https://create.roblox.com/docs/reference/engine/classes/Decal#Specular)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Decal.Texture](https://create.roblox.com/docs/reference/engine/classes/Decal#Texture)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Decal.Transparency](https://create.roblox.com/docs/reference/engine/classes/Decal#Transparency)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Decal.ZIndex](https://create.roblox.com/docs/reference/engine/classes/Decal#ZIndex)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Removed Property Decal.AutoLocalize
  * Removed Property Decal.ColorMap
  * Removed Property Decal.ColorMapContent
  * Removed Property Decal.MetalnessMap
  * Removed Property Decal.MetalnessMapContent
  * Removed Property Decal.NormalMap
  * Removed Property Decal.NormalMapContent
  * Removed Property Decal.Rotation
  * Removed Property Decal.RoughnessMap
  * Removed Property Decal.RoughnessMapContent
  * Removed Property Decal.TextureContent
  * Removed Property Decal.TexturePack
  * Removed Property Decal.TexturePackContent
  * Removed Property Decal.UVOffset
  * Removed Property Decal.UVScale
* Update Class [Texture](https://create.roblox.com/docs/reference/engine/classes/Texture) [⬆️Extends: Decal] [🧠Memory: GraphicsTexture]
  * Changed the capabilities of Property [Texture.OffsetStudsU](https://create.roblox.com/docs/reference/engine/classes/Texture#OffsetStudsU)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Texture.OffsetStudsV](https://create.roblox.com/docs/reference/engine/classes/Texture#OffsetStudsV)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Texture.StudsPerTileU](https://create.roblox.com/docs/reference/engine/classes/Texture#StudsPerTileU)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Texture.StudsPerTileV](https://create.roblox.com/docs/reference/engine/classes/Texture#StudsPerTileV)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [Feature](https://create.roblox.com/docs/reference/engine/classes/Feature) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [Feature.FaceId](https://create.roblox.com/docs/reference/engine/classes/Feature#FaceId)
    from: {🚧Read: Physics | Write: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Feature.InOut](https://create.roblox.com/docs/reference/engine/classes/Feature#InOut)
    from: {🚧Read: Physics | Write: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Feature.LeftRight](https://create.roblox.com/docs/reference/engine/classes/Feature#LeftRight)
    from: {🚧Read: Physics | Write: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Feature.TopBottom](https://create.roblox.com/docs/reference/engine/classes/Feature#TopBottom)
    from: {🚧Read: Physics | Write: Physics}
    to: {🚧None}
* Update Class [File](https://create.roblox.com/docs/reference/engine/classes/File) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [File.Size](https://create.roblox.com/docs/reference/engine/classes/File#Size)
    from: {🚧Read: AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [File.GetBinaryContents](https://create.roblox.com/docs/reference/engine/classes/File#GetBinaryContents)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the return-type of Function [File.GetTemporaryId](https://create.roblox.com/docs/reference/engine/classes/File#GetTemporaryId) from ContentId to Content
  * Changed the capabilities of Function [File.GetTemporaryId](https://create.roblox.com/docs/reference/engine/classes/File#GetTemporaryId)
    from: {🚧AssetRead}
    to: {🚧None}
* Update Class [Fire](https://create.roblox.com/docs/reference/engine/classes/Fire) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Fire.Color](https://create.roblox.com/docs/reference/engine/classes/Fire#Color)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Fire.Enabled](https://create.roblox.com/docs/reference/engine/classes/Fire#Enabled)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Fire.Heat](https://create.roblox.com/docs/reference/engine/classes/Fire#Heat)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Fire.SecondaryColor](https://create.roblox.com/docs/reference/engine/classes/Fire#SecondaryColor)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Fire.Size](https://create.roblox.com/docs/reference/engine/classes/Fire#Size)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Fire.size](https://create.roblox.com/docs/reference/engine/classes/Fire#size)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Removed Property Fire.LocalTransparencyModifier
  * Removed Property Fire.TimeScale
  * Removed Function Fire.FastForward
* Update Class [ForceField](https://create.roblox.com/docs/reference/engine/classes/ForceField) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [ForceField.Visible](https://create.roblox.com/docs/reference/engine/classes/ForceField#Visible)
    from: {🚧Read: AvatarBehavior}
    to: {🚧None}
* Update Class [FunctionalTest](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed the return-type of Function [FunctionalTest.Error](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Error) from null to void
  * Changed the return-type of Function [FunctionalTest.Failed](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Failed) from null to void
  * Changed the return-type of Function [FunctionalTest.Pass](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Pass) from null to void
  * Changed the return-type of Function [FunctionalTest.Passed](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Passed) from null to void
  * Changed the return-type of Function [FunctionalTest.Warn](https://create.roblox.com/docs/reference/engine/classes/FunctionalTest#Warn) from null to void
* Update Class [GamePassService](https://create.roblox.com/docs/reference/engine/classes/GamePassService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Function [GamePassService.PlayerHasPass](https://create.roblox.com/docs/reference/engine/classes/GamePassService#PlayerHasPass)
    from: {🚧Monetization}
    to: {🚧None}
* Update Class [GameSettings](https://create.roblox.com/docs/reference/engine/classes/GameSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Settings] [🏷️ NotBrowsable]
  * Added Property [GameSettings.AdditionalCoreIncludeDirs](https://create.roblox.com/docs/reference/engine/classes/GameSettings#AdditionalCoreIncludeDirs): string [⚡ThreadSafety: ReadSafe]
  * Added Property [GameSettings.OverrideStarterScript](https://create.roblox.com/docs/reference/engine/classes/GameSettings#OverrideStarterScript): string [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [GameSettings.VideoCaptureEnabled](https://create.roblox.com/docs/reference/engine/classes/GameSettings#VideoCaptureEnabled)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [GameSettings.VideoRecording](https://create.roblox.com/docs/reference/engine/classes/GameSettings#VideoRecording): bool [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [GamepadService](https://create.roblox.com/docs/reference/engine/classes/GamepadService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [GamepadService.GamepadCursorEnabled](https://create.roblox.com/docs/reference/engine/classes/GamepadService#GamepadCursorEnabled)
    from: {🔒Read:None, Write:RobloxScriptSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the capabilities of Property [GamepadService.GamepadCursorEnabled](https://create.roblox.com/docs/reference/engine/classes/GamepadService#GamepadCursorEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the serialization of Property [GamepadService.GamepadCursorEnabled](https://create.roblox.com/docs/reference/engine/classes/GamepadService#GamepadCursorEnabled)
    from: [💾|📁Serialized]
    to: [🚫None]
  * Changed the capabilities of Function [GamepadService.GetGamepadCursorPosition](https://create.roblox.com/docs/reference/engine/classes/GamepadService#GetGamepadCursorPosition)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [GamepadService.SetGamepadCursorPosition](https://create.roblox.com/docs/reference/engine/classes/GamepadService#SetGamepadCursorPosition) from null to void
  * Changed the capabilities of Function [GamepadService.SetGamepadCursorPosition](https://create.roblox.com/docs/reference/engine/classes/GamepadService#SetGamepadCursorPosition)
    from: {🚧Input}
    to: {🚧None}
  * Removed Function GamepadService.AutoSelectGui
  * Removed Function GamepadService.DisableGamepadCursor
  * Removed Function GamepadService.EnableGamepadCursor
  * Removed Event GamepadService.GamepadThumbstick1Changed
* Update Class [GlobalDataStore](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Function [GlobalDataStore.OnUpdate](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#OnUpdate)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the parameters of Function [GlobalDataStore.GetAsync](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#GetAsync)
    from: (key: string, options: DataStoreGetOptions = nil)
    to: (key: string)
  * Changed the capabilities of Function [GlobalDataStore.GetAsync](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#GetAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [GlobalDataStore.IncrementAsync](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#IncrementAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [GlobalDataStore.RemoveAsync](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#RemoveAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [GlobalDataStore.SetAsync](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#SetAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [GlobalDataStore.UpdateAsync](https://create.roblox.com/docs/reference/engine/classes/GlobalDataStore#UpdateAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Removed Function GlobalDataStore.BatchGetAsync
* Update Class [DataStore](https://create.roblox.com/docs/reference/engine/classes/DataStore) [⬆️Extends: GlobalDataStore] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Function [DataStore.GetVersionAsync](https://create.roblox.com/docs/reference/engine/classes/DataStore#GetVersionAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the parameters of Function [DataStore.ListKeysAsync](https://create.roblox.com/docs/reference/engine/classes/DataStore#ListKeysAsync)
    from: (prefix: string = , pageSize: int = 0, cursor: string = , excludeDeleted: bool = false)
    to: (prefix: string = , pageSize: int = 0)
  * Changed the capabilities of Function [DataStore.ListKeysAsync](https://create.roblox.com/docs/reference/engine/classes/DataStore#ListKeysAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [DataStore.ListVersionsAsync](https://create.roblox.com/docs/reference/engine/classes/DataStore#ListVersionsAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the return-type of Function [DataStore.RemoveVersionAsync](https://create.roblox.com/docs/reference/engine/classes/DataStore#RemoveVersionAsync) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [DataStore.RemoveVersionAsync](https://create.roblox.com/docs/reference/engine/classes/DataStore#RemoveVersionAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Removed Function DataStore.GetVersionAtTimeAsync
* Update Class [OrderedDataStore](https://create.roblox.com/docs/reference/engine/classes/OrderedDataStore) [⬆️Extends: GlobalDataStore] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [OrderedDataStore.GetSortedAsync](https://create.roblox.com/docs/reference/engine/classes/OrderedDataStore#GetSortedAsync) from DataStorePages to Instance [🏷️ Yields]
  * Changed the capabilities of Function [OrderedDataStore.GetSortedAsync](https://create.roblox.com/docs/reference/engine/classes/OrderedDataStore#GetSortedAsync)
    from: {🚧DataStore}
    to: {🚧None}
* Added Class [GoogleAnalyticsConfiguration](https://create.roblox.com/docs/reference/engine/classes/GoogleAnalyticsConfiguration) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
* Update Class [GroupService](https://create.roblox.com/docs/reference/engine/classes/GroupService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Function [GroupService.GetAlliesAsync](https://create.roblox.com/docs/reference/engine/classes/GroupService#GetAlliesAsync)
    from: {🚧Groups}
    to: {🚧None}
  * Changed the capabilities of Function [GroupService.GetEnemiesAsync](https://create.roblox.com/docs/reference/engine/classes/GroupService#GetEnemiesAsync)
    from: {🚧Groups}
    to: {🚧None}
  * Changed the capabilities of Function [GroupService.GetGroupInfoAsync](https://create.roblox.com/docs/reference/engine/classes/GroupService#GetGroupInfoAsync)
    from: {🚧Groups}
    to: {🚧None}
  * Changed the parameters of Function [GroupService.GetGroupsAsync](https://create.roblox.com/docs/reference/engine/classes/GroupService#GetGroupsAsync)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [GroupService.GetGroupsAsync](https://create.roblox.com/docs/reference/engine/classes/GroupService#GetGroupsAsync)
    from: {🚧Groups}
    to: {🚧None}
  * Removed Function GroupService.PromptJoinCompleted
  * Removed Function GroupService.GetRolesInGroupAsync
  * Removed Function GroupService.PromptJoinAsync
  * Removed Event GroupService.ShowJoinPrompt
* Update Class [GuiBase2d](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d) [⬆️Extends: GuiBase] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [GuiBase2d.AbsolutePosition](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#AbsolutePosition)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.AbsoluteRotation](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#AbsoluteRotation)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.AbsoluteSize](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#AbsoluteSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.AutoLocalize](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#AutoLocalize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.ClippedRect](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#ClippedRect)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.IsNotOccluded](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#IsNotOccluded)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.Localize](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#Localize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.RawRect2D](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#RawRect2D)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.RootLocalizationTable](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#RootLocalizationTable)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase2d.TotalGroupScale](https://create.roblox.com/docs/reference/engine/classes/GuiBase2d#TotalGroupScale)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property GuiBase2d.SelectionBehaviorDown
  * Removed Property GuiBase2d.SelectionBehaviorLeft
  * Removed Property GuiBase2d.SelectionBehaviorRight
  * Removed Property GuiBase2d.SelectionBehaviorUp
  * Removed Property GuiBase2d.SelectionGroup
  * Removed Event GuiBase2d.SelectionChanged
* Update Class [GuiObject](https://create.roblox.com/docs/reference/engine/classes/GuiObject) [⬆️Extends: GuiBase2d] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [GuiObject.Active](https://create.roblox.com/docs/reference/engine/classes/GuiObject#Active)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.AnchorPoint](https://create.roblox.com/docs/reference/engine/classes/GuiObject#AnchorPoint)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.AutomaticSize](https://create.roblox.com/docs/reference/engine/classes/GuiObject#AutomaticSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.BackgroundColor](https://create.roblox.com/docs/reference/engine/classes/GuiObject#BackgroundColor)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.BackgroundColor3](https://create.roblox.com/docs/reference/engine/classes/GuiObject#BackgroundColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.BackgroundTransparency](https://create.roblox.com/docs/reference/engine/classes/GuiObject#BackgroundTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.BorderColor](https://create.roblox.com/docs/reference/engine/classes/GuiObject#BorderColor)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.BorderColor3](https://create.roblox.com/docs/reference/engine/classes/GuiObject#BorderColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.BorderMode](https://create.roblox.com/docs/reference/engine/classes/GuiObject#BorderMode)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.BorderSizePixel](https://create.roblox.com/docs/reference/engine/classes/GuiObject#BorderSizePixel)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.ClipsDescendants](https://create.roblox.com/docs/reference/engine/classes/GuiObject#ClipsDescendants)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.Draggable](https://create.roblox.com/docs/reference/engine/classes/GuiObject#Draggable)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.LayoutOrder](https://create.roblox.com/docs/reference/engine/classes/GuiObject#LayoutOrder)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.NextSelectionDown](https://create.roblox.com/docs/reference/engine/classes/GuiObject#NextSelectionDown)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.NextSelectionLeft](https://create.roblox.com/docs/reference/engine/classes/GuiObject#NextSelectionLeft)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.NextSelectionRight](https://create.roblox.com/docs/reference/engine/classes/GuiObject#NextSelectionRight)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.NextSelectionUp](https://create.roblox.com/docs/reference/engine/classes/GuiObject#NextSelectionUp)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.Position](https://create.roblox.com/docs/reference/engine/classes/GuiObject#Position)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.Rotation](https://create.roblox.com/docs/reference/engine/classes/GuiObject#Rotation)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.Selectable](https://create.roblox.com/docs/reference/engine/classes/GuiObject#Selectable)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.SelectionImageObject](https://create.roblox.com/docs/reference/engine/classes/GuiObject#SelectionImageObject)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.Size](https://create.roblox.com/docs/reference/engine/classes/GuiObject#Size)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.SizeConstraint](https://create.roblox.com/docs/reference/engine/classes/GuiObject#SizeConstraint)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.Transparency](https://create.roblox.com/docs/reference/engine/classes/GuiObject#Transparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.Visible](https://create.roblox.com/docs/reference/engine/classes/GuiObject#Visible)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiObject.ZIndex](https://create.roblox.com/docs/reference/engine/classes/GuiObject#ZIndex)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiObject.TweenPosition](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TweenPosition)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiObject.TweenSize](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TweenSize)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiObject.TweenSizeAndPosition](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TweenSizeAndPosition)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.DragBegin](https://create.roblox.com/docs/reference/engine/classes/GuiObject#DragBegin)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.DragStopped](https://create.roblox.com/docs/reference/engine/classes/GuiObject#DragStopped)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.InputBegan](https://create.roblox.com/docs/reference/engine/classes/GuiObject#InputBegan)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.InputChanged](https://create.roblox.com/docs/reference/engine/classes/GuiObject#InputChanged)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.InputEnded](https://create.roblox.com/docs/reference/engine/classes/GuiObject#InputEnded)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.MouseEnter](https://create.roblox.com/docs/reference/engine/classes/GuiObject#MouseEnter)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.MouseLeave](https://create.roblox.com/docs/reference/engine/classes/GuiObject#MouseLeave)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.MouseMoved](https://create.roblox.com/docs/reference/engine/classes/GuiObject#MouseMoved)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.MouseWheelBackward](https://create.roblox.com/docs/reference/engine/classes/GuiObject#MouseWheelBackward)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.MouseWheelForward](https://create.roblox.com/docs/reference/engine/classes/GuiObject#MouseWheelForward)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.SelectionGained](https://create.roblox.com/docs/reference/engine/classes/GuiObject#SelectionGained)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.SelectionLost](https://create.roblox.com/docs/reference/engine/classes/GuiObject#SelectionLost)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.TouchLongPress](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TouchLongPress)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.TouchPan](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TouchPan)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.TouchPinch](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TouchPinch)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.TouchRotate](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TouchRotate)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.TouchSwipe](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TouchSwipe)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiObject.TouchTap](https://create.roblox.com/docs/reference/engine/classes/GuiObject#TouchTap)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property GuiObject.GuiState
  * Removed Property GuiObject.InputSink
  * Removed Property GuiObject.Interactable
  * Removed Property GuiObject.SelectionOrder
  * Removed Property GuiObject.SelectionRect2D
  * Removed Function GuiObject.TweenPositionInternal
  * Removed Function GuiObject.TweenSizeAndPositionInternal
  * Removed Function GuiObject.TweenSizeInternal
* Update Class [Frame](https://create.roblox.com/docs/reference/engine/classes/Frame) [⬆️Extends: GuiObject] [🧠Memory: Gui]
  * Changed the capabilities of Property [Frame.Style](https://create.roblox.com/docs/reference/engine/classes/Frame#Style)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [GuiButton](https://create.roblox.com/docs/reference/engine/classes/GuiButton) [⬆️Extends: GuiObject] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [GuiButton.AutoButtonColor](https://create.roblox.com/docs/reference/engine/classes/GuiButton#AutoButtonColor)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiButton.Modal](https://create.roblox.com/docs/reference/engine/classes/GuiButton#Modal)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiButton.Selected](https://create.roblox.com/docs/reference/engine/classes/GuiButton#Selected)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiButton.Style](https://create.roblox.com/docs/reference/engine/classes/GuiButton#Style)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiButton.Activated](https://create.roblox.com/docs/reference/engine/classes/GuiButton#Activated)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiButton.MouseButton1Click](https://create.roblox.com/docs/reference/engine/classes/GuiButton#MouseButton1Click)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiButton.MouseButton1Down](https://create.roblox.com/docs/reference/engine/classes/GuiButton#MouseButton1Down)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiButton.MouseButton1Up](https://create.roblox.com/docs/reference/engine/classes/GuiButton#MouseButton1Up)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiButton.MouseButton2Click](https://create.roblox.com/docs/reference/engine/classes/GuiButton#MouseButton2Click)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiButton.MouseButton2Down](https://create.roblox.com/docs/reference/engine/classes/GuiButton#MouseButton2Down)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiButton.MouseButton2Up](https://create.roblox.com/docs/reference/engine/classes/GuiButton#MouseButton2Up)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property GuiButton.HoverHapticEffect
  * Removed Property GuiButton.PressHapticEffect
  * Removed Event GuiButton.SecondaryActivated
* Update Class [ImageButton](https://create.roblox.com/docs/reference/engine/classes/ImageButton) [⬆️Extends: GuiButton] [🧠Memory: Gui]
  * Changed the capabilities of Property [ImageButton.HoverImage](https://create.roblox.com/docs/reference/engine/classes/ImageButton#HoverImage)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.Image](https://create.roblox.com/docs/reference/engine/classes/ImageButton#Image)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.ImageColor3](https://create.roblox.com/docs/reference/engine/classes/ImageButton#ImageColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.ImageRectOffset](https://create.roblox.com/docs/reference/engine/classes/ImageButton#ImageRectOffset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.ImageRectSize](https://create.roblox.com/docs/reference/engine/classes/ImageButton#ImageRectSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.ImageTransparency](https://create.roblox.com/docs/reference/engine/classes/ImageButton#ImageTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.IsLoaded](https://create.roblox.com/docs/reference/engine/classes/ImageButton#IsLoaded)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.PressedImage](https://create.roblox.com/docs/reference/engine/classes/ImageButton#PressedImage)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.ResampleMode](https://create.roblox.com/docs/reference/engine/classes/ImageButton#ResampleMode)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.ScaleType](https://create.roblox.com/docs/reference/engine/classes/ImageButton#ScaleType)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.SliceCenter](https://create.roblox.com/docs/reference/engine/classes/ImageButton#SliceCenter)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.SliceScale](https://create.roblox.com/docs/reference/engine/classes/ImageButton#SliceScale)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageButton.TileSize](https://create.roblox.com/docs/reference/engine/classes/ImageButton#TileSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property ImageButton.ContentImageSize
  * Removed Property ImageButton.HoverImageContent
  * Removed Property ImageButton.ImageContent
  * Removed Property ImageButton.PressedImageContent
  * Removed Function ImageButton.SetEnableContentImageSizeChangedEvents
* Update Class [TextButton](https://create.roblox.com/docs/reference/engine/classes/TextButton) [⬆️Extends: GuiButton] [🧠Memory: Gui]
  * Changed the capabilities of Property [TextButton.Font](https://create.roblox.com/docs/reference/engine/classes/TextButton#Font)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the serialization of Property [TextButton.Font](https://create.roblox.com/docs/reference/engine/classes/TextButton#Font)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [TextButton.FontSize](https://create.roblox.com/docs/reference/engine/classes/TextButton#FontSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.LineHeight](https://create.roblox.com/docs/reference/engine/classes/TextButton#LineHeight)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.LocalizedText](https://create.roblox.com/docs/reference/engine/classes/TextButton#LocalizedText)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.MaxVisibleGraphemes](https://create.roblox.com/docs/reference/engine/classes/TextButton#MaxVisibleGraphemes)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.RichText](https://create.roblox.com/docs/reference/engine/classes/TextButton#RichText)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.Text](https://create.roblox.com/docs/reference/engine/classes/TextButton#Text)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextBounds](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextBounds)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextColor](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextColor)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextColor3](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextFits](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextFits)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextScaled](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextScaled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextSize](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextStrokeColor3](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextStrokeColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextStrokeTransparency](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextStrokeTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextTransparency](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextTruncate](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextTruncate)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextWrap](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextWrap)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextWrapped](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextWrapped)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextXAlignment](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextXAlignment)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextButton.TextYAlignment](https://create.roblox.com/docs/reference/engine/classes/TextButton#TextYAlignment)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [TextButton.SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextButton#SetTextFromInput) from null to void
  * Changed the capabilities of Function [TextButton.SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextButton#SetTextFromInput)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property TextButton.ContentText
  * Removed Property TextButton.FontFace
  * Removed Property TextButton.LocalizationMatchIdentifier
  * Removed Property TextButton.LocalizationMatchedSourceText
  * Removed Property TextButton.OpenTypeFeatures
  * Removed Property TextButton.OpenTypeFeaturesError
  * Removed Property TextButton.TextDirection
* Update Class [ImageLabel](https://create.roblox.com/docs/reference/engine/classes/ImageLabel) [⬆️Extends: GuiLabel] [🧠Memory: Gui]
  * Changed the capabilities of Property [ImageLabel.Image](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#Image)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.ImageColor3](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#ImageColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.ImageRectOffset](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#ImageRectOffset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.ImageRectSize](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#ImageRectSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.ImageTransparency](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#ImageTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.IsLoaded](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#IsLoaded)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.ResampleMode](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#ResampleMode)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.ScaleType](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#ScaleType)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.SliceCenter](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#SliceCenter)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.SliceScale](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#SliceScale)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ImageLabel.TileSize](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#TileSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property ImageLabel.ContentImageSize
  * Removed Property ImageLabel.ImageContent
  * Removed Function ImageLabel.SetEnableContentImageSizeChangedEvents
* Update Class [TextLabel](https://create.roblox.com/docs/reference/engine/classes/TextLabel) [⬆️Extends: GuiLabel] [🧠Memory: Gui]
  * Changed the capabilities of Property [TextLabel.Font](https://create.roblox.com/docs/reference/engine/classes/TextLabel#Font)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the serialization of Property [TextLabel.Font](https://create.roblox.com/docs/reference/engine/classes/TextLabel#Font)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [TextLabel.FontSize](https://create.roblox.com/docs/reference/engine/classes/TextLabel#FontSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.LineHeight](https://create.roblox.com/docs/reference/engine/classes/TextLabel#LineHeight)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.LocalizedText](https://create.roblox.com/docs/reference/engine/classes/TextLabel#LocalizedText)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.MaxVisibleGraphemes](https://create.roblox.com/docs/reference/engine/classes/TextLabel#MaxVisibleGraphemes)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.RichText](https://create.roblox.com/docs/reference/engine/classes/TextLabel#RichText)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.Text](https://create.roblox.com/docs/reference/engine/classes/TextLabel#Text)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextBounds](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextBounds)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextColor](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextColor)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextColor3](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextFits](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextFits)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextScaled](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextScaled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextSize](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextStrokeColor3](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextStrokeColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextStrokeTransparency](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextStrokeTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextTransparency](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextTruncate](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextTruncate)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextWrap](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextWrap)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextWrapped](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextWrapped)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextXAlignment](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextXAlignment)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextLabel.TextYAlignment](https://create.roblox.com/docs/reference/engine/classes/TextLabel#TextYAlignment)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [TextLabel.SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextLabel#SetTextFromInput) from null to void
  * Changed the capabilities of Function [TextLabel.SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextLabel#SetTextFromInput)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property TextLabel.ContentText
  * Removed Property TextLabel.FontFace
  * Removed Property TextLabel.LocalizationMatchIdentifier
  * Removed Property TextLabel.LocalizationMatchedSourceText
  * Removed Property TextLabel.OpenTypeFeatures
  * Removed Property TextLabel.OpenTypeFeaturesError
  * Removed Property TextLabel.TextDirection
* Update Class [ScrollingFrame](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame) [⬆️Extends: GuiObject] [🧠Memory: Gui]
  * Changed ThreadSafety of Property [ScrollingFrame.AbsoluteCanvasSize](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#AbsoluteCanvasSize) from `Unsafe` to `ReadSafe`
  * Changed the security of Property [ScrollingFrame.AbsoluteCanvasSize](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#AbsoluteCanvasSize)
    from: {🔒None}
    to: {🔒RobloxScriptSecurity}
  * Changed the capabilities of Property [ScrollingFrame.AbsoluteCanvasSize](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#AbsoluteCanvasSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the serialization of Property [ScrollingFrame.AbsoluteCanvasSize](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#AbsoluteCanvasSize)
    from: [💾SaveOnly]
    to: [🚫None]
  * Changed the capabilities of Property [ScrollingFrame.AbsoluteWindowSize](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#AbsoluteWindowSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.AutomaticCanvasSize](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#AutomaticCanvasSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.BottomImage](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#BottomImage)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.CanvasPosition](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#CanvasPosition)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.CanvasSize](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#CanvasSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.ElasticBehavior](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ElasticBehavior)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.HorizontalBarRect](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#HorizontalBarRect)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.HorizontalScrollBarInset](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#HorizontalScrollBarInset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.MaxCanvasPosition](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#MaxCanvasPosition)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.MidImage](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#MidImage)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.ScrollBarImageColor3](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ScrollBarImageColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.ScrollBarImageTransparency](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ScrollBarImageTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.ScrollBarThickness](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ScrollBarThickness)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.ScrollingDirection](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ScrollingDirection)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.ScrollingEnabled](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ScrollingEnabled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.TopImage](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#TopImage)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.VerticalBarRect](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#VerticalBarRect)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.VerticalScrollBarInset](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#VerticalScrollBarInset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScrollingFrame.VerticalScrollBarPosition](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#VerticalScrollBarPosition)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [ScrollingFrame.ClearInertialScrolling](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ClearInertialScrolling) from null to void
  * Changed the capabilities of Function [ScrollingFrame.ClearInertialScrolling](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ClearInertialScrolling)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [ScrollingFrame.GetSampledInertialVelocity](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#GetSampledInertialVelocity)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [ScrollingFrame.ScrollToTop](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ScrollToTop) from null to void
  * Changed the capabilities of Function [ScrollingFrame.ScrollToTop](https://create.roblox.com/docs/reference/engine/classes/ScrollingFrame#ScrollToTop)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property ScrollingFrame.BottomImageContent
  * Removed Property ScrollingFrame.DraggingScrollBar
  * Removed Property ScrollingFrame.MidImageContent
  * Removed Property ScrollingFrame.ScrollRate
  * Removed Property ScrollingFrame.ScrollVelocity
  * Removed Property ScrollingFrame.SmoothScroll
  * Removed Property ScrollingFrame.TopImageContent
  * Removed Function ScrollingFrame.GetScrollVelocity
  * Removed Function ScrollingFrame.ResetScrollVelocity
* Update Class [TextBox](https://create.roblox.com/docs/reference/engine/classes/TextBox) [⬆️Extends: GuiObject] [🧠Memory: Gui]
  * Changed the capabilities of Property [TextBox.ClearTextOnFocus](https://create.roblox.com/docs/reference/engine/classes/TextBox#ClearTextOnFocus)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.CursorPosition](https://create.roblox.com/docs/reference/engine/classes/TextBox#CursorPosition)
    from: {🚧Read: UI}
    to: {🚧None}
  * Added Property [TextBox.EnableRealtimeFilteringHints](https://create.roblox.com/docs/reference/engine/classes/TextBox#EnableRealtimeFilteringHints): bool [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [TextBox.Font](https://create.roblox.com/docs/reference/engine/classes/TextBox#Font)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the serialization of Property [TextBox.Font](https://create.roblox.com/docs/reference/engine/classes/TextBox#Font)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [TextBox.FontSize](https://create.roblox.com/docs/reference/engine/classes/TextBox#FontSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.LineHeight](https://create.roblox.com/docs/reference/engine/classes/TextBox#LineHeight)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.ManualFocusRelease](https://create.roblox.com/docs/reference/engine/classes/TextBox#ManualFocusRelease)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.MaxVisibleGraphemes](https://create.roblox.com/docs/reference/engine/classes/TextBox#MaxVisibleGraphemes)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.MultiLine](https://create.roblox.com/docs/reference/engine/classes/TextBox#MultiLine)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.OverlayNativeInput](https://create.roblox.com/docs/reference/engine/classes/TextBox#OverlayNativeInput)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.PlaceholderColor3](https://create.roblox.com/docs/reference/engine/classes/TextBox#PlaceholderColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.PlaceholderText](https://create.roblox.com/docs/reference/engine/classes/TextBox#PlaceholderText)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.ReturnKeyType](https://create.roblox.com/docs/reference/engine/classes/TextBox#ReturnKeyType)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.RichText](https://create.roblox.com/docs/reference/engine/classes/TextBox#RichText)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.SelectionStart](https://create.roblox.com/docs/reference/engine/classes/TextBox#SelectionStart)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.ShowNativeInput](https://create.roblox.com/docs/reference/engine/classes/TextBox#ShowNativeInput)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.Text](https://create.roblox.com/docs/reference/engine/classes/TextBox#Text)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextBounds](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextBounds)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextColor](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextColor)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextColor3](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextEditable](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextEditable)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextFits](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextFits)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextInputType](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextInputType)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextScaled](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextScaled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextSize](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextStrokeColor3](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextStrokeColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextStrokeTransparency](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextStrokeTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextTransparency](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextTruncate](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextTruncate)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextWrap](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextWrap)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextWrapped](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextWrapped)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextXAlignment](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextXAlignment)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [TextBox.TextYAlignment](https://create.roblox.com/docs/reference/engine/classes/TextBox#TextYAlignment)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [TextBox.CaptureFocus](https://create.roblox.com/docs/reference/engine/classes/TextBox#CaptureFocus) from null to void
  * Changed the capabilities of Function [TextBox.CaptureFocus](https://create.roblox.com/docs/reference/engine/classes/TextBox#CaptureFocus)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [TextBox.IsFocused](https://create.roblox.com/docs/reference/engine/classes/TextBox#IsFocused)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [TextBox.ReleaseFocus](https://create.roblox.com/docs/reference/engine/classes/TextBox#ReleaseFocus) from null to void
  * Changed the capabilities of Function [TextBox.ReleaseFocus](https://create.roblox.com/docs/reference/engine/classes/TextBox#ReleaseFocus)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [TextBox.ResetKeyboardMode](https://create.roblox.com/docs/reference/engine/classes/TextBox#ResetKeyboardMode) from null to void
  * Changed the capabilities of Function [TextBox.ResetKeyboardMode](https://create.roblox.com/docs/reference/engine/classes/TextBox#ResetKeyboardMode)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [TextBox.SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextBox#SetTextFromInput) from null to void
  * Changed the capabilities of Function [TextBox.SetTextFromInput](https://create.roblox.com/docs/reference/engine/classes/TextBox#SetTextFromInput)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [TextBox.FocusLost](https://create.roblox.com/docs/reference/engine/classes/TextBox#FocusLost)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [TextBox.Focused](https://create.roblox.com/docs/reference/engine/classes/TextBox#Focused)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [TextBox.ReturnPressedFromOnScreenKeyboard](https://create.roblox.com/docs/reference/engine/classes/TextBox#ReturnPressedFromOnScreenKeyboard)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property TextBox.ContentText
  * Removed Property TextBox.FontFace
  * Removed Property TextBox.LocalizationMatchIdentifier
  * Removed Property TextBox.LocalizationMatchedSourceText
  * Removed Property TextBox.OpenTypeFeatures
  * Removed Property TextBox.OpenTypeFeaturesError
  * Removed Property TextBox.ShouldEmitReturnEvents
  * Removed Property TextBox.ShouldEmitTabEvents
  * Removed Property TextBox.ShouldEmitUpAndDownArrowEvents
  * Removed Property TextBox.TextDirection
* Update Class [VideoFrame](https://create.roblox.com/docs/reference/engine/classes/VideoFrame) [⬆️Extends: GuiObject] [🧠Memory: Gui]
  * Changed the capabilities of Property [VideoFrame.IsLoaded](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#IsLoaded)
    from: {🚧Read: Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Property [VideoFrame.Looped](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Looped)
    from: {🚧Read: Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Property [VideoFrame.Playing](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Playing)
    from: {🚧Read: Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Property [VideoFrame.Resolution](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Resolution)
    from: {🚧Read: Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Property [VideoFrame.TimeLength](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#TimeLength)
    from: {🚧Read: Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Property [VideoFrame.TimePosition](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#TimePosition)
    from: {🚧Read: Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Property [VideoFrame.Video](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Video)
    from: {🚧Read: Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Property [VideoFrame.Volume](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Volume)
    from: {🚧Read: Audio, UI}
    to: {🚧None}
  * Changed the return-type of Function [VideoFrame.Pause](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Pause) from null to void
  * Changed the capabilities of Function [VideoFrame.Pause](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Pause)
    from: {🚧Audio, UI}
    to: {🚧None}
  * Changed the return-type of Function [VideoFrame.Play](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Play) from null to void
  * Changed the capabilities of Function [VideoFrame.Play](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Play)
    from: {🚧Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Event [VideoFrame.DidLoop](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#DidLoop)
    from: {🚧Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Event [VideoFrame.Ended](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Ended)
    from: {🚧Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Event [VideoFrame.Loaded](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Loaded)
    from: {🚧Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Event [VideoFrame.Paused](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Paused)
    from: {🚧Audio, UI}
    to: {🚧None}
  * Changed the capabilities of Event [VideoFrame.Played](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#Played)
    from: {🚧Audio, UI}
    to: {🚧None}
  * Removed Property VideoFrame.InternalVideoUsage
  * Removed Property VideoFrame.MaximumResolution
  * Removed Property VideoFrame.RollOffMaxDistance
  * Removed Property VideoFrame.RollOffMinDistance
  * Removed Property VideoFrame.RollOffMode
  * Removed Property VideoFrame.VideoContent
  * Removed Function VideoFrame.SetStudioPreview
* Update Class [ViewportFrame](https://create.roblox.com/docs/reference/engine/classes/ViewportFrame) [⬆️Extends: GuiObject] [🧠Memory: Gui]
  * Changed the capabilities of Property [ViewportFrame.Ambient](https://create.roblox.com/docs/reference/engine/classes/ViewportFrame#Ambient)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ViewportFrame.CurrentCamera](https://create.roblox.com/docs/reference/engine/classes/ViewportFrame#CurrentCamera)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ViewportFrame.ImageColor3](https://create.roblox.com/docs/reference/engine/classes/ViewportFrame#ImageColor3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ViewportFrame.ImageTransparency](https://create.roblox.com/docs/reference/engine/classes/ViewportFrame#ImageTransparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ViewportFrame.LightColor](https://create.roblox.com/docs/reference/engine/classes/ViewportFrame#LightColor)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ViewportFrame.LightDirection](https://create.roblox.com/docs/reference/engine/classes/ViewportFrame#LightDirection)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property ViewportFrame.IsMirrored
  * Removed Function ViewportFrame.CaptureSnapshotAsync
* Update Class [LayerCollector](https://create.roblox.com/docs/reference/engine/classes/LayerCollector) [⬆️Extends: GuiBase2d] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [LayerCollector.Enabled](https://create.roblox.com/docs/reference/engine/classes/LayerCollector#Enabled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [LayerCollector.ResetOnSpawn](https://create.roblox.com/docs/reference/engine/classes/LayerCollector#ResetOnSpawn)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [LayerCollector.ZIndexBehavior](https://create.roblox.com/docs/reference/engine/classes/LayerCollector#ZIndexBehavior)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Function [LayerCollector.GetLayoutNodeTree](https://create.roblox.com/docs/reference/engine/classes/LayerCollector#GetLayoutNodeTree)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property LayerCollector.TabKeyboardNavigation
  * Removed Function LayerCollector.GetGuiObjectsAtPosition
* Update Class [BillboardGui](https://create.roblox.com/docs/reference/engine/classes/BillboardGui) [⬆️Extends: LayerCollector] [🧠Memory: Instances]
  * Changed the capabilities of Property [BillboardGui.Active](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#Active)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.Adornee](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#Adornee)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.AlwaysOnTop](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#AlwaysOnTop)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.Brightness](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#Brightness)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.ClipsDescendants](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#ClipsDescendants)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.CurrentDistance](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#CurrentDistance)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.DistanceLowerLimit](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#DistanceLowerLimit)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.DistanceStep](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#DistanceStep)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the serialization of Property [BillboardGui.DistanceStep](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#DistanceStep)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [BillboardGui.DistanceUpperLimit](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#DistanceUpperLimit)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.ExtentsOffset](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#ExtentsOffset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.ExtentsOffsetWorldSpace](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#ExtentsOffsetWorldSpace)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.LightInfluence](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#LightInfluence)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.MaxDistance](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#MaxDistance)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.PlayerToHideFrom](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#PlayerToHideFrom)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.Size](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#Size)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.SizeOffset](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#SizeOffset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.StudsOffset](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#StudsOffset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [BillboardGui.StudsOffsetWorldSpace](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#StudsOffsetWorldSpace)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Function [BillboardGui.GetScreenSpaceBounds](https://create.roblox.com/docs/reference/engine/classes/BillboardGui#GetScreenSpaceBounds)
    from: {🚧UI}
    to: {🚧None}
* Update Class [PluginGui](https://create.roblox.com/docs/reference/engine/classes/PluginGui) [⬆️Extends: LayerCollector] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [PluginGui.Title](https://create.roblox.com/docs/reference/engine/classes/PluginGui#Title)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [PluginGui.BindToClose](https://create.roblox.com/docs/reference/engine/classes/PluginGui#BindToClose) from null to void
  * Changed the capabilities of Function [PluginGui.BindToClose](https://create.roblox.com/docs/reference/engine/classes/PluginGui#BindToClose)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [PluginGui.GetRelativeMousePosition](https://create.roblox.com/docs/reference/engine/classes/PluginGui#GetRelativeMousePosition)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [PluginGui.PluginDragDropped](https://create.roblox.com/docs/reference/engine/classes/PluginGui#PluginDragDropped)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [PluginGui.PluginDragEntered](https://create.roblox.com/docs/reference/engine/classes/PluginGui#PluginDragEntered)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [PluginGui.PluginDragLeft](https://create.roblox.com/docs/reference/engine/classes/PluginGui#PluginDragLeft)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [PluginGui.PluginDragMoved](https://create.roblox.com/docs/reference/engine/classes/PluginGui#PluginDragMoved)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [PluginGui.WindowFocusReleased](https://create.roblox.com/docs/reference/engine/classes/PluginGui#WindowFocusReleased)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [PluginGui.WindowFocused](https://create.roblox.com/docs/reference/engine/classes/PluginGui#WindowFocused)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property PluginGui.Plugin
  * Removed Function PluginGui.OverrideStudioAction
  * Removed Event PluginGui.InputBegan
  * Removed Event PluginGui.InputChanged
  * Removed Event PluginGui.InputEnded
  * Removed Event PluginGui.MouseEnter
  * Removed Event PluginGui.MouseLeave
  * Removed Event PluginGui.PointerAction
* Update Class [DockWidgetPluginGui](https://create.roblox.com/docs/reference/engine/classes/DockWidgetPluginGui) [⬆️Extends: PluginGui] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [DockWidgetPluginGui.HostWidgetWasRestored](https://create.roblox.com/docs/reference/engine/classes/DockWidgetPluginGui#HostWidgetWasRestored)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Function DockWidgetPluginGui.RequestRaise
* Update Class [ScreenGui](https://create.roblox.com/docs/reference/engine/classes/ScreenGui) [⬆️Extends: LayerCollector] [🧠Memory: Instances]
  * Changed the capabilities of Property [ScreenGui.DisplayOrder](https://create.roblox.com/docs/reference/engine/classes/ScreenGui#DisplayOrder)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ScreenGui.IgnoreGuiInset](https://create.roblox.com/docs/reference/engine/classes/ScreenGui#IgnoreGuiInset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the serialization of Property [ScreenGui.IgnoreGuiInset](https://create.roblox.com/docs/reference/engine/classes/ScreenGui#IgnoreGuiInset)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [ScreenGui.OnTopOfCoreBlur](https://create.roblox.com/docs/reference/engine/classes/ScreenGui#OnTopOfCoreBlur)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property ScreenGui.ClipToDeviceSafeArea
  * Removed Property ScreenGui.SafeAreaCompatibility
  * Removed Property ScreenGui.ScreenInsets
* Update Class [SurfaceGui](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui) [⬆️Extends: LayerCollector] [🧠Memory: Instances]
  * Changed Superclass of Class [SurfaceGui](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui) from `SurfaceGuiBase` to `LayerCollector`
  * Added Property [SurfaceGui.Active](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#Active): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [SurfaceGui.Adornee](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#Adornee): Instance [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [SurfaceGui.AlwaysOnTop](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#AlwaysOnTop)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceGui.Brightness](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#Brightness)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceGui.CanvasSize](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#CanvasSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceGui.ClipsDescendants](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#ClipsDescendants)
    from: {🚧Read: UI}
    to: {🚧None}
  * Added Property [SurfaceGui.Face](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#Face): NormalId [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [SurfaceGui.LightInfluence](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#LightInfluence)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceGui.PixelsPerStud](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#PixelsPerStud)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceGui.SizingMode](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#SizingMode)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceGui.ToolPunchThroughDistance](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#ToolPunchThroughDistance)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceGui.ZOffset](https://create.roblox.com/docs/reference/engine/classes/SurfaceGui#ZOffset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property SurfaceGui.HorizontalCurvature
  * Removed Property SurfaceGui.MaxDistance
  * Removed Property SurfaceGui.Shape
* Update Class [GuiBase3d](https://create.roblox.com/docs/reference/engine/classes/GuiBase3d) [⬆️Extends: GuiBase] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [GuiBase3d.Color](https://create.roblox.com/docs/reference/engine/classes/GuiBase3d#Color)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase3d.Color3](https://create.roblox.com/docs/reference/engine/classes/GuiBase3d#Color3)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase3d.Transparency](https://create.roblox.com/docs/reference/engine/classes/GuiBase3d#Transparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiBase3d.Visible](https://create.roblox.com/docs/reference/engine/classes/GuiBase3d#Visible)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [FloorWire](https://create.roblox.com/docs/reference/engine/classes/FloorWire) [⬆️Extends: GuiBase3d] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed the capabilities of Property [FloorWire.CycleOffset](https://create.roblox.com/docs/reference/engine/classes/FloorWire#CycleOffset)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [FloorWire.From](https://create.roblox.com/docs/reference/engine/classes/FloorWire#From)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [FloorWire.StudsBetweenTextures](https://create.roblox.com/docs/reference/engine/classes/FloorWire#StudsBetweenTextures)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [FloorWire.Texture](https://create.roblox.com/docs/reference/engine/classes/FloorWire#Texture)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [FloorWire.TextureSize](https://create.roblox.com/docs/reference/engine/classes/FloorWire#TextureSize)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [FloorWire.To](https://create.roblox.com/docs/reference/engine/classes/FloorWire#To)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [FloorWire.Velocity](https://create.roblox.com/docs/reference/engine/classes/FloorWire#Velocity)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [FloorWire.WireRadius](https://create.roblox.com/docs/reference/engine/classes/FloorWire#WireRadius)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
* Update Class [InstanceAdornment](https://create.roblox.com/docs/reference/engine/classes/InstanceAdornment) [⬆️Extends: GuiBase3d] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [InstanceAdornment.Adornee](https://create.roblox.com/docs/reference/engine/classes/InstanceAdornment#Adornee)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
* Update Class [SelectionBox](https://create.roblox.com/docs/reference/engine/classes/SelectionBox) [⬆️Extends: InstanceAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [SelectionBox.LineThickness](https://create.roblox.com/docs/reference/engine/classes/SelectionBox#LineThickness)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [SelectionBox.SurfaceColor](https://create.roblox.com/docs/reference/engine/classes/SelectionBox#SurfaceColor)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [SelectionBox.SurfaceColor3](https://create.roblox.com/docs/reference/engine/classes/SelectionBox#SurfaceColor3)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [SelectionBox.SurfaceTransparency](https://create.roblox.com/docs/reference/engine/classes/SelectionBox#SurfaceTransparency)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Removed Property SelectionBox.StudioSelectionBox
* Update Class [PVAdornment](https://create.roblox.com/docs/reference/engine/classes/PVAdornment) [⬆️Extends: GuiBase3d] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [PVAdornment.Adornee](https://create.roblox.com/docs/reference/engine/classes/PVAdornment#Adornee)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [HandleAdornment](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment) [⬆️Extends: PVAdornment] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [HandleAdornment.AdornCullingMode](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#AdornCullingMode)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [HandleAdornment.AlwaysOnTop](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#AlwaysOnTop)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [HandleAdornment.CFrame](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#CFrame)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [HandleAdornment.SizeRelativeOffset](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#SizeRelativeOffset)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [HandleAdornment.ZIndex](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#ZIndex)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Event [HandleAdornment.MouseButton1Down](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#MouseButton1Down)
    from: {🚧Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Event [HandleAdornment.MouseButton1Up](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#MouseButton1Up)
    from: {🚧Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Event [HandleAdornment.MouseEnter](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#MouseEnter)
    from: {🚧Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Event [HandleAdornment.MouseLeave](https://create.roblox.com/docs/reference/engine/classes/HandleAdornment#MouseLeave)
    from: {🚧Basic, UI}
    to: {🚧None}
  * Removed Property HandleAdornment.GizmoReference
* Update Class [BoxHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/BoxHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [BoxHandleAdornment.Size](https://create.roblox.com/docs/reference/engine/classes/BoxHandleAdornment#Size)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Removed Property BoxHandleAdornment.Shading
* Update Class [ConeHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/ConeHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [ConeHandleAdornment.Height](https://create.roblox.com/docs/reference/engine/classes/ConeHandleAdornment#Height)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [ConeHandleAdornment.Radius](https://create.roblox.com/docs/reference/engine/classes/ConeHandleAdornment#Radius)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Removed Property ConeHandleAdornment.Hollow
  * Removed Property ConeHandleAdornment.Shading
* Update Class [CylinderHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [CylinderHandleAdornment.Angle](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment#Angle)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [CylinderHandleAdornment.Height](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment#Height)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [CylinderHandleAdornment.InnerRadius](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment#InnerRadius)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [CylinderHandleAdornment.Radius](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment#Radius)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Removed Property CylinderHandleAdornment.Shading
* Update Class [ImageHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [ImageHandleAdornment.Image](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment#Image)
    from: {🚧Read: Basic, UI | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ImageHandleAdornment.Size](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment#Size)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Removed Property ImageHandleAdornment.ImageContent
* Update Class [LineHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/LineHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [LineHandleAdornment.Length](https://create.roblox.com/docs/reference/engine/classes/LineHandleAdornment#Length)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [LineHandleAdornment.Thickness](https://create.roblox.com/docs/reference/engine/classes/LineHandleAdornment#Thickness)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
* Update Class [SphereHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/SphereHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [SphereHandleAdornment.Radius](https://create.roblox.com/docs/reference/engine/classes/SphereHandleAdornment#Radius)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Removed Property SphereHandleAdornment.Shading
* Update Class [ParabolaAdornment](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment) [⬆️Extends: PVAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [ParabolaAdornment.A](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment#A)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ParabolaAdornment.B](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment#B)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ParabolaAdornment.C](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment#C)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ParabolaAdornment.Range](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment#Range)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [ParabolaAdornment.Thickness](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment#Thickness)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the parameters of Function [ParabolaAdornment.FindPartOnParabola](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment#FindPartOnParabola)
    from: (ignoreDescendentsTable: Instances)
    to: (ignoreDescendentsTable: Objects)
  * Changed the capabilities of Function [ParabolaAdornment.FindPartOnParabola](https://create.roblox.com/docs/reference/engine/classes/ParabolaAdornment#FindPartOnParabola)
    from: {🚧UI}
    to: {🚧None}
* Update Class [SelectionSphere](https://create.roblox.com/docs/reference/engine/classes/SelectionSphere) [⬆️Extends: PVAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [SelectionSphere.SurfaceColor](https://create.roblox.com/docs/reference/engine/classes/SelectionSphere#SurfaceColor)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [SelectionSphere.SurfaceColor3](https://create.roblox.com/docs/reference/engine/classes/SelectionSphere#SurfaceColor3)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
  * Changed the capabilities of Property [SelectionSphere.SurfaceTransparency](https://create.roblox.com/docs/reference/engine/classes/SelectionSphere#SurfaceTransparency)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
* Update Class [PartAdornment](https://create.roblox.com/docs/reference/engine/classes/PartAdornment) [⬆️Extends: GuiBase3d] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [PartAdornment.Adornee](https://create.roblox.com/docs/reference/engine/classes/PartAdornment#Adornee)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
* Update Class [ArcHandles](https://create.roblox.com/docs/reference/engine/classes/ArcHandles) [⬆️Extends: HandlesBase] [🧠Memory: Instances]
  * Changed the capabilities of Property [ArcHandles.Axes](https://create.roblox.com/docs/reference/engine/classes/ArcHandles#Axes)
    from: {🚧Read: Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ArcHandles.MouseButton1Down](https://create.roblox.com/docs/reference/engine/classes/ArcHandles#MouseButton1Down)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ArcHandles.MouseButton1Up](https://create.roblox.com/docs/reference/engine/classes/ArcHandles#MouseButton1Up)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ArcHandles.MouseDrag](https://create.roblox.com/docs/reference/engine/classes/ArcHandles#MouseDrag)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ArcHandles.MouseEnter](https://create.roblox.com/docs/reference/engine/classes/ArcHandles#MouseEnter)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ArcHandles.MouseLeave](https://create.roblox.com/docs/reference/engine/classes/ArcHandles#MouseLeave)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
* Update Class [Handles](https://create.roblox.com/docs/reference/engine/classes/Handles) [⬆️Extends: HandlesBase] [🧠Memory: Instances]
  * Changed the capabilities of Property [Handles.Faces](https://create.roblox.com/docs/reference/engine/classes/Handles#Faces)
    from: {🚧Read: Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [Handles.Style](https://create.roblox.com/docs/reference/engine/classes/Handles#Style)
    from: {🚧Read: Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [Handles.MouseButton1Down](https://create.roblox.com/docs/reference/engine/classes/Handles#MouseButton1Down)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [Handles.MouseButton1Up](https://create.roblox.com/docs/reference/engine/classes/Handles#MouseButton1Up)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [Handles.MouseDrag](https://create.roblox.com/docs/reference/engine/classes/Handles#MouseDrag)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [Handles.MouseEnter](https://create.roblox.com/docs/reference/engine/classes/Handles#MouseEnter)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [Handles.MouseLeave](https://create.roblox.com/docs/reference/engine/classes/Handles#MouseLeave)
    from: {🚧Basic, UI, Input}
    to: {🚧None}
* Update Class [SurfaceSelection](https://create.roblox.com/docs/reference/engine/classes/SurfaceSelection) [⬆️Extends: PartAdornment] [🧠Memory: Instances]
  * Changed the capabilities of Property [SurfaceSelection.TargetSurface](https://create.roblox.com/docs/reference/engine/classes/SurfaceSelection#TargetSurface)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
* Update Class [SelectionLasso](https://create.roblox.com/docs/reference/engine/classes/SelectionLasso) [⬆️Extends: GuiBase3d] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [SelectionLasso.Humanoid](https://create.roblox.com/docs/reference/engine/classes/SelectionLasso#Humanoid)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [SelectionPartLasso](https://create.roblox.com/docs/reference/engine/classes/SelectionPartLasso) [⬆️Extends: SelectionLasso] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed the capabilities of Property [SelectionPartLasso.Part](https://create.roblox.com/docs/reference/engine/classes/SelectionPartLasso#Part)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
* Update Class [SelectionPointLasso](https://create.roblox.com/docs/reference/engine/classes/SelectionPointLasso) [⬆️Extends: SelectionLasso] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed the capabilities of Property [SelectionPointLasso.Point](https://create.roblox.com/docs/reference/engine/classes/SelectionPointLasso#Point)
    from: {🚧Read: Basic, UI}
    to: {🚧None}
* Update Class [GuiService](https://create.roblox.com/docs/reference/engine/classes/GuiService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [GuiService.AutoSelectGuiEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#AutoSelectGuiEnabled)
    from: {🚧Read: UI, Input | Write: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.CoreEffectFolder](https://create.roblox.com/docs/reference/engine/classes/GuiService#CoreEffectFolder)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.CoreGuiFolder](https://create.roblox.com/docs/reference/engine/classes/GuiService#CoreGuiFolder)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.CoreGuiNavigationEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#CoreGuiNavigationEnabled)
    from: {🚧Read: UI, Input | Write: UI, Input}
    to: {🚧None}
  * Changed the serialization of Property [GuiService.CoreGuiNavigationEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#CoreGuiNavigationEnabled)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [GuiService.GuiNavigationEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#GuiNavigationEnabled)
    from: {🚧Read: UI, Input | Write: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.IsModalDialog](https://create.roblox.com/docs/reference/engine/classes/GuiService#IsModalDialog)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.IsWindows](https://create.roblox.com/docs/reference/engine/classes/GuiService#IsWindows)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.MenuIsOpen](https://create.roblox.com/docs/reference/engine/classes/GuiService#MenuIsOpen)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.SelectedCoreObject](https://create.roblox.com/docs/reference/engine/classes/GuiService#SelectedCoreObject)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.SelectedObject](https://create.roblox.com/docs/reference/engine/classes/GuiService#SelectedObject)
    from: {🚧Read: UI, Input | Write: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [GuiService.TouchControlsEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#TouchControlsEnabled)
    from: {🚧Read: UI, Input | Write: UI, Input}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.AddCenterDialog](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddCenterDialog) from null to void
  * Changed the capabilities of Function [GuiService.AddCenterDialog](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddCenterDialog)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.AddKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddKey) from null to void
  * Changed the capabilities of Function [GuiService.AddKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddKey)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.AddSelectionParent](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSelectionParent) from null to void
  * Changed the capabilities of Function [GuiService.AddSelectionParent](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSelectionParent)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.AddSelectionTuple](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSelectionTuple) from null to void
  * Changed the capabilities of Function [GuiService.AddSelectionTuple](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSelectionTuple)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.AddSpecialKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSpecialKey) from null to void
  * Changed the capabilities of Function [GuiService.AddSpecialKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#AddSpecialKey)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.BroadcastNotification](https://create.roblox.com/docs/reference/engine/classes/GuiService#BroadcastNotification) from null to void
  * Changed the capabilities of Function [GuiService.BroadcastNotification](https://create.roblox.com/docs/reference/engine/classes/GuiService#BroadcastNotification)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.ClearError](https://create.roblox.com/docs/reference/engine/classes/GuiService#ClearError) from null to void
  * Changed the capabilities of Function [GuiService.ClearError](https://create.roblox.com/docs/reference/engine/classes/GuiService#ClearError)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.CloseInspectMenu](https://create.roblox.com/docs/reference/engine/classes/GuiService#CloseInspectMenu) from null to void
  * Changed the capabilities of Function [GuiService.CloseInspectMenu](https://create.roblox.com/docs/reference/engine/classes/GuiService#CloseInspectMenu)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.CloseStatsBasedOnInputString](https://create.roblox.com/docs/reference/engine/classes/GuiService#CloseStatsBasedOnInputString)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.ForceTenFootInterface](https://create.roblox.com/docs/reference/engine/classes/GuiService#ForceTenFootInterface) from null to void
  * Changed the capabilities of Function [GuiService.ForceTenFootInterface](https://create.roblox.com/docs/reference/engine/classes/GuiService#ForceTenFootInterface)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetBrickCount](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetBrickCount)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetClosestDialogToPosition](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetClosestDialogToPosition)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetEmotesMenuOpen](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetEmotesMenuOpen)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetErrorCode](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetErrorCode)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetErrorMessage](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetErrorMessage)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetErrorType](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetErrorType)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetGameplayPausedNotificationEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetGameplayPausedNotificationEnabled)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetGuiInset](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetGuiInset)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetInspectMenuEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetInspectMenuEnabled)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetNotificationTypeList](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetNotificationTypeList)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetResolutionScale](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetResolutionScale)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetSafeZoneOffsets](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetSafeZoneOffsets)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetUiMessage](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetUiMessage)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.InspectPlayerFromHumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromHumanoidDescription) from null to void
  * Changed the capabilities of Function [GuiService.InspectPlayerFromHumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromHumanoidDescription)
    from: {🚧UI, AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.InspectPlayerFromUserId](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserId) from null to void
  * Changed the parameters of Function [GuiService.InspectPlayerFromUserId](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserId)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [GuiService.InspectPlayerFromUserId](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserId)
    from: {🚧UI, AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.InspectPlayerFromUserIdWithCtx](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserIdWithCtx) from null to void
  * Changed the parameters of Function [GuiService.InspectPlayerFromUserIdWithCtx](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserIdWithCtx)
    from: (userId: User, ctx: string)
    to: (userId: int64, ctx: string)
  * Changed the capabilities of Function [GuiService.InspectPlayerFromUserIdWithCtx](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserIdWithCtx)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.IsMemoryTrackerEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#IsMemoryTrackerEnabled)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.IsTenFootInterface](https://create.roblox.com/docs/reference/engine/classes/GuiService#IsTenFootInterface)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.OpenBrowserWindow](https://create.roblox.com/docs/reference/engine/classes/GuiService#OpenBrowserWindow) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [GuiService.OpenBrowserWindow](https://create.roblox.com/docs/reference/engine/classes/GuiService#OpenBrowserWindow)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.OpenNativeOverlay](https://create.roblox.com/docs/reference/engine/classes/GuiService#OpenNativeOverlay) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [GuiService.OpenNativeOverlay](https://create.roblox.com/docs/reference/engine/classes/GuiService#OpenNativeOverlay)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.RemoveCenterDialog](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveCenterDialog) from null to void
  * Changed the capabilities of Function [GuiService.RemoveCenterDialog](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveCenterDialog)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.RemoveKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveKey) from null to void
  * Changed the capabilities of Function [GuiService.RemoveKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveKey)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.RemoveSelectionGroup](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveSelectionGroup) from null to void
  * Changed the capabilities of Function [GuiService.RemoveSelectionGroup](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveSelectionGroup)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.RemoveSpecialKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveSpecialKey) from null to void
  * Changed the capabilities of Function [GuiService.RemoveSpecialKey](https://create.roblox.com/docs/reference/engine/classes/GuiService#RemoveSpecialKey)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.SetEmotesMenuOpen](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetEmotesMenuOpen) from null to void
  * Changed the capabilities of Function [GuiService.SetEmotesMenuOpen](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetEmotesMenuOpen)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.SetGameplayPausedNotificationEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetGameplayPausedNotificationEnabled) from null to void
  * Changed the capabilities of Function [GuiService.SetGameplayPausedNotificationEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetGameplayPausedNotificationEnabled)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.SetGlobalGuiInset](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetGlobalGuiInset) from null to void
  * Changed the capabilities of Function [GuiService.SetGlobalGuiInset](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetGlobalGuiInset)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.SetInspectMenuEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetInspectMenuEnabled) from null to void
  * Changed the capabilities of Function [GuiService.SetInspectMenuEnabled](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetInspectMenuEnabled)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.SetMenuIsOpen](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetMenuIsOpen) from null to void
  * Changed the capabilities of Function [GuiService.SetMenuIsOpen](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetMenuIsOpen)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.SetSafeZoneOffsets](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetSafeZoneOffsets) from null to void
  * Changed the capabilities of Function [GuiService.SetSafeZoneOffsets](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetSafeZoneOffsets)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.SetUiMessage](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetUiMessage) from null to void
  * Changed the capabilities of Function [GuiService.SetUiMessage](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetUiMessage)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.ShowStatsBasedOnInputString](https://create.roblox.com/docs/reference/engine/classes/GuiService#ShowStatsBasedOnInputString)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [GuiService.ToggleFullscreen](https://create.roblox.com/docs/reference/engine/classes/GuiService#ToggleFullscreen) from null to void
  * Changed the capabilities of Function [GuiService.ToggleFullscreen](https://create.roblox.com/docs/reference/engine/classes/GuiService#ToggleFullscreen)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [GuiService.GetScreenResolution](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetScreenResolution)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.BrowserWindowClosed](https://create.roblox.com/docs/reference/engine/classes/GuiService#BrowserWindowClosed)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.CloseInspectMenuRequest](https://create.roblox.com/docs/reference/engine/classes/GuiService#CloseInspectMenuRequest)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.CoreGuiRenderOverflowed](https://create.roblox.com/docs/reference/engine/classes/GuiService#CoreGuiRenderOverflowed)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.EmotesMenuOpenChanged](https://create.roblox.com/docs/reference/engine/classes/GuiService#EmotesMenuOpenChanged)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.ErrorMessageChanged](https://create.roblox.com/docs/reference/engine/classes/GuiService#ErrorMessageChanged)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.InspectMenuEnabledChangedSignal](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectMenuEnabledChangedSignal)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.InspectPlayerFromHumanoidDescriptionRequest](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromHumanoidDescriptionRequest)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.InspectPlayerFromUserIdWithCtxRequest](https://create.roblox.com/docs/reference/engine/classes/GuiService#InspectPlayerFromUserIdWithCtxRequest)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.KeyPressed](https://create.roblox.com/docs/reference/engine/classes/GuiService#KeyPressed)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.MenuClosed](https://create.roblox.com/docs/reference/engine/classes/GuiService#MenuClosed)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.MenuOpened](https://create.roblox.com/docs/reference/engine/classes/GuiService#MenuOpened)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.NativeClose](https://create.roblox.com/docs/reference/engine/classes/GuiService#NativeClose)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.NetworkPausedEnabledChanged](https://create.roblox.com/docs/reference/engine/classes/GuiService#NetworkPausedEnabledChanged)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.Open9SliceEditor](https://create.roblox.com/docs/reference/engine/classes/GuiService#Open9SliceEditor)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.SafeZoneOffsetsChanged](https://create.roblox.com/docs/reference/engine/classes/GuiService#SafeZoneOffsetsChanged)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.ShowLeaveConfirmation](https://create.roblox.com/docs/reference/engine/classes/GuiService#ShowLeaveConfirmation)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.SpecialKeyPressed](https://create.roblox.com/docs/reference/engine/classes/GuiService#SpecialKeyPressed)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [GuiService.UiMessageChanged](https://create.roblox.com/docs/reference/engine/classes/GuiService#UiMessageChanged)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Callback [GuiService.SendCoreUiNotification](https://create.roblox.com/docs/reference/engine/classes/GuiService#SendCoreUiNotification) from null to void
  * Changed the capabilities of Callback [GuiService.SendCoreUiNotification](https://create.roblox.com/docs/reference/engine/classes/GuiService#SendCoreUiNotification)
    from: {🚧UI}
    to: {🚧None}
  * Removed Property GuiService.DisplayScalingMode
  * Removed Property GuiService.PreferredTextSize
  * Removed Property GuiService.PreferredTransparency
  * Removed Property GuiService.ReducedMotionEnabled
  * Removed Property GuiService.TopbarInset
  * Removed Property GuiService.ViewportDisplaySize
  * Removed Property GuiService.ViewportSizeInMM
  * Removed Function GuiService.DismissNotification
  * Removed Function GuiService.GetClosestVisibleDialogToPosition
  * Removed Function GuiService.GetErrorDetails
  * Removed Function GuiService.GetGuiIsVisible
  * Removed Function GuiService.GetHardwareSafeViewport
  * Removed Function GuiService.GetInsetArea
  * Removed Function GuiService.GetRawScreenScale
  * Removed Function GuiService.OnNotificationDisplayed
  * Removed Function GuiService.OnNotificationInteraction
  * Removed Function GuiService.Select
  * Removed Function GuiService.SendNotification
  * Removed Function GuiService.SendUIOcclusionMetricsForQueryRegion
  * Removed Function GuiService.SetHardwareSafeAreaInsets
  * Removed Function GuiService.SetPurchasePromptIsShown
  * Removed Function GuiService.SetTopbarInset
  * Removed Function GuiService.ToggleGuiIsVisibleForCaptures
  * Removed Function GuiService.ToggleGuiIsVisibleIfAllowed
  * Removed Event GuiService.GuiVisibilityChangedSignal
  * Removed Event GuiService.OpenStyleEditor
  * Removed Event GuiService.PurchasePromptShown
* Update Class [HapticService](https://create.roblox.com/docs/reference/engine/classes/HapticService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Function [HapticService.GetMotor](https://create.roblox.com/docs/reference/engine/classes/HapticService#GetMotor)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [HapticService.IsMotorSupported](https://create.roblox.com/docs/reference/engine/classes/HapticService#IsMotorSupported)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [HapticService.IsVibrationSupported](https://create.roblox.com/docs/reference/engine/classes/HapticService#IsVibrationSupported)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [HapticService.SetMotor](https://create.roblox.com/docs/reference/engine/classes/HapticService#SetMotor) from null to void
  * Changed the capabilities of Function [HapticService.SetMotor](https://create.roblox.com/docs/reference/engine/classes/HapticService#SetMotor)
    from: {🚧Input}
    to: {🚧None}
* Update Class [HeightmapImporterService](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [HeightmapImporterService.CancelImportHeightmap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#CancelImportHeightmap) from null to void
  * Changed the parameters of Function [HeightmapImporterService.IsValidColormap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#IsValidColormap)
    from: (colormapAssetId: ContentId)
    to: (colormapAssetId: Content)
  * Changed the parameters of Function [HeightmapImporterService.IsValidHeightmap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#IsValidHeightmap)
    from: (heightmapAssetId: ContentId)
    to: (heightmapAssetId: Content)
  * Changed the return-type of Function [HeightmapImporterService.SetImportHeightmapPaused](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#SetImportHeightmapPaused) from null to void
  * Changed the parameters of Function [HeightmapImporterService.GetHeightmapPreviewAsync](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#GetHeightmapPreviewAsync)
    from: (heightmapAssetId: ContentId)
    to: (heightmapAssetId: Content)
  * Changed the return-type of Function [HeightmapImporterService.ImportHeightmap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#ImportHeightmap) from null to void [🏷️ Yields]
  * Changed the parameters of Function [HeightmapImporterService.ImportHeightmap](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#ImportHeightmap)
    from: (region: Region3, heightmapAssetId: ContentId, colormapAssetId: ContentId, defaultMaterial: Material)
    to: (region: Region3, heightmapAssetId: Content, colormapAssetId: Content, defaultMaterial: Material)
* Update Class [HttpRbxApiService](https://create.roblox.com/docs/reference/engine/classes/HttpRbxApiService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Function [HttpRbxApiService.GetDocumentationUrl](https://create.roblox.com/docs/reference/engine/classes/HttpRbxApiService#GetDocumentationUrl)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Function [HttpRbxApiService.GetAsync](https://create.roblox.com/docs/reference/engine/classes/HttpRbxApiService#GetAsync)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Function [HttpRbxApiService.GetAsyncFullUrl](https://create.roblox.com/docs/reference/engine/classes/HttpRbxApiService#GetAsyncFullUrl)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Function [HttpRbxApiService.PostAsync](https://create.roblox.com/docs/reference/engine/classes/HttpRbxApiService#PostAsync)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Function [HttpRbxApiService.PostAsyncFullUrl](https://create.roblox.com/docs/reference/engine/classes/HttpRbxApiService#PostAsyncFullUrl)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Function [HttpRbxApiService.RequestAsync](https://create.roblox.com/docs/reference/engine/classes/HttpRbxApiService#RequestAsync)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Function [HttpRbxApiService.RequestLimitedAsync](https://create.roblox.com/docs/reference/engine/classes/HttpRbxApiService#RequestLimitedAsync)
    from: {🚧Network}
    to: {🚧None}
* Update Class [HttpRequest](https://create.roblox.com/docs/reference/engine/classes/HttpRequest) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [HttpRequest.Cancel](https://create.roblox.com/docs/reference/engine/classes/HttpRequest#Cancel) from null to void
  * Changed the return-type of Function [HttpRequest.Start](https://create.roblox.com/docs/reference/engine/classes/HttpRequest#Start) from null to void
* Update Class [HttpService](https://create.roblox.com/docs/reference/engine/classes/HttpService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [HttpService.HttpEnabled](https://create.roblox.com/docs/reference/engine/classes/HttpService#HttpEnabled)
    from: {🔒Read:None, Write:LocalUserSecurity}
    to: {🔒LocalUserSecurity}
  * Changed the capabilities of Property [HttpService.HttpEnabled](https://create.roblox.com/docs/reference/engine/classes/HttpService#HttpEnabled)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed ThreadSafety of Function [HttpService.GenerateGUID](https://create.roblox.com/docs/reference/engine/classes/HttpService#GenerateGUID) from `Safe` to `Unsafe`
  * Changed ThreadSafety of Function [HttpService.JSONDecode](https://create.roblox.com/docs/reference/engine/classes/HttpService#JSONDecode) from `Safe` to `Unsafe`
  * Changed ThreadSafety of Function [HttpService.JSONEncode](https://create.roblox.com/docs/reference/engine/classes/HttpService#JSONEncode) from `Safe` to `Unsafe`
  * Changed the return-type of Function [HttpService.SetHttpEnabled](https://create.roblox.com/docs/reference/engine/classes/HttpService#SetHttpEnabled) from null to void
  * Changed ThreadSafety of Function [HttpService.UrlEncode](https://create.roblox.com/docs/reference/engine/classes/HttpService#UrlEncode) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [HttpService.UrlEncode](https://create.roblox.com/docs/reference/engine/classes/HttpService#UrlEncode)
    from: {🚧Network}
    to: {🚧None}
  * Changed the parameters of Function [HttpService.GetAsync](https://create.roblox.com/docs/reference/engine/classes/HttpService#GetAsync)
    from: (url: Variant, nocache: bool = false, headers: Variant)
    to: (url: string, nocache: bool = false, headers: Variant)
  * Changed the capabilities of Function [HttpService.GetAsync](https://create.roblox.com/docs/reference/engine/classes/HttpService#GetAsync)
    from: {🚧Network}
    to: {🚧None}
  * Changed the parameters of Function [HttpService.PostAsync](https://create.roblox.com/docs/reference/engine/classes/HttpService#PostAsync)
    from: (url: Variant, data: string, content_type: HttpContentType = ApplicationJson, compress: bool = false, headers: Variant)
    to: (url: string, data: string, content_type: HttpContentType = ApplicationJson, compress: bool = false, headers: Variant)
  * Changed the capabilities of Function [HttpService.PostAsync](https://create.roblox.com/docs/reference/engine/classes/HttpService#PostAsync)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Function [HttpService.RequestAsync](https://create.roblox.com/docs/reference/engine/classes/HttpService#RequestAsync)
    from: {🚧Network}
    to: {🚧None}
  * Removed Function HttpService.CreateWebStreamClient
  * Removed Function HttpService.CreateWebStreamClientInternal
  * Removed Function HttpService.GetSecret
  * Removed Function HttpService.JSONDecodeAsync
  * Removed Function HttpService.JSONEncodeAsync
  * Removed Function HttpService.RequestAccessTokenScopesAsync
* Update Class [Humanoid](https://create.roblox.com/docs/reference/engine/classes/Humanoid) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Humanoid.AutoJumpEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AutoJumpEnabled)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.AutoRotate](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AutoRotate)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.AutomaticScalingEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AutomaticScalingEnabled)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.BreakJointsOnDeath](https://create.roblox.com/docs/reference/engine/classes/Humanoid#BreakJointsOnDeath)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.CameraOffset](https://create.roblox.com/docs/reference/engine/classes/Humanoid#CameraOffset)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.DisplayDistanceType](https://create.roblox.com/docs/reference/engine/classes/Humanoid#DisplayDistanceType)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.DisplayName](https://create.roblox.com/docs/reference/engine/classes/Humanoid#DisplayName)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.FloorMaterial](https://create.roblox.com/docs/reference/engine/classes/Humanoid#FloorMaterial)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.Health](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Health)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.HealthDisplayDistance](https://create.roblox.com/docs/reference/engine/classes/Humanoid#HealthDisplayDistance)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.HealthDisplayType](https://create.roblox.com/docs/reference/engine/classes/Humanoid#HealthDisplayType)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.HipHeight](https://create.roblox.com/docs/reference/engine/classes/Humanoid#HipHeight)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.Jump](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Jump)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.JumpHeight](https://create.roblox.com/docs/reference/engine/classes/Humanoid#JumpHeight)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.JumpPower](https://create.roblox.com/docs/reference/engine/classes/Humanoid#JumpPower)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.LeftLeg](https://create.roblox.com/docs/reference/engine/classes/Humanoid#LeftLeg)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.MaxHealth](https://create.roblox.com/docs/reference/engine/classes/Humanoid#MaxHealth)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.MaxSlopeAngle](https://create.roblox.com/docs/reference/engine/classes/Humanoid#MaxSlopeAngle)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.MoveDirection](https://create.roblox.com/docs/reference/engine/classes/Humanoid#MoveDirection)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.NameDisplayDistance](https://create.roblox.com/docs/reference/engine/classes/Humanoid#NameDisplayDistance)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.NameOcclusion](https://create.roblox.com/docs/reference/engine/classes/Humanoid#NameOcclusion)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.PlatformStand](https://create.roblox.com/docs/reference/engine/classes/Humanoid#PlatformStand)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.RequiresNeck](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RequiresNeck)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.RigType](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RigType)
    from: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.RightLeg](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RightLeg)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.RootPart](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RootPart)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.SeatPart](https://create.roblox.com/docs/reference/engine/classes/Humanoid#SeatPart)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.Sit](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Sit)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.TargetPoint](https://create.roblox.com/docs/reference/engine/classes/Humanoid#TargetPoint)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.Torso](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Torso)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.UseJumpPower](https://create.roblox.com/docs/reference/engine/classes/Humanoid#UseJumpPower)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.WalkSpeed](https://create.roblox.com/docs/reference/engine/classes/Humanoid#WalkSpeed)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.WalkToPart](https://create.roblox.com/docs/reference/engine/classes/Humanoid#WalkToPart)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.WalkToPoint](https://create.roblox.com/docs/reference/engine/classes/Humanoid#WalkToPoint)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Humanoid.maxHealth](https://create.roblox.com/docs/reference/engine/classes/Humanoid#maxHealth)
    from: {🚧Read: AvatarBehavior | Write: AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.AddAccessory](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AddAccessory) from null to void
  * Changed the capabilities of Function [Humanoid.AddAccessory](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AddAccessory)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Added Function [Humanoid.ApplyDescriptionBlocking](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyDescriptionBlocking) (humanoidDescription: HumanoidDescription) -> void
  * Changed the return-type of Function [Humanoid.BuildRigFromAttachments](https://create.roblox.com/docs/reference/engine/classes/Humanoid#BuildRigFromAttachments) from null to void
  * Changed the capabilities of Function [Humanoid.BuildRigFromAttachments](https://create.roblox.com/docs/reference/engine/classes/Humanoid#BuildRigFromAttachments)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.CacheDefaults](https://create.roblox.com/docs/reference/engine/classes/Humanoid#CacheDefaults) from null to void
  * Changed the return-type of Function [Humanoid.ChangeState](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ChangeState) from null to void
  * Changed the capabilities of Function [Humanoid.ChangeState](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ChangeState)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.EquipTool](https://create.roblox.com/docs/reference/engine/classes/Humanoid#EquipTool) from null to void
  * Changed the capabilities of Function [Humanoid.EquipTool](https://create.roblox.com/docs/reference/engine/classes/Humanoid#EquipTool)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Function [Humanoid.GetAccessories](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetAccessories)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [Humanoid.GetAppliedDescription](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetAppliedDescription)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [Humanoid.GetBodyPartR15](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetBodyPartR15)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Function [Humanoid.GetLimb](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetLimb)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Function [Humanoid.GetPlayingAnimationTracks](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetPlayingAnimationTracks)
    from: {🚧Animation}
    to: {🚧None}
  * Changed ThreadSafety of Function [Humanoid.GetState](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetState) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Humanoid.GetState](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetState)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed ThreadSafety of Function [Humanoid.GetStateEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetStateEnabled) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Humanoid.GetStateEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetStateEnabled)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Function [Humanoid.LoadAnimation](https://create.roblox.com/docs/reference/engine/classes/Humanoid#LoadAnimation)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.Move](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Move) from null to void
  * Changed the capabilities of Function [Humanoid.Move](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Move)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.MoveTo](https://create.roblox.com/docs/reference/engine/classes/Humanoid#MoveTo) from null to void
  * Changed the capabilities of Function [Humanoid.MoveTo](https://create.roblox.com/docs/reference/engine/classes/Humanoid#MoveTo)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.RemoveAccessories](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RemoveAccessories) from null to void
  * Changed the capabilities of Function [Humanoid.RemoveAccessories](https://create.roblox.com/docs/reference/engine/classes/Humanoid#RemoveAccessories)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [Humanoid.ReplaceBodyPartR15](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ReplaceBodyPartR15)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.SetClickToWalkEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#SetClickToWalkEnabled) from null to void
  * Changed the return-type of Function [Humanoid.SetStateEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#SetStateEnabled) from null to void
  * Changed the capabilities of Function [Humanoid.SetStateEnabled](https://create.roblox.com/docs/reference/engine/classes/Humanoid#SetStateEnabled)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.TakeDamage](https://create.roblox.com/docs/reference/engine/classes/Humanoid#TakeDamage) from null to void
  * Changed the capabilities of Function [Humanoid.TakeDamage](https://create.roblox.com/docs/reference/engine/classes/Humanoid#TakeDamage)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.UnequipTools](https://create.roblox.com/docs/reference/engine/classes/Humanoid#UnequipTools) from null to void
  * Changed the capabilities of Function [Humanoid.UnequipTools](https://create.roblox.com/docs/reference/engine/classes/Humanoid#UnequipTools)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Function [Humanoid.loadAnimation](https://create.roblox.com/docs/reference/engine/classes/Humanoid#loadAnimation)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.takeDamage](https://create.roblox.com/docs/reference/engine/classes/Humanoid#takeDamage) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Humanoid.takeDamage](https://create.roblox.com/docs/reference/engine/classes/Humanoid#takeDamage)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Humanoid.ApplyDescription](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyDescription) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [Humanoid.ApplyDescription](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyDescription)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Added Function [Humanoid.ApplyDescriptionClientServer](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyDescriptionClientServer) (humanoidDescription: HumanoidDescription) -> void [🏷️ Yields]
  * Changed the capabilities of Function [Humanoid.PlayEmote](https://create.roblox.com/docs/reference/engine/classes/Humanoid#PlayEmote)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.AnimationPlayed](https://create.roblox.com/docs/reference/engine/classes/Humanoid#AnimationPlayed)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Climbing](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Climbing)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Died](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Died)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.FallingDown](https://create.roblox.com/docs/reference/engine/classes/Humanoid#FallingDown)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.FreeFalling](https://create.roblox.com/docs/reference/engine/classes/Humanoid#FreeFalling)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.GettingUp](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GettingUp)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.HealthChanged](https://create.roblox.com/docs/reference/engine/classes/Humanoid#HealthChanged)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Jumping](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Jumping)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.MoveToFinished](https://create.roblox.com/docs/reference/engine/classes/Humanoid#MoveToFinished)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.PlatformStanding](https://create.roblox.com/docs/reference/engine/classes/Humanoid#PlatformStanding)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Ragdoll](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Ragdoll)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Running](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Running)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Seated](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Seated)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.StateChanged](https://create.roblox.com/docs/reference/engine/classes/Humanoid#StateChanged)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.StateEnabledChanged](https://create.roblox.com/docs/reference/engine/classes/Humanoid#StateEnabledChanged)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Strafing](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Strafing)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Swimming](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Swimming)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Event [Humanoid.Touched](https://create.roblox.com/docs/reference/engine/classes/Humanoid#Touched)
    from: {🚧AvatarBehavior}
    to: {🚧None}
  * Removed Property Humanoid.EvaluateStateMachine
  * Removed Property Humanoid.InternalDisplayName
  * Removed Function Humanoid.ComputeOriginalSizeForPart
  * Removed Function Humanoid.ComputeR15BodyBoundingBox
  * Removed Function Humanoid.GetAccessoryHandleScale
  * Removed Function Humanoid.GetMoveVelocity
  * Removed Function Humanoid.GetRelativeVelocityAtFloor
  * Removed Function Humanoid.ApplyAvatarRules
  * Removed Function Humanoid.ApplyDescriptionAsync
  * Removed Function Humanoid.ApplyDescriptionReset
  * Removed Function Humanoid.ApplyDescriptionResetAsync
  * Removed Function Humanoid.PlayEmoteAsync
  * Removed Event Humanoid.ApplyDescriptionFinished
  * Removed Event Humanoid.EmoteTriggered
* Update Class [HumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [HumanoidDescription.AccessoryBlob](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#AccessoryBlob)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.AccessoryBlob](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#AccessoryBlob)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.BackAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#BackAccessory)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.BackAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#BackAccessory)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.BodyTypeScale](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#BodyTypeScale)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.ClimbAnimation](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#ClimbAnimation)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.DepthScale](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#DepthScale)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.Face](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#Face)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.FaceAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#FaceAccessory)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.FaceAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#FaceAccessory)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.FallAnimation](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#FallAnimation)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.FrontAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#FrontAccessory)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.FrontAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#FrontAccessory)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.GraphicTShirt](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#GraphicTShirt)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.HairAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#HairAccessory)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.HairAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#HairAccessory)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.HatAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#HatAccessory)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.HatAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#HatAccessory)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.Head](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#Head)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.Head](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#Head)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.HeadColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#HeadColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.HeadColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#HeadColor)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.HeadScale](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#HeadScale)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.HeightScale](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#HeightScale)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.IdleAnimation](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#IdleAnimation)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.JumpAnimation](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#JumpAnimation)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.LeftArm](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#LeftArm)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.LeftArm](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#LeftArm)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.LeftArmColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#LeftArmColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.LeftArmColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#LeftArmColor)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.LeftLeg](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#LeftLeg)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.LeftLeg](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#LeftLeg)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.LeftLegColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#LeftLegColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.LeftLegColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#LeftLegColor)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.NeckAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#NeckAccessory)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.NeckAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#NeckAccessory)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.NumberEmotesLoaded](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#NumberEmotesLoaded)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.Pants](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#Pants)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.ProportionScale](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#ProportionScale)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.RightArm](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RightArm)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.RightArm](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RightArm)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.RightArmColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RightArmColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.RightArmColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RightArmColor)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.RightLeg](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RightLeg)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.RightLeg](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RightLeg)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.RightLegColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RightLegColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.RightLegColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RightLegColor)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.RunAnimation](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RunAnimation)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.Shirt](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#Shirt)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.ShouldersAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#ShouldersAccessory)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.ShouldersAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#ShouldersAccessory)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.SwimAnimation](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SwimAnimation)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.Torso](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#Torso)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.Torso](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#Torso)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.TorsoColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#TorsoColor)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.TorsoColor](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#TorsoColor)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.WaistAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#WaistAccessory)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the serialization of Property [HumanoidDescription.WaistAccessory](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#WaistAccessory)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [HumanoidDescription.WalkAnimation](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#WalkAnimation)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Property [HumanoidDescription.WidthScale](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#WidthScale)
    from: {🚧Read: AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [HumanoidDescription.AddEmote](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#AddEmote) from null to void
  * Changed the capabilities of Function [HumanoidDescription.AddEmote](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#AddEmote)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [HumanoidDescription.GetAccessories](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#GetAccessories)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [HumanoidDescription.GetEmotes](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#GetEmotes)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Function [HumanoidDescription.GetEquippedEmotes](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#GetEquippedEmotes)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [HumanoidDescription.RemoveEmote](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RemoveEmote) from null to void
  * Changed the capabilities of Function [HumanoidDescription.RemoveEmote](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#RemoveEmote)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [HumanoidDescription.SetAccessories](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetAccessories) from null to void
  * Changed the capabilities of Function [HumanoidDescription.SetAccessories](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetAccessories)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [HumanoidDescription.SetEmotes](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetEmotes) from null to void
  * Changed the capabilities of Function [HumanoidDescription.SetEmotes](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetEmotes)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the return-type of Function [HumanoidDescription.SetEquippedEmotes](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetEquippedEmotes) from null to void
  * Changed the capabilities of Function [HumanoidDescription.SetEquippedEmotes](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#SetEquippedEmotes)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Event [HumanoidDescription.EmotesChanged](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#EmotesChanged)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Changed the capabilities of Event [HumanoidDescription.EquippedEmotesChanged](https://create.roblox.com/docs/reference/engine/classes/HumanoidDescription#EquippedEmotesChanged)
    from: {🚧AvatarAppearance}
    to: {🚧None}
  * Removed Property HumanoidDescription.MoodAnimation
  * Removed Property HumanoidDescription.ResetIncludesBodyParts
  * Removed Property HumanoidDescription.StaticFacialAnimation
  * Removed Property HumanoidDescription.UseAvatarSettings
* Update Class [IXPService](https://create.roblox.com/docs/reference/engine/classes/IXPService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [IXPService.ClearUserLayers](https://create.roblox.com/docs/reference/engine/classes/IXPService#ClearUserLayers) from null to void
  * Changed the return-type of Function [IXPService.InitializeUserLayers](https://create.roblox.com/docs/reference/engine/classes/IXPService#InitializeUserLayers) from null to void
  * Changed the return-type of Function [IXPService.RegisterUserLayers](https://create.roblox.com/docs/reference/engine/classes/IXPService#RegisterUserLayers) from null to void
  * Removed Function IXPService.ClearCreatorLayers
  * Removed Function IXPService.GetBrowserTrackerStatusForLayer
  * Removed Function IXPService.GetCreatorLayerLoadingStatus
  * Removed Function IXPService.GetCreatorLayerVariables
  * Removed Function IXPService.GetCreatorStatusForLayer
  * Removed Function IXPService.GetRegisteredCreatorLayersToStatus
  * Removed Function IXPService.GetRegisteredUserLayersToStatus
  * Removed Function IXPService.GetUserStatusForLayer
  * Removed Function IXPService.InitializeCreatorLayers
  * Removed Function IXPService.LogBrowserTrackerLayerExposure
  * Removed Function IXPService.LogCreatorLayerExposure
  * Removed Function IXPService.LogFlagLinkedUserLayerExposure
  * Removed Function IXPService.LogUserLayerExposure
  * Removed Function IXPService.RegisterCreatorLayers
  * Removed Event IXPService.OnCreatorLayerLoadingStatusChanged
* Added Class [ImporterBaseSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterBaseSettings) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [ImporterBaseSettings.Id](https://create.roblox.com/docs/reference/engine/classes/ImporterBaseSettings#Id) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [ImporterBaseSettings.ImportName](https://create.roblox.com/docs/reference/engine/classes/ImporterBaseSettings#ImportName) [⚡ThreadSafety: ReadSafe]
  * Added Property [ImporterBaseSettings.ShouldImport](https://create.roblox.com/docs/reference/engine/classes/ImporterBaseSettings#ShouldImport) [⚡ThreadSafety: ReadSafe]
* Added Class [ImporterGroupSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterGroupSettings) {🔒None} [⬆️Extends: ImporterBaseSettings] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
* Added Class [ImporterJointSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterJointSettings) {🔒None} [⬆️Extends: ImporterBaseSettings] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
* Added Class [ImporterMeshSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterMeshSettings) {🔒None} [⬆️Extends: ImporterBaseSettings] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [ImporterMeshSettings.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/ImporterMeshSettings#DoubleSided) [⚡ThreadSafety: ReadSafe]
* Added Class [ImporterRootSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings) {🔒None} [⬆️Extends: ImporterBaseSettings] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [ImporterRootSettings.FileDimensions](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#FileDimensions) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [ImporterRootSettings.FlattenAll](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#FlattenAll) [⚡ThreadSafety: ReadSafe]
  * Added Property [ImporterRootSettings.PolygonCount](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#PolygonCount) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [ImporterRootSettings.ScaleUnit](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#ScaleUnit) [⚡ThreadSafety: ReadSafe]
  * Added Property [ImporterRootSettings.WorldForward](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#WorldForward) [⚡ThreadSafety: ReadSafe]
  * Added Property [ImporterRootSettings.WorldUp](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#WorldUp) [⚡ThreadSafety: ReadSafe]
  * Added Property [ImporterRootSettings.ZeroOrigin](https://create.roblox.com/docs/reference/engine/classes/ImporterRootSettings#ZeroOrigin) [⚡ThreadSafety: ReadSafe]
* Added Class [ImporterTextureSettings](https://create.roblox.com/docs/reference/engine/classes/ImporterTextureSettings) {🔒None} [⬆️Extends: ImporterBaseSettings] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
* Update Class [IncrementalPatchBuilder](https://create.roblox.com/docs/reference/engine/classes/IncrementalPatchBuilder) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property IncrementalPatchBuilder.AddPathsToBundle
  * Removed Property IncrementalPatchBuilder.BuildDebouncePeriod
  * Removed Property IncrementalPatchBuilder.HighCompression
  * Removed Property IncrementalPatchBuilder.SerializePatch
  * Removed Property IncrementalPatchBuilder.UseFileLevelCompressionInsteadOfChunk
  * Removed Property IncrementalPatchBuilder.ZstdCompression
* Update Class [InputObject](https://create.roblox.com/docs/reference/engine/classes/InputObject) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [InputObject.Delta](https://create.roblox.com/docs/reference/engine/classes/InputObject#Delta)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [InputObject.KeyCode](https://create.roblox.com/docs/reference/engine/classes/InputObject#KeyCode)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [InputObject.Position](https://create.roblox.com/docs/reference/engine/classes/InputObject#Position)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [InputObject.UserInputState](https://create.roblox.com/docs/reference/engine/classes/InputObject#UserInputState)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [InputObject.UserInputType](https://create.roblox.com/docs/reference/engine/classes/InputObject#UserInputType)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Function [InputObject.IsModifierKeyDown](https://create.roblox.com/docs/reference/engine/classes/InputObject#IsModifierKeyDown)
    from: {🚧Input}
    to: {🚧None}
* Update Class [InsertService](https://create.roblox.com/docs/reference/engine/classes/InsertService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [InsertService.AllowClientInsertModels](https://create.roblox.com/docs/reference/engine/classes/InsertService#AllowClientInsertModels): bool [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [InsertService.AllowInsertFreeModels](https://create.roblox.com/docs/reference/engine/classes/InsertService#AllowInsertFreeModels)
    from: {🚧Read: LoadUnownedAsset | Write: LoadUnownedAsset}
    to: {🚧None}
  * Changed the return-type of Function [InsertService.ApproveAssetId](https://create.roblox.com/docs/reference/engine/classes/InsertService#ApproveAssetId) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [InsertService.ApproveAssetVersionId](https://create.roblox.com/docs/reference/engine/classes/InsertService#ApproveAssetVersionId) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [InsertService.Insert](https://create.roblox.com/docs/reference/engine/classes/InsertService#Insert) from null to void [🏷️ Deprecated]
  * Added Function [InsertService.LoadPackageAsset](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadPackageAsset) (url: Content) -> Objects
  * Changed the parameters of Function [InsertService.CreateMeshPartAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#CreateMeshPartAsync)
    from: (meshId: ContentId, collisionFidelity: CollisionFidelity, renderFidelity: RenderFidelity)
    to: (meshId: Content, collisionFidelity: CollisionFidelity, renderFidelity: RenderFidelity)
  * Changed the security of Function [InsertService.CreateMeshPartAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#CreateMeshPartAsync)
    from: {🔒None}
    to: {🔒PluginSecurity}
  * Changed the capabilities of Function [InsertService.CreateMeshPartAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#CreateMeshPartAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [InsertService.GetFreeDecals](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetFreeDecals)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [InsertService.GetFreeModels](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetFreeModels)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [InsertService.GetLatestAssetVersionAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetLatestAssetVersionAsync)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the parameters of Function [InsertService.GetUserCategories](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetUserCategories)
    from: (userId: User)
    to: (userId: int64)
  * Changed the parameters of Function [InsertService.GetUserSets](https://create.roblox.com/docs/reference/engine/classes/InsertService#GetUserSets)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [InsertService.LoadAsset](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadAsset)
    from: {🚧LoadOwnedAsset}
    to: {🚧None}
  * Changed the capabilities of Function [InsertService.LoadAssetVersion](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadAssetVersion)
    from: {🚧LoadOwnedAsset}
    to: {🚧None}
  * Changed the return-type of Function [InsertService.LoadPackageAssetAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadPackageAssetAsync) from Instances to Objects [🏷️ Yields]
  * Changed the parameters of Function [InsertService.LoadPackageAssetAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadPackageAssetAsync)
    from: (url: ContentId)
    to: (url: Content)
  * Changed the capabilities of Function [InsertService.loadAsset](https://create.roblox.com/docs/reference/engine/classes/InsertService#loadAsset)
    from: {🚧LoadOwnedAsset}
    to: {🚧None}
  * Removed Function InsertService.GetLocalFileContents
  * Removed Function InsertService.GetFreeDecalsAsync
  * Removed Function InsertService.GetFreeModelsAsync
  * Removed Function InsertService.LoadAssetWithBytecodeAsync
  * Removed Function InsertService.LoadAssetWithFormat
* Added Class [InternalContainer](https://create.roblox.com/docs/reference/engine/classes/InternalContainer) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Update Class [JointInstance](https://create.roblox.com/docs/reference/engine/classes/JointInstance) [⬆️Extends: Instance] [🧠Memory: PhysicsParts] [🏷️ NotCreatable]
  * Changed MemoryCategory of Class [JointInstance](https://create.roblox.com/docs/reference/engine/classes/JointInstance) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [JointInstance.Active](https://create.roblox.com/docs/reference/engine/classes/JointInstance#Active)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [JointInstance.C0](https://create.roblox.com/docs/reference/engine/classes/JointInstance#C0)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [JointInstance.C1](https://create.roblox.com/docs/reference/engine/classes/JointInstance#C1)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [JointInstance.Enabled](https://create.roblox.com/docs/reference/engine/classes/JointInstance#Enabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [JointInstance.Part0](https://create.roblox.com/docs/reference/engine/classes/JointInstance#Part0)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [JointInstance.Part1](https://create.roblox.com/docs/reference/engine/classes/JointInstance#Part1)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [JointInstance.part1](https://create.roblox.com/docs/reference/engine/classes/JointInstance#part1)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [DynamicRotate](https://create.roblox.com/docs/reference/engine/classes/DynamicRotate) [⬆️Extends: JointInstance] [🧠Memory: PhysicsParts] [🏷️ NotCreatable]
  * Changed MemoryCategory of Class [DynamicRotate](https://create.roblox.com/docs/reference/engine/classes/DynamicRotate) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [DynamicRotate.BaseAngle](https://create.roblox.com/docs/reference/engine/classes/DynamicRotate#BaseAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [RotateP](https://create.roblox.com/docs/reference/engine/classes/RotateP) [⬆️Extends: DynamicRotate] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [RotateP](https://create.roblox.com/docs/reference/engine/classes/RotateP) from `BaseParts` to `PhysicsParts`
* Update Class [RotateV](https://create.roblox.com/docs/reference/engine/classes/RotateV) [⬆️Extends: DynamicRotate] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [RotateV](https://create.roblox.com/docs/reference/engine/classes/RotateV) from `BaseParts` to `PhysicsParts`
* Update Class [Glue](https://create.roblox.com/docs/reference/engine/classes/Glue) [⬆️Extends: JointInstance] [🧠Memory: PhysicsParts] [🏷️ Deprecated]
  * Changed MemoryCategory of Class [Glue](https://create.roblox.com/docs/reference/engine/classes/Glue) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [Glue.F0](https://create.roblox.com/docs/reference/engine/classes/Glue#F0)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Glue.F1](https://create.roblox.com/docs/reference/engine/classes/Glue#F1)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Glue.F2](https://create.roblox.com/docs/reference/engine/classes/Glue#F2)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Glue.F3](https://create.roblox.com/docs/reference/engine/classes/Glue#F3)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [ManualSurfaceJointInstance](https://create.roblox.com/docs/reference/engine/classes/ManualSurfaceJointInstance) [⬆️Extends: JointInstance] [🧠Memory: PhysicsParts] [🏷️ NotCreatable]
  * Changed MemoryCategory of Class [ManualSurfaceJointInstance](https://create.roblox.com/docs/reference/engine/classes/ManualSurfaceJointInstance) from `BaseParts` to `PhysicsParts`
* Update Class [ManualGlue](https://create.roblox.com/docs/reference/engine/classes/ManualGlue) [⬆️Extends: ManualSurfaceJointInstance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [ManualGlue](https://create.roblox.com/docs/reference/engine/classes/ManualGlue) from `BaseParts` to `PhysicsParts`
* Update Class [ManualWeld](https://create.roblox.com/docs/reference/engine/classes/ManualWeld) [⬆️Extends: ManualSurfaceJointInstance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [ManualWeld](https://create.roblox.com/docs/reference/engine/classes/ManualWeld) from `BaseParts` to `PhysicsParts`
* Update Class [Motor](https://create.roblox.com/docs/reference/engine/classes/Motor) [⬆️Extends: JointInstance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Motor](https://create.roblox.com/docs/reference/engine/classes/Motor) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [Motor.CurrentAngle](https://create.roblox.com/docs/reference/engine/classes/Motor#CurrentAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Motor.DesiredAngle](https://create.roblox.com/docs/reference/engine/classes/Motor#DesiredAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Motor.MaxVelocity](https://create.roblox.com/docs/reference/engine/classes/Motor#MaxVelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the return-type of Function [Motor.SetDesiredAngle](https://create.roblox.com/docs/reference/engine/classes/Motor#SetDesiredAngle) from null to void
  * Changed the capabilities of Function [Motor.SetDesiredAngle](https://create.roblox.com/docs/reference/engine/classes/Motor#SetDesiredAngle)
    from: {🚧Physics}
    to: {🚧None}
* Update Class [Motor6D](https://create.roblox.com/docs/reference/engine/classes/Motor6D) [⬆️Extends: Motor] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Motor6D](https://create.roblox.com/docs/reference/engine/classes/Motor6D) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [Motor6D.ChildName](https://create.roblox.com/docs/reference/engine/classes/Motor6D#ChildName)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Motor6D.ParentName](https://create.roblox.com/docs/reference/engine/classes/Motor6D#ParentName)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [Motor6D.Transform](https://create.roblox.com/docs/reference/engine/classes/Motor6D#Transform)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Removed Property Motor6D.EnableSkinning
* Update Class [Rotate](https://create.roblox.com/docs/reference/engine/classes/Rotate) [⬆️Extends: JointInstance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Rotate](https://create.roblox.com/docs/reference/engine/classes/Rotate) from `BaseParts` to `PhysicsParts`
* Update Class [Snap](https://create.roblox.com/docs/reference/engine/classes/Snap) [⬆️Extends: JointInstance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Snap](https://create.roblox.com/docs/reference/engine/classes/Snap) from `BaseParts` to `PhysicsParts`
* Update Class [VelocityMotor](https://create.roblox.com/docs/reference/engine/classes/VelocityMotor) [⬆️Extends: JointInstance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [VelocityMotor](https://create.roblox.com/docs/reference/engine/classes/VelocityMotor) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [VelocityMotor.CurrentAngle](https://create.roblox.com/docs/reference/engine/classes/VelocityMotor#CurrentAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [VelocityMotor.DesiredAngle](https://create.roblox.com/docs/reference/engine/classes/VelocityMotor#DesiredAngle)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [VelocityMotor.Hole](https://create.roblox.com/docs/reference/engine/classes/VelocityMotor#Hole)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [VelocityMotor.MaxVelocity](https://create.roblox.com/docs/reference/engine/classes/VelocityMotor#MaxVelocity)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [Weld](https://create.roblox.com/docs/reference/engine/classes/Weld) [⬆️Extends: JointInstance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Weld](https://create.roblox.com/docs/reference/engine/classes/Weld) from `BaseParts` to `PhysicsParts`
  * Removed Property Weld.EnableSkinning
* Update Class [JointsService](https://create.roblox.com/docs/reference/engine/classes/JointsService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ Deprecated]
  * Changed the return-type of Function [JointsService.ClearJoinAfterMoveJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#ClearJoinAfterMoveJoints) from null to void
  * Changed the capabilities of Function [JointsService.ClearJoinAfterMoveJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#ClearJoinAfterMoveJoints)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [JointsService.CreateJoinAfterMoveJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#CreateJoinAfterMoveJoints) from null to void
  * Changed the capabilities of Function [JointsService.CreateJoinAfterMoveJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#CreateJoinAfterMoveJoints)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [JointsService.SetJoinAfterMoveInstance](https://create.roblox.com/docs/reference/engine/classes/JointsService#SetJoinAfterMoveInstance) from null to void
  * Changed the capabilities of Function [JointsService.SetJoinAfterMoveInstance](https://create.roblox.com/docs/reference/engine/classes/JointsService#SetJoinAfterMoveInstance)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [JointsService.SetJoinAfterMoveTarget](https://create.roblox.com/docs/reference/engine/classes/JointsService#SetJoinAfterMoveTarget) from null to void
  * Changed the capabilities of Function [JointsService.SetJoinAfterMoveTarget](https://create.roblox.com/docs/reference/engine/classes/JointsService#SetJoinAfterMoveTarget)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [JointsService.ShowPermissibleJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#ShowPermissibleJoints) from null to void
  * Changed the capabilities of Function [JointsService.ShowPermissibleJoints](https://create.roblox.com/docs/reference/engine/classes/JointsService#ShowPermissibleJoints)
    from: {🚧Physics}
    to: {🚧None}
* Update Class [Keyframe](https://create.roblox.com/docs/reference/engine/classes/Keyframe) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed the capabilities of Property [Keyframe.Time](https://create.roblox.com/docs/reference/engine/classes/Keyframe#Time)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the return-type of Function [Keyframe.AddMarker](https://create.roblox.com/docs/reference/engine/classes/Keyframe#AddMarker) from null to void
  * Changed the capabilities of Function [Keyframe.AddMarker](https://create.roblox.com/docs/reference/engine/classes/Keyframe#AddMarker)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Keyframe.AddPose](https://create.roblox.com/docs/reference/engine/classes/Keyframe#AddPose) from null to void
  * Changed the capabilities of Function [Keyframe.AddPose](https://create.roblox.com/docs/reference/engine/classes/Keyframe#AddPose)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Keyframe.GetMarkers](https://create.roblox.com/docs/reference/engine/classes/Keyframe#GetMarkers) from Instances to Objects
  * Changed the capabilities of Function [Keyframe.GetMarkers](https://create.roblox.com/docs/reference/engine/classes/Keyframe#GetMarkers)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Keyframe.GetPoses](https://create.roblox.com/docs/reference/engine/classes/Keyframe#GetPoses) from Instances to Objects
  * Changed the capabilities of Function [Keyframe.GetPoses](https://create.roblox.com/docs/reference/engine/classes/Keyframe#GetPoses)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Keyframe.RemoveMarker](https://create.roblox.com/docs/reference/engine/classes/Keyframe#RemoveMarker) from null to void
  * Changed the capabilities of Function [Keyframe.RemoveMarker](https://create.roblox.com/docs/reference/engine/classes/Keyframe#RemoveMarker)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Keyframe.RemovePose](https://create.roblox.com/docs/reference/engine/classes/Keyframe#RemovePose) from null to void
  * Changed the capabilities of Function [Keyframe.RemovePose](https://create.roblox.com/docs/reference/engine/classes/Keyframe#RemovePose)
    from: {🚧Animation}
    to: {🚧None}
* Update Class [KeyframeMarker](https://create.roblox.com/docs/reference/engine/classes/KeyframeMarker) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed the capabilities of Property [KeyframeMarker.Value](https://create.roblox.com/docs/reference/engine/classes/KeyframeMarker#Value)
    from: {🚧Read: Animation}
    to: {🚧None}
* Update Class [KeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed Superclass of Class [KeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence) from `AnimationClip` to `Instance`
  * Changed the capabilities of Property [KeyframeSequence.AuthoredHipHeight](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#AuthoredHipHeight)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Added Property [KeyframeSequence.Loop](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#Loop): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [KeyframeSequence.Priority](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#Priority): AnimationPriority [⚡ThreadSafety: ReadSafe]
  * Changed the return-type of Function [KeyframeSequence.AddKeyframe](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#AddKeyframe) from null to void
  * Changed the capabilities of Function [KeyframeSequence.AddKeyframe](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#AddKeyframe)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [KeyframeSequence.GetKeyframes](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#GetKeyframes) from Instances to Objects
  * Changed the capabilities of Function [KeyframeSequence.GetKeyframes](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#GetKeyframes)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [KeyframeSequence.RemoveKeyframe](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#RemoveKeyframe) from null to void
  * Changed the capabilities of Function [KeyframeSequence.RemoveKeyframe](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequence#RemoveKeyframe)
    from: {🚧Animation}
    to: {🚧None}
* Update Class [KeyframeSequenceProvider](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider) [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [KeyframeSequenceProvider.GetKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequence)
    from: (assetId: ContentId)
    to: (assetId: Content)
  * Changed the capabilities of Function [KeyframeSequenceProvider.GetKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequence)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Function [KeyframeSequenceProvider.GetKeyframeSequenceById](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequenceById)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the capabilities of Function [KeyframeSequenceProvider.GetMemStats](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetMemStats)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [KeyframeSequenceProvider.RegisterActiveKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#RegisterActiveKeyframeSequence) from ContentId to Content
  * Changed the capabilities of Function [KeyframeSequenceProvider.RegisterActiveKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#RegisterActiveKeyframeSequence)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [KeyframeSequenceProvider.RegisterKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#RegisterKeyframeSequence) from ContentId to Content
  * Changed the capabilities of Function [KeyframeSequenceProvider.RegisterKeyframeSequence](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#RegisterKeyframeSequence)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the parameters of Function [KeyframeSequenceProvider.GetAnimations](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetAnimations)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [KeyframeSequenceProvider.GetAnimations](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetAnimations)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the parameters of Function [KeyframeSequenceProvider.GetKeyframeSequenceAsync](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequenceAsync)
    from: (assetId: ContentId)
    to: (assetId: Content)
  * Changed the capabilities of Function [KeyframeSequenceProvider.GetKeyframeSequenceAsync](https://create.roblox.com/docs/reference/engine/classes/KeyframeSequenceProvider#GetKeyframeSequenceAsync)
    from: {🚧Animation}
    to: {🚧None}
  * Removed Function KeyframeSequenceProvider.GetAnimationsAsync
* Update Class [LanguageService](https://create.roblox.com/docs/reference/engine/classes/LanguageService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function LanguageService.GetCapabilitiesUsedInPackageAsync
* Update Class [Light](https://create.roblox.com/docs/reference/engine/classes/Light) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [Light.Brightness](https://create.roblox.com/docs/reference/engine/classes/Light#Brightness)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Light.Color](https://create.roblox.com/docs/reference/engine/classes/Light#Color)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Light.Enabled](https://create.roblox.com/docs/reference/engine/classes/Light#Enabled)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Light.Shadows](https://create.roblox.com/docs/reference/engine/classes/Light#Shadows)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [PointLight](https://create.roblox.com/docs/reference/engine/classes/PointLight) [⬆️Extends: Light] [🧠Memory: Instances]
  * Changed the capabilities of Property [PointLight.Range](https://create.roblox.com/docs/reference/engine/classes/PointLight#Range)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [SpotLight](https://create.roblox.com/docs/reference/engine/classes/SpotLight) [⬆️Extends: Light] [🧠Memory: Instances]
  * Changed the capabilities of Property [SpotLight.Angle](https://create.roblox.com/docs/reference/engine/classes/SpotLight#Angle)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SpotLight.Face](https://create.roblox.com/docs/reference/engine/classes/SpotLight#Face)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SpotLight.Range](https://create.roblox.com/docs/reference/engine/classes/SpotLight#Range)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [SurfaceLight](https://create.roblox.com/docs/reference/engine/classes/SurfaceLight) [⬆️Extends: Light] [🧠Memory: Instances]
  * Changed the capabilities of Property [SurfaceLight.Angle](https://create.roblox.com/docs/reference/engine/classes/SurfaceLight#Angle)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceLight.Face](https://create.roblox.com/docs/reference/engine/classes/SurfaceLight#Face)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SurfaceLight.Range](https://create.roblox.com/docs/reference/engine/classes/SurfaceLight#Range)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [Lighting](https://create.roblox.com/docs/reference/engine/classes/Lighting) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [Lighting.Ambient](https://create.roblox.com/docs/reference/engine/classes/Lighting#Ambient)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.Brightness](https://create.roblox.com/docs/reference/engine/classes/Lighting#Brightness)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.ClockTime](https://create.roblox.com/docs/reference/engine/classes/Lighting#ClockTime)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.ColorShift_Bottom](https://create.roblox.com/docs/reference/engine/classes/Lighting#ColorShift_Bottom)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.ColorShift_Top](https://create.roblox.com/docs/reference/engine/classes/Lighting#ColorShift_Top)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.EnvironmentDiffuseScale](https://create.roblox.com/docs/reference/engine/classes/Lighting#EnvironmentDiffuseScale)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.EnvironmentSpecularScale](https://create.roblox.com/docs/reference/engine/classes/Lighting#EnvironmentSpecularScale)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.ExposureCompensation](https://create.roblox.com/docs/reference/engine/classes/Lighting#ExposureCompensation)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.FogColor](https://create.roblox.com/docs/reference/engine/classes/Lighting#FogColor)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.FogEnd](https://create.roblox.com/docs/reference/engine/classes/Lighting#FogEnd)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.FogStart](https://create.roblox.com/docs/reference/engine/classes/Lighting#FogStart)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.GeographicLatitude](https://create.roblox.com/docs/reference/engine/classes/Lighting#GeographicLatitude)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.GlobalShadows](https://create.roblox.com/docs/reference/engine/classes/Lighting#GlobalShadows)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.OutdoorAmbient](https://create.roblox.com/docs/reference/engine/classes/Lighting#OutdoorAmbient)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.Outlines](https://create.roblox.com/docs/reference/engine/classes/Lighting#Outlines)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.ShadowColor](https://create.roblox.com/docs/reference/engine/classes/Lighting#ShadowColor)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Lighting.ShadowSoftness](https://create.roblox.com/docs/reference/engine/classes/Lighting#ShadowSoftness)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the security of Property [Lighting.Technology](https://create.roblox.com/docs/reference/engine/classes/Lighting#Technology)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Lighting.Technology](https://create.roblox.com/docs/reference/engine/classes/Lighting#Technology)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Added Property [Lighting.TempUseNewSkyRemovalBehaviour](https://create.roblox.com/docs/reference/engine/classes/Lighting#TempUseNewSkyRemovalBehaviour): bool [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [Lighting.TimeOfDay](https://create.roblox.com/docs/reference/engine/classes/Lighting#TimeOfDay)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed ThreadSafety of Function [Lighting.GetMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#GetMinutesAfterMidnight) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Lighting.GetMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#GetMinutesAfterMidnight)
    from: {🚧Environment}
    to: {🚧None}
  * Changed ThreadSafety of Function [Lighting.GetMoonDirection](https://create.roblox.com/docs/reference/engine/classes/Lighting#GetMoonDirection) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Lighting.GetMoonDirection](https://create.roblox.com/docs/reference/engine/classes/Lighting#GetMoonDirection)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Lighting.GetMoonPhase](https://create.roblox.com/docs/reference/engine/classes/Lighting#GetMoonPhase)
    from: {🚧Environment}
    to: {🚧None}
  * Changed ThreadSafety of Function [Lighting.GetSunDirection](https://create.roblox.com/docs/reference/engine/classes/Lighting#GetSunDirection) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Lighting.GetSunDirection](https://create.roblox.com/docs/reference/engine/classes/Lighting#GetSunDirection)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Lighting.SetMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#SetMinutesAfterMidnight) from null to void
  * Changed the capabilities of Function [Lighting.SetMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#SetMinutesAfterMidnight)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Lighting.getMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#getMinutesAfterMidnight)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Lighting.setMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#setMinutesAfterMidnight) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Lighting.setMinutesAfterMidnight](https://create.roblox.com/docs/reference/engine/classes/Lighting#setMinutesAfterMidnight)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Event [Lighting.LightingChanged](https://create.roblox.com/docs/reference/engine/classes/Lighting#LightingChanged)
    from: {🚧Environment}
    to: {🚧None}
  * Removed Property Lighting.ExtendLightRangeTo120
  * Removed Property Lighting.LightingStyle
  * Removed Property Lighting.PrioritizeLightingQuality
* Update Class [LocalStorageService](https://create.roblox.com/docs/reference/engine/classes/LocalStorageService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [LocalStorageService.Flush](https://create.roblox.com/docs/reference/engine/classes/LocalStorageService#Flush) from null to void
  * Changed the return-type of Function [LocalStorageService.SetItem](https://create.roblox.com/docs/reference/engine/classes/LocalStorageService#SetItem) from null to void
  * Changed the return-type of Function [LocalStorageService.WhenLoaded](https://create.roblox.com/docs/reference/engine/classes/LocalStorageService#WhenLoaded) from null to void
* Update Class [LocalizationService](https://create.roblox.com/docs/reference/engine/classes/LocalizationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [LocalizationService.ForcePlayModeGameLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#ForcePlayModeGameLocaleId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [LocalizationService.ForcePlayModeRobloxLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#ForcePlayModeRobloxLocaleId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [LocalizationService.IsTextScraperRunning](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#IsTextScraperRunning)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [LocalizationService.RobloxForcePlayModeGameLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#RobloxForcePlayModeGameLocaleId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [LocalizationService.RobloxForcePlayModeRobloxLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#RobloxForcePlayModeRobloxLocaleId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [LocalizationService.RobloxLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#RobloxLocaleId)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [LocalizationService.SystemLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#SystemLocaleId)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationService.GetCorescriptLocalizations](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#GetCorescriptLocalizations) from Instances to Objects
  * Changed the capabilities of Function [LocalizationService.GetCorescriptLocalizations](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#GetCorescriptLocalizations)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationService.GetTableEntries](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#GetTableEntries)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationService.GetTranslatorForPlayer](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#GetTranslatorForPlayer)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationService.SetRobloxLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#SetRobloxLocaleId) from null to void
  * Changed the capabilities of Function [LocalizationService.SetRobloxLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#SetRobloxLocaleId)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationService.StartTextScraper](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#StartTextScraper) from null to void
  * Changed the capabilities of Function [LocalizationService.StartTextScraper](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#StartTextScraper)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationService.StopTextScraper](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#StopTextScraper) from null to void
  * Changed the capabilities of Function [LocalizationService.StopTextScraper](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#StopTextScraper)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationService.GetCountryRegionForPlayerAsync](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#GetCountryRegionForPlayerAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationService.GetTranslatorForLocaleAsync](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#GetTranslatorForLocaleAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationService.GetTranslatorForPlayerAsync](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#GetTranslatorForPlayerAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationService.PromptDownloadGameTableToCSV](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptDownloadGameTableToCSV) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [LocalizationService.PromptDownloadGameTableToCSV](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptDownloadGameTableToCSV)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationService.PromptExportToCSVs](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptExportToCSVs) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [LocalizationService.PromptExportToCSVs](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptExportToCSVs)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationService.PromptImportFromCSVs](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptImportFromCSVs) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [LocalizationService.PromptImportFromCSVs](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptImportFromCSVs)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationService.PromptUploadCSVToGameTable](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#PromptUploadCSVToGameTable)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [LocalizationService.AutoTranslateWillRun](https://create.roblox.com/docs/reference/engine/classes/LocalizationService#AutoTranslateWillRun)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Function LocalizationService.GetIsLoadingInternalTranslations
  * Removed Function LocalizationService.IsLoadingInternalTranslationsSettingChanged
* Update Class [LocalizationTable](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [LocalizationTable.DevelopmentLanguage](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#DevelopmentLanguage)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [LocalizationTable.Root](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#Root)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [LocalizationTable.SourceLocaleId](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SourceLocaleId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationTable.GetContents](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#GetContents)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationTable.GetEntries](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#GetEntries)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationTable.GetString](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#GetString)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [LocalizationTable.GetTranslator](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#GetTranslator)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.RemoveEntry](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveEntry) from null to void
  * Changed the capabilities of Function [LocalizationTable.RemoveEntry](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveEntry)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.RemoveEntryValue](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveEntryValue) from null to void
  * Changed the capabilities of Function [LocalizationTable.RemoveEntryValue](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveEntryValue)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.RemoveKey](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveKey) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [LocalizationTable.RemoveKey](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveKey)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.RemoveTargetLocale](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveTargetLocale) from null to void
  * Changed the capabilities of Function [LocalizationTable.RemoveTargetLocale](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#RemoveTargetLocale)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetContents](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetContents) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [LocalizationTable.SetContents](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetContents)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetEntries](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntries) from null to void
  * Changed the capabilities of Function [LocalizationTable.SetEntries](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntries)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetEntry](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntry) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [LocalizationTable.SetEntry](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntry)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetEntryContext](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryContext) from null to void
  * Changed the capabilities of Function [LocalizationTable.SetEntryContext](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryContext)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetEntryExample](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryExample) from null to void
  * Changed the capabilities of Function [LocalizationTable.SetEntryExample](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryExample)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetEntryKey](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryKey) from null to void
  * Changed the capabilities of Function [LocalizationTable.SetEntryKey](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryKey)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetEntrySource](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntrySource) from null to void
  * Changed the capabilities of Function [LocalizationTable.SetEntrySource](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntrySource)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetEntryValue](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryValue) from null to void
  * Changed the capabilities of Function [LocalizationTable.SetEntryValue](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetEntryValue)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [LocalizationTable.SetIsExemptFromUGCAnalytics](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetIsExemptFromUGCAnalytics) from null to void
  * Changed the capabilities of Function [LocalizationTable.SetIsExemptFromUGCAnalytics](https://create.roblox.com/docs/reference/engine/classes/LocalizationTable#SetIsExemptFromUGCAnalytics)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [LogService](https://create.roblox.com/docs/reference/engine/classes/LogService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [LogService.ExecuteScript](https://create.roblox.com/docs/reference/engine/classes/LogService#ExecuteScript) from null to void
  * Changed the capabilities of Function [LogService.ExecuteScript](https://create.roblox.com/docs/reference/engine/classes/LogService#ExecuteScript)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the capabilities of Function [LogService.GetHttpResultHistory](https://create.roblox.com/docs/reference/engine/classes/LogService#GetHttpResultHistory)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the capabilities of Function [LogService.GetLogHistory](https://create.roblox.com/docs/reference/engine/classes/LogService#GetLogHistory)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the return-type of Function [LogService.RequestHttpResultApproved](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestHttpResultApproved) from null to void
  * Changed the capabilities of Function [LogService.RequestHttpResultApproved](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestHttpResultApproved)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the return-type of Function [LogService.RequestServerHttpResult](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestServerHttpResult) from null to void
  * Changed the capabilities of Function [LogService.RequestServerHttpResult](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestServerHttpResult)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the return-type of Function [LogService.RequestServerOutput](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestServerOutput) from null to void
  * Changed the capabilities of Function [LogService.RequestServerOutput](https://create.roblox.com/docs/reference/engine/classes/LogService#RequestServerOutput)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the capabilities of Event [LogService.HttpResultOut](https://create.roblox.com/docs/reference/engine/classes/LogService#HttpResultOut)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the parameters of Event [LogService.MessageOut](https://create.roblox.com/docs/reference/engine/classes/LogService#MessageOut)
    from: (message: string, messageType: MessageType, context: Dictionary)
    to: (message: string, messageType: MessageType)
  * Changed the capabilities of Event [LogService.MessageOut](https://create.roblox.com/docs/reference/engine/classes/LogService#MessageOut)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the capabilities of Event [LogService.OnHttpResultApproved](https://create.roblox.com/docs/reference/engine/classes/LogService#OnHttpResultApproved)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the capabilities of Event [LogService.ServerHttpResultOut](https://create.roblox.com/docs/reference/engine/classes/LogService#ServerHttpResultOut)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the parameters of Event [LogService.ServerMessageOut](https://create.roblox.com/docs/reference/engine/classes/LogService#ServerMessageOut)
    from: (message: string, messageType: MessageType, timestamp: double)
    to: (message: string, messageType: MessageType, timestamp: int)
  * Changed the capabilities of Event [LogService.ServerMessageOut](https://create.roblox.com/docs/reference/engine/classes/LogService#ServerMessageOut)
    from: {🚧Logging}
    to: {🚧None}
  * Removed Function LogService.ClearOutput
  * Removed Function LogService.Error
  * Removed Function LogService.Info
  * Removed Function LogService.Log
  * Removed Function LogService.Output
  * Removed Function LogService.Warn
  * Removed Event LogService.ServerContextOut
* Update Class [LoginService](https://create.roblox.com/docs/reference/engine/classes/LoginService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [LoginService.Logout](https://create.roblox.com/docs/reference/engine/classes/LoginService#Logout) from null to void
  * Changed the return-type of Function [LoginService.PromptLogin](https://create.roblox.com/docs/reference/engine/classes/LoginService#PromptLogin) from null to void
* Update Class [LuaSourceContainer](https://create.roblox.com/docs/reference/engine/classes/LuaSourceContainer) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Added Property [LuaSourceContainer.CurrentEditor](https://create.roblox.com/docs/reference/engine/classes/LuaSourceContainer#CurrentEditor): Instance [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
* Update Class [BaseScript](https://create.roblox.com/docs/reference/engine/classes/BaseScript) [⬆️Extends: LuaSourceContainer] [🧠Memory: Script] [🏷️ NotCreatable]
  * Changed the capabilities of Property [BaseScript.LinkedSource](https://create.roblox.com/docs/reference/engine/classes/BaseScript#LinkedSource)
    from: {🚧Read: LoadUnownedAsset | Write: LoadUnownedAsset}
    to: {🚧None}
  * Removed Property BaseScript.Enabled
  * Removed Property BaseScript.RunContext
* Update Class [Script](https://create.roblox.com/docs/reference/engine/classes/Script) [⬆️Extends: BaseScript] [🧠Memory: Script]
  * Changed the security of Property [Script.Source](https://create.roblox.com/docs/reference/engine/classes/Script#Source)
    from: {🔒None}
    to: {🔒PluginSecurity}
  * Changed the capabilities of Property [Script.Source](https://create.roblox.com/docs/reference/engine/classes/Script#Source)
    from: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
    to: {🚧None}
* Update Class [ModuleScript](https://create.roblox.com/docs/reference/engine/classes/ModuleScript) [⬆️Extends: LuaSourceContainer] [🧠Memory: Script]
  * Changed the capabilities of Property [ModuleScript.LinkedSource](https://create.roblox.com/docs/reference/engine/classes/ModuleScript#LinkedSource)
    from: {🚧Read: LoadUnownedAsset | Write: LoadUnownedAsset}
    to: {🚧None}
  * Changed the security of Property [ModuleScript.Source](https://create.roblox.com/docs/reference/engine/classes/ModuleScript#Source)
    from: {🔒None}
    to: {🔒PluginSecurity}
  * Changed the capabilities of Property [ModuleScript.Source](https://create.roblox.com/docs/reference/engine/classes/ModuleScript#Source)
    from: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
    to: {🚧None}
* Update Class [MarketplaceService](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [MarketplaceService.PromptBundlePurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptBundlePurchase) from null to void
  * Changed the capabilities of Function [MarketplaceService.PromptBundlePurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptBundlePurchase)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the return-type of Function [MarketplaceService.PromptGamePassPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptGamePassPurchase) from null to void
  * Changed the capabilities of Function [MarketplaceService.PromptGamePassPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptGamePassPurchase)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the return-type of Function [MarketplaceService.PromptNativePurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptNativePurchase) from null to void
  * Changed the return-type of Function [MarketplaceService.PromptPremiumPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptPremiumPurchase) from null to void
  * Changed the capabilities of Function [MarketplaceService.PromptPremiumPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptPremiumPurchase)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the return-type of Function [MarketplaceService.PromptProductPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptProductPurchase) from null to void
  * Changed the capabilities of Function [MarketplaceService.PromptProductPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptProductPurchase)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the return-type of Function [MarketplaceService.PromptPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptPurchase) from null to void
  * Changed the capabilities of Function [MarketplaceService.PromptPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptPurchase)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the return-type of Function [MarketplaceService.PromptRobloxPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptRobloxPurchase) from null to void
  * Added Function [MarketplaceService.PromptSubscriptionCancellation](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionCancellation) (player: Instance, subscriptionId: int64) -> void
  * Changed the return-type of Function [MarketplaceService.PromptSubscriptionPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchase) from null to void
  * Changed the parameters of Function [MarketplaceService.PromptSubscriptionPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchase)
    from: (user: Player, subscriptionId: string)
    to: (player: Instance, subscriptionId: int64)
  * Changed the capabilities of Function [MarketplaceService.PromptSubscriptionPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchase)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the return-type of Function [MarketplaceService.PromptThirdPartyPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptThirdPartyPurchase) from null to void
  * Changed the return-type of Function [MarketplaceService.ReportAssetSale](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#ReportAssetSale) from null to void
  * Changed the return-type of Function [MarketplaceService.ReportRobuxUpsellStarted](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#ReportRobuxUpsellStarted) from null to void
  * Changed the return-type of Function [MarketplaceService.SignalAssetTypePurchased](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalAssetTypePurchased) from null to void
  * Changed the return-type of Function [MarketplaceService.SignalClientPurchaseSuccess](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalClientPurchaseSuccess) from null to void
  * Changed the return-type of Function [MarketplaceService.SignalMockPurchasePremium](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalMockPurchasePremium) from null to void
  * Changed the return-type of Function [MarketplaceService.SignalPromptBundlePurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptBundlePurchaseFinished) from null to void
  * Changed the return-type of Function [MarketplaceService.SignalPromptGamePassPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptGamePassPurchaseFinished) from null to void
  * Changed the return-type of Function [MarketplaceService.SignalPromptPremiumPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptPremiumPurchaseFinished) from null to void
  * Changed the return-type of Function [MarketplaceService.SignalPromptProductPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptProductPurchaseFinished) from null to void
  * Changed the return-type of Function [MarketplaceService.SignalPromptPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptPurchaseFinished) from null to void
  * Added Function [MarketplaceService.SignalPromptSubscriptionCancellationFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptSubscriptionCancellationFinished) (player: Instance, subscriptionId: int64, wasCanceled: bool) -> void
  * Changed the return-type of Function [MarketplaceService.SignalPromptSubscriptionPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptSubscriptionPurchaseFinished) from null to void
  * Changed the parameters of Function [MarketplaceService.SignalPromptSubscriptionPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalPromptSubscriptionPurchaseFinished)
    from: (subscriptionId: string, didTryPurchasing: bool)
    to: (player: Instance, subscriptionId: int64, wasPurchased: bool)
  * Changed the return-type of Function [MarketplaceService.SignalServerLuaDialogClosed](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#SignalServerLuaDialogClosed) from null to void
  * Changed the capabilities of Function [MarketplaceService.GetDeveloperProductsAsync](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#GetDeveloperProductsAsync)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Function [MarketplaceService.GetProductInfo](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#GetProductInfo)
    from: {🚧AssetRead}
    to: {🚧None}
  * Added Function [MarketplaceService.IsPlayerSubscribed](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#IsPlayerSubscribed) (player: Instance, subscriptionId: int64) -> bool [🏷️ Yields]
  * Changed the parameters of Function [MarketplaceService.PerformPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PerformPurchase)
    from: (infoType: InfoType, productId: int64, expectedPrice: int, requestId: string, isRobloxPurchase: bool, collectibleItemId: string = , collectibleProductId: string = , idempotencyKey: string = , purchaseAuthToken: string = , timedOptionsDays: int64 = 0, purchasePayload: string = , purchaseOptions: Dictionary = nil)
    to: (infoType: InfoType, productId: int64, expectedPrice: int, requestId: string, isRobloxPurchase: bool)
  * Changed the capabilities of Function [MarketplaceService.PlayerOwnsAsset](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PlayerOwnsAsset)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the parameters of Function [MarketplaceService.UserOwnsGamePassAsync](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#UserOwnsGamePassAsync)
    from: (userId: User, gamePassId: int64)
    to: (userId: int64, gamePassId: int64)
  * Changed the capabilities of Function [MarketplaceService.UserOwnsGamePassAsync](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#UserOwnsGamePassAsync)
    from: {🚧AssetRead}
    to: {🚧None}
  * Changed the capabilities of Event [MarketplaceService.PromptBundlePurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptBundlePurchaseFinished)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the capabilities of Event [MarketplaceService.PromptGamePassPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptGamePassPurchaseFinished)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the capabilities of Event [MarketplaceService.PromptPremiumPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptPremiumPurchaseFinished)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the capabilities of Event [MarketplaceService.PromptProductPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptProductPurchaseFinished)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the capabilities of Event [MarketplaceService.PromptPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptPurchaseFinished)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Added Event [MarketplaceService.PromptSubscriptionCancellationFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionCancellationFinished)
  * Added Event [MarketplaceService.PromptSubscriptionCancellationRequested](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionCancellationRequested)
  * Changed the parameters of Event [MarketplaceService.PromptSubscriptionPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchaseFinished)
    from: (user: Player, subscriptionId: string, didTryPurchasing: bool)
    to: (player: Instance, subscriptionId: int64, wasPurchased: bool)
  * Changed the capabilities of Event [MarketplaceService.PromptSubscriptionPurchaseFinished](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchaseFinished)
    from: {🚧PromptExternalPurchase}
    to: {🚧None}
  * Changed the parameters of Event [MarketplaceService.PromptSubscriptionPurchaseRequested](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptSubscriptionPurchaseRequested)
    from: (subscriptionId: string)
    to: (player: Instance, subscriptionId: int64)
  * Changed the capabilities of Callback [MarketplaceService.ProcessReceipt](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#ProcessReceipt)
    from: {🚧Monetization}
    to: {🚧None}
  * Removed Function MarketplaceService.BindReceiptHandler
  * Removed Function MarketplaceService.ClearProductInfoCaches
  * Removed Function MarketplaceService.IsPurchaseSimulated
  * Removed Function MarketplaceService.OpenShop
  * Removed Function MarketplaceService.PrepareCollectiblesPurchase
  * Removed Function MarketplaceService.PromptBulkPurchase
  * Removed Function MarketplaceService.PromptCancelSubscription
  * Removed Function MarketplaceService.PromptCollectiblesPurchase
  * Removed Function MarketplaceService.PromptNativePurchaseWithLocalPlayer
  * Removed Function MarketplaceService.PromptNativePurchaseWithLocalPlayerWithPaymentSessionId
  * Removed Function MarketplaceService.PromptNativePurchaseWithPaymentSessionId
  * Removed Function MarketplaceService.PromptRobloxSubscriptionPurchase
  * Removed Function MarketplaceService.SignalCheckPlayerHasRobloxSubscription
  * Removed Function MarketplaceService.SignalMockPurchaseRobloxSubscription
  * Removed Function MarketplaceService.SignalPromptBulkPurchaseFinished
  * Removed Function MarketplaceService.SignalPromptRobloxSubscriptionPurchaseFinished
  * Removed Function MarketplaceService.SignalRobuxTransferCompleted
  * Removed Function MarketplaceService.SignalUserSubscriptionStatusChanged
  * Removed Function MarketplaceService.GetAvailableSubscriptionProductsAsync
  * Removed Function MarketplaceService.GetProductInfoAsync
  * Removed Function MarketplaceService.GetRobloxSubscriptionDetailsAsync
  * Removed Function MarketplaceService.GetSubscriptionProductInfoAsync
  * Removed Function MarketplaceService.GetSubscriptionPurchaseInfoAsync
  * Removed Function MarketplaceService.GetUserSubscriptionDetailsAsync
  * Removed Function MarketplaceService.GetUserSubscriptionDetailsInternalAsync
  * Removed Function MarketplaceService.GetUserSubscriptionPaymentHistoryAsync
  * Removed Function MarketplaceService.GetUserSubscriptionStatusAsync
  * Removed Function MarketplaceService.GetUsersPriceLevelsAsync
  * Removed Function MarketplaceService.PerformBulkPurchase
  * Removed Function MarketplaceService.PerformCancelSubscription
  * Removed Function MarketplaceService.PerformPurchaseV2
  * Removed Function MarketplaceService.PerformSubscriptionPurchase
  * Removed Function MarketplaceService.PerformSubscriptionPurchaseV2
  * Removed Function MarketplaceService.PerformSubscriptionPurchaseV3Async
  * Removed Function MarketplaceService.PerformSubscriptionPurchaseWithRobuxAsync
  * Removed Function MarketplaceService.PlayerOwnsAssetAsync
  * Removed Function MarketplaceService.PlayerOwnsBundle
  * Removed Function MarketplaceService.PlayerOwnsBundleAsync
  * Removed Function MarketplaceService.PromptRobuxTransferAsync
  * Removed Function MarketplaceService.RankProductsAsync
  * Removed Function MarketplaceService.RecommendTopProductsAsync
  * Removed Event MarketplaceService.NativePurchaseFinishedV2
  * Removed Event MarketplaceService.NativePurchaseFinishedWithLocalPlayer
  * Removed Event MarketplaceService.NativePurchaseFinishedWithLocalPlayerV2
  * Removed Event MarketplaceService.OpenShopRequested
  * Removed Event MarketplaceService.PrepareCollectiblesPurchaseRequested
  * Removed Event MarketplaceService.PromptBulkPurchaseFinished
  * Removed Event MarketplaceService.PromptBulkPurchaseRequested
  * Removed Event MarketplaceService.PromptBulkPurchaseRequestedV2
  * Removed Event MarketplaceService.PromptCancelSubscriptionRequested
  * Removed Event MarketplaceService.PromptCollectibleBundlePurchaseRequested
  * Removed Event MarketplaceService.PromptCollectiblesPurchaseRequested
  * Removed Event MarketplaceService.PromptPurchaseRequestedV2
  * Removed Event MarketplaceService.PromptRobloxSubscriptionPurchaseFinished
  * Removed Event MarketplaceService.PromptRobloxSubscriptionPurchaseRequested
  * Removed Event MarketplaceService.PromptRobuxTransferRequested
  * Removed Event MarketplaceService.PromptRobuxTransferSubscriptionUpsellRequested
  * Removed Event MarketplaceService.RobuxTransferCompleted
  * Removed Event MarketplaceService.UserSubscriptionStatusChanged
* Update Class [MemStorageConnection](https://create.roblox.com/docs/reference/engine/classes/MemStorageConnection) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [MemStorageConnection.Disconnect](https://create.roblox.com/docs/reference/engine/classes/MemStorageConnection#Disconnect) from null to void
* Update Class [MemStorageService](https://create.roblox.com/docs/reference/engine/classes/MemStorageService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [MemStorageService.Fire](https://create.roblox.com/docs/reference/engine/classes/MemStorageService#Fire) from null to void
  * Changed the return-type of Function [MemStorageService.SetItem](https://create.roblox.com/docs/reference/engine/classes/MemStorageService#SetItem) from null to void
* Update Class [MemoryStoreQueue](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [MemoryStoreQueue.AddAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue#AddAsync) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [MemoryStoreQueue.AddAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue#AddAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [MemoryStoreQueue.ReadAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue#ReadAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the return-type of Function [MemoryStoreQueue.RemoveAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue#RemoveAsync) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [MemoryStoreQueue.RemoveAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreQueue#RemoveAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Removed Function MemoryStoreQueue.GetSizeAsync
* Update Class [MemoryStoreService](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Changed the capabilities of Function [MemoryStoreService.GetQueue](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreService#GetQueue)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the capabilities of Function [MemoryStoreService.GetSortedMap](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreService#GetSortedMap)
    from: {🚧DataStore}
    to: {🚧None}
  * Removed Function MemoryStoreService.GetHashMap
* Update Class [MemoryStoreSortedMap](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [MemoryStoreSortedMap.GetAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#GetAsync) from Tuple to Variant [🏷️ Yields]
  * Changed the capabilities of Function [MemoryStoreSortedMap.GetAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#GetAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the parameters of Function [MemoryStoreSortedMap.GetRangeAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#GetRangeAsync)
    from: (direction: SortDirection, count: int, exclusiveLowerBound: Variant, exclusiveUpperBound: Variant)
    to: (direction: SortDirection, count: int, exclusiveLowerBound: string = , exclusiveUpperBound: string = )
  * Changed the capabilities of Function [MemoryStoreSortedMap.GetRangeAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#GetRangeAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the return-type of Function [MemoryStoreSortedMap.RemoveAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#RemoveAsync) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [MemoryStoreSortedMap.RemoveAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#RemoveAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the parameters of Function [MemoryStoreSortedMap.SetAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#SetAsync)
    from: (key: string, value: Variant, expiration: int64, sortKey: Variant)
    to: (key: string, value: Variant, expiration: int64)
  * Changed the capabilities of Function [MemoryStoreSortedMap.SetAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#SetAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Changed the return-type of Function [MemoryStoreSortedMap.UpdateAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#UpdateAsync) from Tuple to Variant [🏷️ Yields]
  * Changed the capabilities of Function [MemoryStoreSortedMap.UpdateAsync](https://create.roblox.com/docs/reference/engine/classes/MemoryStoreSortedMap#UpdateAsync)
    from: {🚧DataStore}
    to: {🚧None}
  * Removed Function MemoryStoreSortedMap.GetSizeAsync
* Update Class [Message](https://create.roblox.com/docs/reference/engine/classes/Message) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Deprecated]
  * Changed the capabilities of Property [Message.Text](https://create.roblox.com/docs/reference/engine/classes/Message#Text)
    from: {🚧Read: UI | Write: UI}
    to: {🚧None}
* Update Class [MessageBusConnection](https://create.roblox.com/docs/reference/engine/classes/MessageBusConnection) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [MessageBusConnection.Disconnect](https://create.roblox.com/docs/reference/engine/classes/MessageBusConnection#Disconnect) from null to void
* Update Class [MessageBusService](https://create.roblox.com/docs/reference/engine/classes/MessageBusService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [MessageBusService.Publish](https://create.roblox.com/docs/reference/engine/classes/MessageBusService#Publish) from null to void
  * Removed Function MessageBusService.GetProtocolMethodRequestMessageId
  * Removed Function MessageBusService.GetProtocolMethodResponseMessageId
  * Removed Function MessageBusService.MakeRequest
  * Removed Function MessageBusService.PublishProtocolMethodRequest
  * Removed Function MessageBusService.PublishProtocolMethodResponse
  * Removed Function MessageBusService.SetRequestHandler
  * Removed Function MessageBusService.SubscribeToProtocolMethodRequest
  * Removed Function MessageBusService.SubscribeToProtocolMethodResponse
* Update Class [MessagingService](https://create.roblox.com/docs/reference/engine/classes/MessagingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [MessagingService.PublishAsync](https://create.roblox.com/docs/reference/engine/classes/MessagingService#PublishAsync) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [MessagingService.PublishAsync](https://create.roblox.com/docs/reference/engine/classes/MessagingService#PublishAsync)
    from: {🚧ServerCommunication}
    to: {🚧None}
  * Changed the capabilities of Function [MessagingService.SubscribeAsync](https://create.roblox.com/docs/reference/engine/classes/MessagingService#SubscribeAsync)
    from: {🚧ServerCommunication}
    to: {🚧None}
* Update Class [Mouse](https://create.roblox.com/docs/reference/engine/classes/Mouse) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [Mouse.Hit](https://create.roblox.com/docs/reference/engine/classes/Mouse#Hit)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.Icon](https://create.roblox.com/docs/reference/engine/classes/Mouse#Icon)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.Origin](https://create.roblox.com/docs/reference/engine/classes/Mouse#Origin)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.Target](https://create.roblox.com/docs/reference/engine/classes/Mouse#Target)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.TargetFilter](https://create.roblox.com/docs/reference/engine/classes/Mouse#TargetFilter)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.TargetSurface](https://create.roblox.com/docs/reference/engine/classes/Mouse#TargetSurface)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.UnitRay](https://create.roblox.com/docs/reference/engine/classes/Mouse#UnitRay)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.ViewSizeX](https://create.roblox.com/docs/reference/engine/classes/Mouse#ViewSizeX)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.ViewSizeY](https://create.roblox.com/docs/reference/engine/classes/Mouse#ViewSizeY)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.X](https://create.roblox.com/docs/reference/engine/classes/Mouse#X)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.Y](https://create.roblox.com/docs/reference/engine/classes/Mouse#Y)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.hit](https://create.roblox.com/docs/reference/engine/classes/Mouse#hit)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [Mouse.target](https://create.roblox.com/docs/reference/engine/classes/Mouse#target)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.Button1Down](https://create.roblox.com/docs/reference/engine/classes/Mouse#Button1Down)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.Button1Up](https://create.roblox.com/docs/reference/engine/classes/Mouse#Button1Up)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.Button2Down](https://create.roblox.com/docs/reference/engine/classes/Mouse#Button2Down)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.Button2Up](https://create.roblox.com/docs/reference/engine/classes/Mouse#Button2Up)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.Idle](https://create.roblox.com/docs/reference/engine/classes/Mouse#Idle)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.KeyDown](https://create.roblox.com/docs/reference/engine/classes/Mouse#KeyDown)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.KeyUp](https://create.roblox.com/docs/reference/engine/classes/Mouse#KeyUp)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.Move](https://create.roblox.com/docs/reference/engine/classes/Mouse#Move)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.WheelBackward](https://create.roblox.com/docs/reference/engine/classes/Mouse#WheelBackward)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.WheelForward](https://create.roblox.com/docs/reference/engine/classes/Mouse#WheelForward)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [Mouse.keyDown](https://create.roblox.com/docs/reference/engine/classes/Mouse#keyDown)
    from: {🚧Input}
    to: {🚧None}
  * Removed Property Mouse.IconContent
* Update Class [PluginMouse](https://create.roblox.com/docs/reference/engine/classes/PluginMouse) [⬆️Extends: Mouse] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the parameters of Event [PluginMouse.DragEnter](https://create.roblox.com/docs/reference/engine/classes/PluginMouse#DragEnter)
    from: (instances: Instances)
    to: (instances: Objects)
  * Changed the capabilities of Event [PluginMouse.DragEnter](https://create.roblox.com/docs/reference/engine/classes/PluginMouse#DragEnter)
    from: {🚧Input}
    to: {🚧None}
* Update Class [MouseService](https://create.roblox.com/docs/reference/engine/classes/MouseService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Event MouseService.MouseEnterStudioViewport
  * Removed Event MouseService.MouseLeaveStudioViewport
* Update Class [NetworkMarker](https://create.roblox.com/docs/reference/engine/classes/NetworkMarker) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the capabilities of Event [NetworkMarker.Received](https://create.roblox.com/docs/reference/engine/classes/NetworkMarker#Received)
    from: {🚧Network}
    to: {🚧None}
* Update Class [NetworkPeer](https://create.roblox.com/docs/reference/engine/classes/NetworkPeer) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the return-type of Function [NetworkPeer.SetOutgoingKBPSLimit](https://create.roblox.com/docs/reference/engine/classes/NetworkPeer#SetOutgoingKBPSLimit) from null to void
  * Removed Function NetworkPeer.InitializeRemoteAllowList
* Update Class [NetworkClient](https://create.roblox.com/docs/reference/engine/classes/NetworkClient) [⬆️Extends: NetworkPeer] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Event [NetworkClient.ConnectionAccepted](https://create.roblox.com/docs/reference/engine/classes/NetworkClient#ConnectionAccepted)
    from: {🚧Network}
    to: {🚧None}
  * Changed the parameters of Event [NetworkClient.ConnectionFailed](https://create.roblox.com/docs/reference/engine/classes/NetworkClient#ConnectionFailed)
    from: (peer: string, code: int)
    to: (peer: string, code: int, reason: string)
  * Changed the capabilities of Event [NetworkClient.ConnectionFailed](https://create.roblox.com/docs/reference/engine/classes/NetworkClient#ConnectionFailed)
    from: {🚧Network}
    to: {🚧None}
* Update Class [NetworkServer](https://create.roblox.com/docs/reference/engine/classes/NetworkServer) [⬆️Extends: NetworkPeer] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Function [NetworkServer.EncryptStringForPlayerId](https://create.roblox.com/docs/reference/engine/classes/NetworkServer#EncryptStringForPlayerId)
    from: {🚧Network}
    to: {🚧None}
* Update Class [NetworkReplicator](https://create.roblox.com/docs/reference/engine/classes/NetworkReplicator) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Function [NetworkReplicator.GetPlayer](https://create.roblox.com/docs/reference/engine/classes/NetworkReplicator#GetPlayer)
    from: {🚧Network, Players}
    to: {🚧None}
* Update Class [ClientReplicator](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator) [⬆️Extends: NetworkReplicator] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [ClientReplicator.RequestRCCProfilerData](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator#RequestRCCProfilerData) from null to void
  * Changed the capabilities of Function [ClientReplicator.RequestRCCProfilerData](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator#RequestRCCProfilerData)
    from: {🚧Network}
    to: {🚧None}
  * Changed the return-type of Function [ClientReplicator.RequestServerStats](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator#RequestServerStats) from null to void
  * Changed the capabilities of Function [ClientReplicator.RequestServerStats](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator#RequestServerStats)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Event [ClientReplicator.RCCProfilerDataComplete](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator#RCCProfilerDataComplete)
    from: {🚧Network}
    to: {🚧None}
  * Changed the capabilities of Event [ClientReplicator.StatsReceived](https://create.roblox.com/docs/reference/engine/classes/ClientReplicator#StatsReceived)
    from: {🚧Network}
    to: {🚧None}
  * Removed Function ClientReplicator.IsStreamedOut
* Update Class [NetworkSettings](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [NetworkSettings.EmulatedTotalMemoryInMB](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#EmulatedTotalMemoryInMB)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.FreeMemoryMBytes](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#FreeMemoryMBytes)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.HttpProxyEnabled](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#HttpProxyEnabled)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.HttpProxyURL](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#HttpProxyURL)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.IncomingReplicationLag](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#IncomingReplicationLag)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.PrintJoinSizeBreakdown](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#PrintJoinSizeBreakdown)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.PrintPhysicsErrors](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#PrintPhysicsErrors)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.PrintStreamInstanceQuota](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#PrintStreamInstanceQuota)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.RandomizeJoinInstanceOrder](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#RandomizeJoinInstanceOrder)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.RenderStreamedRegions](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#RenderStreamedRegions)
    from: {🚧Read: Network}
    to: {🚧None}
  * Changed the capabilities of Property [NetworkSettings.ShowActiveAnimationAsset](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#ShowActiveAnimationAsset)
    from: {🚧Read: Network, Animation | Write: Network, Animation}
    to: {🚧None}
  * Added Property [NetworkSettings.TrackDataTypes](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#TrackDataTypes): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [NetworkSettings.TrackPhysicsDetails](https://create.roblox.com/docs/reference/engine/classes/NetworkSettings#TrackPhysicsDetails): bool [⚡ThreadSafety: ReadSafe]
  * Removed Property NetworkSettings.InboundNetworkJitterMs
  * Removed Property NetworkSettings.InboundNetworkLossPercent
  * Removed Property NetworkSettings.InboundNetworkMinDelayMs
  * Removed Property NetworkSettings.OutboundNetworkJitterMs
  * Removed Property NetworkSettings.OutboundNetworkLossPercent
  * Removed Property NetworkSettings.OutboundNetworkMinDelayMs
* Update Class [NoCollisionConstraint](https://create.roblox.com/docs/reference/engine/classes/NoCollisionConstraint) [⬆️Extends: Instance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [NoCollisionConstraint](https://create.roblox.com/docs/reference/engine/classes/NoCollisionConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [NoCollisionConstraint.Enabled](https://create.roblox.com/docs/reference/engine/classes/NoCollisionConstraint#Enabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [NoCollisionConstraint.Part0](https://create.roblox.com/docs/reference/engine/classes/NoCollisionConstraint#Part0)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [NoCollisionConstraint.Part1](https://create.roblox.com/docs/reference/engine/classes/NoCollisionConstraint#Part1)
    from: {🚧Read: Physics}
    to: {🚧None}
* Update Class [NotificationService](https://create.roblox.com/docs/reference/engine/classes/NotificationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [NotificationService.IsLuaChatEnabled](https://create.roblox.com/docs/reference/engine/classes/NotificationService#IsLuaChatEnabled)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [NotificationService.IsLuaGameDetailsEnabled](https://create.roblox.com/docs/reference/engine/classes/NotificationService#IsLuaGameDetailsEnabled)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [NotificationService.SelectedTheme](https://create.roblox.com/docs/reference/engine/classes/NotificationService#SelectedTheme)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the return-type of Function [NotificationService.ActionEnabled](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ActionEnabled) from null to void
  * Changed the capabilities of Function [NotificationService.ActionEnabled](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ActionEnabled)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [NotificationService.ActionTaken](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ActionTaken) from null to void
  * Changed the capabilities of Function [NotificationService.ActionTaken](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ActionTaken)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [NotificationService.CancelAllNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#CancelAllNotification) from null to void
  * Changed the capabilities of Function [NotificationService.CancelAllNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#CancelAllNotification)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [NotificationService.CancelNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#CancelNotification) from null to void
  * Changed the capabilities of Function [NotificationService.CancelNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#CancelNotification)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [NotificationService.ScheduleNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ScheduleNotification) from null to void
  * Changed the capabilities of Function [NotificationService.ScheduleNotification](https://create.roblox.com/docs/reference/engine/classes/NotificationService#ScheduleNotification)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [NotificationService.SwitchedToAppShellFeature](https://create.roblox.com/docs/reference/engine/classes/NotificationService#SwitchedToAppShellFeature) from null to void
  * Changed the capabilities of Function [NotificationService.SwitchedToAppShellFeature](https://create.roblox.com/docs/reference/engine/classes/NotificationService#SwitchedToAppShellFeature)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [NotificationService.GetScheduledNotifications](https://create.roblox.com/docs/reference/engine/classes/NotificationService#GetScheduledNotifications)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [NotificationService.Roblox17sConnectionChanged](https://create.roblox.com/docs/reference/engine/classes/NotificationService#Roblox17sConnectionChanged)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [NotificationService.Roblox17sEventReceived](https://create.roblox.com/docs/reference/engine/classes/NotificationService#Roblox17sEventReceived)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [NotificationService.RobloxConnectionChanged](https://create.roblox.com/docs/reference/engine/classes/NotificationService#RobloxConnectionChanged)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [NotificationService.RobloxEventReceived](https://create.roblox.com/docs/reference/engine/classes/NotificationService#RobloxEventReceived)
    from: {🚧Players}
    to: {🚧None}
  * Removed Property NotificationService.IsConnected
  * Removed Function NotificationService.SubscribeToRccEventNamespace
  * Removed Event NotificationService.RccConnectionChanged
  * Removed Event NotificationService.RccEventReceived
* Update Class [PVInstance](https://create.roblox.com/docs/reference/engine/classes/PVInstance) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Added Property [PVInstance.Origin Orientation](https://create.roblox.com/docs/reference/engine/classes/PVInstance#Origin%20Orientation): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Added Property [PVInstance.Origin Position](https://create.roblox.com/docs/reference/engine/classes/PVInstance#Origin%20Position): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Added Property [PVInstance.Pivot Offset Orientation](https://create.roblox.com/docs/reference/engine/classes/PVInstance#Pivot%20Offset%20Orientation): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Added Property [PVInstance.Pivot Offset Position](https://create.roblox.com/docs/reference/engine/classes/PVInstance#Pivot%20Offset%20Position): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Changed ThreadSafety of Function [PVInstance.GetPivot](https://create.roblox.com/docs/reference/engine/classes/PVInstance#GetPivot) from `Safe` to `Unsafe`
  * Changed the return-type of Function [PVInstance.PivotTo](https://create.roblox.com/docs/reference/engine/classes/PVInstance#PivotTo) from null to void
  * Removed Property PVInstance.Origin
  * Removed Property PVInstance.Pivot Offset
* Update Class [BasePart](https://create.roblox.com/docs/reference/engine/classes/BasePart) [⬆️Extends: PVInstance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the serialization of Property [BasePart.Orientation](https://create.roblox.com/docs/reference/engine/classes/BasePart#Orientation)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the serialization of Property [BasePart.Position](https://create.roblox.com/docs/reference/engine/classes/BasePart#Position)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the return-type of Function [BasePart.ApplyAngularImpulse](https://create.roblox.com/docs/reference/engine/classes/BasePart#ApplyAngularImpulse) from null to void
  * Changed the return-type of Function [BasePart.ApplyImpulse](https://create.roblox.com/docs/reference/engine/classes/BasePart#ApplyImpulse) from null to void
  * Changed the return-type of Function [BasePart.ApplyImpulseAtPosition](https://create.roblox.com/docs/reference/engine/classes/BasePart#ApplyImpulseAtPosition) from null to void
  * Changed the return-type of Function [BasePart.BreakJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#BreakJoints) from null to void
  * Changed the parameters of Function [BasePart.CanCollideWith](https://create.roblox.com/docs/reference/engine/classes/BasePart#CanCollideWith)
    from: (part: BasePart)
    to: (part: Instance)
  * Changed ThreadSafety of Function [BasePart.CanCollideWith](https://create.roblox.com/docs/reference/engine/classes/BasePart#CanCollideWith) from `Safe` to `Unsafe`
  * Changed the return-type of Function [BasePart.GetConnectedParts](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetConnectedParts) from Instances to Objects [⚡ThreadSafety: Safe]
  * Changed the return-type of Function [BasePart.GetJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetJoints) from Instances to Objects [⚡ThreadSafety: Safe]
  * Changed ThreadSafety of Function [BasePart.GetNetworkOwner](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetNetworkOwner) from `Safe` to `Unsafe`
  * Changed ThreadSafety of Function [BasePart.GetNetworkOwnershipAuto](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetNetworkOwnershipAuto) from `Safe` to `Unsafe`
  * Changed the return-type of Function [BasePart.GetTouchingParts](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetTouchingParts) from Instances to Objects
  * Changed ThreadSafety of Function [BasePart.GetVelocityAtPosition](https://create.roblox.com/docs/reference/engine/classes/BasePart#GetVelocityAtPosition) from `Safe` to `Unsafe`
  * Changed the return-type of Function [BasePart.MakeJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#MakeJoints) from null to void
  * Changed the return-type of Function [BasePart.SetNetworkOwner](https://create.roblox.com/docs/reference/engine/classes/BasePart#SetNetworkOwner) from null to void
  * Changed the return-type of Function [BasePart.SetNetworkOwnershipAuto](https://create.roblox.com/docs/reference/engine/classes/BasePart#SetNetworkOwnershipAuto) from null to void
  * Changed the return-type of Function [BasePart.breakJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#breakJoints) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [BasePart.makeJoints](https://create.roblox.com/docs/reference/engine/classes/BasePart#makeJoints) from null to void [🏷️ Deprecated]
  * Changed the parameters of Function [BasePart.SubtractAsync](https://create.roblox.com/docs/reference/engine/classes/BasePart#SubtractAsync)
    from: (parts: Instances, collisionfidelity: CollisionFidelity = Default, renderFidelity: RenderFidelity = Automatic)
    to: (parts: Objects, collisionfidelity: CollisionFidelity = Default, renderFidelity: RenderFidelity = Automatic)
  * Changed the capabilities of Function [BasePart.SubtractAsync](https://create.roblox.com/docs/reference/engine/classes/BasePart#SubtractAsync)
    from: {🚧CSG}
    to: {🚧None}
  * Changed the parameters of Function [BasePart.UnionAsync](https://create.roblox.com/docs/reference/engine/classes/BasePart#UnionAsync)
    from: (parts: Instances, collisionfidelity: CollisionFidelity = Default, renderFidelity: RenderFidelity = Automatic)
    to: (parts: Objects, collisionfidelity: CollisionFidelity = Default, renderFidelity: RenderFidelity = Automatic)
  * Changed the capabilities of Function [BasePart.UnionAsync](https://create.roblox.com/docs/reference/engine/classes/BasePart#UnionAsync)
    from: {🚧CSG}
    to: {🚧None}
  * Removed Property BasePart.AudioCanCollide
  * Removed Property BasePart.CollisionGroup
  * Removed Property BasePart.CurrentPhysicalProperties
  * Removed Property BasePart.EnableFluidForces
  * Removed Property BasePart.ExtentsCFrame
  * Removed Property BasePart.ExtentsSize
  * Removed Property BasePart.MaterialVariant
  * Removed Function BasePart.AngularAccelerationToTorque
  * Removed Function BasePart.GetClosestPointOnSurface
  * Removed Function BasePart.GetNoCollisionConstraints
  * Removed Function BasePart.GetPhysicsCost
  * Removed Function BasePart.TorqueToAngularAcceleration
  * Removed Function BasePart.IntersectAsync
* Update Class [Part](https://create.roblox.com/docs/reference/engine/classes/Part) [⬆️Extends: FormFactorPart] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Part](https://create.roblox.com/docs/reference/engine/classes/Part) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [Part.Shape](https://create.roblox.com/docs/reference/engine/classes/Part#Shape)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [FlagStand](https://create.roblox.com/docs/reference/engine/classes/FlagStand) [⬆️Extends: Part] [🧠Memory: PhysicsParts] [🏷️ Deprecated]
  * Changed MemoryCategory of Class [FlagStand](https://create.roblox.com/docs/reference/engine/classes/FlagStand) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [FlagStand.TeamColor](https://create.roblox.com/docs/reference/engine/classes/FlagStand#TeamColor)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Event [FlagStand.FlagCaptured](https://create.roblox.com/docs/reference/engine/classes/FlagStand#FlagCaptured)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [Platform](https://create.roblox.com/docs/reference/engine/classes/Platform) [⬆️Extends: Part] [🧠Memory: PhysicsParts] [🏷️ NotCreatable]
  * Changed MemoryCategory of Class [Platform](https://create.roblox.com/docs/reference/engine/classes/Platform) from `BaseParts` to `PhysicsParts`
* Update Class [Seat](https://create.roblox.com/docs/reference/engine/classes/Seat) [⬆️Extends: Part] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Seat](https://create.roblox.com/docs/reference/engine/classes/Seat) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [Seat.Disabled](https://create.roblox.com/docs/reference/engine/classes/Seat#Disabled)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [Seat.Occupant](https://create.roblox.com/docs/reference/engine/classes/Seat#Occupant)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [Seat.Sit](https://create.roblox.com/docs/reference/engine/classes/Seat#Sit) from null to void
  * Changed the capabilities of Function [Seat.Sit](https://create.roblox.com/docs/reference/engine/classes/Seat#Sit)
    from: {🚧Basic, AvatarBehavior}
    to: {🚧None}
* Update Class [SkateboardPlatform](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform) [⬆️Extends: Part] [🧠Memory: PhysicsParts] [🏷️ Deprecated]
  * Changed MemoryCategory of Class [SkateboardPlatform](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [SkateboardPlatform.Controller](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#Controller)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SkateboardPlatform.ControllingHumanoid](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#ControllingHumanoid)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SkateboardPlatform.Steer](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#Steer)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SkateboardPlatform.StickyWheels](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#StickyWheels)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [SkateboardPlatform.Throttle](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#Throttle)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [SkateboardPlatform.ApplySpecificImpulse](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#ApplySpecificImpulse) from null to void
  * Changed the capabilities of Function [SkateboardPlatform.ApplySpecificImpulse](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#ApplySpecificImpulse)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [SkateboardPlatform.Equipped](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#Equipped)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [SkateboardPlatform.MoveStateChanged](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#MoveStateChanged)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [SkateboardPlatform.Unequipped](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#Unequipped)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [SkateboardPlatform.equipped](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#equipped)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [SkateboardPlatform.unequipped](https://create.roblox.com/docs/reference/engine/classes/SkateboardPlatform#unequipped)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [SpawnLocation](https://create.roblox.com/docs/reference/engine/classes/SpawnLocation) [⬆️Extends: Part] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [SpawnLocation](https://create.roblox.com/docs/reference/engine/classes/SpawnLocation) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [SpawnLocation.AllowTeamChangeOnTouch](https://create.roblox.com/docs/reference/engine/classes/SpawnLocation#AllowTeamChangeOnTouch)
    from: {🚧Read: Basic, Players}
    to: {🚧None}
  * Changed the capabilities of Property [SpawnLocation.Duration](https://create.roblox.com/docs/reference/engine/classes/SpawnLocation#Duration)
    from: {🚧Read: Basic, Players}
    to: {🚧None}
  * Changed the capabilities of Property [SpawnLocation.Enabled](https://create.roblox.com/docs/reference/engine/classes/SpawnLocation#Enabled)
    from: {🚧Read: Basic, Players}
    to: {🚧None}
  * Changed the capabilities of Property [SpawnLocation.Neutral](https://create.roblox.com/docs/reference/engine/classes/SpawnLocation#Neutral)
    from: {🚧Read: Basic, Players}
    to: {🚧None}
  * Changed the capabilities of Property [SpawnLocation.TeamColor](https://create.roblox.com/docs/reference/engine/classes/SpawnLocation#TeamColor)
    from: {🚧Read: Basic, Players}
    to: {🚧None}
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [Terrain.Decoration](https://create.roblox.com/docs/reference/engine/classes/Terrain#Decoration)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.IsSmooth](https://create.roblox.com/docs/reference/engine/classes/Terrain#IsSmooth)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.LastUsedModificationMethod](https://create.roblox.com/docs/reference/engine/classes/Terrain#LastUsedModificationMethod)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.MaterialColors](https://create.roblox.com/docs/reference/engine/classes/Terrain#MaterialColors)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.MaxExtents](https://create.roblox.com/docs/reference/engine/classes/Terrain#MaxExtents)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.WaterColor](https://create.roblox.com/docs/reference/engine/classes/Terrain#WaterColor)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.WaterReflectance](https://create.roblox.com/docs/reference/engine/classes/Terrain#WaterReflectance)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.WaterTransparency](https://create.roblox.com/docs/reference/engine/classes/Terrain#WaterTransparency)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.WaterWaveSize](https://create.roblox.com/docs/reference/engine/classes/Terrain#WaterWaveSize)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Terrain.WaterWaveSpeed](https://create.roblox.com/docs/reference/engine/classes/Terrain#WaterWaveSpeed)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.AutowedgeCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#AutowedgeCell)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.AutowedgeCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#AutowedgeCells) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Terrain.AutowedgeCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#AutowedgeCells)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.CellCenterToWorld](https://create.roblox.com/docs/reference/engine/classes/Terrain#CellCenterToWorld)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.CellCornerToWorld](https://create.roblox.com/docs/reference/engine/classes/Terrain#CellCornerToWorld)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.Clear](https://create.roblox.com/docs/reference/engine/classes/Terrain#Clear) from null to void
  * Changed the capabilities of Function [Terrain.Clear](https://create.roblox.com/docs/reference/engine/classes/Terrain#Clear)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.ConvertToSmooth](https://create.roblox.com/docs/reference/engine/classes/Terrain#ConvertToSmooth) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Terrain.ConvertToSmooth](https://create.roblox.com/docs/reference/engine/classes/Terrain#ConvertToSmooth)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.CopyRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#CopyRegion) from TerrainRegion to Instance
  * Changed the capabilities of Function [Terrain.CopyRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#CopyRegion)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.CountCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#CountCells)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.FillBall](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillBall) from null to void
  * Changed the capabilities of Function [Terrain.FillBall](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillBall)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.FillBlock](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillBlock) from null to void
  * Changed the capabilities of Function [Terrain.FillBlock](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillBlock)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.FillCylinder](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillCylinder) from null to void
  * Changed the capabilities of Function [Terrain.FillCylinder](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillCylinder)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.FillRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillRegion) from null to void
  * Changed the capabilities of Function [Terrain.FillRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillRegion)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.FillWedge](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillWedge) from null to void
  * Changed the capabilities of Function [Terrain.FillWedge](https://create.roblox.com/docs/reference/engine/classes/Terrain#FillWedge)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.GetCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#GetCell)
    from: {🚧Environment}
    to: {🚧None}
  * Changed ThreadSafety of Function [Terrain.GetMaterialColor](https://create.roblox.com/docs/reference/engine/classes/Terrain#GetMaterialColor) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Terrain.GetMaterialColor](https://create.roblox.com/docs/reference/engine/classes/Terrain#GetMaterialColor)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.GetWaterCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#GetWaterCell)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.PasteRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#PasteRegion) from null to void
  * Changed the parameters of Function [Terrain.PasteRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#PasteRegion)
    from: (region: TerrainRegion, corner: Vector3int16, pasteEmptyCells: bool)
    to: (region: Instance, corner: Vector3int16, pasteEmptyCells: bool)
  * Changed the capabilities of Function [Terrain.PasteRegion](https://create.roblox.com/docs/reference/engine/classes/Terrain#PasteRegion)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.ReadVoxels](https://create.roblox.com/docs/reference/engine/classes/Terrain#ReadVoxels)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.ReplaceMaterial](https://create.roblox.com/docs/reference/engine/classes/Terrain#ReplaceMaterial) from null to void
  * Changed the capabilities of Function [Terrain.ReplaceMaterial](https://create.roblox.com/docs/reference/engine/classes/Terrain#ReplaceMaterial)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.SetCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetCell) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Terrain.SetCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetCell)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.SetCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetCells) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Terrain.SetCells](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetCells)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.SetMaterialColor](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetMaterialColor) from null to void
  * Changed the capabilities of Function [Terrain.SetMaterialColor](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetMaterialColor)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.SetWaterCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetWaterCell) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Terrain.SetWaterCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetWaterCell)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.WorldToCell](https://create.roblox.com/docs/reference/engine/classes/Terrain#WorldToCell)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.WorldToCellPreferEmpty](https://create.roblox.com/docs/reference/engine/classes/Terrain#WorldToCellPreferEmpty)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the capabilities of Function [Terrain.WorldToCellPreferSolid](https://create.roblox.com/docs/reference/engine/classes/Terrain#WorldToCellPreferSolid)
    from: {🚧Environment}
    to: {🚧None}
  * Changed the return-type of Function [Terrain.WriteVoxels](https://create.roblox.com/docs/reference/engine/classes/Terrain#WriteVoxels) from null to void [🏷️ CustomLuaState]
  * Changed the capabilities of Function [Terrain.WriteVoxels](https://create.roblox.com/docs/reference/engine/classes/Terrain#WriteVoxels)
    from: {🚧Environment}
    to: {🚧None}
  * Removed Property Terrain.GrassLength
  * Removed Property Terrain.SmoothVoxelsUpgraded
  * Removed Function Terrain.CanSmoothVoxelsBeUpgraded
  * Removed Function Terrain.ClearVoxelsAsync_beta
  * Removed Function Terrain.CreateVoxelBuffer_beta
  * Removed Function Terrain.FillBallSlot
  * Removed Function Terrain.FillBlockSlot
  * Removed Function Terrain.FillCylinderSlot
  * Removed Function Terrain.FillRegionSlot
  * Removed Function Terrain.FillWedgeSlot
  * Removed Function Terrain.GetMaterialSlot
  * Removed Function Terrain.GetTerrainWireframe
  * Removed Function Terrain.IterateVoxelsAsync_beta
  * Removed Function Terrain.ModifyVoxelsAsync_beta
  * Removed Function Terrain.ReadVoxelChannels
  * Removed Function Terrain.ReadVoxelsAsync_beta
  * Removed Function Terrain.ReplaceMaterialInTransform
  * Removed Function Terrain.ReplaceMaterialInTransformSubregion
  * Removed Function Terrain.ResetMaterialSlot
  * Removed Function Terrain.SetMaterialInTransform
  * Removed Function Terrain.SetMaterialInTransformSubregion
  * Removed Function Terrain.SetMaterialSlot
  * Removed Function Terrain.SmoothRegion
  * Removed Function Terrain.WriteVoxelChannels
  * Removed Function Terrain.WriteVoxelsAsync_beta
  * Removed Function Terrain.DrawBufferAsync
  * Removed Function Terrain.ReadBufferAsync
* Update Class [TriangleMeshPart](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [TriangleMeshPart.CollisionFidelity](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart#CollisionFidelity)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Removed Property TriangleMeshPart.FluidFidelity
  * Removed Property TriangleMeshPart.MeshSize
  * Removed Property TriangleMeshPart.UnscaledCofm
  * Removed Property TriangleMeshPart.UnscaledVolInertiaDiags
  * Removed Property TriangleMeshPart.UnscaledVolInertiaOffDiags
  * Removed Property TriangleMeshPart.UnscaledVolume
* Update Class [MeshPart](https://create.roblox.com/docs/reference/engine/classes/MeshPart) [⬆️Extends: TriangleMeshPart] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [MeshPart](https://create.roblox.com/docs/reference/engine/classes/MeshPart) from `BaseParts` to `PhysicsParts`
  * Changed the security of Property [MeshPart.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/MeshPart#DoubleSided)
    from: {🔒None}
    to: {🔒Read:None, Write:PluginSecurity}
  * Changed the capabilities of Property [MeshPart.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/MeshPart#DoubleSided)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [MeshPart.HasJointOffset](https://create.roblox.com/docs/reference/engine/classes/MeshPart#HasJointOffset)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [MeshPart.HasSkinnedMesh](https://create.roblox.com/docs/reference/engine/classes/MeshPart#HasSkinnedMesh)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [MeshPart.JointOffset](https://create.roblox.com/docs/reference/engine/classes/MeshPart#JointOffset)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Added Property [MeshPart.MeshID](https://create.roblox.com/docs/reference/engine/classes/MeshPart#MeshID): Content [🏷️ NotScriptable] [🏷️ Deprecated] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [MeshPart.MeshId](https://create.roblox.com/docs/reference/engine/classes/MeshPart#MeshId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Added Property [MeshPart.MeshSize](https://create.roblox.com/docs/reference/engine/classes/MeshPart#MeshSize): Vector3 [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [MeshPart.RenderFidelity](https://create.roblox.com/docs/reference/engine/classes/MeshPart#RenderFidelity)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [MeshPart.TextureID](https://create.roblox.com/docs/reference/engine/classes/MeshPart#TextureID)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [MeshPart.ApplyMesh](https://create.roblox.com/docs/reference/engine/classes/MeshPart#ApplyMesh) from null to void
  * Changed the capabilities of Function [MeshPart.ApplyMesh](https://create.roblox.com/docs/reference/engine/classes/MeshPart#ApplyMesh)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Property MeshPart.MeshContent
  * Removed Property MeshPart.TextureContent
* Update Class [PartOperation](https://create.roblox.com/docs/reference/engine/classes/PartOperation) [⬆️Extends: TriangleMeshPart] [🧠Memory: Instances]
  * Changed the capabilities of Property [PartOperation.RenderFidelity](https://create.roblox.com/docs/reference/engine/classes/PartOperation#RenderFidelity)
    from: {🚧Read: Basic, CSG}
    to: {🚧None}
  * Changed the capabilities of Property [PartOperation.SmoothingAngle](https://create.roblox.com/docs/reference/engine/classes/PartOperation#SmoothingAngle)
    from: {🚧Read: Basic, CSG}
    to: {🚧None}
  * Changed the security of Property [PartOperation.TriangleCount](https://create.roblox.com/docs/reference/engine/classes/PartOperation#TriangleCount)
    from: {🔒Read:None, Write:RobloxSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [PartOperation.TriangleCount](https://create.roblox.com/docs/reference/engine/classes/PartOperation#TriangleCount)
    from: {🚧Read: Basic, CSG}
    to: {🚧None}
  * Changed the serialization of Property [PartOperation.TriangleCount](https://create.roblox.com/docs/reference/engine/classes/PartOperation#TriangleCount)
    from: [💾|📁Serialized]
    to: [💾SaveOnly]
  * Changed the capabilities of Property [PartOperation.UsePartColor](https://create.roblox.com/docs/reference/engine/classes/PartOperation#UsePartColor)
    from: {🚧Read: Basic, CSG}
    to: {🚧None}
  * Removed Function PartOperation.SubstituteGeometry
* Update Class [TrussPart](https://create.roblox.com/docs/reference/engine/classes/TrussPart) [⬆️Extends: BasePart] [🧠Memory: Instances]
  * Changed the capabilities of Property [TrussPart.Style](https://create.roblox.com/docs/reference/engine/classes/TrussPart#Style)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [VehicleSeat](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat) [⬆️Extends: BasePart] [🧠Memory: Instances]
  * Changed the capabilities of Property [VehicleSeat.AreHingesDetected](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#AreHingesDetected)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.Disabled](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#Disabled)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.HeadsUpDisplay](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#HeadsUpDisplay)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.MaxSpeed](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#MaxSpeed)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.Occupant](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#Occupant)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.Steer](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#Steer)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.SteerFloat](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#SteerFloat)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.Throttle](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#Throttle)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.ThrottleFloat](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#ThrottleFloat)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.Torque](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#Torque)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the capabilities of Property [VehicleSeat.TurnSpeed](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#TurnSpeed)
    from: {🚧Read: Basic, AvatarBehavior}
    to: {🚧None}
  * Changed the return-type of Function [VehicleSeat.Sit](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#Sit) from null to void
  * Changed the capabilities of Function [VehicleSeat.Sit](https://create.roblox.com/docs/reference/engine/classes/VehicleSeat#Sit)
    from: {🚧Basic, AvatarBehavior}
    to: {🚧None}
* Update Class [Model](https://create.roblox.com/docs/reference/engine/classes/Model) [⬆️Extends: PVInstance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Model](https://create.roblox.com/docs/reference/engine/classes/Model) from `BaseParts` to `PhysicsParts`
  * Added Property [Model.World Pivot Orientation](https://create.roblox.com/docs/reference/engine/classes/Model#World%20Pivot%20Orientation): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Added Property [Model.World Pivot Position](https://create.roblox.com/docs/reference/engine/classes/Model#World%20Pivot%20Position): Vector3 [🏷️ NotReplicated] [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Changed the return-type of Function [Model.BreakJoints](https://create.roblox.com/docs/reference/engine/classes/Model#BreakJoints) from null to void
  * Changed the return-type of Function [Model.GetBoundingBox](https://create.roblox.com/docs/reference/engine/classes/Model#GetBoundingBox) from any to Tuple
  * Changed the return-type of Function [Model.MakeJoints](https://create.roblox.com/docs/reference/engine/classes/Model#MakeJoints) from null to void
  * Changed the return-type of Function [Model.MoveTo](https://create.roblox.com/docs/reference/engine/classes/Model#MoveTo) from null to void
  * Changed the return-type of Function [Model.ResetOrientationToIdentity](https://create.roblox.com/docs/reference/engine/classes/Model#ResetOrientationToIdentity) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Model.SetIdentityOrientation](https://create.roblox.com/docs/reference/engine/classes/Model#SetIdentityOrientation) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Model.SetPrimaryPartCFrame](https://create.roblox.com/docs/reference/engine/classes/Model#SetPrimaryPartCFrame) from null to void
  * Changed the return-type of Function [Model.TranslateBy](https://create.roblox.com/docs/reference/engine/classes/Model#TranslateBy) from null to void
  * Changed the return-type of Function [Model.breakJoints](https://create.roblox.com/docs/reference/engine/classes/Model#breakJoints) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Model.makeJoints](https://create.roblox.com/docs/reference/engine/classes/Model#makeJoints) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Model.move](https://create.roblox.com/docs/reference/engine/classes/Model#move) from null to void [🏷️ Deprecated]
  * Changed the return-type of Function [Model.moveTo](https://create.roblox.com/docs/reference/engine/classes/Model#moveTo) from null to void [🏷️ Deprecated]
  * Removed Property Model.ModelStreamingMode
  * Removed Property Model.Scale
  * Removed Function Model.AddPersistentPlayer
  * Removed Function Model.GetPersistentPlayers
  * Removed Function Model.GetScale
  * Removed Function Model.RemovePersistentPlayer
  * Removed Function Model.ScaleTo
* Update Class [Actor](https://create.roblox.com/docs/reference/engine/classes/Actor) [⬆️Extends: Model] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [Actor](https://create.roblox.com/docs/reference/engine/classes/Actor) from `BaseParts` to `PhysicsParts`
  * Removed Function Actor.BindToMessage
  * Removed Function Actor.BindToMessageParallel
  * Removed Function Actor.SendMessage
* Update Class [Status](https://create.roblox.com/docs/reference/engine/classes/Status) [⬆️Extends: Model] [🧠Memory: PhysicsParts] [🏷️ NotCreatable] [🏷️ Deprecated]
  * Changed MemoryCategory of Class [Status](https://create.roblox.com/docs/reference/engine/classes/Status) from `BaseParts` to `PhysicsParts`
* Update Class [WorldRoot](https://create.roblox.com/docs/reference/engine/classes/WorldRoot) [⬆️Extends: Model] [🧠Memory: PhysicsParts] [🏷️ NotCreatable]
  * Changed MemoryCategory of Class [WorldRoot](https://create.roblox.com/docs/reference/engine/classes/WorldRoot) from `BaseParts` to `PhysicsParts`
  * Changed the parameters of Function [WorldRoot.ArePartsTouchingOthers](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#ArePartsTouchingOthers)
    from: (partList: Instances, overlapIgnored: float = 0.000199999995)
    to: (partList: Objects, overlapIgnored: float = 0.000199999995)
  * Changed the return-type of Function [WorldRoot.BulkMoveTo](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#BulkMoveTo) from null to void
  * Changed the parameters of Function [WorldRoot.BulkMoveTo](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#BulkMoveTo)
    from: (partList: Instances, cframeList: Array, eventMode: BulkMoveMode = FireAllEvents)
    to: (partList: Objects, cframeList: Array, eventMode: BulkMoveMode = FireAllEvents)
  * Changed the parameters of Function [WorldRoot.FindPartOnRayWithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartOnRayWithIgnoreList)
    from: (ray: Ray, ignoreDescendantsTable: Instances, terrainCellsAreCubes: bool = false, ignoreWater: bool = false)
    to: (ray: Ray, ignoreDescendantsTable: Objects, terrainCellsAreCubes: bool = false, ignoreWater: bool = false)
  * Changed the parameters of Function [WorldRoot.FindPartOnRayWithWhitelist](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartOnRayWithWhitelist)
    from: (ray: Ray, whitelistDescendantsTable: Instances, ignoreWater: bool = false)
    to: (ray: Ray, whitelistDescendantsTable: Objects, ignoreWater: bool = false)
  * Changed the return-type of Function [WorldRoot.FindPartsInRegion3](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3) from Instances to Objects [⚡ThreadSafety: Safe]
  * Changed ThreadSafety of Function [WorldRoot.FindPartsInRegion3](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3) from `Unsafe` to `Safe`
  * Changed the return-type of Function [WorldRoot.FindPartsInRegion3WithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithIgnoreList) from Instances to Objects
  * Changed the parameters of Function [WorldRoot.FindPartsInRegion3WithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithIgnoreList)
    from: (region: Region3, ignoreDescendantsTable: Instances, maxParts: int = 20)
    to: (region: Region3, ignoreDescendantsTable: Objects, maxParts: int = 20)
  * Changed the return-type of Function [WorldRoot.FindPartsInRegion3WithWhiteList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithWhiteList) from Instances to Objects
  * Changed the parameters of Function [WorldRoot.FindPartsInRegion3WithWhiteList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#FindPartsInRegion3WithWhiteList)
    from: (region: Region3, whitelistDescendantsTable: Instances, maxParts: int = 20)
    to: (region: Region3, whitelistDescendantsTable: Objects, maxParts: int = 20)
  * Changed the return-type of Function [WorldRoot.GetPartBoundsInBox](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox) from Instances to Objects
  * Changed the parameters of Function [WorldRoot.GetPartBoundsInBox](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox)
    from: (cframe: CFrame, size: Vector3, overlapParams: OverlapParams = OverlapParams{MaxParts=0, Tolerance=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (cframe: CFrame, size: Vector3, overlapParams: OverlapParams = OverlapParams{MaxParts=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed ThreadSafety of Function [WorldRoot.GetPartBoundsInBox](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInBox) from `Safe` to `Unsafe`
  * Changed the return-type of Function [WorldRoot.GetPartBoundsInRadius](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInRadius) from Instances to Objects
  * Changed the parameters of Function [WorldRoot.GetPartBoundsInRadius](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInRadius)
    from: (position: Vector3, radius: float, overlapParams: OverlapParams = OverlapParams{MaxParts=0, Tolerance=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (position: Vector3, radius: float, overlapParams: OverlapParams = OverlapParams{MaxParts=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed ThreadSafety of Function [WorldRoot.GetPartBoundsInRadius](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartBoundsInRadius) from `Safe` to `Unsafe`
  * Changed the return-type of Function [WorldRoot.GetPartsInPart](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartsInPart) from Instances to Objects
  * Changed the parameters of Function [WorldRoot.GetPartsInPart](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartsInPart)
    from: (part: BasePart, overlapParams: OverlapParams = OverlapParams{MaxParts=0, Tolerance=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (part: BasePart, overlapParams: OverlapParams = OverlapParams{MaxParts=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed ThreadSafety of Function [WorldRoot.GetPartsInPart](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetPartsInPart) from `Safe` to `Unsafe`
  * Changed the return-type of Function [WorldRoot.IKMoveTo](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#IKMoveTo) from null to void
  * Changed the parameters of Function [WorldRoot.IsRegion3EmptyWithIgnoreList](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#IsRegion3EmptyWithIgnoreList)
    from: (region: Region3, ignoreDescendentsTable: Instances)
    to: (region: Region3, ignoreDescendentsTable: Objects)
  * Changed the return-type of Function [WorldRoot.Raycast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Raycast) from RaycastResult? to RaycastResult [⚡ThreadSafety: Safe]
  * Changed the parameters of Function [WorldRoot.Raycast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Raycast)
    from: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed the return-type of Function [WorldRoot.SetInsertPoint](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#SetInsertPoint) from null to void
  * Changed the parameters of Function [WorldRoot.SetInsertPoint](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#SetInsertPoint)
    from: (point: Vector3)
    to: (point: Vector3, ignoreGrid: bool = false)
  * Changed the return-type of Function [WorldRoot.findPartsInRegion3](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#findPartsInRegion3) from Instances to Objects [🏷️ Deprecated]
  * Removed Property WorldRoot.PhysicsStepTime
  * Removed Function WorldRoot.Blockcast
  * Removed Function WorldRoot.CacheCurrentTerrain
  * Removed Function WorldRoot.ClearCachedTerrain
  * Removed Function WorldRoot.GetAwakeContactNormals
  * Removed Function WorldRoot.GetAwakeContactParts
  * Removed Function WorldRoot.GetAwakeContactPositions
  * Removed Function WorldRoot.GetAwakeRootParts
  * Removed Function WorldRoot.RaycastCachedTerrain
  * Removed Function WorldRoot.Shapecast
  * Removed Function WorldRoot.Spherecast
  * Removed Function WorldRoot.StepPhysics
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: PhysicsParts] [🏷️ NotCreatable] [🏷️ Service]
  * Changed MemoryCategory of Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [Workspace.AllowThirdPartySales](https://create.roblox.com/docs/reference/engine/classes/Workspace#AllowThirdPartySales)
    from: {🚧Read: Monetization | Write: Monetization}
    to: {🚧None}
  * Added Property [Workspace.AnimationWeightedBlendFix](https://create.roblox.com/docs/reference/engine/classes/Workspace#AnimationWeightedBlendFix): NewAnimationRuntimeSetting [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [Workspace.ClientAnimatorThrottling](https://create.roblox.com/docs/reference/engine/classes/Workspace#ClientAnimatorThrottling)
    from: {🚧Read: Animation | Write: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [Workspace.CurrentCamera](https://create.roblox.com/docs/reference/engine/classes/Workspace#CurrentCamera)
    from: {🚧Read: Basic | Write: Basic, Input}
    to: {🚧None}
  * Changed the capabilities of Property [Workspace.DistributedGameTime](https://create.roblox.com/docs/reference/engine/classes/Workspace#DistributedGameTime)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Workspace.FallenPartsDestroyHeight](https://create.roblox.com/docs/reference/engine/classes/Workspace#FallenPartsDestroyHeight)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Workspace.FilteringEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#FilteringEnabled)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Workspace.Gravity](https://create.roblox.com/docs/reference/engine/classes/Workspace#Gravity)
    from: {🚧Read: Basic | Write: Basic, Physics}
    to: {🚧None}
  * Added Property [Workspace.HumanoidOnlySetCollisionsOnStateChange](https://create.roblox.com/docs/reference/engine/classes/Workspace#HumanoidOnlySetCollisionsOnStateChange): HumanoidOnlySetCollisionsOnStateChange [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [Workspace.InterpolationThrottling](https://create.roblox.com/docs/reference/engine/classes/Workspace#InterpolationThrottling)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the serialization of Property [Workspace.InterpolationThrottling](https://create.roblox.com/docs/reference/engine/classes/Workspace#InterpolationThrottling)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Added Property [Workspace.PhysicsSimulationRate](https://create.roblox.com/docs/reference/engine/classes/Workspace#PhysicsSimulationRate): PhysicsSimulationRate [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Changed the serialization of Property [Workspace.SignalBehavior](https://create.roblox.com/docs/reference/engine/classes/Workspace#SignalBehavior)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Added Property [Workspace.StreamingPauseMode](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamingPauseMode): StreamingPauseMode [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Changed the return-type of Function [Workspace.BreakJoints](https://create.roblox.com/docs/reference/engine/classes/Workspace#BreakJoints) from null to void
  * Changed the parameters of Function [Workspace.BreakJoints](https://create.roblox.com/docs/reference/engine/classes/Workspace#BreakJoints)
    from: (objects: Instances)
    to: (objects: Objects)
  * Changed ThreadSafety of Function [Workspace.GetNumAwakeParts](https://create.roblox.com/docs/reference/engine/classes/Workspace#GetNumAwakeParts) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Workspace.GetNumAwakeParts](https://create.roblox.com/docs/reference/engine/classes/Workspace#GetNumAwakeParts)
    from: {🚧Basic}
    to: {🚧None}
  * Changed ThreadSafety of Function [Workspace.GetPhysicsThrottling](https://create.roblox.com/docs/reference/engine/classes/Workspace#GetPhysicsThrottling) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Workspace.GetPhysicsThrottling](https://create.roblox.com/docs/reference/engine/classes/Workspace#GetPhysicsThrottling)
    from: {🚧Basic}
    to: {🚧None}
  * Changed ThreadSafety of Function [Workspace.GetRealPhysicsFPS](https://create.roblox.com/docs/reference/engine/classes/Workspace#GetRealPhysicsFPS) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Workspace.GetRealPhysicsFPS](https://create.roblox.com/docs/reference/engine/classes/Workspace#GetRealPhysicsFPS)
    from: {🚧Basic}
    to: {🚧None}
  * Changed ThreadSafety of Function [Workspace.GetServerTimeNow](https://create.roblox.com/docs/reference/engine/classes/Workspace#GetServerTimeNow) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Workspace.GetServerTimeNow](https://create.roblox.com/docs/reference/engine/classes/Workspace#GetServerTimeNow)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Workspace.JoinToOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#JoinToOutsiders) from null to void
  * Changed the parameters of Function [Workspace.JoinToOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#JoinToOutsiders)
    from: (objects: Instances, jointType: JointCreationMode)
    to: (objects: Objects, jointType: JointCreationMode)
  * Changed the capabilities of Function [Workspace.JoinToOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#JoinToOutsiders)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [Workspace.MakeJoints](https://create.roblox.com/docs/reference/engine/classes/Workspace#MakeJoints) from null to void
  * Changed the parameters of Function [Workspace.MakeJoints](https://create.roblox.com/docs/reference/engine/classes/Workspace#MakeJoints)
    from: (objects: Instances)
    to: (objects: Objects)
  * Changed the capabilities of Function [Workspace.PGSIsEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#PGSIsEnabled)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Workspace.SetMeshPartHeadsAndAccessories](https://create.roblox.com/docs/reference/engine/classes/Workspace#SetMeshPartHeadsAndAccessories) from null to void
  * Changed the return-type of Function [Workspace.SetPhysicsThrottleEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#SetPhysicsThrottleEnabled) from null to void
  * Changed the return-type of Function [Workspace.UnjoinFromOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#UnjoinFromOutsiders) from null to void
  * Changed the parameters of Function [Workspace.UnjoinFromOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#UnjoinFromOutsiders)
    from: (objects: Instances)
    to: (objects: Objects)
  * Changed the capabilities of Function [Workspace.UnjoinFromOutsiders](https://create.roblox.com/docs/reference/engine/classes/Workspace#UnjoinFromOutsiders)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [Workspace.ZoomToExtents](https://create.roblox.com/docs/reference/engine/classes/Workspace#ZoomToExtents) from null to void
  * Removed Property Workspace.AirDensity
  * Removed Property Workspace.AirTurbulenceIntensity
  * Removed Property Workspace.AuthorityMode
  * Removed Property Workspace.AvatarUnificationMode
  * Removed Property Workspace.EnableSLIMAvatars
  * Removed Property Workspace.FallHeightEnabled
  * Removed Property Workspace.FluidForces
  * Removed Property Workspace.GlobalWind
  * Removed Property Workspace.IKControlConstraintSupport
  * Removed Property Workspace.ImprovedAnimationConstraint
  * Removed Property Workspace.ImprovedPhysicsReplication
  * Removed Property Workspace.InsertPoint
  * Removed Property Workspace.LayeredClothingCacheOptimizations
  * Removed Property Workspace.LuauTypeCheckMode
  * Removed Property Workspace.MeshStreamingAndImprovedLods
  * Removed Property Workspace.ModelStreamingBehavior
  * Removed Property Workspace.NextGenerationReplication
  * Removed Property Workspace.NextGenerationReplicationAlias
  * Removed Property Workspace.PathfindingUseImprovedSearch
  * Removed Property Workspace.PlayerCharacterDestroyBehavior
  * Removed Property Workspace.PlayerScriptsUseInputActionSystem
  * Removed Property Workspace.PlayerScriptsUseInputActionSystemAlias
  * Removed Property Workspace.PredictiveStreamingMode
  * Removed Property Workspace.PrimalPhysicsSolver
  * Removed Property Workspace.RejectCharacterDeletions
  * Removed Property Workspace.RenderingCacheOptimizations
  * Removed Property Workspace.ReplicateInstanceDestroySetting
  * Removed Property Workspace.Retargeting
  * Removed Property Workspace.SandboxedInstanceMode
  * Removed Property Workspace.SignalBehaviorAlias
  * Removed Property Workspace.StreamingEnabledAlias
  * Removed Property Workspace.StreamingIntegrityMode
  * Removed Property Workspace.TouchEventsUseCollisionGroups
  * Removed Property Workspace.UseFixedSimulation
  * Removed Property Workspace.UseFixedSimulationAlias
  * Removed Property Workspace.UseNewLuauTypeSolver
  * Removed Property Workspace.ValidateEnabledProximityPrompt
  * Removed Function Workspace.ApplyRecommendedStreamingSettings
  * Removed Function Workspace.SetAvatarUnificationMode
  * Removed Event Workspace.PersistentLoaded
* Update Class [WorldModel](https://create.roblox.com/docs/reference/engine/classes/WorldModel) [⬆️Extends: WorldRoot] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [WorldModel](https://create.roblox.com/docs/reference/engine/classes/WorldModel) from `BaseParts` to `PhysicsParts`
  * Removed Property WorldModel.UseWorkspaceCollisionGroups
* Update Class [PackageLink](https://create.roblox.com/docs/reference/engine/classes/PackageLink) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the security of Property [PackageLink.AutoUpdate](https://create.roblox.com/docs/reference/engine/classes/PackageLink#AutoUpdate)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [PackageLink.AutoUpdate](https://create.roblox.com/docs/reference/engine/classes/PackageLink#AutoUpdate)
    from: {🚧Read: AssetRead}
    to: {🚧None}
  * Changed the capabilities of Property [PackageLink.Creator](https://create.roblox.com/docs/reference/engine/classes/PackageLink#Creator)
    from: {🚧Read: AssetRead | Write: AssetRead}
    to: {🚧None}
  * Changed the capabilities of Property [PackageLink.PackageAssetName](https://create.roblox.com/docs/reference/engine/classes/PackageLink#PackageAssetName)
    from: {🚧Read: AssetRead | Write: AssetRead}
    to: {🚧None}
  * Changed the capabilities of Property [PackageLink.PackageId](https://create.roblox.com/docs/reference/engine/classes/PackageLink#PackageId)
    from: {🚧Read: AssetRead | Write: AssetRead}
    to: {🚧None}
  * Changed the capabilities of Property [PackageLink.PermissionLevel](https://create.roblox.com/docs/reference/engine/classes/PackageLink#PermissionLevel)
    from: {🚧Read: AssetRead | Write: AssetRead}
    to: {🚧None}
  * Changed the capabilities of Property [PackageLink.Status](https://create.roblox.com/docs/reference/engine/classes/PackageLink#Status)
    from: {🚧Read: AssetRead}
    to: {🚧None}
  * Changed the capabilities of Property [PackageLink.VersionNumber](https://create.roblox.com/docs/reference/engine/classes/PackageLink#VersionNumber)
    from: {🚧Read: AssetRead}
    to: {🚧None}
  * Removed Property PackageLink.DefaultName
  * Removed Property PackageLink.HasNewVersion
  * Removed Property PackageLink.ModifiedState
  * Removed Property PackageLink.PackageContent
  * Removed Property PackageLink.SerializedDefaultAttributes
* Update Class [PackageService](https://create.roblox.com/docs/reference/engine/classes/PackageService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function PackageService.UpdateAsync
* Update Class [Pages](https://create.roblox.com/docs/reference/engine/classes/Pages) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [Pages.AdvanceToNextPageAsync](https://create.roblox.com/docs/reference/engine/classes/Pages#AdvanceToNextPageAsync) from null to void [🏷️ Yields]
* Update Class [DataStoreKeyPages](https://create.roblox.com/docs/reference/engine/classes/DataStoreKeyPages) [⬆️Extends: Pages] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Property DataStoreKeyPages.Cursor
* Update Class [DataStoreListingPages](https://create.roblox.com/docs/reference/engine/classes/DataStoreListingPages) [⬆️Extends: Pages] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Property DataStoreListingPages.Cursor
* Added Class [EmotesPages](https://create.roblox.com/docs/reference/engine/classes/EmotesPages) {🔒None} [⬆️Extends: InventoryPages] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
* Update Class [ParticleEmitter](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [ParticleEmitter.Acceleration](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Acceleration)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Color](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Color)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Drag](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Drag)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.EmissionDirection](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#EmissionDirection)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Enabled](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Enabled)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Lifetime](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Lifetime)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.LightEmission](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#LightEmission)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.LightInfluence](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#LightInfluence)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.LockedToPart](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#LockedToPart)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Orientation](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Orientation)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Rate](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Rate)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.RotSpeed](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#RotSpeed)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Rotation](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Rotation)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Size](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Size)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Speed](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Speed)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.SpreadAngle](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#SpreadAngle)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Texture](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Texture)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.TimeScale](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#TimeScale)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.Transparency](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Transparency)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.VelocityInheritance](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#VelocityInheritance)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.VelocitySpread](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#VelocitySpread)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [ParticleEmitter.ZOffset](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#ZOffset)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [ParticleEmitter.Clear](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Clear) from null to void
  * Changed the capabilities of Function [ParticleEmitter.Clear](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Clear)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [ParticleEmitter.Emit](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Emit) from null to void
  * Changed the capabilities of Function [ParticleEmitter.Emit](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter#Emit)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Property ParticleEmitter.Brightness
  * Removed Property ParticleEmitter.FlipbookBlendFrames
  * Removed Property ParticleEmitter.FlipbookFramerate
  * Removed Property ParticleEmitter.FlipbookIncompatible
  * Removed Property ParticleEmitter.FlipbookLayout
  * Removed Property ParticleEmitter.FlipbookMode
  * Removed Property ParticleEmitter.FlipbookSizeX
  * Removed Property ParticleEmitter.FlipbookSizeY
  * Removed Property ParticleEmitter.FlipbookStartRandom
  * Removed Property ParticleEmitter.LocalTransparencyModifier
  * Removed Property ParticleEmitter.Shape
  * Removed Property ParticleEmitter.ShapeInOut
  * Removed Property ParticleEmitter.ShapePartial
  * Removed Property ParticleEmitter.ShapeStyle
  * Removed Property ParticleEmitter.Squash
  * Removed Property ParticleEmitter.TextureContent
  * Removed Property ParticleEmitter.WindAffectsDrag
  * Removed Function ParticleEmitter.FastForward
* Update Class [Path](https://create.roblox.com/docs/reference/engine/classes/Path) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [Path.Status](https://create.roblox.com/docs/reference/engine/classes/Path#Status)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Path.GetPointCoordinates](https://create.roblox.com/docs/reference/engine/classes/Path#GetPointCoordinates)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Path.GetWaypoints](https://create.roblox.com/docs/reference/engine/classes/Path#GetWaypoints)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Path.CheckOcclusionAsync](https://create.roblox.com/docs/reference/engine/classes/Path#CheckOcclusionAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Path.ComputeAsync](https://create.roblox.com/docs/reference/engine/classes/Path#ComputeAsync) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [Path.ComputeAsync](https://create.roblox.com/docs/reference/engine/classes/Path#ComputeAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [Path.Blocked](https://create.roblox.com/docs/reference/engine/classes/Path#Blocked)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [Path.Unblocked](https://create.roblox.com/docs/reference/engine/classes/Path#Unblocked)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [PathfindingModifier](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [PathfindingModifier.ModifierId](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier#ModifierId): string [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [PathfindingModifier.PassThrough](https://create.roblox.com/docs/reference/engine/classes/PathfindingModifier#PassThrough)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Removed Property PathfindingModifier.Label
* Update Class [PathfindingService](https://create.roblox.com/docs/reference/engine/classes/PathfindingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [PathfindingService.EmptyCutoff](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#EmptyCutoff)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [PathfindingService.CreatePath](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#CreatePath) from Path to Instance
  * Changed the capabilities of Function [PathfindingService.CreatePath](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#CreatePath)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [PathfindingService.ComputeRawPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#ComputeRawPathAsync) from Path to Instance [🏷️ Yields] [🏷️ Deprecated]
  * Changed the capabilities of Function [PathfindingService.ComputeRawPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#ComputeRawPathAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [PathfindingService.ComputeSmoothPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#ComputeSmoothPathAsync) from Path to Instance [🏷️ Yields] [🏷️ Deprecated]
  * Changed the capabilities of Function [PathfindingService.ComputeSmoothPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#ComputeSmoothPathAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [PathfindingService.FindPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#FindPathAsync) from Path to Instance [🏷️ Yields]
  * Changed the capabilities of Function [PathfindingService.FindPathAsync](https://create.roblox.com/docs/reference/engine/classes/PathfindingService#FindPathAsync)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [PausedState](https://create.roblox.com/docs/reference/engine/classes/PausedState) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [PausedState.IsValid](https://create.roblox.com/docs/reference/engine/classes/PausedState#IsValid): bool [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [PausedState.ThreadCount](https://create.roblox.com/docs/reference/engine/classes/PausedState#ThreadCount): int [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [PausedState.GetThread](https://create.roblox.com/docs/reference/engine/classes/PausedState#GetThread) (index: int) -> Instance
  * Removed Property PausedState.AllThreadsPaused
  * Removed Property PausedState.ThreadId
* Update Class [PausedStateBreakpoint](https://create.roblox.com/docs/reference/engine/classes/PausedStateBreakpoint) [⬆️Extends: PausedState] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [PausedStateBreakpoint.BreakpointThread](https://create.roblox.com/docs/reference/engine/classes/PausedStateBreakpoint#BreakpointThread): ThreadState [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [PausedStateException](https://create.roblox.com/docs/reference/engine/classes/PausedStateException) [⬆️Extends: PausedState] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [PausedStateException.ExceptionThread](https://create.roblox.com/docs/reference/engine/classes/PausedStateException#ExceptionThread): ThreadState [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [PermissionsService](https://create.roblox.com/docs/reference/engine/classes/PermissionsService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [PermissionsService.SetPermissions](https://create.roblox.com/docs/reference/engine/classes/PermissionsService#SetPermissions) from null to void
* Update Class [PhysicsService](https://create.roblox.com/docs/reference/engine/classes/PhysicsService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Function [PhysicsService.CollisionGroupContainsPart](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#CollisionGroupContainsPart)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [PhysicsService.CollisionGroupSetCollidable](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#CollisionGroupSetCollidable) from null to void
  * Changed the capabilities of Function [PhysicsService.CollisionGroupSetCollidable](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#CollisionGroupSetCollidable)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Function [PhysicsService.CollisionGroupsAreCollidable](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#CollisionGroupsAreCollidable)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Function [PhysicsService.CreateCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#CreateCollisionGroup)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Function [PhysicsService.GetCollisionGroupId](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#GetCollisionGroupId)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Function [PhysicsService.GetCollisionGroupName](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#GetCollisionGroupName)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Function [PhysicsService.GetCollisionGroups](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#GetCollisionGroups)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the capabilities of Function [PhysicsService.GetMaxCollisionGroups](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#GetMaxCollisionGroups)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [PhysicsService.IkSolve](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#IkSolve) from null to void
  * Changed the capabilities of Function [PhysicsService.IkSolve](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#IkSolve)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [PhysicsService.LocalIkSolve](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#LocalIkSolve) from null to void
  * Changed the capabilities of Function [PhysicsService.LocalIkSolve](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#LocalIkSolve)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [PhysicsService.RemoveCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#RemoveCollisionGroup) from null to void
  * Changed the capabilities of Function [PhysicsService.RemoveCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#RemoveCollisionGroup)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [PhysicsService.RenameCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#RenameCollisionGroup) from null to void
  * Changed the capabilities of Function [PhysicsService.RenameCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#RenameCollisionGroup)
    from: {🚧Physics}
    to: {🚧None}
  * Changed the return-type of Function [PhysicsService.SetPartCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#SetPartCollisionGroup) from null to void
  * Changed the capabilities of Function [PhysicsService.SetPartCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsService#SetPartCollisionGroup)
    from: {🚧Physics}
    to: {🚧None}
  * Removed Function PhysicsService.GetRegisteredCollisionGroups
  * Removed Function PhysicsService.IsCollisionGroupRegistered
  * Removed Function PhysicsService.RegisterCollisionGroup
  * Removed Function PhysicsService.UnregisterCollisionGroup
* Update Class [PhysicsSettings](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Settings]
  * Changed the security of Property [PhysicsSettings.AllowSleep](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AllowSleep)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreAnchorsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreAnchorsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreAssembliesShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreAssembliesShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreAwakePartsHighlighted](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreAwakePartsHighlighted)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreBodyTypesShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreBodyTypesShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreContactIslandsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreContactIslandsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreContactPointsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreContactPointsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreJointCoordinatesShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreJointCoordinatesShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreMechanismsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreMechanismsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreModelCoordsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreModelCoordsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreOwnersShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreOwnersShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.ArePartCoordsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#ArePartCoordsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreRegionsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreRegionsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreTerrainReplicationRegionsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreTerrainReplicationRegionsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreUnalignedPartsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreUnalignedPartsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.AreWorldCoordsShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#AreWorldCoordsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.DisableCSGv2](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#DisableCSGv2)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.ForceCSGv2](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#ForceCSGv2)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.IsInterpolationThrottleShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#IsInterpolationThrottleShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.IsReceiveAgeShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#IsReceiveAgeShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.IsTreeShown](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#IsTreeShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.PhysicsEnvironmentalThrottle](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#PhysicsEnvironmentalThrottle)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.ShowDecompositionGeometry](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#ShowDecompositionGeometry)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.ThrottleAdjustTime](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#ThrottleAdjustTime)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [PhysicsSettings.UseCSGv2](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#UseCSGv2)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Removed Property PhysicsSettings.AreAssemblyCentersOfMassShown
  * Removed Property PhysicsSettings.AreCollisionCostsShown
  * Removed Property PhysicsSettings.AreConstraintForcesShownForSelectedOrHoveredInstances
  * Removed Property PhysicsSettings.AreConstraintTorquesShownForSelectedOrHoveredInstances
  * Removed Property PhysicsSettings.AreContactForcesShownForSelectedOrHoveredAssemblies
  * Removed Property PhysicsSettings.AreGravityForcesShownForSelectedOrHoveredAssemblies
  * Removed Property PhysicsSettings.AreMagnitudesShownForDrawnForcesAndTorques
  * Removed Property PhysicsSettings.AreNonAnchorsShown
  * Removed Property PhysicsSettings.AreSolverIslandsShown
  * Removed Property PhysicsSettings.DisableCSGv3ForPlugins
  * Removed Property PhysicsSettings.DrawConstraintsNetForce
  * Removed Property PhysicsSettings.DrawContactsNetForce
  * Removed Property PhysicsSettings.DrawTotalNetForce
  * Removed Property PhysicsSettings.EnableForceVisualizationSmoothing
  * Removed Property PhysicsSettings.FluidForceDrawScale
  * Removed Property PhysicsSettings.ForceDrawScale
  * Removed Property PhysicsSettings.ForceVisualizationSmoothingSteps
  * Removed Property PhysicsSettings.ShowFluidForcesForSelectedOrHoveredMechanisms
  * Removed Property PhysicsSettings.ShowInstanceNamesForDrawnForcesAndTorques
  * Removed Property PhysicsSettings.SolverConvergenceMetricType
  * Removed Property PhysicsSettings.SolverConvergenceVisualizationMode
  * Removed Property PhysicsSettings.TorqueDrawScale
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Player.AccountAge](https://create.roblox.com/docs/reference/engine/classes/Player#AccountAge)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.AppearanceDidLoad](https://create.roblox.com/docs/reference/engine/classes/Player#AppearanceDidLoad)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.AutoJumpEnabled](https://create.roblox.com/docs/reference/engine/classes/Player#AutoJumpEnabled)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.CameraMaxZoomDistance](https://create.roblox.com/docs/reference/engine/classes/Player#CameraMaxZoomDistance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.CameraMinZoomDistance](https://create.roblox.com/docs/reference/engine/classes/Player#CameraMinZoomDistance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.CameraMode](https://create.roblox.com/docs/reference/engine/classes/Player#CameraMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.CanLoadCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#CanLoadCharacterAppearance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.Character](https://create.roblox.com/docs/reference/engine/classes/Player#Character)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.CharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#CharacterAppearance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.CharacterAppearanceId](https://create.roblox.com/docs/reference/engine/classes/Player#CharacterAppearanceId)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.ChatMode](https://create.roblox.com/docs/reference/engine/classes/Player#ChatMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DataComplexity](https://create.roblox.com/docs/reference/engine/classes/Player#DataComplexity)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DataComplexityLimit](https://create.roblox.com/docs/reference/engine/classes/Player#DataComplexityLimit)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DataReady](https://create.roblox.com/docs/reference/engine/classes/Player#DataReady)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DevCameraOcclusionMode](https://create.roblox.com/docs/reference/engine/classes/Player#DevCameraOcclusionMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DevComputerCameraMode](https://create.roblox.com/docs/reference/engine/classes/Player#DevComputerCameraMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DevComputerMovementMode](https://create.roblox.com/docs/reference/engine/classes/Player#DevComputerMovementMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DevEnableMouseLock](https://create.roblox.com/docs/reference/engine/classes/Player#DevEnableMouseLock)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DevTouchCameraMode](https://create.roblox.com/docs/reference/engine/classes/Player#DevTouchCameraMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DevTouchMovementMode](https://create.roblox.com/docs/reference/engine/classes/Player#DevTouchMovementMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.DisplayName](https://create.roblox.com/docs/reference/engine/classes/Player#DisplayName)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.FollowUserId](https://create.roblox.com/docs/reference/engine/classes/Player#FollowUserId)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.GameplayPaused](https://create.roblox.com/docs/reference/engine/classes/Player#GameplayPaused)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the serialization of Property [Player.GameplayPaused](https://create.roblox.com/docs/reference/engine/classes/Player#GameplayPaused)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [Player.Guest](https://create.roblox.com/docs/reference/engine/classes/Player#Guest)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.HealthDisplayDistance](https://create.roblox.com/docs/reference/engine/classes/Player#HealthDisplayDistance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.LocaleId](https://create.roblox.com/docs/reference/engine/classes/Player#LocaleId)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.MaximumSimulationRadius](https://create.roblox.com/docs/reference/engine/classes/Player#MaximumSimulationRadius)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.MembershipType](https://create.roblox.com/docs/reference/engine/classes/Player#MembershipType)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.NameDisplayDistance](https://create.roblox.com/docs/reference/engine/classes/Player#NameDisplayDistance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.Neutral](https://create.roblox.com/docs/reference/engine/classes/Player#Neutral)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.OsPlatform](https://create.roblox.com/docs/reference/engine/classes/Player#OsPlatform)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.PlatformName](https://create.roblox.com/docs/reference/engine/classes/Player#PlatformName)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.ReplicationFocus](https://create.roblox.com/docs/reference/engine/classes/Player#ReplicationFocus)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.RespawnLocation](https://create.roblox.com/docs/reference/engine/classes/Player#RespawnLocation)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.SimulationRadius](https://create.roblox.com/docs/reference/engine/classes/Player#SimulationRadius)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.Team](https://create.roblox.com/docs/reference/engine/classes/Player#Team)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.TeamColor](https://create.roblox.com/docs/reference/engine/classes/Player#TeamColor)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.Teleported](https://create.roblox.com/docs/reference/engine/classes/Player#Teleported)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.TeleportedIn](https://create.roblox.com/docs/reference/engine/classes/Player#TeleportedIn)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.UserId](https://create.roblox.com/docs/reference/engine/classes/Player#UserId)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.VRDevice](https://create.roblox.com/docs/reference/engine/classes/Player#VRDevice)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Player.userId](https://create.roblox.com/docs/reference/engine/classes/Player#userId)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.AddToBlockList](https://create.roblox.com/docs/reference/engine/classes/Player#AddToBlockList) from null to void
  * Changed the capabilities of Function [Player.AddToBlockList](https://create.roblox.com/docs/reference/engine/classes/Player#AddToBlockList)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.ClearCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#ClearCharacterAppearance) from null to void
  * Changed the capabilities of Function [Player.ClearCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#ClearCharacterAppearance)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.DistanceFromCharacter](https://create.roblox.com/docs/reference/engine/classes/Player#DistanceFromCharacter)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.GetFriendStatus](https://create.roblox.com/docs/reference/engine/classes/Player#GetFriendStatus)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.GetGameSessionID](https://create.roblox.com/docs/reference/engine/classes/Player#GetGameSessionID)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.GetJoinData](https://create.roblox.com/docs/reference/engine/classes/Player#GetJoinData)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.GetMouse](https://create.roblox.com/docs/reference/engine/classes/Player#GetMouse)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed ThreadSafety of Function [Player.GetNetworkPing](https://create.roblox.com/docs/reference/engine/classes/Player#GetNetworkPing) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Player.GetNetworkPing](https://create.roblox.com/docs/reference/engine/classes/Player#GetNetworkPing)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.GetUnder13](https://create.roblox.com/docs/reference/engine/classes/Player#GetUnder13)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.HasAppearanceLoaded](https://create.roblox.com/docs/reference/engine/classes/Player#HasAppearanceLoaded)
    from: {🚧Players}
    to: {🚧None}
  * Added Function [Player.IsUserAvailableForExperiment](https://create.roblox.com/docs/reference/engine/classes/Player#IsUserAvailableForExperiment) () -> bool [🏷️ Deprecated]
  * Changed the return-type of Function [Player.Kick](https://create.roblox.com/docs/reference/engine/classes/Player#Kick) from null to void
  * Changed the capabilities of Function [Player.Kick](https://create.roblox.com/docs/reference/engine/classes/Player#Kick)
    from: {🚧Players, Consequences}
    to: {🚧None}
  * Changed the capabilities of Function [Player.LoadBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#LoadBoolean)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.LoadCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterAppearance) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.LoadCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterAppearance)
    from: {🚧AvatarAppearance, Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.LoadData](https://create.roblox.com/docs/reference/engine/classes/Player#LoadData) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.LoadData](https://create.roblox.com/docs/reference/engine/classes/Player#LoadData)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.LoadInstance](https://create.roblox.com/docs/reference/engine/classes/Player#LoadInstance)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.LoadNumber](https://create.roblox.com/docs/reference/engine/classes/Player#LoadNumber)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.LoadString](https://create.roblox.com/docs/reference/engine/classes/Player#LoadString)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.Move](https://create.roblox.com/docs/reference/engine/classes/Player#Move) from null to void
  * Changed the capabilities of Function [Player.Move](https://create.roblox.com/docs/reference/engine/classes/Player#Move)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.RemoveCharacter](https://create.roblox.com/docs/reference/engine/classes/Player#RemoveCharacter) from null to void
  * Changed the capabilities of Function [Player.RemoveCharacter](https://create.roblox.com/docs/reference/engine/classes/Player#RemoveCharacter)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.RequestFriendship](https://create.roblox.com/docs/reference/engine/classes/Player#RequestFriendship) from null to void
  * Changed the capabilities of Function [Player.RequestFriendship](https://create.roblox.com/docs/reference/engine/classes/Player#RequestFriendship)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.RevokeFriendship](https://create.roblox.com/docs/reference/engine/classes/Player#RevokeFriendship) from null to void
  * Changed the capabilities of Function [Player.RevokeFriendship](https://create.roblox.com/docs/reference/engine/classes/Player#RevokeFriendship)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SaveBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#SaveBoolean) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.SaveBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#SaveBoolean)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SaveData](https://create.roblox.com/docs/reference/engine/classes/Player#SaveData) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.SaveData](https://create.roblox.com/docs/reference/engine/classes/Player#SaveData)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SaveInstance](https://create.roblox.com/docs/reference/engine/classes/Player#SaveInstance) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.SaveInstance](https://create.roblox.com/docs/reference/engine/classes/Player#SaveInstance)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SaveNumber](https://create.roblox.com/docs/reference/engine/classes/Player#SaveNumber) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.SaveNumber](https://create.roblox.com/docs/reference/engine/classes/Player#SaveNumber)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SaveString](https://create.roblox.com/docs/reference/engine/classes/Player#SaveString) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.SaveString](https://create.roblox.com/docs/reference/engine/classes/Player#SaveString)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SetAccountAge](https://create.roblox.com/docs/reference/engine/classes/Player#SetAccountAge) from null to void
  * Changed the capabilities of Function [Player.SetAccountAge](https://create.roblox.com/docs/reference/engine/classes/Player#SetAccountAge)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SetCharacterAppearanceJson](https://create.roblox.com/docs/reference/engine/classes/Player#SetCharacterAppearanceJson) from null to void
  * Changed the capabilities of Function [Player.SetCharacterAppearanceJson](https://create.roblox.com/docs/reference/engine/classes/Player#SetCharacterAppearanceJson)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SetMembershipType](https://create.roblox.com/docs/reference/engine/classes/Player#SetMembershipType) from null to void
  * Changed the capabilities of Function [Player.SetMembershipType](https://create.roblox.com/docs/reference/engine/classes/Player#SetMembershipType)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SetSuperSafeChat](https://create.roblox.com/docs/reference/engine/classes/Player#SetSuperSafeChat) from null to void
  * Changed the capabilities of Function [Player.SetSuperSafeChat](https://create.roblox.com/docs/reference/engine/classes/Player#SetSuperSafeChat)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.SetUnder13](https://create.roblox.com/docs/reference/engine/classes/Player#SetUnder13) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.SetUnder13](https://create.roblox.com/docs/reference/engine/classes/Player#SetUnder13)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.UpdatePlayerBlocked](https://create.roblox.com/docs/reference/engine/classes/Player#UpdatePlayerBlocked) from null to void
  * Changed the capabilities of Function [Player.UpdatePlayerBlocked](https://create.roblox.com/docs/reference/engine/classes/Player#UpdatePlayerBlocked)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.loadBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#loadBoolean)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.loadInstance](https://create.roblox.com/docs/reference/engine/classes/Player#loadInstance)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.loadNumber](https://create.roblox.com/docs/reference/engine/classes/Player#loadNumber)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.loadString](https://create.roblox.com/docs/reference/engine/classes/Player#loadString)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.saveBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#saveBoolean) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.saveBoolean](https://create.roblox.com/docs/reference/engine/classes/Player#saveBoolean)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.saveInstance](https://create.roblox.com/docs/reference/engine/classes/Player#saveInstance) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.saveInstance](https://create.roblox.com/docs/reference/engine/classes/Player#saveInstance)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.saveNumber](https://create.roblox.com/docs/reference/engine/classes/Player#saveNumber) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.saveNumber](https://create.roblox.com/docs/reference/engine/classes/Player#saveNumber)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.saveString](https://create.roblox.com/docs/reference/engine/classes/Player#saveString) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Player.saveString](https://create.roblox.com/docs/reference/engine/classes/Player#saveString)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.GetFriendsOnline](https://create.roblox.com/docs/reference/engine/classes/Player#GetFriendsOnline)
    from: {🚧Players, Social}
    to: {🚧None}
  * Changed the capabilities of Function [Player.GetRankInGroup](https://create.roblox.com/docs/reference/engine/classes/Player#GetRankInGroup)
    from: {🚧Players, Groups}
    to: {🚧None}
  * Changed the capabilities of Function [Player.GetRoleInGroup](https://create.roblox.com/docs/reference/engine/classes/Player#GetRoleInGroup)
    from: {🚧Players, Groups}
    to: {🚧None}
  * Changed the parameters of Function [Player.IsBestFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#IsBestFriendsWith)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Player.IsBestFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#IsBestFriendsWith)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Function [Player.IsFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#IsFriendsWith)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Player.IsFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#IsFriendsWith)
    from: {🚧Players, Social}
    to: {🚧None}
  * Changed the capabilities of Function [Player.IsInGroup](https://create.roblox.com/docs/reference/engine/classes/Player#IsInGroup)
    from: {🚧Players, Groups}
    to: {🚧None}
  * Changed the return-type of Function [Player.LoadCharacter](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacter) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [Player.LoadCharacter](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacter)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.LoadCharacterBlocking](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterBlocking) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [Player.LoadCharacterBlocking](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterBlocking)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.LoadCharacterWithHumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithHumanoidDescription) from null to void [🏷️ Yields]
  * Changed the parameters of Function [Player.LoadCharacterWithHumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithHumanoidDescription)
    from: (humanoidDescription: HumanoidDescription, assetTypeVerification: AssetTypeVerification = Default)
    to: (humanoidDescription: HumanoidDescription)
  * Changed the capabilities of Function [Player.LoadCharacterWithHumanoidDescription](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithHumanoidDescription)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Player.RequestStreamAroundAsync](https://create.roblox.com/docs/reference/engine/classes/Player#RequestStreamAroundAsync) from null to void [🏷️ Yields]
  * Changed the capabilities of Function [Player.RequestStreamAroundAsync](https://create.roblox.com/docs/reference/engine/classes/Player#RequestStreamAroundAsync)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.WaitForDataReady](https://create.roblox.com/docs/reference/engine/classes/Player#WaitForDataReady)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Function [Player.isFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#isFriendsWith)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Player.isFriendsWith](https://create.roblox.com/docs/reference/engine/classes/Player#isFriendsWith)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Player.waitForDataReady](https://create.roblox.com/docs/reference/engine/classes/Player#waitForDataReady)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [Player.CharacterAdded](https://create.roblox.com/docs/reference/engine/classes/Player#CharacterAdded)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [Player.CharacterAppearanceLoaded](https://create.roblox.com/docs/reference/engine/classes/Player#CharacterAppearanceLoaded)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [Player.CharacterRemoving](https://create.roblox.com/docs/reference/engine/classes/Player#CharacterRemoving)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [Player.Chatted](https://create.roblox.com/docs/reference/engine/classes/Player#Chatted)
    from: {🚧Chat, Players}
    to: {🚧None}
  * Changed the capabilities of Event [Player.FriendStatusChanged](https://create.roblox.com/docs/reference/engine/classes/Player#FriendStatusChanged)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [Player.Idled](https://create.roblox.com/docs/reference/engine/classes/Player#Idled)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [Player.OnTeleport](https://create.roblox.com/docs/reference/engine/classes/Player#OnTeleport)
    from: {🚧Players, Teleport}
    to: {🚧None}
  * Changed the capabilities of Event [Player.SimulationRadiusChanged](https://create.roblox.com/docs/reference/engine/classes/Player#SimulationRadiusChanged)
    from: {🚧Players}
    to: {🚧None}
  * Removed Property Player.AgeChecked
  * Removed Property Player.ChatAvailabilityStatus
  * Removed Property Player.HasRobloxSubscription
  * Removed Property Player.HasVerifiedBadge
  * Removed Property Player.InputLatency
  * Removed Property Player.PartyId
  * Removed Property Player.StepIdOffset
  * Removed Property Player.ThirdPartyTextChatRestrictionStatus
  * Removed Property Player.UnfilteredChat
  * Removed Property Player.User
  * Removed Property Player.VREnabled
  * Removed Property Player.VoiceChatVolume
  * Removed Function Player.AddReplicationFocus
  * Removed Function Player.AddReplicationFocusPosition
  * Removed Function Player.ClearCachedAvatarAppearance
  * Removed Function Player.GetBlockListInitialized
  * Removed Function Player.GetCameraState
  * Removed Function Player.GetData
  * Removed Function Player.GetSeatRequested
  * Removed Function Player.GetToolRequested
  * Removed Function Player.HasBlockedPlayer
  * Removed Function Player.IsVerified
  * Removed Function Player.NotifyAgeCheckPassed
  * Removed Function Player.OverrideStreamingRadii
  * Removed Function Player.PinStreamingForInstance
  * Removed Function Player.PinStreamingForInstanceByUniqueId
  * Removed Function Player.PromptAgeCheck
  * Removed Function Player.RemoveReplicationFocus
  * Removed Function Player.RemoveReplicationFocusPosition
  * Removed Function Player.RequestSeat
  * Removed Function Player.RequestTool
  * Removed Function Player.SetBlockListInitialized
  * Removed Function Player.SetChatTranslationSettingsLocaleId
  * Removed Function Player.SetExperienceSettingsLocaleId
  * Removed Function Player.SetHasRobloxSubscription
  * Removed Function Player.SetModerationAccessKey
  * Removed Function Player.UnpinStreamingForInstance
  * Removed Function Player.GetCanManageAsync
  * Removed Function Player.GetFriendsOnlineAsync
  * Removed Function Player.GetFriendsWhoPlayedAsync
  * Removed Function Player.GetRankInGroupAsync
  * Removed Function Player.GetRoleInGroupAsync
  * Removed Function Player.IsFriendsWithAsync
  * Removed Function Player.IsInGroupAsync
  * Removed Function Player.LoadCharacterAsync
  * Removed Function Player.LoadCharacterWithAvatarRules
  * Removed Function Player.LoadCharacterWithHumanoidDescriptionAsync
  * Removed Function Player.PromptSecurityChallengeAsync
  * Removed Event Player.BlockListChanged
  * Removed Event Player.CloudEditSelectionChanged
  * Removed Event Player.InstancePinned
  * Removed Event Player.InstanceUnpinned
  * Removed Event Player.StreamingPinComplete
* Update Class [PlayerEmulatorService](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [PlayerEmulatorService.DEPRECATED_SerializedEmulatedPolicyInfo](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#DEPRECATED_SerializedEmulatedPolicyInfo): string [🏷️ Hidden] [⚡ThreadSafety: ReadSafe]
  * Added Property [PlayerEmulatorService.PlayerEmulationEnabled_deprecated](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#PlayerEmulationEnabled_deprecated): bool [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [PlayerEmulatorService.StudioEmulatedCountryRegionCode](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#StudioEmulatedCountryRegionCode): string [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Changed the return-type of Function [PlayerEmulatorService.SetEmulatedPolicyInfo](https://create.roblox.com/docs/reference/engine/classes/PlayerEmulatorService#SetEmulatedPolicyInfo) from null to void
  * Removed Property PlayerEmulatorService.PseudolocalizationEnabled
  * Removed Property PlayerEmulatorService.TextElongationFactor
  * Removed Function PlayerEmulatorService.RegionCodeWillHaveAutomaticNonCustomPolicies
* Update Class [PlayerScripts](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [PlayerScripts.ClearComputerCameraMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearComputerCameraMovementModes) from null to void
  * Changed the capabilities of Function [PlayerScripts.ClearComputerCameraMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearComputerCameraMovementModes)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed the return-type of Function [PlayerScripts.ClearComputerMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearComputerMovementModes) from null to void
  * Changed the capabilities of Function [PlayerScripts.ClearComputerMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearComputerMovementModes)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed the return-type of Function [PlayerScripts.ClearTouchCameraMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearTouchCameraMovementModes) from null to void
  * Changed the capabilities of Function [PlayerScripts.ClearTouchCameraMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearTouchCameraMovementModes)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed the return-type of Function [PlayerScripts.ClearTouchMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearTouchMovementModes) from null to void
  * Changed the capabilities of Function [PlayerScripts.ClearTouchMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ClearTouchMovementModes)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed the capabilities of Function [PlayerScripts.GetRegisteredComputerCameraMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#GetRegisteredComputerCameraMovementModes)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [PlayerScripts.GetRegisteredComputerMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#GetRegisteredComputerMovementModes)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [PlayerScripts.GetRegisteredTouchCameraMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#GetRegisteredTouchCameraMovementModes)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [PlayerScripts.GetRegisteredTouchMovementModes](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#GetRegisteredTouchMovementModes)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [PlayerScripts.RegisterComputerCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterComputerCameraMovementMode) from null to void
  * Changed the capabilities of Function [PlayerScripts.RegisterComputerCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterComputerCameraMovementMode)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed the return-type of Function [PlayerScripts.RegisterComputerMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterComputerMovementMode) from null to void
  * Changed the capabilities of Function [PlayerScripts.RegisterComputerMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterComputerMovementMode)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed the return-type of Function [PlayerScripts.RegisterTouchCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterTouchCameraMovementMode) from null to void
  * Changed the capabilities of Function [PlayerScripts.RegisterTouchCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterTouchCameraMovementMode)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed the return-type of Function [PlayerScripts.RegisterTouchMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterTouchMovementMode) from null to void
  * Changed the capabilities of Function [PlayerScripts.RegisterTouchMovementMode](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#RegisterTouchMovementMode)
    from: {🚧Input, Players}
    to: {🚧None}
  * Changed the capabilities of Event [PlayerScripts.ComputerCameraMovementModeRegistered](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ComputerCameraMovementModeRegistered)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [PlayerScripts.ComputerMovementModeRegistered](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#ComputerMovementModeRegistered)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [PlayerScripts.TouchCameraMovementModeRegistered](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#TouchCameraMovementModeRegistered)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [PlayerScripts.TouchMovementModeRegistered](https://create.roblox.com/docs/reference/engine/classes/PlayerScripts#TouchMovementModeRegistered)
    from: {🚧Players}
    to: {🚧None}
* Update Class [Players](https://create.roblox.com/docs/reference/engine/classes/Players) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [Players.BubbleChat](https://create.roblox.com/docs/reference/engine/classes/Players#BubbleChat)
    from: {🚧Read: Chat, Players | Write: Chat}
    to: {🚧None}
  * Changed the capabilities of Property [Players.CharacterAutoLoads](https://create.roblox.com/docs/reference/engine/classes/Players#CharacterAutoLoads)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.ClassicChat](https://create.roblox.com/docs/reference/engine/classes/Players#ClassicChat)
    from: {🚧Read: Chat, Players | Write: Chat}
    to: {🚧None}
  * Changed the capabilities of Property [Players.LocalPlayer](https://create.roblox.com/docs/reference/engine/classes/Players#LocalPlayer)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.MaxPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#MaxPlayers)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.MaxPlayersInternal](https://create.roblox.com/docs/reference/engine/classes/Players#MaxPlayersInternal)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.NumPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#NumPlayers)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.PreferredPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#PreferredPlayers)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.PreferredPlayersInternal](https://create.roblox.com/docs/reference/engine/classes/Players#PreferredPlayersInternal)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.RespawnTime](https://create.roblox.com/docs/reference/engine/classes/Players#RespawnTime)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.localPlayer](https://create.roblox.com/docs/reference/engine/classes/Players#localPlayer)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Players.numPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#numPlayers)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.Chat](https://create.roblox.com/docs/reference/engine/classes/Players#Chat) from null to void
  * Changed the capabilities of Function [Players.Chat](https://create.roblox.com/docs/reference/engine/classes/Players#Chat)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.CreateLocalPlayer](https://create.roblox.com/docs/reference/engine/classes/Players#CreateLocalPlayer) from Player to Instance
  * Changed the capabilities of Function [Players.CreateLocalPlayer](https://create.roblox.com/docs/reference/engine/classes/Players#CreateLocalPlayer)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Function [Players.GetPlayerByUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayerByUserId)
    from: (userId: User)
    to: (userId: int64)
  * Changed ThreadSafety of Function [Players.GetPlayerByUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayerByUserId) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Players.GetPlayerByUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayerByUserId)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Players.GetPlayerFromCharacter](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayerFromCharacter)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.GetPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayers) from Instances to Objects
  * Changed ThreadSafety of Function [Players.GetPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayers) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Players.GetPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#GetPlayers)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.ReportAbuse](https://create.roblox.com/docs/reference/engine/classes/Players#ReportAbuse) from null to void
  * Changed the parameters of Function [Players.ReportAbuse](https://create.roblox.com/docs/reference/engine/classes/Players#ReportAbuse)
    from: (player: Player, reason: string, optionalMessage: string)
    to: (player: Instance, reason: string, optionalMessage: string)
  * Changed the capabilities of Function [Players.ReportAbuse](https://create.roblox.com/docs/reference/engine/classes/Players#ReportAbuse)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.SetChatStyle](https://create.roblox.com/docs/reference/engine/classes/Players#SetChatStyle) from null to void
  * Changed the capabilities of Function [Players.SetChatStyle](https://create.roblox.com/docs/reference/engine/classes/Players#SetChatStyle)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.SetLocalPlayerInfo](https://create.roblox.com/docs/reference/engine/classes/Players#SetLocalPlayerInfo) from null to void
  * Changed the parameters of Function [Players.SetLocalPlayerInfo](https://create.roblox.com/docs/reference/engine/classes/Players#SetLocalPlayerInfo)
    from: (userId: int64, userName: string, displayName: string, membershipType: MembershipType, isUnder13: bool, hasRobloxSubscription: bool = false, ageCheckedStatus: AgeCheckStatus = Unchecked)
    to: (userId: int64, userName: string, displayName: string, membershipType: MembershipType, isUnder13: bool)
  * Changed the capabilities of Function [Players.SetLocalPlayerInfo](https://create.roblox.com/docs/reference/engine/classes/Players#SetLocalPlayerInfo)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.TeamChat](https://create.roblox.com/docs/reference/engine/classes/Players#TeamChat) from null to void
  * Changed the capabilities of Function [Players.TeamChat](https://create.roblox.com/docs/reference/engine/classes/Players#TeamChat)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.WhisperChat](https://create.roblox.com/docs/reference/engine/classes/Players#WhisperChat) from null to void
  * Changed the capabilities of Function [Players.WhisperChat](https://create.roblox.com/docs/reference/engine/classes/Players#WhisperChat)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.getPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#getPlayers) from Instances to Objects [🏷️ Deprecated]
  * Changed the capabilities of Function [Players.getPlayers](https://create.roblox.com/docs/reference/engine/classes/Players#getPlayers)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Players.playerFromCharacter](https://create.roblox.com/docs/reference/engine/classes/Players#playerFromCharacter)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.players](https://create.roblox.com/docs/reference/engine/classes/Players#players) from Instances to Objects [🏷️ Deprecated]
  * Changed the capabilities of Function [Players.players](https://create.roblox.com/docs/reference/engine/classes/Players#players)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.CreateHumanoidModelFromDescription](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromDescription) from Model to Instance [🏷️ Yields]
  * Changed the parameters of Function [Players.CreateHumanoidModelFromDescription](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromDescription)
    from: (description: HumanoidDescription, rigType: HumanoidRigType, assetTypeVerification: AssetTypeVerification = Default)
    to: (description: Instance, rigType: HumanoidRigType, assetTypeVerification: AssetTypeVerification = Default)
  * Changed the capabilities of Function [Players.CreateHumanoidModelFromDescription](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromDescription)
    from: {🚧AvatarAppearance, Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.CreateHumanoidModelFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromUserId) from Model to Instance [🏷️ Yields]
  * Changed the parameters of Function [Players.CreateHumanoidModelFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromUserId)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Players.CreateHumanoidModelFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#CreateHumanoidModelFromUserId)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.GetCharacterAppearanceAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceAsync) from Model to Instance [🏷️ Yields] [🏷️ Deprecated]
  * Changed the parameters of Function [Players.GetCharacterAppearanceAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceAsync)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Players.GetCharacterAppearanceAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceAsync)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Function [Players.GetCharacterAppearanceInfoAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceInfoAsync)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Players.GetCharacterAppearanceInfoAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetCharacterAppearanceInfoAsync)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.GetFriendsAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetFriendsAsync) from FriendPages to Instance [🏷️ Yields]
  * Changed the parameters of Function [Players.GetFriendsAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetFriendsAsync)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Players.GetFriendsAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetFriendsAsync)
    from: {🚧Players, Social}
    to: {🚧None}
  * Changed the return-type of Function [Players.GetHumanoidDescriptionFromOutfitId](https://create.roblox.com/docs/reference/engine/classes/Players#GetHumanoidDescriptionFromOutfitId) from HumanoidDescription to Instance [🏷️ Yields]
  * Changed the capabilities of Function [Players.GetHumanoidDescriptionFromOutfitId](https://create.roblox.com/docs/reference/engine/classes/Players#GetHumanoidDescriptionFromOutfitId)
    from: {🚧AvatarAppearance, Players}
    to: {🚧None}
  * Changed the return-type of Function [Players.GetHumanoidDescriptionFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetHumanoidDescriptionFromUserId) from HumanoidDescription to Instance [🏷️ Yields]
  * Changed the parameters of Function [Players.GetHumanoidDescriptionFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetHumanoidDescriptionFromUserId)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Players.GetHumanoidDescriptionFromUserId](https://create.roblox.com/docs/reference/engine/classes/Players#GetHumanoidDescriptionFromUserId)
    from: {🚧AvatarAppearance, Players}
    to: {🚧None}
  * Changed the parameters of Function [Players.GetNameFromUserIdAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetNameFromUserIdAsync)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [Players.GetNameFromUserIdAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetNameFromUserIdAsync)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [Players.GetUserIdFromNameAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetUserIdFromNameAsync)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Function [Players.GetUserThumbnailAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetUserThumbnailAsync)
    from: (userId: User, thumbnailType: ThumbnailType, thumbnailSize: ThumbnailSize)
    to: (userId: int64, thumbnailType: ThumbnailType, thumbnailSize: ThumbnailSize)
  * Changed the capabilities of Function [Players.GetUserThumbnailAsync](https://create.roblox.com/docs/reference/engine/classes/Players#GetUserThumbnailAsync)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Event [Players.FriendRequestEvent](https://create.roblox.com/docs/reference/engine/classes/Players#FriendRequestEvent)
    from: {🚧Players}
    to: {🚧None}
  * Added Event [Players.GameAnnounce](https://create.roblox.com/docs/reference/engine/classes/Players#GameAnnounce)
  * Changed the capabilities of Event [Players.PlayerAdded](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerAdded)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Event [Players.PlayerChatted](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerChatted)
    from: (chatType: PlayerChatType, player: Player, message: string, targetPlayer: Player)
    to: (chatType: PlayerChatType, player: Instance, message: string, targetPlayer: Instance)
  * Changed the capabilities of Event [Players.PlayerChatted](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerChatted)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Event [Players.PlayerConnecting](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerConnecting)
    from: (player: Player)
    to: (player: Instance)
  * Changed the capabilities of Event [Players.PlayerConnecting](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerConnecting)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Event [Players.PlayerDisconnecting](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerDisconnecting)
    from: (player: Player)
    to: (player: Instance)
  * Changed the capabilities of Event [Players.PlayerDisconnecting](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerDisconnecting)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Event [Players.PlayerMembershipChanged](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerMembershipChanged)
    from: (player: Player)
    to: (player: Instance)
  * Changed the capabilities of Event [Players.PlayerMembershipChanged](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerMembershipChanged)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Event [Players.PlayerRejoining](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerRejoining)
    from: (player: Player)
    to: (player: Instance)
  * Changed the capabilities of Event [Players.PlayerRejoining](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerRejoining)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Event [Players.PlayerRemoving](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerRemoving)
    from: (player: Player, reason: PlayerExitReason)
    to: (player: Player)
  * Changed the capabilities of Event [Players.PlayerRemoving](https://create.roblox.com/docs/reference/engine/classes/Players#PlayerRemoving)
    from: {🚧Players}
    to: {🚧None}
  * Removed Property Players.BanningEnabled
  * Removed Property Players.UseStrafingAnimations
  * Removed Function Players.CreateThumbnailPlayer
  * Removed Function Players.ReportAbuseV3
  * Removed Function Players.ReportAvatarAbuse
  * Removed Function Players.ReportChatAbuse
  * Removed Function Players.ResetLocalPlayer
  * Removed Function Players.BanAsync
  * Removed Function Players.CreateHumanoidModelFromDescriptionAsync
  * Removed Function Players.CreateHumanoidModelFromUserIdAsync
  * Removed Function Players.GetBanHistoryAsync
  * Removed Function Players.GetHumanoidDescriptionFromOutfitIdAsync
  * Removed Function Players.GetHumanoidDescriptionFromUserIdAsync
  * Removed Function Players.GetProfileConfigurationFromUserIdAsync
  * Removed Function Players.UnbanAsync
  * Removed Event Players.PromptAgeCheckRequested
  * Removed Event Players.UserSubscriptionStatusChanged
* Update Class [Plugin](https://create.roblox.com/docs/reference/engine/classes/Plugin) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [Plugin.Activate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Activate) from null to void
  * Changed the return-type of Function [Plugin.Deactivate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Deactivate) from null to void
  * Changed the return-type of Function [Plugin.Invoke](https://create.roblox.com/docs/reference/engine/classes/Plugin#Invoke) from null to void
  * Changed the return-type of Function [Plugin.Negate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Negate) from Instances to Objects
  * Changed the parameters of Function [Plugin.Negate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Negate)
    from: (objects: Instances)
    to: (objects: Objects)
  * Changed the return-type of Function [Plugin.OpenScript](https://create.roblox.com/docs/reference/engine/classes/Plugin#OpenScript) from null to void
  * Changed the return-type of Function [Plugin.OpenWikiPage](https://create.roblox.com/docs/reference/engine/classes/Plugin#OpenWikiPage) from null to void
  * Changed the return-type of Function [Plugin.PauseSound](https://create.roblox.com/docs/reference/engine/classes/Plugin#PauseSound) from null to void
  * Changed the return-type of Function [Plugin.PlaySound](https://create.roblox.com/docs/reference/engine/classes/Plugin#PlaySound) from null to void
  * Changed the return-type of Function [Plugin.ResumeSound](https://create.roblox.com/docs/reference/engine/classes/Plugin#ResumeSound) from null to void
  * Changed the return-type of Function [Plugin.SaveSelectedToRoblox](https://create.roblox.com/docs/reference/engine/classes/Plugin#SaveSelectedToRoblox) from null to void
  * Changed the return-type of Function [Plugin.SelectRibbonTool](https://create.roblox.com/docs/reference/engine/classes/Plugin#SelectRibbonTool) from null to void
  * Changed the return-type of Function [Plugin.Separate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Separate) from Instances to Objects
  * Changed the parameters of Function [Plugin.Separate](https://create.roblox.com/docs/reference/engine/classes/Plugin#Separate)
    from: (objects: Instances)
    to: (objects: Objects)
  * Changed the return-type of Function [Plugin.SetItem](https://create.roblox.com/docs/reference/engine/classes/Plugin#SetItem) from null to void
  * Changed the return-type of Function [Plugin.SetReady](https://create.roblox.com/docs/reference/engine/classes/Plugin#SetReady) from null to void
  * Changed the return-type of Function [Plugin.SetSetting](https://create.roblox.com/docs/reference/engine/classes/Plugin#SetSetting) from null to void
  * Changed the return-type of Function [Plugin.StartDecalDrag](https://create.roblox.com/docs/reference/engine/classes/Plugin#StartDecalDrag) from null to void
  * Changed the return-type of Function [Plugin.StartDrag](https://create.roblox.com/docs/reference/engine/classes/Plugin#StartDrag) from null to void
  * Changed the return-type of Function [Plugin.StopAllSounds](https://create.roblox.com/docs/reference/engine/classes/Plugin#StopAllSounds) from null to void
  * Changed the parameters of Function [Plugin.Union](https://create.roblox.com/docs/reference/engine/classes/Plugin#Union)
    from: (objects: Instances)
    to: (objects: Objects)
  * Removed Property Plugin.DisableUIDragDetectorDrags
  * Removed Property Plugin.IsDebuggable
  * Removed Function Plugin.FinishFullLoading
  * Removed Function Plugin.GetPluginComponent
  * Removed Function Plugin.GetUri
  * Removed Function Plugin.Intersect
  * Removed Function Plugin.IsLoadedFromProject
  * Removed Function Plugin.OnInvokeSuspendOverride
  * Removed Function Plugin.CreateDockWidgetPluginGuiAsync
  * Removed Function Plugin.ImportFbxAnimationAsync
  * Removed Function Plugin.ImportFbxRigAsync
  * Removed Function Plugin.PromptForExistingAssetIdAsync
  * Removed Function Plugin.PromptSaveSelectionAsync
  * Removed Event Plugin.ViewportDragDropped
  * Removed Event Plugin.ViewportDragEntered
  * Removed Event Plugin.ViewportDragLeft
  * Removed Callback Plugin.ProcessAssetInsertionDrag
  * Removed Callback Plugin.ProcessAssetInsertionDrop
* Update Class [PluginAction](https://create.roblox.com/docs/reference/engine/classes/PluginAction) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Changed the security of Property [PluginAction.Text](https://create.roblox.com/docs/reference/engine/classes/PluginAction#Text)
    from: {🔒Read:None, Write:RobloxScriptSecurity}
    to: {🔒None}
  * Changed the serialization of Property [PluginAction.Text](https://create.roblox.com/docs/reference/engine/classes/PluginAction#Text)
    from: [📁LoadOnly]
    to: [🚫None]
  * Removed Property PluginAction.Visible
* Update Class [PluginManager](https://create.roblox.com/docs/reference/engine/classes/PluginManager) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [PluginManager.ExportPlace](https://create.roblox.com/docs/reference/engine/classes/PluginManager#ExportPlace) from null to void
  * Changed the return-type of Function [PluginManager.ExportSelection](https://create.roblox.com/docs/reference/engine/classes/PluginManager#ExportSelection) from null to void
* Update Class [PluginManagerInterface](https://create.roblox.com/docs/reference/engine/classes/PluginManagerInterface) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [PluginManagerInterface.ExportPlace](https://create.roblox.com/docs/reference/engine/classes/PluginManagerInterface#ExportPlace) from null to void
  * Changed the return-type of Function [PluginManagerInterface.ExportSelection](https://create.roblox.com/docs/reference/engine/classes/PluginManagerInterface#ExportSelection) from null to void
* Update Class [PluginMenu](https://create.roblox.com/docs/reference/engine/classes/PluginMenu) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the return-type of Function [PluginMenu.AddAction](https://create.roblox.com/docs/reference/engine/classes/PluginMenu#AddAction) from null to void
  * Changed the return-type of Function [PluginMenu.AddMenu](https://create.roblox.com/docs/reference/engine/classes/PluginMenu#AddMenu) from null to void
  * Changed the return-type of Function [PluginMenu.AddSeparator](https://create.roblox.com/docs/reference/engine/classes/PluginMenu#AddSeparator) from null to void
  * Changed the return-type of Function [PluginMenu.Clear](https://create.roblox.com/docs/reference/engine/classes/PluginMenu#Clear) from null to void
  * Removed Property PluginMenu.Visible
* Update Class [PluginToolbar](https://create.roblox.com/docs/reference/engine/classes/PluginToolbar) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [PluginToolbar.CreateButton](https://create.roblox.com/docs/reference/engine/classes/PluginToolbar#CreateButton) from PluginToolbarButton to Instance
  * Removed Function PluginToolbar.CreatePopupButton
* Update Class [PluginToolbarButton](https://create.roblox.com/docs/reference/engine/classes/PluginToolbarButton) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [PluginToolbarButton.SetActive](https://create.roblox.com/docs/reference/engine/classes/PluginToolbarButton#SetActive) from null to void
  * Removed Property PluginToolbarButton.IconContent
  * Removed Function PluginToolbarButton.SetDropdownActive
  * Removed Event PluginToolbarButton.DropdownClick
* Update Class [PointsService](https://create.roblox.com/docs/reference/engine/classes/PointsService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ Deprecated]
  * Changed the capabilities of Function [PointsService.GetAwardablePoints](https://create.roblox.com/docs/reference/engine/classes/PointsService#GetAwardablePoints)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [PointsService.AwardPoints](https://create.roblox.com/docs/reference/engine/classes/PointsService#AwardPoints)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [PointsService.GetGamePointBalance](https://create.roblox.com/docs/reference/engine/classes/PointsService#GetGamePointBalance)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [PointsService.GetPointBalance](https://create.roblox.com/docs/reference/engine/classes/PointsService#GetPointBalance)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [PointsService.PointsAwarded](https://create.roblox.com/docs/reference/engine/classes/PointsService#PointsAwarded)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [PolicyService](https://create.roblox.com/docs/reference/engine/classes/PolicyService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [PolicyService.IsLuobuServer](https://create.roblox.com/docs/reference/engine/classes/PolicyService#IsLuobuServer)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [PolicyService.LuobuWhitelisted](https://create.roblox.com/docs/reference/engine/classes/PolicyService#LuobuWhitelisted)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Function [PolicyService.GetPolicyInfoForPlayerAsync](https://create.roblox.com/docs/reference/engine/classes/PolicyService#GetPolicyInfoForPlayerAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [PolicyService.GetPolicyInfoForServerRobloxOnlyAsync](https://create.roblox.com/docs/reference/engine/classes/PolicyService#GetPolicyInfoForServerRobloxOnlyAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Function PolicyService.CanViewBrandProjectAsync
* Update Class [PoseBase](https://create.roblox.com/docs/reference/engine/classes/PoseBase) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [PoseBase.EasingDirection](https://create.roblox.com/docs/reference/engine/classes/PoseBase#EasingDirection)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [PoseBase.EasingStyle](https://create.roblox.com/docs/reference/engine/classes/PoseBase#EasingStyle)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [PoseBase.Weight](https://create.roblox.com/docs/reference/engine/classes/PoseBase#Weight)
    from: {🚧Read: Animation}
    to: {🚧None}
* Update Class [NumberPose](https://create.roblox.com/docs/reference/engine/classes/NumberPose) [⬆️Extends: PoseBase] [🧠Memory: Animation]
  * Changed the capabilities of Property [NumberPose.Value](https://create.roblox.com/docs/reference/engine/classes/NumberPose#Value)
    from: {🚧Read: Animation}
    to: {🚧None}
* Update Class [Pose](https://create.roblox.com/docs/reference/engine/classes/Pose) [⬆️Extends: PoseBase] [🧠Memory: Animation]
  * Changed the capabilities of Property [Pose.CFrame](https://create.roblox.com/docs/reference/engine/classes/Pose#CFrame)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the capabilities of Property [Pose.MaskWeight](https://create.roblox.com/docs/reference/engine/classes/Pose#MaskWeight)
    from: {🚧Read: Animation}
    to: {🚧None}
  * Changed the return-type of Function [Pose.AddSubPose](https://create.roblox.com/docs/reference/engine/classes/Pose#AddSubPose) from null to void
  * Changed the capabilities of Function [Pose.AddSubPose](https://create.roblox.com/docs/reference/engine/classes/Pose#AddSubPose)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Pose.GetSubPoses](https://create.roblox.com/docs/reference/engine/classes/Pose#GetSubPoses) from Instances to Objects
  * Changed the capabilities of Function [Pose.GetSubPoses](https://create.roblox.com/docs/reference/engine/classes/Pose#GetSubPoses)
    from: {🚧Animation}
    to: {🚧None}
  * Changed the return-type of Function [Pose.RemoveSubPose](https://create.roblox.com/docs/reference/engine/classes/Pose#RemoveSubPose) from null to void
  * Changed the capabilities of Function [Pose.RemoveSubPose](https://create.roblox.com/docs/reference/engine/classes/Pose#RemoveSubPose)
    from: {🚧Animation}
    to: {🚧None}
* Update Class [PostEffect](https://create.roblox.com/docs/reference/engine/classes/PostEffect) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [PostEffect.Enabled](https://create.roblox.com/docs/reference/engine/classes/PostEffect#Enabled)
    from: {🚧Read: Environment}
    to: {🚧None}
* Update Class [BloomEffect](https://create.roblox.com/docs/reference/engine/classes/BloomEffect) [⬆️Extends: PostEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [BloomEffect.Intensity](https://create.roblox.com/docs/reference/engine/classes/BloomEffect#Intensity)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [BloomEffect.Size](https://create.roblox.com/docs/reference/engine/classes/BloomEffect#Size)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [BloomEffect.Threshold](https://create.roblox.com/docs/reference/engine/classes/BloomEffect#Threshold)
    from: {🚧Read: Environment}
    to: {🚧None}
* Update Class [BlurEffect](https://create.roblox.com/docs/reference/engine/classes/BlurEffect) [⬆️Extends: PostEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [BlurEffect.Size](https://create.roblox.com/docs/reference/engine/classes/BlurEffect#Size)
    from: {🚧Read: Environment}
    to: {🚧None}
* Update Class [ColorCorrectionEffect](https://create.roblox.com/docs/reference/engine/classes/ColorCorrectionEffect) [⬆️Extends: PostEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [ColorCorrectionEffect.Brightness](https://create.roblox.com/docs/reference/engine/classes/ColorCorrectionEffect#Brightness)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [ColorCorrectionEffect.Contrast](https://create.roblox.com/docs/reference/engine/classes/ColorCorrectionEffect#Contrast)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [ColorCorrectionEffect.Saturation](https://create.roblox.com/docs/reference/engine/classes/ColorCorrectionEffect#Saturation)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [ColorCorrectionEffect.TintColor](https://create.roblox.com/docs/reference/engine/classes/ColorCorrectionEffect#TintColor)
    from: {🚧Read: Environment}
    to: {🚧None}
* Update Class [DepthOfFieldEffect](https://create.roblox.com/docs/reference/engine/classes/DepthOfFieldEffect) [⬆️Extends: PostEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [DepthOfFieldEffect.FarIntensity](https://create.roblox.com/docs/reference/engine/classes/DepthOfFieldEffect#FarIntensity)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [DepthOfFieldEffect.FocusDistance](https://create.roblox.com/docs/reference/engine/classes/DepthOfFieldEffect#FocusDistance)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [DepthOfFieldEffect.InFocusRadius](https://create.roblox.com/docs/reference/engine/classes/DepthOfFieldEffect#InFocusRadius)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [DepthOfFieldEffect.NearIntensity](https://create.roblox.com/docs/reference/engine/classes/DepthOfFieldEffect#NearIntensity)
    from: {🚧Read: Environment}
    to: {🚧None}
* Update Class [SunRaysEffect](https://create.roblox.com/docs/reference/engine/classes/SunRaysEffect) [⬆️Extends: PostEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [SunRaysEffect.Intensity](https://create.roblox.com/docs/reference/engine/classes/SunRaysEffect#Intensity)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [SunRaysEffect.Spread](https://create.roblox.com/docs/reference/engine/classes/SunRaysEffect#Spread)
    from: {🚧Read: Environment}
    to: {🚧None}
* Update Class [ProximityPrompt](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [ProximityPrompt.ActionText](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#ActionText)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.AutoLocalize](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#AutoLocalize)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.ClickablePrompt](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#ClickablePrompt)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.Enabled](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#Enabled)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.Exclusivity](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#Exclusivity)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.GamepadKeyCode](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#GamepadKeyCode)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.HoldDuration](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#HoldDuration)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.KeyboardKeyCode](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#KeyboardKeyCode)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.MaxActivationDistance](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#MaxActivationDistance)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.ObjectText](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#ObjectText)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.RequiresLineOfSight](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#RequiresLineOfSight)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.RootLocalizationTable](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#RootLocalizationTable)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.Style](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#Style)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPrompt.UIOffset](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#UIOffset)
    from: {🚧Read: UI, Input}
    to: {🚧None}
  * Changed the return-type of Function [ProximityPrompt.InputHoldBegin](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#InputHoldBegin) from null to void
  * Changed the capabilities of Function [ProximityPrompt.InputHoldBegin](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#InputHoldBegin)
    from: {🚧UI, Input}
    to: {🚧None}
  * Changed the return-type of Function [ProximityPrompt.InputHoldEnd](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#InputHoldEnd) from null to void
  * Changed the capabilities of Function [ProximityPrompt.InputHoldEnd](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#InputHoldEnd)
    from: {🚧UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPrompt.PromptButtonHoldBegan](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#PromptButtonHoldBegan)
    from: {🚧UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPrompt.PromptButtonHoldEnded](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#PromptButtonHoldEnded)
    from: {🚧UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPrompt.PromptHidden](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#PromptHidden)
    from: {🚧UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPrompt.PromptShown](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#PromptShown)
    from: {🚧UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPrompt.TriggerEnded](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#TriggerEnded)
    from: {🚧UI, Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPrompt.Triggered](https://create.roblox.com/docs/reference/engine/classes/ProximityPrompt#Triggered)
    from: {🚧UI, Input}
    to: {🚧None}
  * Removed Property ProximityPrompt.MaxIndicatorDistance
  * Removed Event ProximityPrompt.IndicatorHidden
  * Removed Event ProximityPrompt.IndicatorShown
* Update Class [ProximityPromptService](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [ProximityPromptService.Enabled](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService#Enabled)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Property [ProximityPromptService.MaxPromptsVisible](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService#MaxPromptsVisible)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPromptService.PromptButtonHoldBegan](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService#PromptButtonHoldBegan)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPromptService.PromptButtonHoldEnded](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService#PromptButtonHoldEnded)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPromptService.PromptHidden](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService#PromptHidden)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPromptService.PromptShown](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService#PromptShown)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPromptService.PromptTriggerEnded](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService#PromptTriggerEnded)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [ProximityPromptService.PromptTriggered](https://create.roblox.com/docs/reference/engine/classes/ProximityPromptService#PromptTriggered)
    from: {🚧Input}
    to: {🚧None}
  * Removed Property ProximityPromptService.MaxIndicatorsVisible
  * Removed Event ProximityPromptService.IndicatorHidden
  * Removed Event ProximityPromptService.IndicatorShown
* Update Class [PublishService](https://create.roblox.com/docs/reference/engine/classes/PublishService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [PublishService.PublishCageMeshAsync](https://create.roblox.com/docs/reference/engine/classes/PublishService#PublishCageMeshAsync) from ContentId to Content [🏷️ Yields]
  * Removed Function PublishService.PublishDescendantAssets
  * Removed Function PublishService.CreateAssetAndWaitForAssetId
  * Removed Function PublishService.CreateAssetOrAssetVersionAndPollAssetWithTelemetryAsync
  * Removed Function PublishService.CreateAssetOrAssetVersionAndPollAssetWithTelemetryAsyncWithAddParam
  * Removed Function PublishService.CreateAssetOrAssetVersionAndPollAssetWithTelemetryAsyncWithAddParamErrorJson
  * Removed Function PublishService.PublishDescendantAssetsAsync
* Update Class [RbxAnalyticsService](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [RbxAnalyticsService.AddGlobalPointsField](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#AddGlobalPointsField) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.AddGlobalPointsTag](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#AddGlobalPointsTag) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.ReleaseRBXEventStream](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReleaseRBXEventStream) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.RemoveGlobalPointsField](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#RemoveGlobalPointsField) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.RemoveGlobalPointsTag](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#RemoveGlobalPointsTag) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.ReportCounter](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReportCounter) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.ReportInfluxSeries](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReportInfluxSeries) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.ReportStats](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReportStats) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.ReportToDiagByCountryCode](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#ReportToDiagByCountryCode) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.SendEventDeferred](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#SendEventDeferred) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.SendEventImmediately](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#SendEventImmediately) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.SetRBXEvent](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#SetRBXEvent) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.SetRBXEventStream](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#SetRBXEventStream) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.TrackEvent](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#TrackEvent) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.TrackEventWithArgs](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#TrackEventWithArgs) from null to void
  * Changed the return-type of Function [RbxAnalyticsService.UpdateHeartbeatObject](https://create.roblox.com/docs/reference/engine/classes/RbxAnalyticsService#UpdateHeartbeatObject) from null to void
  * Removed Function RbxAnalyticsService.DEPRECATED_TrackEvent
  * Removed Function RbxAnalyticsService.DEPRECATED_TrackEventWithArgs
  * Removed Function RbxAnalyticsService.GetPlaySessionId
* Update Class [ReflectionMetadataItem](https://create.roblox.com/docs/reference/engine/classes/ReflectionMetadataItem) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Removed Property ReflectionMetadataItem.SliderScaling
* Update Class [ReflectionMetadataClass](https://create.roblox.com/docs/reference/engine/classes/ReflectionMetadataClass) [⬆️Extends: ReflectionMetadataItem] [🧠Memory: Instances]
  * Removed Property ReflectionMetadataClass.ServiceVisibility
* Update Class [RemoteEvent](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed Superclass of Class [RemoteEvent](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent) from `BaseRemoteEvent` to `Instance`
  * Changed the return-type of Function [RemoteEvent.FireAllClients](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireAllClients) from null to void
  * Changed the capabilities of Function [RemoteEvent.FireAllClients](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireAllClients)
    from: {🚧RemoteEvent}
    to: {🚧None}
  * Changed the return-type of Function [RemoteEvent.FireClient](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireClient) from null to void
  * Changed the capabilities of Function [RemoteEvent.FireClient](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireClient)
    from: {🚧RemoteEvent}
    to: {🚧None}
  * Changed the return-type of Function [RemoteEvent.FireServer](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireServer) from null to void
  * Changed the capabilities of Function [RemoteEvent.FireServer](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#FireServer)
    from: {🚧RemoteEvent}
    to: {🚧None}
  * Changed the capabilities of Event [RemoteEvent.OnClientEvent](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#OnClientEvent)
    from: {🚧RemoteEvent}
    to: {🚧None}
  * Changed the capabilities of Event [RemoteEvent.OnServerEvent](https://create.roblox.com/docs/reference/engine/classes/RemoteEvent#OnServerEvent)
    from: {🚧RemoteEvent}
    to: {🚧None}
* Update Class [RemoteFunction](https://create.roblox.com/docs/reference/engine/classes/RemoteFunction) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Function [RemoteFunction.InvokeClient](https://create.roblox.com/docs/reference/engine/classes/RemoteFunction#InvokeClient)
    from: {🚧RemoteEvent}
    to: {🚧None}
  * Changed the capabilities of Function [RemoteFunction.InvokeServer](https://create.roblox.com/docs/reference/engine/classes/RemoteFunction#InvokeServer)
    from: {🚧RemoteEvent}
    to: {🚧None}
  * Changed the capabilities of Callback [RemoteFunction.OnClientInvoke](https://create.roblox.com/docs/reference/engine/classes/RemoteFunction#OnClientInvoke)
    from: {🚧RemoteEvent}
    to: {🚧None}
  * Changed the parameters of Callback [RemoteFunction.OnServerInvoke](https://create.roblox.com/docs/reference/engine/classes/RemoteFunction#OnServerInvoke)
    from: (player: Player, arguments: Tuple)
    to: (player: Instance, arguments: Tuple)
  * Changed the capabilities of Callback [RemoteFunction.OnServerInvoke](https://create.roblox.com/docs/reference/engine/classes/RemoteFunction#OnServerInvoke)
    from: {🚧RemoteEvent}
    to: {🚧None}
* Update Class [RenderSettings](https://create.roblox.com/docs/reference/engine/classes/RenderSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotBrowsable]
  * Changed the security of Property [RenderSettings.AutoFRMLevel](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#AutoFRMLevel)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.EagerBulkExecution](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#EagerBulkExecution)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.EditQualityLevel](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#EditQualityLevel)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.EnableFRM](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#EnableFRM)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.ExportMergeByMaterial](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#ExportMergeByMaterial)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.FrameRateManager](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#FrameRateManager)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.GraphicsMode](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#GraphicsMode)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.MeshCacheSize](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#MeshCacheSize)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.MeshPartDetailLevel](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#MeshPartDetailLevel)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.QualityLevel](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#QualityLevel)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.ReloadAssets](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#ReloadAssets)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.RenderCSGTrianglesDebug](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#RenderCSGTrianglesDebug)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [RenderSettings.ShowBoundingBoxes](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#ShowBoundingBoxes)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Function [RenderSettings.GetMaxQualityLevel](https://create.roblox.com/docs/reference/engine/classes/RenderSettings#GetMaxQualityLevel)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Removed Property RenderSettings.Enable VR Mode
  * Removed Property RenderSettings.ViewMode
* Update Class [RenderingTest](https://create.roblox.com/docs/reference/engine/classes/RenderingTest) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [RenderingTest.CFrame](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#CFrame)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [RenderingTest.ComparisonDiffThreshold](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#ComparisonDiffThreshold)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [RenderingTest.ComparisonMethod](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#ComparisonMethod)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [RenderingTest.ComparisonPsnrThreshold](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#ComparisonPsnrThreshold)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [RenderingTest.Description](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#Description)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [RenderingTest.FieldOfView](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#FieldOfView)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [RenderingTest.Orientation](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#Orientation)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the serialization of Property [RenderingTest.Orientation](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#Orientation)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [RenderingTest.Position](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#Position)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the serialization of Property [RenderingTest.Position](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#Position)
    from: [🚫None]
    to: [📁LoadOnly]
  * Changed the capabilities of Property [RenderingTest.QualityLevel](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#QualityLevel)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [RenderingTest.ShouldSkip](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#ShouldSkip)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [RenderingTest.Ticket](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#Ticket)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the return-type of Function [RenderingTest.RenderdocTriggerCapture](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#RenderdocTriggerCapture) from null to void
  * Changed the capabilities of Function [RenderingTest.RenderdocTriggerCapture](https://create.roblox.com/docs/reference/engine/classes/RenderingTest#RenderdocTriggerCapture)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Property RenderingTest.PerfTest
  * Removed Property RenderingTest.QualityAuto
  * Removed Property RenderingTest.RenderingTestFrameCount
  * Removed Property RenderingTest.Timeout
  * Removed Event RenderingTest.TestFramesCountdownAboutToStart
* Update Class [ReplicatedFirst](https://create.roblox.com/docs/reference/engine/classes/ReplicatedFirst) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [ReplicatedFirst.RemoveDefaultLoadingScreen](https://create.roblox.com/docs/reference/engine/classes/ReplicatedFirst#RemoveDefaultLoadingScreen) from null to void
  * Changed the return-type of Function [ReplicatedFirst.SetDefaultLoadingGuiRemoved](https://create.roblox.com/docs/reference/engine/classes/ReplicatedFirst#SetDefaultLoadingGuiRemoved) from null to void
* Added Class [ReplicatedScriptService](https://create.roblox.com/docs/reference/engine/classes/ReplicatedScriptService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [RunService.ClientGitHash](https://create.roblox.com/docs/reference/engine/classes/RunService#ClientGitHash)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.BindToRenderStep](https://create.roblox.com/docs/reference/engine/classes/RunService#BindToRenderStep) from null to void
  * Changed the capabilities of Function [RunService.BindToRenderStep](https://create.roblox.com/docs/reference/engine/classes/RunService#BindToRenderStep)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [RunService.GetCoreScriptVersion](https://create.roblox.com/docs/reference/engine/classes/RunService#GetCoreScriptVersion)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [RunService.GetRobloxVersion](https://create.roblox.com/docs/reference/engine/classes/RunService#GetRobloxVersion)
    from: {🚧Basic}
    to: {🚧None}
  * Changed ThreadSafety of Function [RunService.IsClient](https://create.roblox.com/docs/reference/engine/classes/RunService#IsClient) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [RunService.IsClient](https://create.roblox.com/docs/reference/engine/classes/RunService#IsClient)
    from: {🚧Basic}
    to: {🚧None}
  * Changed ThreadSafety of Function [RunService.IsEdit](https://create.roblox.com/docs/reference/engine/classes/RunService#IsEdit) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [RunService.IsEdit](https://create.roblox.com/docs/reference/engine/classes/RunService#IsEdit)
    from: {🚧Basic}
    to: {🚧None}
  * Changed ThreadSafety of Function [RunService.IsRunMode](https://create.roblox.com/docs/reference/engine/classes/RunService#IsRunMode) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [RunService.IsRunMode](https://create.roblox.com/docs/reference/engine/classes/RunService#IsRunMode)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [RunService.IsRunning](https://create.roblox.com/docs/reference/engine/classes/RunService#IsRunning)
    from: {🚧Basic}
    to: {🚧None}
  * Changed ThreadSafety of Function [RunService.IsServer](https://create.roblox.com/docs/reference/engine/classes/RunService#IsServer) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [RunService.IsServer](https://create.roblox.com/docs/reference/engine/classes/RunService#IsServer)
    from: {🚧Basic}
    to: {🚧None}
  * Changed ThreadSafety of Function [RunService.IsStudio](https://create.roblox.com/docs/reference/engine/classes/RunService#IsStudio) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [RunService.IsStudio](https://create.roblox.com/docs/reference/engine/classes/RunService#IsStudio)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.Pause](https://create.roblox.com/docs/reference/engine/classes/RunService#Pause) from null to void
  * Changed the capabilities of Function [RunService.Pause](https://create.roblox.com/docs/reference/engine/classes/RunService#Pause)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.Reset](https://create.roblox.com/docs/reference/engine/classes/RunService#Reset) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [RunService.Reset](https://create.roblox.com/docs/reference/engine/classes/RunService#Reset)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.Run](https://create.roblox.com/docs/reference/engine/classes/RunService#Run) from null to void
  * Changed the capabilities of Function [RunService.Run](https://create.roblox.com/docs/reference/engine/classes/RunService#Run)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.Set3dRenderingEnabled](https://create.roblox.com/docs/reference/engine/classes/RunService#Set3dRenderingEnabled) from null to void
  * Changed the capabilities of Function [RunService.Set3dRenderingEnabled](https://create.roblox.com/docs/reference/engine/classes/RunService#Set3dRenderingEnabled)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.SetRobloxGuiFocused](https://create.roblox.com/docs/reference/engine/classes/RunService#SetRobloxGuiFocused) from null to void
  * Changed the capabilities of Function [RunService.SetRobloxGuiFocused](https://create.roblox.com/docs/reference/engine/classes/RunService#SetRobloxGuiFocused)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.Stop](https://create.roblox.com/docs/reference/engine/classes/RunService#Stop) from null to void
  * Changed the capabilities of Function [RunService.Stop](https://create.roblox.com/docs/reference/engine/classes/RunService#Stop)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.UnbindFromRenderStep](https://create.roblox.com/docs/reference/engine/classes/RunService#UnbindFromRenderStep) from null to void
  * Changed the capabilities of Function [RunService.UnbindFromRenderStep](https://create.roblox.com/docs/reference/engine/classes/RunService#UnbindFromRenderStep)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [RunService.setThrottleFramerateEnabled](https://create.roblox.com/docs/reference/engine/classes/RunService#setThrottleFramerateEnabled) from null to void
  * Changed the capabilities of Function [RunService.setThrottleFramerateEnabled](https://create.roblox.com/docs/reference/engine/classes/RunService#setThrottleFramerateEnabled)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [RunService.Heartbeat](https://create.roblox.com/docs/reference/engine/classes/RunService#Heartbeat)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the parameters of Event [RunService.PostSimulation](https://create.roblox.com/docs/reference/engine/classes/RunService#PostSimulation)
    from: (deltaTimeSim: double)
    to: (deltaTime: double)
  * Changed the capabilities of Event [RunService.PostSimulation](https://create.roblox.com/docs/reference/engine/classes/RunService#PostSimulation)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the parameters of Event [RunService.PreAnimation](https://create.roblox.com/docs/reference/engine/classes/RunService#PreAnimation)
    from: (deltaTimeSim: double)
    to: (deltaTime: double)
  * Changed the capabilities of Event [RunService.PreAnimation](https://create.roblox.com/docs/reference/engine/classes/RunService#PreAnimation)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the parameters of Event [RunService.PreRender](https://create.roblox.com/docs/reference/engine/classes/RunService#PreRender)
    from: (deltaTimeRender: double)
    to: (deltaTime: double)
  * Changed the capabilities of Event [RunService.PreRender](https://create.roblox.com/docs/reference/engine/classes/RunService#PreRender)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the parameters of Event [RunService.PreSimulation](https://create.roblox.com/docs/reference/engine/classes/RunService#PreSimulation)
    from: (deltaTimeSim: double)
    to: (deltaTime: double)
  * Changed the capabilities of Event [RunService.PreSimulation](https://create.roblox.com/docs/reference/engine/classes/RunService#PreSimulation)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [RunService.RenderStepped](https://create.roblox.com/docs/reference/engine/classes/RunService#RenderStepped)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [RunService.Stepped](https://create.roblox.com/docs/reference/engine/classes/RunService#Stepped)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Property RunService.FrameNumber
  * Removed Property RunService.RunState
  * Removed Function RunService.BindToSimulation
  * Removed Function RunService.GetControlAndVariantRolloutFlags
  * Removed Function RunService.GetPhysicsStepId
  * Removed Function RunService.GetPredictionStatus
  * Removed Function RunService.GetRobloxClientChannel
  * Removed Function RunService.GetRobloxGuiFocused
  * Removed Function RunService.GetTotalScriptPlusExecutionTime
  * Removed Function RunService.IsResimulating
  * Removed Function RunService.SetPredictionMode
  * Removed Function RunService.getThrottleFramerateEnabled
  * Removed Event RunService.Misprediction
  * Removed Event RunService.RobloxGuiFocusedChanged
  * Removed Event RunService.Rollback
* Update Class [ScriptContext](https://create.roblox.com/docs/reference/engine/classes/ScriptContext) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [ScriptContext.AddCoreScriptLocal](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#AddCoreScriptLocal) from null to void
  * Changed the security of Function [ScriptContext.GetCoverageStats](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#GetCoverageStats)
    from: {🔒None}
    to: {🔒RobloxScriptSecurity}
  * Changed the capabilities of Function [ScriptContext.GetCoverageStats](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#GetCoverageStats)
    from: {🚧PluginOrOpenCloud}
    to: {🚧None}
  * Changed the return-type of Function [ScriptContext.SetTimeout](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#SetTimeout) from null to void
  * Changed the capabilities of Event [ScriptContext.Error](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#Error)
    from: {🚧Logging}
    to: {🚧None}
  * Changed the parameters of Event [ScriptContext.ErrorDetailed](https://create.roblox.com/docs/reference/engine/classes/ScriptContext#ErrorDetailed)
    from: (message: string, stackTrace: string, script: Instance, details: string, securityLevel: int, messageId: string)
    to: (message: string, stackTrace: string, script: Instance, details: string, securityLevel: int)
  * Removed Function ScriptContext.CompressLuaApp
  * Removed Function ScriptContext.EnableCoverage
  * Removed Function ScriptContext.GetLuauHeapInstanceReferenceReport
  * Removed Function ScriptContext.GetLuauHeapMemoryReport
  * Removed Function ScriptContext.ReportLuaRequireCount
* Update Class [ScriptDebugger](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [ScriptDebugger.GetBreakpoints](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#GetBreakpoints) from Instances to Objects
  * Changed the return-type of Function [ScriptDebugger.GetWatches](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#GetWatches) from Instances to Objects
  * Changed the return-type of Function [ScriptDebugger.SetGlobal](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#SetGlobal) from null to void
  * Changed the return-type of Function [ScriptDebugger.SetLocal](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#SetLocal) from null to void
  * Changed the return-type of Function [ScriptDebugger.SetUpvalue](https://create.roblox.com/docs/reference/engine/classes/ScriptDebugger#SetUpvalue) from null to void
* Added Class [ScriptRef](https://create.roblox.com/docs/reference/engine/classes/ScriptRef) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
* Added Class [ScriptRefId](https://create.roblox.com/docs/reference/engine/classes/ScriptRefId) {🔒None} [⬆️Extends: ScriptRef] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
* Added Class [ScriptRefPath](https://create.roblox.com/docs/reference/engine/classes/ScriptRefPath) {🔒None} [⬆️Extends: ScriptRef] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
* Update Class [Selection](https://create.roblox.com/docs/reference/engine/classes/Selection) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [Selection.ActiveInstance](https://create.roblox.com/docs/reference/engine/classes/Selection#ActiveInstance)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Selection.SelectionThickness](https://create.roblox.com/docs/reference/engine/classes/Selection#SelectionThickness)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the return-type of Function [Selection.Add](https://create.roblox.com/docs/reference/engine/classes/Selection#Add) from null to void
  * Changed the parameters of Function [Selection.Add](https://create.roblox.com/docs/reference/engine/classes/Selection#Add)
    from: (instancesToAdd: Instances)
    to: (instancesToAdd: Objects)
  * Changed the capabilities of Function [Selection.Add](https://create.roblox.com/docs/reference/engine/classes/Selection#Add)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Selection.ClearTerrainSelectionHack](https://create.roblox.com/docs/reference/engine/classes/Selection#ClearTerrainSelectionHack) from null to void
  * Changed the capabilities of Function [Selection.ClearTerrainSelectionHack](https://create.roblox.com/docs/reference/engine/classes/Selection#ClearTerrainSelectionHack)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Selection.Get](https://create.roblox.com/docs/reference/engine/classes/Selection#Get) from Instances to Objects
  * Changed the capabilities of Function [Selection.Get](https://create.roblox.com/docs/reference/engine/classes/Selection#Get)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Selection.Remove](https://create.roblox.com/docs/reference/engine/classes/Selection#Remove) from null to void
  * Changed the parameters of Function [Selection.Remove](https://create.roblox.com/docs/reference/engine/classes/Selection#Remove)
    from: (instancesToRemove: Instances)
    to: (instancesToRemove: Objects)
  * Changed the capabilities of Function [Selection.Remove](https://create.roblox.com/docs/reference/engine/classes/Selection#Remove)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Selection.Set](https://create.roblox.com/docs/reference/engine/classes/Selection#Set) from null to void
  * Changed the parameters of Function [Selection.Set](https://create.roblox.com/docs/reference/engine/classes/Selection#Set)
    from: (selection: Instances)
    to: (selection: Objects)
  * Changed the capabilities of Function [Selection.Set](https://create.roblox.com/docs/reference/engine/classes/Selection#Set)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the return-type of Function [Selection.SetTerrainSelectionHack](https://create.roblox.com/docs/reference/engine/classes/Selection#SetTerrainSelectionHack) from null to void
  * Changed the capabilities of Function [Selection.SetTerrainSelectionHack](https://create.roblox.com/docs/reference/engine/classes/Selection#SetTerrainSelectionHack)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Event [Selection.SelectionChanged](https://create.roblox.com/docs/reference/engine/classes/Selection#SelectionChanged)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Property Selection.RenderMode
  * Removed Property Selection.SelectionBoxThickness
  * Removed Property Selection.SelectionLineThickness
  * Removed Property Selection.ShowActiveInstanceHighlight
  * Removed Function Selection.AddFocusCallback
  * Removed Event Selection.SelectionChangedThisFrame
* Update Class [ServerScriptService](https://create.roblox.com/docs/reference/engine/classes/ServerScriptService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [ServerScriptService.LoadStringEnabled](https://create.roblox.com/docs/reference/engine/classes/ServerScriptService#LoadStringEnabled)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [ServiceProvider](https://create.roblox.com/docs/reference/engine/classes/ServiceProvider) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed ThreadSafety of Function [ServiceProvider.GetService](https://create.roblox.com/docs/reference/engine/classes/ServiceProvider#GetService) from `Unsafe` to `Safe`
* Update Class [DataModel](https://create.roblox.com/docs/reference/engine/classes/DataModel) [⬆️Extends: ServiceProvider] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the return-type of Function [DataModel.BindToClose](https://create.roblox.com/docs/reference/engine/classes/DataModel#BindToClose) from null to void
  * Changed the return-type of Function [DataModel.GetObjects](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetObjects) from Instances to Objects
  * Changed the parameters of Function [DataModel.GetObjects](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetObjects)
    from: (url: ContentId)
    to: (url: Content)
  * Changed the return-type of Function [DataModel.Load](https://create.roblox.com/docs/reference/engine/classes/DataModel#Load) from null to void
  * Changed the parameters of Function [DataModel.Load](https://create.roblox.com/docs/reference/engine/classes/DataModel#Load)
    from: (url: ContentId)
    to: (url: Content)
  * Changed the return-type of Function [DataModel.OpenScreenshotsFolder](https://create.roblox.com/docs/reference/engine/classes/DataModel#OpenScreenshotsFolder) from null to void
  * Changed the return-type of Function [DataModel.OpenVideosFolder](https://create.roblox.com/docs/reference/engine/classes/DataModel#OpenVideosFolder) from null to void
  * Added Function [DataModel.ReportInGoogleAnalytics](https://create.roblox.com/docs/reference/engine/classes/DataModel#ReportInGoogleAnalytics) (category: string, action: string = custom, label: string = none, value: int = 0) -> void
  * Changed the return-type of Function [DataModel.SetPlaceId](https://create.roblox.com/docs/reference/engine/classes/DataModel#SetPlaceId) from null to void
  * Changed the return-type of Function [DataModel.SetUniverseId](https://create.roblox.com/docs/reference/engine/classes/DataModel#SetUniverseId) from null to void
  * Changed the return-type of Function [DataModel.Shutdown](https://create.roblox.com/docs/reference/engine/classes/DataModel#Shutdown) from null to void
  * Changed the return-type of Function [DataModel.GetObjectsAsync](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetObjectsAsync) from Instances to Objects [🏷️ Yields]
  * Changed the parameters of Function [DataModel.GetObjectsAsync](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetObjectsAsync)
    from: (url: ContentId)
    to: (url: Content)
  * Changed the return-type of Function [DataModel.InsertObjectsAndJoinIfLegacyAsync](https://create.roblox.com/docs/reference/engine/classes/DataModel#InsertObjectsAndJoinIfLegacyAsync) from Instances to Objects [🏷️ Yields]
  * Changed the parameters of Function [DataModel.InsertObjectsAndJoinIfLegacyAsync](https://create.roblox.com/docs/reference/engine/classes/DataModel#InsertObjectsAndJoinIfLegacyAsync)
    from: (url: ContentId)
    to: (url: Content)
  * Removed Property DataModel.Environment
  * Removed Property DataModel.IsPioneerBuild
  * Removed Property DataModel.MatchmakingType
  * Removed Property DataModel.PioneerSource
  * Removed Property DataModel.RunService
  * Removed Function DataModel.GetPlaySessionId
  * Removed Function DataModel.IsContentLoaded
  * Removed Function DataModel.IsUniverseMetadataLoaded
  * Removed Function DataModel.OpenLogsFolder
  * Removed Function DataModel.SetFlagVersion
  * Removed Function DataModel.SetIsLoaded
  * Removed Function DataModel.getGameTime
  * Removed Function DataModel.GetObjectsAllOrNone
  * Removed Event DataModel.ServerLifecycleChanged
  * Removed Event DataModel.ServerRestartScheduled
  * Removed Event DataModel.UniverseMetadataLoaded
* Added Class [AnalysticsSettings](https://create.roblox.com/docs/reference/engine/classes/AnalysticsSettings) {🔒None} [⬆️Extends: GenericSettings] [🧠Memory: Instances] [🏷️ NotCreatable]
* Update Class [GlobalSettings](https://create.roblox.com/docs/reference/engine/classes/GlobalSettings) [⬆️Extends: GenericSettings] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Removed Function GlobalSettings.GetFFlagOverrides
  * Removed Function GlobalSettings.GetFFlags
  * Removed Function GlobalSettings.SetFFlagOverrides
* Update Class [UserSettings](https://create.roblox.com/docs/reference/engine/classes/UserSettings) [⬆️Extends: GenericSettings] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Function [UserSettings.IsUserFeatureEnabled](https://create.roblox.com/docs/reference/engine/classes/UserSettings#IsUserFeatureEnabled)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [UserSettings.Reset](https://create.roblox.com/docs/reference/engine/classes/UserSettings#Reset) from null to void
  * Changed the capabilities of Function [UserSettings.Reset](https://create.roblox.com/docs/reference/engine/classes/UserSettings#Reset)
    from: {🚧Players}
    to: {🚧None}
  * Removed Function UserSettings.SaveState
* Update Class [SessionService](https://create.roblox.com/docs/reference/engine/classes/SessionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [SessionService.RemoveMetadata](https://create.roblox.com/docs/reference/engine/classes/SessionService#RemoveMetadata) from null to void
  * Changed the parameters of Function [SessionService.RemoveMetadata](https://create.roblox.com/docs/reference/engine/classes/SessionService#RemoveMetadata)
    from: (sid: string, key: string, context: string = )
    to: (sid: string, key: string)
  * Changed the return-type of Function [SessionService.RemoveSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#RemoveSession) from null to void
  * Changed the parameters of Function [SessionService.RemoveSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#RemoveSession)
    from: (sid: string, context: string = )
    to: (sid: string)
  * Changed the return-type of Function [SessionService.ReplaceSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#ReplaceSession) from null to void
  * Changed the return-type of Function [SessionService.SetMetadata](https://create.roblox.com/docs/reference/engine/classes/SessionService#SetMetadata) from null to void
  * Changed the parameters of Function [SessionService.SetMetadata](https://create.roblox.com/docs/reference/engine/classes/SessionService#SetMetadata)
    from: (sid: string, key: string, value: Variant, context: string = )
    to: (sid: string, key: string, value: Variant)
  * Changed the return-type of Function [SessionService.SetSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#SetSession) from null to void
  * Changed the parameters of Function [SessionService.SetSession](https://create.roblox.com/docs/reference/engine/classes/SessionService#SetSession)
    from: (parentSid: string, childSid: string, tag: string, context: string = )
    to: (parentSid: string, childSid: string, tag: string)
  * Removed Function SessionService.AcquireContextFocus
  * Removed Function SessionService.GenerateSessionInfoString
  * Removed Function SessionService.GetBreadcrumbs
  * Removed Function SessionService.GetHistory
  * Removed Function SessionService.GetSessionID
  * Removed Function SessionService.GetSessionTag
  * Removed Function SessionService.IsContextFocused
  * Removed Function SessionService.ReleaseContextFocus
  * Removed Function SessionService.RemoveSessionsWithMetadataKey
  * Removed Event SessionService.SessionChanged
* Update Class [Sky](https://create.roblox.com/docs/reference/engine/classes/Sky) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Sky.CelestialBodiesShown](https://create.roblox.com/docs/reference/engine/classes/Sky#CelestialBodiesShown)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.MoonAngularSize](https://create.roblox.com/docs/reference/engine/classes/Sky#MoonAngularSize)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.MoonTextureId](https://create.roblox.com/docs/reference/engine/classes/Sky#MoonTextureId)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.SkyboxBk](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxBk)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.SkyboxDn](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxDn)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.SkyboxFt](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxFt)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.SkyboxLf](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxLf)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.SkyboxRt](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxRt)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.SkyboxUp](https://create.roblox.com/docs/reference/engine/classes/Sky#SkyboxUp)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.StarCount](https://create.roblox.com/docs/reference/engine/classes/Sky#StarCount)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.SunAngularSize](https://create.roblox.com/docs/reference/engine/classes/Sky#SunAngularSize)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [Sky.SunTextureId](https://create.roblox.com/docs/reference/engine/classes/Sky#SunTextureId)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Removed Property Sky.MoonTextureContent
  * Removed Property Sky.SkyboxBackContent
  * Removed Property Sky.SkyboxDownContent
  * Removed Property Sky.SkyboxFrontContent
  * Removed Property Sky.SkyboxLeftContent
  * Removed Property Sky.SkyboxOrientation
  * Removed Property Sky.SkyboxRightContent
  * Removed Property Sky.SkyboxUpContent
  * Removed Property Sky.SunTextureContent
* Update Class [Smoke](https://create.roblox.com/docs/reference/engine/classes/Smoke) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Smoke.Color](https://create.roblox.com/docs/reference/engine/classes/Smoke#Color)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Smoke.Enabled](https://create.roblox.com/docs/reference/engine/classes/Smoke#Enabled)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Smoke.Opacity](https://create.roblox.com/docs/reference/engine/classes/Smoke#Opacity)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Smoke.RiseVelocity](https://create.roblox.com/docs/reference/engine/classes/Smoke#RiseVelocity)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Smoke.Size](https://create.roblox.com/docs/reference/engine/classes/Smoke#Size)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Removed Property Smoke.LocalTransparencyModifier
  * Removed Property Smoke.TimeScale
  * Removed Function Smoke.FastForward
* Update Class [SocialService](https://create.roblox.com/docs/reference/engine/classes/SocialService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [SocialService.InvokeGameInvitePromptClosed](https://create.roblox.com/docs/reference/engine/classes/SocialService#InvokeGameInvitePromptClosed) from null to void
  * Changed the capabilities of Function [SocialService.InvokeGameInvitePromptClosed](https://create.roblox.com/docs/reference/engine/classes/SocialService#InvokeGameInvitePromptClosed)
    from: {🚧Social}
    to: {🚧None}
  * Changed the return-type of Function [SocialService.PromptGameInvite](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptGameInvite) from null to void
  * Changed the parameters of Function [SocialService.PromptGameInvite](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptGameInvite)
    from: (player: Instance, experienceInviteOptions: Instance = nil)
    to: (player: Instance)
  * Changed the capabilities of Function [SocialService.PromptGameInvite](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptGameInvite)
    from: {🚧Social}
    to: {🚧None}
  * Changed the parameters of Function [SocialService.CanSendGameInviteAsync](https://create.roblox.com/docs/reference/engine/classes/SocialService#CanSendGameInviteAsync)
    from: (player: Instance, recipientId: User = U1.AQAAAAAAAAAAAAAAAAAAAAA)
    to: (player: Instance)
  * Changed the capabilities of Function [SocialService.CanSendGameInviteAsync](https://create.roblox.com/docs/reference/engine/classes/SocialService#CanSendGameInviteAsync)
    from: {🚧Social}
    to: {🚧None}
  * Changed the capabilities of Event [SocialService.GameInvitePromptClosed](https://create.roblox.com/docs/reference/engine/classes/SocialService#GameInvitePromptClosed)
    from: {🚧Social}
    to: {🚧None}
  * Changed the parameters of Event [SocialService.PromptInviteRequested](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptInviteRequested)
    from: (player: Instance, experienceInviteOptions: Instance)
    to: (player: Instance)
  * Changed the capabilities of Event [SocialService.PromptInviteRequested](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptInviteRequested)
    from: {🚧Social}
    to: {🚧None}
  * Removed Function SocialService.GetPlayersByPartyId
  * Removed Function SocialService.HideSelfView
  * Removed Function SocialService.InvokeIrisInvite
  * Removed Function SocialService.InvokeIrisInvitePromptClosed
  * Removed Function SocialService.InvokeShareSheetClosed
  * Removed Function SocialService.PromptPhoneBook
  * Removed Function SocialService.PromptRsvpToEventCompleted
  * Removed Function SocialService.ShowSelfView
  * Removed Function SocialService.SignalFeedbackSubmissionCompleted
  * Removed Function SocialService.SignalFeedbackSubmissionPermissionDenied
  * Removed Function SocialService.UpdatePlayerPartyData
  * Removed Function SocialService.CanSendCallInviteAsync
  * Removed Function SocialService.GetEventRsvpStatusAsync
  * Removed Function SocialService.GetExperienceEventAsync
  * Removed Function SocialService.GetPartyAsync
  * Removed Function SocialService.GetUpcomingExperienceEventsAsync
  * Removed Function SocialService.PromptFeedbackSubmissionAsync
  * Removed Function SocialService.PromptLinkSharing
  * Removed Function SocialService.PromptLinkSharingAsync
  * Removed Function SocialService.PromptRsvpToEventAsync
  * Removed Event SocialService.CallInviteStateChanged
  * Removed Event SocialService.OpenShareSheetWithLink
  * Removed Event SocialService.PhoneBookPromptClosed
  * Removed Event SocialService.PlayerPartyDataChanged
  * Removed Event SocialService.PromptIrisInviteRequested
  * Removed Event SocialService.SelfViewHidden
  * Removed Event SocialService.SelfViewVisible
  * Removed Event SocialService.ShareSheetClosed
  * Removed Event SocialService.ShowPromptFeedbackSubmission
  * Removed Event SocialService.ShowPromptFeedbackUnavailable
  * Removed Event SocialService.ShowPromptRsvpToEvent
  * Removed Callback SocialService.OnCallInviteInvoked
* Update Class [Sound](https://create.roblox.com/docs/reference/engine/classes/Sound) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Changed the capabilities of Property [Sound.ChannelCount](https://create.roblox.com/docs/reference/engine/classes/Sound#ChannelCount)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.EmitterSize](https://create.roblox.com/docs/reference/engine/classes/Sound#EmitterSize)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the serialization of Property [Sound.EmitterSize](https://create.roblox.com/docs/reference/engine/classes/Sound#EmitterSize)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the capabilities of Property [Sound.IsLoaded](https://create.roblox.com/docs/reference/engine/classes/Sound#IsLoaded)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.IsPaused](https://create.roblox.com/docs/reference/engine/classes/Sound#IsPaused)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.IsPlaying](https://create.roblox.com/docs/reference/engine/classes/Sound#IsPlaying)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.Looped](https://create.roblox.com/docs/reference/engine/classes/Sound#Looped)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.MaxDistance](https://create.roblox.com/docs/reference/engine/classes/Sound#MaxDistance)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.MinDistance](https://create.roblox.com/docs/reference/engine/classes/Sound#MinDistance)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.Pitch](https://create.roblox.com/docs/reference/engine/classes/Sound#Pitch)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.PlayOnRemove](https://create.roblox.com/docs/reference/engine/classes/Sound#PlayOnRemove)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.PlaybackLoudness](https://create.roblox.com/docs/reference/engine/classes/Sound#PlaybackLoudness)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.PlaybackSpeed](https://create.roblox.com/docs/reference/engine/classes/Sound#PlaybackSpeed)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.Playing](https://create.roblox.com/docs/reference/engine/classes/Sound#Playing)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.RollOffMaxDistance](https://create.roblox.com/docs/reference/engine/classes/Sound#RollOffMaxDistance)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the serialization of Property [Sound.RollOffMaxDistance](https://create.roblox.com/docs/reference/engine/classes/Sound#RollOffMaxDistance)
    from: [💾|📁Serialized]
    to: [🚫None]
  * Changed the capabilities of Property [Sound.RollOffMinDistance](https://create.roblox.com/docs/reference/engine/classes/Sound#RollOffMinDistance)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the serialization of Property [Sound.RollOffMinDistance](https://create.roblox.com/docs/reference/engine/classes/Sound#RollOffMinDistance)
    from: [💾|📁Serialized]
    to: [🚫None]
  * Changed the capabilities of Property [Sound.RollOffMode](https://create.roblox.com/docs/reference/engine/classes/Sound#RollOffMode)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.SoundGroup](https://create.roblox.com/docs/reference/engine/classes/Sound#SoundGroup)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.SoundId](https://create.roblox.com/docs/reference/engine/classes/Sound#SoundId)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.TimeLength](https://create.roblox.com/docs/reference/engine/classes/Sound#TimeLength)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.TimePosition](https://create.roblox.com/docs/reference/engine/classes/Sound#TimePosition)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.Volume](https://create.roblox.com/docs/reference/engine/classes/Sound#Volume)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [Sound.isPlaying](https://create.roblox.com/docs/reference/engine/classes/Sound#isPlaying)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the return-type of Function [Sound.Pause](https://create.roblox.com/docs/reference/engine/classes/Sound#Pause) from null to void
  * Changed the capabilities of Function [Sound.Pause](https://create.roblox.com/docs/reference/engine/classes/Sound#Pause)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the return-type of Function [Sound.Play](https://create.roblox.com/docs/reference/engine/classes/Sound#Play) from null to void
  * Changed the capabilities of Function [Sound.Play](https://create.roblox.com/docs/reference/engine/classes/Sound#Play)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the return-type of Function [Sound.Resume](https://create.roblox.com/docs/reference/engine/classes/Sound#Resume) from null to void
  * Changed the capabilities of Function [Sound.Resume](https://create.roblox.com/docs/reference/engine/classes/Sound#Resume)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the return-type of Function [Sound.Stop](https://create.roblox.com/docs/reference/engine/classes/Sound#Stop) from null to void
  * Changed the capabilities of Function [Sound.Stop](https://create.roblox.com/docs/reference/engine/classes/Sound#Stop)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the return-type of Function [Sound.pause](https://create.roblox.com/docs/reference/engine/classes/Sound#pause) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Sound.pause](https://create.roblox.com/docs/reference/engine/classes/Sound#pause)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the return-type of Function [Sound.play](https://create.roblox.com/docs/reference/engine/classes/Sound#play) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Sound.play](https://create.roblox.com/docs/reference/engine/classes/Sound#play)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the return-type of Function [Sound.stop](https://create.roblox.com/docs/reference/engine/classes/Sound#stop) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Sound.stop](https://create.roblox.com/docs/reference/engine/classes/Sound#stop)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the capabilities of Event [Sound.DidLoop](https://create.roblox.com/docs/reference/engine/classes/Sound#DidLoop)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the capabilities of Event [Sound.Ended](https://create.roblox.com/docs/reference/engine/classes/Sound#Ended)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the capabilities of Event [Sound.Loaded](https://create.roblox.com/docs/reference/engine/classes/Sound#Loaded)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the capabilities of Event [Sound.Paused](https://create.roblox.com/docs/reference/engine/classes/Sound#Paused)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the capabilities of Event [Sound.Played](https://create.roblox.com/docs/reference/engine/classes/Sound#Played)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the capabilities of Event [Sound.Resumed](https://create.roblox.com/docs/reference/engine/classes/Sound#Resumed)
    from: {🚧LegacySound}
    to: {🚧None}
  * Changed the capabilities of Event [Sound.Stopped](https://create.roblox.com/docs/reference/engine/classes/Sound#Stopped)
    from: {🚧LegacySound}
    to: {🚧None}
  * Removed Property Sound.AcousticSimulationEnabled
  * Removed Property Sound.AssetRepresentation
  * Removed Property Sound.AudioContent
  * Removed Property Sound.IsSpatial
  * Removed Property Sound.LoopRegion
  * Removed Property Sound.PlaybackRegion
  * Removed Property Sound.PlaybackRegionsEnabled
  * Removed Property Sound.RollOffGain
  * Removed Property Sound.UsageContextPermission
  * Removed Function Sound.GetUnderlyingAudioPlayer
* Update Class [SoundEffect](https://create.roblox.com/docs/reference/engine/classes/SoundEffect) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [SoundEffect.Enabled](https://create.roblox.com/docs/reference/engine/classes/SoundEffect#Enabled)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [SoundEffect.Priority](https://create.roblox.com/docs/reference/engine/classes/SoundEffect#Priority)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [ChannelSelectorSoundEffect](https://create.roblox.com/docs/reference/engine/classes/ChannelSelectorSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Changed Superclass of Class [ChannelSelectorSoundEffect](https://create.roblox.com/docs/reference/engine/classes/ChannelSelectorSoundEffect) from `CustomSoundEffect` to `SoundEffect`
  * Changed the capabilities of Property [ChannelSelectorSoundEffect.Channel](https://create.roblox.com/docs/reference/engine/classes/ChannelSelectorSoundEffect#Channel)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [ChorusSoundEffect](https://create.roblox.com/docs/reference/engine/classes/ChorusSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [ChorusSoundEffect.Depth](https://create.roblox.com/docs/reference/engine/classes/ChorusSoundEffect#Depth)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [ChorusSoundEffect.Mix](https://create.roblox.com/docs/reference/engine/classes/ChorusSoundEffect#Mix)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [ChorusSoundEffect.Rate](https://create.roblox.com/docs/reference/engine/classes/ChorusSoundEffect#Rate)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [CompressorSoundEffect](https://create.roblox.com/docs/reference/engine/classes/CompressorSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [CompressorSoundEffect.Attack](https://create.roblox.com/docs/reference/engine/classes/CompressorSoundEffect#Attack)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [CompressorSoundEffect.GainMakeup](https://create.roblox.com/docs/reference/engine/classes/CompressorSoundEffect#GainMakeup)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [CompressorSoundEffect.Ratio](https://create.roblox.com/docs/reference/engine/classes/CompressorSoundEffect#Ratio)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [CompressorSoundEffect.Release](https://create.roblox.com/docs/reference/engine/classes/CompressorSoundEffect#Release)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [CompressorSoundEffect.SideChain](https://create.roblox.com/docs/reference/engine/classes/CompressorSoundEffect#SideChain)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [CompressorSoundEffect.Threshold](https://create.roblox.com/docs/reference/engine/classes/CompressorSoundEffect#Threshold)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [DistortionSoundEffect](https://create.roblox.com/docs/reference/engine/classes/DistortionSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [DistortionSoundEffect.Level](https://create.roblox.com/docs/reference/engine/classes/DistortionSoundEffect#Level)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [EchoSoundEffect](https://create.roblox.com/docs/reference/engine/classes/EchoSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [EchoSoundEffect.Delay](https://create.roblox.com/docs/reference/engine/classes/EchoSoundEffect#Delay)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [EchoSoundEffect.DryLevel](https://create.roblox.com/docs/reference/engine/classes/EchoSoundEffect#DryLevel)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [EchoSoundEffect.Feedback](https://create.roblox.com/docs/reference/engine/classes/EchoSoundEffect#Feedback)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [EchoSoundEffect.WetLevel](https://create.roblox.com/docs/reference/engine/classes/EchoSoundEffect#WetLevel)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [EqualizerSoundEffect](https://create.roblox.com/docs/reference/engine/classes/EqualizerSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [EqualizerSoundEffect.HighGain](https://create.roblox.com/docs/reference/engine/classes/EqualizerSoundEffect#HighGain)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [EqualizerSoundEffect.LowGain](https://create.roblox.com/docs/reference/engine/classes/EqualizerSoundEffect#LowGain)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [EqualizerSoundEffect.MidGain](https://create.roblox.com/docs/reference/engine/classes/EqualizerSoundEffect#MidGain)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [FlangeSoundEffect](https://create.roblox.com/docs/reference/engine/classes/FlangeSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [FlangeSoundEffect.Depth](https://create.roblox.com/docs/reference/engine/classes/FlangeSoundEffect#Depth)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [FlangeSoundEffect.Mix](https://create.roblox.com/docs/reference/engine/classes/FlangeSoundEffect#Mix)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [FlangeSoundEffect.Rate](https://create.roblox.com/docs/reference/engine/classes/FlangeSoundEffect#Rate)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [PitchShiftSoundEffect](https://create.roblox.com/docs/reference/engine/classes/PitchShiftSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [PitchShiftSoundEffect.Octave](https://create.roblox.com/docs/reference/engine/classes/PitchShiftSoundEffect#Octave)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [ReverbSoundEffect](https://create.roblox.com/docs/reference/engine/classes/ReverbSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [ReverbSoundEffect.DecayTime](https://create.roblox.com/docs/reference/engine/classes/ReverbSoundEffect#DecayTime)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [ReverbSoundEffect.Density](https://create.roblox.com/docs/reference/engine/classes/ReverbSoundEffect#Density)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [ReverbSoundEffect.Diffusion](https://create.roblox.com/docs/reference/engine/classes/ReverbSoundEffect#Diffusion)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [ReverbSoundEffect.DryLevel](https://create.roblox.com/docs/reference/engine/classes/ReverbSoundEffect#DryLevel)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [ReverbSoundEffect.WetLevel](https://create.roblox.com/docs/reference/engine/classes/ReverbSoundEffect#WetLevel)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [TremoloSoundEffect](https://create.roblox.com/docs/reference/engine/classes/TremoloSoundEffect) [⬆️Extends: SoundEffect] [🧠Memory: Instances]
  * Changed the capabilities of Property [TremoloSoundEffect.Depth](https://create.roblox.com/docs/reference/engine/classes/TremoloSoundEffect#Depth)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [TremoloSoundEffect.Duty](https://create.roblox.com/docs/reference/engine/classes/TremoloSoundEffect#Duty)
    from: {🚧Read: LegacySound}
    to: {🚧None}
  * Changed the capabilities of Property [TremoloSoundEffect.Frequency](https://create.roblox.com/docs/reference/engine/classes/TremoloSoundEffect#Frequency)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [SoundGroup](https://create.roblox.com/docs/reference/engine/classes/SoundGroup) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Changed the capabilities of Property [SoundGroup.Volume](https://create.roblox.com/docs/reference/engine/classes/SoundGroup#Volume)
    from: {🚧Read: LegacySound}
    to: {🚧None}
* Update Class [SoundService](https://create.roblox.com/docs/reference/engine/classes/SoundService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [SoundService.AmbientReverb](https://create.roblox.com/docs/reference/engine/classes/SoundService#AmbientReverb)
    from: {🚧Read: Audio | Write: Audio}
    to: {🚧None}
  * Changed the capabilities of Property [SoundService.DistanceFactor](https://create.roblox.com/docs/reference/engine/classes/SoundService#DistanceFactor)
    from: {🚧Read: Audio | Write: Audio}
    to: {🚧None}
  * Changed the capabilities of Property [SoundService.DopplerScale](https://create.roblox.com/docs/reference/engine/classes/SoundService#DopplerScale)
    from: {🚧Read: Audio | Write: Audio}
    to: {🚧None}
  * Changed the capabilities of Property [SoundService.RespectFilteringEnabled](https://create.roblox.com/docs/reference/engine/classes/SoundService#RespectFilteringEnabled)
    from: {🚧Read: Audio | Write: Audio}
    to: {🚧None}
  * Changed the capabilities of Property [SoundService.RolloffScale](https://create.roblox.com/docs/reference/engine/classes/SoundService#RolloffScale)
    from: {🚧Read: Audio | Write: Audio}
    to: {🚧None}
  * Changed the capabilities of Function [SoundService.BeginRecording](https://create.roblox.com/docs/reference/engine/classes/SoundService#BeginRecording)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the capabilities of Function [SoundService.GetListener](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetListener)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the capabilities of Function [SoundService.GetOutputDevice](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetOutputDevice)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the capabilities of Function [SoundService.GetOutputDevices](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetOutputDevices)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the capabilities of Function [SoundService.GetSoundMemoryData](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetSoundMemoryData)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the return-type of Function [SoundService.PlayLocalSound](https://create.roblox.com/docs/reference/engine/classes/SoundService#PlayLocalSound) from null to void
  * Changed the capabilities of Function [SoundService.PlayLocalSound](https://create.roblox.com/docs/reference/engine/classes/SoundService#PlayLocalSound)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the return-type of Function [SoundService.SetListener](https://create.roblox.com/docs/reference/engine/classes/SoundService#SetListener) from null to void
  * Changed the capabilities of Function [SoundService.SetListener](https://create.roblox.com/docs/reference/engine/classes/SoundService#SetListener)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the return-type of Function [SoundService.SetOutputDevice](https://create.roblox.com/docs/reference/engine/classes/SoundService#SetOutputDevice) from null to void
  * Changed the capabilities of Function [SoundService.SetOutputDevice](https://create.roblox.com/docs/reference/engine/classes/SoundService#SetOutputDevice)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the capabilities of Function [SoundService.SetRecordingDevice](https://create.roblox.com/docs/reference/engine/classes/SoundService#SetRecordingDevice)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the capabilities of Function [SoundService.EndRecording](https://create.roblox.com/docs/reference/engine/classes/SoundService#EndRecording)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the capabilities of Function [SoundService.GetRecordingDevices](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetRecordingDevices)
    from: {🚧Audio}
    to: {🚧None}
  * Changed the capabilities of Event [SoundService.DeviceListChanged](https://create.roblox.com/docs/reference/engine/classes/SoundService#DeviceListChanged)
    from: {🚧Audio}
    to: {🚧None}
  * Removed Property SoundService.AcousticSimulationEnabled
  * Removed Property SoundService.AudioApiByDefault
  * Removed Property SoundService.CharacterSoundsUseNewApi
  * Removed Property SoundService.DefaultListenerLocation
  * Removed Property SoundService.DiffractionEnabled
  * Removed Property SoundService.IsNewExpForAudioApiByDefault
  * Removed Property SoundService.ListenerCFrame
  * Removed Property SoundService.ListenerObject
  * Removed Property SoundService.ListenerType
  * Removed Property SoundService.OcclusionEnabled
  * Removed Property SoundService.ReverbEnabled
  * Removed Property SoundService.VolumetricAudio
  * Removed Function SoundService.GetAudioApiByDefault
  * Removed Function SoundService.GetAudioInstances
  * Removed Function SoundService.GetInputDevice
  * Removed Function SoundService.GetInputDevices
  * Removed Function SoundService.GetMixerTime
  * Removed Function SoundService.InsertAsset
  * Removed Function SoundService.OpenAttenuationCurveEditor
  * Removed Function SoundService.OpenDirectionalCurveEditor
  * Removed Function SoundService.SetAudioApiByDefault
  * Removed Function SoundService.SetInputDevice
  * Removed Function SoundService.SetSoundEnabled
  * Removed Event SoundService.AudioInstanceAdded
  * Removed Event SoundService.OpenAttenuationCurveEditorSignal
  * Removed Event SoundService.OpenAudioCompressorEditorSignal
  * Removed Event SoundService.OpenAudioEqualizerEditorSignal
  * Removed Event SoundService.OpenDirectionalCurveEditorSignal
* Update Class [Sparkles](https://create.roblox.com/docs/reference/engine/classes/Sparkles) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Sparkles.Color](https://create.roblox.com/docs/reference/engine/classes/Sparkles#Color)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Sparkles.Enabled](https://create.roblox.com/docs/reference/engine/classes/Sparkles#Enabled)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Sparkles.SparkleColor](https://create.roblox.com/docs/reference/engine/classes/Sparkles#SparkleColor)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Removed Property Sparkles.LocalTransparencyModifier
  * Removed Property Sparkles.TimeScale
  * Removed Function Sparkles.FastForward
* Added Class [Speaker](https://create.roblox.com/docs/reference/engine/classes/Speaker) {🔒None} [⬆️Extends: Instance] [🧠Memory: Internal] [🏷️ Deprecated]
  * Added Property [Speaker.ChannelCount](https://create.roblox.com/docs/reference/engine/classes/Speaker#ChannelCount) [🏷️ ReadOnly] [🏷️ NotReplicated] [🏷️ NotBrowsable] [⚡ThreadSafety: ReadSafe]
  * Added Property [Speaker.PlaybackLoudness](https://create.roblox.com/docs/reference/engine/classes/Speaker#PlaybackLoudness) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [Speaker.RollOffMaxDistance](https://create.roblox.com/docs/reference/engine/classes/Speaker#RollOffMaxDistance) [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [Speaker.RollOffMinDistance](https://create.roblox.com/docs/reference/engine/classes/Speaker#RollOffMinDistance) [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [Speaker.RollOffMode](https://create.roblox.com/docs/reference/engine/classes/Speaker#RollOffMode) [⚡ThreadSafety: ReadSafe]
  * Added Property [Speaker.SoundGroup](https://create.roblox.com/docs/reference/engine/classes/Speaker#SoundGroup) [⚡ThreadSafety: ReadSafe]
  * Added Property [Speaker.Source](https://create.roblox.com/docs/reference/engine/classes/Speaker#Source) [⚡ThreadSafety: ReadSafe]
  * Added Property [Speaker.Volume](https://create.roblox.com/docs/reference/engine/classes/Speaker#Volume) [⚡ThreadSafety: ReadSafe]
* Update Class [StarterPlayer](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [StarterPlayer.AllowCustomAnimations](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#AllowCustomAnimations)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.AutoJumpEnabled](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#AutoJumpEnabled)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.CameraMaxZoomDistance](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CameraMaxZoomDistance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.CameraMinZoomDistance](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CameraMinZoomDistance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.CameraMode](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CameraMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.CharacterJumpHeight](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CharacterJumpHeight)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.CharacterJumpPower](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CharacterJumpPower)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.CharacterMaxSlopeAngle](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CharacterMaxSlopeAngle)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.CharacterUseJumpPower](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CharacterUseJumpPower)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.CharacterWalkSpeed](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CharacterWalkSpeed)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.DevCameraOcclusionMode](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#DevCameraOcclusionMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.DevComputerCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#DevComputerCameraMovementMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.DevComputerMovementMode](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#DevComputerMovementMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.DevTouchCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#DevTouchCameraMovementMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.DevTouchMovementMode](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#DevTouchMovementMode)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.EnableMouseLockOption](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#EnableMouseLockOption)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDFace](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDFace)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDHead](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDHead)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDLeftArm](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDLeftArm)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDLeftLeg](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDLeftLeg)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDPants](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDPants)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDRightArm](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDRightArm)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDRightLeg](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDRightLeg)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDShirt](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDShirt)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDTeeShirt](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDTeeShirt)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAssetIDTorso](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAssetIDTorso)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsAvatar](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsAvatar)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsR15Collision](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsR15Collision)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsScaleRangeBodyType](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsScaleRangeBodyType)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsScaleRangeHead](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsScaleRangeHead)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsScaleRangeHeight](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsScaleRangeHeight)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsScaleRangeProportion](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsScaleRangeProportion)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.GameSettingsScaleRangeWidth](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#GameSettingsScaleRangeWidth)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.HealthDisplayDistance](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#HealthDisplayDistance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.LoadCharacterAppearance](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#LoadCharacterAppearance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Added Property [StarterPlayer.LoadCharacterLayeredClothing](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#LoadCharacterLayeredClothing): LoadCharacterLayeredClothing [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [StarterPlayer.NameDisplayDistance](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#NameDisplayDistance)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [StarterPlayer.UserEmotesEnabled](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#UserEmotesEnabled)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the return-type of Function [StarterPlayer.ClearDefaults](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#ClearDefaults) from null to void
  * Changed the capabilities of Function [StarterPlayer.ClearDefaults](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#ClearDefaults)
    from: {🚧Players}
    to: {🚧None}
  * Removed Property StarterPlayer.AvatarJointUpgrade
  * Removed Property StarterPlayer.CharacterBreakJointsOnDeath
  * Removed Property StarterPlayer.ClassicDeath
  * Removed Property StarterPlayer.CreateDefaultPlayerModule
  * Removed Property StarterPlayer.EnableDynamicHeads
  * Removed Property StarterPlayer.LoadCharacterLayeredClothing 
  * Removed Property StarterPlayer.LuaCharacterController
  * Removed Property StarterPlayer.PlayerModuleStatus
* Update Class [Stats](https://create.roblox.com/docs/reference/engine/classes/Stats) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Property Stats.FrameTime
  * Removed Property Stats.HeartbeatTime
  * Removed Property Stats.MemoryTrackingEnabled
  * Removed Property Stats.PhysicsStepTime
  * Removed Property Stats.RenderCPUFrameTime
  * Removed Property Stats.RenderGPUFrameTime
  * Removed Property Stats.SceneDrawcallCount
  * Removed Property Stats.SceneTriangleCount
  * Removed Property Stats.ShadowsDrawcallCount
  * Removed Property Stats.ShadowsTriangleCount
  * Removed Property Stats.UI2DDrawcallCount
  * Removed Property Stats.UI2DTriangleCount
  * Removed Property Stats.UI3DDrawcallCount
  * Removed Property Stats.UI3DTriangleCount
  * Removed Function Stats.GetHarmonyQualityLevel
  * Removed Function Stats.GetMemoryCategoryNames
  * Removed Function Stats.GetMemoryUsageMbAllCategories
  * Removed Function Stats.ResetHarmonyMemoryTarget
  * Removed Function Stats.SetHarmonyMemoryTarget
* Update Class [StopWatchReporter](https://create.roblox.com/docs/reference/engine/classes/StopWatchReporter) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [StopWatchReporter.FinishTask](https://create.roblox.com/docs/reference/engine/classes/StopWatchReporter#FinishTask) from null to void
  * Changed the return-type of Function [StopWatchReporter.SendReport](https://create.roblox.com/docs/reference/engine/classes/StopWatchReporter#SendReport) from null to void
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the security of Property [Studio."TODO" Color](https://create.roblox.com/docs/reference/engine/classes/Studio#%22TODO%22%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio."function" Color](https://create.roblox.com/docs/reference/engine/classes/Studio#%22function%22%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio."local" Color](https://create.roblox.com/docs/reference/engine/classes/Studio#%22local%22%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio."nil" Color](https://create.roblox.com/docs/reference/engine/classes/Studio#%22nil%22%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio."self" Color](https://create.roblox.com/docs/reference/engine/classes/Studio#%22self%22%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Active Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Active%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Active Hover Over Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Active%20Hover%20Over%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Always Save Script Changes](https://create.roblox.com/docs/reference/engine/classes/Studio#Always%20Save%20Script%20Changes)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Animate Hover Over](https://create.roblox.com/docs/reference/engine/classes/Studio#Animate%20Hover%20Over)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Auto Clean Empty Line](https://create.roblox.com/docs/reference/engine/classes/Studio#Auto%20Clean%20Empty%20Line)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Auto Closing Brackets](https://create.roblox.com/docs/reference/engine/classes/Studio#Auto%20Closing%20Brackets)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Auto Closing Quotes](https://create.roblox.com/docs/reference/engine/classes/Studio#Auto%20Closing%20Quotes)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Auto Indent Rule](https://create.roblox.com/docs/reference/engine/classes/Studio#Auto%20Indent%20Rule)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Auto-Recovery Enabled](https://create.roblox.com/docs/reference/engine/classes/Studio#Auto-Recovery%20Enabled)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Auto-Recovery Interval (Minutes)](https://create.roblox.com/docs/reference/engine/classes/Studio#Auto-Recovery%20Interval%20(Minutes))
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.Auto-Recovery Path](https://create.roblox.com/docs/reference/engine/classes/Studio#Auto-Recovery%20Path): QDir [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.Background Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Background%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Basic Objects Display Mode](https://create.roblox.com/docs/reference/engine/classes/Studio#Basic%20Objects%20Display%20Mode)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Bool Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Bool%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Bracket Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Bracket%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Built-in Function Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Built-in%20Function%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Camera Mouse Wheel Speed](https://create.roblox.com/docs/reference/engine/classes/Studio#Camera%20Mouse%20Wheel%20Speed)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Camera Shift Speed](https://create.roblox.com/docs/reference/engine/classes/Studio#Camera%20Shift%20Speed)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Camera Speed](https://create.roblox.com/docs/reference/engine/classes/Studio#Camera%20Speed)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Camera Zoom to Mouse Position](https://create.roblox.com/docs/reference/engine/classes/Studio#Camera%20Zoom%20to%20Mouse%20Position)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Clear Output On Start](https://create.roblox.com/docs/reference/engine/classes/Studio#Clear%20Output%20On%20Start)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.CommandBarLocalState](https://create.roblox.com/docs/reference/engine/classes/Studio#CommandBarLocalState)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Comment Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Comment%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Current Line Highlight Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Current%20Line%20Highlight%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Debugger Current Line Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Debugger%20Current%20Line%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Debugger Error Line Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Debugger%20Error%20Line%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.DefaultScriptFileDir](https://create.roblox.com/docs/reference/engine/classes/Studio#DefaultScriptFileDir): QDir [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.DeprecatedObjectsShown](https://create.roblox.com/docs/reference/engine/classes/Studio#DeprecatedObjectsShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.Drag Multiple Parts As Single Part](https://create.roblox.com/docs/reference/engine/classes/Studio#Drag%20Multiple%20Parts%20As%20Single%20Part): bool [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.Enable Autocomplete](https://create.roblox.com/docs/reference/engine/classes/Studio#Enable%20Autocomplete)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Enable CoreScript Debugger](https://create.roblox.com/docs/reference/engine/classes/Studio#Enable%20CoreScript%20Debugger)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Enable Http Sandboxing](https://create.roblox.com/docs/reference/engine/classes/Studio#Enable%20Http%20Sandboxing)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Enable Internal Beta Features](https://create.roblox.com/docs/reference/engine/classes/Studio#Enable%20Internal%20Beta%20Features)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Enable Internal Features](https://create.roblox.com/docs/reference/engine/classes/Studio#Enable%20Internal%20Features)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Enable Temporary Tabs](https://create.roblox.com/docs/reference/engine/classes/Studio#Enable%20Temporary%20Tabs)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Enable Temporary Tabs In Explorer](https://create.roblox.com/docs/reference/engine/classes/Studio#Enable%20Temporary%20Tabs%20In%20Explorer)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Error Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Error%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Find Selection Background Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Find%20Selection%20Background%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Font](https://create.roblox.com/docs/reference/engine/classes/Studio#Font)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Format On Paste](https://create.roblox.com/docs/reference/engine/classes/Studio#Format%20On%20Paste)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Format On Type](https://create.roblox.com/docs/reference/engine/classes/Studio#Format%20On%20Type)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Function Name Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Function%20Name%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Highlight Current Line](https://create.roblox.com/docs/reference/engine/classes/Studio#Highlight%20Current%20Line)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Highlight Occurances](https://create.roblox.com/docs/reference/engine/classes/Studio#Highlight%20Occurances)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Hover Animate Speed](https://create.roblox.com/docs/reference/engine/classes/Studio#Hover%20Animate%20Speed)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Hover Over Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Hover%20Over%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Indent Using Spaces](https://create.roblox.com/docs/reference/engine/classes/Studio#Indent%20Using%20Spaces)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Keyword Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Keyword%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Line Thickness](https://create.roblox.com/docs/reference/engine/classes/Studio#Line%20Thickness)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.LuaDebuggerEnabled](https://create.roblox.com/docs/reference/engine/classes/Studio#LuaDebuggerEnabled)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.LuaDebuggerEnabledAtStartup](https://create.roblox.com/docs/reference/engine/classes/Studio#LuaDebuggerEnabledAtStartup)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Luau Keyword Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Luau%20Keyword%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Matching Word Background Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Matching%20Word%20Background%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Maximum Output Lines](https://create.roblox.com/docs/reference/engine/classes/Studio#Maximum%20Output%20Lines)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Menu Item Background Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Menu%20Item%20Background%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Method Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Method%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Number Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Number%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Only Play Audio from Window in Focus](https://create.roblox.com/docs/reference/engine/classes/Studio#Only%20Play%20Audio%20from%20Window%20in%20Focus)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Operator Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Operator%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Output Font](https://create.roblox.com/docs/reference/engine/classes/Studio#Output%20Font)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Output Layout Mode](https://create.roblox.com/docs/reference/engine/classes/Studio#Output%20Layout%20Mode)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.OverrideCoreScripts](https://create.roblox.com/docs/reference/engine/classes/Studio#OverrideCoreScripts): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [Studio.OverrideCoreScriptsDir](https://create.roblox.com/docs/reference/engine/classes/Studio#OverrideCoreScriptsDir): QDir [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.PermissionLevelShown](https://create.roblox.com/docs/reference/engine/classes/Studio#PermissionLevelShown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.PluginDebuggingEnabled](https://create.roblox.com/docs/reference/engine/classes/Studio#PluginDebuggingEnabled)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.PluginsDir](https://create.roblox.com/docs/reference/engine/classes/Studio#PluginsDir)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Primary Text Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Primary%20Text%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Property Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Property%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.Render Throttle Percentage](https://create.roblox.com/docs/reference/engine/classes/Studio#Render%20Throttle%20Percentage): int [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.Respect Studio shortcuts when game has focus](https://create.roblox.com/docs/reference/engine/classes/Studio#Respect%20Studio%20shortcuts%20when%20game%20has%20focus)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Ruler Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Ruler%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Rulers](https://create.roblox.com/docs/reference/engine/classes/Studio#Rulers)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.RuntimeUndoBehavior](https://create.roblox.com/docs/reference/engine/classes/Studio#RuntimeUndoBehavior)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Script Editor Color Preset](https://create.roblox.com/docs/reference/engine/classes/Studio#Script%20Editor%20Color%20Preset)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Script Editor Scrollbar Background Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Script%20Editor%20Scrollbar%20Background%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Script Editor Scrollbar Handle Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Script%20Editor%20Scrollbar%20Handle%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.ScriptTimeoutLength](https://create.roblox.com/docs/reference/engine/classes/Studio#ScriptTimeoutLength)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Scroll Past Last Line](https://create.roblox.com/docs/reference/engine/classes/Studio#Scroll%20Past%20Last%20Line)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.Search Content For Core Scripts](https://create.roblox.com/docs/reference/engine/classes/Studio#Search%20Content%20For%20Core%20Scripts): bool [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.Secondary Text Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Secondary%20Text%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Select Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Select%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Select/Hover Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Select%2FHover%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Selected Menu Item Background Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Selected%20Menu%20Item%20Background%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Selected Text Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Selected%20Text%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Selection Background Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Selection%20Background%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Selection Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Selection%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.Selection Highlight Thickness](https://create.roblox.com/docs/reference/engine/classes/Studio#Selection%20Highlight%20Thickness): float [⚡ThreadSafety: ReadSafe]
  * Added Property [Studio.Server Audio Behavior](https://create.roblox.com/docs/reference/engine/classes/Studio#Server%20Audio%20Behavior): ServerAudioBehavior [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.Set Pivot of Imported Parts](https://create.roblox.com/docs/reference/engine/classes/Studio#Set%20Pivot%20of%20Imported%20Parts)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Show Core GUI in Explorer while Playing](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Core%20GUI%20in%20Explorer%20while%20Playing)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.Show Deployment Warnings](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Deployment%20Warnings): bool [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.Show Diagnostics Bar](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Diagnostics%20Bar)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Show FileSyncService](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20FileSyncService)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Show Hidden Objects in Explorer](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Hidden%20Objects%20in%20Explorer)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Show Hover Over](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Hover%20Over)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.Show Navigation Areas](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Navigation%20Areas): bool [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.Show Navigation Mesh](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Navigation%20Mesh)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Show Plugin GUI Service in Explorer](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Plugin%20GUI%20Service%20in%20Explorer)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Added Property [Studio.Show QT warnings in output](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20QT%20warnings%20in%20output): bool [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Studio.Show Whitespace](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20Whitespace)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Show plus button on hover in Explorer](https://create.roblox.com/docs/reference/engine/classes/Studio#Show%20plus%20button%20on%20hover%20in%20Explorer)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Skip Closing Brackets and Quotes](https://create.roblox.com/docs/reference/engine/classes/Studio#Skip%20Closing%20Brackets%20and%20Quotes)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.String Color](https://create.roblox.com/docs/reference/engine/classes/Studio#String%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Tab Width](https://create.roblox.com/docs/reference/engine/classes/Studio#Tab%20Width)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Text Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Text%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Text Wrapping](https://create.roblox.com/docs/reference/engine/classes/Studio#Text%20Wrapping)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Theme](https://create.roblox.com/docs/reference/engine/classes/Studio#Theme)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.UI Theme](https://create.roblox.com/docs/reference/engine/classes/Studio#UI%20Theme)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Warning Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Warning%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [Studio.Whitespace Color](https://create.roblox.com/docs/reference/engine/classes/Studio#Whitespace%20Color)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Removed Property Studio.ActionOnAutoResumeSync
  * Removed Property Studio.ActionOnStopSync
  * Removed Property Studio.Animation Skeleton Scale
  * Removed Property Studio.Animation Skeleton Transparency
  * Removed Property Studio.AutoResumeSyncOnPlaceOpen
  * Removed Property Studio.AutoUpdateEnabled
  * Removed Property Studio.Auto Delete Closing Brackets and Quotes
  * Removed Property Studio.AutocompleteAcceptanceBehavior
  * Removed Property Studio.Automatically trigger AI Code Completion
  * Removed Property Studio.CameraAdaptiveSpeed
  * Removed Property Studio.CameraAltLeftMouseToRotate
  * Removed Property Studio.CameraMouseMultiplier
  * Removed Property Studio.CameraNavigationModel
  * Removed Property Studio.CameraOrbitSensitivity
  * Removed Property Studio.CameraPanSensitivity
  * Removed Property Studio.CameraShiftFactor
  * Removed Property Studio.CameraTweenFocus
  * Removed Property Studio.CameraZoomSpeed
  * Removed Property Studio.CameraZoomToMousePosition
  * Removed Property Studio.Camera Pan Speed
  * Removed Property Studio.Camera Speed Adjust Binding
  * Removed Property Studio.CommandBarEnterExec
  * Removed Property Studio.CommandBarFont
  * Removed Property Studio.CommandBarHistoryLen
  * Removed Property Studio.DefaultInstancesDir
  * Removed Property Studio.DefaultScriptSyncFileType
  * Removed Property Studio.Doc View Code Background Color
  * Removed Property Studio.DraggerActiveColor
  * Removed Property Studio.DraggerLengthFactor
  * Removed Property Studio.DraggerMajorGridIncrement
  * Removed Property Studio.DraggerMaxSoftSnaps
  * Removed Property Studio.DraggerPassiveColor
  * Removed Property Studio.DraggerScaleFactor
  * Removed Property Studio.DraggerShowAxisTicks
  * Removed Property Studio.DraggerShowDraggedPoint
  * Removed Property Studio.DraggerShowHoverRuler
  * Removed Property Studio.DraggerShowMeasurement
  * Removed Property Studio.DraggerShowNegativeAxes
  * Removed Property Studio.DraggerShowPlanes
  * Removed Property Studio.DraggerShowTargetSnap
  * Removed Property Studio.DraggerShowTrackball
  * Removed Property Studio.DraggerShowWhileDragging
  * Removed Property Studio.DraggerSoftSnapMarginFactor
  * Removed Property Studio.DraggerSummonMarginFactor
  * Removed Property Studio.DraggerTiltRotateDuration
  * Removed Property Studio.EnableCodeAssist
  * Removed Property Studio.EnableFindOnType
  * Removed Property Studio.EnableIndentationRulers
  * Removed Property Studio.EnableOvertypeMode
  * Removed Property Studio.EnableSelectionTooltips
  * Removed Property Studio.EnableStudioStreaming
  * Removed Property Studio.Enable Autocomplete Doc View
  * Removed Property Studio.Enable Client/Server MDI
  * Removed Property Studio.Enable Scrollbar Markers
  * Removed Property Studio.Enable Signature Help Doc View
  * Removed Property Studio.ExternalEditorMode
  * Removed Property Studio.ExternalEditorSelection
  * Removed Property Studio.HintColor
  * Removed Property Studio.Hover Line Thickness
  * Removed Property Studio.IconOverrideDir
  * Removed Property Studio.IndentationRulerColor
  * Removed Property Studio.InformationColor
  * Removed Property Studio.LargeFileLineCountThreshold
  * Removed Property Studio.LargeFileThreshold
  * Removed Property Studio.LoadAllBuiltinPluginsInRunModes
  * Removed Property Studio.LoadInternalPlugins
  * Removed Property Studio.LoadUserPluginsInRunModes
  * Removed Property Studio.Main Volume
  * Removed Property Studio.MaxFindReplaceAllResults
  * Removed Property Studio.PreferredTextSize
  * Removed Property Studio.ReloadBuiltinPluginsOnChange
  * Removed Property Studio.ReloadLocalPluginsOnChange
  * Removed Property Studio.Selection Box Thickness
  * Removed Property Studio.Selection Line Thickness
  * Removed Property Studio.Show Animation Skeleton
  * Removed Property Studio.Show Animation Skeleton Attachments
  * Removed Property Studio.Show Animation Skeleton Axes
  * Removed Property Studio.Show Animation Skeleton Rotations
  * Removed Property Studio.Show Animation Skeleton Text
  * Removed Property Studio.Show Navigation Labels
  * Removed Property Studio.Show Pathfinding Links
  * Removed Property Studio.Show Singly Selected Attachment Parent Frame
  * Removed Property Studio.TypeColor
  * Removed Property Studio.UseDefaultExternalEditor
  * Removed Property Studio.Use Bounding Box Move Handles
  * Removed Property Studio.VAxisColor
  * Removed Property Studio.XAxisColor
  * Removed Property Studio.YAxisColor
  * Removed Property Studio.ZAxisColor
* Update Class [StudioData](https://create.roblox.com/docs/reference/engine/classes/StudioData) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [StudioData.SrcPlaceId](https://create.roblox.com/docs/reference/engine/classes/StudioData#SrcPlaceId): int64 [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [StudioData.SrcUniverseId](https://create.roblox.com/docs/reference/engine/classes/StudioData#SrcUniverseId): int64 [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [StudioDeviceEmulatorService](https://create.roblox.com/docs/reference/engine/classes/StudioDeviceEmulatorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [StudioDeviceEmulatorService.SetCurrentDeviceId](https://create.roblox.com/docs/reference/engine/classes/StudioDeviceEmulatorService#SetCurrentDeviceId) from null to void [🏷️ Yields]
  * Changed the return-type of Function [StudioDeviceEmulatorService.SetCurrentOrientation](https://create.roblox.com/docs/reference/engine/classes/StudioDeviceEmulatorService#SetCurrentOrientation) from null to void [🏷️ Yields]
* Update Class [StudioService](https://create.roblox.com/docs/reference/engine/classes/StudioService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [StudioService.ShowActiveInstanceHighlight](https://create.roblox.com/docs/reference/engine/classes/StudioService#ShowActiveInstanceHighlight): bool [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Changed the return-type of Function [StudioService.AnimationIdSelected](https://create.roblox.com/docs/reference/engine/classes/StudioService#AnimationIdSelected) from null to void
  * Added Function [StudioService.ConvertToPackageUpload](https://create.roblox.com/docs/reference/engine/classes/StudioService#ConvertToPackageUpload) (uploadUrl: string) -> void
  * Changed the return-type of Function [StudioService.CopyToClipboard](https://create.roblox.com/docs/reference/engine/classes/StudioService#CopyToClipboard) from null to void
  * Added Function [StudioService.EmitPlacePublishedSignal](https://create.roblox.com/docs/reference/engine/classes/StudioService#EmitPlacePublishedSignal) () -> void
  * Changed the return-type of Function [StudioService.GizmoRaycast](https://create.roblox.com/docs/reference/engine/classes/StudioService#GizmoRaycast) from RaycastResult? to RaycastResult
  * Changed the parameters of Function [StudioService.GizmoRaycast](https://create.roblox.com/docs/reference/engine/classes/StudioService#GizmoRaycast)
    from: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed the return-type of Function [StudioService.OpenInBrowser_DONOTUSE](https://create.roblox.com/docs/reference/engine/classes/StudioService#OpenInBrowser_DONOTUSE) from null to void
  * Added Function [StudioService.PromptForLocalSave](https://create.roblox.com/docs/reference/engine/classes/StudioService#PromptForLocalSave) () -> void
  * Added Function [StudioService.PublishAs](https://create.roblox.com/docs/reference/engine/classes/StudioService#PublishAs) (universeId: int64, placeId: int64, groupId: int64) -> void
  * Added Function [StudioService.RequestClose](https://create.roblox.com/docs/reference/engine/classes/StudioService#RequestClose) (closeMode: StudioCloseMode) -> void
  * Added Function [StudioService.SerializeInstances](https://create.roblox.com/docs/reference/engine/classes/StudioService#SerializeInstances) (instances: Objects) -> string
  * Added Function [StudioService.SetDocumentDisplayName](https://create.roblox.com/docs/reference/engine/classes/StudioService#SetDocumentDisplayName) (newName: string) -> void
  * Changed the return-type of Function [StudioService.SetPluginEnabled](https://create.roblox.com/docs/reference/engine/classes/StudioService#SetPluginEnabled) from null to void
  * Added Function [StudioService.SetUniverseDisplayName](https://create.roblox.com/docs/reference/engine/classes/StudioService#SetUniverseDisplayName) (newName: string) -> void
  * Added Function [StudioService.ShowPlaceVersionHistoryDialog](https://create.roblox.com/docs/reference/engine/classes/StudioService#ShowPlaceVersionHistoryDialog) (placeId: int64) -> void
  * Changed the return-type of Function [StudioService.ShowPublishToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#ShowPublishToRoblox) from null to void
  * Added Function [StudioService.ShowSaveOrPublishPlaceToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#ShowSaveOrPublishPlaceToRoblox) (showGameSelect: bool, isPublish: bool, closeMode: StudioCloseMode) -> void
  * Changed the return-type of Function [StudioService.UninstallPlugin](https://create.roblox.com/docs/reference/engine/classes/StudioService#UninstallPlugin) from null to void
  * Changed the return-type of Function [StudioService.UpdatePluginManagement](https://create.roblox.com/docs/reference/engine/classes/StudioService#UpdatePluginManagement) from null to void
  * Changed the return-type of Function [StudioService.PromptImportFiles](https://create.roblox.com/docs/reference/engine/classes/StudioService#PromptImportFiles) from Instances to Objects [🏷️ Yields]
  * Changed the return-type of Function [StudioService.TryInstallPlugin](https://create.roblox.com/docs/reference/engine/classes/StudioService#TryInstallPlugin) from null to void [🏷️ Yields]
  * Added Event [StudioService.FirstPublishOfCloudPlace](https://create.roblox.com/docs/reference/engine/classes/StudioService#FirstPublishOfCloudPlace)
  * Added Event [StudioService.GameNameUpdated](https://create.roblox.com/docs/reference/engine/classes/StudioService#GameNameUpdated)
  * Added Event [StudioService.GamePublishFinished](https://create.roblox.com/docs/reference/engine/classes/StudioService#GamePublishFinished)
  * Added Event [StudioService.OnConvertToPackageResult](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnConvertToPackageResult)
  * Changed the parameters of Event [StudioService.OnImportFromRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnImportFromRoblox)
    from: (assetType: string)
    to: ()
  * Added Event [StudioService.OnOpenConvertToPackagePlugin](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnOpenConvertToPackagePlugin)
  * Changed the parameters of Event [StudioService.OnPublishAsPlugin](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnPublishAsPlugin)
    from: (instances: Instances)
    to: (instances: Objects)
  * Added Event [StudioService.OnPublishPlaceToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnPublishPlaceToRoblox)
  * Added Event [StudioService.OnSaveOrPublishPlaceToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnSaveOrPublishPlaceToRoblox)
  * Changed the parameters of Event [StudioService.OnSaveToRoblox](https://create.roblox.com/docs/reference/engine/classes/StudioService#OnSaveToRoblox)
    from: (instances: Instances)
    to: (instances: Objects)
  * Removed Property StudioService.Secrets
  * Removed Property StudioService.ShowWeldDetails
  * Removed Function StudioService.GetPlaceIsPersistedToCloud
  * Removed Function StudioService.PromptImportFileAsync
  * Removed Function StudioService.PromptImportFilesAsync
* Update Class [SurfaceAppearance](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Property [SurfaceAppearance.AlphaMode](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#AlphaMode)
    from: {🔒None}
    to: {🔒LocalUserSecurity}
  * Changed the capabilities of Property [SurfaceAppearance.AlphaMode](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#AlphaMode)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the security of Property [SurfaceAppearance.ColorMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#ColorMap)
    from: {🔒PluginSecurity}
    to: {🔒LocalUserSecurity}
  * Changed the capabilities of Property [SurfaceAppearance.ColorMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#ColorMap)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the security of Property [SurfaceAppearance.MetalnessMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#MetalnessMap)
    from: {🔒PluginSecurity}
    to: {🔒LocalUserSecurity}
  * Changed the capabilities of Property [SurfaceAppearance.MetalnessMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#MetalnessMap)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the security of Property [SurfaceAppearance.NormalMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#NormalMap)
    from: {🔒PluginSecurity}
    to: {🔒LocalUserSecurity}
  * Changed the capabilities of Property [SurfaceAppearance.NormalMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#NormalMap)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the security of Property [SurfaceAppearance.RoughnessMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#RoughnessMap)
    from: {🔒PluginSecurity}
    to: {🔒LocalUserSecurity}
  * Changed the capabilities of Property [SurfaceAppearance.RoughnessMap](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#RoughnessMap)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the security of Property [SurfaceAppearance.TexturePack](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#TexturePack)
    from: {🔒Read:RobloxScriptSecurity, Write:RobloxSecurity}
    to: {🔒RobloxSecurity}
  * Changed the capabilities of Property [SurfaceAppearance.TexturePack](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#TexturePack)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Removed Property SurfaceAppearance.Color
  * Removed Property SurfaceAppearance.ColorMapContent
  * Removed Property SurfaceAppearance.EmissiveMaskContent
  * Removed Property SurfaceAppearance.EmissiveStrength
  * Removed Property SurfaceAppearance.EmissiveTint
  * Removed Property SurfaceAppearance.MetalnessMapContent
  * Removed Property SurfaceAppearance.NormalMapContent
  * Removed Property SurfaceAppearance.ResampleMode
  * Removed Property SurfaceAppearance.RoughnessMapContent
  * Removed Property SurfaceAppearance.TexturePackContent
* Update Class [TaskScheduler](https://create.roblox.com/docs/reference/engine/classes/TaskScheduler) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [TaskScheduler.SchedulerDutyCycle](https://create.roblox.com/docs/reference/engine/classes/TaskScheduler#SchedulerDutyCycle)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [TaskScheduler.SchedulerRate](https://create.roblox.com/docs/reference/engine/classes/TaskScheduler#SchedulerRate)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [TaskScheduler.ThreadPoolConfig](https://create.roblox.com/docs/reference/engine/classes/TaskScheduler#ThreadPoolConfig)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [TaskScheduler.ThreadPoolSize](https://create.roblox.com/docs/reference/engine/classes/TaskScheduler#ThreadPoolSize)
    from: {🚧Read: Basic | Write: Basic}
    to: {🚧None}
* Update Class [Team](https://create.roblox.com/docs/reference/engine/classes/Team) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Team.AutoAssignable](https://create.roblox.com/docs/reference/engine/classes/Team#AutoAssignable)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Team.AutoColorCharacters](https://create.roblox.com/docs/reference/engine/classes/Team#AutoColorCharacters)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Team.ChildOrder](https://create.roblox.com/docs/reference/engine/classes/Team#ChildOrder)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Team.Score](https://create.roblox.com/docs/reference/engine/classes/Team#Score)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the capabilities of Property [Team.TeamColor](https://create.roblox.com/docs/reference/engine/classes/Team#TeamColor)
    from: {🚧Read: Players}
    to: {🚧None}
  * Changed the return-type of Function [Team.GetPlayers](https://create.roblox.com/docs/reference/engine/classes/Team#GetPlayers) from Instances to Objects
  * Changed ThreadSafety of Function [Team.GetPlayers](https://create.roblox.com/docs/reference/engine/classes/Team#GetPlayers) from `Safe` to `Unsafe`
  * Changed the capabilities of Function [Team.GetPlayers](https://create.roblox.com/docs/reference/engine/classes/Team#GetPlayers)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Event [Team.PlayerAdded](https://create.roblox.com/docs/reference/engine/classes/Team#PlayerAdded)
    from: (player: Player)
    to: (player: Instance)
  * Changed the capabilities of Event [Team.PlayerAdded](https://create.roblox.com/docs/reference/engine/classes/Team#PlayerAdded)
    from: {🚧Players}
    to: {🚧None}
  * Changed the parameters of Event [Team.PlayerRemoved](https://create.roblox.com/docs/reference/engine/classes/Team#PlayerRemoved)
    from: (player: Player)
    to: (player: Instance)
  * Changed the capabilities of Event [Team.PlayerRemoved](https://create.roblox.com/docs/reference/engine/classes/Team#PlayerRemoved)
    from: {🚧Players}
    to: {🚧None}
* Update Class [Teams](https://create.roblox.com/docs/reference/engine/classes/Teams) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [Teams.GetTeams](https://create.roblox.com/docs/reference/engine/classes/Teams#GetTeams) from Instances to Objects
  * Changed the capabilities of Function [Teams.GetTeams](https://create.roblox.com/docs/reference/engine/classes/Teams#GetTeams)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [Teams.RebalanceTeams](https://create.roblox.com/docs/reference/engine/classes/Teams#RebalanceTeams) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [Teams.RebalanceTeams](https://create.roblox.com/docs/reference/engine/classes/Teams#RebalanceTeams)
    from: {🚧Players}
    to: {🚧None}
* Update Class [TeleportAsyncResult](https://create.roblox.com/docs/reference/engine/classes/TeleportAsyncResult) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [TeleportAsyncResult.PrivateServerId](https://create.roblox.com/docs/reference/engine/classes/TeleportAsyncResult#PrivateServerId)
    from: {🚧Read: Teleport | Write: Teleport}
    to: {🚧None}
  * Changed the capabilities of Property [TeleportAsyncResult.ReservedServerAccessCode](https://create.roblox.com/docs/reference/engine/classes/TeleportAsyncResult#ReservedServerAccessCode)
    from: {🚧Read: Teleport | Write: Teleport}
    to: {🚧None}
* Update Class [TeleportOptions](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [TeleportOptions.ReservedServerAccessCode](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#ReservedServerAccessCode)
    from: {🚧Read: Teleport | Write: Teleport}
    to: {🚧None}
  * Changed the capabilities of Property [TeleportOptions.ServerInstanceId](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#ServerInstanceId)
    from: {🚧Read: Teleport | Write: Teleport}
    to: {🚧None}
  * Changed the capabilities of Property [TeleportOptions.ShouldReserveServer](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#ShouldReserveServer)
    from: {🚧Read: Teleport | Write: Teleport}
    to: {🚧None}
  * Changed the capabilities of Function [TeleportOptions.GetTeleportData](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#GetTeleportData)
    from: {🚧Teleport}
    to: {🚧None}
  * Changed the return-type of Function [TeleportOptions.SetTeleportData](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#SetTeleportData) from null to void
  * Changed the capabilities of Function [TeleportOptions.SetTeleportData](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#SetTeleportData)
    from: {🚧Teleport}
    to: {🚧None}
* Update Class [TeleportService](https://create.roblox.com/docs/reference/engine/classes/TeleportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [TeleportService.CustomizedTeleportUI](https://create.roblox.com/docs/reference/engine/classes/TeleportService#CustomizedTeleportUI)
    from: {🚧Read: Teleport}
    to: {🚧None}
  * Changed the capabilities of Function [TeleportService.GetArrivingTeleportGui](https://create.roblox.com/docs/reference/engine/classes/TeleportService#GetArrivingTeleportGui)
    from: {🚧UI, Teleport}
    to: {🚧None}
  * Changed the capabilities of Function [TeleportService.GetLocalPlayerTeleportData](https://create.roblox.com/docs/reference/engine/classes/TeleportService#GetLocalPlayerTeleportData)
    from: {🚧Teleport}
    to: {🚧None}
  * Changed the capabilities of Function [TeleportService.GetTeleportSetting](https://create.roblox.com/docs/reference/engine/classes/TeleportService#GetTeleportSetting)
    from: {🚧Teleport}
    to: {🚧None}
  * Changed the return-type of Function [TeleportService.SetTeleportGui](https://create.roblox.com/docs/reference/engine/classes/TeleportService#SetTeleportGui) from null to void
  * Changed the capabilities of Function [TeleportService.SetTeleportGui](https://create.roblox.com/docs/reference/engine/classes/TeleportService#SetTeleportGui)
    from: {🚧UI, Teleport}
    to: {🚧None}
  * Changed the return-type of Function [TeleportService.SetTeleportSetting](https://create.roblox.com/docs/reference/engine/classes/TeleportService#SetTeleportSetting) from null to void
  * Changed the capabilities of Function [TeleportService.SetTeleportSetting](https://create.roblox.com/docs/reference/engine/classes/TeleportService#SetTeleportSetting)
    from: {🚧Teleport}
    to: {🚧None}
  * Changed the return-type of Function [TeleportService.Teleport](https://create.roblox.com/docs/reference/engine/classes/TeleportService#Teleport) from null to void
  * Changed the capabilities of Function [TeleportService.Teleport](https://create.roblox.com/docs/reference/engine/classes/TeleportService#Teleport)
    from: {🚧UI, Teleport}
    to: {🚧None}
  * Changed the return-type of Function [TeleportService.TeleportCancel](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportCancel) from null to void
  * Changed the capabilities of Function [TeleportService.TeleportCancel](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportCancel)
    from: {🚧Teleport}
    to: {🚧None}
  * Changed the return-type of Function [TeleportService.TeleportToPlaceInstance](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToPlaceInstance) from null to void
  * Changed the capabilities of Function [TeleportService.TeleportToPlaceInstance](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToPlaceInstance)
    from: {🚧UI, Teleport}
    to: {🚧None}
  * Changed the return-type of Function [TeleportService.TeleportToPrivateServer](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToPrivateServer) from null to void
  * Changed the parameters of Function [TeleportService.TeleportToPrivateServer](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToPrivateServer)
    from: (placeId: int64, reservedServerAccessCode: string, players: Instances, spawnName: string = , teleportData: Variant, customLoadingScreen: Instance = nil)
    to: (placeId: int64, reservedServerAccessCode: string, players: Objects, spawnName: string = , teleportData: Variant, customLoadingScreen: Instance = nil)
  * Changed the capabilities of Function [TeleportService.TeleportToPrivateServer](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToPrivateServer)
    from: {🚧UI, Teleport}
    to: {🚧None}
  * Changed the return-type of Function [TeleportService.TeleportToSpawnByName](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToSpawnByName) from null to void
  * Changed the capabilities of Function [TeleportService.TeleportToSpawnByName](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportToSpawnByName)
    from: {🚧UI, Teleport}
    to: {🚧None}
  * Changed the parameters of Function [TeleportService.GetPlayerPlaceInstanceAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#GetPlayerPlaceInstanceAsync)
    from: (userId: User)
    to: (userId: int64)
  * Changed the capabilities of Function [TeleportService.GetPlayerPlaceInstanceAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#GetPlayerPlaceInstanceAsync)
    from: {🚧Teleport}
    to: {🚧None}
  * Changed the capabilities of Function [TeleportService.ReserveServer](https://create.roblox.com/docs/reference/engine/classes/TeleportService#ReserveServer)
    from: {🚧Teleport}
    to: {🚧None}
  * Changed the parameters of Function [TeleportService.TeleportAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportAsync)
    from: (placeId: int64, players: Instances, teleportOptions: Instance = nil)
    to: (placeId: int64, players: Objects, teleportOptions: Instance = nil)
  * Changed the capabilities of Function [TeleportService.TeleportAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportAsync)
    from: {🚧UI, Teleport}
    to: {🚧None}
  * Changed the parameters of Function [TeleportService.TeleportPartyAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportPartyAsync)
    from: (placeId: int64, players: Instances, teleportData: Variant, customLoadingScreen: Instance = nil)
    to: (placeId: int64, players: Objects, teleportData: Variant, customLoadingScreen: Instance = nil)
  * Changed the capabilities of Function [TeleportService.TeleportPartyAsync](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportPartyAsync)
    from: {🚧UI, Teleport}
    to: {🚧None}
  * Changed the capabilities of Event [TeleportService.LocalPlayerArrivedFromTeleport](https://create.roblox.com/docs/reference/engine/classes/TeleportService#LocalPlayerArrivedFromTeleport)
    from: {🚧Teleport}
    to: {🚧None}
  * Changed the parameters of Event [TeleportService.TeleportInitFailed](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportInitFailed)
    from: (player: Instance, teleportResult: TeleportResult, errorMessage: string, placeId: int64, teleportOptions: Instance)
    to: (player: Instance, teleportResult: TeleportResult, errorMessage: string)
  * Changed the capabilities of Event [TeleportService.TeleportInitFailed](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportInitFailed)
    from: {🚧Teleport}
    to: {🚧None}
  * Removed Function TeleportService.Block
  * Removed Function TeleportService.GetThirdPartyTeleportInfo
  * Removed Function TeleportService.PromptExperienceDetailsCompleted
  * Removed Function TeleportService.TeleportReconnect
  * Removed Function TeleportService.TeleportTrustedBackForth
  * Removed Function TeleportService.TeleportTrustedBackHistory
  * Removed Function TeleportService.TeleportedPlacesBackHistory
  * Removed Function TeleportService.TeleportedUniversesBackHistory
  * Removed Function TeleportService.PromptExperienceDetailsAsync
  * Removed Function TeleportService.ReserveServerAsync
  * Removed Function TeleportService.UnblockAsync
  * Removed Event TeleportService.MenuTeleportAttempt
  * Removed Event TeleportService.OpenExperienceDetailsPrompt
  * Removed Event TeleportService.ReconnectTeleportInitFailed
* Update Class [TerrainRegion](https://create.roblox.com/docs/reference/engine/classes/TerrainRegion) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [TerrainRegion.IsSmooth](https://create.roblox.com/docs/reference/engine/classes/TerrainRegion#IsSmooth)
    from: {🚧Read: Environment}
    to: {🚧None}
  * Changed the capabilities of Property [TerrainRegion.SizeInCells](https://create.roblox.com/docs/reference/engine/classes/TerrainRegion#SizeInCells)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧None}
  * Changed the return-type of Function [TerrainRegion.ConvertToSmooth](https://create.roblox.com/docs/reference/engine/classes/TerrainRegion#ConvertToSmooth) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [TerrainRegion.ConvertToSmooth](https://create.roblox.com/docs/reference/engine/classes/TerrainRegion#ConvertToSmooth)
    from: {🚧Environment}
    to: {🚧None}
  * Removed Function TerrainRegion.ApplyTransform
  * Removed Function TerrainRegion.ApplyTransformSubregion
  * Removed Function TerrainRegion.GetRegionWireframe
* Update Class [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Changed the serialization of Property [TestService.Is30FpsThrottleEnabled](https://create.roblox.com/docs/reference/engine/classes/TestService#Is30FpsThrottleEnabled)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Changed the return-type of Function [TestService.Check](https://create.roblox.com/docs/reference/engine/classes/TestService#Check) from null to void
  * Changed the return-type of Function [TestService.Checkpoint](https://create.roblox.com/docs/reference/engine/classes/TestService#Checkpoint) from null to void
  * Changed the return-type of Function [TestService.Done](https://create.roblox.com/docs/reference/engine/classes/TestService#Done) from null to void
  * Changed the return-type of Function [TestService.Error](https://create.roblox.com/docs/reference/engine/classes/TestService#Error) from null to void
  * Changed the return-type of Function [TestService.Fail](https://create.roblox.com/docs/reference/engine/classes/TestService#Fail) from null to void
  * Changed the return-type of Function [TestService.Message](https://create.roblox.com/docs/reference/engine/classes/TestService#Message) from null to void
  * Changed the return-type of Function [TestService.Require](https://create.roblox.com/docs/reference/engine/classes/TestService#Require) from null to void
  * Changed the return-type of Function [TestService.Warn](https://create.roblox.com/docs/reference/engine/classes/TestService#Warn) from null to void
  * Changed the return-type of Function [TestService.Run](https://create.roblox.com/docs/reference/engine/classes/TestService#Run) from null to void [🏷️ Yields]
  * Removed Property TestService.ThrottlePhysicsToRealtime
  * Removed Function TestService.ConvertSlimAcrToObj
  * Removed Function TestService.CreateAndSavePropertySet
  * Removed Function TestService.CreateExtraAssetsFileFromPropertySet
  * Removed Function TestService.FetchExtraAssets
  * Removed Function TestService.GetTestControlSchema
  * Removed Function TestService.GetTestControls
  * Removed Function TestService.RegisterTest
  * Removed Function TestService.RegisterTestLegacy
  * Removed Function TestService.ResetTestControl
  * Removed Function TestService.SetTestControl
  * Removed Function TestService.StartTestSession
  * Removed Function TestService.StopTestSession
  * Removed Function TestService.TakeSnapshot
  * Removed Function TestService.TranscodePropertySet
  * Removed Function TestService.getTestSessionProviderStats
  * Removed Function TestService.CaptureScreenshotAsync
  * Removed Function TestService.FetchTestControlsAsync
  * Removed Function TestService.RequestValidationAsync
  * Removed Function TestService.RunAsync
  * Removed Function TestService.StartVideoCaptureAsync
  * Removed Function TestService.StopVideoCaptureAsync
* Update Class [TextFilterResult](https://create.roblox.com/docs/reference/engine/classes/TextFilterResult) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Function [TextFilterResult.GetChatForUserAsync](https://create.roblox.com/docs/reference/engine/classes/TextFilterResult#GetChatForUserAsync)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [TextFilterResult.GetNonChatStringForBroadcastAsync](https://create.roblox.com/docs/reference/engine/classes/TextFilterResult#GetNonChatStringForBroadcastAsync)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Function [TextFilterResult.GetNonChatStringForUserAsync](https://create.roblox.com/docs/reference/engine/classes/TextFilterResult#GetNonChatStringForUserAsync)
    from: {🚧UI}
    to: {🚧None}
* Update Class [TextService](https://create.roblox.com/docs/reference/engine/classes/TextService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Function [TextService.GetTextSize](https://create.roblox.com/docs/reference/engine/classes/TextService#GetTextSize)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [TextService.SetResolutionScale](https://create.roblox.com/docs/reference/engine/classes/TextService#SetResolutionScale) from null to void
  * Changed the capabilities of Function [TextService.SetResolutionScale](https://create.roblox.com/docs/reference/engine/classes/TextService#SetResolutionScale)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [TextService.FilterStringAsync](https://create.roblox.com/docs/reference/engine/classes/TextService#FilterStringAsync) from TextFilterResult to Instance [🏷️ Yields]
  * Changed the capabilities of Function [TextService.FilterStringAsync](https://create.roblox.com/docs/reference/engine/classes/TextService#FilterStringAsync)
    from: {🚧UI}
    to: {🚧None}
  * Removed Function TextService.GetFontMemoryData
  * Removed Function TextService.FilterAndTranslateStringAsync
  * Removed Function TextService.GetFamilyInfoAsync
  * Removed Function TextService.GetTextBoundsAsync
  * Removed Function TextService.GetTextSizeOffsetAsync
* Update Class [ThirdPartyUserService](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ThirdPartyUserService.GetUserPlatformId](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#GetUserPlatformId) () -> string
  * Added Function [ThirdPartyUserService.ReturnToEngagement](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#ReturnToEngagement) () -> void
  * Changed the return-type of Function [ThirdPartyUserService.ShowAccountPicker](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#ShowAccountPicker) from null to void
  * Added Event [ThirdPartyUserService.ActiveGamepadAdded](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#ActiveGamepadAdded)
  * Added Event [ThirdPartyUserService.ActiveGamepadRemoved](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService#ActiveGamepadRemoved)
  * Removed Property ThirdPartyUserService.FriendCommunicationRestrictionStatus
  * Removed Property ThirdPartyUserService.HasActiveUser
  * Removed Property ThirdPartyUserService.VoiceChatRestrictionStatus
  * Removed Function ThirdPartyUserService.GetVoiceChatRestrictionStatus
  * Removed Function ThirdPartyUserService.IsAccountSwitchingSupported
  * Removed Function ThirdPartyUserService.IsChatRestrictionSupported
  * Removed Function ThirdPartyUserService.IsSingleSignOnSupported
* Update Class [ThreadState](https://create.roblox.com/docs/reference/engine/classes/ThreadState) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [ThreadState.GetCallstack](https://create.roblox.com/docs/reference/engine/classes/ThreadState#GetCallstack) () -> Objects
  * Added Function [ThreadState.RequestCallstack](https://create.roblox.com/docs/reference/engine/classes/ThreadState#RequestCallstack) (status: Function) -> int
  * Removed Property ThreadState.FrameCount
  * Removed Property ThreadState.Populated
  * Removed Property ThreadState.ThreadName
  * Removed Function ThreadState.GetFrame
* Update Class [ToastNotificationService](https://create.roblox.com/docs/reference/engine/classes/ToastNotificationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [ToastNotificationService.HideNotification](https://create.roblox.com/docs/reference/engine/classes/ToastNotificationService#HideNotification) from null to void
  * Changed the return-type of Function [ToastNotificationService.ShowNotification](https://create.roblox.com/docs/reference/engine/classes/ToastNotificationService#ShowNotification) from null to void
* Update Class [TracerService](https://create.roblox.com/docs/reference/engine/classes/TracerService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [TracerService.FinishSpan](https://create.roblox.com/docs/reference/engine/classes/TracerService#FinishSpan) from null to void
* Update Class [Trail](https://create.roblox.com/docs/reference/engine/classes/Trail) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [Trail.Attachment0](https://create.roblox.com/docs/reference/engine/classes/Trail#Attachment0)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.Attachment1](https://create.roblox.com/docs/reference/engine/classes/Trail#Attachment1)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.Color](https://create.roblox.com/docs/reference/engine/classes/Trail#Color)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.Enabled](https://create.roblox.com/docs/reference/engine/classes/Trail#Enabled)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.FaceCamera](https://create.roblox.com/docs/reference/engine/classes/Trail#FaceCamera)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.Lifetime](https://create.roblox.com/docs/reference/engine/classes/Trail#Lifetime)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.LightEmission](https://create.roblox.com/docs/reference/engine/classes/Trail#LightEmission)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.LightInfluence](https://create.roblox.com/docs/reference/engine/classes/Trail#LightInfluence)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.MaxLength](https://create.roblox.com/docs/reference/engine/classes/Trail#MaxLength)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.MinLength](https://create.roblox.com/docs/reference/engine/classes/Trail#MinLength)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.Texture](https://create.roblox.com/docs/reference/engine/classes/Trail#Texture)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.TextureLength](https://create.roblox.com/docs/reference/engine/classes/Trail#TextureLength)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.TextureMode](https://create.roblox.com/docs/reference/engine/classes/Trail#TextureMode)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.Transparency](https://create.roblox.com/docs/reference/engine/classes/Trail#Transparency)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Trail.WidthScale](https://create.roblox.com/docs/reference/engine/classes/Trail#WidthScale)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the return-type of Function [Trail.Clear](https://create.roblox.com/docs/reference/engine/classes/Trail#Clear) from null to void
  * Changed the capabilities of Function [Trail.Clear](https://create.roblox.com/docs/reference/engine/classes/Trail#Clear)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Property Trail.Brightness
  * Removed Property Trail.LocalTransparencyModifier
  * Removed Property Trail.TextureContent
* Update Class [Translator](https://create.roblox.com/docs/reference/engine/classes/Translator) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the capabilities of Property [Translator.LocaleId](https://create.roblox.com/docs/reference/engine/classes/Translator#LocaleId)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Translator.FormatByKey](https://create.roblox.com/docs/reference/engine/classes/Translator#FormatByKey)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Translator.RobloxOnlyTranslate](https://create.roblox.com/docs/reference/engine/classes/Translator#RobloxOnlyTranslate)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [Translator.Translate](https://create.roblox.com/docs/reference/engine/classes/Translator#Translate)
    from: {🚧Basic}
    to: {🚧None}
* Update Class [TweenBase](https://create.roblox.com/docs/reference/engine/classes/TweenBase) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the return-type of Function [TweenBase.Cancel](https://create.roblox.com/docs/reference/engine/classes/TweenBase#Cancel) from null to void
  * Changed the return-type of Function [TweenBase.Pause](https://create.roblox.com/docs/reference/engine/classes/TweenBase#Pause) from null to void
  * Changed the return-type of Function [TweenBase.Play](https://create.roblox.com/docs/reference/engine/classes/TweenBase#Play) from null to void
* Update Class [Tween](https://create.roblox.com/docs/reference/engine/classes/Tween) [⬆️Extends: TweenBase] [🧠Memory: Instances]
  * Changed the capabilities of Property [Tween.Instance](https://create.roblox.com/docs/reference/engine/classes/Tween#Instance)
    from: {🚧Read: Basic}
    to: {🚧None}
  * Changed the capabilities of Property [Tween.TweenInfo](https://create.roblox.com/docs/reference/engine/classes/Tween#TweenInfo)
    from: {🚧Read: Basic}
    to: {🚧None}
* Update Class [TweenService](https://create.roblox.com/docs/reference/engine/classes/TweenService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [TweenService.Create](https://create.roblox.com/docs/reference/engine/classes/TweenService#Create) from Tween to Instance
  * Changed the capabilities of Function [TweenService.Create](https://create.roblox.com/docs/reference/engine/classes/TweenService#Create)
    from: {🚧Basic}
    to: {🚧None}
  * Changed the capabilities of Function [TweenService.GetValue](https://create.roblox.com/docs/reference/engine/classes/TweenService#GetValue)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Function TweenService.SmoothDamp
* Update Class [UGCValidationService](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [UGCValidationService.GetMeshTriCountSync](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetMeshTriCountSync) (meshId: string) -> int
  * Added Function [UGCValidationService.GetMeshVertsSync](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetMeshVertsSync) (meshId: string) -> Array
  * Added Function [UGCValidationService.GetTextureSizeSync](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetTextureSizeSync) (textureId: string) -> Vector2
  * Changed the return-type of Function [UGCValidationService.SetMeshIdBlocking](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#SetMeshIdBlocking) from null to void
  * Changed the return-type of Function [UGCValidationService.FetchAssetWithFormat](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#FetchAssetWithFormat) from Instances to Objects [🏷️ Yields]
  * Changed the parameters of Function [UGCValidationService.FetchAssetWithFormat](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#FetchAssetWithFormat)
    from: (url: ContentId, assetFormat: string)
    to: (url: Content, assetFormat: string)
  * Added Function [UGCValidationService.GetMeshTriCount](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetMeshTriCount) (meshId: string) -> int [🏷️ Yields]
  * Added Function [UGCValidationService.GetMeshVertColors](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetMeshVertColors) (meshId: string) -> Array [🏷️ Yields]
  * Added Function [UGCValidationService.GetTextureSize](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetTextureSize) (textureId: string) -> Vector2 [🏷️ Yields]
  * Removed Function UGCValidationService.CalculateAverageEditableCageMeshDistance
  * Removed Function UGCValidationService.CalculateEditableMeshInsideMeshPercentage
  * Removed Function UGCValidationService.CalculateEditableMeshModifiedCageBoundingBox
  * Removed Function UGCValidationService.CalculateEditableMeshNumModifiedCageUVsInSet
  * Removed Function UGCValidationService.CalculateEditableMeshTotalSurfaceArea
  * Removed Function UGCValidationService.CalculateEditableMeshUniqueUVCount
  * Removed Function UGCValidationService.CheckEditableMeshInCameraFrustum
  * Removed Function UGCValidationService.CreateEditableImageFromBinaryStringRobloxOnly
  * Removed Function UGCValidationService.CreateEditableMeshFromBinaryStringRobloxOnly
  * Removed Function UGCValidationService.GetBoundingBoxManipulationData
  * Removed Function UGCValidationService.GetDynamicHeadEditableMeshInactiveControls
  * Removed Function UGCValidationService.GetEditableCagingRelevancyMetrics
  * Removed Function UGCValidationService.GetEditableImageSize
  * Removed Function UGCValidationService.GetEditableMeshMaxNearbyVerticesCollisions
  * Removed Function UGCValidationService.GetEditableMeshSkinningTransferJointsInfo
  * Removed Function UGCValidationService.GetEditableMeshTriCount
  * Removed Function UGCValidationService.GetEditableMeshVertColors
  * Removed Function UGCValidationService.GetEditableMeshVerticesSimilarityRate
  * Removed Function UGCValidationService.GetEditableMeshVerts
  * Removed Function UGCValidationService.GetExpectedTposeRotation
  * Removed Function UGCValidationService.GetFacsDrivenJointNamesFromEditableMesh
  * Removed Function UGCValidationService.GetLayeredClothingPostDeformationSize
  * Removed Function UGCValidationService.GetMaximalJointDistancesWithinFacs
  * Removed Function UGCValidationService.GetMinAndMaxMeshSizeAcrossAllFacs
  * Removed Function UGCValidationService.GetPropertyValue
  * Removed Function UGCValidationService.GetSkinnedJointNamesFromEditableMesh
  * Removed Function UGCValidationService.IsEditableMeshNumCoplanarIntersectionsOverLimit
  * Removed Function UGCValidationService.RegisterAlternateMesh
  * Removed Function UGCValidationService.RegisterUGCValidationFunction
  * Removed Function UGCValidationService.ReportUGCValidationCounter
  * Removed Function UGCValidationService.ReportUGCValidationFailureTelemetry
  * Removed Function UGCValidationService.ReportUGCValidationTelemetry
  * Removed Function UGCValidationService.ResetCollisionFidelity
  * Removed Function UGCValidationService.ResetCollisionFidelityWithEditableMeshDataLua
  * Removed Function UGCValidationService.ValidateDynamicHeadEditableMesh
  * Removed Function UGCValidationService.ValidateEditableMeshCageMeshIntersection
  * Removed Function UGCValidationService.ValidateEditableMeshCageNonManifoldAndHoles
  * Removed Function UGCValidationService.ValidateEditableMeshCageUVCoincident
  * Removed Function UGCValidationService.ValidateEditableMeshCageUVTriangleArea
  * Removed Function UGCValidationService.ValidateEditableMeshFacialBounds
  * Removed Function UGCValidationService.ValidateEditableMeshFacialExpressiveness
  * Removed Function UGCValidationService.ValidateEditableMeshFullBodyCageDeletion
  * Removed Function UGCValidationService.ValidateEditableMeshMisMatchUV
  * Removed Function UGCValidationService.ValidateEditableMeshOverlappingVertices
  * Removed Function UGCValidationService.ValidateEditableMeshTriangleArea
  * Removed Function UGCValidationService.ValidateEditableMeshTriangles
  * Removed Function UGCValidationService.ValidateEditableMeshUVDuplicates
  * Removed Function UGCValidationService.ValidateEditableMeshUVSpace
  * Removed Function UGCValidationService.ValidateEditableMeshUVValuesInReference
  * Removed Function UGCValidationService.ValidateEditableMeshUniqueUVCount
  * Removed Function UGCValidationService.ValidateEditableMeshVertColors
  * Removed Function UGCValidationService.ValidateHSRMeshIds
  * Removed Function UGCValidationService.ValidateLeaderSkinnedVertsNearCageIslands
  * Removed Function UGCValidationService.ValidatePartBBoxAfterFullFacs
  * Removed Function UGCValidationService.ValidatePropertiesSensible
  * Removed Function UGCValidationService.ValidateSkinnedEditableMesh
  * Removed Function UGCValidationService.CalculateBodyMaxCageDistance
  * Removed Function UGCValidationService.CanLoadAsset
  * Removed Function UGCValidationService.CreateEditableImageOriginalSizeAsync
  * Removed Function UGCValidationService.DoesMeshHaveSkinningData
  * Removed Function UGCValidationService.DoesSurfaceAppearanceMatchTexturePackAsync
  * Removed Function UGCValidationService.GetMeshDataBinaryString
  * Removed Function UGCValidationService.IsDeformedLayeredClothingOutOfRenderBounds
* Update Class [UIAspectRatioConstraint](https://create.roblox.com/docs/reference/engine/classes/UIAspectRatioConstraint) [⬆️Extends: UIConstraint] [🧠Memory: Instances]
  * Changed the capabilities of Property [UIAspectRatioConstraint.AspectRatio](https://create.roblox.com/docs/reference/engine/classes/UIAspectRatioConstraint#AspectRatio)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIAspectRatioConstraint.AspectType](https://create.roblox.com/docs/reference/engine/classes/UIAspectRatioConstraint#AspectType)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIAspectRatioConstraint.DominantAxis](https://create.roblox.com/docs/reference/engine/classes/UIAspectRatioConstraint#DominantAxis)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [UISizeConstraint](https://create.roblox.com/docs/reference/engine/classes/UISizeConstraint) [⬆️Extends: UIConstraint] [🧠Memory: Instances]
  * Changed the capabilities of Property [UISizeConstraint.MaxSize](https://create.roblox.com/docs/reference/engine/classes/UISizeConstraint#MaxSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UISizeConstraint.MinSize](https://create.roblox.com/docs/reference/engine/classes/UISizeConstraint#MinSize)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [UITextSizeConstraint](https://create.roblox.com/docs/reference/engine/classes/UITextSizeConstraint) [⬆️Extends: UIConstraint] [🧠Memory: Instances]
  * Changed the capabilities of Property [UITextSizeConstraint.MaxTextSize](https://create.roblox.com/docs/reference/engine/classes/UITextSizeConstraint#MaxTextSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UITextSizeConstraint.MinTextSize](https://create.roblox.com/docs/reference/engine/classes/UITextSizeConstraint#MinTextSize)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [UICorner](https://create.roblox.com/docs/reference/engine/classes/UICorner) [⬆️Extends: UIComponent] [🧠Memory: Instances]
  * Changed the capabilities of Property [UICorner.CornerRadius](https://create.roblox.com/docs/reference/engine/classes/UICorner#CornerRadius)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the serialization of Property [UICorner.CornerRadius](https://create.roblox.com/docs/reference/engine/classes/UICorner#CornerRadius)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
  * Removed Property UICorner.BottomLeftRadius
  * Removed Property UICorner.BottomRightRadius
  * Removed Property UICorner.TopLeftRadius
  * Removed Property UICorner.TopRightRadius
* Update Class [UIGradient](https://create.roblox.com/docs/reference/engine/classes/UIGradient) [⬆️Extends: UIComponent] [🧠Memory: Instances]
  * Changed the capabilities of Property [UIGradient.Color](https://create.roblox.com/docs/reference/engine/classes/UIGradient#Color)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGradient.Enabled](https://create.roblox.com/docs/reference/engine/classes/UIGradient#Enabled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGradient.Offset](https://create.roblox.com/docs/reference/engine/classes/UIGradient#Offset)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGradient.Rotation](https://create.roblox.com/docs/reference/engine/classes/UIGradient#Rotation)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGradient.Transparency](https://create.roblox.com/docs/reference/engine/classes/UIGradient#Transparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property UIGradient.Scale
  * Removed Property UIGradient.TileMode
  * Removed Property UIGradient.Type
* Update Class [UIGridStyleLayout](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout) [⬆️Extends: UILayout] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [UIGridStyleLayout.AbsoluteContentSize](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#AbsoluteContentSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridStyleLayout.FillDirection](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#FillDirection)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridStyleLayout.HorizontalAlignment](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#HorizontalAlignment)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridStyleLayout.SortOrder](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#SortOrder)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridStyleLayout.VerticalAlignment](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#VerticalAlignment)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [UIGridStyleLayout.ApplyLayout](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#ApplyLayout) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [UIGridStyleLayout.ApplyLayout](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#ApplyLayout)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [UIGridStyleLayout.SetCustomSortFunction](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#SetCustomSortFunction) from null to void [🏷️ Deprecated]
  * Changed the capabilities of Function [UIGridStyleLayout.SetCustomSortFunction](https://create.roblox.com/docs/reference/engine/classes/UIGridStyleLayout#SetCustomSortFunction)
    from: {🚧UI}
    to: {🚧None}
* Update Class [UIGridLayout](https://create.roblox.com/docs/reference/engine/classes/UIGridLayout) [⬆️Extends: UIGridStyleLayout] [🧠Memory: Instances]
  * Changed the capabilities of Property [UIGridLayout.AbsoluteCellCount](https://create.roblox.com/docs/reference/engine/classes/UIGridLayout#AbsoluteCellCount)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridLayout.AbsoluteCellSize](https://create.roblox.com/docs/reference/engine/classes/UIGridLayout#AbsoluteCellSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridLayout.CellPadding](https://create.roblox.com/docs/reference/engine/classes/UIGridLayout#CellPadding)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridLayout.CellSize](https://create.roblox.com/docs/reference/engine/classes/UIGridLayout#CellSize)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridLayout.FillDirectionMaxCells](https://create.roblox.com/docs/reference/engine/classes/UIGridLayout#FillDirectionMaxCells)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIGridLayout.StartCorner](https://create.roblox.com/docs/reference/engine/classes/UIGridLayout#StartCorner)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [UIListLayout](https://create.roblox.com/docs/reference/engine/classes/UIListLayout) [⬆️Extends: UIGridStyleLayout] [🧠Memory: Instances]
  * Changed the capabilities of Property [UIListLayout.Padding](https://create.roblox.com/docs/reference/engine/classes/UIListLayout#Padding)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property UIListLayout.HorizontalFlex
  * Removed Property UIListLayout.ItemLineAlignment
  * Removed Property UIListLayout.VerticalFlex
  * Removed Property UIListLayout.Wraps
* Update Class [UIPageLayout](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout) [⬆️Extends: UIGridStyleLayout] [🧠Memory: Instances]
  * Changed the capabilities of Property [UIPageLayout.Animated](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Animated)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.Circular](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Circular)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.CurrentPage](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#CurrentPage)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.EasingDirection](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#EasingDirection)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.EasingStyle](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#EasingStyle)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.GamepadInputEnabled](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#GamepadInputEnabled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.Padding](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Padding)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.ScrollWheelInputEnabled](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#ScrollWheelInputEnabled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.TouchInputEnabled](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#TouchInputEnabled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPageLayout.TweenTime](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#TweenTime)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the return-type of Function [UIPageLayout.JumpTo](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#JumpTo) from null to void
  * Changed the capabilities of Function [UIPageLayout.JumpTo](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#JumpTo)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [UIPageLayout.JumpToIndex](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#JumpToIndex) from null to void
  * Changed the capabilities of Function [UIPageLayout.JumpToIndex](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#JumpToIndex)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [UIPageLayout.Next](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Next) from null to void
  * Changed the capabilities of Function [UIPageLayout.Next](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Next)
    from: {🚧UI}
    to: {🚧None}
  * Changed the return-type of Function [UIPageLayout.Previous](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Previous) from null to void
  * Changed the capabilities of Function [UIPageLayout.Previous](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Previous)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [UIPageLayout.PageEnter](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#PageEnter)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [UIPageLayout.PageLeave](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#PageLeave)
    from: {🚧UI}
    to: {🚧None}
  * Changed the capabilities of Event [UIPageLayout.Stopped](https://create.roblox.com/docs/reference/engine/classes/UIPageLayout#Stopped)
    from: {🚧UI}
    to: {🚧None}
* Update Class [UITableLayout](https://create.roblox.com/docs/reference/engine/classes/UITableLayout) [⬆️Extends: UIGridStyleLayout] [🧠Memory: Instances]
  * Changed the capabilities of Property [UITableLayout.FillEmptySpaceColumns](https://create.roblox.com/docs/reference/engine/classes/UITableLayout#FillEmptySpaceColumns)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UITableLayout.FillEmptySpaceRows](https://create.roblox.com/docs/reference/engine/classes/UITableLayout#FillEmptySpaceRows)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UITableLayout.MajorAxis](https://create.roblox.com/docs/reference/engine/classes/UITableLayout#MajorAxis)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UITableLayout.Padding](https://create.roblox.com/docs/reference/engine/classes/UITableLayout#Padding)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [UIPadding](https://create.roblox.com/docs/reference/engine/classes/UIPadding) [⬆️Extends: UIComponent] [🧠Memory: Instances]
  * Changed the capabilities of Property [UIPadding.PaddingBottom](https://create.roblox.com/docs/reference/engine/classes/UIPadding#PaddingBottom)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPadding.PaddingLeft](https://create.roblox.com/docs/reference/engine/classes/UIPadding#PaddingLeft)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPadding.PaddingRight](https://create.roblox.com/docs/reference/engine/classes/UIPadding#PaddingRight)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIPadding.PaddingTop](https://create.roblox.com/docs/reference/engine/classes/UIPadding#PaddingTop)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [UIScale](https://create.roblox.com/docs/reference/engine/classes/UIScale) [⬆️Extends: UIComponent] [🧠Memory: Instances]
  * Changed the capabilities of Property [UIScale.Scale](https://create.roblox.com/docs/reference/engine/classes/UIScale#Scale)
    from: {🚧Read: UI}
    to: {🚧None}
* Update Class [UIStroke](https://create.roblox.com/docs/reference/engine/classes/UIStroke) [⬆️Extends: UIComponent] [🧠Memory: Instances]
  * Changed the capabilities of Property [UIStroke.ApplyStrokeMode](https://create.roblox.com/docs/reference/engine/classes/UIStroke#ApplyStrokeMode)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIStroke.Color](https://create.roblox.com/docs/reference/engine/classes/UIStroke#Color)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIStroke.Enabled](https://create.roblox.com/docs/reference/engine/classes/UIStroke#Enabled)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIStroke.LineJoinMode](https://create.roblox.com/docs/reference/engine/classes/UIStroke#LineJoinMode)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIStroke.Thickness](https://create.roblox.com/docs/reference/engine/classes/UIStroke#Thickness)
    from: {🚧Read: UI}
    to: {🚧None}
  * Changed the capabilities of Property [UIStroke.Transparency](https://create.roblox.com/docs/reference/engine/classes/UIStroke#Transparency)
    from: {🚧Read: UI}
    to: {🚧None}
  * Removed Property UIStroke.BorderOffset
  * Removed Property UIStroke.BorderStrokePosition
  * Removed Property UIStroke.StrokeSizingMode
  * Removed Property UIStroke.ZIndex
* Update Class [UnvalidatedAssetService](https://create.roblox.com/docs/reference/engine/classes/UnvalidatedAssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the return-type of Function [UnvalidatedAssetService.AppendTempAssetId](https://create.roblox.com/docs/reference/engine/classes/UnvalidatedAssetService#AppendTempAssetId) from null to void
* Update Class [UserGameSettings](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ UserSettings]
  * Changed the capabilities of Property [UserGameSettings.ComputerCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#ComputerCameraMovementMode)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserGameSettings.ComputerMovementMode](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#ComputerMovementMode)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserGameSettings.ControlMode](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#ControlMode)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserGameSettings.GamepadCameraSensitivity](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#GamepadCameraSensitivity)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the security of Property [UserGameSettings.MasterVolume](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#MasterVolume)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [UserGameSettings.MouseSensitivity](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#MouseSensitivity)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserGameSettings.RotationType](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#RotationType)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserGameSettings.SavedQualityLevel](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SavedQualityLevel)
    from: {🚧Read: Players | Write: Players}
    to: {🚧None}
  * Changed the capabilities of Property [UserGameSettings.TouchCameraMovementMode](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#TouchCameraMovementMode)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserGameSettings.TouchMovementMode](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#TouchMovementMode)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserGameSettings.GetCameraYInvertValue](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#GetCameraYInvertValue)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserGameSettings.GetOnboardingCompleted](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#GetOnboardingCompleted)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [UserGameSettings.InFullScreen](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#InFullScreen)
    from: {🚧Players}
    to: {🚧None}
  * Changed the capabilities of Function [UserGameSettings.InStudioMode](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#InStudioMode)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [UserGameSettings.ResetOnboardingCompleted](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#ResetOnboardingCompleted) from null to void
  * Changed the return-type of Function [UserGameSettings.SetCameraYInvertVisible](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetCameraYInvertVisible) from null to void
  * Changed the capabilities of Function [UserGameSettings.SetCameraYInvertVisible](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetCameraYInvertVisible)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [UserGameSettings.SetGamepadCameraSensitivityVisible](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetGamepadCameraSensitivityVisible) from null to void
  * Changed the capabilities of Function [UserGameSettings.SetGamepadCameraSensitivityVisible](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetGamepadCameraSensitivityVisible)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [UserGameSettings.SetOnboardingCompleted](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetOnboardingCompleted) from null to void
  * Changed the capabilities of Function [UserGameSettings.SetOnboardingCompleted](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetOnboardingCompleted)
    from: {🚧Players}
    to: {🚧None}
  * Changed the return-type of Function [UserGameSettings.SetTutorialState](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#SetTutorialState) from null to void
  * Removed Property UserGameSettings.BadgeVisible
  * Removed Property UserGameSettings.ChatTranslationEnabled
  * Removed Property UserGameSettings.ChatTranslationFTUXShown
  * Removed Property UserGameSettings.ChatTranslationLocale
  * Removed Property UserGameSettings.ChatTranslationToggleEnabled
  * Removed Property UserGameSettings.DefaultCameraID
  * Removed Property UserGameSettings.FramerateCap
  * Removed Property UserGameSettings.GraphicsOptimizationMode
  * Removed Property UserGameSettings.HapticStrength
  * Removed Property UserGameSettings.MasterVolumeStudio
  * Removed Property UserGameSettings.MaxQualityEnabled
  * Removed Property UserGameSettings.PartyVoiceVolume
  * Removed Property UserGameSettings.PeoplePageLayout
  * Removed Property UserGameSettings.PlayerHeight
  * Removed Property UserGameSettings.PlayerListVisible
  * Removed Property UserGameSettings.PlayerNamesEnabled
  * Removed Property UserGameSettings.PreferredTextSize
  * Removed Property UserGameSettings.PreferredTransparency
  * Removed Property UserGameSettings.QualityResetLevel
  * Removed Property UserGameSettings.ReadAloud
  * Removed Property UserGameSettings.ReducedMotion
  * Removed Property UserGameSettings.StudioPreferredTextSize
  * Removed Property UserGameSettings.UiNavigationKeyBindEnabled
  * Removed Property UserGameSettings.VRComfortSetting
  * Removed Property UserGameSettings.VRSafetyBubbleMode
  * Removed Property UserGameSettings.VRSmoothRotationEnabled
  * Removed Property UserGameSettings.VRSmoothRotationEnabledCustomOption
  * Removed Property UserGameSettings.VRThirdPersonFollowCamEnabled
  * Removed Property UserGameSettings.VRThirdPersonFollowCamEnabledCustomOption
  * Removed Property UserGameSettings.VignetteEnabled
  * Removed Property UserGameSettings.VignetteEnabledCustomOption
  * Removed Property UserGameSettings.VoiceChatVolume
  * Removed Function UserGameSettings.GetDefaultFramerateCap
* Update Class [UserInputService](https://create.roblox.com/docs/reference/engine/classes/UserInputService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the capabilities of Property [UserInputService.AccelerometerEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#AccelerometerEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.BottomBarSize](https://create.roblox.com/docs/reference/engine/classes/UserInputService#BottomBarSize)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.GamepadEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GamepadEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Added Property [UserInputService.GazeSelectionEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GazeSelectionEnabled): bool [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [UserInputService.GyroscopeEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GyroscopeEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.KeyboardEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#KeyboardEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.LegacyInputEventsEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#LegacyInputEventsEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.ModalEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#ModalEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.MouseBehavior](https://create.roblox.com/docs/reference/engine/classes/UserInputService#MouseBehavior)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.MouseDeltaSensitivity](https://create.roblox.com/docs/reference/engine/classes/UserInputService#MouseDeltaSensitivity)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.MouseEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#MouseEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.MouseIconEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#MouseIconEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.NavBarSize](https://create.roblox.com/docs/reference/engine/classes/UserInputService#NavBarSize)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.OnScreenKeyboardAnimationDuration](https://create.roblox.com/docs/reference/engine/classes/UserInputService#OnScreenKeyboardAnimationDuration)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.OnScreenKeyboardPosition](https://create.roblox.com/docs/reference/engine/classes/UserInputService#OnScreenKeyboardPosition)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.OnScreenKeyboardSize](https://create.roblox.com/docs/reference/engine/classes/UserInputService#OnScreenKeyboardSize)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.OnScreenKeyboardVisible](https://create.roblox.com/docs/reference/engine/classes/UserInputService#OnScreenKeyboardVisible)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.OverrideMouseIconBehavior](https://create.roblox.com/docs/reference/engine/classes/UserInputService#OverrideMouseIconBehavior)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.RightBarSize](https://create.roblox.com/docs/reference/engine/classes/UserInputService#RightBarSize)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.StatusBarSize](https://create.roblox.com/docs/reference/engine/classes/UserInputService#StatusBarSize)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.TouchEnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchEnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.UserHeadCFrame](https://create.roblox.com/docs/reference/engine/classes/UserInputService#UserHeadCFrame)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [UserInputService.VREnabled](https://create.roblox.com/docs/reference/engine/classes/UserInputService#VREnabled)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GamepadSupports](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GamepadSupports)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetConnectedGamepads](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetConnectedGamepads)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetDeviceAcceleration](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetDeviceAcceleration)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetDeviceGravity](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetDeviceGravity)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetDeviceRotation](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetDeviceRotation)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetDeviceType](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetDeviceType)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetFocusedTextBox](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetFocusedTextBox)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetGamepadConnected](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetGamepadConnected)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [UserInputService.GetGamepadState](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetGamepadState) from Instances to Array
  * Changed the capabilities of Function [UserInputService.GetGamepadState](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetGamepadState)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [UserInputService.GetKeysPressed](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetKeysPressed) from Instances to Array
  * Changed the capabilities of Function [UserInputService.GetKeysPressed](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetKeysPressed)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetLastInputType](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetLastInputType)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [UserInputService.GetMouseButtonsPressed](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetMouseButtonsPressed) from Instances to Array
  * Changed the capabilities of Function [UserInputService.GetMouseButtonsPressed](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetMouseButtonsPressed)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetMouseDelta](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetMouseDelta)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetMouseLocation](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetMouseLocation)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetNavigationGamepads](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetNavigationGamepads)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetPlatform](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetPlatform)
    from: {🚧Input}
    to: {🚧None}
  * Changed the parameters of Function [UserInputService.GetStringForKeyCode](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetStringForKeyCode)
    from: (keyCode: KeyCode, format: KeyCodeStringFormat = Default)
    to: (keyCode: KeyCode)
  * Changed the capabilities of Function [UserInputService.GetStringForKeyCode](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetStringForKeyCode)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetSupportedGamepadKeyCodes](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetSupportedGamepadKeyCodes)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.GetUserCFrame](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GetUserCFrame)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.IsGamepadButtonDown](https://create.roblox.com/docs/reference/engine/classes/UserInputService#IsGamepadButtonDown)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.IsKeyDown](https://create.roblox.com/docs/reference/engine/classes/UserInputService#IsKeyDown)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.IsMouseButtonPressed](https://create.roblox.com/docs/reference/engine/classes/UserInputService#IsMouseButtonPressed)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [UserInputService.IsNavigationGamepad](https://create.roblox.com/docs/reference/engine/classes/UserInputService#IsNavigationGamepad)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [UserInputService.RecenterUserHeadCFrame](https://create.roblox.com/docs/reference/engine/classes/UserInputService#RecenterUserHeadCFrame) from null to void
  * Changed the capabilities of Function [UserInputService.RecenterUserHeadCFrame](https://create.roblox.com/docs/reference/engine/classes/UserInputService#RecenterUserHeadCFrame)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [UserInputService.SendAppUISizes](https://create.roblox.com/docs/reference/engine/classes/UserInputService#SendAppUISizes) from null to void
  * Changed the capabilities of Function [UserInputService.SendAppUISizes](https://create.roblox.com/docs/reference/engine/classes/UserInputService#SendAppUISizes)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [UserInputService.SetNavigationGamepad](https://create.roblox.com/docs/reference/engine/classes/UserInputService#SetNavigationGamepad) from null to void
  * Changed the capabilities of Function [UserInputService.SetNavigationGamepad](https://create.roblox.com/docs/reference/engine/classes/UserInputService#SetNavigationGamepad)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.DeviceAccelerationChanged](https://create.roblox.com/docs/reference/engine/classes/UserInputService#DeviceAccelerationChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.DeviceGravityChanged](https://create.roblox.com/docs/reference/engine/classes/UserInputService#DeviceGravityChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.DeviceRotationChanged](https://create.roblox.com/docs/reference/engine/classes/UserInputService#DeviceRotationChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.GamepadConnected](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GamepadConnected)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.GamepadDisconnected](https://create.roblox.com/docs/reference/engine/classes/UserInputService#GamepadDisconnected)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.InputBegan](https://create.roblox.com/docs/reference/engine/classes/UserInputService#InputBegan)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.InputChanged](https://create.roblox.com/docs/reference/engine/classes/UserInputService#InputChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.InputEnded](https://create.roblox.com/docs/reference/engine/classes/UserInputService#InputEnded)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.JumpRequest](https://create.roblox.com/docs/reference/engine/classes/UserInputService#JumpRequest)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.LastInputTypeChanged](https://create.roblox.com/docs/reference/engine/classes/UserInputService#LastInputTypeChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.PointerAction](https://create.roblox.com/docs/reference/engine/classes/UserInputService#PointerAction)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.StatusBarTapped](https://create.roblox.com/docs/reference/engine/classes/UserInputService#StatusBarTapped)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TextBoxFocusReleased](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TextBoxFocusReleased)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TextBoxFocused](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TextBoxFocused)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchEnded](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchEnded)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchLongPress](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchLongPress)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchMoved](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchMoved)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchPan](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchPan)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchPinch](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchPinch)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchRotate](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchRotate)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchStarted](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchStarted)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchSwipe](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchSwipe)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchTap](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchTap)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.TouchTapInWorld](https://create.roblox.com/docs/reference/engine/classes/UserInputService#TouchTapInWorld)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.UserCFrameChanged](https://create.roblox.com/docs/reference/engine/classes/UserInputService#UserCFrameChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.WindowFocusReleased](https://create.roblox.com/docs/reference/engine/classes/UserInputService#WindowFocusReleased)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [UserInputService.WindowFocused](https://create.roblox.com/docs/reference/engine/classes/UserInputService#WindowFocused)
    from: {🚧Input}
    to: {🚧None}
  * Removed Property UserInputService.MouseIcon
  * Removed Property UserInputService.MouseIconContent
  * Removed Property UserInputService.PreferredInput
  * Removed Property UserInputService.TouchScreenEnabled
  * Removed Function UserInputService.CreateVirtualInput
  * Removed Function UserInputService.GetDeviceLevel
  * Removed Function UserInputService.GetImageForKeyCode
  * Removed Function UserInputService.GetPasteText
  * Removed Event UserInputService.TouchDrag
* Update Class [UserService](https://create.roblox.com/docs/reference/engine/classes/UserService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Function [UserService.GetUserInfosByUserIdsAsync](https://create.roblox.com/docs/reference/engine/classes/UserService#GetUserInfosByUserIdsAsync)
    from: {🚧Basic}
    to: {🚧None}
  * Removed Function UserService.GetUserFromGlobalUserIdAsync
* Update Class [VRService](https://create.roblox.com/docs/reference/engine/classes/VRService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [VRService.GuiInputUserCFrame](https://create.roblox.com/docs/reference/engine/classes/VRService#GuiInputUserCFrame)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the capabilities of Property [VRService.VRDeviceName](https://create.roblox.com/docs/reference/engine/classes/VRService#VRDeviceName)
    from: {🚧Read: Input}
    to: {🚧None}
  * Changed the capabilities of Property [VRService.VREnabled](https://create.roblox.com/docs/reference/engine/classes/VRService#VREnabled)
    from: {🚧Read: Input | Write: Input}
    to: {🚧None}
  * Changed the serialization of Property [VRService.VREnabled](https://create.roblox.com/docs/reference/engine/classes/VRService#VREnabled)
    from: [🚫None]
    to: [💾SaveOnly]
  * Changed the capabilities of Function [VRService.GetTouchpadMode](https://create.roblox.com/docs/reference/engine/classes/VRService#GetTouchpadMode)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [VRService.GetUserCFrame](https://create.roblox.com/docs/reference/engine/classes/VRService#GetUserCFrame)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Function [VRService.GetUserCFrameEnabled](https://create.roblox.com/docs/reference/engine/classes/VRService#GetUserCFrameEnabled)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [VRService.RecenterUserHeadCFrame](https://create.roblox.com/docs/reference/engine/classes/VRService#RecenterUserHeadCFrame) from null to void
  * Changed the capabilities of Function [VRService.RecenterUserHeadCFrame](https://create.roblox.com/docs/reference/engine/classes/VRService#RecenterUserHeadCFrame)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [VRService.RequestNavigation](https://create.roblox.com/docs/reference/engine/classes/VRService#RequestNavigation) from null to void
  * Changed the capabilities of Function [VRService.RequestNavigation](https://create.roblox.com/docs/reference/engine/classes/VRService#RequestNavigation)
    from: {🚧Input}
    to: {🚧None}
  * Changed the return-type of Function [VRService.SetTouchpadMode](https://create.roblox.com/docs/reference/engine/classes/VRService#SetTouchpadMode) from null to void
  * Changed the capabilities of Function [VRService.SetTouchpadMode](https://create.roblox.com/docs/reference/engine/classes/VRService#SetTouchpadMode)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [VRService.NavigationRequested](https://create.roblox.com/docs/reference/engine/classes/VRService#NavigationRequested)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [VRService.TouchpadModeChanged](https://create.roblox.com/docs/reference/engine/classes/VRService#TouchpadModeChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [VRService.UserCFrameChanged](https://create.roblox.com/docs/reference/engine/classes/VRService#UserCFrameChanged)
    from: {🚧Input}
    to: {🚧None}
  * Changed the capabilities of Event [VRService.UserCFrameEnabled](https://create.roblox.com/docs/reference/engine/classes/VRService#UserCFrameEnabled)
    from: {🚧Input}
    to: {🚧None}
  * Removed Property VRService.AutomaticScaling
  * Removed Property VRService.AvatarGestures
  * Removed Property VRService.ControllerModels
  * Removed Property VRService.DidPointerHit
  * Removed Property VRService.FadeOutViewOnCollision
  * Removed Property VRService.LaserDistance
  * Removed Property VRService.LaserPointer
  * Removed Property VRService.PointerHitCFrame
  * Removed Property VRService.QuestASWState
  * Removed Property VRService.QuestDisplayRefreshRate
  * Removed Property VRService.ThirdPersonFollowCamEnabled
  * Removed Property VRService.VRDeviceAvailable
  * Removed Property VRService.VRSessionState
  * Removed Function VRService.IsMaquettes
  * Removed Function VRService.IsVRAppBuild
  * Removed Event VRService.LaserPointerTriggered
* Update Class [VersionControlService](https://create.roblox.com/docs/reference/engine/classes/VersionControlService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Property VersionControlService.ScriptCollabEnabled
* Update Class [VirtualInputManager](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Changed the return-type of Function [VirtualInputManager.Dump](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#Dump) from null to void
  * Changed the return-type of Function [VirtualInputManager.HandleGamepadAxisInput](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#HandleGamepadAxisInput) from null to void
  * Changed the return-type of Function [VirtualInputManager.HandleGamepadButtonInput](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#HandleGamepadButtonInput) from null to void
  * Changed the return-type of Function [VirtualInputManager.HandleGamepadConnect](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#HandleGamepadConnect) from null to void
  * Changed the return-type of Function [VirtualInputManager.HandleGamepadDisconnect](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#HandleGamepadDisconnect) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendAccelerometerEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendAccelerometerEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendGravityEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendGravityEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendGyroscopeEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendGyroscopeEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendKeyEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendKeyEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendMouseButtonEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendMouseButtonEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendMouseMoveEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendMouseMoveEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendMouseWheelEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendMouseWheelEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendTextInputCharacterEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendTextInputCharacterEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SendTouchEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SendTouchEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.SetInputTypesToIgnore](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#SetInputTypesToIgnore) from null to void
  * Changed the return-type of Function [VirtualInputManager.StartPlaying](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StartPlaying) from null to void
  * Changed the return-type of Function [VirtualInputManager.StartPlayingJSON](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StartPlayingJSON) from null to void
  * Changed the return-type of Function [VirtualInputManager.StartRecording](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StartRecording) from null to void
  * Changed the return-type of Function [VirtualInputManager.StopPlaying](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StopPlaying) from null to void
  * Changed the return-type of Function [VirtualInputManager.StopRecording](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#StopRecording) from null to void
  * Changed the return-type of Function [VirtualInputManager.sendRobloxEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#sendRobloxEvent) from null to void
  * Changed the return-type of Function [VirtualInputManager.sendThemeChangeEvent](https://create.roblox.com/docs/reference/engine/classes/VirtualInputManager#sendThemeChangeEvent) from null to void
  * Removed Function VirtualInputManager.SendMouseMoveDeltaEvent
  * Removed Function VirtualInputManager.SendScroll
  * Removed Function VirtualInputManager.WaitForInputEventsProcessed
* Update Class [VirtualUser](https://create.roblox.com/docs/reference/engine/classes/VirtualUser) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the return-type of Function [VirtualUser.Button1Down](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button1Down) from null to void
  * Changed the parameters of Function [VirtualUser.Button1Down](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button1Down)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity)
  * Changed the return-type of Function [VirtualUser.Button1Up](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button1Up) from null to void
  * Changed the parameters of Function [VirtualUser.Button1Up](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button1Up)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity)
  * Changed the return-type of Function [VirtualUser.Button2Down](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button2Down) from null to void
  * Changed the parameters of Function [VirtualUser.Button2Down](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button2Down)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity)
  * Changed the return-type of Function [VirtualUser.Button2Up](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button2Up) from null to void
  * Changed the parameters of Function [VirtualUser.Button2Up](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#Button2Up)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity)
  * Changed the return-type of Function [VirtualUser.CaptureController](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#CaptureController) from null to void
  * Changed the return-type of Function [VirtualUser.ClickButton1](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#ClickButton1) from null to void
  * Changed the parameters of Function [VirtualUser.ClickButton1](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#ClickButton1)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity)
  * Changed the return-type of Function [VirtualUser.ClickButton2](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#ClickButton2) from null to void
  * Changed the parameters of Function [VirtualUser.ClickButton2](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#ClickButton2)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity)
  * Changed the return-type of Function [VirtualUser.MoveMouse](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#MoveMouse) from null to void
  * Changed the parameters of Function [VirtualUser.MoveMouse](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#MoveMouse)
    from: (position: Vector2, camera: CFrame = 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0, 1)
    to: (position: Vector2, camera: CFrame = Identity)
  * Changed the return-type of Function [VirtualUser.SetKeyDown](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#SetKeyDown) from null to void
  * Changed the return-type of Function [VirtualUser.SetKeyUp](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#SetKeyUp) from null to void
  * Changed the return-type of Function [VirtualUser.StartRecording](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#StartRecording) from null to void
  * Changed the return-type of Function [VirtualUser.TypeKey](https://create.roblox.com/docs/reference/engine/classes/VirtualUser#TypeKey) from null to void
* Update Class [VoiceChatService](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [VoiceChatService.VoiceChatState](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#VoiceChatState): VoiceChatState [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [VoiceChatService.GetAndClearCallFailureMessage](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetAndClearCallFailureMessage) () -> string
  * Added Function [VoiceChatService.GetAudioProcessingSettings](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetAudioProcessingSettings) () -> Tuple
  * Added Function [VoiceChatService.GetGroupId](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetGroupId) () -> string
  * Added Function [VoiceChatService.GetMicDevices](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetMicDevices) () -> Tuple
  * Added Function [VoiceChatService.GetParticipants](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetParticipants) () -> Array
  * Added Function [VoiceChatService.GetSpeakerDevices](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetSpeakerDevices) () -> Tuple
  * Added Function [VoiceChatService.GetVoiceChatApiVersion](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetVoiceChatApiVersion) () -> int
  * Added Function [VoiceChatService.GetVoiceChatAvailable](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#GetVoiceChatAvailable) () -> int
  * Added Function [VoiceChatService.IsPublishPaused](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#IsPublishPaused) () -> bool
  * Added Function [VoiceChatService.IsSubscribePaused](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#IsSubscribePaused) (userId: int64) -> bool
  * Added Function [VoiceChatService.JoinByGroupId](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#JoinByGroupId) (groupId: string, isMicMuted: bool = false) -> bool
  * Added Function [VoiceChatService.JoinByGroupIdToken](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#JoinByGroupIdToken) (groupId: string, isMicMuted: bool = false) -> bool
  * Added Function [VoiceChatService.Leave](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#Leave) () -> void
  * Added Function [VoiceChatService.PublishPause](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#PublishPause) (paused: bool) -> bool
  * Added Function [VoiceChatService.SetMicDevice](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#SetMicDevice) (micDeviceName: string, micDeviceGuid: string) -> void
  * Added Function [VoiceChatService.SetSpeakerDevice](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#SetSpeakerDevice) (speakerDeviceName: string, speakerDeviceGuid: string) -> void
  * Added Function [VoiceChatService.SubscribePause](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#SubscribePause) (userId: int64, paused: bool) -> bool
  * Added Event [VoiceChatService.ParticipantsStateChanged](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#ParticipantsStateChanged)
  * Added Event [VoiceChatService.PlayerMicActivitySignalChange](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#PlayerMicActivitySignalChange)
  * Added Event [VoiceChatService.StateChanged](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#StateChanged)
  * Removed Property VoiceChatService.DefaultDistanceAttenuation
  * Removed Property VoiceChatService.EnableDefaultVoice
  * Removed Property VoiceChatService.EnableVoiceVolumeControls
  * Removed Property VoiceChatService.UseAudioApi
  * Removed Property VoiceChatService.UseNewAudioApi
  * Removed Property VoiceChatService.UseNewControlPaths
  * Removed Property VoiceChatService.UseNewJoinFlow
  * Removed Property VoiceChatService.UseStreamSwitching
  * Removed Property VoiceChatService.VoiceChatEnabledForPlaceOnRcc
  * Removed Property VoiceChatService.VoiceChatEnabledForUniverseOnRcc
  * Removed Function VoiceChatService.getInternalChannelId
  * Removed Function VoiceChatService.getInternalGroupId
  * Removed Function VoiceChatService.getInternalPublishPause
  * Removed Function VoiceChatService.getInternalSessionId
  * Removed Function VoiceChatService.getInternalSubscribePause
  * Removed Function VoiceChatService.getInternalSubscribePauseAll
  * Removed Function VoiceChatService.getInternalVoiceChatApiVersion
  * Removed Function VoiceChatService.isInternalPublishPaused
  * Removed Function VoiceChatService.joinVoice
  * Removed Function VoiceChatService.lastVoiceChatStats
  * Removed Function VoiceChatService.leaveVoice
  * Removed Function VoiceChatService.notifyServerACSCleanup
  * Removed Function VoiceChatService.rejoinVoice
  * Removed Function VoiceChatService.GetChatGroupsAsync
  * Removed Function VoiceChatService.IsVoiceEnabledForUserIdAsync
  * Removed Event VoiceChatService.VoiceChatStatsCollected
* Added Class [VoiceSource](https://create.roblox.com/docs/reference/engine/classes/VoiceSource) {🔒None} [⬆️Extends: Instance] [🧠Memory: Internal] [🏷️ NotCreatable] [🏷️ Deprecated]
  * Added Property [VoiceSource.UserId](https://create.roblox.com/docs/reference/engine/classes/VoiceSource#UserId) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [WeldConstraint](https://create.roblox.com/docs/reference/engine/classes/WeldConstraint) [⬆️Extends: Instance] [🧠Memory: PhysicsParts]
  * Changed MemoryCategory of Class [WeldConstraint](https://create.roblox.com/docs/reference/engine/classes/WeldConstraint) from `BaseParts` to `PhysicsParts`
  * Changed the capabilities of Property [WeldConstraint.Active](https://create.roblox.com/docs/reference/engine/classes/WeldConstraint#Active)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [WeldConstraint.Enabled](https://create.roblox.com/docs/reference/engine/classes/WeldConstraint#Enabled)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [WeldConstraint.Part0](https://create.roblox.com/docs/reference/engine/classes/WeldConstraint#Part0)
    from: {🚧Read: Physics}
    to: {🚧None}
  * Changed the capabilities of Property [WeldConstraint.Part1](https://create.roblox.com/docs/reference/engine/classes/WeldConstraint#Part1)
    from: {🚧Read: Physics}
    to: {🚧None}
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
* Added Enum [ABTestLoadingStatus](https://create.roblox.com/docs/reference/engine/enums/ABTestLoadingStatus)
  * Added EnumItem `None` (0)
  * Added EnumItem `Pending` (1)
  * Added EnumItem `Initialized` (2)
  * Added EnumItem `Error` (3)
  * Added EnumItem `TimedOut` (4)
  * Added EnumItem `ShutOff` (5)
* Update Enum [AccessoryType](https://create.roblox.com/docs/reference/engine/enums/AccessoryType)
  * Removed EnumItem `Eyebrow`
  * Removed EnumItem `Eyelash`
* Update Enum [AlignType](https://create.roblox.com/docs/reference/engine/enums/AlignType)
  * Removed EnumItem `PrimaryAxisParallel`
  * Removed EnumItem `PrimaryAxisPerpendicular`
  * Removed EnumItem `PrimaryAxisLookAt`
  * Removed EnumItem `AllAxes`
* Update Enum [AlphaMode](https://create.roblox.com/docs/reference/engine/enums/AlphaMode)
  * Removed EnumItem `TintMask`
  * Removed EnumItem `Opaque`
* Update Enum [AnimationPriority](https://create.roblox.com/docs/reference/engine/enums/AnimationPriority)
  * Removed EnumItem `Action2`
  * Removed EnumItem `Action3`
  * Removed EnumItem `Action4`
* Update Enum [AppShellActionType](https://create.roblox.com/docs/reference/engine/enums/AppShellActionType)
  * Removed EnumItem `HomePageInteractive`
* Update Enum [AppShellFeature](https://create.roblox.com/docs/reference/engine/enums/AppShellFeature)
  * Removed EnumItem `WatchPage`
* Update Enum [AppUpdateStatus](https://create.roblox.com/docs/reference/engine/enums/AppUpdateStatus)
  * Removed EnumItem `AvailableBoundChannel`
  * Removed EnumItem `AvailableBetaProgram`
* Update Enum [AssetFetchStatus](https://create.roblox.com/docs/reference/engine/enums/AssetFetchStatus)
  * Removed EnumItem `None`
  * Removed EnumItem `Loading`
  * Removed EnumItem `TimedOut`
* Update Enum [AssetType](https://create.roblox.com/docs/reference/engine/enums/AssetType)
  * Removed EnumItem `FontFamily`
  * Removed EnumItem `EyebrowAccessory`
  * Removed EnumItem `EyelashAccessory`
  * Removed EnumItem `MoodAnimation`
  * Removed EnumItem `DynamicHead`
  * Removed EnumItem `FaceMakeup`
  * Removed EnumItem `LipMakeup`
  * Removed EnumItem `EyeMakeup`
  * Removed EnumItem `AvatarBackground`
  * Removed EnumItem `TextDocument`
* Update Enum [AvatarAssetType](https://create.roblox.com/docs/reference/engine/enums/AvatarAssetType)
  * Removed EnumItem `EyebrowAccessory`
  * Removed EnumItem `EyelashAccessory`
  * Removed EnumItem `MoodAnimation`
  * Removed EnumItem `DynamicHead`
  * Removed EnumItem `FaceMakeup`
  * Removed EnumItem `LipMakeup`
  * Removed EnumItem `EyeMakeup`
  * Removed EnumItem `AvatarBackground`
* Update Enum [BundleType](https://create.roblox.com/docs/reference/engine/enums/BundleType)
  * Removed EnumItem `Shoes`
  * Removed EnumItem `DynamicHead`
  * Removed EnumItem `DynamicHeadAvatar`
* Update Enum [CatalogSortType](https://create.roblox.com/docs/reference/engine/enums/CatalogSortType)
  * Added EnumItem `RecentlyUpdated` (4)
  * Removed EnumItem `RecentlyCreated`
  * Removed EnumItem `Bestselling`
* Update Enum [CollisionFidelity](https://create.roblox.com/docs/reference/engine/enums/CollisionFidelity)
  * Removed EnumItem `Scalable`
* Update Enum [ConnectionError](https://create.roblox.com/docs/reference/engine/enums/ConnectionError)
  * Removed EnumItem `Unknown`
  * Removed EnumItem `ConnectErrors`
  * Removed EnumItem `AlreadyConnected`
  * Removed EnumItem `NoFreeIncomingConnections`
  * Removed EnumItem `ConnectionBanned`
  * Removed EnumItem `InvalidPassword`
  * Removed EnumItem `IncompatibleProtocolVersion`
  * Removed EnumItem `IPRecentlyConnected`
  * Removed EnumItem `OurSystemRequiresSecurity`
  * Removed EnumItem `SecurityKeyMismatch`
  * Removed EnumItem `DisconnectClientRequest`
  * Removed EnumItem `DisconnectPrivateServerKickout`
  * Removed EnumItem `DisconnectModeratedGame`
  * Removed EnumItem `ServerShutdown`
  * Removed EnumItem `ReplicatorTimeout`
  * Removed EnumItem `PlayerRemoved`
  * Removed EnumItem `DisconnectOutOfMemoryKeepPlayingLeave`
  * Removed EnumItem `DisconnectRomarkEndOfTest`
  * Removed EnumItem `DisconnectCollaboratorPermissionRevoked`
  * Removed EnumItem `DisconnectCollaboratorUnderage`
  * Removed EnumItem `NetworkInternal`
  * Removed EnumItem `NetworkSend`
  * Removed EnumItem `NetworkTimeout`
  * Removed EnumItem `NetworkMisbehavior`
  * Removed EnumItem `NetworkSecurity`
  * Removed EnumItem `ReplacementReady`
  * Removed EnumItem `ServerEmpty`
  * Removed EnumItem `PhantomFreeze`
  * Removed EnumItem `AndroidAnticheatKick`
  * Removed EnumItem `AndroidEmulatorKick`
  * Removed EnumItem `AndroidRootedKick`
  * Removed EnumItem `ScreentimeLockoutKick`
  * Removed EnumItem `DisconnectionNotification`
  * Removed EnumItem `DisconnectVerboselyModeratedGame`
  * Removed EnumItem `DisconnectCollaboratorNotAgeVerified`
  * Removed EnumItem `DisconnectCollaboratorTrustedConnectionsRequired`
  * Removed EnumItem `DisconnectCollaboratorOwnerActionRequired`
  * Removed EnumItem `DisconnectCollaboratorTooManyCollaborators`
  * Removed EnumItem `DisconnectCollaboratorUnknownError`
  * Removed EnumItem `DisconnectCollaboratorRequestedEviction`
  * Removed EnumItem `DisconnectCollaboratorTrustedConnectionsRequiredPC`
  * Removed EnumItem `DisconnectRemoteAttestationUnsupported`
  * Removed EnumItem `DisconnectRemoteAttestationGeneralFailure`
  * Removed EnumItem `DisconnectRemoteAttestationTimeout`
  * Removed EnumItem `DisconnectRemoteAttestationOSOutOfDate`
  * Removed EnumItem `DisconnectRemoteAttestationBootValidationFailure`
  * Removed EnumItem `PlacelaunchUserPrivacyUnauthorized`
  * Removed EnumItem `PlacelaunchVipOwnerNotPresent`
  * Removed EnumItem `PlacelaunchAgeVerificationRequired`
  * Removed EnumItem `PlacelaunchParentalApprovalRequired`
  * Removed EnumItem `PlacelaunchCoreGated`
  * Removed EnumItem `PlacelaunchCollaborationCoreGated`
  * Removed EnumItem `PlacelaunchCreatorBan`
  * Removed EnumItem `PlacelaunchDeviceBlock`
* Update Enum [ContextActionPriority](https://create.roblox.com/docs/reference/engine/enums/ContextActionPriority)
  * Added EnumItem `Default` (2000)
* Update Enum [CoreGuiType](https://create.roblox.com/docs/reference/engine/enums/CoreGuiType)
  * Removed EnumItem `SelfView`
  * Removed EnumItem `Captures`
  * Removed EnumItem `AvatarSwitcher`
  * Removed EnumItem `ExperienceShop`
* Update Enum [DataStoreRequestType](https://create.roblox.com/docs/reference/engine/enums/DataStoreRequestType)
  * Removed EnumItem `ListAsync`
  * Removed EnumItem `GetVersionAsync`
  * Removed EnumItem `RemoveVersionAsync`
  * Removed EnumItem `StandardRead`
  * Removed EnumItem `StandardWrite`
  * Removed EnumItem `StandardList`
  * Removed EnumItem `StandardRemove`
  * Removed EnumItem `OrderedRead`
  * Removed EnumItem `OrderedWrite`
  * Removed EnumItem `OrderedList`
  * Removed EnumItem `OrderedRemove`
* Update Enum [DebuggerStatus](https://create.roblox.com/docs/reference/engine/enums/DebuggerStatus)
  * Removed EnumItem `ConnectionClosed`
* Update Enum [DeveloperMemoryTag](https://create.roblox.com/docs/reference/engine/enums/DeveloperMemoryTag)
  * Added EnumItem `PhysicsParts` (7)
  * Changed Value of EnumItem `GraphicsMeshParts` from `10` to `9`
  * Changed Value of EnumItem `GraphicsParticles` from `11` to `10`
  * Changed Value of EnumItem `GraphicsParts` from `12` to `11`
  * Changed Value of EnumItem `GraphicsSpatialHash` from `13` to `12`
  * Changed Value of EnumItem `GraphicsTerrain` from `14` to `13`
  * Changed Value of EnumItem `GraphicsTexture` from `15` to `14`
  * Changed Value of EnumItem `GraphicsTextureCharacter` from `16` to `15`
  * Changed Value of EnumItem `Sounds` from `17` to `16`
  * Changed Value of EnumItem `StreamingSounds` from `18` to `17`
  * Changed Value of EnumItem `TerrainVoxels` from `19` to `18`
  * Changed Value of EnumItem `Gui` from `21` to `20`
  * Changed Value of EnumItem `Animation` from `22` to `21`
  * Changed Value of EnumItem `Navigation` from `23` to `22`
  * Removed EnumItem `BaseParts`
  * Removed EnumItem `GeometryCSG`
  * Removed EnumItem `GraphicsSlimModels`
* Update Enum [DeviceType](https://create.roblox.com/docs/reference/engine/enums/DeviceType)
  * Removed EnumItem `TV`
* Update Enum [Font](https://create.roblox.com/docs/reference/engine/enums/Font)
  * Added EnumItem `GothamSemibold` (18)
  * Removed EnumItem `GothamMedium`
  * Removed EnumItem `BuilderSans`
  * Removed EnumItem `BuilderSansMedium`
  * Removed EnumItem `BuilderSansBold`
  * Removed EnumItem `BuilderSansExtraBold`
  * Removed EnumItem `Arimo`
  * Removed EnumItem `ArimoBold`
  * Removed EnumItem `Unknown`
* Update Enum [GraphicsMode](https://create.roblox.com/docs/reference/engine/enums/GraphicsMode)
  * Added EnumItem `Direct3D9` (3)
  * Changed Value of EnumItem `NoGraphics` from `9` to `7`
* Update Enum [HttpError](https://create.roblox.com/docs/reference/engine/enums/HttpError)
  * Removed EnumItem `ConnectionClosed`
  * Removed EnumItem `ServerProtocolError`
  * Removed EnumItem `CreatorEnvironmentsNotSupportedByService`
  * Removed EnumItem `InactivityTimeout`
  * Removed EnumItem `TooManyOutstandingRequests`
  * Removed EnumItem `InvalidRangeResponse`
* Added Enum [HumanoidOnlySetCollisionsOnStateChange](https://create.roblox.com/docs/reference/engine/enums/HumanoidOnlySetCollisionsOnStateChange)
  * Added EnumItem `Default` (0)
  * Added EnumItem `Disabled` (1)
  * Added EnumItem `Enabled` (2)
* Update Enum [IXPLoadingStatus](https://create.roblox.com/docs/reference/engine/enums/IXPLoadingStatus)
  * Added EnumItem `ShutOff` (3)
  * Changed Value of EnumItem `ErrorTimedOut` from `6` to `7`
  * Changed Value of EnumItem `ErrorConnection` from `4` to `5`
  * Changed Value of EnumItem `ErrorJsonParse` from `5` to `6`
  * Changed Value of EnumItem `ErrorInvalidUser` from `3` to `4`
* Update Enum [KeyCode](https://create.roblox.com/docs/reference/engine/enums/KeyCode)
  * Added EnumItem `Unknown` (0)
  * Removed EnumItem `None`
  * Removed EnumItem `Thumbstick1Up`
  * Removed EnumItem `Thumbstick1Down`
  * Removed EnumItem `Thumbstick1Left`
  * Removed EnumItem `Thumbstick1Right`
  * Removed EnumItem `Thumbstick2Up`
  * Removed EnumItem `Thumbstick2Down`
  * Removed EnumItem `Thumbstick2Left`
  * Removed EnumItem `Thumbstick2Right`
  * Removed EnumItem `MouseLeftButton`
  * Removed EnumItem `MouseRightButton`
  * Removed EnumItem `MouseMiddleButton`
  * Removed EnumItem `MouseBackButton`
  * Removed EnumItem `MouseNoButton`
  * Removed EnumItem `MouseX`
  * Removed EnumItem `MouseY`
  * Removed EnumItem `MousePosition`
  * Removed EnumItem `TouchPosition`
  * Removed EnumItem `MouseWheel`
  * Removed EnumItem `TrackpadPan`
  * Removed EnumItem `TrackpadPinch`
  * Removed EnumItem `MouseDelta`
  * Removed EnumItem `TouchDelta`
  * Removed EnumItem `TouchPinch`
  * Removed EnumItem `ButtonCenter`
  * Removed EnumItem `ButtonBack`
  * Removed EnumItem `ButtonUp`
  * Removed EnumItem `ButtonDown`
  * Removed EnumItem `ButtonLeft`
  * Removed EnumItem `ButtonRight`
* Added Enum [LevelOfDetailSetting](https://create.roblox.com/docs/reference/engine/enums/LevelOfDetailSetting)
  * Added EnumItem `High` (2)
  * Added EnumItem `Medium` (1)
  * Added EnumItem `Low` (0)
* Update Enum [Material](https://create.roblox.com/docs/reference/engine/enums/Material)
  * Removed EnumItem `Cardboard`
  * Removed EnumItem `Carpet`
  * Removed EnumItem `CeramicTiles`
  * Removed EnumItem `ClayRoofTiles`
  * Removed EnumItem `RoofShingles`
  * Removed EnumItem `Leather`
  * Removed EnumItem `Plaster`
  * Removed EnumItem `Rubber`
* Update Enum [MeshPartDetailLevel](https://create.roblox.com/docs/reference/engine/enums/MeshPartDetailLevel)
  * Changed Value of EnumItem `Level01` from `2` to `1`
  * Changed Value of EnumItem `Level02` from `3` to `2`
  * Changed Value of EnumItem `Level03` from `4` to `3`
  * Changed Value of EnumItem `Level04` from `5` to `4`
  * Removed EnumItem `Level00`
  * Removed EnumItem `Level05`
  * Removed EnumItem `Level06`
  * Removed EnumItem `Level07`
  * Removed EnumItem `Level08`
  * Removed EnumItem `Level09`
* Update Enum [ModelLevelOfDetail](https://create.roblox.com/docs/reference/engine/enums/ModelLevelOfDetail)
  * Removed EnumItem `SLIM`
* Added Enum [NewAnimationRuntimeSetting](https://create.roblox.com/docs/reference/engine/enums/NewAnimationRuntimeSetting)
  * Added EnumItem `Default` (0)
  * Added EnumItem `Disabled` (1)
  * Added EnumItem `Enabled` (2)
* Added Enum [PacketPriority](https://create.roblox.com/docs/reference/engine/enums/PacketPriority)
  * Added EnumItem `IMMEDIATE_PRIORITY` (0)
  * Added EnumItem `HIGH_PRIORITY` (1)
  * Added EnumItem `MEDIUM_PRIORITY` (2)
  * Added EnumItem `LOW_PRIORITY` (3)
* Update Enum [PartType](https://create.roblox.com/docs/reference/engine/enums/PartType)
  * Removed EnumItem `Wedge`
  * Removed EnumItem `CornerWedge`
* Update Enum [PathWaypointAction](https://create.roblox.com/docs/reference/engine/enums/PathWaypointAction)
  * Removed EnumItem `Custom`
* Update Enum [Platform](https://create.roblox.com/docs/reference/engine/enums/Platform)
  * Changed Value of EnumItem `None` from `22` to `19`
  * Removed EnumItem `PS5`
  * Removed EnumItem `MetaOS`
  * Removed EnumItem `Web`
* Update Enum [PoseEasingStyle](https://create.roblox.com/docs/reference/engine/enums/PoseEasingStyle)
  * Removed EnumItem `CubicV2`
* Update Enum [RaycastFilterType](https://create.roblox.com/docs/reference/engine/enums/RaycastFilterType)
  * Added EnumItem `Blacklist` (0)
  * Added EnumItem `Whitelist` (1)
  * Removed EnumItem `Exclude`
  * Removed EnumItem `Include`
* Update Enum [RibbonTool](https://create.roblox.com/docs/reference/engine/enums/RibbonTool)
  * Removed EnumItem `PivotEditor`
* Added Enum [ServerAudioBehavior](https://create.roblox.com/docs/reference/engine/enums/ServerAudioBehavior)
  * Added EnumItem `Enabled` (0)
  * Added EnumItem `Muted` (1)
  * Added EnumItem `OnlineGame` (2)
* Update Enum [SignalBehavior](https://create.roblox.com/docs/reference/engine/enums/SignalBehavior)
  * Removed EnumItem `AncestryDeferred`
* Added Enum [SoundType](https://create.roblox.com/docs/reference/engine/enums/SoundType)
  * Added EnumItem `NoSound` (0)
  * Added EnumItem `Boing` (1)
  * Added EnumItem `Bomb` (2)
  * Added EnumItem `Break` (3)
  * Added EnumItem `Click` (4)
  * Added EnumItem `Clock` (5)
  * Added EnumItem `Slingshot` (6)
  * Added EnumItem `Page` (7)
  * Added EnumItem `Ping` (8)
  * Added EnumItem `Snap` (9)
  * Added EnumItem `Splat` (10)
  * Added EnumItem `Step` (11)
  * Added EnumItem `StepOn` (12)
  * Added EnumItem `Swoosh` (13)
  * Added EnumItem `Victory` (14)
* Update Enum [StudioCloseMode](https://create.roblox.com/docs/reference/engine/enums/StudioCloseMode)
  * Removed EnumItem `LogOut`
* Update Enum [StudioDataModelType](https://create.roblox.com/docs/reference/engine/enums/StudioDataModelType)
  * Added EnumItem `RobloxPlugin` (3)
  * Added EnumItem `UserPlugin` (4)
  * Changed Value of EnumItem `None` from `4` to `5`
  * Removed EnumItem `Standalone`
* Update Enum [StudioScriptEditorColorCategories](https://create.roblox.com/docs/reference/engine/enums/StudioScriptEditorColorCategories)
  * Changed Value of EnumItem `Whitespace` from `26` to `24`
  * Changed Value of EnumItem `ActiveLine` from `27` to `25`
  * Changed Value of EnumItem `DebuggerCurrentLine` from `28` to `26`
  * Changed Value of EnumItem `DebuggerErrorLine` from `29` to `27`
  * Changed Value of EnumItem `Ruler` from `30` to `28`
  * Changed Value of EnumItem `Bracket` from `31` to `29`
  * Changed Value of EnumItem `MenuPrimaryText` from `33` to `30`
  * Changed Value of EnumItem `MenuSecondaryText` from `34` to `31`
  * Changed Value of EnumItem `MenuSelectedText` from `35` to `32`
  * Changed Value of EnumItem `MenuBackground` from `36` to `33`
  * Changed Value of EnumItem `MenuSelectedBackground` from `37` to `34`
  * Changed Value of EnumItem `MenuScrollbarBackground` from `38` to `35`
  * Changed Value of EnumItem `MenuScrollbarHandle` from `39` to `36`
  * Changed Value of EnumItem `MenuBorder` from `40` to `37`
  * Removed EnumItem `Info`
  * Removed EnumItem `Hint`
  * Removed EnumItem `Type`
  * Removed EnumItem `DocViewCodeBackground`
  * Removed EnumItem `AICOOverlayText`
  * Removed EnumItem `AICOOverlayButtonBackground`
  * Removed EnumItem `AICOOverlayButtonBackgroundHover`
  * Removed EnumItem `AICOOverlayButtonBackgroundPressed`
  * Removed EnumItem `IndentationRuler`
* Update Enum [StudioStyleGuideColor](https://create.roblox.com/docs/reference/engine/enums/StudioStyleGuideColor)
  * Changed Value of EnumItem `Shadow` from `33` to `32`
  * Changed Value of EnumItem `Light` from `34` to `33`
  * Changed Value of EnumItem `Dark` from `35` to `34`
  * Changed Value of EnumItem `Mid` from `36` to `35`
  * Changed Value of EnumItem `MainText` from `37` to `36`
  * Changed Value of EnumItem `SubText` from `38` to `37`
  * Changed Value of EnumItem `TitlebarText` from `39` to `38`
  * Changed Value of EnumItem `BrightText` from `40` to `39`
  * Changed Value of EnumItem `DimmedText` from `41` to `40`
  * Changed Value of EnumItem `LinkText` from `42` to `41`
  * Changed Value of EnumItem `WarningText` from `43` to `42`
  * Changed Value of EnumItem `ErrorText` from `44` to `43`
  * Changed Value of EnumItem `InfoText` from `45` to `44`
  * Changed Value of EnumItem `SensitiveText` from `46` to `45`
  * Changed Value of EnumItem `ScriptSideWidget` from `47` to `46`
  * Changed Value of EnumItem `ScriptBackground` from `48` to `47`
  * Changed Value of EnumItem `ScriptText` from `49` to `48`
  * Changed Value of EnumItem `ScriptSelectionText` from `50` to `49`
  * Changed Value of EnumItem `ScriptSelectionBackground` from `51` to `50`
  * Changed Value of EnumItem `ScriptFindSelectionBackground` from `52` to `51`
  * Changed Value of EnumItem `ScriptMatchingWordSelectionBackground` from `53` to `52`
  * Changed Value of EnumItem `ScriptOperator` from `54` to `53`
  * Changed Value of EnumItem `ScriptNumber` from `55` to `54`
  * Changed Value of EnumItem `ScriptString` from `56` to `55`
  * Changed Value of EnumItem `ScriptComment` from `57` to `56`
  * Changed Value of EnumItem `ScriptKeyword` from `58` to `57`
  * Changed Value of EnumItem `ScriptBuiltInFunction` from `59` to `58`
  * Changed Value of EnumItem `ScriptWarning` from `60` to `59`
  * Changed Value of EnumItem `ScriptError` from `61` to `60`
  * Changed Value of EnumItem `ScriptWhitespace` from `64` to `61`
  * Changed Value of EnumItem `ScriptRuler` from `65` to `62`
  * Changed Value of EnumItem `DebuggerCurrentLine` from `67` to `63`
  * Changed Value of EnumItem `DebuggerErrorLine` from `68` to `64`
  * Changed Value of EnumItem `ScriptEditorCurrentLine` from `107` to `103`
  * Changed Value of EnumItem `DiffFilePathText` from `69` to `65`
  * Changed Value of EnumItem `DiffTextHunkInfo` from `70` to `66`
  * Changed Value of EnumItem `DiffTextNoChange` from `71` to `67`
  * Changed Value of EnumItem `DiffTextAddition` from `72` to `68`
  * Changed Value of EnumItem `DiffTextDeletion` from `73` to `69`
  * Changed Value of EnumItem `DiffTextSeparatorBackground` from `74` to `70`
  * Changed Value of EnumItem `DiffTextNoChangeBackground` from `75` to `71`
  * Changed Value of EnumItem `DiffTextAdditionBackground` from `76` to `72`
  * Changed Value of EnumItem `DiffTextDeletionBackground` from `77` to `73`
  * Changed Value of EnumItem `DiffLineNum` from `78` to `74`
  * Changed Value of EnumItem `DiffLineNumSeparatorBackground` from `79` to `75`
  * Changed Value of EnumItem `DiffLineNumNoChangeBackground` from `80` to `76`
  * Changed Value of EnumItem `DiffLineNumAdditionBackground` from `81` to `77`
  * Changed Value of EnumItem `DiffLineNumDeletionBackground` from `82` to `78`
  * Changed Value of EnumItem `DiffFilePathBackground` from `83` to `79`
  * Changed Value of EnumItem `DiffFilePathBorder` from `84` to `80`
  * Changed Value of EnumItem `ChatIncomingBgColor` from `85` to `81`
  * Changed Value of EnumItem `ChatIncomingTextColor` from `86` to `82`
  * Changed Value of EnumItem `ChatOutgoingBgColor` from `87` to `83`
  * Changed Value of EnumItem `ChatOutgoingTextColor` from `88` to `84`
  * Changed Value of EnumItem `ChatModeratedMessageColor` from `89` to `85`
  * Changed Value of EnumItem `Separator` from `90` to `86`
  * Changed Value of EnumItem `ButtonBorder` from `91` to `87`
  * Changed Value of EnumItem `ButtonText` from `92` to `88`
  * Changed Value of EnumItem `InputFieldBorder` from `93` to `89`
  * Changed Value of EnumItem `CheckedFieldBackground` from `94` to `90`
  * Changed Value of EnumItem `CheckedFieldBorder` from `95` to `91`
  * Changed Value of EnumItem `CheckedFieldIndicator` from `96` to `92`
  * Changed Value of EnumItem `HeaderSection` from `97` to `93`
  * Changed Value of EnumItem `Midlight` from `98` to `94`
  * Changed Value of EnumItem `StatusBar` from `99` to `95`
  * Changed Value of EnumItem `DialogButton` from `100` to `96`
  * Changed Value of EnumItem `DialogButtonText` from `101` to `97`
  * Changed Value of EnumItem `DialogButtonBorder` from `102` to `98`
  * Changed Value of EnumItem `DialogMainButton` from `103` to `99`
  * Changed Value of EnumItem `DialogMainButtonText` from `104` to `100`
  * Changed Value of EnumItem `InfoBarWarningBackground` from `105` to `101`
  * Changed Value of EnumItem `InfoBarWarningText` from `106` to `102`
  * Changed Value of EnumItem `ScriptMethod` from `108` to `104`
  * Changed Value of EnumItem `ScriptProperty` from `109` to `105`
  * Changed Value of EnumItem `ScriptNil` from `110` to `106`
  * Changed Value of EnumItem `ScriptBool` from `111` to `107`
  * Changed Value of EnumItem `ScriptFunction` from `112` to `108`
  * Changed Value of EnumItem `ScriptLocal` from `113` to `109`
  * Changed Value of EnumItem `ScriptSelf` from `114` to `110`
  * Changed Value of EnumItem `ScriptLuauKeyword` from `115` to `111`
  * Changed Value of EnumItem `ScriptFunctionName` from `116` to `112`
  * Changed Value of EnumItem `ScriptTodo` from `117` to `113`
  * Changed Value of EnumItem `ScriptBracket` from `118` to `114`
  * Changed Value of EnumItem `AttributeCog` from `119` to `115`
  * Removed EnumItem `DropShadow`
  * Removed EnumItem `ScriptInformation`
  * Removed EnumItem `ScriptHint`
  * Removed EnumItem `DocViewCodeBackground`
  * Removed EnumItem `AICOOverlayText`
  * Removed EnumItem `AICOOverlayButtonBackground`
  * Removed EnumItem `AICOOverlayButtonBackgroundHover`
  * Removed EnumItem `AICOOverlayButtonBackgroundPressed`
  * Removed EnumItem `OnboardingCover`
  * Removed EnumItem `OnboardingHighlight`
  * Removed EnumItem `OnboardingShadow`
  * Removed EnumItem `BreakpointMarker`
  * Removed EnumItem `DiffLineNumHover`
  * Removed EnumItem `DiffLineNumSeparatorBackgroundHover`
* Update Enum [Technology](https://create.roblox.com/docs/reference/engine/enums/Technology)
  * Removed EnumItem `Unified`
* Update Enum [TeleportMethod](https://create.roblox.com/docs/reference/engine/enums/TeleportMethod)
  * Changed Value of EnumItem `TeleportUnknown` from `6` to `4`
  * Removed EnumItem `TeleportToVIPServer`
  * Removed EnumItem `TeleportToInstanceBack`
* Update Enum [TeleportType](https://create.roblox.com/docs/reference/engine/enums/TeleportType)
  * Removed EnumItem `ToVIPServer`
  * Removed EnumItem `ToInstanceBack`
* Update Enum [TextInputType](https://create.roblox.com/docs/reference/engine/enums/TextInputType)
  * Removed EnumItem `NewPassword`
  * Removed EnumItem `NewPasswordShown`
* Update Enum [TextTruncate](https://create.roblox.com/docs/reference/engine/enums/TextTruncate)
  * Removed EnumItem `SplitWord`
* Update Enum [UserCFrame](https://create.roblox.com/docs/reference/engine/enums/UserCFrame)
  * Removed EnumItem `Floor`
* Update Enum [WrapLayerDebugMode](https://create.roblox.com/docs/reference/engine/enums/WrapLayerDebugMode)
  * Removed EnumItem `ReferenceMeshAfterMorph`
  * Removed EnumItem `HSROuterDetail`
  * Removed EnumItem `HSROuter`
  * Removed EnumItem `HSRInner`
  * Removed EnumItem `HSRInnerReverse`
  * Removed EnumItem `LayerCageFittedToBase`
  * Removed EnumItem `LayerCageFittedToPrev`
  * Removed EnumItem `PreWrapDeformerOuterCage`
  * Removed EnumItem `SkinningTransfer`
* Update Enum [WrapTargetDebugMode](https://create.roblox.com/docs/reference/engine/enums/WrapTargetDebugMode)
  * Removed EnumItem `OuterCageDetail`
  * Removed EnumItem `PreWrapDeformerCage`
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
