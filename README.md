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

You can use Azure Media Player to stream videos from Azure Media Services. The samples in this set include basic to advanced configurations (listed below.)

![azure media player screen capture](media/azure-media-player.gif)

You can view the Azure Media Player [demo](https://ampdemo.azureedge.net/azuremediaplayer.html) here.

## Sample Listing

| Type | Sample Name | Description | Dynamic | Static |
|-------------|-------------|-------------|-------------|-------------|
| Basic | Set Source | Playback unprotected content. | azure-media-player-samples-dynamic_setsource.html | azure-media-player-samples-videotag_setsource.html |
| Features | VOD Ad insertion (VAST) | Insert pre- mid- and post- roll VAST ads into a VOD asset. | azure-media-player-samples-dynamic_vast_ads_vod.html | N/A |
| | Playback Speed | Enables viewers to control what speed at which they're watching their video. | azure-media-player-samples-dynamic_playback_speed.html | N/A |
| | AMP Flush Skin | Enables new AMP skin. **Please note: AMP flush is only supported in AMP versions 2.1.0+** | azure-media-player-samples-dynamic_flush_skin.html| azure-media-player-samples-videotag_flush_skin.html | 
| | Captions and Subtitles|  Playback with WebVTT subtitles.| azure-media-player-samples-dynamic_webvtt.html | azure-media-player-samples-videotag_webvtt.html |
| | Live CEA 708 Captions | Playback with live CEA 708 inbound captions.| azure-media-player-samples-dynamic_live_captions.html| N/A |
| | Streaming with Progressive Fallback |  Basic setup of adaptive playback with fallback for progressive if streaming not supported on platform. | azure-media-player-samples-dynamic_progressiveFallback.html | azure-media-player-samples-videotag_progressiveFallback.html |
| | Progressive Video MP4 | Playback of progressive audio MP4. | azure-media-player-samples-dynamic_progressiveVideo.html | azure-media-player-samples-videotag_progressiveVideo.html |
| | Progressive Audio MP3 | Playback of progressive audio MP3. | azure-media-player-samples-dynamic_progressiveAudio.html | azure-media-player-samples-videotag_progressiveAudio.html |
| | DD+ | Playback of content with DD+ audio. | azure-media-player-samples-dynamic_dolbyDigitalPlus.html | N/A |

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