---
permalink: /maths/dot_product_algebra
previous: /maths/dot_product
next: /maths/euclidean_space
---

# Kalkil aljebrik yon pwodwi eskalè:

Si nou konsidere yon baz vektoryel ($$\vec{i}, \vec{j}$$), si nou genyen 2 vektè $$\vec{u}$$ ak $$\vec{v}$$ ki genyen kòm kowòdone:

$$\vec{u} = a \vec{i} + b\vec{j} = \begin{bmatrix} a \\ b \end{bmatrix}$$

$$\vec{v} = x \vec{i} + y\vec{j} = \begin{bmatrix} x \\ y \end{bmatrix}$$

Lè nou itilize tout karakteristik [pwodwi eskalè](/fizikkreyol/math/dot_product) nou ka ekri:

$$\vec{u} \cdot \vec{v} = [a \vec{i} + b\vec{j}] \cdot [x \vec{i} + y\vec{j}] $$

Si nou itilize **distribitivite** pwodwi eskalè nou ka ekri: 

$$\vec{u} \cdot \vec{v} = x[ a \vec{i} + b\vec{j}] \cdot \vec{i} + y [ a \vec{i} + b\vec{j}] \cdot\vec{j}$$

$$\vec{u} \cdot \vec{v} = ax \vec{i}  \cdot \vec{i}  + bx\vec{j} \cdot \vec{i} + ay \vec{i} \cdot\vec{j} + by\vec{j} \cdot\vec{j} $$

Epi se **komitativite** pwodwi eskalè ki pèmet nou di ke $$\vec{i} \cdot \vec{j} = \vec{j} \cdot \vec{i} $$ e ki pèmèt nou rive nan fomil sa:

$$\vec{u} \cdot \vec{v} = (ax) \vec{i}  \cdot \vec{i}  + (bx + ay)\vec{i} \cdot \vec{j} + (by)\vec{j} \cdot\vec{j} $$

An jeneral (se pa tout tan), pami tout baz posib yo, yo renmen chwazi **yon baz vèktoryèl ki òtonòme**. Sa sa vle di ?
- Tout vektè nan baz lan gen yon longè ki egal ak 1. Pa egzanp si $$\vec{i}$$ gen yon longè ki egal ak yon inite nap genyen $$\vec{i}  \cdot \vec{i} = 1$$ .
- Tout vektè nan baz lan pèpandikilè ak tout lòt vektè nan baz lan . Pa egzanp si vektè $$\vec{i}$$ ak $$\vec{j}$$ pèpandikilè nap genyen $$\vec{i}  \cdot \vec{j} = 0$$ 

**Si baz vektoyel la òtonòme**, fòmil pwodi vektoryèl la tounen:

$$\vec{u} \cdot \vec{v} = (ax) \vec{i}  \cdot \vec{i}  + (bx + ay)\vec{i} \cdot \vec{j} + (by)\vec{j} \cdot\vec{j}$$

$$\vec{u} \cdot \vec{v} = (ax) \times 1  + (bx + ay) \times 0 + (by)  1 $$

$$\vec{u} \cdot \vec{v} = ax + by$$

> **Fok nou raple ke pwodwi eskalè 2 vektè pa depann de chwa [baz vektoyel](/maths/vector_space/) lan**. Isi a nou selman esplike kijan pou nou kalkile pwodwi eskalè si nou konnen kowòdone vektè yo nan yon **baz**

> Nan paj sa nou pran egzanp yon baz vektoryel ki gen 2 vektè, men nou ka fè menm kalkil sa pou yon baz ki gen 3,4,100 ou menm mil vektè.

### Rezime
Pwodwi eskalè la se yon operasyon matematik ki pran 2 vektè ki melanje yo ansanm pou bay yon eskalè.

Eskalè sa bay yon lide de kijan 2 vektè sa yo ale youn nan sans lòt (Si vektè yo te moun, nou ta di ke li bay nivo lanmitye ou lanmou nan mitan 2 vektè yo.)

Pwodwi eskalè sanble anpil avek militiplikasyon, men li pa menm bagay.

Se yon zouti matematik ki itlize anpil pou defini distans, e se yon konsèp nap bezwen pou nou defini yon lòt konsèp matematik ki rele espas vektoryel eklidyen.