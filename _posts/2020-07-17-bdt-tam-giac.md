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
Chứng minh:  $$|z_1 + z_2|^2 = (z_1 + z_2)(\overline{z_1} + \overline{z_2})$$  
$$= z_1.\overline{z_1} + (z_1.\overline{z_2} + z_2.\overline{z_1}) + z_2.\overline{z_2}$$  
$$ = |z_1|^2 + 2\Re {z_1.\overline{z_2}} + |z_2|^2 \leq |z_1|^2 + 2|z_1.\overline{z_2}| + |z_2|^2$$   
$$= |z_1|^2 + 2|z_1|.|\overline{z_2}| + |z_2|^2$$  
$$ = (|z_1| + |z_2|)^2 \Rightarrow |z_1 + z_2| \leq |z_1| + |z_2|$$  
Áp dụng bất đẳng thức vừa chứng minh ở trên thay $z_1$$ bởi $$z_1 + z_2$$ và $$z_2$$ bởi $$-z_2$$:   
$$|z_1 + z_2| + |-z_2| \geq |z_1 + z_2 - z_2| = |z_1| \Rightarrow |z_1| - |z_2| \leq |z_1 + z_2|$$(1)  
Vì vai trò của $$z_1$$ và $$z_2$$ là như nhau nên $$|z_2| - |z_1| \leq |z_1 + z_2|$$(2)  
Từ (1) và (2) $$\Rightarrow$$ $$||z_1| - |z_2|| \leq |z_1 + z_2|$$  
**Dấu đẳng thức xảy ra khi và chỉ khi $$Re {z_1.\overline{z_2} = |z_1.\overline{z_2}|$$ hay z_1.\overline{z_2} là một số thực không âm($$z_1.\overline{z_2} \geq 0)**
