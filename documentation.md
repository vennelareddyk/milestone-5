
PROJECT AIM:
This project will walk you through the development of a complete transfer learning pipeline from annotation to producing performance
results of a network that performs semantic segmentation in the so called small data regime i.e. when the annotated examples 
per category are very few.

5.1. Milestone 1: Environment Preparation :
   In this stage you will be working with CVAT - you need to install CVAT locally to your laptop/desktop and we urge you to 
   follow the docker setup instructions here

 5.2. Milestone 2: Data Acquisition :
      Select 10 product categories 
     
 ou will need to scrape using beautiful soup or retrieve using the Google Custom Search API (better solution), 
 100 images of each of the selected product categories. Make sure you select products that are not included on 
 the video, meaning if a specific sink is shown on the video, you srape / search different but similar sinks.
 
 5.3. Milestone 3: Annotation (20 points)
Upload the images in your CVAT instance and annotate all object categories. This is a manual step and you will 
need to use the DEXTR cutter.

5.4. Milestone 4: Semantic Segmentation 
