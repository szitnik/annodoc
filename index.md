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



To je zelo specifična povezava, ki vpliva na zelo velijo jezikovnih značilnosti, o katerih se bomo razpisali v nadaljevanju .... 

~~~ sdparse
Premišljeval/VERB je/AUX o/ADP Jayu/PROPN in/CCONJ njegovih/DET prijateljih/NOUN ,/PUNCT ko/SCONJ je/AUX prečkal/VERB temačno/ADJ parkirišče/NOUN ./PUNCT
advcl(Premišljeval,prečkal)
aux(Premišljeval,je)
case(Jayu,o)
obl(Premišljeval,Jayu)
cc(prijateljih,in)
det(prijateljih,njegovih)
conj(Jayu,prijateljih)
punct(prečkal,,)
mark(prečkal,ko)
aux(prečkal,je-10)
amod(parkirišče,temačno)
obj(prečkal,parkirišče)
punct(Premišljeval,.)
~~~

--->

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
obj(imela,Lase)
~~~
~~~ sdparse
Vsa prestrašena je Mrvica stekla po pomoč .
acl(Mrvica,prestrašena)
nsubj(stekla,Mrvica)
~~~
~~~ sdparse
Ponesrečeno žensko so hudo ranjeno odpeljali v UKC .
acl(žensko,ranjeno)
obj(odpeljali,žensko)
~~~

#### advcl
~~~ sdparse
Premišljeval je o Jayu in njegovih prijateljih , ko je prečkal temačno parkirišče .
advcl(Premišljeval,prečkal)
~~~
~~~ sdparse
Čeprav so poroke večinoma veseli dogodki , so lahko priprave na to slavje polne težav .
advcl(polne,dogodki)
cop(polne,so-8)
nsubj(polne,priprave)

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
amod(mišice,delujoče)
~~~
~~~ sdparse
dogodki so se odvijali bistveno drugače
advmod(drugače,bistveno)
advmod(odvijali,drugače)
~~~
~~~ sdparse
farmarjem ne prav ljubi časopisi
advmod(ljubi,ne)
advmod(ljubi,prav)
amod(časopisi,ljubi)
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
case(začetku,ob)
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
na kar so/AUX udeleženci reagirali z gromkim aplavzom
aux(reagirali,so)
~~~
~~~ sdparse
Za to bosta/AUX poskrbela Nikki in njen štirinožni ljubljenček
aux(poskrbela,bosta)
~~~
~~~ sdparse
Zakaj bi/AUX divjali okoli , če to ni potrebno
aux(divjali,bi)
~~~
~~~ sdparse
Takrat naj bi/AUX se bil/AUX proti njemu zagnal Robi .
aux(zagnal,bi)
aux(zagnal,bil)
~~~
~~~ sdparse
Zaradi njegovega polhastega spanja je/AUX bila/AUX večkrat jezna .
aux(jezna,je)
cop(jezna,bila)
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
conj(mojstrica,svetovalka)
~~~
~~~ sdparse
Meso je lahko belo , modrikasto ali zelenkasto
cc(zelenkasto,ali)
conj(belo,modrikasto)
conj(belo,zelenkasto)
~~~
~~~ sdparse
na območju od Kočevske Reke do Pirč oz. Broda na Kolpi
cc(Broda,oz.)
conj(Pirč,Broda)
~~~
~~~ sdparse
Vprašanje se morda zdi absurdno , vendar je nekaj vzporednic .
cc(je,vendar)
conj(zdi,je)
~~~
~~~ sdparse
A slednjega se pri Peugeotu gotovo ne bojijo več .
cc(bojijo,A)
~~~
~~~ sdparse
Tudi zato s tovrstnim nasiljem ne ravnatelji ne učitelji nimajo izkušenj .
cc(učitelji,ne-8)
cc:preconj(ravnatelji,ne-6)
conj(ravnatelji,učitelji)
~~~

#### ccomp
~~~ sdparse
Ugotovili so tudi , da je izvleček baldrijana podaljšal delovanje barbituratov .
ccomp(Ugotovili,podaljšal)
~~~
~~~ sdparse
Prepričan sem , da je terjalo veliko korajže , je svečano rekel Tom .
ccomp(Prepričan,terjalo)
cop(Prepričan,sem)
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
amod(odgovorom,kratkim)
~~~
~~~ sdparse
drugi so bolj ali manj zanimivi
conj(bolj,manj)
cc(manj,ali)
advmod(zanimivi,bolj)
~~~
~~~ sdparse
opaziti je že tudi predstavnike ruske finančno - ekonomske elite
conj(finančno,ekonomske)
punct(ekonomske,-)
amod(elite,finančno)
amod(elite,ruske)
~~~


~~~ sdparse
Kaldenove oči so se jezno zožile , vendar je spregovoril z mirnim glasom.
conj(zožile,spregovoril)
cc(spregovoril,vendar)
~~~
~~~ sdparse
Prvenstvo bo zelo izenačeno , saj lahkega tekmeca tokrat ne bo .
conj(izenačeno,bo-11)
cc(bo-11,saj)
cop(izenačeno,bo)
~~~
~~~ sdparse
Ko si enkrat na vrhu in se poškoduješ , se je težko vrniti .
conj(si,poškoduješ)
cc(poškoduješ,in)
~~~

#### cop
~~~ sdparse
Začetek izvajanja programa je/AUX odvisen od podpisa sporazuma
cop(odvisen,je)
nsubj(odvisen,Začetek)
~~~
~~~ sdparse
Rečna jezera mrtvice so/AUX stalni spremljevalci Mure 
cop(spremljevalci,so)
nsubj(spremljevalci,jezera)
~~~
~~~ sdparse
Da , jaz	sem/AUX tisti , ki bi moral biti tukaj
cop(tisti,sem)
nsubj(tisti,jaz)
~~~
~~~ sdparse
Niti prijatelja nista/AUX več bila/AUX
cop(prijatelja,bila)
aux(prijatelja,nista)
~~~

~~~ sdparse
kajenje je/AUX prepovedano
cop(prepovedano,je)
nsubj(prepovedano,kajenje)
~~~
~~~ sdparse
kajenje ji je/AUX bilo/AUX prepovedano
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
Te modele je/VERB treba/ADV potem le malenkostno prilagoditi .
csubj(je,prilagoditi)
advmod(je,treba)
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
discourse(fundacija,Da)
acl(fundacija,ustanovljena)
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


#### reparandum
~~~ sdparse
da so te eee ti stroški čim manjši
mark(manjši,da)
cop(manjši,so)
nsubj(manjši,stroški)
advmod(manjši,čim)
reparandum(ti,te)
det(stroški,ti)
~~~

#### root
~~~ sdparse
ROOT Lastnika je oškodoval za 30 tisočakov .
root(ROOT,oškodoval)
~~~
~~~ sdparse
ROOT To je bilo značilno za pokrajine daleč od morja .
root(ROOT,značilno)
cop(značilno,bilo)
nsubj(značilno,To)
~~~

~~~ sdparse
ROOT Večno hvaležni udeleženci prometa v Ljubljani !
root(ROOT,udeleženci)
~~~

#### vocative
~~~ sdparse
Tebi gre najbrž drugače , rdečečopek , kajne ?
vocative(gre,rdečečopek)
~~~
~~~ sdparse
Kako s kej , Nelly ?
vocative(s,Nelly)
~~~

#### xcomp
~~~ sdparse
Za delovno mesto stažista je moral izpolnjevati dva pogoja .
xcomp(moral,izpolnjevati)
~~~
~~~ sdparse
Tam se je dalo kaj naučiti
xcomp(dalo,naučiti)
~~~
~~~ sdparse
Avgust je skušal uvesti dedno pravico do prestola
xcomp(skušal,uvesti)
~~~
~~~ sdparse
Čilsko sodišče mu je sklenilo odvzeti imuniteto
xcomp(sklenilo,odvzeti)
~~~
~~~ sdparse
Johnnyja Younga , ki si je prišel pogledat bazar
xcomp(prišel,pogledat)
~~~


~~~ sdparse
Voda ostaja najboljši dodatek za gnojevko . 
xcomp(ostaja,dodatek)
~~~
~~~ sdparse
Potem je svet postal lepši . 
xcomp(postal,lepši)
~~~
~~~ sdparse
Velja za najpomembnejšo špansko blagovno znamko luksuznih izdelkov .
xcomp(Velja,znamko)
case(znamko,za)
~~~
~~~ sdparse
Sodišče je lucijskega podjetnika spoznalo za krivega .
xcomp(spoznalo,krivega)
case(krivega,za)
~~~

#### T: elipse
~~~ sdparse
Sebi je kupila rdeč klobuk , meni pa je podarila zelenega .
obj(kupila,klobuk)
amod(klobuk,rdeč)
obj(podarila,zelenega)
~~~


~~~ sdparse
Kupila sem jabolka in tudi Peter jih je .
conj(Kupila,je)
cc(je,in)
advmod(je,tudi)
nsubj(je,Peter)
obj(je,jih)
~~~
~~~ sdparse
Ne vem , kdaj .
ccomp(vem,kdaj)
~~~


~~~ sdparse
Odšli so , nekateri za zmeraj .
parataxis(Odšli,nekateri)
orphan(nekateri,zmeraj)
case(zmeraj,za)
~~~
~~~ sdparse
No , H. ni prevzel od Anglosasov ničesar , pač pa Anglosasi nekaj od H.
conj(prevzel,Anglosasi)
cc(Anglosasi,pač)
fixed(pač,pa)
orphan(Anglosasi,nekaj)
orphan(Anglosasi,H.-15)
case(H.-15, od-14)
~~~
~~~ sdparse
Leva zanima predvsem telesna , Vodnarja pa duhovna plat življenja .
nsubj(zanima,telesna)
parataxis(zanima,plat)
orphan(plat,Vodnarja)
orphan(plat,pa)
amod(plat,duhovna)
nmod(plat,življenja)
~~~


~~~ sdparse
Odprtina se poveča najpozneje takrat , pogosto pa že prej .
parataxis(poveča,pogosto)
orphan(pogosto,pa)
orphan(pogosto,prej)
orphan(pogosto,že)
~~~


~~~ sdparse
je bilo treba razložiti sistem dogajanja in geografsko lego Slovenije
obj(razložiti,sistem)
conj(sistem,lego)
cc(lego,in)
~~~
~~~ sdparse
je bilo treba razložiti sistem dogajanja in tudi geografsko lego Slovenije
obj(razložiti,sistem)
conj(sistem,lego)
cc(lego,in)
advmod(lego,tudi)
~~~
~~~ sdparse
je bilo treba razložiti sistem dogajanja in znova tudi geografsko lego Slovenije
obj(razložiti,sistem)
conj(razložiti,lego)
cc(lego,in)
advmod(lego,tudi)
orphan(lego,znova)
~~~

#### T: primerjave
~~~ sdparse
Spal je , kot da se ni nič zgodilo .
advcl(Spal,zgodilo)
mark(zgodilo,kot)
fixed(kot,da)
~~~

~~~ sdparse
Njun razhod je bil grši , kot je pričakovala .
advcl(grši,pričakovala)
mark(pričakovala,kot)
~~~
~~~ sdparse
Toledo V5 skriva svojih 170 konjskih moči za enako zunanjostjo , kot jo imajo šibkejše različice
advcl(enako,imajo)
mark(imajo,kot)
~~~
~~~ sdparse
Prvorojenca se kot partnerja razumeta bolje , kot če bi bil eden od njiju edinec .
cop(edinec,bil)
advcl(bolje,edinec)
mark(edinec,kot-8)
fixed(kot-8,če)
~~~

~~~ sdparse
Spal je kot dojenček .
obl(Spal,dojenček)
case(dojenček,kot)
~~~
~~~ sdparse
kot odrasli prvorojenci potrebujejo manj spodbude
obl(potrebujejo,odrasli)
case(odrasli,kot)
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
amod(čustvo,pogostejše)
case(strah,kot)
~~~

#### T: druge strukture s primerjalnimi vezniki
~~~ sdparse
Zmaj , kot ga poznajo na Kitajskem , je živ 
acl(Zmaj, poznajo)
mark(poznajo, kot)
~~~
~~~ sdparse
Lastnosti besedila , kot so velikost , teža in slog 
acl(Lastnosti,so)
mark(so,kot)
~~~


~~~ sdparse
Augusto Pinochet je zdaj , kot pravijo , na začetku poti
advcl(je, pravijo)
mark(pravijo, kot)
~~~
~~~ sdparse
Valimo krivdo na sonce; kot da smo capini po sili usode .
advcl(Valimo,capini)
mark(capini,kot)
fixed(kot,da)
cop(capini,smo)
~~~


~~~ sdparse
z mizami za več kot 10 ljudi 
fixed(več,kot)
advmod(10,več)
case(ljudi,za)
nummod(ljudi,10)
~~~
~~~ sdparse
so običajni mobilni terminali vse prej kot primerni 
fixed(vse,prej)
fixed(vse,kot)
advmod(primerni,vse)
cop(primerni,so)
~~~
~~~ sdparse
bi moralo priti do sprave s televizijo, tako kot se je to zgodilo s časopisi
fixed(tako,kot)
advcl(moralo,zgodilo)
mark(zgodilo,tako)
~~~
<!-- advcl iz moralo ali priti?-->

~~~ sdparse
mu lahko pride prav tako pri dokumentarnih kot igranih filmih
cc:preconj(dokumentarnih,tako)
cc(igranih,kot)
conj(dokumentarnih,igranih)
amod(filmih,dokumentarnih)
case(filmih,pri)
~~~

#### T: besedilni povezovalci
~~~ sdparse
Bo se je nasmehnil in postavil v držo.
conj(nasmehnil,postavil)
cc(postavil,in)
~~~
~~~ sdparse
Saj samo spiš !
cc(spiš,Saj)
~~~

~~~ sdparse
Sem namreč zdravljeni alkoholik .
advmod(alkoholik,namreč)
cop(alkoholik,Sem)
~~~
~~~ sdparse
Pogledala me je , nato pa se spet obrnila k reki .
advmod(obrnila,pa)
advmod(obrnila,nato)
parataxis(Pogledala,obrnila)
~~~


~~~ sdparse
Torej , gre za to , kakšen je učinek .
discourse(gre,Torej)
~~~
~~~ sdparse
Kakorkoli , obstaja utemeljeni sum .
discourse(obstaja,Kakorkoli)
~~~
~~~ sdparse
Skratka , gre za ubežnike iz psihiatričnih ustanov .
discourse(gre,Skratka)
~~~


#### T: nedoločniki
~~~ sdparse
Država potemtakem mora uvesti nove davke
xcomp(mora,uvesti)
~~~

~~~ sdparse
Seveda ni mogoče/ADJ ničesar narediti čez noč
cop(mogoče,ni)
csubj(mogoče,narediti)
~~~
~~~ sdparse
Tako je cilj srečanja predvsem spodbuditi povezovanje malih podjetnikov
cop(cilj,je)
csubj(cilj,spodbuditi)
~~~

~~~ sdparse
občasno jih je treba/ADV spraviti v en koš
csubj(je,spraviti)
advmod(je,treba)
~~~
~~~ sdparse
v zraku je bilo čutiti nekakšno vznemirjenje
csubj(bilo,čutiti)
aux(bilo,je)
~~~


~~~ sdparse
V turističnem krožku so razmišljali , kako privabiti goste .
ccomp(razmišljali,privabiti)
~~~
~~~ sdparse
v zadnjem času se spet pojavljajo poskusi , oživiti življenje mladih
acl(poskusi,oživiti)
~~~
~~~ sdparse
Konec koncev je potovati prav tako zabavno , kot prispeti na cilj .
cop(zabavno,je)
csubj(zabavno,potovati)
advcl(zabavno, prispeti)
mark(prispeti,kot)
~~~

~~~ sdparse
Pogodba mora biti jasna in eksaktna .
xcomp(mora,jasna)
cop(jasna,biti)
~~~

#### T: povezovanje - nedoločniki
~~~ sdparse
Podplati so se mi začeli lepiti na tla .
xcomp(začeli,lepiti)
nsubj(Podplati,začeli)
aux(začeli,so)
expl(lepiti,se)
obj(lepiti,mi)
obl(lepiti,tla)
case(tla,na)
~~~
~~~ sdparse
v tem času Osmani niso pustili graditi objektov
xcomp(pustili,graditi)
nsubj(pustili,Osmani)
obl(graditi,času)
obj(graditi,objektov)
case(času,v)
det(času,tem)
aux(pustili,niso)
~~~
~~~ sdparse
ko so avstrijske oblasti dovolile zaradi romana P razpuščeni Matici spet delati
xcomp(dovolile,delati)
nsubj(dovolile,oblasti)
obj(dovolile,Matici)
obl(dovolile,romana)
advmod(delati,spet)
mark(dovolile,ko)
aux(dovolile,so)
amod(oblasti,avstrijske)
case(romana,zaradi)
nmod(romana,P)
amod(Matici,razpuščeni)
~~~


#### T: sekundarna predikacija
~~~ sdparse
Lase je imela pristrižene .
acl(Lase,pristrižene)
obj(imela,Lase)
~~~
~~~ sdparse
Vsa prestrašena je Mrvica stekla po pomoč .
acl(Mrvica,prestrašena)
nsubj(stekla,Mrvica)
~~~
~~~ sdparse
Ponesrečeno žensko so hudo ranjeno odpeljali v UKC .
acl(žensko,ranjeno)
obj(odpeljali,žensko)
~~~

~~~ sdparse
Prišla je oblečena v eleganten komplet s svetlomodro bluzo .
advcl(Prišla,oblečena)
~~~
~~~ sdparse
Ves blaten sem bil ob srečanju s kagujem nenadoma najsrečnejši človek .
advcl(človek,blaten)
~~~


~~~ sdparse
Voda ostaja najboljši dodatek za gnojevko . 
xcomp(ostaja,dodatek)
nsubj(ostaja,Voda)
~~~
~~~ sdparse
Potem je svet postal lepši . 
xcomp(postal,lepši)
nsubj(postal,svet)
~~~
~~~ sdparse
Velja za najpomembnejšo špansko blagovno znamko luksuznih izdelkov .
xcomp(Velja,znamko)
case(znamko,za)
~~~

#### T: ločevanje povedkovega določila in osebka
~~~ sdparse
Ena od obtožb je bila njegovo škandalozno druženje z ženskami .
nsubj(druženje,Ena)
cop(druženje,bila)
aux(druženje,je)
~~~
~~~ sdparse
da bi bil to le blag dotik ob srečanju
nsubj(dotik,to)
cop(dotik,bil)
aux(dotik,bi)
~~~
~~~ sdparse
Za nas bo bistveno , ali bomo znali spretno ravnati
csubj(bistveno,znali)
cop(bistveno,bo)
~~~
~~~ sdparse
Branko Majerič , ki je bil pobudnik tega strokovnega večera
acl(Branko,pobudnik)
cop(pobudnik,bil)
aux(pobudnik,je)
~~~



#### T: povezovanje in pridevniška določila
~~~ sdparse
V Sloveniji tega ne bi bili sposobni
obl(sposobni,Sloveniji)
obj(sposobni,tega)
cop(sposobni,bili)
aux(sposobni,bi)
advmod(sposobni,ne)
~~~
~~~ sdparse
V predlogu zakona je to prepuščeno izbranim cenilcem
obl(prepuščeno,predlogu)
cop(prepuščeno,je)
nsubj(prepuščeno,to)
obj(prepuščeno,cenilcem)
~~~


~~~ sdparse
na njih so ostale zapisane njegove misli
xcomp(ostale,zapisane)
obl(ostale,njih)
nsubj(ostale,misli)
~~~
~~~ sdparse
Kljub tradiciji so bili tokrat organizatorji prisiljeni izvesti nekatere spremembe .
cop(prisiljeni,bili)
obl(prisiljeni,tradiciji)
advmod(prisiljeni,tokrat)
nsubj(prisiljeni,organizatorji)
ccomp(prisiljeni,izvesti)
obj(izvesti,spremembe)
~~~

#### T: povezovanje in samostalniška določila
~~~ sdparse
To je bil hkrati tudi težko pričakovan test pnevmatik za novi razred
cop(test,bil)
nmod(test,pnevmatik)
nmod(test,razred)
case(razred,za)
~~~
~~~ sdparse
Molitev naj nam bo najmočnejša spodbuda za sprejemanje odgovornosti .
cop(spodbuda,bo)
nsubj(spodbuda,Molitev)
nmod(spodbuda,sprejemanje)
case(sprejemanje,za)
nmod(sprejemanje,odgovornosti)
obj(spodbuda,nam)
~~~

#### T: navidezni odvisniki
~~~ sdparse
Izkoristite ga sebi v prid , namesto da bi se nesmiselno borili proti lastnemu telesu .
advcl(Izkoristite,borili)
mark(borili,namesto)
fixed(namesto,da)
~~~
~~~ sdparse
Če se prav spominjam , je kot opravičilo navajal prezaposlenost .
advcl(navajal,spominjam)
mark(spominjam,Če)
~~~
~~~ sdparse
Kolikor vem , pa imajo tudi v EU še vedno težave z mikročipi .
advcl(imajo,vem)
mark(vem,Kolikor)
~~~

~~~ sdparse
Konec tedna je blagovnica v Cerknici samevala , kar je izkoristil nepridiprav iz bližnje okolice . 
parataxis(samevala,izkoristil)
obj(izkoristil,kar)
~~~
~~~ sdparse
Pri lastninjenju prihaja do številnih zlorab ,	pri čemer je presenetljivo , da pravosodje ne reagira
parataxis(prihaja,presenetljivo)
cop(presenetljivo,je)
case(čemer,pri)
obl(presenetljivo,čemer)
~~~
 
#### T: prislovi in prislovni odvisniki
~~~ sdparse
Vsakič , ko vstopim v kuhinjo , ga nežno pobožam .
advmod(pobožam,Vsakič)
advcl(pobožam,vstopim)
mark(vstopim,ko)
~~~
~~~ sdparse
Danes , ko boste s plesnimi koraki stopili življenju nasproti , ste vi župani tega mesta .
advmod(župani,Danes)
advcl(župani,stopili)
mark(stopili,ko)
cop(župani,ste)
~~~
~~~ sdparse
Tam , kjer ste dobri , ste vladar .
advmod(vladar,Tam)
advcl(vladar,dobri)
mark(dobri,kjer)
cop(vladar,ste-7)
cop(dobri,ste-4)
~~~

~~~ sdparse
Zdaj ko ni več kadrovskih štipendij , socialno šibke družine nimajo denarja za bivanje otrok .
advcl(nimajo,ni)
fixed(Zdaj,ko)
mark(ni,Zdaj)
~~~

#### T: modificirani vezniki
~~~ sdparse
Šele ko je zagotovljena solventnost , je ostanek kapital .
fixed(Šele,ko)
mark(zagotovljena,Šele)
cop(zagotovljena,je)
~~~

~~~ sdparse
Mladina se zdaj trumoma pojavlja na vratih duhovnika , še posebno odkar ve , da obožuje Metallico .
mark(ve,odkar)
advmod(ve,še)
fixed(še,posebno)
advcl(pojavlja,ve)
~~~
~~~ sdparse
zakaj ne bi v hrani uživali , tudi če se ne bašemo s čisto vsem
mark(bašemo,če)
advmod(bašemo,tudi)
advcl(uživali,bašemo)
~~~

~~~ sdparse
Po ustanovni listini lahko članica ZN uporabi silo , a samo , če jo kdo napade z oboroženo silo
mark(napade,če)
advcl(uporabi,napade)
cc(napade,a)
advmod(napade,samo)
~~~
~~~ sdparse
uporabljamo orožje , toda	le zato , ker ne vemo , kako bi drugače dosegli spremembe 
mark(vemo,zato)
fixed(zato,ker)
punct(zato,,-7)
advcl(uporabljamo,vemo)
cc(vemo,toda)
advmod(vemo,le)
~~~


#### T: poudarjalni prislovi
~~~ sdparse
Veliko se je govorilo o hladni vojni .
advmod(govorilo,Veliko)
~~~
~~~ sdparse
Jaz sem se spuščal čedalje globlje v psihopatologijo
advmod(globlje,čedalje)
advmod(spuščal,globlje)
~~~
~~~ sdparse
Odigrali so približno 40 koncertov po Sloveniji .
advmod(40,približno)
nummod(koncertov,40)
~~~
~~~ sdparse
Pri grafiki to ni tako zelo neposredno .
advmod(neposredno,zelo)
advmod(zelo,tako)
cop(neposredno,ni)
~~~

~~~ sdparse
Pravo delo se bo šele začelo .
advmod(začelo,šele)
~~~
~~~ sdparse
Moškim je vstop dovoljen šele po polnoči .
advmod(polnoči,šele)
case(polnoči,po)
~~~
~~~ sdparse
vložki iz krp , spletene volne , gobe	in celo trave
advmod(trave,celo)
conj(krp,volne)
conj(krp,gobe)
conj(krp,trave)
cc(trave,in)
~~~

#### T: razdruženi količinski izrazi
~~~ sdparse
Največ se jih je izselilo v Argentino .
obl(izselilo,Največ)
nsubj(izselilo,jih)
~~~
~~~ sdparse
teh je skupaj 14
obl(je,14)
nsubj(je,teh)
~~~

#### T: vprašalnice
~~~ sdparse
S testiranjem vnetja lahko določimo , komu preti srčni napad .
obj(preti,komu)
ccomp(določimo,preti)
~~~
~~~ sdparse
Belokranjce precej skrbi , kaj se bo zgodilo .
nsubj(zgodilo,kaj)
ccomp(skrbi,zgodilo)
~~~
~~~ sdparse
Sprva nisem vedela , kako vse skupaj deluje .
advmod(deluje,kako)
ccomp(vedela,deluje)
~~~
~~~ sdparse
Zamislite si položaj , v katerem si želite nastopiti mirno in sproščeno .
obl(želite,katerem)
case(katerem,v)
acl(položaj,želite)
~~~
~~~ sdparse
Vprašajte jo , kateri konji prihajajo na dirkališče .
det(konji,kateri)
nsubj(prihajajo,konji)
ccomp(Vprašajte,prihajajo)
~~~
~~~ sdparse
Vprašajte jo , kateri konji prihajajo na dirkališče .
det(konji,kateri)
nsubj(prihajajo,konji)
ccomp(Vprašajte,prihajajo)
~~~
~~~ sdparse
naš zeleni tobogan , po vijugah katerega se kopalci lahko na obročih spuščajo v dvojcu
nmod(vijugah,katerega)
obl(spuščajo,vijugah)
case(vijugah,po)
acl(tobogan,spuščajo)
~~~
~~~ sdparse
Gregor ni vedel ,	kakšni so njegovi nameni 
ccomp(vedel,kakšni)
cop(kakšni,so)
nsubj(kakšni,nameni)
~~~



#### T: okrajšave in simboli
~~~ sdparse
baročni oltar sv. Marka
amod(Marka,sv.)
~~~
~~~ sdparse
vsak kmet ima t. i. hlevsko knjigo
amod(knjigo,t.)
fixed(t.,i.)
~~~
~~~ sdparse
vzorci sovinjona oz. muškatnega silvanca
cc(silvanca,oz.)
conj(sovinjona,silvanca)
~~~
~~~ sdparse
tudi Barbara P. iz sosednje vasi
flat:name(Barbara,P.)
~~~
~~~ sdparse
Kmetijski minister dr. Milan Pogačnik
nmod(Milan,dr.)
flat:name(Milan,Pogačnik)
~~~

~~~ sdparse
poravnati približno 60 % obveznosti
nummod(%,60)
nmod(%,obveznosti)
obj(poravnati,%)
~~~
~~~ sdparse
voda se je segrela na 35,7 ° C
nummod(°,35,7)
nmod(°,C)
obl(segrela,°)
case(°,na)
~~~


