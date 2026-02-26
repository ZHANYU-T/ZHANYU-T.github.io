---
permalink: /
title: "ZHANYU TUO"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second year PhD candidate with research interests in 3D Computer Vision, Vision Language Models, Camera Mocap Sensor Fusion and so on.

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
      <a href="#">Zhanyu Tuo</a><br>
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
  

Talks
======
- [The RenAIssance](https://www.rsa.org/news/702862/Program-Announced-The-RenAIssance.htm): Graduate Student Lightning Talks in 2025.

Thesis
======
- [Object Detection and Localization with Multi-agent Sensor Fusion](https://odr.chalmers.se/items/d2739ec1-4d56-4570-8d44-28921e41c8cd).

Projects
======
- Available Surface Detection
- 3D Object Detection from Stereo
- Intelligent Humanoid Robot
- Music Genre Recognition
- Orientation Estimation by EKF Algorithm
- Sequential 3D Reconstruction

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
