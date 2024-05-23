# RoboFlamingo-Plus
Fusion of Depth and RGB Perception with Vision-Language Models for Enhanced Robotic Manipulation
![image](https://github.com/AIGCer0807/RoboFlamingo-Plus/assets/125721646/ade37b3f-b070-4052-bd56-82e5d7a466c9)
RoboFlamingo-Plus enhances the existing RoboFlamingo framework by integrating depth data into Vision-Language Models (VLMs) to improve robotic manipulation. This upgrade includes a new resampling technique combined with a pre-trained Vision Transformer (ViT), enabling more precise alignment of RGB and depth information with linguistic cues. This advancement allows RoboFlamingo-Plus to perform complex language-guided tasks more effectively in three-dimensional environments. Notably, RoboFlamingo-Plus has demonstrated a 10-20% improvement in task performance over existing methods.

The model weights and code will be made publicly available upon acceptance of the paper to facilitate further research and application.

We do all of our training on 8 A-800s (80G).

# Performance
Task 1-5 reflects the success rates of executing specific tasks. It displays a performance comparison where our 
RoboFlamingo-Plus model outperforms the original, achieving a performance improvement of 10-20%. Success rates were 
evaluated across 200 sequences from the Calvin dataset for each configuration. The label 'Enriched' denotes tests conducted with 
a variety of linguistic inputs to assess the model's robustness to language variations. 
![image](https://github.com/AIGCer0807/RoboFlamingo-Plus/assets/125721646/ff90eac8-7d70-4786-bf89-0f669d5ea052)
