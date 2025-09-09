---
show: true
width: 6
date: 2017-01-12 00:01:00 +0800
---

<!-- 自适应 16:9 的容器，支持圆角 -->
<style>
.ratio-16x9 { position: relative; width: 100%; aspect-ratio: 16/9; background:#000; border-radius: 12px; overflow: hidden; }
.ratio-16x9 iframe { position: absolute; inset: 0; width: 100%; height: 100%; border: 0; }
</style>

<div class="ratio-16x9">
  <iframe
    src="https://www.youtube-nocookie.com/embed/ElcOFTFr0Zg"
    title="YouTube video"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>


<div class="p-4">
    <h5>myCobot-320 Camera & Voice-Based Control</h5>
    <hr />
    <p class="card-text">
      The visual control module is powered by YOLO, whereas the voice control module is realized through OpenAI’s Whisper and ChatGPT-4.
    </p>
</div>