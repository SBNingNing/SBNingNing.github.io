---
layout: plain
title: 视频
---

<video width="100%" controls>
  <!-- 使用 relative_url 以适配本地与部署路径 -->
  <source src="{{ '/assets/videos/my-video.mp4' | relative_url }}" type="video/mp4">
  您的浏览器不支持 Video 标签。
</video>
