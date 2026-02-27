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
      Zhanyu Tuo<br>
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
  Zhanyu Tuo<br>
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
    <img src="assets/img/IMAGE3.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    Available surface detection by top-view depth camera
    -automatic ground truth generation for binary semantic segmentation
</h3>

<p style="margin:6px 0;">
  <span style="text-decoration: underline;">Z. Tuo</span>, 
  V. Brandt, 
  M. Juhlin,
  L. Rauh<br>
  <i>2020</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-3')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-3" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
A common problem for factory environments is incorporating a flexible assembly-line workflow that does not occupy too much space on the factory floor. For these purposes autonomous vehicles could be used to supply the assembly-lines with materials, but the problem of navigating in the factory then arises. Therefore this project aims to solve the problem of what areas of a factory floor are drivable, using a workflow consisting of background subtraction to generate a ground truth, that is then used to train a neural network. The output could potentially be used as a mapping for which a scheduler or robot control system could work upon to avoid collisions and problems with dynamic obstacles.
      </p>
    </div>

  </div>
</div>


<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE4.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    3D Object Detection from Stereo - combining 3D computer vision geometry with neural networks
</h3>

<p style="margin:6px 0;">
  Zhanyu Tuo 
  <br>
  <i>2020</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-4')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-4" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
In this project we apply Geometry based Computer Vision to refine 3D bounding boxes from the outputs of neural networks. The neural networks predict the boxes boundary on stereo images, and then 3D computer vision geometry are added to refine the 3D boundary boxes.
      </p>
    </div>

  </div>
</div>

<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE5.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    Implementation of an Interactive Autonomous Guard Robot with Humanoid Features
</h3>

<p style="margin:6px 0;">
  F. Lagerstedt,
  <span style="text-decoration: underline;">Z. Tuo</span>, 
  T. Stenström, 
  N. C. Gammanage<br>
  <i>2019</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-5')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-5" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
In this project we have developed a humanoid guard robot that interacts with people that approach it. Its sole purpose is to grant access to people with proper credentials and keep intruders off. More specifically, face detection is used to detect an approaching person. It then initiates a dialogue, asking for credentials. If the person is authorized, the robot will greet the them. Otherwise, the robot will ask the person to leave. The purpose of this project has been to design and construct this robot to get a better understanding of robotics hardware and software such as Robot Operating System (ROS) and to apply basic algorithms from computer vision and mechanical dynamics.
      </p>
    </div>

  </div>
</div>

<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE9.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    3D reconstruction of Skansen Lejonet by Structure from Motion
</h3>

<p style="margin:6px 0;">
   D. Xue 
  <span style="text-decoration: underline;">Z. Tuo</span> 
  <br>
  <i>2019</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-9')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-9" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
In this project, we reconstruct the 3D point cloud of Skansen Lejonet by using severl images from different view points. we use RANSAC to estimate a new camera pose with minimum outliers, and evaluate a picture-sorting strategy by comparison with a carefully manually ranked order, we also evaluate effect of refine-triangulation in process of adding new cameras.
      </p>
    </div>

  </div>
</div>

<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE10.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    Bike trajectory tracking based on Partical Filter 
</h3>

<p style="margin:6px 0;">
  Zhanyu Tuo 
  <br>
  <i>2019</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-11')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-11" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
In this project, we design a Partical Filter with resampling to track a bike trajectory. We have a map and a measurment of the velocity of bike. With a initial guess of the bike location,  the particles are getting close to the true trajectory step by step, and finally the Particil filter follow the trajectory very well.
      </p>
    </div>

  </div>
</div>


<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE11.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    Virtual Verification and Validation of Machine Learning Models for Road Damage Detection 
</h3>

<p style="margin:6px 0;">
  Zhanyu Tuo 
  <br>
  <i>2019</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-10')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-11" style="display:none; margin-top:11px;">
      <b>Abstract:</b>
      <p>
In this project, we use Unity to design vertial environment with a virtual camera to collect dataset for road damage detection. Since collecting real data in the real world is very expensive, a vertial environment with different types of road damages is built and differnt types of road damages are generated and then used for verification and validation of machine learning models for road damage detection.
      </p>
    </div>

  </div>
</div>

<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE6.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    Music Genre Recognition and Classification by CNN and CRNN on Spectrogram Images
</h3>

<p style="margin:6px 0;">
  <span style="text-decoration: underline;">Z. Tuo</span>, 
  M. Sikora <br>
  <i>2019</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-6')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-6" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
To classify the genre of digital music, a sound signal is transformed into a Spectrogram image. Then, a traditional convolutional neural network (CNN)--transfer learning with VGG16, and a convolutional recurrent neural network (CRNN)--a RNN on top of a CNN, are designed separately to recognise music genre. It is proved that CRNN performs better than CNN when it comes to music genre recognition using spectrogram images.
      </p>
    </div>

  </div>
</div>


<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE7.jpg" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    Orientation Estimation by EKF Algorithm on Gyroscope, Accelerometer, and Magnetomete
</h3>

<p style="margin:6px 0;">
  <span style="text-decoration: underline;">Z. Tuo</span>, 
  N. Moheq <br>
  <i>2019</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-7')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-7" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
In this project, a filter is designed to use the data from 3 key sensors of an Android mobile phone: gyroscope, accelerometer and magnetometer. The gyroscope, measures the angular velocity(omega). The accelerometer sensor measures the external force causing acceleration(a) such as gravity and other force that are acting on the phone. Finally, the magnetometer, measures the affect of the magnetic field(m) on the device. Then we designed an outlier to omit out the unaccepted measurements and only use the measurements which are in a accepted interval.
      </p>
    </div>

  </div>
</div>

<div style="display:flex; flex-wrap:wrap; gap:20px; margin-bottom:35px;">

  <!-- Left image -->
  <div style="flex:0 0 260px; max-width:260px;">
    <img src="assets/img/IMAGE8.png" style="width:100%; border-radius:10px;">
  </div>

  <!-- Right content -->
  <div style="flex:1; min-width:260px;">

<h3 style="margin-top:0;">
    Model, Simulate, Design, Implement, and Validat a LQR controller for a Quadrocopter
</h3>

<p style="margin:6px 0;">
  N. Andr´en, 
  <span style="text-decoration: underline;">Z. Tuo</span>, 
  O. Wahlgren, X. Liang<br>
  <i>2019</i>
</p>

<!-- Buttons -->
    <p style="margin:10px 0;">

      <a href="javascript:void(0);" onclick="toggleBlock('abstract-8')" style="background:#7aa874; color:white; padding:6px 12px; border-radius:6px; text-decoration:none;">abstract</a>
    </p>

<!-- Abstract (hidden) -->
    <div id="abstract-8" style="display:none; margin-top:10px;">
      <b>Abstract:</b>
      <p>
In this project, we design a complimentary filter which uses the readings from the gyroscope and calculated angle from accelerometer, the drift of the readings of the sensors is eliminated. By comparing the simulations results we verify that the model is correct. We also chose a proper operating point to linearize the model so that we can design a LQR controller to control the system.  The LQR controller has been designed by adjusting the values of Q and R matrix. From the simulation results, we can see that the LQR controller performs well that the output can follow the reference well. But for the real physical system, the performance which can be improved later is noisy and not as good as the simulation result.
      </p>
    </div>

  </div>
</div>



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
