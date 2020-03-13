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


| Sample Name and Description                     | File Name                                                             |
|-------------------------------------------------|:----------------------------------------------------------------------|
| **Basic**                                       | |
| Set Source <br/>Playback unprotected content. | **Dynamic:** dynamic_setsource.html<br/>**Static:** videotag_setsource.html |
| **Features**                                    | |
| VOD Ad insertion - VAST<br/>Insert pre- mid-<br/>and post- roll VAST ads into a VOD asset. | **Dynamic:** dynamic_vast_ads_vod.html<br/>**Static:** N/A |
| Playback Speed<br/>Enables viewers to control what the speed<br/> of the video. | **Dynamic:** dynamic_playback_speed.html <br/>**Static:** N/A  |
| AMP Flush Skin<br/>Enables new AMP skin.<br/>*Please note: AMP flush is only supported in<br/> AMP versions 2.1.0+* | **Dynamic:** dynamic_flush_skin.html <br/>**Static:** videotag_flush_skin.html  |
| Captions and Subtitles<br/>Playback with WebVTT subtitles. | **Dynamic:** dynamic_webvtt.html <br/>**Static:** videotag_webvtt.html |
| Live CEA 708 Captions<br/>Playback with live<br>CEA 708 inbound captions with the captions<br/> left-aligned. | **Dynamic:** dynamic_live_captions.html<br/>**Static:** N/A  |
| Streaming with Progressive Fallback<br/>Basic setup of adaptive playback with fallback<br/> for progressive if streaming not supported<br/>on platform. | **Dynamic:** dynamic_progressiveFallback.html<br/>**Static:** videotag_progressiveFallback.html  |
| Progressive Video MP4<br/>Playback of progressive MP4 video. | **Dynamic:** dynamic_progressiveVideo.html <br/>**Static:** videotag_progressiveVideo.html |
| Progressive Audio MP3<br/>Playback of progressive audio MP3. | **Dynamic:** dynamic_progressiveAudio.html<br/>**Static:** videotag_progressiveAudio.html  |
| DD+<br/>Playback of content with DD+ audio. | **Dynamic:** dynamic_dolbyDigitalPlus.html<br/>**Static:** N/A  |
| **Options**                                     | |
| Heuristic Profile<br/>Change the heuristics profile | **Dynamic:** dynamic_heuristicsProfile.html<br/>**Static:** videotag_heuristicsProfile.html |
| Localization<br/>Set localization           | **Dynamic:** dynamic_localization.html<br/>**Static:** videotag_localization.html  |
| Audio Tracks Menu<br/>Options to show how to display audio tracks<br/> menu on the default skin. | **Dynamic:** dynamic_multiAudio.html<br/>**Static:** videotag_multiAudio.html |
| Hotkeys<br/>This sample shows how to configure which<br/> hotkeys are enabled in the player | **Dynamic:** dynamic_hotKeys.html<br/>**Static:** videotag_hotKeys.html  |
| **Events, Logging and Diagnostics**             | |
| Register Events<br/>Playback with event listeners. | **Dynamic:** dynamic_registerEvents.html<br/>**Static:** videotag_registerEvents.html |
| Logging<br/>Turn on verbose logging to the console. | **Dynamic:** dynamic_logging.html<br/>**Static:** videotag_logging.html |
| Diagnostics<br/>Get diagnostic data.<br/> *This sample only works on some techs.* | **Dynamic:** dynamic_diagnostics.htnml<br/>**Static:** N/A |
| **AES** |  |
| AES no token<br/>Playback of AES content with no token. | **Dynamic:** dynamic_aes_notoken.html<br/>**Static:** videotag_aes_notoken.html |
| AES token<br/>Playback of AES content with token. | **Dynamic:** dynamic_aes_token.html<br/>**Static:** videotag_aes_token.html |
| AES HLS proxy simulation<br/>Playback of AES content with token, showing<br/> a proxy for HLS so that token<br/> can be used with iOS devices. | **Dynamic:** dynamic_aes_token_withHLSProxy.html<br/>**Static:** videotag_aes_token_withHLSProxy.html |
| AES token force flash<br/>Playback of AES content with token, forcing the flashSS tech. | **Dynamic:** dynamic_aes_token_forceFlash.html<br/>**Static:** videotag_aes_token_forceFlash.html |
| **DRM** |  |
| DRM<br/>Multi-DRM with PlayReady, Widevine, and<br/>FairPlay | **Dynamic:** dynamic_multiDRM_PlayReadyWidevineFairPlay_notoken.html<br/>**Static:** videotag_multiDRM_PlayReadyWidevineFairPlay_notoken.html  |
| PlayReady no token<br/>Playback of PlayReady content with no token. | **Dynamic:** dynamic_playready_notoken.html<br/>**Static:** videotag_playready_notoken.html  |
| PlayReady no token force Silverlight<br/>Playback of PlayReady content with no token, forcing silverlightSS tech. | **Dynamic:** dynamic_playready_notoken_forceSilverlight.html<br/>**Static:** videotag_playready_notoken_forceSilverlight.html |
| PlayReady token<br/>Playback of PlayReady content with token. | **Dynamic:** dynamic_playready_token.html<br/>**Static:** videotag_playready_token.html |
| PlayReady token force Silverlight<br/>Playback of PlayReady content with token,<br/> forcing silverlightSS tech. | **Dynamic:** dynamic_playready_token_forceSilverlight.html<br/>**Static:** videotag_playready_token_forceSilverlight.html  |
| **Protocol and Tech** |  |
| Change techOrder<br/>Change the tech order | **Dynamic:** dynamic_techOrder.html<br/>**Static:** videotag_techOrder.html |
| Force MPEG-DASH only in UrlRewriter<br/>Playback of unprotected content only using<br/> the DASH protocol. | **Dynamic:** dynamic_forceDash.html<br/>**Static:** videotag_forceDash.html  |
| Exclude MPEG-DASH in UrlRewriter<br/>Playback of unprotected content only using<br/> the Smooth and HLS protocols. | **Dynamic:** dynamic_forceNoDash.html<br/>**Static:** videotag_forceNoDash.html |
| Multiple delivery policy<br/>Setting the source with content that has<br/>multiple delivery policies from Azure Media Services | **Dynamic:** dynamic_multipleDeliveryPolicy.html<br/>**Static:** videotag_multipleDeliveryPolicy.html  |
| **Programatically Select** | |
| Select Text Track<br/>Select a WebVTT track from the from the track list. | **Dynamic:** dynamic_selectTextTrack.html<br/>**Static:** N/A |
| Select Bitrate<br/>Selecting a bitrate from the list of bitrates.<br/> *This sample only works on some techs.* | **Dynamic:** dynamic_selectBitrate.html<br/>**Static:** N/A |
| Select Audio Stream<br/>Selecting an audio stream from the list of available audio streams. *This sample only works on some techs.* | **Dynamic:**dynamic_selectAudioStream.html <br/>**Static:** N/A |

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
