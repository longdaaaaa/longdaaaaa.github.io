---
show: true
width: 12
date: 2022-01-12 00:01:00 +0800
height: 500px                     # 轮播区域的显示高度
title: Project 1
images:
- src: assets/images/projects/overall.png
  title: Overall Framework
  desc: 
  link: 
- src: assets/images/projects/cross.png
  title: XS Mechanisim
  desc:
- src: assets/images/projects/network.png
  title: Network Architecture
- src: assets/images/projects/sotas.png
  title: Performance
---

<div class="card h-100 rounded-xl overflow-hidden">
  <!-- 轮播放在“卡片图像区域” -->
  <div class="card-img-top p-0" style="height: {{ page.height }}; overflow:hidden;">
    {% include widgets/carousel.html id=page.id images=page.images height=page.height %}
  </div>

<!-- <div>
  <img data-src="assets/images/projects/cross.png" class="lazy w-100 rounded-xl-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}"> -->
  
  <div class="card-body">
    <h5 class="card-title">LightPose: A Lightweight Fatigue-Aware Pose Estimation Framework</h5>
    <p class="card-text">
      <span style="color: #00bfa6;">LightPose</span> is a lightweight human pose estimation framework guided by bone segment principles. <span style="color: #00bfa6;">LightPose</span> is designed to balance spatial accuracy with computational efficiency, delivering pose quality comparable to recent sequence-based baselines while remaining lightweight enough for real-time, fatigue-aware analysis. The framework incorporates a dual-stream supervision mechanism that enforces local geometric consistency through mutual prediction between joint pairs on the same bone segment. Additionally, kinematic constraints and fatigue-relevant metric regulations are embedded within the training objective, promoting biomechanical plausibility and alignment with fatigue-related motion patterns. Experimental results on standard 3D pose estimation benchmarks demonstrate that <span style="color: #00bfa6;">LightPose</span> delivers competitive accuracy with reduced computational cost. Further evaluations confirm its effectiveness in estimating fatigue-related kinematic indicators, establishing its suitability for fatigue detection tasks. 
    </p>
    <p class="card-text">
      The manuscript of this work is submitted to <code>Journal of Industrial Information Integration</code>. And the major revision has been completed. <span style="color: #191970;">This is my first time independently completing the entire process of writing a journal paper manuscript, preparing the figures, and responding to reviewers’ comments.</span>
    </p>
  </div>
</div>
