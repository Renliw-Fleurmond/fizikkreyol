---
permalink: /maths/affine_space
previous: /maths/euclidean_space
next: /maths/linear_application
---
# Espas afin

Nan jewometri yo defini **espas afin** apati yon [espas vektoryèl](/fizikkreyol/maths/vector_space) sou yon kò.

Na majorite ka pratik, se kò nonb reyèl yo, $$\mathbb{R}$$.

Eleman nan yon espas afin pote non **pwen**.

> Nan imaj ki anba nou ka wè 4 pwen: **O**, **A**, **B**  ak **C**

![Desen plizyè vektè](/fizikkreyol/assets/vector/anpil_vektè_xy.png)

Nan jewometri, nosyon espas afin nan jeneralize nosyon espas nou jwenn nan jewometri Eklid la. 

Si nou genyen yon espas vektoryèl E sou yon kò $$\mathbb{K}$$, yon espas **afin** ki gen direksyon E se yon ansanm **$$\mathcal{E}$$** ki pa vid, ki gen yon mwayen pou l asosye chak **bipwen** (*group de 2 pwen*) $$(A,B)\in \mathcal{E}^2$$ ak yon vektè nan E:

$$(A,B) \in \mathcal{E}^2 \longrightarrow  \overrightarrow{AB} \in E$$

Kidonk, si $$(A,B,C)\in \mathcal{E}^3$$, nou dwe genyen:

- $$ \overrightarrow{AB}=- \overrightarrow{BA}$$
- $$\overrightarrow{AC}= \overrightarrow{AB}+ \overrightarrow{BC}$$

- Depi nou plase yon pwen **O** nan $$\mathcal{E}$$, si nou pran yon vektè $$\overrightarrow{v}$$ nan E, ap toujou gen yon lot pwen nan $$\mathcal{E}$$, ke nou ka rele A, ki ap verifye ekwasyon sa: $$\overrightarrow{OA}= \overrightarrow{v}$$
Nou ka ekri menm fraz sa yon jan ki pi kout:
$$O \in \mathcal{E},\ \stackrel{\rightarrow}{v} \in E,\ \exists A\in \mathcal{E}$$ ki fè nou genyen $$\overrightarrow{OA}= \overrightarrow{v}$$

Nou te entwodwi nosyon sa yo lè nou te komanse pale de [vektè](/fizikkreyol/maths/vector).

Pa konvansyon, yo souvan rele **O**, pwen ki non orijin referansyèl ke nou chwazi an.

Yon referansyèl, nan yon espas afin, se:
- Yon baz vektoryèl nan yon [espas vektoryèl](/fizikkreyol/maths/vector_space)
- Plis yon pwen nan espas afin lan

Yon espas afin eklidyen se yon espas afin ki gen yon [espas vektoryèl eklidyen](/fizikkreyol/maths/euclidean_space) pou direksyon.
 Lè sa a, nou vin gen yon **distans** sou espas afin $$\mathcal{E}$$ a.

## Distans

Nan langaj nou yon distans se longè ki separe de kote. Nan yon espas afin, se ta longè ki separe 2 **pwen**.


Men definisyon matematik li pi jeneral.

Yon **distans** nan sans matematik. sou yon espas **E** la se yon fonksyon ki defini sou $$E \times E$$, ki bay yon eskalè ki positif, e ki gen karakteristik sa yo:

| Non    | Ekwasyon | Esplikasyon |
|--------|:---------|:------------|
|**Simetri** | $$ \forall (A, B) \in E^2: d(A, B) = d(B, A)$$| Distans nan mitan A ak B, se menm nan mitan B ak A |
|**Separasyon**| $$ \forall (A, B) \in E^2: d(A, B) = 0 \implies A = B$$ | Depi distans A ak B bay zero, sa vle di A ak B yo se menm|
|**Inegalite tryangilè** | $$ \forall (A, B, C) \in E^3: d(A, C) <= d(A,B) + d(B, C)$$ | Distan nan mitan 2 eleman A ak B pa janm pi gran ke distans A ak nenpot ki eleman C, plis distans nan mitan B ak C |

Si nou gade imaj ki anba a nou wè, ke definisyon distans nan langaj kouran an, ranpli tout kondisyon sa yo

![distans_nan_mitan_pwen](/fizikkreyol/assets/affine/distans.png)

Men gen lòt fonksyon ki ranpli menm kondisyon sa yo, ke nou pap abòde isit la. Nou ka sèvi ak [pwodwi  eskalè](/fizikkreyol/maths/dot_product) pou nou ekri yon fonksyon ki ranpli tout kondisyon nou site yo. Fonksyon sa rele **distans ekildyènn**:

$$(A,B)\in \mathcal{E}^2, d(A,B)=\left\|\overrightarrow{AB}\right\| =  \sqrt{ \overrightarrow{AB} \cdot \overrightarrow{AB}} $$


> **Not**: An fizik nou travay anpil ak espas ki gen 2 ou byen 3 dimansyon. Paske nou kwè ke monn nap viv la gen 3 dimansyon. Depi yon fizisyen pale ou de espas, gen anpil chans ke li ap pale de yon espas tridimansyonèl.

