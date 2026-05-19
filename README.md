# SurgFM-SLAM Project Page

Project page for **"SurgFM-SLAM: Robust Surgical Scene Reconstruction via 3D Foundation Adaptation Model"**.

Authors: Xiaoxi Lu*, Gan Liu*, Bingwen Dong*, Guangcheng Chen, Mingdao Gong, Yan Hu, Xiaoqing Zhang&dagger;, Jiang Liu&dagger;
(*Equal contribution, &dagger;Corresponding authors)

Affiliations: Southern University of Science and Technology; Chinese Academy of Sciences, Nanjing; Shenzhen Institutes of Advanced Technology, CAS; University of Nottingham Ningbo China; Changchun University.

## Project Overview

SurgFM-SLAM is an end-to-end framework that couples a 3D foundation model with a SLAM backend for robust surgical scene reconstruction. A frame-similarity sampling strategy and LoRA-based fine-tuning produce a surgical foundation model (SurgFM) that captures illumination-invariant geometric priors of texture-sparse tissues, while the SLAM backend handles tracking, mapping, and relocalization over extended surgical sequences.

## Features

- End-to-end depth, camera pose, and dense 3D reconstruction for surgical video
- Frame-similarity sampling for stable training under viewpoint changes and specular highlights
- Parameter-efficient LoRA adaptation of a 3D foundation model
- Strong intra-domain performance on SimCol and zero-shot generalization to C3VD and SCARED

## Usage

Open `index.html` in a web browser, or visit the deployed GitHub Pages site.

## Code

Code will be released **after acceptance**.

## Acknowledgments

This project page template was adopted from the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) and the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
