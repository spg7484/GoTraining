# Exercise 3.6
superSampling is a technique to reduce the effect of pixelation by computing the color value at several points within each pixel and taking the average. The simplest method is to divide each pixel into four "subpixels". Implement it. 

---
# 練習問題 3.6
スーパーサンプリング(supersampling)は、個々の画素内の複数の点のカラー値を計算して平均を求めることでピクセル化の影響を薄める技法です。最も単純な方法は、個々の画素を4つの「サブピクセル」へ分割することです。その方法を実装しなさい。



# Result

````sh
$  go run superSampling.go > ss.png
````

![SuperSampling for mandelbrot](./ss.png)
