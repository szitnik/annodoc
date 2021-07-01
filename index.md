---
layout: entry
title: Navodila za označevanje povezav po lastni želji :)
---

Tu so moja super-duper navodila za označevanje

#### Označevanje povezave ITI V TRGOVINO

Tu prikazujemo način označevanja povezav iti v trgovino.

~~~ ann
Janez Novak je šel v Mercator, kjer imajo slastne žemlje, polnjene s šunko, sirom in kumaricami - njami!
T1 PERSON 0 11	Janez Novak
T2 ORGANIZATION 21 29	Mercator
R1 ITI_V_TRGOVINO Arg1:T1 Arg2:T2
~~~

To je zelo specifična povezava, ki vpliva na zelo velijo jezikovnih značilnosti, o katerih se bomo razpisali v nadaljevanju .... 

To pa Kajin test prikazovanja na spletni strani.
~~~ sdparse
Il y a Marie qui danse dans la pièce . \n Marie dances in the room .
nsubj(a,Il)
advmod(a,y)
obj(a,Marie)
advcl:cleft(Marie,danse)
nsubj(danse,qui)
obl(danse,pièce)
case(pièce,dans)
det(pièce,la)
punct(a,.)
~~~

#### Primeri za acl
~~~ sdparse
Točno tako je s standardi, ki nastajajo v internetu.
acl(standardi,nastajajo)
~~~
~~~ sdparse
V hiši, v kateri so stanovali, so imeli skupna stranišča.
acl(hiši,stanovali)
~~~
~~~ sdparse
Kaj je tisto, kar bomo z vso odgovornostjo zapustili našim dedičem ?
acl(tisto,zapustili)
~~~


