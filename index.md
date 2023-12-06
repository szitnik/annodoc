---
layout: entry
title: Navodila za označevanje povezav
---

<!--- Kaja začasno zakomentirala zaradi avtomatskega številčenja primerov, ki sledijo

#### Označevanje povezave ITI V TRGOVINO

~~~ ann
Janez Novak je šel v Mercator, kjer imajo slastne žemlje, polnjene s šunko, sirom in kumaricami - njami!
T1 PERSON 0 11 Janez Novak
T2 ORGANIZATION 21 29 Mercator
R1 ITI_V_TRGOVINO Arg1:T1 Arg2:T2
~~~


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
appos(središče,peč)
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
Podatke iz evidence je/AUX mogoče/ADJ	dobiti samo na podlagi pisne prošnje posameznika .
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
advcl(težko,si)
cop(težko,je)
~~~
~~~ sdparse
Honorar , ki ga bo prejela , naj bi imel sedem številk. 
mark(prejela,ki)
acl(Honorar,prejela)
~~~
~~~ sdparse
Razmislite , ali je ta beseda ustrezna za naslov romana.
mark(ustrezna,ali)
cop(ustrezna,je)
ccomp(Razmislite,ustrezna)
~~~



~~~ sdparse
Tako nam ni preostalo drugega , kot da smo pustili nepopito pijačo in odšli .
fixed(kot,da)
mark(pustili,kot)
advcl(preostalo,pustili)
~~~
~~~ sdparse
Upam , da turistični delavci , medtem ko bodo širili Pohorje , ne bodo pozabili na to
fixed(medtem,ko)
mark(širili,medtem)
advcl(pozabili,širili)
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
Zato tudi ne manjka odzivov	nanjo .
nmod(odzivov,nanjo)
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
det(opazka,ta)
~~~
~~~ sdparse
v niz razporejene slabotne zobce
nmod(razporejene,niz)
case(niz,v)
amod(zobce,razporejene)
amod(zobce,slabotne)
~~~
~~~ sdparse
773 metrov visok vrh 
nmod(visok,metrov)
amod(vrh,visok)
nummod(metrov,773)
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
Sebi je kupila en rdeč klobuk , meni pa je podarila enega zelenega .
obj(kupila,klobuk)
nummod(klobuk,en)
amod(klobuk,rdeč)
obj(podarila,zelenega)
nummod(zelenega,enega)
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
advmod(prej,že)
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
Seveda ni/AUX mogoče/ADJ ničesar narediti čez noč
cop(mogoče,ni)
csubj(mogoče,narediti)
~~~
~~~ sdparse
Tako je/AUX cilj srečanja predvsem spodbuditi povezovanje malih podjetnikov
cop(cilj,je)
csubj(cilj,spodbuditi)
~~~

~~~ sdparse
občasno jih je/VERB treba/ADV spraviti v en koš
csubj(je,spraviti)
advmod(je,treba)
~~~
~~~ sdparse
v zraku je/AUX bilo/VERB čutiti nekakšno vznemirjenje
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
nsubj(test,To)
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

#### T: jedro paratakse
~~~ sdparse
Svetujemo : Bodite pozitivni do sebe in svoje okolice .
parataxis(Svetujemo,pozitivni)
cop(pozitivni,Bodite)
~~~
~~~ sdparse
Nekaj ljudi iz te bolnišnice odide drugam , nekaj pa jih pride iz drugih .
parataxis(odide,pride)
~~~
~~~ sdparse
Obarvanost : Hrbet in zgornji del bokov sta temna z zelenkastimi odtenki , spodnji del bokov in trebuh pa srebrna .
parataxis(Obarvanost,temna)
parataxis(temna,srebrna)
~~~

#### T: nestavčna parataksa

~~~ sdparse
Postojna - Z nedeljskim mitingom so se končali Dnevi vojske
parataxis(končali,Postojna)
~~~
~~~ sdparse
Prav idealizacija določenih oblik lepote je prispevala k oblikovanju nacionalnih parkov ( Aitchison 2002 ) .
parataxis(prispevala,Aitchison)
nummod(Aitchison,2002)
~~~

~~~ sdparse
O uniformi vemo , da je nasprotje sproščenosti , znamenje poenotenosti .
appos(nasprotje,znamenje)
~~~
~~~ sdparse
Na voljo dajo nov izdelek , na primer depilator .
appos(izdelek,depilator)
~~~
~~~ sdparse
Ithaca : Cornell University Press .
appos(Ithaca,Cornell)
~~~

#### T: pojasnjevalne strukture
~~~ sdparse
Nov sistem najemnine bo začel veljati šele v začetku leta 2005 , in sicer bo prehod tudi tedaj postopen .
conj(začel,postopen)
cop(postopen, bo-15)
fixed(in,sicer)
cc(postopen,in)
~~~
~~~ sdparse
Zaradi negativne naravnanosti v življenju zapademo v bolezen , lahko tudi v odvisnost .
parataxis(zapademo,odvisnost)
orphan(odvisnost,lahko)
advmod(odvisnost,tudi)
case(odvisnost,v)
~~~
~~~ sdparse
Zamešajte puder z bleščicami ( najbolje v roza barvi ) in losjon za telo .
parataxis(Zamešajte,barvi)
orphan(barvi,najbolje)
~~~

~~~ sdparse
Na voljo dajo nov izdelek , na primer depilator .
appos(izdelek,depilator)
fixed(na,primer)
cc(depilator,na)
~~~
~~~ sdparse
Prvotno je bil razširjen v Severni Ameriki , predvsem v jezerih .
appos(Ameriki,jezerih)
advmod(jezerih,predvsem)
case(jezerih,v-10)
~~~
~~~ sdparse
Jezera so bolj ali manj oligotrofna , to je , z malo hranilnih snovi .
appos(oligotrofna,snovi)
case(snovi,z)
det(snovi,malo)
amod(snovi,hranilnih)
fixed(to,je)
cc(snovi,to)
~~~
~~~ sdparse
Še kasneje , v zrelih letih , je zelo dobro spal .
appos(kasneje,letih)
case(letih,v)
amod(letih,zrelih)
~~~
~~~ sdparse
Hrbtna in repna plavut sta temne srebrnkaste do rumenkaste barve , prsne in trebušni plavuti pa temno rumeno pegaste . 
parataxis(barve,pegaste)
nsubj(pegaste,plavuti)
advmod(pegaste,pa)
advmod(pegaste,rumeno)
~~~

#### T: pojasnjevalne strukture

#### Novi primeri (ki jih zaradi številčenja premaknili pred izidom smernic)

##### novi-advmod
~~~ sdparse
Do takrat mu niso ponudili niti pijače .
advmod(ponudili,takrat)
case(takrat,Do)
~~~
~~~ sdparse
Dobiček družbe bo znašal približno 75 milijonov dolarjev .
advmod(75,približno)
nummod(milijonov,75)
~~~
~~~ sdparse
Neznanec je svoj protest poslal na kar 46.000 internetnih naslovov .
advmod(46.000,kar)
nummod(naslovov,46.000)
case(naslovov,na)
~~~



##### novi-conj
~~~ sdparse
Na ogled so preša , panji , vosek itd.
conj(preša,panji)
conj(preša,vosek)
conj(preša,itd.)
~~~


~~~ sdparse
Lahko je spal deset , dvanajst ur .
conj(deset,dvanajst)
nummod(ur,deset)
punct(dvanajst,,)
~~~
~~~ sdparse
Vnema učitelja Bogdana Žolnirja ( 1908 - 1998 )
conj(1908,1998)
punct(1998,-)
~~~
~~~ sdparse
Desno roko za pet do deset centimetrov dvignite proti stropu .
conj(pet,deset)
cc(deset,do)
nummod(centimetrov,pet)
~~~

##### novi-nummod
~~~ sdparse
Bojazni , ki so v desetletju pred 1914 zastrupljale evropsko atmosfero .
case(1914,pred)
nmod(desetletju,1914)
~~~
~~~ sdparse
Novomeške odbojkarice so se z zmago nad Celjem s 3:1 uvrstile v končnico .
case(3:1,s)
nmod(zmago,3:1)
nmod(zmago,Celjem)
case(Celjem,nad)
~~~
~~~ sdparse
V 7270 tiči tehnologija , ki jo slovenski ponudniki mobilnih signalov še ne ponujajo . 
case(7270,V)
obl(tiči,7270)
~~~

##### novi-obl
~~~ sdparse
Potem pa le pazi name .
obl(pazi,name)
~~~
~~~ sdparse
Kandidata pa za to obtožujeta drug drugega .
obl(obtožujeta,drug)
obj(obtožujeta,drugega)
~~~

##### novi-parataxis
~~~ sdparse
Kar zadeva zmogljivost , je bil računalnik hiter .
parataxis(zadeva,hiter)
nsubj(zadeva,Kar)
cop(hiter,bil)
aux(hiter,je)
~~~
~~~ sdparse
Sam sem bil zmeraj mal živčen , kar se drog tiče .
parataxis(živčen,tiče)
nsubj(tiče,kar)
cop(živčen,bil)
aux(živčen,sem)
~~~

##### novi-elipse
~~~ sdparse
Naklonjena so vprašanju vlaganj in prevzemov na tujem .
nmod(prevzemov,tujem)
case(tujem,na)
~~~
~~~ sdparse
To pa je pomenilo vstajanje ob dveh .
nmod(vstajanje,dveh)
case(dveh,ob)
~~~

~~~ sdparse
Delničarji so večinoma potrdili predlagane sklepe , marsikje pa tudi ne v celoti .
parataxis(potrdili,ne)
orphan(ne,marsikje)
orphan(ne,pa)
orphan(ne,tudi)
orphan(ne,celoti)
case(celoti,v)
punct(ne,,)
~~~


##### novi-prim-vezniki
~~~ sdparse
Spal je kot dojenček .
obl(Spal,dojenček)
case(dojenček,kot)
~~~
~~~ sdparse
Spal je , kot da se ni nič zgodilo .
advcl(Spal,zgodilo)
mark(zgodilo,kot)
fixed(kot,da)
~~~
~~~ sdparse
kot odrasli prvorojenci potrebujejo manj spodbude
obl(potrebujejo,odrasli)
case(odrasli,kot)
~~~

##### novi-nedoločniki
~~~ sdparse
Alverstead je videti šokiran .
cop(videti,je)
nsubj(videti,Alverstead)
acl(Alverstead,šokiran)
~~~
~~~ sdparse
Stolpnica je bila videti kot avtocesta v nebo .
cop(videti,bila)
aux(videti,je)
nsubj(videti,Stolpnica)
obl(videti,avtocesta)
case(avtocesta,kot)
~~~

#### T: od-do
~~~ sdparse
Potrebno je od široke baze idej na koncu priti do prave kakovosti izdelka .
obl(priti,idej)
case(idej,od)
obl(priti,kakovosti)
case(kakovosti,do)
~~~
~~~ sdparse
Z MNZ RS smo poslovali od septembra 1991 do marca 1992 .
obl(poslovali,septembra)
case(septembra,od)
obl(poslovali,marca)
case(marca,do)
~~~
~~~ sdparse
Prireditev bodo začeli s sprevodom od sedeža Turistice do Lucije .
nmod(sprevodom,sedeža)
case(sedeža,od)
nmod(sprevodom,Lucije)
case(Lucije,do)
~~~
~~~ sdparse
Zvrstili so s v obdobju od padca Beneške republike do dunajskega kongresa .
nmod(obdobju,padca)
case(padca,od)
nmod(obdobju,kongresa)
case(kongresa,do)
~~~


~~~ sdparse
Brizgači lahko živijo od 5 do 10 let .
obl(živijo,let)
case(5,od)
nmod(let,5)
case(let,do)
nummod(let,10)
~~~
~~~ sdparse
Policisti so od 2. do 9. septembra prejeli 650 tujcev .
obl(prejeli,septembra)
case(2.,od)
nmod(septembra,2.)
case(septembra,do)
nummod(septembra,9.)
~~~
~~~ sdparse
Vabe postavimo v globino od 5 do 10 cm .
nmod(globino,cm)
case(5,od)
nmod(cm,5)
case(cm,do)
nummod(cm,10)
~~~
~~~ sdparse
Od 40 do 50 odstotkov slovenskega gospodarstva je v lasti države .
case(40,Od)
nmod(odstotkov,40)
case(50,do)
nummod(odstotkov,50)
~~~


~~~ sdparse
Desno roko za pet do deset centimetrov dvignite proti stropu .
conj(pet,deset)
cc(deset,do)
nummod(centimetrov,pet)
~~~

	
#### T: neprojektivnost
~~~ sdparse
Jeza je pri otrocih pogosto čustvo .
nsubj(čustvo,Jeza)
cop(čustvo,je)
case(otrocih,pri)
obl(čustvo,otrocih)
amod(čustvo,pogosto)
punct(čustvo,.)
~~~
~~~ sdparse
Jeza je pri otrocih pogostejše čustvo kot strah .
nsubj(čustvo,Jeza)
cop(čustvo,je)
case(otrocih,pri)
obl(čustvo,otrocih)
amod(čustvo,pogostejše)
obl(pogostejše,strah)
case(strah,kot)
punct(čustvo,.)
~~~

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
Nikamor nimam namena odpotovat .
acl(namena,odpotovat)
obj(nimam,namena)
advmod(odpotovat,Nikamor)
punct(nimam,.)
~~~

~~~ sdparse
Palico držimo iztegnjeno .
acl(Palico,iztegnjeno)
obj(držimo,Palico)
punct(držimo,.)
~~~
~~~ sdparse
Jeza je pri otrocih pogostejše čustvo kot strah .
nsubj(čustvo,Jeza)
cop(čustvo,je)
case(otrocih,pri)
obl(čustvo,otrocih)
amod(čustvo,pogostejše)
obl(pogostejše,strah)
case(strah,kot)
punct(čustvo,.)
~~~
~~~ sdparse
Ljubi Boga ( kolikor ga pozna ) , sebe in bližnjega .
conj(Boga,sebe)
conj(Boga,bližnjega)
obj(Ljubi,Boga)
advcl(Ljubi,pozna)
~~~
~~~ sdparse
Obseg sredstev se je povečal kar za 555 milijonov .
advmod(555,kar)
nummod(milijonov,555)
case(milijonov,za)
~~~
~~~ sdparse
John Deere je pri proizvodnji traktorjev zelo avtonomen ( motorji , menjalniki ) . 
cop(avtonomen,je)
nsubj(avtonomen,John)
obl(avtonomen,proizvodnji)
appos(proizvodnji,motorji)
conj(motorji,menjalniki)
punct(motorji,()
punct(motorji,))
~~~

#### Dodatki v smernice oktober 2022
#### obl: vsi, prvi

~~~ sdparse
Odmerki deksametazona so , kot se zdi , vsi enako učinkoviti .
nsubj(učinkoviti,Odmerki)
nmod(Odmerki,deksametazona)
obl(učinkoviti,vsi)
cop(učinkoviti,so)
~~~
~~~ sdparse
Zdravnik John Langdon Down je leta 1866 ta sindrom prvi opisal .
nsubj(opisal,Zdravnik)
obl(opisal,prvi)
obj(opisal,sindrom)
det(sindrom,ta)
nmod(Zdravnik,John)
flat:name(John,Langdon)
flat:name(John,Down)
~~~

#### večbesedna tujejezična lastna imena

~~~ sdparse
Angry Birds je franšiza videoiger .
nmod(Angry,Birds)
nsubj(franšiza,Angry)
cop(franšiza,je)
~~~

#### expl: rodilniški zaimki 

~~~ sdparse
Je ni substance , pri kateri bi bila raziskovalna dejavnost tako silovita .
expl(ni,Je)
nsubj(ni,substance)
~~~

#### parataxis: popravek pri premem govoru

~~~ sdparse
takole se je glasil : » Ali mora kmet res vedno le ubogati ? «
parataxis(glasil,mora)
~~~

~~~ sdparse
» To je Victor , « je pojasnil Victor Riccio .
parataxis(Victor-4,pojasnil)
cop(Victor-4,je)
~~~

~~~ sdparse
» Nimam Časa , « sem butasto bleknila , » ker moram na postajo .
parataxis(Nimam,bleknila)
advcl(Nimam,moram)
~~~

#### kar v vezniški vlogi kot advmod

~~~ sdparse
Tokratna kampanja je bila ena najdaljših , kar pomni .
advmod(pomni,kar)
~~~

~~~ sdparse
V najmehkejših copatih , kar ste si jih kdaj nadeli .
advmod(nadeli,kar)
~~~

#### biti + strah/groza/sram/...

~~~ sdparse
Vas ni prav nič strah ?
nsubj(ni,strah)
obj(ni,Vas)
~~~

~~~ sdparse
Lahko te je ravno tako strah , če od spodaj gledaš zelo visoko .
nsubj(je,strah)
obj(je,te)
~~~

~~~ sdparse
Pijanec , ki pije , da bi pozabil , da ga je sram , ker pije .
nsubj(je,sram)
obj(je,ga)
~~~

#### pogoste napake označevalnika

narobe:
~~~ sdparse
Strategija določa cilje financiranja ESS , ki si jih deloma ali v celoti deli z drugimi strukturnimi skladi .
acl(financiranja,deli)
mark(deli,ki)
~~~

~~~ sdparse
Ta v primeru potrebe po svoji presoji napoti bolnika k specialistu .
nmod(potrebe,presoji)
case(presoji,po)
~~~

~~~ sdparse
Ima pa tudi ambicije sodelovati za kreacijo oblek .
advmod(Ima,tudi)
obj(Ima,ambicije)
~~~

pravilno:
~~~ sdparse
Strategija določa cilje financiranja ESS , ki si jih deloma ali v celoti deli z drugimi strukturnimi skladi .
acl(cilje,deli)
mark(deli,ki)
~~~

~~~ sdparse
Ta v primeru potrebe po svoji presoji napoti bolnika k specialistu .
obl(napoti,presoji)
case(presoji,po)
~~~

~~~ sdparse
Ima pa tudi ambicije sodelovati za kreacijo oblek .
advmod(ambicije,tudi)
obj(Ima,ambicije)
~~~

### posebnosti govorjenega jezika

#### ločila
~~~ sdparse
kje pa dobim podatke za tujino ?
punct(dobim,?)
~~~

~~~ sdparse
kaj ? a nama je ušlo tole zdajle ?
punct(kaj,?-2)
punct(ušlo,?-9)
parataxis(kaj,ušlo)
~~~


#### elipse
~~~ sdparse
pri nas pa občasno
orphan(nas,pa)
orphan(nas,občasno)
case(nas,pri)
~~~

~~~ sdparse
kam pa ?
orphan(kam,pa)
punct(kam,?)
~~~

~~~ sdparse
tudi Francozinja v težavah
orphan(Francozinja,težavah)
advmod(Francozinja,tudi)
case(težavah,v)
~~~

~~~ sdparse
in pol jaz njemu
orphan(jaz,pol)
orphan(jaz,njemu)
cc(jaz,in)
~~~

~~~ sdparse
ja to pa bova z-
discourse(bova,ja)
obj(bova,to)
advmod(bova,pa)
orphan(bova,z-)
~~~


~~~ sdparse
upam da
ccomp (upam,da)
~~~

~~~ sdparse
zakaj ne ?
orphan(ne,zakaj)
punct(ne,?)
~~~

#### parataxis:discourse
~~~ sdparse
mislim imamo zajtrk in imamo večerjo ne
parataxis:discourse (imamo-2,mislim)
obj(imamo-2,zajtrk)
cc(imamo-5,in)
obj(imamo-5,večerjo)
discourse(imamo-2,ne)
~~~

#### discourse:filler
~~~ sdparse
tukaj je so stvari eee zelo jasne ne
discourse(jasne,ne)
advmod(jasne,zelo)
discourse:filler(jasne,eee)
nsubj(jasne,stvari)
cop(jasne,so)
reparandum(so,je)
advmod(jasne,tukaj)
~~~

~~~ sdparse
eee danes bom predstavil predavanje eee skupaj z očetom
discourse:filler(predstavil,eee-1)
discourse:filler(predstavil,eee-6)
~~~

~~~ sdparse
da so te eee ti stroški čim manjši
mark(manjši,da)
cop(manjši,so)
nsubj(manjši,stroški)
advmod(manjši,čim)
reparandum(ti,te)
det(stroški,ti)
discourse:filler(manjši,eee)
~~~

~~~ sdparse
eee to te mora pač eee resnično eee zanimati
discourse:filler(mora,eee-1)
advmod(mora,pač)
xcomp(mora,zanimati)
advmod(zanimati,resnično)
discourse:filler(mora,eee-6)
discourse:filler(mora,eee-8)
~~~

#### navidezni odvisniki (advcl)
~~~ sdparse
predavala bo gospa doktor ki je kolikor jaz vem edina v sloveniji
mark(edina,ki)
cop(edina,je)
advcl(edina,vem)
mark(vem,kolikor)
nsubj(vem,jaz)
~~~


#### nadaljevalniki (conj)
~~~ sdparse
preveč organske snovi pomeni gnitje , slabše prezimovanje in podobno
conj(gnitje,prezimovanje)
conj(gnitje,podobno)
cc(podobno,in)
~~~

~~~ sdparse
že se pripravljamo na pust , veliko noč in tako dalje
conj(pust,noč)
conj(pust,in)
fixed(in,tako)
fixed(in,dalje)
~~~

~~~ sdparse
špago sem mogel omotati pa take
conj(mogel,take)
cc(take,pa)
~~~

~~~ sdparse
kako orož- orožje pa to
det(orožje,kako)
reparandum(orožje,orož-)
conj(orožje,to)
cc(to,pa)
~~~

~~~ sdparse
kaj ga še kar geekaš ali kaj ?
conj(geekaš,kaj-7)
cc(kaj-7,ali)
~~~

#### asidentična (conj)
~~~ sdparse
preden zapusti vrtec šolo dijaški dom
conj(vrtec,šolo)
conj(vrtec,dom)
~~~

#### neprojektivnost-dopustna

~~~ sdparse
ja kaj pa mislim glede recimo hrane
discourse(kaj,ja)
advmod(kaj,pa)
parataxis:discourse(kaj,mislim)
case(hrane,glede)
orphan(kaj,hrane)
parataxis:discourse(kaj,recimo)
~~~

~~~ sdparse
eee to te mora pač eee resnično eee zanimati
discourse:filler(mora,eee-1)
advmod(mora,pač)
xcomp(mora,zanimati)
advmod(zanimati,resnično)
discourse:filler(mora,eee-6)
discourse:filler(mora,eee-8)
~~~

~~~ sdparse
predavala gos- bo gospa doktor
nsubj(predavala,gospa)
aux(predavala,bo)
reparandum(gospa,gos-)
nmod(gospa,doktor)
~~~


#### atipicni besedni red

~~~ sdparse
Mama je Marini dala jabolko .
nsubj(dala,Mama)
iobj(dala,Marini)
obj(dala,jabolko)
~~~
~~~ sdparse
Jabolko je mama dala Marini .
nsubj(dala,mama)
iobj(dala,Marini)
obj(dala,Jabolko)
~~~

~~~ sdparse
velika skrb
amod(skrb,velika)
~~~
~~~ sdparse
skrb velika
amod(skrb,velika)
~~~



~~~ sdparse
imam pa tudi debelo ono uro jekleno
obj(imam,uro)
amod(uro,debelo)
det(uro,ono)
amod(uro,jekleno)
~~~

~~~ sdparse
torej volilni molk tega v združenih državah ne poznajo
discourse(poznajo,torej)
case(državah,v)
amod(državah,združenih)
dislocated(poznajo,molk)
amod(molk,volilni)
obj(poznajo,tega)
~~~

#### govor - določilniki
~~~ sdparse
zdaj ste se dotaknili ene teme ki je letos aktualna
det(teme,ene)
~~~
~~~ sdparse
zdaj po tej ta novi diplomi je drugače
det(diplomi,ta)
amod(diplomi,novi)
~~~


#### flat v govoru
~~~ sdparse
dva cela pet odstotka
flat(dva,cela)
flat(dva,pet)
nummod(odstotka,dva)
~~~

~~~ sdparse
skok na trikrat dvojni v pika Radio Capris pika si poševnica Kikiriki
nmod(skok,v)
case(v,na)
advmod(dvojni,trikrat)
amod(v,dvojni)
flat(v,pika-6)
flat(v,pika-9)
flat(v,Radio)
nmod(Radio,Capris)
flat(v,pika)
flat(v,si)
flat(v,poševnica)
flat(v,Kikiriki)
~~~

~~~ sdparse
i a si torej
flat(i,a)
flat(i,si)
discourse(i,torej)
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

~~~ sdparse
eem kako orož- orožje pa to
reparandum(orožje,orož-)
det(orožje,kako)
discourse:filler(orožje,eem)
conj(orožje,to)
cc(to,pa)
~~~

~~~ sdparse
predavala gos- bo gospa doktor
nsubj(predavala,gospa)
aux(predavala,bo)
reparandum(gospa,gos-)
nmod(gospa,doktor)
~~~

~~~ sdparse
ste zadovoljni s stanoval- s svojimi stanovalci
reparandum(stanovalci,stanoval-)
case(stanoval-,s-3)
case(stanovalci,s-5)
amod(stanovalci,svojimi)
obl(zadovoljni,stanovalci)
~~~

~~~ sdparse
huh eem da da zožamo nekatere eee teritorije ne
reparandum(da-4,da-3)
mark(zožamo,da-4)
~~~



#### reparandum - nezakljucene


~~~ sdparse
če prav če sem prav razumel
reparandum(razumel,prav-2)
mark(prav-2,če-1)
mark(razumel,če-3)
aux(razumel,sem)
advmod(razumel,prav-5)
~~~

~~~ sdparse
ne daj naj požri naj požre tisto
discourse(požre,ne)
parataxis:discourse(požre,daj)
advmod(požri,naj-3)
reparandum(požre,požri)
advmod(požre,naj-5)
obj(požre,tisto)
~~~

~~~ sdparse
zdaj vse se da potem spraviti v povezati z kozmologijo
discourse(da,zdaj)
nsubj(da,vse)
expl(da,se)
advmod(da,potem)
xcomp(da,povezati)
reparandum(povezati,spraviti)
orphan(spraviti,v)
~~~

~~~ sdparse
nekega dne sem se eee sem se skregal
advmod(skregal,dne)
det(dne,nekega)
aux(skregal,sem-6)
expl(skregal,se-7)
reparandum(skregal,sem-3)
orphan(sem-3,se-4)
~~~


#### parataxis:restart
~~~ sdparse
slika kaže kako so ta človek sedi
parataxis:restart (kaže,sedi)
~~~

~~~ sdparse
kaj si zdaj pravkar katero črto boš narisala
parataxis:restart (si,narisala)
~~~

### veriženje reparandum

~~~ sdparse
iskalnik je po krajih po imenih po po po ukrepih ne
reparandum(po-9,po-8)
reparandum(po-9,po-7)
case(ukrepih,po-9)
~~~

~~~ sdparse
kako k- kako hodiš
advmod(hodiš,kako-3)
reparandum(kako-3,kako-1)
reparandum(kako-3,k-)
~~~

### besedni red
~~~ sdparse
s katerimi rastlinami v povezavi
case(rastlinami,s)
det(rastlinami,katerimi)
case(povezavi,v)
nmod(rastlinami,povezavi)
~~~

~~~ sdparse
nenazadnje so bili voditelji dolgo časa , voditelji TV dnevnikov , dolgo časa tudi napovedovalci
appos(voditelji-4,voditelji-8)
nsubj(napovedovalci,voditelji-4)
obl(napovedovalci,časa-13)
advmod(časa-13,dolgo-12)
reparandum(časa-13,časa-6)
advmod(časa-6,dolgo-5)
advmod(napovedovalci,nenazadnje)
advmod(napovedovalci,tudi)
aux(napovedovalci,so)
cop(napovedovalci,bili)
punct(voditelji-8, ,-7)
punct(voditelji-8, ,-11)
nmod(voditelji-8,dnevnikov)
nmod(dnevnikov,TV)
~~~

### veriženje discourse
~~~ sdparse
aja ja dobro
discourse(dobro,aja)
discourse(dobro,ja)
~~~

~~~ sdparse
okej ja
discourse(okej,ja)
~~~

~~~ sdparse
ja ja … ja
discourse(ja-1,ja-2)
discourse(ja-1,ja-4)
~~~

### veriženje discourse
~~~ sdparse
hvala vam za eee vašo pripombo
obj(hvala,vam)
nmod(hvala,pripombo)
~~~

### expl: to
~~~ sdparse
tako da to pol nekega posebnega izobraževanja pa verjetno ni ne
expl(ni,to)
~~~

### kazalni zaimki kot discourse
~~~ sdparse
pa ti bo vleklo ono v nos noter
discourse(vleklo,ono)
~~~

~~~ sdparse
še vedno rajši tako v malih zasedbah bolj ne ?
discourse(zasedbah,tako)
~~~

### appos v govoru
~~~ sdparse
najbogatejši slovenec gospod [name:personal] je pripravljen da zapusti zemljo
appos(slovenec,gospod)
flat:name(slovenec,[name:personal])
~~~

## Dodatki v smernice December 2023

### Zadostnost in presežek
~~~ sdparse
Pri nas pomanjkanje časa še ni tako pereče , da bi že razmišljali o tem .
advmod(pereče,tako)
advcl(pereče,razmišljali)
~~~

~~~ sdparse
Nikoli ni bilo toliko socialno patoloških pojavov kot danes .
det(pojavov,toliko)
obl(toliko,danes)
~~~

### Sole obj
~~~ sdparse
Županja se je odločila , da jim bo občina po svojih močeh pomagala .
iobj(pomagala, jim)
~~~

~~~ sdparse
Takoj nam je povedal , da morajo biti za to odgovorni drugi .
iobj(povedal, nam)
ccomp(povedal, odgovorni)
~~~

### Premi govor s ccomp
~~~ sdparse
Takole se je glasil : " Ali mora kmet res vedno le ubogati ? "
ccomp(glasil, mora)
~~~

~~~ sdparse
" To je Victor , " je pojasnil Victor Riccio .
ccomp(pojasnil, Victor-4)
cop(Victor-4, je-3) 
~~~

### Za + nedoločnik
~~~ sdparse
Vzemi s sabo nekaj za se ogrniti .
acl(nekaj, ogrniti)
case(ogrniti, za)
obj(ogrniti, se)
obj(Vzemi, nekaj)
~~~

~~~ sdparse
Džingli so res za popizditi hudi .
advcl(hudi, popizditi)
case(popizditi, za)
cop(hudi, so)
~~~
