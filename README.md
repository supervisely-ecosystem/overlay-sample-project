<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250" /> <br>

# Overlay Sample Project

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#download">Download</a>
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervisely.com/slack)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/multiview-video-sample-annotated)
[![views](https://app.supervisely.com/img/badges/views/supervisely-ecosystem/multiview-video-sample-annotated.png)](https://supervisely.com)
[![downloads](https://app.supervisely.com/img/badges/downloads/supervisely-ecosystem/multiview-video-sample-annotated.png)](https://supervisely.com)

</div>

## Overview

This is a multiview video project sample consisting of four synchronized videos, each representing a different camera view (synchronization achieved using time offset), annotated with polygon shapes for object tracking.

### Annotation Details

The annotation was performed by manually creating first frames for each video and then using AutoTrack to propagate the annotations across the frames. The annotation process was done in a way to ensure that the same objects across different views have the same object IDs, allowing for easy tracking and analysis of objects across multiple camera angles. The [CoTracker](https://ecosystem.supervisely.com/apps/co-tracker/supervisely_integration/serve) model was connected to the [AutoTrack](https://docs.supervisely.com/labeling/labeling-toolbox/videos-3.0#auto-tracking) tool to track point-based geometry (polygon) objects across the frames, with manual adjustments when needed.

### Classes and Tags

The project includes 2 object classes: `box` for annotating boxes and `chalk` for annotating chalk objects. Additionally, there is 1 object tag `color` - a tag for additional color-based object properties.
<img src="https://github.com/supervisely-ecosystem/multiview-video-sample-annotated/releases/download/v1.0.0/screenshot-dev-internal-supervisely-com-app-videos_v3-1768485576526.png" />

## Download

Multiview project sample in Supervisely format (88.6 MB): [Download ZIP archive](https://github.com/supervisely-ecosystem/multiview-video-sample-annotated/releases/download/v1.0.1/project.zip)
