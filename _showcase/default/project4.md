---
show: true
width: 12
date: 2020-02-12 00:01:00 +0800
height: 500px                     # 轮播区域的显示高度
title: Project 4
images:
- src: assets/images/projects/project4/dahui.png
  title: 
- src: assets/images/projects/project4/task.jpg
  title: 
- src: assets/images/projects/project4/new.jpg
  title: 
- src: assets/images/projects/project4/robot.jpg
  title: 
- src: assets/images/projects/project4/robot2.jpg
  title: 
- src: assets/images/projects/project4/end.jpg
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
    <h5 class="card-title">Design of a Desert Tree-Planting Robot</h5>
    <p class="card-text">
      After completing my bachelor’s degree, I joined <code>Eason Intelligence</code>, a startup that, at the time of my arrival, had only the CEO and the general manager. Both were seasoned entrepreneurs who had already secured cooperation intentions from the Chinese and Saudi governments to support efforts in combating desertification. The company’s parent firm, a publicly listed enterprise with extensive experience in desertification control, had developed specialized Salix seedlings suitable for plantation in arid regions.
    </p>
    <p class="card-text">
      I was involved in defining the overall design plan of the tree-planting robot. Once the plan was finalized, I took charge of tasks including the battery and track selection and sizing, the water distribution system design, and FEA of the overall framework. It was also my first time participating in manufacturer selection and coordinating with them throughout the production process. During this period, I obtained several invention patents.
    </p>
    <p class="card-text">
      Today, the company has grown to more than 20 employees and established its own manufacturing facility.
    </p>
    <p class="card-text">
    </p>
  </div>
</div>
