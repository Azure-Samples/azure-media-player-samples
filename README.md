---
page_type: sample
languages:
  - javascript
products:
  - azure
  - azure-media-services
  - azure-media-player
description: "The samples in this repo show how to use the Azure Media Player in multiple scenarios."  
---
 
# Azure Media Player Samples

The samples in this repo show how to embed the Azure Media player either dynamically with JavaScript or statically with HTML5 video element attributes.

## Contents

Outline the file contents of the repository. It helps users navigate the codebase, build configuration and any related assets.

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `html`            | Azure Media Player embedding samples       |
| `.gitignore`      | Define what to ignore at commit time.      |
| `CHANGELOG.md`    | List of changes to the sample.             |
| `CONTRIBUTING.md` | Guidelines for contributing to the sample. |
| `README.md`       | This README file.                          |
| `LICENSE`         | The license for the sample.                |

## Azure Media Player

You can use Azure Media Player to stream videos from Azure Media Services. The samples in this set include basic to advanced configurations (listed below.)

<iframe src="https://github.com/Azure-Samples/azure-media-player-samples/blob/master/html/azure-media-player-sample-dynamic-setsource.html" width="640" height="320" allowFullScreen="true" frameBorder="0"></iframe>

## Sample Listing

| Sample Name | Programmatic via JavaScript | Static via HTML5 | Description |
|-------------|-------------|
|\4 Basic |
| Set Source | Dynamic: azure-media-player-samples-dynamic_setsource.html | Static: azure-media-player-samples-videotag_setsource.html) | Playback unprotected content. |
|\4 Features |
| VOD Ad insertion (VAST) | Dynamic: azure-media-player-samples-dynamic_vast_ads_vod.html) | N/A | Insert pre- mid- and post- roll VAST ads into a VOD asset. |
| Playback Speed | Dynamic: azure-media-player-samples-dynamic_playback_speed.html | N/A |  Enables viewers to control what speed they're watching their video at. |  
| AMP Flush Skin | Dynamic: azure-media-player-samples-dynamic_flush_skin.html)| Static: azure-media-player-samples-videotag_flush_skin.html) | Enables new AMP skin. **Please note: AMP flush is only supported in AMP versions 2.1.0+** |
| Captions and Subtitles| Dynamic: azure-media-player-samples-dynamic_webvtt.html) | Static: azure-media-player-samples-videotag_webvtt.html | Playback with WebVTT subtitles.|  
| Live CEA 708 Captions | Dynamic: azure-media-player-samples-dynamic_live_captions.html)| N/A | Playback with live CEA 708 inbound captions.|
| Streaming with Progressive Fallback | Dynamic: azure-media-player-samples-dynamic_progressiveFallback.html) | Static: azure-media-player-samples-videotag_progressiveFallback.html | Basic setup of adaptive playback with fallback for progressive if streaming not supported on platform.|
| Progressive Video MP4 | Dynamic: azure-media-player-samples-dynamic_progressiveVideo.html)| Static: azure-media-player-samples-videotag_progressiveVideo.html | Playback of progressive audio MP4. |
| Progressive Audio MP3 | Dynamic: azure-media-player-samples-dynamic_progressiveAudio.html) | Static: azure-media-player-samples-videotag_progressiveAudio.html | Playback of progressive audio MP3. |
| DD+ | Dynamic: azure-media-player-samples-dynamic_dolbyDigitalPlus.html) | N/A | Playback of content with DD+ audio. |
|\4 Options |
| Heuristic Profile | Dynamic: azure-media-player-samples-dynamic_heuristicsProfile.html) | Static: azure-media-player-samples-videotag_heuristicsProfile.html | Changing the heuristics profile |
| Localization | Dynamic: azure-media-player-samples-dynamic_localization.html) | Static: azure-media-player-samples-videotag_localization.html |  
| Setting localization |
| Audio Tracks Menu | Dynamic: azure-media-player-samples-dynamic_multiAudio.html) | Static: azure-media-player-samples-videotag_multiAudio.html| Options to show how to display audio tracks menu on the default skin. |  
| Hotkeys | Dynamic: azure-media-player-samples-dynamic_hotKeys.html">Dynamic </a> | Static: azure-media-player-samples-videotag_hotKeys.html | This sample shows how to configure which hotkeys are enabled in the player. |
|\4 Events, Logging and Diagnostics
| Register Events | Dynamic: azure-media-player-samples-dynamic_registerEvents.html) | N/A | Playback with event listeners. | 
| Logging | Dynamic: azure-media-player-samples-dynamic_logging.html) | Static: azure-media-player-samples-videotag_logging.html | Turning on verbose logging to console. |
| Diagnostics| Dynamic: azure-media-player-samples-dynamic_diagnostics.html) | N/A | Getting diagnostic data. This sample only works on some techs. |
|\4 AES |
| AES no token | Dynamic: azure-media-player-samples-dynamic_aes_notoken.html) | Static: azure-media-player-samples-videotag_aes_notoken.html| Playback of AES content with no token. |
| AES token | Dynamic: azure-media-player-samples-dynamic_aes_token.html) | Static: azure-media-player-samples-videotag_aes_token.html | Playback of AES content with token.|  
| AES HLS proxy simulation | Dynamic: azure-media-player-samples-dynamic_aes_token_withHLSProxy.html) | Static: azure-media-player-samples-videotag_aes_token_withHLSProxy.html | Playback of AES content with token, showing a proxy for HLS so that token can be used with iOS devices. |
| AES token force flash | Dynamic: azure-media-player-samples-dynamic_aes_token_forceFlash.html) | Static: azure-media-player-samples-videotag_aes_token_forceFlash.html | Playback of AES content with token, forcing the flashSS tech.|  
|\4 DRM |
| Multi-DRM with PlayReady, Widevine, and FairPlay | Dynamic: azure-media-player-samples-dynamic_multiDRM_PlayReadyWidevineFairPlay_notoken.html) | Static: videotag_multiDRM_PlayReadyWidevineFairPlay_notoken.html | Playback of DRM content with no token, with PlayReady, Widevine, and FairPlay headers. |
| PlayReady no token | Dynamic: azure-media-player-samples-dynamic_playready_notoken.html) | Static: videotag_playready_notoken.html | Playback of PlayReady content with no token.|  
| PlayReady no token force Silverlight | Dynamic: azure-media-player-samples-dynamic_playready_notoken_forceSilverlight.html) | Static: videotag_playready_notoken_forceSilverlight.html | Playback of PlayReady content with no token, forcing silverlightSS tech. |
| PlayReady token | Dynamic: azure-media-player-samples-dynamic_playready_token.html) | Static: videotag_playready_token.html | Playback of PlayReady content with token.|  
| PlayReady token force Silverlight | Dynamic: azure-media-player-samples-dynamic_playready_token_forceSilverlight.html) | Static: videotag_playready_token_forceSilverlight.html | Playback of PlayReady content with token, forcing silverlightSS tech.|
|\4 Protocol and Tech |
| Change techOrder | Dynamic: azure-media-player-samples-dynamic_techOrder.html) | Static: videotag_techOrder.html | Changing the tech order|  
| Force MPEG-DASH only in UrlRewriter | Dynamic: azure-media-player-samples-dynamic_forceDash.html) | Static: videotag_forceDash.html | Playback of unprotected content only using the DASH protocol. |
| Exclude MPEG-DASH in UrlRewriter | Dynamic: azure-media-player-samples-dynamic_forceNoDash.html) | Static: videotag_forceNoDash.html | Playback of unprotected content only using the Smooth and HLS protocols. |
| Multiple delivery policy | Dynamic: azure-media-player-samples-dynamic_multipleDeliveryPolicy.html) | Static: videotag_multipleDeliveryPolicy.html | Setting the source with content that has multiple delivery policies from Azure Media Services |
|\4 Programatically Select |
| Select text track | Dynamic: azure-media-player-samples-dynamic_selectTextTrack.html) | N/A | Selecting a WebVTT track from the from the track list. |
| Select bitrate | Dynamic: azure-media-player-samples-dynamic_selectBitrate.html) | N/A | Selecting a bitrate from the list of bitrates. This sample only works on some techs. |
| Select audio stream | Dynamic: azure-media-player-samples-dynamic_selectAudioStream.html) | N/A | Selecting a Audio Stream from the list of available audio streams. This sample only works on some techs.|

## Prerequisites

- Basic knowledge of HTML5.
- A link to a video

## Setup

- Clone or download this sample repository.
- Open the sample file in Visual Studio or other code editor.
- See comments in the sample file to edit the files for your environment.

## Next steps

- Azure Media Services documentation: https://docs.microsoft.com/en-us/azure/media-services/
- Azure Media Services pricing: https://azure.microsoft.com/en-in/pricing/details/media-services/