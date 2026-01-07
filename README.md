# Satellite Cloud Detection PoC

A proof-of-concept integration of [ColonyOS](https://github.com/colonyos), [Digital Earth Sweden](https://github.com/DigitalEarthSweden), and [ML cloud detection models](https://github.com/aleksispi/ml-cloud-opt-thick) for automated satellite image filtering based on cloudiness.

## Overview

This project uses trained machine learning models to analyze satellite imagery, filter out cloudy images, and download only cloud-free data. The system combines ColonyOS for distributed workflow orchestration.

## Prerequisites

- Docker
- Docker Compose
- ColonyOS

For detailed information about each component, refer to their respective repositories linked above.

## Current Capabilities

- Automated cloud detection in satellite imagery
- Filtering based on cloudiness thresholds
- Download orchestration for cloud-free images

## Possible Future Roadmap

### Large-Scale Data Processing

Expand ColonyOS integration to process large volumes of satellite data for various applications, including machine learning dataset creation.

### Enhanced User Interface

- Interactive map interface for coordinate selection
- Area-based image collection (bounding boxes)
- Configurable time range queries
- Batch download functionality

### Real-Time Sweden Map

Develop a production system that generates daily cloud-free maps of Sweden:

- Distributed processing across multiple executors
- Grid-based map updates using masked approach
- Near real-time continuous updates

### Data Pipeline Infrastructure

Build flexible pipelines for supervised and unsupervised learning:

- Complex workflow orchestration via ColonyOS
- Automated data collection and processing
- Large-scale dataset aggregation

### Event Detection System

Deploy pre-trained models for automated event monitoring:

- Configurable spatial filters (local or global)
- Real-time notifications for detected events
- Continuous monitoring capability

## License
See license.txt in the root of this repo.
