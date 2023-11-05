## CSS FLEX (flex box)- regim de aranjare a elementelor, care a aprut in 2016
A fost creat pentru a elimina una din defectele in celelalte regimuri.
Este un regim inteligent, contribuie ca să scrii mai putin cod. Nu putem folosi flex peste tot pentru că putem supra incărca browserul, poate da unele erori.

Cele mai importante opțiuni:
- row/column(aranjarea elementelo in rand sau coloana)
- Horizontaly/verticaly symmetry(simetria orizontala si verticală)
- + Directionarea- new coordinates: start, center, end(left, right, top, bottom)
- + noi regimuri de aliniere: space-*(autocalcularea spatiului intre elemente)
- flex container(parinte)/ flex item(copii)- el nu poate lucra pe mai multe niveluri simultal, doar 2 niveluri, extindere pentru regimurile inline/block.
- + order(poti scrie elemetele in html in ordine după semantică, dar pe ecran poti sa le schimbi cu locul datorita elementului order, seamana cu z-index din pozitionare, el funcționeaza din perpendicular pe ecran, adică scoti deasupra unor elemente sau desupt. Orderul tot cu plus si minus doar ca pe v/h)
- axe(axis): main(horizontal), cross(vertical)
- smart aligment/size(aliniere si dimensionare automata) el va funcționa diferit de block și inline.
- direction(sa intorci directia invers)
- reverse(sa manevrezi ordinea v/h)
- wrap(poti sa aplici diferite politici sa treci din rand nou)
- shrink(are politici de ajustare si expandare, dai proportii cand este prea putin sau prea mult spatiu intre elemente)
- grow
- ...