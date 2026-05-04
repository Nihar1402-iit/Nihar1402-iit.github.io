---
layout: archive
title: "RESEARCH PROJECTS"
permalink: /research/
author_profile: true
---

<div class="domain-badges scroll-reveal" style="margin-bottom: 2rem;">
  <span class="badge"><i class="fas fa-eye"></i> Computer Vision</span>
  <span class="badge"><i class="fas fa-brain"></i> Machine Learning</span>
  <span class="badge"><i class="fas fa-x-ray"></i> Medical Imaging</span>
</div>

<!-- Precision-Aware Quantization -->
<div class="glass-card scroll-reveal">
  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <h3 style="margin-top: 0; color: #66FCF1;">Precision-Aware Quantization for Depth Estimation Models</h3>
    <span class="badge"><i class="fas fa-file-alt"></i> Manuscript submitted to A/A*</span>
  </div>
  <p style="font-size: 0.9em; color: #45A29E; margin-bottom: 1em;">Prof. Joycee Mekie | IIT Gandhinagar • Aug 2025 – Present</p>
  <ul>
    <li>Performed system-level quantization of depth estimation models (UniDepth-CNN, UniDepth-ViT, MASt3R) across 11 numerical formats including FP, Posit, and FixedPosit.</li>
    <li>Evaluated accuracy–efficiency trade-offs using SILog, AbsRel, and RMSE metrics, analyzing convergence under low-precision training.</li>
    <li>Benchmarked training and inference across five hardware accelerators (Eyeriss, Simba, EnX3D, Gemmini, AiM), demonstrating up to <strong>4×–30× energy savings</strong>.</li>
  </ul>
</div>

<!-- HYDRA-ULM -->
<div class="glass-card scroll-reveal">
  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <h3 style="margin-top: 0; color: #66FCF1;">HYDRA-ULM: Physics-Guided Two-Stage Localization and Tracking</h3>
    <span class="badge"><i class="fas fa-microscope"></i> Manuscript in prep</span>
  </div>
  <p style="font-size: 0.9em; color: #45A29E; margin-bottom: 1em;">Prof. Himanshu Shekhar | IIT Gandhinagar • Jan 2026 – Present</p>
  <ul>
    <li>Developed a hybrid two-stage ULM pipeline combining neural microbubble localization with adaptive temporal tracking for sparse, overlapping, and noisy acquisitions.</li>
    <li>Built a physics-guided simulation engine for synthetic vascular structures and microbubble trajectories to enable scalable supervised training.</li>
    <li>Achieved super-resolution vascular reconstruction at reduced frame rates, preserving vessel continuity while lowering computational cost.</li>
  </ul>
</div>

<!-- GSC Beamforming -->
<div class="glass-card scroll-reveal">
  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <h3 style="margin-top: 0; color: #66FCF1;">Low-Complexity GSC Beamforming via Kronecker Approximation</h3>
    <span class="badge"><i class="fas fa-wave-square"></i> Manuscript in prep</span>
  </div>
  <p style="font-size: 0.9em; color: #45A29E; margin-bottom: 1em;">Prof. Nithin George | IIT Gandhinagar • Jan 2025 – Present</p>
  <ul>
    <li>Devised a Nearest Kronecker Product (NKP)-based adaptive GSC beamformer to reduce computational complexity in large microphone arrays.</li>
    <li>Achieved speedup in LMS/RLS updates by decomposing weight matrices into low-rank Kronecker factors.</li>
    <li>Demonstrated improved interference suppression with reduced execution time at the Undergraduate Research Showcase 2025.</li>
  </ul>
</div>

<!-- Knowledge Distillation -->
<div class="glass-card scroll-reveal">
  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <h3 style="margin-top: 0; color: #66FCF1;">Hybrid Precision Optimization via Knowledge Distillation and RL</h3>
    <span class="badge"><i class="fas fa-brain"></i> Ongoing Work</span>
  </div>
  <p style="font-size: 0.9em; color: #45A29E; margin-bottom: 1em;">Prof. Joycee Mekie | IIT Gandhinagar • Dec 2026 – Present</p>
  <ul>
    <li>Applied knowledge distillation on UniDepth-ViT to transfer performance from high-precision teacher models to low-precision student variants.</li>
    <li>Designed a reinforcement learning-based framework to assign optimal numerical formats to different model components (encoder, decoder, attention blocks).</li>
    <li>Explored mixed-precision configurations (e.g., FP8 encoder, FixedPosit16 decoder), demonstrating improved trade-offs over uniform quantization.</li>
  </ul>
</div>

<!-- OmniStrain-Net -->
<div class="glass-card scroll-reveal">
  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <h3 style="margin-top: 0; color: #66FCF1;">OmniStrain-Net: Physics-Informed Neural Representations for Ultrasound Elastography</h3>
    <span class="badge"><i class="fas fa-pulse"></i> Ongoing Work</span>
  </div>
  <p style="font-size: 0.9em; color: #45A29E; margin-bottom: 1em;">Prof. Himanshu Shekhar | IIT Gandhinagar • Feb 2026 – Present</p>
  <ul>
    <li>Developed OmniStrain-Net, an unsupervised deep learning framework integrating Vision Transformers (ViT) and Implicit Neural Representations (INR) for continuous tissue displacement tracking.</li>
    <li>Implemented a Physics-Informed Neural Network (PINN) loss function to enforce biomechanical constraints and ensure anatomical consistency.</li>
    <li>Currently benchmarking against SOTA models including ReUSENet, MUSSE-Net, and SMURF.</li>
  </ul>
</div>

<!-- Inverse Rendering -->
<div class="glass-card scroll-reveal">
  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <h3 style="margin-top: 0; color: #66FCF1;">Outdoor Scene Inverse Rendering using Single Image</h3>
    <span class="badge"><i class="fas fa-camera"></i> Completed</span>
  </div>
  <p style="font-size: 0.9em; color: #45A29E; margin-bottom: 1em;">Prof. Shanmuganathan Raman | IIT Gandhinagar • Dec 2024 – Aug 2025</p>
  <ul>
    <li>Formulated a pipeline to perform inverse rendering of outdoor scenes from a single RGB image by estimating lighting (SH coefficients) using VQGAN-based feature extraction.</li>
    <li>Implemented 2D and 3D Gaussian Splatting for high-fidelity depth map and surface normal reconstruction.</li>
    <li>Evaluated geometry and lighting accuracy across diverse real-world outdoor datasets.</li>
  </ul>
</div>

<!-- CLIP-Infused IBRNet -->
<div class="glass-card scroll-reveal">
  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <h3 style="margin-top: 0; color: #66FCF1;">CLIP-Infused Image-Based Rendering (IBRNet)</h3>
    <span class="badge"><i class="fas fa-images"></i> Completed</span>
  </div>
  <p style="font-size: 0.9em; color: #45A29E; margin-bottom: 1em;">Prof. Shanmuganathan Raman | IIT Gandhinagar • Aug 2024 – Dec 2024</p>
  <ul>
    <li>Enhanced IBRNet’s robustness to large baseline variations using CLIP embeddings for generalized, high-quality feature representation.</li>
    <li>Designed a WaveNet-inspired encoder to compress CLIP’s 768-dimensional embeddings to 32 dimensions while retaining spatial context.</li>
    <li>Fine-tuned the encoder-decoder pipeline with pretrained weights, improving interpolation accuracy and multi-view rendering quality.</li>
  </ul>
</div>
