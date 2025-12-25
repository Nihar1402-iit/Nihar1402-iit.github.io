---
layout: archive
title: "Blogs"
permalink: /blogs/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}

<style>
.projects-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 blogs per row */
  gap: 25px;
  margin-top: 30px;
}

.project {
  box-sizing: border-box;
  padding: 10px;
  text-align: center;
}

.project img {
  width: 100%;
  height: 200px;              /* Fixed height for uniformity */
  object-fit: cover;          /* Ensures same aspect ratio */
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.project p {
  margin-top: 10px;
  font-size: 0.95rem;
}

/* Navigation styling */
.navigation {
  text-align: center;
  margin: 50px 0 20px 0;
}

.navigation a {
  display: inline-block;
  margin: 0 6px;
  padding: 6px 12px;
  background-color: #ddd;
  color: #333;
  text-decoration: none;
  border-radius: 5px;
}

.navigation a:hover {
  background-color: #bbb;
}

.navigation .arrow {
  font-size: 18px;
  vertical-align: middle;
}

/* Responsive fallback */
@media (max-width: 900px) {
  .projects-container {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 600px) {
  .projects-container {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="projects-container">

  <div class="project">
    <a href="/_pages/Assignment1_ES666_The_Chamber_of_Singular_Truths_22110237.html">
      <img src="https://github.com/user-attachments/assets/05df42ad-3d2c-4cdf-b6c6-827c5153b2bb" alt="">
    </a>
    <p>Singularities and Image Structure: Foundations of Visual Signal Representation</p>
  </div>

  <div class="project">
    <a href="/_pages/22110237_ES666_Assignment_4_The_Flux_of_Motion.html">
      <img src="https://github.com/user-attachments/assets/acad45ce-7e11-456e-8820-47401fe3fab1" alt="">
    </a>
    <p>Motion Estimation and Temporal Dynamics in Visual Signals</p>
  </div>

  <div class="project">
    <a href="/_pages/22110237_D_Matrix_Methods.html">
      <img src="https://github.com/user-attachments/assets/4becdbfd-4c34-4831-aefb-81e850e8bc12" alt="">
    </a>
    <p>Matrix Decompositions, Subspaces, and Dimensionality Reduction</p>
  </div>

  <div class="project">
    <a href="/_pages/22110237_C_Matrix_Methods.html">
      <img src="https://github.com/user-attachments/assets/25e822bd-8c67-41fa-83a9-42a6d6e2f057" alt="">
    </a>
    <p>Linear Transformations, Eigenanalysis, and Matrix Representations</p>
  </div>

  <div class="project">
    <a href="/_pages/ES670_Assignment_A_Vectors_and_Clustering.html">
      <img src="https://github.com/user-attachments/assets/9c772baf-9cf9-4dbe-923d-c799b38a321f" alt="">
    </a>
    <p>Vector Spaces, Distance Metrics, and Clustering in High-Dimensional Data</p>
  </div>

  <div class="project">
    <a href="/_pages/Mosaic_of_Whispers_Blog.html">
      <img src="https://github.com/user-attachments/assets/b8b10960-08b0-42e5-aea1-8575d9ac16a3" alt="">
    </a>
    <p>Frequency Analysis and Spatial Filtering in Images</p>
  </div>

  <div class="project">
    <a href="/_pages/Assignment_2_22110237.html">
      <img src="https://github.com/user-attachments/assets/f25860ae-a6b6-48bd-9c7d-1c25bf862357" alt="">
    </a>
    <p>Understanding Gradient Descent and Its Variants</p>
  </div>

  <div class="project">
    <a href="/_pages/22110237_Assignment3_ES666_trimmed_6MB.html">
      <img src="https://github.com/user-attachments/assets/0c0344f8-5536-424e-a6a3-bacad49a56e7" alt="">
    </a>
    <p>Foundations of Image Representation and Analysis: Gradients, Frequency-Domain Methods, Motion, and Image Stitching</p>
  </div>

  <div class="project">
    <a href="/_pages/Shot_Prompting.html">
      <img src="https://github.com/user-attachments/assets/e90f183e-0004-4d03-9159-e99b7e73911c" alt="">
    </a>
    <p>Shot Prompting (Explained on Amazon ML Challenge 2024 Dataset)</p>
  </div>

</div>

<div class="navigation">
  <a href="/blogs">1</a>
  <a href="/blogs2">2</a>
  <a href="/blogs2" class="arrow">Next &gt;</a>
</div>
