---
permalink: /maths/matrix
previous: /maths/linear_application
---

# Matris ak aplikasyon lineyè

An nou konsidere yon aplikasyon lineyè $$g: E \rightarrow F$$ ki pran yon vektè nan makòn E e ki bay kòm rezilta yon vektè nan makòn F.

![represantasyon yon aplikasyon linyè](/fizikkreyol/assets/linear_application/aplikasyon_lineyè.png)

Annou konsidere $$(\vec{e}_1, \vec{e}_2)$$ yon baz vektoryèl nan E ak $$(\vec{f}_1, \vec{f}_2)$$ yon baz vektoryèl nan F.

An nou pran $$\vec{u}\in E$$, nou ka ekri:

$$\vec{u}=a \vec{e}_1 +  b\vec{e}_2 = \begin{bmatrix} a\\ b \end{bmatrix}$$

Paske $$g$$ se yon aplikasyon lineyè, nou ka ekri:

$$g(\vec{u})  = a g(\vec{e}_1) + bg(\vec{e}_2) $$

$$g(\vec{e}_1)$$ ak $$g(\vec{e}_2)$$ se 2 vektè nan makòn F. Ki donk nou ka ekri toujou:

$$g(\vec{e}_1)  = g_{11} \vec{f}_1 + g_{21} \vec{f}_2 = \begin{bmatrix} g_{11} \\ g_{21} \end{bmatrix} $$

$$g(\vec{e}_2)  = g_{12} \vec{f}_1 + g_{22} \vec{f}_2  = \begin{bmatrix} g_{12} \\ g_{22} \end{bmatrix}$$

$$g_{11}$$, $$g_{12}$$, $$g_{21}$$, $$g_{22}$$ se tout eskalè ki depann de baz vektoryèl ke nou te chwazi nan E ak F. Si nou chanje youn nan eskalè sa yo se yon lòt aplikasyon lineyè nap genyen. Ki donk 4 eskalè sa yo ka reprezante korekteman aplikasyon lineyè a.

An nou kontinye ekri $$g(\vec{u})$$. Nou genyen:

$$g(\vec{u})  = a g(\vec{e}_1) + bg(\vec{e}_2)$$

$$g(\vec{u})  = a \begin{bmatrix} g_{11}\\ g_{21} \end{bmatrix}  + b \begin{bmatrix} g_{12}\\ g_{22} \end{bmatrix}$$

Men nou ka senplifye ankò:

$$g(\vec{u}) = \begin{bmatrix} g_{11} & g_{12}\\  g_{21} & g_{22}\end{bmatrix} \begin{bmatrix} a\\ b \end{bmatrix}$$

Nou ka wè ke nou separe tout eskalè sa yo nan 2 **tablo**.
-  Tablo ki a dwat lan se kowòdone vetkè $$\vec{u}$$  avek baz vektoryel $$(\vec{e}_1, \vec{e}_2)$$  nan espas E
- Tablo ki a gòch lan se kowòdone $$g(\vec{e}_1)$$ ak $$g(\vec{e}_2)$$  avek baz vektoryèl  $$(\vec{f}_1, \vec{f}_2)$$ nan F.

**Nap rele tablo ki genyen $$g_{11}$$, $$g_{12}$$, $$g_{21}$$, $$g_{22}$$ matris aplikasyon $$g$$.**
(*Nou ka wè se matris la se yon tablo kote nou kole plizyè vektè youn ak lot.*) Matris nan egzanp sa gen 2 kolònn ak 2 liy. Epi fok nou defini yon **_miltiplikasyon adwat_** ant yon matris ak yon vektè.

> Nou mete aksan sou **adwat** paske miltipliksayon sila pa **komitatif**. Men nap esplike sa yon lòt lè.

Pou nou ka miltipliye a dwat yon matris ak yon vektè, **fòk kantite kolònn matris la egal ak kantite liy vektè a**. (*Sonje ke vetkè ka gen plis ke 2 liy*)

Nap defini miltiplikasyon a dwat matris G ak yon vektè $$\vec{v}$$ konsa:

$$\begin{bmatrix}  g_{11} & g_{12} & \dots  & g_{1n}\\ g_{21} & g_{22} & \dots  & g_{2n}\\ \vdots & \vdots & \vdots & \vdots \\ g_{k1} & g_{k2} & \dots  & g_{kn}  \end{bmatrix} \begin{bmatrix} v_1 \\ v_2 \\ \vdots \\ v_n \end{bmatrix}  =   \begin{bmatrix}  g_{11} \times v_1 + g_{12} \times v_2 + \dots  + g_{1n} \times v_n\\ g_{21} \times v_1 + g_{22} \times v_2 + \dots  + g_{2n} \times v_n \\ \vdots \\ g_{k1} \times v_1 + g_{k2} \times v_2 + \dots  + g_{kn} \times v_n  \end{bmatrix}$$

Avek definisyon sa, yon matris $$G$$ sifi pou reprezante yon aplikasyon lineyè $$g: E \rightarrow F$$ si nou gen **2 baz vektoryèl, youn nan E ak youn nan F**.

Konsa, pou n ka konnen yon aplikasyon lineyè, nou sèlman bezwen konnen imaj chak vektè nan baz la atravè aplikasyon an.

An nou pran egzanp aplikasyon lineyè sa:

![represantasyon yon aplikasyon linyè](/fizikkreyol/assets/linear_application/aplikasyon_lineyè.png)

Si nou di ke vektè **ble** a lan se imaj $$\vec{e}_1$$ ak vektè **rouj** se imaj vektè $$\vec{e}_2$$ nou ka ekri matris aplikasyon lineyè a nan baz vektoryèl sa yo:

$$g(\vec{e}_1) = 2 \vec{f}_1 + 1 \vec{f}_2 = \begin{bmatrix} 2 \\ 1 \end{bmatrix}$$

$$g(\vec{e}_2) = 1 \vec{f}_1 + 3 \vec{f}_2 = \begin{bmatrix} 1 \\ 3 \end{bmatrix}$$

Ki donk nou ka ekri matris aplikasyon lineyè a :

$$G = \begin{bmatrix} 2  & 1 \\ 1 & 3 \end{bmatrix}$$

An nou rele $$\vec{u}$$ vektè koulè **nwa** nan imaj lan, ki nan espas $$E$$:

$$ \vec{u} = \begin{bmatrix} 2 \\ 1 \end{bmatrix}$$

$$g(\vec{u}) = \begin{bmatrix} 2  & 1 \\ 1 & 3 \end{bmatrix} \begin{bmatrix} 2 \\ 1 \end{bmatrix}$$

$$g(\vec{u}) = \begin{bmatrix} 2 \times 2  + 1 \times 1 \\ 1 \times 2 + 3 \times 1 \end{bmatrix}$$

$$g(\vec{u}) = \begin{bmatrix} 5 \\ 5 \end{bmatrix}$$

Nou ka verifye ke se kowòdone vektè koulè **nwa** nan espas F.