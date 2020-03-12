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

<table width="100%">
<tr>
<td colspan="4"><b>Basic</b></td></tr>
<tr>
<td colspan="4">Set Source<br/>
Playback unprotected content</td>
</tr>
<tr>
<td>Dynamic<td></td>
<td>dynamic_setsource.html</td>
<td>Static</td>
<td>videotag_setsource.html</td>
</tr>
<tr>
<td colspan="4"><b>Features</b></td>
</tr>
<tr>
<td colspan="4">VOD Ad insertion (VAST)<br/>
Insert pre- mid- and post- roll VAST ads into a VOD asset
</td>
</tr>
<tr>
<td>Dynamic</td>
<td>dynamic_vast_ads_vod.html</td>
<td>Static</td>
<td>N/A</td>
</tr>
<tr>
<td colspan="4">Playback Speed<br/>
Enables viewers to control what speed at which they're watching their video</td>
</tr>
<tr>
<td>Dynamic</td>
<td>dynamic_playback_speed.html</td>
<td>Static</td>
<td>N/A</td>
</tr>
<tr>
<td colspan="4">AMP Flush Skin<br/>
Enables new AMP skin **Please note: AMP flush is only supported in AMP versions 2.1.0+**</td>
</tr>
<tr>
<td>Dynamic</td>
<td>dynamic_flush_skin.html</td>
<td>Static</td>
<td>videotag_flush_skin.html</td>
</tr>
<tr>
<td colspan="4">Captions and Subtitles<br/>
Playback with WebVTT subtitles</td>
</tr>
<tr>
<td>Dynamic</td>
<td>dynamic_webvtt.html</td>
<td>Static</td>
<td>videotag_webvtt.html</td>
</tr>
<tr>
<td colspan="4">Live CEA 708 Captions<br/>
Playback with live CEA 708 inbound captions</td>
</tr>
<tr>
<td>Dynamic</td>
<td>dynamic_live_captions.html</td>
<td>Static</td>
<td>N/A</td>
</tr>
<tr>
<td colspan="4">Streaming with Progressive Fallback<br/>
Basic setup of adaptive playback with fallback for progressive if streaming not supported on platform</td>
</tr>
<tr>
<td>Dynamic</td>
<td>dynamic_progressiveFallback.html</td>
<td>Static</td>
<td>videotag_progressiveFallback.html</td>
</tr>

</table>
</div>

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
