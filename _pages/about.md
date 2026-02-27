---
permalink: /
title: "ZHANYU TUO"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second year PhD candidate with research interests in 3D Computer Vision, Vision Language Models, Camera Mocap Sensor Fusion, Robotics, and so on.

Please feel free to contact me if there are any opportunities for secondements, collaborations, open discussions, and so on.

Publications
======
<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE1.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

  <h3 style="margin-top:0;">
      RPGD: RANSAC-P3P Gradient Descent for Extrinsic Calibration in 3D Human Pose Estimation
    </h3>

  <p style="margin:6px 0;">
      <span style="text-decoration: underline;">Zhanyu Tuo</span><br>
      <i>arXiv 2026</i>
    </p>

    <!-- Buttons -->
    <p style="margin:10px 0;">
      <a href="assets/papers/2602.13901v1.pdf" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none; margin-right:6px;">pdf</a>

      <a href="javascript:void(0);" onclick="toggleBlock('bibtex-paper1')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none; margin-right:6px;">bibtex</a>

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-paper1')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

    <!-- Abstract (hidden) -->
    <div id="abstract-paper1" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
      In this paper, we propose RPGD (RANSAC-P3P Gradient Descent), a human-pose-driven extrinsic calibration framework that robustly aligns MoCap-based 3D skeletal data with monocular or multi-view RGB cameras using only natural human motion. RPGD formulates extrinsic calibration as a coarse-to-fine problem tailored to human poses, combining the global robustness of RANSAC-P3P with Gradient-Descent-based refinement. We evaluate RPGD on three large-scale public 3D HPE datasets as well as on a self-collected in-the-wild dataset. Experimental results demonstrate that RPGD consistently recovers extrinsic parameters with accuracy comparable to the provided ground truth, achieving sub-pixel MPJPE reprojection error even in challenging, noisy settings. These results indicate that RPGD provides a practical and automatic solution for reliable extrinsic calibration of large-scale 3D HPE dataset collection.
      </p>
    </div>

    <!-- BibTeX (hidden) -->
    <div id="bibtex-paper1" style="display:none; margin-top:10px;">
<pre>
@article{tuo2026rpgd,
  title={RPGD: RANSAC-P3P Gradient Descent for Extrinsic Calibration in 3D Human Pose Estimation},
  author={Tuo, Zhanyu},
  journal={arXiv preprint arXiv:2602.13901},
  year={2026}
}
</pre>
    </div>

  </div>
</div>
  
Thesis
======
<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE2.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
  <a href="https://odr.chalmers.se/items/d2739ec1-4d56-4570-8d44-28921e41c8cd">
    Object Detection and Localization with Multi-agent Sensor Fusion
  </a>
</h3>

<p style="margin:6px 0;">
  <span style="text-decoration: underline;">Zhanyu Tuo</span><br>
  <i>2020</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-paper2')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-paper2" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
The development of Autonomous Driving and Advanced Driver Assistance Systems (AD \& ADAS) has seen rapid progress recently. With the evolution of hardware such as Graphics Processing Units (GPUs) and sensors, as well as a massive increase in the number of datasets and increasingly powerful algorithms, more and more research projects focusing on AD \& ADAS are carried out. In this project, we explore the feasibility of multi-agent sensor fusion for object detection and localization, especially for detection of objects that are occluded in Lidar point clouds, and some prediction results such as 2D vehicle bounding boxes on the images and 3D vehicle bounding boxes in the Lidar point clouds are achieved.

In terms of safe driving, it is important to obtain an exhaustive perception of all objects around the ego vehicle. Sometimes surrounding objects to be detected are occluded when all the sensors are installed on an ego vehicle. To detect and localize surrounding objects, especially for those occluded in the Lidar view, Lidar sensor data and aerial photography from a drone are fused off-line. A Convolutional Neural Network (CNN) focusing on instance segmentation is trained using transfer learning along with image augmentation. An image-based 3D reconstruction map is created and matched with a corresponding Lidar SLAM map. Finally, Lidar point clouds are projected onto the corresponding images, and predicted masks from the CNN are used to detect and localize objects in the Lidar point clouds. The method is evaluated on static and dynamic scenarios separately, and objects can be detected and localized based on fused sensors regardless of the occlusion in the Lidar point clouds. 
      </p>
    </div>

  </div>
</div>

Projects
======
<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE3.jpg" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    Available surface detection by top-view depth camera
    -automatic ground truth generation for binary semantic segmentation
  </a>
</h3>

<p style="margin:6px 0;">
  <span style="text-decoration: underline;">Z. Tuo</span><br>
  <i>2019</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-paper2')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-paper2" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
A common problem for factory environments is incorporating a flexible assembly-line workflow that does not occupy too much space on the factory floor. For these purposes autonomous vehicles could be used to supply the assembly-lines with materials, but the problem of navigating in the factory then arises. Therefore this project aims to solve the problem of what areas of a factory floor are drivable, using a workflow consisting of background subtraction to generate a ground truth, that is then used to train a neural network. The output could potentially be used as a mapping for which a scheduler or robot control system could work upon to avoid collisions and problems with dynamic obstacles.
      </p>
    </div>

  </div>
</div>

- 3D Object Detection from Stereo
- Intelligent Humanoid Robot
- Music Genre Recognition
- Orientation Estimation by EKF Algorithm
- Sequential 3D Reconstruction

Talks
======
- [The RenAIssance](https://www.rsa.org/news/702862/Program-Announced-The-RenAIssance.htm): Graduate Student Lightning Talks in 2025.

Awards
======
- [Volvo Car Scholarship](https://www.european-funding-guide.eu/fr/bourse/8412-The-Volvo-Car-Group-Scholarships) from 2018 to 2020, 2 students in total per year.

Beyonds
======
I am very interested in taking photos, road and trail runnings, hiking and camping, backpacking around the world, and so on.
- Marathon PB: 03:59:36 at Paris Marathon 2025
- Half Marathon PB: 01:44:24 at Half Marathon in Vincennes 2025
- Highest mountains peaked on foot: Kebnekaise in Sweden and Mount Taibai in China.
- Best hiking experience: Tour du Mont Blanc through France, Italy, and Swizerland in 2023.

<script>
function toggleBlock(id) {
  var x = document.getElementById(id);
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>
