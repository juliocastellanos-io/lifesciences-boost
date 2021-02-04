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
  - type: features-section
    title: MRI sequences
    features:
      - title: 
        content: >-
          1. **FLAIR:** Fluid-attenuated inversion recovery is an MRI sequence with an inversion recovery set to null fluids.
   

          2. **T1-w:** T1 weighted image is a basic pulse MRI sequence that depicts differences in signal based upon intrinsic T1 relaxation time of various tissues.


          3. **T2-w:** T2 weighted image is a basic pulse MRI sequence that depicts differences in signal based upon intrinsic T1 relaxation time of various tissues.


          4. **PD:** Proton Density weighted image is a MRI sequence where the tissues with the higher concentration or density of protons (hydrogen atoms) produce the strongest signals and appear the brightest on the image.

        align: left
        image: images/msc_sequences_resized2.png   
        image_position: right 
      # - title: 3D render visualization
      #   content: >-
      #     Get a 3D visualization of the detected tumor
      #   align: left
      #   image: images/ai-l-3.png
      #   image_position: left
      # - title: DICOM Tools and Metrics
      #   content: >-
      #     Visual tools for browsing and manipulating DICOM series, get metrics and export images.
      #   align: left
      #   image: images/ai-l-f-1.png
      #   image_position: right
  # - type: cta_section
  #   title:  AI Lung Tumor Detection 
  #   subtitle: >-
  #     Make sure you are connected to Globant's VPN  
  #   actions:
  #     - label: Live Demo
  #       url: 'http://on-demad-ai-life-sciences-v2.s3-website-us-east-1.amazonaws.com/'
  #       style: primary
  #   has_background: true
  #   background_color: gray
template: post 

# Compare follow-up MRI studies
---
# AI Model

## Pipeline

Easy multiple sclerosis white matter lesion segmentation using convolutional deep neural networks.

- For each subject, use FLAIR and T1-w images to infer segmentation
- You will obtain a mask with the segmentation
![Demo](/images/FLAIR_segmentation_resized.png)
- It can be overlayed on the MRI study with a medical image viewer
- Here it is done over the FLAIR sequence, since it can be used in brain imaging to suppress cerebrospinal fluid (CSF) effects on the image, so as to bring out the periventricular hyperintense lesions, such as multiple sclerosis (MS) plaques.


## Follow-up

By means of this AI model Multiple sclerosis lesion segmentatation can be performed on consecutive MRI studies
This allows for the monitoring the evolution of the disease

<video autoplay loop playsinline>
  <source src="/images/nicMSlesions_flair_follow-up.mp4" type="video/mp4">
</video>
<!-- ![Demo](/images/nicMSlesions_flair_follow-up.mp4) -->

<!-- - A loading page will be presented

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

 -->
