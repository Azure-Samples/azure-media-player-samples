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
|------|-------------|-------------|---------|--------|
| **Basic** | Set Source | Playback unprotected content | azure-media-player-samples-dynamic_setsource.html | azure-media-player-samples-videotag_setsource.html |
| **Features** | VOD Ad insertion (VAST) | Insert pre- mid- and post- roll VAST ads into a VOD asset | azure-media-player-samples-dynamic_vast_ads_vod.html | N/A |
| | Playback Speed | Enables viewers to control what speed at which they're watching their video | azure-media-player-samples-dynamic_playback_speed.html | N/A |
| | AMP Flush Skin | Enables new AMP skin **Please note: AMP flush is only supported in AMP versions 2.1.0+** | azure-media-player-samples-dynamic_flush_skin.html | azure-media-player-samples-videotag_flush_skin.html |
| | Captions and Subtitles| Playback with WebVTT subtitles | azure-media-player-samples-dynamic_webvtt.html | azure-media-player-samples-videotag_webvtt.html |
| | Live CEA 708 Captions | Playback with live CEA 708 inbound captions | azure-media-player-samples-dynamic_live_captions.html| N/A |
| | Streaming with Progressive Fallback |  Basic setup of adaptive playback with fallback for progressive if streaming not supported on platform | azure-media-player-samples-dynamic_progressiveFallback.html | azure-media-player-samples-videotag_progressiveFallback.html |
| | Progressive Video MP4 | Playback of progressive audio MP4 | azure-media-player-samples-dynamic_progressiveVideo.html | azure-media-player-samples-videotag_progressiveVideo.html |
| | Progressive Audio MP3 | Playback of progressive audio MP3 | azure-media-player-samples-dynamic_progressiveAudio.html | azure-media-player-samples-videotag_progressiveAudio.html |
| | DD+ | Playback of content with DD+ audio | azure-media-player-samples-dynamic_dolbyDigitalPlus.html | N/A |
| **Options** | Heuristic Profile | Changing the heuristics profile | azure-media-player-samples-dynamic_heuristicsProfile.html | azure-media-player-samples-videotag_heuristicsProfile.html |
| | Localization | Setting localization | azure-media-player-samples-dynamic_localization.html | azure-media-player-samples-videotag_localization.html |
| | Audio Tracks Menu | Options to show how to display audio tracks menu on the default skin | azure-media-player-samples-dynamic_multiAudio.html | azure-media-player-samples-videotag_multiAudio.html|
| | Hotkeys | This sample shows how to configure which hotkeys are enabled in the player | azure-media-player-samples-dynamic_hotKeys.html | azure-media-player-samples-videotag_hotKeys.html |
| **Events, Logging and Diagnostics** | Register Events | Playback with event listeners | azure-media-player-samples-dynamic_registerEvents.html | N/A |
| | Logging | Turning on verbose logging to console | azure-media-player-samples-dynamic_logging.html | azure-media-player-samples-videotag_logging.html |
| | Diagnostics | Getting diagnostic data *This sample only works on some techs* | azure-media-player-samples-dynamic_diagnostics.html | N/A |
| **AES** | AES no token | Playback of AES content with no token | azure-media-player-samples-dynamic_aes_notoken.html | azure-media-player-samples-videotag_aes_notoken.html |
| | AES token | Playback of AES content with token | azure-media-player-samples-dynamic_aes_token.html | azure-media-player-samples-videotag_aes_token.html |
| | AES HLS proxy simulation | Playback of AES content with token, showing a proxy for HLS so that token can be used with iOS devices | azure-media-player-samples-dynamic_aes_token_withHLSProxy.html | azure-media-player-samples-videotag_aes_token_withHLSProxy.html |
| | AES token force flash | Playback of AES content with token, forcing the flashSS tech | azure-media-player-samples-dynamic_aes_token_forceFlash.html | azure-media-player-samples-videotag_aes_token_forceFlash.html |
| **DRM** | Multi-DRM with PlayReady, Widevine, and FairPlay | Playback of DRM content with no token, with PlayReady, Widevine, and FairPlay headers | azure-media-player-samples-dynamic_multiDRM_PlayReadyWidevineFairPlay_notoken.html | videotag_multiDRM_PlayReadyWidevineFairPlay_notoken.html |
| | PlayReady no token | Playback of PlayReady content with no token | azure-media-player-samples-dynamic_playready_notoken.html | Static: videotag_playready_notoken.html |
 | | PlayReady no token force Silverlight | Playback of PlayReady content with no token, forcing silverlightSS tech | azure-media-player-samples-dynamic_playready_notoken_forceSilverlight.html | videotag_playready_notoken_forceSilverlight.html |
| | PlayReady token | Playback of PlayReady content with token | azure-media-player-samples-dynamic_playready_token.html | videotag_playready_token.html |
| | PlayReady token force Silverlight | Playback of PlayReady content with token, forcing silverlightSS tech | azure-media-player-samples-dynamic_playready_token_forceSilverlight.html | videotag_playready_token_forceSilverlight.html |
| **Protocol and Tech** | Change techOrder | Changing the tech order | azure-media-player-samples-dynamic_techOrder.html | videotag_techOrder.html |
| | Force MPEG-DASH only in UrlRewriter | Playback of unprotected content only using the DASH protocol | azure-media-player-samples-dynamic_forceDash.html | videotag_forceDash.html |
| | Exclude MPEG-DASH in UrlRewriter | Playback of unprotected content only using the Smooth and HLS protocols | azure-media-player-samples-dynamic_forceNoDash.html | videotag_forceNoDash.html |
| | Multiple delivery policy | Setting the source with content that has multiple delivery policies from Azure Media Services | azure-media-player-samples-dynamic_multipleDeliveryPolicy.html | videotag_multipleDeliveryPolicy.html |
| **Programatically Select** | Select text track | Selecting a WebVTT track from the from the track list | azure-media-player-samples-dynamic_selectTextTrack.html | N/A |
| | Select bitrate | Selecting a bitrate from the list of bitrates *This sample only works on some techs* | azure-media-player-samples-dynamic_selectBitrate.html | N/A |
| | Select audio stream | Selecting a Audio Stream from the list of available audio streams *This sample only works on some techs.* | azure-media-player-samples-dynamic_selectAudioStream.html | N/A |

## HTML Table

<table class="table table-bordered table-hover table-condensed">
<tbody>
<tr>
<th>
Sample Name
</th>
<th>
Programatic via JavaScript
</th>
<th>
Static via HTML5 <code>video</code>
</th>
<th>
Description
</th>
</tr>
<tr>
<th style="font:bold;text-align:left" colspan="4">
Basic
</th>
</tr>
<tr>
<td>
Set Source
</td>
<td>
<a href="../samples/dynamic_setsource.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_setsource.html">Static</a>
</td>
<td>
Playback unprotected content.
</td>
</tr>
<tr>
<th style="font:bold;text-align:left" colspan="4">
Features
</th>
</tr>
<tr>
<td>
VOD Ad insertion - VAST
</td>
<td>
<a id="vodadsample" href="../samples/dynamic_vast_ads_vod.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Insert pre- mid- and post- roll VAST ads into a VOD asset.
</td>
</tr>
<tr>
<td>
Playback Speed
</td>
<td>
<a href="../samples/dynamic_playback_speed.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Enables viewers to control what speed they're watching their video at.
</td>
</tr>
<tr>
<td>
AMP Flush Skin
</td>
<td>
<a href="../samples/dynamic_flush_skin.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_flush_skin.html">Static</a>
</td>
<td>
Enables new AMP skin. <strong>Please note: AMP flush is only supported in AMP versions 2.1.0+</strong>
</td>
</tr>
<tr>
<td>
Captions and Subtitles
</td>
<td>
<a href="../samples/dynamic_webvtt.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_webvtt.html">Static</a>
</td>
<td>
Playback with WebVTT subtitles.
</td>
</tr>
<tr>
<td>
Live CEA 708 Captions
</td>
<td>
<a href="../samples/dynamic_live_captions.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Playback with live CEA 708 inbound captions with the captions left-aligned.
</td>
</tr>
<tr>
<td>
Streaming with Progressive Fallback
</td>
<td>
<a href="../samples/dynamic_progressiveFallback.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_progressiveFallback.html">Static</a>
</td>
<td>
Basic setup of adaptive playback with fallback for progressive if streaming not supported on platform.
</td>
</tr>
<tr>
<td>
Progressive Video MP4
</td>
<td>
<a href="../samples/dynamic_progressiveVideo.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_progressiveVideo.html">Static</a>
</td>
<td>
Playback of progressive audio MP4.
</td>
</tr>
<tr>
<td>
Progressive Audio MP3
</td>
<td>
<a href="../samples/dynamic_progressiveAudio.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_progressiveAudio.html">Static</a>
</td>
<td>
Playback of progressive audio MP3.
</td>
</tr>
<tr>
<td>
DD+
</td>
<td>
<a href="../samples/dynamic_dolbyDigitalPlus.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Playback of content with DD+ audio.
</td>
</tr>
<tr>
<th style="font:bold;text-align:left" colspan="4">
Options
</th>
</tr>
<tr>
<td>
Heuristic Profile
</td>
<td>
<a href="../samples/dynamic_heuristicsProfile.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_heuristicsProfile.html">Static</a>
</td>
<td>
Changing the heuristics profile
</td>
</tr>
<tr>
<td>
Localization
</td>
<td>
<a href="../samples/dynamic_localization.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_localization.html">Static</a>
</td>
<td>
Setting localization
</td>
</tr>
<tr>
<td>
Audio Tracks Menu
</td>
<td>
<a href="../samples/dynamic_multiAudio.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_multiAudio.html">Static</a>
</td>
<td>
Options to show how to display audio tracks menu on the default skin.
</td>
</tr>
<tr>
<td>
Hotkeys
</td>
<td>
<a href="../samples/dynamic_hotKeys.html">Dynamic </a>
</td>
<td>
<a href="../samples/videotag_hotKeys.html">Static</a>
</td>
<td>
This sample shows how to configure which hotkeys are enabled in the player
</td>
</tr>
<tr>
<th style="font:bold;text-align:left" colspan="4">
Events, Logging and Diagnostics
</th>
</tr>
<tr>
<td>
Register Events
</td>
<td>
<a href="../samples/dynamic_registerEvents.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Playback with event listeners.
</td>
</tr>
<tr>
<td>
Logging
</td>
<td>
<a href="../samples/dynamic_logging.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_logging.html">Static</a>
</td>
<td>
Turning on verbose logging to console.
</td>
</tr>
<tr>
<td>
Diagnostics
</td>
<td>
<a href="../samples/dynamic_diagnostics.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Getting diagnostic data. This sample only works on some techs.
</td>
</tr>
<tr>
<th style="font:bold;text-align:left" colspan="4">
AES
</th>
</tr>
<tr>
<td>
AES no token
</td>
<td>
<a href="../samples/dynamic_aes_notoken.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_aes_notoken.html">Static</a>
</td>
<td>
Playback of AES content with no token.
</td>
</tr>
<tr>
<td>
AES token
</td>
<td>
<a href="../samples/dynamic_aes_token.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_aes_token.html">Static</a>
</td>
<td>
Playback of AES content with token.
</td>
</tr>
<tr>
<td>
AES HLS proxy simulation
</td>
<td>
<a href="../samples/dynamic_aes_token_withHLSProxy.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_aes_token_withHLSProxy.html">Static</a>
</td>
<td>
Playback of AES content with token, showing a proxy for HLS so that token can be used with iOS devices.
</td>
</tr>
<tr>
<td>
AES token force flash
</td>
<td>
<a href="../samples/dynamic_aes_token_forceFlash.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_aes_token_forceFlash.html">Static</a>
</td>
<td>
Playback of AES content with token, forcing the flashSS tech.
</td>
</tr>
<tr>
<th style="font:bold;text-align:left" colspan="4">
DRM
</th>
</tr>
<tr>
<td>
Multi-DRM with PlayReady, Widevine, and FairPlay
</td>
<td>
<a href="../samples/dynamic_multiDRM_PlayReadyWidevineFairPlay_notoken.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_multiDRM_PlayReadyWidevineFairPlay_notoken.html">Static</a>
</td>
<td>
Playback of DRM content with no token, with PlayReady, Widevine, and FairPlay headers.
</td>
</tr>
<tr>
<td>
PlayReady no token
</td>
<td>
<a href="../samples/dynamic_playready_notoken.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_playready_notoken.html">Static</a>
</td>
<td>
Playback of PlayReady content with no token.
</td>
</tr>
<tr>
<td>
PlayReady no token force Silverlight
</td>
<td>
<a href="../samples/dynamic_playready_notoken_forceSilverlight.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_playready_notoken_forceSilverlight.html">Static</a>
</td>
<td>
Playback of PlayReady content with no token, forcing silverlightSS tech.
</td>
</tr>
<tr>
<td>
PlayReady token
</td>
<td>
<a href="../samples/dynamic_playready_token.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_playready_token.html">Static</a>
</td>
<td>
Playback of PlayReady content with token.
</td>
</tr>
<tr>
<td>
PlayReady token force Silverlight
</td>
<td>
<a href="../samples/dynamic_playready_token_forceSilverlight.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_playready_token_forceSilverlight.html">Static</a>
</td>
<td>
Playback of PlayReady content with token, forcing silverlightSS tech.
</td>
</tr>
<tr>
<th style="font:bold;text-align:left" colspan="4">
Protocol and Tech
</th>
</tr>
<tr>
<td>
Change techOrder
</td>
<td>
<a href="../samples/dynamic_techOrder.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_techOrder.html">Static</a>
</td>
<td>
Changing the tech order
</td>
</tr>
<tr>
<td>
Force MPEG-DASH only in UrlRewriter
</td>
<td>
<a href="../samples/dynamic_forceDash.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_forceDash.html">Static</a>
</td>
<td>
Playback of unprotected content only using the DASH protocol.
</td>
</tr>
<tr>
<td>
Exclude MPEG-DASH in UrlRewriter
</td>
<td>
<a href="../samples/dynamic_forceNoDash.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_forceNoDash.html">Static</a>
</td>
<td>
Playback of unprotected content only using the Smooth and HLS protocols.
</td>
</tr>
<tr>
<td>
Multiple delivery policy
</td>
<td>
<a href="../samples/dynamic_multipleDeliveryPolicy.html">Dynamic</a>
</td>
<td>
<a href="../samples/videotag_multipleDeliveryPolicy.html">Static</a>
</td>
<td>
Setting the source with content that has multiple delivery policies from Azure Media Services
</td>
</tr>
<tr>
<th style="font:bold;text-align:left" colspan="4">
Programatically Select
</th>
</tr>
<tr>
<td>
Select text track
</td>
<td>
<a href="../samples/dynamic_selectTextTrack.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Selecting a WebVTT track from the from the track list.
</td>
</tr>
<tr>
<td>
Select bitrate
</td>
<td>
<a href="../samples/dynamic_selectBitrate.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Selecting a bitrate from the list of bitrates. This sample only works on some techs.
</td>
</tr>
<tr>
<td>
Select audio stream
</td>
<td>
<a href="../samples/dynamic_selectAudioStream.html">Dynamic</a>
</td>
<td>
N/A
</td>
<td>
Selecting a Audio Stream from the list of available audio streams. This sample only works on some techs.
</td>
</tr>
</tbody>
</table>

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
