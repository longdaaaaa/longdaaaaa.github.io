<!-- ---
show: true
width: 12
date: 2018-02-12 00:01:00 +0800
height: 500px                     # 轮播区域的显示高度
title: Project 1
images:
- src: assets/images/projects/project3/A.jpg
  title: Montreal
  desc: 
  link: 
- src: assets/images/projects/project3/B.jpg
  title: Presentation
  desc:
- src: assets/images/projects/project3/C.jpg
  title: On Conference
- src: assets/images/projects/project3/D.jpg
  title: On Conference
- src: assets/images/projects/project3/E.jpg
  title: On Conference
---

<div class="card h-100 rounded-xl overflow-hidden">
  <!-- 轮播放在“卡片图像区域” -->
  <div class="card-img-top p-0" style="height: {{ page.height }}; overflow:hidden;">
    {% include widgets/carousel.html id=page.id images=page.images height=page.height %}
  </div>

<!-- <div>
  <img data-src="assets/images/projects/cross.png" class="lazy w-100 rounded-xl-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}"> -->
  
  <div class="card-body">
    <h5 class="card-title">Thank Braithwaite Conference Travel Grant for sponsoring my participation in CSME 2025!</h5>
    <p class="card-text">
    </p>
  </div>
</div> -->
