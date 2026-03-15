---
show: true
width: 4
date: 2026-12-31 23:59:58 +0800
height: 295px
images:
- src: /assets/images/showcase/Everest.jpg
  desc: Golden Sunrise, Mount Everest
- src: /assets/images/showcase/sunset2.JPG  # 第二张本地图片
  desc: Sunset, Inner Mongolia
- src: /assets/images/showcase/Samarqand2.JPG  # 第二张本地图片
  desc: A Thousand and One Nights, Samarkand
- src: /assets/images/showcase/Хабаровск.JPG  # 第二张本地图片
  desc: Khabarovsk, Russia
- src: /assets/images/showcase/Heavenly Lake.JPG  # 第二张本地图片
  desc: Heavenly Lake, Xinjiang
- src: /assets/images/showcase/Pingtan.JPG  # 第二张本地图片
  desc: Pingtan Island, Fujian
- src: /assets/images/showcase/8,000 meters.jpg  # 改成本地路径
  # title: Mount Everest
  desc: I saw five peaks over 8,000 meters around Mount Everest.
  link:                                  # 如果不需要跳转链接，可以留空
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
