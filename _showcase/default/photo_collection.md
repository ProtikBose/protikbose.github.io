---
show: true
width: 8
date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: assets/images/myshowcase/firework_dhaka.jpg
  #title: Photo 1
  desc: Fireworks in Dhaka, Bangladesh
  link: https://picsum.photos/
- src: assets/images/myshowcase/thailand_1.jpg
  #title: Photo 2
  desc: Golden Palace, Thailand
- src: assets/images/myshowcase/dhaka.jpg
- src: assets/images/myshowcase/ohio.jpg
  #title: Photo 2
  desc: Put-in-Bay, OH
- src: assets/images/myshowcase/nepal_1.jpg
  #title: Photo 2
  desc: Kathmandu, Nepal
- src: assets/images/myshowcase/india_1.jpg
  #title: Photo 2
  desc: Manali, India
- src: assets/images/myshowcase/india_2.jpg
  #title: Photo 2
  desc: kashmir, India
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
