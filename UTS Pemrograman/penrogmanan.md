1. HTML
2. CSS
3. Javascript

- html
- css
- javascript

1. italic
2. bold
3. strikethrough

_italic_

**bold**

~~strikethrough~~

_**bold italic**_

## Penurunan Persamaan Gelombang dalam bentuk diferensial

```math
y=A \sin (\omega t = kx)
```

A = amplitudo gelombang

$\omega$ = frekuensi sudut  
($\omega = 2\pi$)

### turunan pertama terhadap waktu

```math
\frac{\partial y}{\partial t} = A
\cos (\omega t-kx)\cdot \omega
\tag{1}
```
---

turunan kedua terhadap waktu:

```math
\frac{\partial^2y}{\partial t^2}= 
-A \sin(\omega t-kx)\cdot\omega^2
\tag{2}
```
---

### turuna terhadap posisi

```math
\frac{\partial y}{\partial t} = A
\cos (\omega t-kx)\cdot -k
\tag{3}
```
---

```math
\frac{\partial^2y}{\partial ^2x}= 
-A \sin(\omega t-kx)\cdot k^2
\tag{4}
```
---
```math
\frac{\frac{\partial^2y}{\partial^2t}}
{\frac{\partial^2t}{\partial x}}= 
\frac{-\omega^2 y}{-k^2y}= 
\frac{\omega}{k}
\rightarrow
\frac{1}{v^2} 
\frac{d^2y}{d^2t}= 
\frac{d^2y}{d^2x}
\tag{5}