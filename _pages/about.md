---
permalink: /
title: "Welcome to 618"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

　　She walks in beauty， like the night

　　她走在美的光彩中，像夜晚；

　　Of cloudless climes and starry skies

　　皎洁无云并且繁星漫天；

　　And all that's best of dark and bright

　　黑夜与白天最美妙的色彩；

　　Meet in her aspect and her eyes

　　都在她的面容和目光里显现。

![image](https://user-images.githubusercontent.com/54856248/118637147-0ea6e580-b808-11eb-80a0-82d4d2207217.png)

My Code For You
------
clc
close all
figure;
t=pi+pi/2:-0.01:pi/2;
x=1+1*cos(t);
y=-10+10*sin(t);
plot(x,y,'color',[0.2 0 0],'linewidth',3);
axis equal;
pause(0.1);
hold on;
t=0:0.01:2*pi;
x=10*cos(t);
y=3*sin(t);
for i=1:5
    hold on;
    q=[x;y];
    e=pi/5*i;
    z=[cos(e) -sin(e);sin(e) cos(e)];
    k=z*q;
    r=k(1,:);
    d=k(2,:);
    fill(r,d,'r');
    plot(r,d,'r','linewidth',5);
    axis square;  
    pause(0.1);
end
hold on;
x=3*cos(t);
y=3*sin(t);
patch(x,y,'y');
text(0,0,'618')

For more info
------
More info about configuring academicpages can be found in [the guide](http://ruanyanlin.cn/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
