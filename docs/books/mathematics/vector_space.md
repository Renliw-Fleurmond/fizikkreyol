---
permalink: /maths/vector_space
---

# Espas vektoryèl

Yon **espas vektoryèl** se yon ansanm (makòn) ki gen yon estrikti ki pèmèt yo fè konbinezon lineyè ak eleman l yo. Eleman nan ansanm (makòn) sa a rele [vektè]((/fizikkreyol/maths/vector)).

Nan desen ki anba a, nou ka reprezante yon vektè ki gen 2 dimansyon. Nan desen sa a, chak pwen nan desen an se yon vektè. Men nou reprezante yon vektè:

$$\vec{v} = \begin{bmatrix} 4 \\ 3 \end{bmatrix}$$

Nan ansanm vektoryèl, nou genyen yon adisyon vektoryèl ki komitatif, sa vle di lòd la pa enpòtan:

$$\vec{w} = \vec{u} + \vec{v} = \vec{v} + \vec{u}$$

Adisyon de vektè bay yon lòt vektè. Se menm adisyon nou te bay egzanp la nan paj vektè a.

$$\vec{u} + \vec{v} = \begin{bmatrix} 2.0 \\ 0.5 \end{bmatrix} + \begin{bmatrix} 1.5 \\ 2.0 \end{bmatrix} = \begin{bmatrix} 3.5 \\ 2.5 \end{bmatrix}$$

Nan yon ansanm (makòn) vektoryèl, genyen yon vektè ki spesyal, ki rele vektè nil $$\vec{0}$$. Ou mèt pran nenpot ki vektè $$\vec{v}$$ ou adisyone li avek vektè nil, lap reba ou menm vektè $$\vec{v}$$ a toujou:

$$\vec{v} + \vec{0} = \vec{0} + \vec{v} = \vec{v}$$

An algèb yon eleman konsa rele yon eleman nèt ( élement neutre en français). Nan egzanp nou ak vektè ki gen 2 dimansyon, kowòdone li se :

$$\vec{0} = \begin{bmatrix} 0 \\ 0 \end{bmatrix}$$

Nan yon ansanm (makòn) vektoryèl, nou defini yon miltiplikasyon yon vektè ak yon eskalè.

$$\vec{u} = \lambda \times \vec{v}$$

>**Nan paj sa a tout lèt ki gen yon ti flèch sou tèt yo se vektè, sa ki pa gen ti flèch la, se eskalè**.

Lè w miltipliye yon vektè ak yon eskalè, sa bay yon lòt vektè, menm jan nou ka wè nan desen ki anba a.

$$3 \times \begin{bmatrix} 1.5 \\ 1.0 \end{bmatrix} = \begin{bmatrix} 4.5 \\ 3.0 \end{bmatrix}$$

Fok nou remake ke si nou miltpliye nenpot ki vektè pa zero, rezilta bay **vektè nil**.

$$0 \times \vec{v} = \vec{0}$$

Fok nou remake ke si nou miltpliye nenpot ki vektè pa 1, rezilta bay menm vektè a.

$$1 \times \vec{v} = \vec{v}$$

Men nou pa ka miltipliye 2 vektè ansanm. Antouka nou poko defini kijan pou nou ta fè sa. Men ak miltiplikasyon eskalè e adisyon nou ka fè konbinezon 2 vektè k ap ban nou yon lòt vektè:

$$\vec{w} = a \vec{u} + b \vec{v}$$

Sa rele yon **konbinezon lineyè**.

## Baz yon espas vektoryèl

Nan yon espas vektoryèl, ou toujou ka jwen yon ti gwoup vektè (**yo rele sa yon fanmi vektè**) ki ka ba w nenpòt ki vektè w vle, ak yon konbinezon lineyè. Nou ka di li yon lòt jan: kèlkeswa vektè w pran nan espas vektoryèl la, li se yon konbinezon lineyè de fanmi vektè sa. Lè sa yo di fanmi vektè sa a **jeneratris**.

Pa egzanp si nou pran vektè $$\vec{i}$$ ak vektè $$\vec{j}$$, jan nou wè nan desen sa a nou ka ekri vektè $$\vec{v}$$ tankou yon konbinezon lineyè:

$$\vec{v} = 4 \times \vec{i} + 3 \times \vec{j}$$

Nou mèt pran tan chache nan desen an, pou nou wè si nou ka jwenn yon vektè ki pa ka ekri tankou yon konbinezon lineyè vektè $$\vec{i}$$ ak vektè $$\vec{j}$$.

M panse n ap sispèk deja, nou te ka jwenn yon lòt fanmi vektè ki ka bay nenpòt ki vektè lè n fè konbinezon lineyè . An reyalite gen yon enfinite fanmi vektè ki ka fè sa. Nou ka bay yon lòt egzanp ak menm vektè sa a.

$$\vec{v} = 3 \times \vec{k} + 1 \times \vec{l}$$

Yon fanmi vektè ka gen plis pase 2 vektè ladan li. Kidonk, nou te ka pran tou vektè sa yo $$\vec{i}$$, $$\vec{j}$$, $$\vec{k}$$ ak $$\vec{l}$$ nan yon sèl fanmi. Men fanmi sa a pa tab lib sa vle di nou te ka jwenn manm nan fanmi sa a ki ka ekri tankou konbinezon lineyè lòt manm nan fanmi an.

$$\vec{k} = 1.5 \vec{i} + 0.5 \vec{j}$$

$$\vec{l} = -0.5 \vec{i} + 1.5 \vec{j}$$

Pou yon fanmi vektè ka rele yon **baz vektoryèl**,

- Fòk fanmi an lib, sa vle di pa gen okenn manm nan fanmi an ki ka ekri tankou yon konbinezon lineyè lòt manm nan fanmi an.
- Fòk fanmi an jeneratris, sa vle di li ka bay tout vektè nan espas vektoryèl la lè n fè konbinezon.
Yon bagay enpòtan pou nou kenbe sèke nan yon espas vektoryèl gen yon enfinite kantite baz vektoryèl.

Nou ka ekri kondisyon sa yo matematikman:

|Definisyon matematik |	Esplikasyon an kreyol |
|:--------------------|:---------------------|
|Fanmi $$(\stackrel{\rightarrow}{e}_i)_{i\in \left[1,n\right]}\in E$$ se yon baz si |Si nou gade yon fanmi vektè nan ansanm E, ki genyen $$\vec{e_1}$$ , $$\vec{e_2}$$ rive nan $$\vec{e_n}$$, li se yon baz si|
| $$\alpha_i \in \mathbb{R}, \stackrel{\rightarrow}{e}_i \in E, \displaystyle \sum_{i=1}^{n}\alpha_i\stackrel{\rightarrow}{e}_i=\stackrel{\rightarrow}{0}\Longrightarrow \alpha_i=0 $$ | Pa gen okenn kobinezon lineyè nou ka fè avek yo pou ban nou vektè nil, san tout eskalè nan miliplikasyon an pa egal zero. |
| $$\forall \stackrel{\rightarrow}{u}\in E,\stackrel{\rightarrow}{u}=\displaystyle \sum_{i=1}^n{e_i\stackrel{\rightarrow}{e}_i}$$ |Tout vektè nan espas la se yon konbinezon lineyè de vektè nan fanmi sa.|

## Pwen enpòtan:

> **Dimansyon yon espas vektoryèl se kantite vektè ki genyen nan baz vektoryèl li.**

> **Kowòdone yon vektè toujou defini pa rapò ak yon baz vektoryèl**. Pa egzanp lè nou ekri ke yon vektè gen kowòdone $$\vec{v} = \begin{bmatrix} a \\ b \end{bmatrix}$$ nan baz vektoryèl ($$\vec{i}$$, $$\vec{j}$$), se menm bagay ke si nou te ekri $$\vec{v} = a  \vec{i} + b  \vec{i}$$

Nou ka bay yon **definisyon matematik yon espas vektoryèl**

Si n gen yon ansanm E (yon makòn E) ak yon kò $$\mathbb{K}$$ (li posib pou $$\mathbb{K}$$ se ansanm reyèl yo $$\mathbb{R}$$ oubyen ansanm konplèks yo $$\mathbb{C}$$). Eleman nan kò a se eskalè. Ansanm E sa a se yon espas vektoryèl si lè n asosye l ak lwa adisyon an (+) li se yon gwoup komitatif  epi li verifye kondisyon sa yo:

Si n pran $$(\overrightarrow{u}, \overrightarrow{v})\in E$$ ak $$(\lambda, \mu)\in \mathbb{K}$$, n ap genyen:

- $$\lambda(\stackrel{\rightarrow}{u}+\stackrel{\rightarrow}{v})=\lambda\stackrel{\rightarrow}{u}+ \lambda\stackrel{\rightarrow}{v}$$
- $$(\lambda + \mu)\stackrel{\rightarrow}{u}= \lambda\stackrel{\rightarrow}{u}+\mu\stackrel{\rightarrow}{u}$$
- $$\lambda(\mu\stackrel{\rightarrow}{u})=(\lambda\,\mu)\stackrel{\rightarrow}{u}$$
- $$1\stackrel{\rightarrow}{u}=\stackrel{\rightarrow}{u}$$

Men gen operasyon matematik ki manke, kijan nou ka pa egzamp konpare 2 vektè ? Si nou travay ak vektè , kijan nou ka kalkile longè yo ? Nou ka eseye reponn kesyon sa yo avek yon lòt operasyon matematik ki rele [pwodwi eskalè](/fizikkreyol/maths/dot_product).

