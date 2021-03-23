---
permalink: /maths/vector
---
# Vektè

Nou ka sèvi ak eksalè pou mezire kèk grandè fizik tankou longè, mas, tan elatriye.  Men gen bagay nou pa ka rive fè ak eskalè sèlman .

Imajine nou nan yon pyès kay, epi atè a kouvri ak kawo seramik, oubyen mozayik. Kijan ou ta di yon moun ki kote yon bagay ye nan pyès sa a? Ki kote **A**, **B** ak **C** ye ?

![Imaj plizyè pwen nan yon kadriyaj](/assets/vector/pozisyon.png)

Pou nou ka bay pozisyon wonn koulè yo, nou ka konte kawo pou sòti nan yon pozisyon pou nou rive nan yon lòt pozisyon. Men pou nou ka bay pozisyon ki klè pou tout moun , nou oblije mete nou dakò sou kèk bagay: 

- Fòk ou chwazi yon kote pou w kòmanse konte (yo rele sa yon **orijin**)
- Fòk ou chwazi yon non pou direksyon yo ak nan ki sans pou nou konte
- Fòk ou defini nan ki inite w ap konte (egzanp, yon kawo ka vo 2 inite oubyen se 5 kawo ki bay yon inite),

Fizisyen yo ka rele sa yon **referansyèl**. N ap tounen sou sa pita.

![Imaj plizyè pwen nan yon kadriyaj](/assets/vector/pozisyon_referans.png)

Nan desen sa a nou wè nou ranje kò nou, pou nou byen defini pozisyon yo.

- Nou chwazi yon orijin: **kawo ki gen wonn ki nwa a.**
- Nou chwazi **2 direksyon**: Devan-Dèyè (vètikal) , Gòch-Dwat (orizontal).
- Nou chwazi nan ki sans pou nou konte: Devan, ak Dwat
- Nou chwazi inite nou: N ap konte an kawo.

Ak definisyon sa yo nou ka bay pozisyon tout bagay nan pyès la :

- Wonn **ble a**: 2 Devan, 5 Dwat
- Wonn **wouj la**: 9 Devan, 8 Dwat
- Wonn **vèt la** : 7 Devan, 3 Dwat

Fòk nou remake di **2 Devan, 5 Dwat** se menm bagay ak di **5 Dwat, 2 Devan**.

Si nou pran kòm konvansyon pou di chif **dwat** an premye epi chif **devan** an dezyèm, nan notasyon matematik nou t a ka bay pozisyon wonn ble  a konsa:

$$\begin{bmatrix} 5 \\ 2 \end{bmatrix}$$

Gwoup de chif sa yo (ki se eskalè) reprezante direkyon ak distans **wonn ble** a pa rapò ak **wonn nwa** a. Yo rele group chif sa, **kowòdone pwen** A, nan referansyel nou chwazi a.

Kòm nou nan matematik, an nou mete tèt nou nan yon kad ki pi jeneral. N ap rele direksyon dwat la x, epi direksyon devan an y, epi n ap rele pozisyon wonn ble a **A**. Nou ka itilize reprezantayon ki trè kouran kay fizisyen yo ak matematisyen yo.

![Desen vektè nan yon baz vektoryel X, Y](/assets/vector/vektè_xy.png)

Lè nou pale de pozisyon, an matematik nou rele sa pwen. Nan chema sa a nou ka wè 4 wonn koulè ki reprezante 4 pwen : **O**, **A**, **B** ak **C**.

Si nou nan pozisyon **O**, pou nou ale nan pozisyon **A**, fòk nou fè yon deplasman ki reprezante sou chema a ak yon flèch ble. Flèch sa reprezante yon vektè. Yon vektè, nan kad sa a, reprezante yon grandè ak yon oryantasyon. Nan egzanp sa a se longè ak direksyon pou w mache pou w sòti nan **O** pou al nan **A**. Si nou di chif x la se li ki an premye, nou ka ekri vektè sa a konsa:

$$\overrightarrow{OA} = \begin{bmatrix} 5 \\ 2 \end{bmatrix} - \begin{bmatrix} 0 \\ 0 \end{bmatrix}$$

$$\overrightarrow{OA} = \begin{bmatrix} 5 \\ 2 \end{bmatrix}.$$

Nan imaj la nou ka wè plizyè lòt vektè (Nan egzanp sa a se deplasman depi yon pwen pou rive nan yon lòt.):

$$\overrightarrow{OB} = \begin{bmatrix} 3 \\ 7 \end{bmatrix}$$

$$\overrightarrow{OC} = \begin{bmatrix} 8 \\ 9 \end{bmatrix}$$

Si nou byen gade imaj la, nou ka wè vektè $$\overrightarrow{BC}$$ ak vektè $$\overrightarrow{OA}$$ se menm vektè a. Menm deplasman ou fè pou sòti nan **O** pou rive nan **A** a, se menm deplasman an ou fè, pou sòti nan **B** pou rive nan **C**. Nan matematik yo di $$\overrightarrow{OA}$$ ak $$\overrightarrow{BC}$$ se de vektè ekipolan menm jan an tou $$\overrightarrow{OB}$$ ak $$\overrightarrow{AC}$$ se de vektè ekipolan. Ekipolan an vle di yo gen menm longè ak menm oryantasyon.

$$\overrightarrow{BC} = \begin{bmatrix} 8 \\ 9 \end{bmatrix} - \begin{bmatrix} 3 \\ 7 \end{bmatrix} = \begin{bmatrix} 5 \\ 2 \end{bmatrix}$$

![Desen plizyè vektè](/assets/vector/anpil_vektè_xy.png)

Men sa pa fini la. Jan imaj la montre li, nou ka konbine 2 vektè, egzanp $$\overrightarrow{OA}$$ ak $$\overrightarrow{OB}$$ pou bay yon lòt vektè: $$\overrightarrow{OC}$$ . Men kijan konbinezon an mache: Ou soti nan **O** ou deplase al nan **A**(sa vle di ou mache sou 5 kawo nan direksyon x, epi ou mache 2 kawo nan direksyon y), pandan w nan **A** ou avanse sou 3 inite nan direksyon x la, epi ou deplase 7 inite nan direksyon y la . Pozisyon ou rive a se **C** (8 kawo nan direksyon x, 9 kawo nan direksyon y).

Yon bagay ki enpòtan pou note sèke konbinezon sa a pa depann de lòd nou mete vektè yo. Se sa matematisyen rele yon operasyon ki komitatif, ki pa depann de lòd. Se menmman lè n ap travay ak eskalè, adisyon an pa depann de lòd la:

2 + 3 = 5 menm jan 3 +2 = 5

Nou rele sa **adisyon vektoryèl,** e sa ki enteresan sè ke nan egzanp pou nou an, adisyon sa vini bay yon 2 adisyon eskalè.

$$\overrightarrow{OA}+ \overrightarrow{OB}= \overrightarrow{OC}$$

$$\begin{bmatrix} 5 \\2 \end{bmatrix} + \begin{bmatrix} 3 \\ 7 \end{bmatrix} = \begin{bmatrix} 8\\ 9 \end{bmatrix}$$

**Fòk nou mete aksan sou yon pwen ki ènpotan anpil**: gen yon diferans ant vektè an matematik ak konpozant yon vektè. Menm jan yon **pwen** ak **kowòdone** yon pwen nan yon referansyèl se de bagay ki diferan.

Pa egzamp si nou menm imajine menm pyès lan, men yo te mete seramik yo an dyagonal. Pozisyon pwen yo pa chanje, men jan nou ka bay kowòdone pwen an, li menm ap chanje.

![pwen_lozanj](/assets/vector/pwen_lozanj.png)

Nan premye kadriyaj lan, nou te chwazi direksyon **Dwat** ak **Devan**. Si nou chwazi yon lòt referansyèl, ak orijin nan **O**, men de lòt direksyon n ap rele **Ana** ak **Kata**. Nan referansyèl sila, kowòdone pwen yo chanje menm si pwen yo pa deplase. Si nou pran direksyon **Ana** an premye ak direksyon **Kata** an dezyèm nou ka ekri kowòdone pwen yo:

$$O=\begin{bmatrix} 0.0 \\ 0.0 \end{bmatrix},A=\begin{bmatrix} 3.5 \\ -1.5 \end{bmatrix}, B = \begin{bmatrix} 5.0 \\ 2.0 \end{bmatrix}, C = \begin{bmatrix} 8.5 \\ 0.5 \end{bmatrix}$$

Operasyon sa a pote **chanjman repè**. Se yon nosyon ki enpòtan pou yon mou k ap fè Fizik.

![anpil_vektè_lozanj](/assets/vector/anpil_vektè_lozanj.png)

Nou ka remake adisyon vektoryèl la, toujou valab nan referansyèl sa a:

$$\overrightarrow{OA}+ \overrightarrow{OB}= \overrightarrow{OC}$$

$$\begin{bmatrix}3.5 \\ -1.5 \end{bmatrix} + \begin{bmatrix} 5 \\ 2 \end{bmatrix} = \begin{bmatrix} 8.5 \\ 0.5 \end{bmatrix}$$

Sa vle di nou ka fè operasyon matematik ak vektè san nou pa bezwen konn nan ki referansyèl n ap travay. Yon vektè se yon eleman nan yon ansanm ki pote non espas vektoryèl.

Nan egzanp nou bay la, nou travay ak vektè ki genyen **2** dimansyon (2 chif) men nan matematik yon vektè ka gen nenpòt kantite dimansyon.
