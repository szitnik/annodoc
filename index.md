---
layout: entry
title: Navodila za označevanje povezav po lastni želji :)
---

Tu so moja super-duper navodila za označevanje

#### Označevanje povezave ITI V TRGOVINO

Tu prikazujemo način označevanja povezav iti v trgovino.

<!--- Kaja začasno zakomentirala zaradi avtomatskega številčenja primerov, ki sledijo

~~~ ann
Janez Novak je šel v Mercator, kjer imajo slastne žemlje, polnjene s šunko, sirom in kumaricami - njami!
T1 PERSON 0 11	Janez Novak
T2 ORGANIZATION 21 29	Mercator
R1 ITI_V_TRGOVINO Arg1:T1 Arg2:T2
~~~

--->

To je zelo specifična povezava, ki vpliva na zelo velijo jezikovnih značilnosti, o katerih se bomo razpisali v nadaljevanju .... 

#### Primeri za acl
<!--- prilastkovi odvisniki--->
~~~ sdparse
Točno tako je s standardi , ki nastajajo v internetu .
acl(standardi, nastajajo)
~~~

~~~ sdparse
V hiši , v kateri so stanovali , so imeli skupna stranišča .
acl(hiši,stanovali)
~~~

~~~ sdparse
Kaj je tisto , kar bomo z vso odgovornostjo zapustili našim dedičem ?
acl(tisto,zapustili)
~~~

<!--- prilastkovi odvisniki--->
~~~ sdparse
Lase je imela pristrižene .
acl(Lase,pristrižene)
~~~
~~~ sdparse
Vsa prestrašena je Mrvica stekla po pomoč .
acl(Mrvica,prestrašena)
~~~
~~~ sdparse
Ponesrečeno žensko so hudo ranjeno odpeljali v UKC .
acl(žensko,ranjeno)
~~~

#### Primeri za advcl
~~~ sdparse
Premišljeval je o Jayu in njegovih prijateljih , ko je prečkal temačno parkirišče .
advcl(Premišljeval,prečkal)
~~~
~~~ sdparse
Čeprav so poroke večinoma veseli dogodki , so lahko priprave na to slavje polne težav .
advcl(težav,dogodki)
~~~


~~~ sdparse
Njihovo življenje je malce bolj umirjeno , kot smo ga vajeni .
advcl(umirjeno,vajeni)
~~~

~~~ sdparse
Prišla je oblečena v eleganten komplet s svetlomodro bluzo .
advcl(Prišla,oblečena)
~~~
~~~ sdparse
Ves blaten sem bil ob srečanju s kagujem nenadoma najsrečnejši človek .
advcl(človek,blaten)
~~~

#### Primeri za advmod

~~~ sdparse
pravilno je postavil diagnozo
advmod(postavil,pravilno)
~~~
~~~ sdparse
elektroda je navadno nameščena na bolnikovem hrbtu
advmod(nameščena,navadno)
~~~
~~~ sdparse
kot smo že poročali
advmod(poročali,že)
~~~
~~~ sdparse
še pes ima rad mir pri jedi
advmod(ima,rad)
~~~

~~~ sdparse
Rupla	ne skrbi usoda slovenskega jezika v EU .
advmod(skrbi,ne)
~~~
~~~ sdparse
Po tej poti so	lahko konji vlekli vprege . 
advmod(vlekli,lahko)
~~~
~~~ sdparse
Le zakaj	naj bi ju porinila ven ?
advmod(porinila,naj)
~~~
~~~ sdparse
normalno delujoče mišice
advmod(delujoče,normalno)
~~~
~~~ sdparse
dogodki so se odvijali bistveno drugače
advmod(drugače,bistveno)
~~~
~~~ sdparse
farmarjem ne prav ljubi časopisi
advmod(ljubi,ne)
advmod(ljubi,prav)
~~~

