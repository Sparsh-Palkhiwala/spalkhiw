---
title: "NavAssist : The project that got me into Deep Learning"
date: 2024-08-17T09:47:45+02:00
---
# Little Bit about NavAssist
The YOLOv5 model has been meticulously fine-tuned and trained on a custom dataset comprising over 16,000 images, designed to capture Indian surroundings. This finetuned model achieves up to 70% precision in car detection and an overall precision of 65.4% for detecting all vehicles, all while maintaining real-time processing capabilities at 25 frames per second. 

In addition, the model has undergone pruning to enhance resource efficiency, allowing it to run on lightweight devices such as the Jetson Nano. Furthermore, we have integrated a Safety Detection Algorithm into the model, enabling it to classify road safety conditions into three distinct categories: safe to cross, requires caution, and not safe to cross. This integration ensures that the model not only detects vehicles but also provides real-time safety assessments, making it a solution for traffic and pedestrian safety management.