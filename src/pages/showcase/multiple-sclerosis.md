---
title: Multiple Sclerosis Lesion Segmentation 
date: '2021-02-03'
image: images/msc_image.PNG
categories:
  - data/categories/demo.yaml
excerpt: 'Multiple sclerosis lesion segmentation from MRI scans.'
sections:
  - type: hero_section
    title: Multiple Sclerosis Lesion Segmentation AI
    subtitle: >-
      Multiple sclerosis lesion segmentation from MRI scans.
    # actions:  # sacar
    #   - label: Live Demo
    #     url: 'http://on-demad-ai-life-sciences-v2.s3-website-us-east-1.amazonaws.com/'  # change
    #     style: primary
    align: left
    video: images/nicMSlesions_flair_registered.mp4  
    image_position: right
    has_background: true
    background:
      background_color: blue
      background_image: images/diagonal-lines.svg
      background_image_opacity: 20
      background_image_size: auto
      background_image_repeat: repeat
  - type: features_section
    title: Features
    features:
      - title: PACS Integration
        content: >-
         Connect to the a PACS server and get patient's medical imaging information to analyze.
        align: left
        image: images/ai-l-f-2.png   # change
        image_position: right
      - title: 3D render visualization
        content: >-
          Get a 3D visualization of the detected tumor
        align: left
        image: images/ai-l-3.png
        image_position: left
      - title: DICOM Tools and Metrics
        content: >-
          Visual tools for browsing and manipulating DICOM series, get metrics and export images.
        align: left
        image: images/ai-l-f-1.png
        image_position: right
  - type: cta_section
    title:  AI Lung Tumor Detection 
    subtitle: >-
      Make sure you are connected to Globant's VPN
    actions:
      - label: Live Demo
        url: 'http://on-demad-ai-life-sciences-v2.s3-website-us-east-1.amazonaws.com/'
        style: primary
    has_background: true
    background_color: gray
template: post
---
## How to run the demo

## Run the model


- Go to the demo link
- You will see the following page, press the "Open" button
![Demo](/images/ai-l-d-2.png)
- Next, press search and a test patient will show up
- Select the patient and the test study
- Click on "Load"

![Demo](/images/ai-l-d-3.png)

- A loading page will be presented

![Demo](/images/ai-l-d-4.png)

- It will take in optimal nework conditions around 2min (VPN dependent) for a 130MB transfer with the results.
- You will get the following result
![Demo](/images/ai-lu-d-5.png)


## The 3D view

- To work with the 3D focus on the yellow square 

![Demo](/images/ai-l-d-6.png)

- Click on sigle view, anotated in red, this will maximize the view
- You can hide the body layer by cliking on the eye icon anotated in blue.
- It will look like the following image

![Demo](/images/ai-l-d-7.png)

- To capure and export a image click on the screenshots option.
- Then capture active view
- You will get this view

![Demo](/images/ai-l-3.png)

## Metrics result

- On left menu click on "Results"
- Click on the arrow anotated in yellow to show the metrics

![Demo](/images/ai-l-d-8.png)


