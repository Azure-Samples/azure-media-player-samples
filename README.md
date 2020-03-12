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

| Type | Sample Name | Programmatic via JavaScript | Static via HTML5 | Description |
|-------------|-------------|-------------|-------------|
| Basic | Set Source | Dynamic: azure-media-player-samples-dynamic_setsource.html | Static: azure-media-player-samples-videotag_setsource.html) | Playback unprotected content. |
| Features | VOD Ad insertion (VAST) | Dynamic: azure-media-player-samples-dynamic_vast_ads_vod.html) | N/A | Insert pre- mid- and post- roll VAST ads into a VOD asset. |
| | Playback Speed | Dynamic: azure-media-player-samples-dynamic_playback_speed.html | N/A |  Enables viewers to control what speed at which they're watching their video. |

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