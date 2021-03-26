---
permalink: /maths/dot_product
previous: /maths/vector_space
---
# Pwodwi eksalè
An nou imajine 2 [vektè](/fizikkreyol/maths/vector) $$\vec{u}$$ ak $$\vec{v}$$, kijan nou te ka konpare yo ?
Si nou gade egzanp ki bay nan desen anba a, nou wè ke 2 vektè sa yo, al preske nan menm direksyon, menmsi nou wè gen yon ang $$\theta$$ nan mitan yo.

![ang_nan_mitan_de_vektè](/fizikkreyol/assets/dot_product/pwodwi_eskalè_definisyon.png)

Nou ka defini you fonksyon matematik ki pran 2 vektè e ki remet nou yon nomb, ki te ka eseye dekri kijan 2 vektè yo ale nan direksyon youn lot.

$$f(\vec{u}, \vec{v})$$

Si nap gade desen an, nou ka defini yon fonksyon ki se longè $$\vec{u}$$ ki ale nan sans vektè $$\vec{v}$$.

An nou ekri kom konvansyon $$\|\vec{u}\|$$ pou longè vektè $$\vec{u}$$. Si nou fè sa, nou ka ekri fonksyon an konsa:

$$f(\vec{u}, \vec{v}) =   \|\vec{u}\| \cos (\theta)$$

Men jan foksyon sa defini, nou wè ke lòd vektè a enpòtan:

$$f(\vec{u}, \vec{v}) \neq f(\vec{v}, \vec{u})$$

$$\|\vec{u}\| \cos (\theta) \neq \|\vec{v}\| \cos (\theta)$$

Pou fonksyon a pa depann de lòd la, an nou chanje fonksyon an yon ti jan, nap miltipliye pati vektè $$\vec{u}$$ ki al nan sans vektè $$\vec{v}$$ avek longè vektè $$\vec{v}$$:

$$f(\vec{u}, \vec{v}) =   \|\vec{u}\|   \|\vec{v}\|\cos (\theta)$$

Kounye a fonksyon nou an **komitatif**.

Nou ka konprann rezilta fonksyon sa tankou sifas youn nan rektang gri nan imaj ki pi ba a. Kòm fonksyon nou defini a komitatif, sa vle di sifas de rektang sa yo menm. *Pran tan pou fè konparezon ant fòmil la, ak rektang nan imaj lan.*

![entèpretasyon_pwodwi_eskalè](/fizikkreyol/assets/dot_product/pwodwi_eskalè_imaj.png)

Men si nap gade byen fonksyon nou an yon ti jan espesyal. Si nou gade 2 vektè $$\vec{a}$$ ak $$\vec{b}$$, nou ka wè ke pati vektè $$\vec{a} + \vec{b}$$ ki al nan sans vektè $$\vec{v}$$ se adisyon pati vektè $$\vec{a}$$ ki al nan sans $$\vec{v}$$ ak pati vektè $$\vec{b}$$ ki al nan sans vektè $$\vec{v}$$

![adisyon_pwodwi_eskalè](/fizikkreyol/assets/dot_product/pwodwi_eskalè_adisyon.png)

Sa ki ta vle di nou genyen (paske vektè $$\vec{v}$$ pa chanje:

$$f(\vec{a} + \vec{b}, \vec{v}) = f(\vec{a}, \vec{v}) +  f(\vec{b}, \vec{v})$$

Lè sa yo di ke fonksyon an distribiye adisyon an. Se menm karakteristik ke nou jwenn nan miltiplikasyon avek eskalè.

$$a (b + c) = ab + ac$$

An nou gade yon ka patikilye ak adisyon an:

$$f(\vec{a} + \vec{a}, \vec{v}) = f(\vec{a}, \vec{v}) +  f(\vec{a}, \vec{v}) = 2 f(\vec{a}, \vec{v}) = f(2\vec{a}, \vec{v}) $$

La nou ka sispèk ke fonksyon nou defini gen yon lòt propryete: li lineyè pa rapò ak chak vektè yo.

An nou gade pa egzanp imaj sila:

![miltiplikasyon_pwodwi_eskalè](/fizikkreyol/assets/dot_product/pwodwi_eskalè_miltiplikasyon.png)

Nou wè ke si nou militpliye yon vektè $$\vec{a}$$ avek yon eskalè $$\lambda$$ pa egzanp, pati vektè $$\lambda \vec{a}$$ ki nan menm sans ak vektè $$\vec{v}$$ egal a $$\lambda$$ fwa pati vektè $$\vec{a}$$ ki nan menm sans ak vektè $$\vec{v}$$. Ki donk fonksyon nou an ap lineyè pa rapò ak chak nan vektè yo.

Nou ka rezime fraz long sa ak yon fòmil matematik tou kout:

$$f(\lambda \vec{u}, \vec{v}) =\lambda  f( \vec{u}, \vec{v}) = f( \vec{u},  \lambda \vec{v})$$

Fonksyon nou an gen yon pakèt karakteristik miltiplikasyon genyen, nap rele fonksyon sa yon **pwodwi eskalè**. Se paske rezilta fonsksyon an se yon eskalè. Nou pral note pwodwi sa konsa:

$$f(\vec{u}, \vec{v}) =  \vec{u} \cdot \vec{v}$$

Pwodwi eskalè sa genyen yon lot seri ti karakteristik.

- Nou ka wè ke si 2 vektè pèpandikilè youn ak lòt, ang ki nan mitan yo se 90 degre, pa gen okenn vektè ki al nan sans lot, ki donk rezilta pwodwi eskalè 2 vektè sa yo bay 0.
- Pwodwi eksalè ka negatif, lè de vektè yo ap tire nan de sans difèran, menm jan lè 2 moun ap tire sou yon kòd.
- Lè nou mete vektè nil nan yon pwodwi eskalè rezila bay zero.
- Si nou fè pwodwi eskalè de menm vektè li bay longè vektè a o kare, ou byen sifas yon kare ki gen yon kote ki gen longè vektè a. $$\vec{u} \cdot \vec{u} = \|\vec{u}\|\|\vec{u}\| = {\|\vec{u}\|}^2$$

**An rezime**, pwodwi eskalè se yon fonksyon vektoryèl ki pran 2 vektè pou li bay yon eskalè. Fonskyon sa ranpli kondisyon sa yo:

- Komitativite: $$f(\stackrel{\rightarrow}{u}, \stackrel{\rightarrow}{v})=f(\stackrel{\rightarrow}{v}, \stackrel{\rightarrow}{u})$$

- Miltiplikasyon: $$f(\stackrel{\rightarrow}{u}, \lambda \stackrel{\rightarrow}{v})= \lambda f(\stackrel{\rightarrow}{u}, \stackrel{\rightarrow}{v})$$

- Adisyon: $$f(\stackrel{\rightarrow}{u}, \stackrel{\rightarrow}{v}+\stackrel{\rightarrow}{w})= f(\stackrel{\rightarrow}{u}, \stackrel{\rightarrow}{v})+f(\stackrel{\rightarrow}{u}, \stackrel{\rightarrow}{w})$$

- Prodwi eskalè ki nil: $$f(\stackrel{\rightarrow}{u}, \stackrel{\rightarrow}{u})>0$$ si $$ \stackrel{\rightarrow}{u}\neq\stackrel{\rightarrow}{0}$$ epi $$f(\stackrel{\rightarrow}{u}, \stackrel{\rightarrow}{u})=0$$ si $$\stackrel{\rightarrow}{u}=\stackrel{\rightarrow}{0}$$

- Kare eskalè: $$f(\stackrel{\rightarrow}{u},\stackrel{\rightarrow}{u}) = \|\stackrel{\rightarrow}{u}\|^2$$

- Notasyon: $$f(\stackrel{\rightarrow}{u}, \stackrel{\rightarrow}{v})=\stackrel{\rightarrow}{u} \cdot \stackrel{\rightarrow}{v}$$

Se yon zouti matematik ki itlize anpil pou defini distans, e se yon konsèp nap bezwen pou nou defini yon lòt konsèp matematik ki rele espas vektoryel eklidyen.

**Kijan nou ka kalkile yon pwodwi eskalè ?** An nou gade sa nan paj sa