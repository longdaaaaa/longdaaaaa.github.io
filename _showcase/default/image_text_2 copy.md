---
show: true
width: 12
date: 2022-02-12 00:01:00 +0800
height: 500px                     # 轮播区域的显示高度
title: Project 1
images:
- src: assets/images/projects/cof1.png
  title: Data Collection
  desc: 
  link: 
- src: assets/images/projects/cof2.png
  title: Test Execution
  desc:
- src: assets/images/projects/grabbing.png
  title: End Position Fine-tuning

---

<div class="card h-100 rounded-xl overflow-hidden">
  <!-- 轮播放在“卡片图像区域” -->
  <div class="card-img-top p-0" style="height: {{ page.height }}; overflow:hidden;">
    {% include widgets/carousel.html id=page.id images=page.images height=page.height %}
  </div>

<!-- <div>
  <img data-src="assets/images/projects/cross.png" class="lazy w-100 rounded-xl-top" src="{{ '/assets/images/empty_300x200.png' | relative_url }}"> -->
  
  <div class="card-body">
    <h5 class="card-title">Retrieval-Augmented Prompting for VLM Robotic Manipulation in Real-World Tasks</h5>
    <p class="card-text">
      This project first collects images and robot state information in the <code>LeRobot</code> format. Then, it leverages <span style="color: #00bfa6;">Qwen3, CLIP, VGGT, and Google Gemini</span> to convert environmental data, instructions, and motion sequences into vector representations, which are stored in the Meta FAISS vector database. During the execution phase, similar sequences are retrieved from the vector database and combined into a prompt for Gemini. In addition, I am experimenting with a reliable VLM confidence voting strategy to fine-tune the end-effector position.
    </p>
    <p class="card-text">
      This project makes use of Google Gemini’s extended sequence input processing and reasoning capabilities. I am currently working on transforming it into a manuscript. 
    </p>

  </div>
</div>
