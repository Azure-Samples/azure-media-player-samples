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
| `media`           | folder for animated GIF of player          |
| `.gitignore`      | Define what to ignore at commit time.      |
| `CHANGELOG.md`    | List of changes to the sample.             |
| `CONTRIBUTING.md` | Guidelines for contributing to the sample. |
| `README.md`       | This README file.                          |
| `LICENSE`         | The license for the sample.                |

## Azure Media Player

You can use Azure Media Player to stream videos from Azure Media Services. The samples in this set include basic to advanced configurations (listed below.) See each sample comments on how to use.

![azure media player screen capture](media/azure-media-player.gif)

You can view the Azure Media Player [demo](https://ampdemo.azureedge.net/azuremediaplayer.html) here.

## Sample Listing

| Type | Sample Name | Description | Dynamic | Static |
|-------------|-------------|-------------|-------------|-------------|
| **Basic** | Set Source | Playback unprotected content | azure-media-player-samples-dynamic_setsource.html | azure-media-player-samples-videotag_setsource.html |
| **Features** | VOD Ad insertion (VAST) | Insert pre- mid- and post- roll VAST ads into a VOD asset | azure-media-player-samples-dynamic_vast_ads_vod.html | N/A |
| | Playback Speed | Enables viewers to control what speed at which they're watching their video | azure-media-player-samples-dynamic_playback_speed.html | N/A |
| | AMP Flush Skin | Enables new AMP skin **Please note: AMP flush is only supported in AMP versions 2.1.0+** | azure-media-player-samples-dynamic_flush_skin.html| azure-media-player-samples-videotag_flush_skin.html | 
| | Captions and Subtitles|  Playback with WebVTT subtitles| azure-media-player-samples-dynamic_webvtt.html | azure-media-player-samples-videotag_webvtt.html |
| | Live CEA 708 Captions | Playback with live CEA 708 inbound captions| azure-media-player-samples-dynamic_live_captions.html| N/A |
| | Streaming with Progressive Fallback |  Basic setup of adaptive playback with fallback for progressive if streaming not supported on platform | azure-media-player-samples-dynamic_progressiveFallback.html | azure-media-player-samples-videotag_progressiveFallback.html |
| | Progressive Video MP4 | Playback of progressive audio MP4 | azure-media-player-samples-dynamic_progressiveVideo.html | azure-media-player-samples-videotag_progressiveVideo.html |
| | Progressive Audio MP3 | Playback of progressive audio MP3 | azure-media-player-samples-dynamic_progressiveAudio.html | azure-media-player-samples-videotag_progressiveAudio.html |
| | DD+ | Playback of content with DD+ audio | azure-media-player-samples-dynamic_dolbyDigitalPlus.html | N/A |
| **Options** | Heuristic Profile | Changing the heuristics profile | azure-media-player-samples-dynamic_heuristicsProfile.html | azure-media-player-samples-videotag_heuristicsProfile.html |
| | Localization | Setting localization | azure-media-player-samples-dynamic_localization.html | azure-media-player-samples-videotag_localization.html |
| | Audio Tracks Menu |  Options to show how to display audio tracks menu on the default skin | azure-media-player-samples-dynamic_multiAudio.html | Static: azure-media-player-samples-videotag_multiAudio.html|
| | Hotkeys |  This sample shows how to configure which hotkeys are enabled in the player | azure-media-player-samples-dynamic_hotKeys.html">Dynamic </a> | azure-media-player-samples-videotag_hotKeys.html |
| **Events, Logging and Diagnostics** | Register Events | Playback with event listeners | azure-media-player-samples-dynamic_registerEvents.html | N/A |
| | Logging | Turning on verbose logging to console | azure-media-player-samples-dynamic_logging.html | azure-media-player-samples-videotag_logging.html |
| | Diagnostics | Getting diagnostic data. This sample only works on some techs | azure-media-player-samples-dynamic_diagnostics.html | N/A |
| **AES** | AES no token | Playback of AES content with no token | azure-media-player-samples-dynamic_aes_notoken.html | azure-media-player-samples-videotag_aes_notoken.html|
| | AES token | Playback of AES content with token | azure-media-player-samples-dynamic_aes_token.html | azure-media-player-samples-videotag_aes_token.html |
| | AES HLS proxy simulation | Playback of AES content with token, showing a proxy for HLS so that token can be used with iOS devices | azure-media-player-samples-dynamic_aes_token_withHLSProxy.html | azure-media-player-samples-videotag_aes_token_withHLSProxy.html |
| | AES token force flash | Playback of AES content with token, forcing the flashSS tech | azure-media-player-samples-dynamic_aes_token_forceFlash.html | azure-media-player-samples-videotag_aes_token_forceFlash.html |
| **DRM** | Multi-DRM with PlayReady, Widevine, and FairPlay |  Playback of DRM content with no token, with PlayReady, Widevine, and FairPlay headers | azure-media-player-samples-dynamic_multiDRM_PlayReadyWidevineFairPlay_notoken.html | videotag_multiDRM_PlayReadyWidevineFairPlay_notoken.html |
| | PlayReady no token | Playback of PlayReady content with no token | azure-media-player-samples-dynamic_playready_notoken.html | Static: videotag_playready_notoken.html |
 | | PlayReady no token force Silverlight | Playback of PlayReady content with no token, forcing silverlightSS tech | azure-media-player-samples-dynamic_playready_notoken_forceSilverlight.html | videotag_playready_notoken_forceSilverlight.html |
| | PlayReady token | Playback of PlayReady content with token | azure-media-player-samples-dynamic_playready_token.html | videotag_playready_token.html |
| | PlayReady token force Silverlight | Playback of PlayReady content with token, forcing silverlightSS tech | azure-media-player-samples-dynamic_playready_token_forceSilverlight.html | videotag_playready_token_forceSilverlight.html |
| **Protocol and Tech** | Change techOrder |  Changing the tech order | azure-media-player-samples-dynamic_techOrder.html | videotag_techOrder.html |
| | Force MPEG-DASH only in UrlRewriter | Playback of unprotected content only using the DASH protocol | azure-media-player-samples-dynamic_forceDash.html | videotag_forceDash.html |
| | Exclude MPEG-DASH in UrlRewriter | Playback of unprotected content only using the Smooth and HLS protocols | azure-media-player-samples-dynamic_forceNoDash.html | videotag_forceNoDash.html |
| | Multiple delivery policy | Setting the source with content that has multiple delivery policies from Azure Media Services | azure-media-player-samples-dynamic_multipleDeliveryPolicy.html | videotag_multipleDeliveryPolicy.html |
| **Programatically Select** | Select text track | Selecting a WebVTT track from the from the track list | azure-media-player-samples-dynamic_selectTextTrack.html | N/A |
| | Select bitrate | Selecting a bitrate from the list of bitrates *This sample only works on some techs* | azure-media-player-samples-dynamic_selectBitrate.html | N/A |
| | Select audio stream | Selecting a Audio Stream from the list of available audio streams *This sample only works on some techs.* | azure-media-player-samples-dynamic_selectAudioStream.html | N/A |

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