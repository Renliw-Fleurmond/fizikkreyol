---
permalink: /maths/trigonometry
---

# Trigonometri

> **Trignometri se etid relasyon ki egziste nan mitan ang ak kote yon triyang**

An nou gade senp ti triyang sa :

![Desen yon tryang ak plizyè ang](/fizikkreyol/assets/trigonometry/tryang.png)

Nou wè li gen 3 ang (*Se sa ki ba li non li "tri-angle" an fransè*)

Nou wè ke ang sa yo $$\alpha$$, $$\beta$$, $$\gamma$$ yo relye youn ak lot.
Pa egzanp si $$\alpha$$ rete jan li ye a, nou ka wè ke depi nou laji $$\beta$$, $$\gamma$$ ap vin pi piti, epi kote triyang ki an fas $$\beta$$ ap vinn pi long. 

Ki relasyon genyen ant ang sa yo, ak longè kote triyang lan? Se egzakteman sa 
**trigonometri** ap etidye.

## Ang, konvansyon ak inite

Pou nou pa pèdi an nou fokis sou ang $$\alpha$$.

Si nou trase yon sèk, ke nou byen enstalè nan yon repè, nou ka defini yon **sans** (*oryantasyon*) pou yon ang.

![Nap vini ak sèk initè](/fizikkreyol/assets/trigonometry/tryang_ak_sek_initè.png)

> Sans ang ke nou montre nan imaj la rele  **sans dirèk**, lòt sans lan rele **sans endirèk** .Se yon **konvansyon**, sa vle di se yon gwoup moun ki deside rele li konsa pou yo tout ka konnen de kisa yap pale.

Nou ka wè ke pozisyon yon pwen sou sèk la depann de ang li fè. Sa vle di, ke gen yon fonksyon, ki depi nou ba li yon ang, ki ka bay yon pwen sou sèk sa.

Lè nou gade imaj lan, nou wè ke si nou kenbe ang lan, men rayon sèk la varye, longè $$l$$ koub lan ap varye pwopòsyonèlman ak reyon $$r$$ lan. Menm jan, si nou varye ang lan $$\alpha$$, men nou kenbe reyon an fiks, longè koub lan pral varye menm jan avek ang lan.

Tout sa, nou ka ekri li ak fòmil matematik:

$$l \propto r $$ 

$$l \propto \alpha$$ 

Sa ki vle di:

$$l \propto \alpha \times r \implies \alpha \propto \frac{l}{r}$$

Ang $$\alpha$$ propòsyonel ak yon rapò:  longè ki divise pa yon lòt longè. Sa vle di yon ang se pa yon longè, ni yon sifas, se yon grandè **san inite fizik**.

Pou senplifye la vi nou, nou defini yon *inite* pou ang. Inite ke yo plis itilize nan matematik se **radyan**

> Yon **radyan** se gwosè yon ang, ki bay yon **ak de sèk** ki gen menm longè ak rayon sèk lan. Yon **radyan** se gwosè yon ang, ki pou yon sèk ki gen longè $$1$$ bay yon ak de sèk ki gen longè $$1$$.

Nou ka wè tou,  ke depi nou fè yon tou konplè sèk la,  nou retounen nan menm pwen kote nou te komanse a.
 
> **Pou rezon istorik, nou defini [$$\pi$$](https://fr.wikipedia.org/wiki/Pi) kòm gwosè yon ang, ki bay yon ak de sèk ki mwatye perimèt tout sèk lan**.  Ki fè longè perimèt yon sèk se $$2\pi r$$

![Desen yon sèk initè](/fizikkreyol/assets/trigonometry/sèk_initè.png)

> $$\pi$$ se yon nonb ki gen yon pakèt istwa e li itilize anpil nan tout domèn la syans. Pou konnen plis ou ka komanse li atik [Wikipédia sa](https://fr.wikipedia.org/wiki/Pi)

## Fonksyon Sinis (*sinus* an fransè) ak Kosinis (*cosinus* an fransè)

An nou gade imaj sa 

![Definisyon Cosinis ak Sinis](/fizikkreyol/assets/trigonometry/kosinis_ak_sinis.png)

Pozisyon pwen sou sèk lan depann direkteman de ang lan. Pozisyon pwen an ka dekri avèk 2 kowòdone ki se $$x$$ ak $$y$$.

Nou wè ke de kowòdone sa yo, depann de ang $$\alpha$$. Sa pral pèmèt nou **defini** 2 fonksyon:

> **Fonksyon kosinis**: $$\cos(\alpha)$$ se kowòdone $$x$$ yon pwen sou sèk initè a ki nan yon ang $$\alpha$$.

> **Fonksyon Sinis**: $$\sin(\alpha)$$ se kowòdone $$y$$ yon pwen sou sèk initè a ki nan yon ang $$\alpha$$.

Sa yo se de
 dapre li fonksyon *kosinis* ak *sinis* toujou bay yon valè ki ant $$-1$$ ak $$1$$

Gen yon premye ekwasyon ke nou ka jwenn ki relye 2 fonskyon sa yo.

Nou ka wè gen 2 triyang rektang, nenpòt ladan yo ka pèmèt nou itilize [teworèm Pytagò](https://fr.wikipedia.org/wiki/Th%C3%A9or%C3%A8me_de_Pythagore)
pou ekri:

$$\forall \alpha,\  \cos(\alpha)^2 + \sin(\alpha)^2 = 1 $$

Sèlman nan gade imaj sa, nou ka wè kèk lòt karakteristik fonksyon sa, nou ka wè ke 2 fonksyon sa yo peryodik

$$f(x) = f(x + 2 k\pi),\ \forall k \in \mathbb{Z}$$

Nou wè ke peryod lan se $$2\pi$$, ki se ang ki nesesè pou fè tou sèk la.

Lè nou gade imaj sa nou ka gentan wè egalite sa yo, avek yon ti imajinasyon

![Definisyon Cosinis ak Sinis](/fizikkreyol/assets/trigonometry/ang_konplemantè.png)

### Kek egalite

|:-----------------------------------------|:----------------------------------------|
| $$\cos(-\alpha) = \cos(\alpha)$$         | $$\sin(-\alpha) = -\sin(\alpha)$$       |
| $$\cos(\pi - \alpha) = -\cos(\alpha)$$   | $$\sin(\pi - \alpha) = \sin(\alpha)$$   |
| $$\cos(\pi + \alpha) = -\cos(\alpha)$$   | $$\sin(\pi + \alpha) = -\sin(\alpha)$$  |
| $$\cos(\pi/2 + \alpha) = -\sin(\alpha)$$ | $$\sin(\pi/2 + \alpha) = \cos(\alpha)$$ |
| $$\cos(\pi/2 - \alpha) = \sin(\alpha)$$  | $$\sin(\pi/2 - \alpha) = \cos(\alpha)$$ |

Nou ka etidye kijan fonksyon yo evolye avek ang $$\alpha$$

### Fonksyon kosinis
![Fonksyon kosinis](/fizikkreyol/assets/trigonometry/fonksyon_kosinis.png)

#### Fonksyon sinis
![Fonksyon sinis](/fizikkreyol/assets/trigonometry/fonksyon_sinis.png)

Nou ka wè ke fonksyon sinis ak fonksyon se preske memm fonksyon yo ye, avek yon senp dekalaj
### Fonksyon kosinis (koub vèt) ak fonksyon sinis (koub rouj)
![Fonksyon kosinis ak sinis](/fizikkreyol/assets/trigonometry/fonksyon_kosinis_ak_sinis.png)

Fonksyon kosinis ak sinis se fonksyon ki pi itilize nan trigonometri.
Epi nou ka itilize yo pou defini yon pakèt lot fonksyon trigonometrik.

## Fonksyon sektant ak kosekant

> Nou ka defini fonksyon **sekant** : $$\sec(\alpha) = \dfrac{1}{\cos(\alpha)}$$

> Nou ka defini fonksyon **kosekant** : $$\csc(\alpha) = \dfrac{1}{\sin(\alpha)}$$

Nou ka wè nan imaj lan yon reprezantasyon 2 fonksyon sa yo

> Nou ka idantify plizyè tryang ki sanble([Triangles semblables](https://fr.wikipedia.org/wiki/Triangles_semblables) an fransè)

![Definisyon sekant ak kosekant](/fizikkreyol/assets/trigonometry/sekant_ak_kosekant.png)

Dapre imaj lan nou ka wè ke fonksyon **sekant** ak **kosekant** ka tann vè **enfini**

$$ \lim_{\alpha \to 0} \sec(\alpha) = \pm \infty $$

$$ \lim_{\alpha \to \dfrac{\pi}{2}} \csc(\alpha) = \pm \infty $$

## Fonksyon tanjant

Nou ka wè nan imaj sa, yon reprezantasyon grafik de fonksyon **tanjant** ak fonksyon **kotanjant**

### Definisyon tanjant ak kotanjant
![Definisyon tanjant ak kotanjant](/fizikkreyol/assets/trigonometry/tanjant.png)

Nou ka defini fonksyon sa yo avek fòmil:

$$ \tan(\alpha) = \dfrac{\sin(\alpha)}{\cos(\alpha)} $$

$$ \cot(\alpha) = \dfrac{\cos(\alpha)}{\sin(\alpha)} $$

Nou ka wè kijan fonksyon yo evolye:
### Fonksyon tanjant
![Fonksyon tanjant](/fizikkreyol/assets/trigonometry/fonksyon_tanjant.png)
### Fonksyon kotanjant
![Fonksyon kotanjant](/fizikkreyol/assets/trigonometry/fonksyon_kotanjant.png)

Nou rezime nan imaj sa 4 nan fonksyon trigonometrik:

### Kek foksyon trigonometrik
![Trigonometri](/fizikkreyol/assets/trigonometry/trigonometri.png)

## Kèk valè patikiyè
Nan imaj ki anba a nou ka wè kek valè patikiyè kosinis ak sinis

Valè ki bay yo nan lòd sa:
$$(\cos(\alpha),\ \sin(\alpha))$$

![Kek valè patikiyè](/fizikkreyol/assets/trigonometry/valè_espesyal.png)