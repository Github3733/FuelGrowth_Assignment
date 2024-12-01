# Influencer Video Performance Analysis

This repository contains a Jupyter notebook that processes influencer video data, detects faces in videos, and evaluates the performance of each video. The project analyzes and visualizes the results, providing insights into top-performing influencers based on their video performance.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)
- [Results](#results)
- [License](#license)

## Overview

This project processes influencer video data to calculate the average performance of videos. It performs the following key steps:

1. **Downloads videos from URLs.**
2. **Computes unique video hashes to eliminate duplicates.**
3. **Analyzes the performance data of each unique video.**
4. **Detects faces in the videos and saves frames with detected faces.**
5. **Visualizes the performance of top influencers and their associated faces.**

The final result is a CSV file containing video URLs, average performance scores, and paths to images of detected faces. A series of plots are also generated to visualize the data.

## Features

- **Video Downloading**: Automatically downloads videos from the provided URLs.
- **Face Detection**: Detects faces in videos and saves images with detected faces.
- **Performance Aggregation**: Aggregates performance data for each unique video, calculating the average performance.
- **Data Visualization**: Plots the top influencers based on average performance and displays their faces.

## Installation

To use this notebook, you'll need to install the following dependencies:

1. **Python 3.x** (Recommended version: 3.7+)
2. **Required Libraries**:
   - `opencv-python`
   - `matplotlib`
   - `pandas`
   - `seaborn`
   - `requests`

You can install the dependencies using `pip`:

```bash
pip install opencv-python matplotlib pandas seaborn requests

