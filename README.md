# Осциллятор Дуффинга

В данной работе проводится качественный анализ свойств нелинейного осциллятора Дуффинга. Первая часть посвящена колебаниям без вынуждающей силы. Уравнение в таком случае принимает вид:

<p align="center">
    <img src="http://latex.codecogs.com/gif.latex?%5Cddot%7Bx%7D%20&plus;%20%5Cbeta%20%5Cdot%7Bx%7D%20&plus;%20%5Comega%20x%20&plus;%20k%20x%5E3%20%3D%200">
</p>

Рассморены положения равновесия как консервативной системы, так и системы при наличии диссипации. Каждая из визуализаций анимирована и позволяет отследить изменения типа положения равновесия при изменении одного из параметров:

<table style="width:100%" border="0">
  <tr>
    <th><img src="./img/0.png" height="200px" align="right"></th>
    <th><img src="./img/1.png" height="200px" align="left"></th>
  </tr>
</table>

Наиболее интересные свойства данного уравнения появляются при добавлении вынуждающей силы:

<p align="center">
    <img src="http://latex.codecogs.com/gif.latex?%5Cddot%7Bx%7D%20&plus;%20%5Cbeta%20%5Cdot%7Bx%7D%20&plus;%20%5Comega%20x%20&plus;%20k%20x%5E3%20%3D%20f%20cos%28%5COmega%20t%29">
</p>

Наглядно показано явление удвоения прериода, построено сечение Пупнкаре и бифуркационная диаграмма. Все материалы, а также исходный код находятся в [duffing.nb](https://github.com/krashkov/DuffingOscillator/blob/master/duffing.nb).

<table style="width:100%" border="0">
  <tr>
    <th><img src="./img/2.png" height="200px" align="right"></th>
    <th><img src="./img/3.png" height="200px" align="middle"></th>
    <th><img src="./img/4.png" height="200px" align="left"></th>
  </tr>
</table>
