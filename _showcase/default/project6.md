---
show: true
width: 12
date: 2019-02-12 00:01:00 +0800
height: 500px                     # 轮播区域的显示高度
title: Project 6
images:
- src: assets/images/projects/project6/1.png
  title: 
- src: assets/images/projects/project6/2.png
  title: 
- src: assets/images/projects/project6/3.png
  title: 
- src: assets/images/projects/project6/4.png
  title: 
- src: assets/images/projects/project6/5.png
  title: 
- src: assets/images/projects/project6/6.png
  title: 
- src: assets/images/projects/project6/7.png
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
    <h5 class="card-title">Debugging and Application of High Power Impulse Magnetron Sputtering Power Supply(Undergraduate Thesis) </h5>
    <p class="card-text">
      High-power pulsed magnetron sputtering power supply is a special power supply that can generate high peak pulse voltage with a certain power. It is mainly used in the field of coating, and coating is widely used in industry, so this power supply is widely used in in industry. There are three wastes in the traditional electroplating process, which requires a lot of funds to manage, and it is difficult to solve them fundamentally. Under the high-power pulsed magnetron sputtering, the ionization rate of the metal is very high, so that better wrapping performance can be obtained. In addition, the sputtering yield of copper is very high, so the deposition rate on the film using high-power pulsed magnetron sputtering technology is higher than other sputtering technologies, and an efficient, fast, high-volume coating process can be achieved, and it is environmentally friendly. pollution is small. The use of high-power pulsed magnetron sputtering technology to fabricate thin films is a very practical method. In this thesis, a high-performance and high-power pulsed magnetron sputtering source is designed for the first time, and its working principle, structure design and power supply are studied comprehensively, and it is applied in the 702 teaching and research room of Beijing University of Aeronautics and Astronautics. Secondly, the output signal test of the internal circuits of all levels is carried out using the self-developed high-power pulsed magnetron sputtering power supply. The plasma load and resistance load were connected, and the output signal was tested, and the influence factors of some parameters on the output current were studied. Finally, Cu thin films were prepared using the self-developed high-power pulsed magnetron sputtering power supply, which verified the availability of the power supply.
    </p>
  </div>
</div>
