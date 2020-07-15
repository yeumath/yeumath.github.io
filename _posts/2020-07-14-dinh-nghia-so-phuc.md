---
layout: post
title: Số phức(phần 2) Định nghĩa số phức (Definition of Complex Numbers)
date: 2020-07-14 20:15:00
author: Nikola Tesla
summary: Số phức cơ bản phần 2
categories: Algebra
tags: 
  - Đại số
  - Số phức
---

Ở phần 1 chúng ta biết rằng các phép toán với số phức tương tự các phép toán với số thực. Nhưng tại sao lại có điều này ? Chúng ta sẽ xây dựng số phức một cách chặt chẽ, từ đó
chúng ta sẽ có câu trả lời cho câu hỏi trên.
## 1.Nhắc lại các tính chất của tập số thực $$\Bbb R$$:
### 1.1.Các tính chất liên quan đến phép cộng:
a) Tính giao hoán (Commutative law):  
$$a + b = b + a$$ với mọi $$a, b \in \Bbb R$$  
b) Tính kết hợp (Associative law): $$(a + b) + c = a + (b + c)$$ với mọi $$a, b, c \in \Bbb R$$  
c) Phần tử đơn vị (Additive identity): Tồn tại duy nhất một số thực kí hiệu là $$0$$ thỏa mãn tính chất: $$a + 0 = 0 + a = a$$ với mọi số $$a \in \Bbb R$$  
d) Phần tử đối (Additive inverse): Với mọi số thực $$a$$ tồn tại duy nhất một số thực $$x$$ thỏa mãn: $$a + x = x + a = 0$$, số thực $$x$$ này được kí hiệu là $$-a$$.  
### 1.2.Các tính chất liên quan đến phép nhân:
a) Tính giao hoán (Commutative law):
$$ab = ba$$ với mọi $$a, b \in \Bbb R$$  
b) Tính kết hợp (Associative law): $$(ab)c = a(bc)$$ với mọi $$a, b, c \in \Bbb R$$  
c) Phần tử đơn vị (Additive identity): Tồn tại duy nhất một số thực kí hiệu là $$1$$ thỏa mãn tính chất: $$a.1 = 1.a = a$$ với mọi số $$a \in \Bbb R$$  
d) Phần tử đối (Additive inverse): Với mọi số thực $$a \neq 0$$ tồn tại duy nhất một số thực $$x$$ thỏa mãn: $$ax = xa = 1$$, số thực $$x$$ này được kí hiệu là $$a^-1$$ hay $$\frac{1}{a}$$.  
e) Tính chất phân phối (Distributive law): $$a(b + c) = ab + ac$$ với mọi $$a, b, c \in \Bbb R$$  
Mọi tập hợp thỏa mãn các tính chất trên được gọi là một *trường(field)*, vậy nên $$\Bbb R$$ là một *trường*. Tương tự $$\Bbb Q$$ cũng là một *trường*. Nhưng $$\Bbb N$$ và $$\Bbb Z$$ không phải là một *trường*.  
## 2. Xây dựng số phức:
Một số phức là một cặp có thứ tự các số thực $$(a, b)$$ thỏa mãn các tính chất sau đây: Hai cặp $$(a, b)$$ và $$(c, d)$$ bằng nhau khi và chỉ khi $$a = c$$ và $$b = d$$. Tổng và tích của hai số phức $$(a, b)$$ và $$(c, d)$$ được định nghĩa như sau:  
$$(a, b) + (c, d) = (a + c, b + d)$$  
$$(a, b).(c, d) = (ac - bd, bc + ad)$$  
Từ định nghĩa về hai số phức bằng nhau ta có các tính chất sau:  
a) Tính phản xạ (Reflexive): $$(a, b) = (b, a)$$ với mọi số phức $$(a, b)$$  
b) Tính đối xứng $$(a, b) = (c, d)$$ tương đương với $$(c, d) = (a, b)$$  
c) Tính bắc cầu: $$(a, b) = (c, d)$$ và $$(c, d) = (e, f)$$ thì $$(a, b) = (e, f)$$  
Với các phép cộng và phép nhân được định nghĩa như trên, dễ dàng chứng minh được $$\Bbb C$$ cũng là một *trường*. Bây giờ ta sẽ xét các số phức có dạng $$(a, 0)$$:  
$$(a, 0) \pm (b, 0) = (a \pm b, 0)$$  
$$(a, 0).(b, 0) = (ab - 0.0, 0.b + a.0) = (ab, 0)$$  
$$\frac{(a, 0)}{(b, 0)} = (a, 0).(b^{-1}, 0) = (ab^{-1} - 0.0, 0.b^{-1} + a.0)$$ $$ = (ab^{-1}, 0) = (\frac{a}{b}, 0)$$ với $$(b \neq 0)$$  
Từ những tính chất trên ta có thể xem những số phức có dạng $$(a, 0)$$ như là số thực.  
Tiếp theo ta sẽ xét số phức $$(0, 1)$$:
Ta có $$(0, 1)^2 = (0, 1)(0, 1) = (-1, 0) = -1$$. Vậy nếu chúng ta kí hiệu $$(0, 1)$$ là $$i$$ thì $$i^2 = -1$$ và một số phức bất kì đều có thể viết dưới dạng sau:  
$$(a, b) = (a, 0) + (b, 0)(0, 1) = a + bi$$, $$i$$ được gọi là đơn vị ảo(*imaginary unit*).  
## 3. Số phức liên hợp: 
Số phức $$(a, -b) = a - bi$$ được gọi là *số phức liên hợp (conjugate complex number)* của số phức $$z = (a, b) = a + bi$$ và được kí hiệu là $$\overline z$$. Với hai số phức $$z_1$$ và $$z_2$$ ta có một vài tính chất sau đây:  
$$\overline{z_1} \pm \overline{z_2} = \overline{z_1 \pm z_2}$$  
$$\overline{z_1}.\overline{z_2} = \overline{z_1.z_2}$$
$$\overline{\frac{z_1}{z_2}} = \frac{\overline{z_1}}{\overline{z_2}}$$    



