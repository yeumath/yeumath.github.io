---
layout: post
title: Số phức(phần 4) Bất đẳng thức tam giác
date: 2020-07-17 9:05:00
author: Nikola Tesla
summary: Số phức cơ bản
categories: Algebra
tags: 
  - Đại số
  - Số phức
---

Với mọi số phức $$z_1, z_2$$ ta có bất đẳng thức sau:  
$$||z_1| - |z_2|| \leq |z_1 + z_2| \leq |z_1| + |z_2|$$  
Chứng minh:  $$|z_1 + z_2|^2 = (z_1 + z_2)(\overline{z_1} + \overline{z_2}) = z_1.\overline{z_1} + (z_1.\overline{z_2} + z_2.\overline{z_1}) + z_2.\overline{z_2}$$  
$$ = |z_1|^2 + 2\Re {z_1.\overline{z_2}} + |z_2|^2 \leq |z_1|^2 + 2|z_1.\overline{z_2}| + |z_2|^2 = |z_1|^2 + 2|z_1|.|\overline{z_2}| + |z_2|^2$$  
$$ = (|z_1| + |z_2|)^2 \Rightarrow |z_1 + z_2| \leq |z_1| + |z_2|$$  
