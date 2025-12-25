---
layout: archive
title: "blogs2"
permalink: /blogs2/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}

<style>
.projects-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 20px;
}

.project {
  flex: 0 0 30%;   /* EXACTLY 3 per row */
  box-sizing: border-box;
  text-align: center;
}

.project img {
  width: 100%;
  height: 200px;          /* ✅ fixed height */
  object-fit: cover;      /* ✅ uniform crop */
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.project p {
  margin-top: 10px;
  font-size: 0.95rem;
}

/* Responsive: 2 per row on tablets */
@media (max-width: 900px) {
  .project {
    flex: 0 0 45%;
  }
}

/* Responsive: 1 per row on mobile */
@media (max-width: 600px) {
  .project {
    flex: 0 0 100%;
  }
}

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
</style>

<div class="projects-container">

  <div class="project">
    <a href="/_pages/UPI_voice.html">
      <img src="https://github.com/user-attachments/assets/789a699f-c4f6-40cd-ae20-8ac0bc0dfb5b">
    </a>
    <p>UPI Payment using Voice</p>
  </div>

  <div class="project">
    <a href="/_pages/HNSW_2.html">
      <img src="https://github.com/user-attachments/assets/ef9dd466-d5f2-44fe-affa-bc0bde0d64b4">
    </a>
    <p>Hierarchical Navigable Small World (HNSW) Graphs</p>
  </div>

  <div class="project">
    <a href="/_pages/FFT_2.html">
      <img src="https://github.com/user-attachments/assets/ba545056-0b90-4649-820e-441b11ee8d96">
    </a>
    <p>FFT and Its Applications</p>
  </div>

  <div class="project">
    <a href="/_pages/RNN.html">
      <img src="https://github.com/user-attachments/assets/3b55f107-5ec2-4ffb-a13c-47edc5bcfd98">
    </a>
    <p>Recurrent Neural Networks</p>
  </div>

  <div class="project">
    <a href="/_pages/Grad_desc.html">
      <img src="https://github.com/user-attachments/assets/8e5a954a-fb03-484d-b9fd-16cf6e36c1d9">
    </a>
    <p>Understanding Gradient Descent and Its Variants</p>
  </div>

  <div class="project">
    <a href="/_pages/dlib_face_recognition.html">
      <img src="https://github.com/Nihar1402-iit/Nihar1402-iit.github.io/assets/117573996/288685f4-bff4-40ed-a303-df0b43067314">
    </a>
    <p>dlib Face Recognition</p>
  </div>

  <div class="project">
    <a href="/_pages/HOG_blogs.html">
      <img src="https://github.com/Nihar1402-iit/Nihar1402-iit.github.io/assets/117573996/56ac26a3-2f85-4dfe-9898-a22e3b779b63">
    </a>
    <p>Histogram of Oriented Gradients (HOG)</p>
  </div>

  <div class="project">
    <a href="/_pages/SVM_kernals.html">
      <img src="https://github.com/Nihar1402-iit/Nihar1402-iit.github.io/assets/117573996/80c4683d-5c96-4ff5-b54e-4e4d1d06bf07">
    </a>
    <p>SVM Kernels</p>
  </div>

  <div class="project">
    <a href="/_pages/Blog_SVM (1).html">
      <img src="https://github.com/Nihar1402-iit/Nihar1402-iit.github.io/assets/117573996/5e0cb2c3-9943-466d-ad9b-20559840b74a">
    </a>
    <p>Support Vector Machines</p>
  </div>

</div>

<div class="navigation">
  <a href="/blogs" class="arrow">&lt; Previous</a>
  <a href="/blogs">1</a>
  <a href="/blogs2">2</a>
</div>

