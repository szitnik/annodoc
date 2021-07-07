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

#### discourse
~~~ sdparse
Oh , lepše od te si niste mogli izbrati 
discourse(mogli,Oh)
~~~
~~~ sdparse
Tam so samo zamahnili z roko,	češ , se bo že vrnila.
discourse(zamahnili,češ)
~~~
~~~ sdparse
Tebi gre najbrž drugače, rdečečopek ,	kajne ?
discourse(gre,kajne)
~~~

#### dislocated
~~~ sdparse
Marko , on se je udeležil vsakega sestanka 
dislocated(udeležil,Marko)
nsubj(udeležil,on)
~~~
~~~ sdparse
nikoli jih nismo zares razumeli , otrok 
dislocated(razumeli,otrok)
obj(razumeli,jih)
~~~

#### expl
~~~ sdparse
Vse so se veselo smejale .
expl(smejale,se)
~~~
~~~ sdparse
Pogosto se omenja planinski turizem .
expl(omenja,se)
~~~

~~~ sdparse
Celo noč so ga žurali .
expl(žurali,ga)
~~~
~~~ sdparse
Zagodla jim jo je bolezen .
expl(Zagodla,jo)
~~~

#### fixed
~~~ sdparse
Po več	kot tridesetih letih tega dela
fixed(več,kot)
~~~
~~~ sdparse
Čisto me je prevzelo, tako da je to opazila tudi Jasna
fixed(tako,da)
~~~
~~~ sdparse
na Kolpi bo tako imenovana schengenska meja
fixed(tako,imenovana)
~~~
~~~ sdparse
kljub temu , da
fixed(kljub,temu)
fixed(kljub,da)
punct(kljub,,)
~~~


#### flat
~~~ sdparse
Rojena sem bila 5. 10. 1957 
flat(5.,10.)
flat(5.,1957)
~~~
~~~ sdparse
Oškodovanka je v torbici nosila dobrih sto trideset tisoč tolarjev
flat(sto,trideset)
flat(sto,tisoč)
~~~

~~~ sdparse
Vladimir Putin
flat:name(Vladimir,Putin)
~~~
~~~ sdparse
Manca Šetina Miklič
flat:name(Manca,Šetina)
flat:name(Manca,Miklič)
~~~

~~~ sdparse
v svoji uspešnici You Can Heal Your Life
flat:foreign(You,Can)
flat:foreign(You,Heal)
flat:foreign(You,Your)
flat:foreign(You,Life)
~~~

#### goeswith
~~~ sdparse
brez časna knjiga
goeswith(brez,časna)
~~~

#### iobj
~~~ sdparse
Otrokoma je hotel zagotoviti lepo prihodnost
iobj(zagotoviti,Otrokoma)
obj(zagotoviti, prihodnost)
~~~
~~~ sdparse
prosili so me , naj govorim z njim
iobj(prosili,me)
ccomp(prosili,govorim)
~~~
~~~ sdparse
razbremeniti sodišče obravnave
iobj(razbremeniti,sodišče)
obj(razbremeniti,obravnave)
~~~

#### list
~~~ sdparse
Branko Tomažič , telefon : 041 707 534 , e-pošta : kz.vipava@siol.net .
list(Branko,telefon)
list(Branko,e-pošta)
appos(telefon,041)
appos(e-pošta,kz.vipava@siol.net)
flat:name(Branko,Tomažič)
flat(041,707)
flat(041,534)
~~~


#### mark
~~~ sdparse
Ko si enkrat na vrhu , se je težko vrniti.
mark(si,Ko)
~~~
~~~ sdparse
Honorar , ki ga bo prejela , naj bi imel sedem številk. 
mark(prejela,ki)
~~~
~~~ sdparse
Razmislite , ali je ta beseda ustrezna za naslov romana.
mark(ustrezna,ali)
cop(ustrezna,je)
~~~



~~~ sdparse
Tako nam ni preostalo drugega , kot da smo pustili nepopito pijačo in odšli .
fixed(kot,da)
mark(pustili,kot)
~~~
~~~ sdparse
Upam , da turistični delavci , medtem ko bodo širili Pohorje , ne bodo pozabili na to
fixed(medtem,ko)
mark(širili,medtem)
~~~

#### nmod
~~~ sdparse
prava poplava patentov za zdravila
nmod(poplava,patentov)
nmod(patentov,zdravila)
case(zdravila,za)
~~~
~~~ sdparse
nevšečnosti na televiziji BBC
nmod(nevšečnosti,televiziji)
case(televiziji,na)
nmod(televiziji,BBC)
~~~
~~~ sdparse
 v svoji uspešnici You Can Heal Your Life 
nmod(uspešnici,You)
~~~
~~~ sdparse
prilagajanje evropskim merilom
nmod(prilagajanje,merilom)
~~~

~~~ sdparse
Poraženci za kaj takega nimajo časa .
nmod(kaj,takega)
~~~
~~~ sdparse
eden od ciljev je državno prvenstvo
nmod(eden,ciljev)
case(ciljev,od)
~~~


~~~ sdparse
v državah članicah EU
nmod(državah,članicah)
nmod(članicah,EU)
~~~
~~~ sdparse
Mariborčan Iztok Božič
nmod(Mariborčan,Iztok)
~~~
~~~ sdparse
Harrisonov prijatelj Michael Palin
nmod(prijatelj,Michael)
~~~



~~~ sdparse
ta na pogled prostodušna opazka
nmod(prostodušna,pogled)
case(pogled,na)
amod(opazka,prostodušna)
~~~
~~~ sdparse
v niz razporejene slabotne zobce
nmod(razporejene,niz)
case(niz,v)
amod(zobce,razporejene)
~~~
~~~ sdparse
773 metrov visok vrh 
nmod(visok,metrov)
amod(vrh,visok)
~~~

~~~ sdparse
na plenarnem zasedanju leto kasneje 
nmod(kasneje,leto)
~~~
~~~ sdparse
Genska tehnologija pa je šla v tem smislu še korak dlje .
nmod(dlje,korak)
~~~

#### nsubj
~~~ sdparse
Kava povečuje izločanje želodčnega soka
nsubj(povečuje,Kava)
~~~
~~~ sdparse
Poleg tega je pa zadeva lahko tudi ustavno sporna .
nsubj(zadeva,sporna)
cop(sporna,je)
~~~
~~~ sdparse
Zato tudi ne manjka odzivov nanjo
nsubj(manjka,odzivov)
~~~
~~~ sdparse
prek pobočnice poteka 15 ozkih valovitih	prog 
nsubj(poteka,prog)
~~~

#### nummod
~~~ sdparse
pred desetimi leti
nummod(leti,desetimi)
~~~
~~~ sdparse
študentki 3. letnika Akademije za glasbo
nummod(letnika,3.)
~~~


~~~ sdparse
pet tisoč tristo metrov
nummod(metrov,pet)
flat(pet,tisoč)
flat(pet,tristo)
~~~
~~~ sdparse
Lani so ustvarili 550 milijonov tolarjev prometa .
nummod(milijonov,550)
nmod(milijonov,tolarjev)
~~~

~~~ sdparse
Zemljanka številka pet 
nummod(številka,pet)
~~~
~~~ sdparse
v letu 2002 
nummod(letu,2002)
~~~

#### obj
~~~ sdparse
Andreja Burin pa je dobila posebno pohvalo
obj(dobila,pohvalo)
~~~
~~~ sdparse
Neznosna teža nahrbtnika me je vlekla v globino.
obj(vlekla,me)
~~~
~~~ sdparse
Trojka ni upoštevala opozorila poročevalca Specialeja
obj(upoštevala,opozorila)
~~~
~~~ sdparse
Suho listje jima je šelestelo pod čevlji
obj(šelestelo,jima)
~~~

~~~ sdparse
Mladi gasilci so prav željni vaj .
obj(željni,vaj)
cop(željni,so)
nsubj(željni,gasilci)
~~~
~~~ sdparse
K sreči niste zapisani samo šahu .
obj(zapisani,šahu)
cop(zapisani,niste)
~~~
~~~ sdparse
Župančič je bil domači učitelj	grofiču Manfredu Attemsu
obj(učitelj,grofiču)
cop(učitelj,bil)
nsubj(učitelj,Župančič)
~~~


#### obl
~~~ sdparse
medtem pa se bodo pogovorili z razredom
obl(pogovorili,razredom)
case(razredom,z)
~~~
~~~ sdparse
Billovo vozilo je stalo na parkirišču pred bolnišnico.
obl(stalo,parkirišču)
case(parkirišču,na)
~~~
~~~ sdparse
slikarstvo je sicer res vezano na besedilno predlogo
obl(vezano,predlogo)
case(predlogo,na)
cop(vezano,je)
~~~
~~~ sdparse
Čudil se je, da niso sezidane iz lesa ali bambusa.
obl(sezidane,lesa)
case(lesa,iz)
cop(sezidane,niso)
~~~

#### obl
~~~ sdparse
Evropska komisija vsako jesen objavlja letno poročilo
obl(objavlja,jesen)
~~~
~~~ sdparse
učinki pa so znani že več stoletij
obl(znani,stoletij)
cop(znani,so)
~~~
~~~ sdparse
Odprava napake naj bi stala 64 milijonov mark
obl(stala,milijonov)
~~~
~~~ sdparse
Poslušalci so bili v povprečju stari štiriindvajset let
obl(stari,let)
~~~


~~~ sdparse
Najraje bi sam poklical Kyla Craiga
obl(poklical,sam)
~~~
~~~ sdparse
Nekatere slike so visele same zase
obl(visele,same)
~~~


~~~ sdparse
kot prva drsalka je nastopila v filmih
obl(nastopila,drsalka)
case(drsalka,kot)
~~~
~~~ sdparse
konflikt razume kot spopad
obl(razume,spopad)
case(spopad,kot)
~~~
~~~ sdparse
Dimenzije okvirjev so večje od vzorčnega dela šablone .
obl(večje,dela)
cop(večje,so)
case(dela,od)
~~~
~~~ sdparse
Jeza je pri otrocih pogostejše čustvo kot strah .
obl(pogostejše,strah)
case(strah,kot)
cop(čustvo,je)
~~~

#### orphan
~~~ sdparse
No , H. ni prevzel od Anglosasov ničesar , pač pa Anglosasi nekaj od H.
conj(prevzel,Anglosasi)
cc(Anglosasi,pač)
fixed(pač,pa)
orphan(Anglosasi,nekaj)
orphan(Anglosasi,H.-15)
case(H.-15, od-14)
~~~

#### parataxis
~~~ sdparse
Svetujemo : Bodite pozitivni do sebe in svoje okolice .
parataxis(Svetujemo,pozitivni)
cop(pozitivni,Bodite)
~~~
~~~ sdparse
Cena ne bo ravno visoka , predvidoma bo treba za hrano in bivanje plačevati po 500 SIT na dan .
parataxis(visoka,bo-8)
cop(visoka,bo-3)
~~~


~~~ sdparse
Nekaj ljudi iz te bolnišnice odide drugam , nekaj pa jih pride iz drugih .
parataxis(odide,pride)
advmod(pride,pa)
~~~
~~~ sdparse
Prišel , videl , zmagal .
parataxis(Prišel,videl)
parataxis(Prišel,zmagal)
~~~
~~~ sdparse
Ona ve , da je to moj stil življenja , da to potrebujem .
parataxis(stil,potrebujem)
cop(stil,je)
ccomp(ve,stil)
~~~


~~~ sdparse
Konec tedna je blagovnica v Cerknici samevala , kar je izkoristil nepridiprav iz bližnje okolice . 
parataxis(samevala,izkoristil)
obj(izkoristil,kar)
~~~

~~~ sdparse
Glavni žrtvi bova , kaže , prav midva .
parataxis(žrtvi,kaže)
cop(žrtvi,bova)
~~~

~~~ sdparse
Takole se je glasil : » Ali mora kmet res vedno le ubogati ? «
parataxis(glasil,mora)
~~~
~~~ sdparse
» To je Victor , « je pojasnil Victor Riccio .
parataxis(Victor-4,pojasnil)
cop(Victor-4,je)
~~~
~~~ sdparse
» Nimam časa , « sem butasto bleknila , » ker moram na postajo .
parataxis(bleknila,Nimam)
advcl(Nimam,moram)
~~~

~~~ sdparse
Postojna - Z nedeljskim mitingom so se končali Dnevi vojske
parataxis(končali,Postojna)
~~~



#### punct
~~~ sdparse
noben analgetik ne bo odpravil vozličkov , zaprtja in blokade tega območja 
conj(vozličkov,zaprtja)
conj(vozličkov,blokade)
punct(zaprtja,,)
cc(blokade,in)
~~~
~~~ sdparse
Da , to je fundacija , ki je bila ustanovljena v Ameriki . 
punct(Da,,)
punct(ustanovljena,,-6)
cop(ustanovljena,bila)
punct(fundacija,.)
cop(fundacija,je)
~~~
~~~ sdparse
so ugotovili še citotoksičnost ( toksičnost za zdrave celice ) in protitumorno delovanje
appos(citotoksičnost,toksičnost)
punct(toksičnost,()
punct(toksičnost,))
~~~

