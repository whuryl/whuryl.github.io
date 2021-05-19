---
permalink: /
title: "Welcome"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My best 618
------

　　If you were a teardrop;

　　In my eye,

　　For fear of losing you, I would never cry

　　And if the golden sun,

　　Should cease to shine its light,

　　Just one smile from you,

　　Would make my whole world bright.

　　——Hannah Jo Kee

![src=http___pic1 win4000 com_wallpaper_2019-07-22_5d354e82f1e0c jpg refer=http___pic1 win4000](https://user-images.githubusercontent.com/54856248/118769660-ff30a680-b8b2-11eb-955b-216230ba45a0.jpg)

Matlab codes for you
------
    f=@(x,y,z)(x.^2+ (9./4).*y.^2 + z.^2 - 1).^3 - x.^2.*z.^3 - (9./80).*y.^2.*z.^3;
    [x,y,z]=meshgrid(linspace(-3,3));
    val=f(x,y,z);
    [p,v]=isosurface(x,y,z,val,0);
    patch('faces',p,'vertices',v,'facevertexcdata',jet(size(v,1)),'facecolor','w','edgecolor','flat');
    view(3);
    grid on;
    axis equal;
