# Books in markdown

<!-- badges: start -->

[![bookdown](https://github.com/CUG-hydro/CUG-HydroMeteorology/actions/workflows/bookdown.yaml/badge.svg?branch=master)](https://github.com/CUG-hydro/CUG-HydroMeteorology/actions/workflows/bookdown.yaml)

<!-- badges: end -->

[https://github.com/CUG-hydro/CUG-HydroMeteorology](https://github.com/CUG-hydro/CUG-HydroMeteorology)

[https://CUG-hydro.github.io/CUG-HydroMeteorology](https://CUG-hydro.github.io/CUG-HydroMeteorology)

## 实现的功能

这是一个bookdown写作模板，已经实现了如下功能：

- [X] github action自动编译代码、部署到网页。
- [X] 兼容R包的结构。`Rmarkdown`可以调用该R包中的函数。
- [X] require2自动安装和加载R包（若未安装，则 `pak::pkg_install`装之）。
- [ ] 参考文献
- [ ] 交叉引用
- [X] pandoc markdown转word

## TODO: 

### 1. 辐射与蒸发
#### 夏季撑伞与否对人体感知温度的影响
  
  > 可能用到的理论：
  > 1. **散射理论**
  > 2. **蒸发理论**：湿表面与空气的温差

### 2. 气象成因分析
#### 工具

  - `metpy`: <https://github.com/Unidata/MetPy>, <https://unidata.github.io/MetPy/latest/examples/index.html>
  - `metR`: <https://github.com/eliocamp/metR>

  #### 理论
  - 位势高度场
  - 水汽通量
  - 锋生锋消
  - Q矢量
  - 涡度守恒


# 参考文献

1. 南京大学MOOC, 气象动力学，<https://open.163.com/newview/movie/free?pid=KFTN98Q57>
