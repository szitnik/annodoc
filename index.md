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
T1 PERSON 0 11 Janez Novak
T2 ORGANIZATION 21 29 Mercator
R1 ITI_V_TRGOVINO Arg1:T1 Arg2:T2
~~~

--->

To je zelo specifična povezava, ki vpliva na zelo velijo jezikovnih značilnosti, o katerih se bomo razpisali v nadaljevanju .... 

#### acl
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

#### advcl
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

#### advmod

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
Rupla ne skrbi usoda slovenskega jezika v EU .
advmod(skrbi,ne)
~~~
~~~ sdparse
Po tej poti so lahko konji vlekli vprege . 
advmod(vlekli,lahko)
~~~
~~~ sdparse
Le zakaj naj bi ju porinila ven ?
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




~~~ sdparse
največji uspeh doslej
advmod(uspeh,doslej)
~~~
~~~ sdparse
v torek zvečer
advmod(torek,zvečer)
~~~
~~~ sdparse
popke takoj ob začetku sušenja hitro segrejejo
advmod(začetku,takoj)
~~~

~~~ sdparse
 vložki iz krp, spletene volne, gobe in celo trave
advmod(trave,celo)
~~~

#### amod
~~~ sdparse
v vrste prostovoljnega gasilskega društva Dolga vas
amod(društva,prostovoljnega)
amod(društva,gasilskega)
amod(vas,Dolga)
~~~
~~~ sdparse
astronome zanima nekaj drugega
amod(nekaj,drugega)
~~~


~~~ sdparse
Se strinjate s trditvijo , postavljeno v naslovu pesmi ?
amod(trditvijo,postavljeno)
~~~
~~~ sdparse
Spremeni se v temen vzorec , podoben šahovnici .
amod(vzorec,podoben)
~~~
~~~ sdparse
nova ladja , velika 1350 kvadratnih metrov
amod(ladja,velika)
~~~

#### appos
~~~ sdparse
Območje medenice je središče telesa , glavna peč , ki greje in uravnava vse telo
appos(telesa,peč)
~~~
~~~ sdparse
Dianne se je sprla z Liso , svojo prijateljico , in se je odločila, da gre domov 
appos(Liso,prijateljico)
~~~

#### aux
~~~ sdparse
na kar so udeleženci reagirali z gromkim aplavzom
aux(reagirali,so)
~~~
~~~ sdparse
Za to bosta poskrbela Nikki in njen štirinožni ljubljenček
aux(poskrbela,bosta)
~~~
~~~ sdparse
Zakaj bi divjali okoli , če to ni potrebno
aux(divjali,bi)
~~~
~~~ sdparse
Takrat naj bi se bil proti njemu zagnal Robi .
aux(zagnal,bi)
aux(zagnal,bil)
~~~
~~~ sdparse
Zaradi njegovega polhastega spanja je bila večkrat jezna .
aux(jezna,je)
~~~

#### case
~~~ sdparse
Za nekaj pomežikov je verjela , da je v hotelu
case(pomežikov,Za)
case(hotelu,v)
~~~
~~~ sdparse
V veliki ponvi segrejemo štiri do pet žlic olja
case(ponvi,V)
case(pet,do)
~~~

~~~ sdparse
bodice , ki pri hranjenju delujejo kot filter
case(hranjenju,pri)
case(filter,kot)
~~~
~~~ sdparse
V Slovenski filharmoniji je kot poslovna direktorica izpeljala projekt obnove
case(direktorica,kot)
case(filharmoniji,V)
~~~

#### cc, cc:preconj
~~~ sdparse
mojstrica poslovne komunikacije in svetovalka
cc(svetovalka,in)
~~~
~~~ sdparse
Meso je lahko belo , modrikasto ali zelenkasto
cc(zelenkasto,ali)
~~~
~~~ sdparse
na območju od Kočevske Reke do Pirč oz. Broda na Kolpi
cc(Broda,oz.)
~~~
~~~ sdparse
Vprašanje se morda zdi absurdno , vendar je nekaj vzporednic .
cc(je,vendar)
~~~
~~~ sdparse
A slednjega se pri Peugeotu gotovo ne bojijo več .
cc(bojijo,A)
~~~
~~~ sdparse
Tudi zato s tovrstnim nasiljem ne ravnatelji ne učitelji nimajo izkušenj .
cc(učitelji,ne-8)
cc:preconj(ravnatelji,ne-6)
~~~

#### ccomp
~~~ sdparse
Ugotovili so tudi , da je izvleček baldrijana podaljšal delovanje barbituratov .
ccomp(Ugotovili,podaljšal)
~~~
~~~ sdparse
Prepričan sem , da je terjalo veliko korajže , je svečano rekel Tom .
ccomp(Prepričan,terjalo)
~~~
~~~ sdparse
Udeležence že opozarjajo , naj med tekom ne jemljejo vode iz rok neznanih gledalcev
ccomp(opozarjajo,jemljejo)
~~~

#### conj
~~~ sdparse
z Rusi , Čehi in Španci ni bilo pretirane nevarnosti za poraz
conj(Rusi,Čehi)
conj(Rusi,Španci)
cc(Španci,in)
punct(Čehi,,)
~~~
~~~ sdparse
Vitka Ribičič je postregla s kratkim , a jasnim odgovorom
conj(kratkim,jasnim)
cc(jasnim,a)
punct(jasnim,,)
~~~
~~~ sdparse
drugi so bolj ali manj zanimivi
conj(bolj,manj)
cc(manj,ali)
~~~
~~~ sdparse
opaziti je že tudi predstavnike ruske finančno - ekonomske elite
conj(finančno,ekonomske)
punct(ekonomske,-)
~~~


~~~ sdparse
Kaldenove oči so se jezno zožile , vendar je spregovoril z mirnim glasom.
conj(zožile,spregovoril)
cc(spregovoril,vendar)
~~~
~~~ sdparse
Prvenstvo bo zelo izenačeno , saj lahkega tekmeca tokrat ne bo .
conj(izenačeno,bo)
cc(bo,saj)
~~~
~~~ sdparse
Ko si enkrat na vrhu in se poškoduješ , se je težko vrniti .
conj(si,poškoduješ)
cc(poškoduješ,in)
~~~

#### cop
~~~ sdparse
Začetek izvajanja programa je odvisen od podpisa sporazuma
cop(odvisen,je)
nsubj(odvisen,Začetek)
~~~
~~~ sdparse
Rečna jezera mrtvice so stalni spremljevalci Mure 
cop(spremljevalci,so)
nsubj(spremljevalci,jezera)
~~~
~~~ sdparse
Da , jaz	sem tisti , ki bi moral biti tukaj
cop(tisti,sem)
nsubj(tisti,jaz)
~~~
~~~ sdparse
Niti prijatelja nista več bila
cop(prijatelja,bila)
aux(prijatelja,nista)
~~~

~~~ sdparse
kajenje je prepovedano
cop(prepovedano,je)
nsubj(prepovedano,kajenje)
~~~
~~~ sdparse
kajenje ji je bilo prepovedano
cop(prepovedano,bilo)
aux(prepovedano,je)
nsubj(prepovedano,kajenje)
~~~

#### csubj
~~~ sdparse
Karkoli že bi ruski predsednik rekel študentom , bi tukaj doživelo uspeh .
csubj(doživelo,rekel)
~~~
~~~ sdparse
Tako se večkrat zgodi , da so podjetja še vesela , če občani ne zberejo kaj dosti teh odpadkov .
csubj(zgodi,vesela)
cop(vesela,so)
~~~
~~~ sdparse
Vprašanje je , ali jih bomo obdržali na listi . 
csubj(Vprašanje,obdržali)
cop(Vprašanje,je)
~~~
~~~ sdparse
Bilo je	jasno , da ne bo mogel prebrati knjige .
csubj(jasno,mogel)
cop(jasno,Bilo)
~~~


~~~ sdparse
Podatke iz evidence je mogoče	dobiti samo na podlagi pisne prošnje posameznika .
csubj(mogoče,dobiti)
cop(mogoče,je)
~~~
~~~ sdparse
Mislim , da je zares velik dar srečati takega človeka .
csubj(dar,srečati)
cop(dar,je)
~~~
~~~ sdparse
Za detektiva bi bil pravi izziv odkriti , kje spi kralj tatov .
csubj(izziv,odkriti)
cop(izziv,bil)
~~~
~~~ sdparse
Te modele je treba potem le malenkostno prilagoditi .
csubj(je,prilagoditi)
~~~

#### dep
~~~ sdparse
Tip menda misl ,	dam	začel mlatit psa s palco .
dep(začel,dam)
~~~
~~~ sdparse
19 Institucija je za Mary Douglas sprejetje določenega miselnega sloga
dep(sprejetje,19)
cop(sprejetje,je)
nsubj(sprejetje,Institucija)
~~~


#### det
~~~ sdparse
Definitivno je odločitev unije za širitev	naš velik zaveznik .
det(zaveznik,naš)
~~~
~~~ sdparse
Ali ima center veliko dela spričo tako hudih medvrstniških obračunavanj ?
det(dela,veliko)
~~~

