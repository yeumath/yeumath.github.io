---
layout: post
title: Số phức(phần 1) Giới thiệu về số phức
date: 2020-07-14 12:48:00
author: Nikola Tesla
summary: Số phức cơ bản phần 1
categories: Số phức
tags: 
  - Đại số
  - Số phức
---

Chào các bạn, đây là bài đầu tiên trong chuỗi bài về số phức. Trong bài này mình sẽ giới thiệu số phức là gì, lịch sử hình thành số phức và những ứng dụng của nó.
## 1. Lịch sử hình thành số phức:
Số phức xuất hiện lần đầu vào thế kỉ XVI khi [Niccolò Fontana Tartaglia](https://vi.wikipedia.org/wiki/Niccolo_Fontana_Tartaglia)
và [Gerolamo Cardano](https://vi.wikipedia.org/wiki/Gerolamo_Cardano) nghiên cứu về các phương trình bậc 3. Tartaglia đã đưa ra công thức nghiệm của phương trình $$x^3 = x$$ là
$$\frac{1}{\sqrt3}((\sqrt{-1})^{1 \over 3}+(\sqrt{-1})^{-1 \over 3})$$ và rõ ràng phương trình trên có 3 nghiệm 0, 1 và -1. Do đó [Rafael Bombelli](https://en.wikipedia.org/wiki/Rafael_Bombelli) đã đưa ra khái niệm căn bậc hai của -1 để giải quyết vấn đề trên và gọi nó là số ảo. Mãi đến thế kỉ XVIII, bằng những kĩ thuật tính toán khéo léo với số phức, [Leonhard Euler](https://vi.wikipedia.org/wiki/Leonhard_Euler) đã giải được nhiều bài toán khó. Nhờ việc biểu diễn số phức như là 1 điểm trong mặt phẳng mà [Carl Friedrich Gauß](https://vi.wikipedia.org/wiki/Carl_Friedrich_Gau%C3%9F) đã đạt được nhiều kết quả quan trọng trong lí thuyết số. Cùng thời còn có [Augustin-Louis Cauchy](https://vi.wikipedia.org/wiki/Augustin-Louis_Cauchy) nghiên cứu về phép tính vi phân và tích phân với các biến phức. Đây là khởi điểm cho công trình về các hàm Elliptic của [N.H. Abel](https://vi.wikipedia.org/wiki/Niels_Henrik_Abel) và [C.G.J.Jacobi](https://vi.wikipedia.org/wiki/Carl_Gustav_Jakob_Jacobi). Ngoài ra sự phát triển của hình học xạ ảnh đã cho thấy những ứng dụng to lớn của số phức.
## 2. Biểu diễn số phức:
Để biểu diễn cho $$\sqrt{-1}$$ ta dùng kí hiệu $$i$$. Vì vậy số phức là những số có dạng $$z = a + bi$$ với $$a, b$$ là các số thực, a được gọi là phần thực kí hiệu là $$\Ree z$$, b được gọi là phần ảo kí hiệu là $$\Imm z$$. Khi b = 0 thì z là số thực, khi a = 0 thì z = bi được gọi là số thuần ảo. Tập hợp các số phức được kí hiệu là $$\Bbb C$$.
Việc tính toán với số phức cũng tương tự như khi tính toán với số thực(chú ý thay $$i^2  =-1$$)
$$(a + bi) \pm (c + di) = (a \pm c) + (b \pm d)i$$
$$(a + bi).(c + di) = ac + adi + bci + bdi^2$$ $$= (ac - bd) + (ad + bc)i$$

$$\frac{a + bi}{c + di} = \frac{(a + bi)(c - di)}{(c - di)(c + di)} = \frac{ac + bd}{c^2 + d^2} + \frac{bc - ad}{c^2 + d^2}i$$
