---
show: true
width: 12
date: 2021-02-12 00:01:00 +0800
height: 500px                     # 轮播区域的显示高度
title: Project 4
images:
- src: assets/images/projects/project5/flow.png
  title: 
- src: assets/images/projects/project5/process.JPG
  title: 
- src: assets/images/projects/project5/allarena.png
  title: 
- src: assets/images/projects/project5/AMHS.png
  title: 
- src: assets/images/projects/project5/results2.JPG
  title: 
- src: assets/images/projects/project5/loop.JPG
  title: 
- src: assets/images/projects/project5/control.png
  title: 
- src: assets/images/projects/project5/results.png
  title: 
---

<div class="card h-100 rounded-xl overflow-hidden">
  <!-- 轮播放在“卡片图像区域” -->
  <div class="card-img-top p-0" style="height: {{ page.height }}; overflow:hidden;">
    {% include widgets/carousel.html id=page.id images=page.images height=page.height %}
  </div>

<!-- <div>
  <img data-src="assets/images/projects/cross.png" class="lazy w-100 rounded-xl-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}"> -->
  
  <div class="card-body">
    <h5 class="card-title">Simulation analysis of different fatigue intervention strategies based on fatigue estimation in manufacturing scenarios</h5>
    <p class="card-text">
      I conducted simulation modeling of wafer fab defect detection process using ARENA. Also designed a simulation strategy for worker fatigue progression and common interventions, and conducted comparative analysis across different intervention strategies.
    </p>
    <p class="card-text">
      This represents a feasible simulation approach for worker fatigue in industrial scenarios, and the project also provides some simulation logics that can serve as useful references. I am now actively working on transforming this project into a publication.
    </p>
  </div>
</div>
