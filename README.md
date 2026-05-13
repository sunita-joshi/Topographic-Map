# Topographic Map Preparation using ZY-3 Satellite Imagery and Freely Available DEM

## Introduction

This repository documents my bachelor thesis project on the preparation of a topographic map at a scale of 1:25,000 using ZY-3 satellite imagery and freely available DEM data.

The project focused on assessing the feasibility of using high-resolution satellite mono imagery for topographic mapping in Panauti Municipality, Nepal. The workflow included DEM assessment, satellite image processing, orthorectification, pansharpening, manual feature digitization, contour extraction, map preparation, and accuracy validation.

## Project Overview

The study used ZY-3 satellite imagery together with freely available DEM data to prepare a topographic map of Panauti Municipality. Since stereo imagery was not available, ALOS PALSAR DEM was used for elevation information after comparing its accuracy with SRTM DEM.

The final map included major topographic features such as roads, rivers, land-cover classes, settlements, contours, and other cartographic elements.

## Study Area

The study area was Panauti Municipality, Nepal.

![Study Area](Study%20Area.jpg)

## Methodology

The general workflow included image preprocessing, DEM accuracy assessment, orthorectification using RPC and GCP data, pansharpening of multispectral and panchromatic images, manual digitization of topographic features, contour extraction, map preparation, and final accuracy validation.

![Methodological Workflow](Methodological%20Workflow.png)

## Selected Results

### DEM Assessment

ALOS PALSAR DEM and SRTM DEM were compared to select a suitable elevation dataset for the mapping workflow.

![DEM Assessment](DEM%20Assessment.png)

### Positional Accuracy

The prepared map was validated using GCPs collected through DGPS survey.

![Positional Accuracy](Positional%20Accuracy.png)

### Accuracy of Map

![Accuracy of Map](Accuracy%20of%20Map%20.png)

### Final Topographic Map

![Topographic Map](Topographic%20Map.jpg)

## Tools Used

- ERDAS IMAGINE
- ArcGIS
- ZY-3 satellite imagery
- ALOS PALSAR DEM
- SRTM DEM
- DGPS/GCP data
- Orthorectification
- Pansharpening
- Manual digitization
- Accuracy assessment

## Notes

This was a bachelor thesis group project completed as part of the Geomatics Engineering program. This repository provides a concise summary of the workflow, selected outputs, and mapping methodology.

## Keywords

Topographic Mapping, ZY-3 Satellite Imagery, DEM, ALOS PALSAR, SRTM, Orthorectification, Pansharpening, GCP, DGPS, ArcGIS, ERDAS IMAGINE, Remote Sensing, GIS, Photogrammetry
