# Методы вычислений  ММФ НГУ 2018/2019

## Задачи
 1.Решение задачи Коши для обыкновенного дифференциального уравнения первого порядка

<img src="https://tex.s2cms.ru/svg/%5Cfrac%7Bdu%7D%7Bdt%7D%20%20%5C%3A%20%3D%20%20%5C%3A%20f(x%2C%5C%2Cu(x))%5C%2C%2C%5C%3A%20x%5C%2C_0%20%3C%20x%20%5Cle%20x%5C%2C_N%2C" alt="\frac{du}{dt}  \: =  \: f(x,\,u(x))\,,\: x\,_0 &lt; x \le x\,_N," />
<img src="https://tex.s2cms.ru/svg/%20u(x%5C%2C_0)%20%5C%2C%20%3D%20%5C%2C%20y%5C%2C_0" alt=" u(x\,_0) \, = \, y\,_0" /> 

 методами Эйлера, Адамса, предиктор-корректор, Адамса-Бэшфорта-Моултона, Рунге-Кутты, Гира. 
 
 2.Решение задачи Дирихле для для уравнения теплопроводности 

<img src="https://tex.s2cms.ru/svg/%5Cfrac%7B%5Cpartial%20u%7D%7B%5Cpartial%20t%7D%20%5C%3A%20%3D%20%5C%3A%20a%5Cfrac%7B%5Cpartial%5E2%20u%7D%7B%5Cpartial%5E2%20x%7D%20%5C%3A%20%2B%20%20%5C%3A%20f(x%2C%5C%2Ct)%5C%2C%2C%20%5C%3A%200%20%3C%20x%20%3C%201%2C%20%5C%3A%200%20%3C%20t%20%5Cle%201%2C" alt="\frac{\partial u}{\partial t} \: = \: a\frac{\partial^2 u}{\partial^2 x} \: +  \: f(x,\,t)\,, \: 0 &lt; x &lt; 1, \: 0 &lt; t \le 1," />

<img src="https://tex.s2cms.ru/svg/%20%20%5Cquad%20u(x%2C%5C%2C0)%20%5C%3A%20%3D%20%5C%3A%20%5Cmu(x)%2C%20%5C%3A%20x%20%5C%2C%20%5Cin%20%5C%2C%20%5B0%2C%20%5C%2C%201%5D%2C" alt="  \quad u(x,\,0) \: = \: \mu(x), \: x \, \in \, [0, \, 1]," /> 

<img src="https://tex.s2cms.ru/svg/%20u(0%2C%5C%2Ct)%20%5C%3A%20%3D%20%5C%3A%20%5Cmu_1(t)%2C%20%5Cquad%20u(1%2C%5C%2Ct)%20%5C%3A%20%3D%20%5C%3A%20%5Cmu_2(t)%20%5C%2C%2C%20%5C%3A%20t%20%5C%2C%20%5Cin%20%20%5C%2C%20%5B0%2C%20%5C%2C%201%5D%20" alt=" u(0,\,t) \: = \: \mu_1(t), \quad u(1,\,t) \: = \: \mu_2(t) \,, \: t \, \in  \, [0, \, 1] " />

<img src="https://tex.s2cms.ru/svg/%20a%20%5C%3A%20%3D%200.017%5C%2C%2C%20%0A%20%5Cquad%20u(x%2Ct)%20%5C%3A%20%3D%20%5C%3A%20-x%5E4%20%5C%3A%20%2B%20%5C%3A%20tx%20%5C%3A%20%2B%20t%5E2%20%5C%3A%20-%20te%5Ex.%20" alt=" a \: = 0.017\,, 
 \quad u(x,t) \: = \: -x^4 \: + \: tx \: + t^2 \: - te^x. " />

Схема Кранка-Николсона:

<img src="https://tex.s2cms.ru/svg/%20%5Cfrac%7Bu%5E%7Bj%2B1%7D_k%20%5C%3A%20-%20%5C%3A%20u%5Ej_k%7D%7B%5Ctau%7D%20%5C%3A%20%3D%20%5C%3A%20a%5CBiggl(%5Cfrac%7Bu%5E%7Bj%2B1%7D_%7Bk%2B1%7D%20%5C%3A%20-%20%5C%3A%202u%5E%7Bj%2B1%7D_%7Bk%7D%20%5C%3A%20%2B%20%5C%3A%20u%5E%7Bj%2B1%7D_%7Bk-1%7D%7D%7B2h%5E2%7D%20%2B%20%5C%3A%20%5Cfrac%7Bu%5E%7Bj%7D_%7Bk%2B1%7D%20%5C%3A%20-%20%5C%3A%202u%5E%7Bj%7D_%7Bk%7D%20%5C%3A%20%2B%20%5C%3A%20u%5E%7Bj%7D_%7Bk-1%7D%7D%7B2h%5E2%7D%20%5CBiggr)%20%5C%3A%20%2B%20%5C%3A%20f%5E%7Bj%2B1%7D_k%20%5C%3A%20%5Ccdot" alt=" \frac{u^{j+1}_k \: - \: u^j_k}{\tau} \: = \: a\Biggl(\frac{u^{j+1}_{k+1} \: - \: 2u^{j+1}_{k} \: + \: u^{j+1}_{k-1}}{2h^2} + \: \frac{u^{j}_{k+1} \: - \: 2u^{j}_{k} \: + \: u^{j}_{k-1}}{2h^2} \Biggr) \: + \: f^{j+1}_k \: \cdot" />
 
 
 3.Решение задачи Дирихле для для уравнения переноса 

<img src="https://tex.s2cms.ru/svg/%20%5Cfrac%7B%5Cpartial%20u%7D%7B%5Cpartial%20t%7D%20%5C%3A%20%2B%20%5C%3A%20a%5Cfrac%7B%5Cpartial%20u%7D%7B%5Cpartial%20t%7D%20%5C%2C%20%3D%20%5C%2C%20f(x%2C%20%5C%2C%20t)%2C%20%5Cquad%200%20%3C%20x%20%5Cle%201%2C%20%5Cquad%200%20%3C%20t%20%5Cle%201%2C%20%5Cquad%20a%20%5C%3A%20%3E%20%5C%3A%200" alt=" \frac{\partial u}{\partial t} \: + \: a\frac{\partial u}{\partial t} \, = \, f(x, \, t), \quad 0 &lt; x \le 1, \quad 0 &lt; t \le 1, \quad a \: &gt; \: 0" />

<img src="https://tex.s2cms.ru/svg/%20u(x%2C%5C%2C0)%20%5C%2C%20%3D%20%5C%2C%20%5Cvarphi(x)%2C%20%5C%3A%20x%20%5C%2C%20%5Cin%20%5C%2C%20%5B0%2C%20%5C%2C%201%5D%2C" alt=" u(x,\,0) \, = \, \varphi(x), \: x \, \in \, [0, \, 1]," /> 

<img src="https://tex.s2cms.ru/svg/%20u(0%2C%5C%2Ct)%20%5C%2C%20%3D%20%5C%2C%20g_1(t)%2C%20%5C%3A%20t%20%5C%2C%20%5Cin%20%20%5C%2C%20%5B0%2C%20%5C%2C%201%5D.%20%20" alt=" u(0,\,t) \, = \, g_1(t), \: t \, \in  \, [0, \, 1].  " />

<img src="https://tex.s2cms.ru/svg/%20a%20%5C%2C%20%3D%20%5C%2C%200.26%5C%2C%2C%20u(x%2C%20%5C%2C%20t)%20%5C%2C%20%3D%20%5C%2C%20%5Ccos(%5Cpi%20x)%20%5C%2C%20-%20%5C%2C%20%5Csin(2%5Cpi%20t)%2F2%20%5C%2C%20%2B%20%5C%2C%202%5Cpi%20x%20%5C%2C%20-%20%5C%2C%203.5t." alt=" a \, = \, 0.26\,, u(x, \, t) \, = \, \cos(\pi x) \, - \, \sin(2\pi t)/2 \, + \, 2\pi x \, - \, 3.5t." />

Неявная схема бегущего счёта:

<img src="https://tex.s2cms.ru/svg/%20%5Cfrac%7BU%5E%7Bn%2B1%7D_j%20-%20U%5En_j%7D%7B%5Ctau%7D%20%5C%2C%20%2B%20%5C%2C%20a%5Cfrac%7BU%5E%7Bn%2B1%7D_j%20%5C%2C%20-%20%5C%2C%20U%5E%7Bn%2B1%7D_%7Bj-1%7D%20%7D%7Bh%7D%20%5C%2C%20%3D%20%5C%2C%20f%5E%7Bn%2B1%7D_j%5C%2C%2C%20%5C%3A%20j%20%5C%2C%20%3D%20%5C%2C%20%5Coverline%7B1%2C%20%5C%2C%20M%7D%5C%2C%2C" alt=" \frac{U^{n+1}_j - U^n_j}{\tau} \, + \, a\frac{U^{n+1}_j \, - \, U^{n+1}_{j-1} }{h} \, = \, f^{n+1}_j\,, \: j \, = \, \overline{1, \, M}\,," />

<img src="https://tex.s2cms.ru/svg/%20%5C%3A%20U_0%5E%7Bn%2B1%7D%20%5C%2C%20%3D%20%5C%2C%20g_1%5E%7Bn%2B1%7D." alt=" \: U_0^{n+1} \, = \, g_1^{n+1}." />
 
 4.Решение задачи Дирихле для уравнения Лапласа 

<img src="https://tex.s2cms.ru/svg/%20-a%5Cfrac%7B%5Cpartial%5E2%20u%7D%7B%5Cpartial%5E2%20x%7D%20%5C%3A%20-%20%5C%3A%20b%5Cfrac%7B%5Cpartial%5E2%20u%7D%7B%5Cpartial%5E2%20y%7D%20%5C%3A%20%3D%20%5C%3A%20f(x%2C%5C%2Cy)%20%5C%2C%2C%5C%3A%20x%5C%2C%2C%20y%20%5C%2C%20%5Cin%20%20%5C%2C%20D%5C%2C%2C%0Au%7C_%5CGamma%20%5C%3A%20%3D%20%5C%3A%20%5Cvarphi(x%2C%5C%2Cy)%20%5C%2C%2C%5C%3A%20x%5C%2C%2C%20y%20%5C%2C%20%5Cin%20%20%5C%2C%20%5Cpartial%20D%5C%2C%20" alt=" -a\frac{\partial^2 u}{\partial^2 x} \: - \: b\frac{\partial^2 u}{\partial^2 y} \: = \: f(x,\,y) \,,\: x\,, y \, \in  \, D\,,
u|_\Gamma \: = \: \varphi(x,\,y) \,,\: x\,, y \, \in  \, \partial D\, " />

<img src="https://tex.s2cms.ru/svg/a%20%5C%3A%20%3D%5C%3A1.2%5C%2C%2C%20%5C%3A%20b%20%5C%3A%20%3D%20%5C%3A%200.9%5C%2C%2C%20%5C%3A%20u%20%3D%20y%5E2sin(x)%20%2B%20xe%5Ey%20%5C%3A-%5C%3A1%20" alt="a \: =\:1.2\,, \: b \: = \: 0.9\,, \: u = y^2sin(x) + xe^y \:-\:1 " />

методом верхней релаксации используя 5-и точечную схему <img src="https://tex.s2cms.ru/svg/%20(A%5Ehu)_%7Bij%7D%20%5C%3A%20%3D%20%5C%3A%20f_%7Bij%7D%3A" alt=" (A^hu)_{ij} \: = \: f_{ij}:" />

<img src="https://tex.s2cms.ru/svg/%20-a%5Cfrac%7Bu_%7Bi-1%2Cj%7D%20%5C%3A%20-%20%5C%3A%202u_%7Bi%2Cj%7D%20%5C%3A%20%2B%20%5C%3A%20u_%7Bi%2B1%2Cj%7D%7D%7B2h%5E2%7D%20%5C%3A%20-%20%5C%3A%20b%5Cfrac%7Bu_%7Bi%2Cj-1%7D%20%5C%3A%20-%20%5C%3A%202u_%7Bi%2Cj%7D%20%5C%3A%20%2B%20%5C%3A%20u_%7Bi%2Cj%2B1%7D%7D%7B2h%5E2%7D%20%5C%3A%20%3D%20%5C%3A%20f_%7Bij%7D" alt=" -a\frac{u_{i-1,j} \: - \: 2u_{i,j} \: + \: u_{i+1,j}}{2h^2} \: - \: b\frac{u_{i,j-1} \: - \: 2u_{i,j} \: + \: u_{i,j+1}}{2h^2} \: = \: f_{ij}" />

 Нахождение наименьшего и наибольшего собственных значений <img src="https://tex.s2cms.ru/svg/A%5Eh" alt="A^h" /> методом Люстерника.
 
 
 ## Requirements
 Python 3 with NumPy, matplotlib
