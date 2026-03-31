<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250" /> <br>

# DAPI Microscope Images Overlay Interface

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#what-is-dapi-data">What is DAPI data?</a> •
  <a href="#how-this-interface-helps-users">How this interface helps users</a> •
  <a href="#download">Download</a>
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervisely.com/slack)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/overlay-sample-project)
[![views](https://app.supervisely.com/img/badges/views/supervisely-ecosystem/overlay-sample-project.png)](https://supervisely.com)
[![downloads](https://app.supervisely.com/img/badges/downloads/supervisely-ecosystem/overlay-sample-project.png)](https://supervisely.com)

</div>

## Overview

This is a DAPI microscope images overlay interface project sample consisting of base images and linked overlay layers with adjustable opacity. The project allows users to view and adjust the opacity of overlay layers on top of base images, which is particularly useful for analyzing microscope images.

## What is DAPI data?

DAPI (4′,6-diamidino-2-phenylindole) is a fluorescent stain that binds strongly to DNA and is commonly used in microscopy to highlight cell nuclei. In practice, DAPI data usually appears as grayscale or blue-channel images where nuclei are bright and easy to localize.

This makes DAPI an important reference layer for:

- detecting and counting nuclei,
- checking cell distribution and density,
- aligning and comparing other microscopy channels.

## How this interface helps users

This interface helps users work with DAPI data faster and more clearly by providing:

- linked base image + overlay layers for direct visual comparison,
- adjustable overlay opacity to inspect weak or partially overlapping structures,
- a simple, focused workspace for quality control and interpretation of microscopy results.

## Download

This project sample in Supervisely format (88.6 MB): [Download ZIP archive](https://github.com/supervisely-ecosystem/multiview-video-sample-annotated/releases/download/v1.0.1/project.zip)
