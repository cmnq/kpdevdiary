---
layout: post
title:  Pimp my site odc 1 Locked
date:   2019-06-20 12:24:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img:  mockupresp2.png # Add image post (optional)
tags: [Dev, Pimp my Site]
author: Kamil Podufalski # Add name author (optional)
---
 Cześć 

Poprzedni post był o moim portfolio, z którego jak już wspomniałem - mimo, iż jest bez fajerwerków, to jestem z niego dumny. Po pierwsze dlatego, że starałem się w nim wykorzystać wiedzę, którą zdobywałem systematycznie przez dłuższy okreś, a po drugie - po prostu patrząc na moje pierwsze, pokracznie pisane strony - widzę progres. Z tego drugiego też powodu bliżej przyjrzałem się sekcji ze swoimi projektami i widzę tam (bardzo) delikatnie mówiąc sporo do poprawy. Bo skoro samo portfolio pisałem w scss, z odpowiednim nazewnictwem bloków w htmlu, responsywnymi obrazami, a gulp czy npm zadbał o prefiksy i minifikację - to czemu cała reszta projektów jest napisana w dość nagannym stylu spaghetti? Strony wyglądają w większości ładnie, estetycznie - dlatego, zamiast całkowitego wyrzucenia ich do kosza, postanowiłem napisać je jeszcze raz - tym razem wykorzystując wiedzę, którą zdobywałem w późniejszym czasie. Na pierwszy ogień - Locked, czyli strona fikcyjnego escape-roomu, z którą z tego co pamiętam - miałem dość sporo problemów. Była to przede wszystkim pierwsza strona, na której bawiłem się flexboxem oraz pierwsza, na której użyłem efektu parallax. O ile flex wyszedł nawet spoko, było responsywnie i nie rozjeżdzało na co drugim nośniku, to parallax wyszedł tragicznie - na stronie niskie fpsy łapały nawet naprawdę dobre komputery, a na urządzeniach mobilnych o parallaksie nie było mowy. W dodatku contact-form był zrobiony w pół minuty w mało atrakcyjnym stylu. 

Jak to wyglądało na początku? 
![Sekcja-about]({{site.baseurl}}/assets/img/old-0.png)
![Sekcja about]({{site.baseurl}}/assets/img/old-1.png)
![Sekcja about]({{site.baseurl}}/assets/img/old-2.png)

Nie zmieniałem głownego celu tego projektu - praktyki flexboxa, rozmieszczania ikon i parallaksu. Nadal będzie to prosty one-page bez żadnych skomplikowanych aplikacji czy efektów. 

Zaczynając od postaw - tym razem przy "odnowieniu" tego projektu dodatkowo potrenuje sobie gulpa, więc to tym task runnerem uruchomimy sobie gulpa i browsersynca a na końcu dodamy prefiksy i skompresujemy końcowy css.

Zaczynając od heada - FontAwesome został zastąpiony IcoMoon i ikonami svg. Poznałem je podczas robienia kursu Advanced CSS&Sass Jonasa Schedtmanna na Udemy - to świetnie rozwiązanie, dużo większa (i ładniejsza) baza ikon.
![Sekcja about]({{site.baseurl}}/assets/img/new-1.png)


Nawigacja pozbawiona odniesień do klas była napisana prostym skryptem w jQuery - do zmiany praktycznie wszystko. Zostanę jedynie przy opcji, by faktycznie menu było "sticky" i by można było krążyć między sekcjami bez konieczności scrollowania w nieskończoność. Zrezygnuje jednak z jQuery, ba! nawet js sobie odpuszczę - zrobię to za pomocą samego CSS (sorry IE). 

Sekcja z ikonami jak już wyżej wspomniałem zastąpiona .svg z IcoMoon. Wyrównanie z 2 na 3 równe kolumny, co jest znacznie bardziej przejrzyste. Ograiczyłem też nadmiar znaczników, spanów, etc.

Parallaksy to ciekawy efekt. Robi wrażenie, szczególnie na stronach o podobnej tematyce, jaką właśnie imituję. No ale, to, że w pierwszej wersji zdjęcia miały rozdzielczość po 5000px i ponad 3mb wagi to już kryminał. Przynajmniej wiadomo, dlaczego fps'y leciały drastycznie w dół. Wszystko rzecz jasna zmniejszone, zoptymalizowane i z uzupełnieniem prefiksów na reszte przeglądarek.

Sekcja z prezentacją poszególnych escape roomów jest teraz dużo bardziej zoptymalizowana. Obrazy oraz z rozmiarach w -mega ważą teraz w -kilo bajtach, jest porządek w kodzie i w końcu wszystko ma swoje miejsce (inspirując się architekturą 7-1).

W tej wersji darowałem sobie mapę pobraną z GoogleMaps. Cały footer w zasadzie sobie darowałem. Strona/makieta zakończona jest blank formularzem, który imo ciekawie wpasował się w całe tło. Dodawanie kolejnych linków, logotypu czy stopki biorąc pod uwagę, że cały czas u rogu ekranu mamy menu wydało mi się zupełnie nieuzasadnione. 
![Sekcja about]({{site.baseurl}}/assets/img/mockupresp1.png)
A więc to by było na tyle. Malutki projekcik, który nadal pozostał malutki ale tym razem został napisany znacznie szybciej, poprawniej i lżej. Trochę się pośmiałem z samego siebie, bo chyba w pierwotnej wersji, patrząc na to jak nazywałem elementy w htmlu - chyba chciałem stworzyć jakiegoś własnego bem'a. W dodatku bardzo dziwne media queries czy mistyczna klasa o nazwie `stopro`. Trzeba umieć śmiać się z samego siebie - ale nie szyderczo bo szydery i jadu zdecydowanie za dużo na forach. Tak po ludzku stwierdzić - "damn, debil ze mnie", po czym się uśmiechnąć, poprawić i zapamiętać :P 

Demo strony możecie zobaczyć [Tutaj], a kod podejrzeć na [Github].

Do następnego

[Tutaj]:   http://cmnq.github.io/locked
[Github]: https://cmnq.github.com/locked





