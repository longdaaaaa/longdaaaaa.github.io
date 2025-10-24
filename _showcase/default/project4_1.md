---
show: true
width: 12
date: 2021-03-22 00:01:00 +0800
height: 500px                     # 轮播区域的显示高度
title: Project 4
images:
- src: assets/images/projects/trans.png
  title: Pipeline
---

<div class="card h-100 rounded-xl overflow-hidden">
  <!-- 轮播放在“卡片图像区域” -->
  <div class="card-img-top p-0" style="height: {{ page.height }}; overflow:hidden;">
    {% include widgets/carousel.html id=page.id images=page.images height=page.height %}
  </div>

<!-- <div>
  <img data-src="assets/images/projects/cross.png" class="lazy w-100 rounded-xl-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}"> -->
  
  <div class="card-body">
    <h5 class="card-title">Sequential Multi-Teacher Cross-Modal Distillation for Lightweight IMU Representation Learning</h5>
    <p class="card-text">
      This project introduces a multi teacher to single student cross modal knowledge distillation framework that transfers information from rich multi sensor models to an IMU only student model. Each teacher learns shared and modality specific representations through self supervised cross modal masked reconstruction, and their outputs are aligned in a unified global space using prototype alignment based on optimal transport. The IMU student model uses a mixture of experts architecture and learns sequentially from teachers while applying anti forgetting strategies such as LwF, EWC and replay to maintain stability. This approach enables a lightweight IMU network to achieve multi modal level understanding for human machine interaction.
    </p>
    <p class="card-text">
      The project is currently in the manuscript preparation stage, and the target journal is <code>IEEE Transactions on Affective Computing</code>.
    </p>
  </div>
</div>
