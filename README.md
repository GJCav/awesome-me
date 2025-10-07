# Awesome list

this is a personal awe some list

[toc]


## Real network

> across the great wall, we can reach the world.

Clients:

* [ssr-command-client](https://github.com/TyrantLucifer/ssr-command-client): a terminal SSR client, supports speedtest. Simple to use. Suitable for linux.
* [Matsuri](https://github.com/MatsuriDayo/Matsuri): Android client for SS, SSR, vless, trojan and etc. Supports speedtest.

Server & Forwarding & Tunnel

* [gost](https://github.com/ginuerzh/gost): A toolkit of proxy, with extensive features. I just use it to forward HTTP proxy to SOCKS proxy.


Other awesome repo: [Other](https://github.com/stars/GJCav/lists/readnetwork)



## Wechat

> f**k you. ZXL

* [SharpWxDump](https://github.com/AdminTest0/SharpWxDump): find the wechatkey on the local PC



## Python

* Rich: https://github.com/Textualize/rich
  
  Display pretty content in console, such as a table, a tree, a layout and etc.
  
* ETE Toolkit: http://etetoolkit.org/

  Plot trees in python, or, use a really simple [online tools](http://mshang.ca/syntree/)
  
### 3D Meshes Processing & Visualization

**Processing**

* [PyVista](https://github.com/pyvista/pyvista): A easy-to-use wrapper on [vtk](https://vtk.org/) that enables fast visualization, which is an open source software for manipulating and displaying scientific data.
  * [fast-simplication](https://github.com/pyvista/fast-simplification): Fast Quadratic Mesh Simplification provided by PyVista.
* [Trimesh](https://trimesh.org/): A pure Python library for loading and using triangular meshes with an emphasis on watertight surfaces. It provides lots of handy functions. To convert a Trimesh mesh into pyvista, use [pyvista.wrap](https://docs.pyvista.org/api/utilities/_autosummary/pyvista.wrap.html).
* [Pytorch3d](https://pytorch3d.org/): Added here because of its popularity that many CG/CV research papers uses `Pytorch3d` to render the algorithm output. 

**Visualization**

* [ParaView](https://www.paraview.org/): Though most 3D mesh processing libraries have the ability of visualization, they require boilerplate codes, even with which, the user interaction is far from intuitive. So, I recommend to export processing results as vtk files, and then visualize them with ParaView.

