# Image Segmentation — ComfyUI Assessment

## Project Overview

This project demonstrates image segmentation and mask generation using ComfyUI. It includes multiple input images and their corresponding generated alpha masks or segmentation masks.

## Repository Structure

- `Image_Segmentation.json` — ComfyUI segmentation workflow.
- `Images/` — input images used for segmentation.
- `Masks/` — generated alpha masks and segmentation masks.

## Input Images

The assessment includes the following examples:

- Bottle
- Dog
- People
- Plant
- Pothole
- Road

## Workflow

1. Load the input image into the ComfyUI workflow.
2. Process the image using the configured segmentation nodes and models.
3. Generate the corresponding mask.
4. Save the mask output in the `Masks/` folder.

## Usage

1. Install ComfyUI and the required custom nodes.
2. Download or configure the models required by the workflow.
3. Load `Image_Segmentation.json` into ComfyUI.
4. Provide an input image from the `Images/` folder.
5. Execute the workflow and review the generated mask.

## Contents

This repository contains the workflow JSON, input images, and generated masks for the image segmentation assessment.

