---
layout: post
title:  Cześć, jestem Kamil - Portfolio
date:   2019-06-19 14:10:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: portfolio-1.jpg # Add image post (optional)
tags: [HTML/CSS, Dev]
author: Kamil Podufalski # Add name author (optional)
---

Cześć!

Im so excited! Moje pierwsze portfolio właśnie wylądowało na Github Pages. Z tego też powodu chciałbym go trochę rozebrać na czynniki pierwsze i się nieco pochwalić. 

Zanim ono powstało, uwierzcie mi - ogrom czasu poświęciłem nad samym jego planowaniem. Układ oraz treść chociaż był gdzieś z tyłu głowy już dawno rozpisany, tak zmieniał się dynamicznie na każdym z etapów produkcji. Z jednej strony chciałem pokazać jak najwięcej, z drugiej mimo wszystko pozostać przy wersji minimalistycznej, mega skondensowanej. Dlatego też w surowej wersji była mieszanka Flexa z gridem, masa animacji, przejść, video-background, dwie wersje językowe, karuzela, itp... Większość rzeczy, które przed chwilą wymieniłem poszły do kosza. Dlaczego? 

To był zdecydowany przerost formy nad treścią - ok, przyznam - sekcja, w której tle widnieje ktoś wklepujący kod wyglądała bardzo ładnie ale ... kompletnie nie komponowała się z całą resztą i szatą graficzną, którą już miałem ustalną. Mieszanka grida z flexem i kasacja tego "tworu" jest oczywista. Animacje, przejścia, karuzele to też "bajery", które bardziej odbierałyby Waszą uwagę przed treścią i konkretami, które na stronie chciałem umieścić. No i swoją drogą - znacznie ją obciążyły, a moim celem było też stworzenie lekkiego projektu, który bez problemu wczyta każdy, a PageSpeed Insights pokaże mi zielone światło. 

Nie mogłem oprzeć się tylko jednej rzeczy - particle.js. Tak, tak - wiem doskonale... Masa juniorów i początkujących osób używa tego w swoich pierwszych portfoliach, jest to kompletnie oklepany skrypt, lecz w połączeniu z kolorystyką, którą sobie wybrałem dała naprawdę świetny efekt. 

Ale od początku. Opracowałem sobie swój sandbox i wstępny design. Przejście między sekcjami dzielone będzie przy użyciu clip-path, a cała strona będzie oddzielona od krawędzi wyraźnym marginesem. Paleta kolorów z początku miała być zielono-biała, później była też opcja z fioletem, ostatecznie zdecydowałem się pozostawić następujące wartości :

![kolory]({{site.baseurl}}/assets/img/colors.png)

Logotypów miałem w głowie masę - od sygnatur, po bardziej zaawansowane dzieła. Stwierdziłem jednak, że nie jestem ani żadną marką, ani kimś, kto powinen ukrywać się za jakimkolwiek logo. "Zrezygnowałem" z niego i wydaje mi się, że zwykłe "cześć, jestem Kamil" wygląda dużo bardziej naturalnie w mojej obecnej sytuacji, niż font z autografem czy jakiś tam herb. 
Jak wcześniej wspomniałem - w "skromnym" headerze obraz umieściłem pod gradientem niebieskich odcieni, background, a nim "interaktywny" particle.js ze sloganem, który jest podstawowym założeniem tej strony.

![header]({{site.baseurl}}/assets/img/header.png)

Kolejna sekcja a'la about miała w pierwotnym założeniu wykorzystywać efekt pisania na maszynie. Nie ukrywam, że byłem na to konkretnie nastawiony ale w praktyce, aby nie było to zbyt męczące dla odbiorcy - treść musiałbym ograniczyć praktycznie do minimum. No bo kto z Was patrzyłby jak powoli na ekranie ukazuje się tekst, który widzicie na zrzucie poniżej? W moim bio chciałem umieścić zdecydowanie nieco więcej. Z początku miało być parę informacji + mój aktualny stack, ale ten pomysł też rozbiłem na dwie części. Rozbudowałem bio uzupełniając informacje dlaczego w ogóle się zainteresowałem tym tematem no i jeden akapit, w którym subtelnie stram się Wam "sprzedać"...
![about]({{site.baseurl}}/assets/img/about.png)

...a mój stack powędrował do drugiej sekcji. To cięzkie napisać o swoich umiejętnościach i ich poziomie. Każdy patrzy na to zupełnie inną skalą. Dla jednych dobra znajomość CSS'a to po prostu napisanie poprawnego layoutu, drugi zaś powie, że coś tam z niego jarzy, a krzywą Beeziera wklepuje z pamięci. Zastosowałem w tej sekcji karciany układ ze wszystkim co po trochu poznałem. Darowałem sobie diagramy, procenty czy paski progresu. Po prostu karta z zagadnieniem, narzędziem czy technologią, krótki opis i ... tyle. 

![skills]({{site.baseurl}}/assets/img/skills.png)

Następna sekcja powstała dość spontanicznie ale jest dla mnie niesamowicie istotna. Są to cele, które chciałbym osiągnąć. Taka swoista lista życzeń, które mam nadzieję, wkrótce będzie realizowana. Z początku ta sekcja wyglądała identycznie jak ta powyżej - układ kart, nieco bardziej zaawansowane technologie, które w przyszłości bym chciał poznać - jak React, Vue, Gatsby, Webpack, etc... Jednak poza technologiami, które wymieniłem, najbardziej ze wszystkich zależy mi po prostu na zespole, mentorze, pracy i zaufaniu. Jeden z kolegów mi powiedział, że po pierwszym dniu w jego nowej pracy, w której czuł się kompletnie zagubiony i zdezorientowany, nauczył się więcej, niż przez rok swoich studiów (pozdro Rafał). Jestem tego samego zdania, że żaden samotnie przerobiony kurs, poradnik, przeczytana dokumentacja nie da tyle co po prostu praca w zespole, doświadczenie, słowa mentora.
Ale tak gwoli ścisłości - dyskretna sekcja z ikonkami Vue, Reacta i Gatsbyego też się znalazła :).

![cel1]({{site.baseurl}}/assets/img/cel1.png)
![cel2]({{site.baseurl}}/assets/img/cele2.png)

Przy sekcji z projektami miałem chyba najwięcej zabawy. Znowu zrobiłem opcje identyczną jak w sekcji z umiejętnościami, tj. karta wycięta clip-pathem, "logo", krótki opis i odnośniki do wersji live i kodu bezpośrednio na Githubie. Nie dość, że wyglądało to kiepsko, to jeszcze byście mi zarzucili pójście na łatwiznę - bo przecież w sumie skopiowałbym poprzednią sekcję i zmienił w niej treść. W drugiej wersji zastosowałem efekt parallaksy, czyli tego obrazu wtopionego w strone. Przyznam, wyglądało super ale było średnio funckjonalne i bardzo ciężkie. Poza tym cała ta sekcja leżałaby na mobile. Postawiłem na wyjątkowo proste karty, bo w sumie liczy się projekt, który chce wam pokazać a nie piękna ramka do kiepskiego obrazu. 

![projects]({{site.baseurl}}/assets/img/projects.png)

Ostatnia sekcja miała być zwykłym formularzem z walidacją. Dałem sobie z tym spokój - z jednej strony bałem się, że ktoś wykorzysta te opcje żeby mnie nieco potrollować i uprzykrzyć mi życie, z drugiej jakoś mi po prostu nie pasowała. Poza tym było to dobre miejsce, by jeszcze raz przypomnieć, że jestem zdeterminowany by osiągnąć to co wymieniłem z sekcji "Cele". Jeśli ktoś po przejrzeniu portfolio by pomyślał - "Spoko, dajemy mu szanse" - miał dostęp do mojego LinkedIna, a tam wszystkie informacje i najszybszą formę kontaktu. Dla przypomnienia jeszcze Github :)

![interested]({{site.baseurl}}/assets/img/interested.png)

W momencie, w którym to czytacie, odnośnik do bloga jest już aktywny, wtedy jeszcze nad nim pracowałem, więc go chwilowo dezaktywowałem. Stopka miała być malutka, to przecież typowy, skromny one-page. Darowałem sobie kontakty, namiary, mapy, numery - skoro nie było tego nigdzie wyżej, nie było też sensu umieszczać go w footerze. 

![interested]({{site.baseurl}}/assets/img/footer.png)

I to by było na tyle, choć zdaje sobie sprawę, że jest to bardzo prosty, pozbawiony efektów one-page, to jestem z niego cholernie dumny. Napracowałem się przy nim, nadenerwowałem nad responsywnością, kombinowałem, dodawałem po czym usuwałem całe sekcje, które potrafiłem robić pół dnia. Był fun. Był to też pierwszy projekt, w którym wykorzystałem .scss i wygodnie wszystko sobie zautomatyzowałem npm scripts. Miałem przy okazji kodowania tej strony okazje do użycia w praktyce wiedzy, którą szczątkowo łapałem przez dłuższy czas, jak m.in clip-path, wspomniany sass, npm, Git, a także poznałem znaczenie kompresowania plików css, całego procesu "post-css", prefiksów, etc. 

Portfolio dostępne [Tutaj]

[Tutaj]: http://cmnq.github.io/portfolio