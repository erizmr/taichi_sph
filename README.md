# 太极图形课S1-SPH 示例程序

## 背景简介
该repo实现了Weakly Compressible Smooth Particle Hydrodynamics (WCSPH) 

## 效果展示

<img src="./imgs/wcsph.gif" width="400">

|                    Color only                     |              Lambertian reflection              |                      Blinn-Phong model                       |
| :-----------------------------------------------: | :---------------------------------------------: | :----------------------------------------------------------: |
|   <img src="./img/color_only.png" width="200">    |  <img src="./img/lambertian.png" width="200">   |            <img src="./img/b_p.png" width="200">             |
|           Blinn-Phong model with shadow           |            Whitted style ray tracing            |                         Path tracing                         |
| <img src="./img/b_p_with_shadow.png" width="200"> | <img src="./img/whitted_style.png" width="200"> | <img src="./img/path_tracing_sample_on_sphere_surface.png" width="200"> |


## 运行环境

```
[Taichi] version 0.8.3, llvm 10.0.0, commit 2680dabd, linux, python 3.8.10
```

## 运行方式
`python3 demo.py`