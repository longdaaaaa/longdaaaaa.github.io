---
show: true
width: 12
date: 2021-03-12 00:01:00 +0800
height: 500px                     # 轮播区域的显示高度
title: Project 1
images:
- src: assets/images/projects/project2/1.png
  title: Overall Framework
  desc: 
  link: 
- src: assets/images/projects/project2/2.png
  title: Network
  desc:
- src: assets/images/projects/project3/wave.png
  title: Wavelet Transform Matrix
  desc:
- src: assets/images/projects/project2/3.png
  title: Skeletal Stream
- src: assets/images/projects/project2/4.png
  title: Task
- src: assets/images/projects/project2/5.png
  title: Aggregation Effect after FFT
- src: assets/images/projects/project2/6.png
  title: Kinematic Matrix
---

<div class="card h-100 rounded-xl overflow-hidden">
  <!-- 轮播放在“卡片图像区域” -->
  <div class="card-img-top p-0" style="height: {{ page.height }}; overflow:hidden;">
    {% include widgets/carousel.html id=page.id images=page.images height=page.height %}
  </div>

<!-- <div>
  <img data-src="assets/images/projects/cross.png" class="lazy w-100 rounded-xl-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}"> -->
  
  <div class="card-body">
    <h5 class="card-title">Deep Learning-Based Fatigue Detection Using Kinematic Information from Videos</h5>
    <p class="card-text">
      Detecting human fatigue in manufacturing scenarios has been a long-standing research focus, driven by its profound impact on worker welfare. Fatigue contributes to work-related accidents and long-term musculoskeletal disorders, underscoring the need for effective monitoring solutions. With advancements in deep learning and image processing technologies, fatigue detection methods are increasingly adopting noninvasive approaches. Such solutions minimize disruptions to workers’ activities while ensuring accurate monitoring. In this paper, we proposed a deep learning-based method that leverages motion and posture data extracted from videos to detect worker fatigue. This approach is both noninvasive and cost-effective, offering practical benefits for industrial applications. 
    </p>
    <p class="card-text">
      This work has contributed to a papar which was presented at <code>Proceedings of the Canadian Society for Mechanical Engineering International Congress</code> (Montreal, 2025).
    </p>
  </div>
</div>
