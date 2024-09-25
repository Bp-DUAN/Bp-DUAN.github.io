---
layout: default   # 使用你项目中的布局文件（例如default.html）
title: "Animations"
---

# Animations for surface diffusion
<h3> An H-shaped Box </h3>
<video style="width: 100%; max-width: 600px;" controls>
  <source src="https://raw.githubusercontent.com/Bp-DUAN/Animation_GFs/main/SDF_H_cross.mp4" type="video/mp4">
</video>

<h3> A 6-1-1 Box </h3>
<video style="width: 100%; max-width: 600px;" controls>
  <source src="https://raw.githubusercontent.com/Bp-DUAN/Animation_GFs/main/SDF_Box_1_1_6.mp4" type="video/mp4">
</video>

<style>
body {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* 每行两列 */
  gap: 20px;                             /* 视频之间的间距 */
}

h3 {
  grid-column: span 2; /* 每个标题占据两列，确保标题在单独一行 */
  text-align: center;
}
</style>

<p> In the simulations above, the Duan-Li scheme[SISC 2024] was used. </p>

# Animations for mean curvature flow

