# NightWithJulia2025
Event "Night With Julia" organised in 2025. Introduction course and a few problem to hack.
GPT or any other AI should be able to translate the content of this repo to English if necessary :)

## Co się będzie działo?

Wydarzenie będzie składało się z dwóch części:
* Standardowy kurs podstaw języka Julia
* (Hakaton) Problemy do rozważania w grupach/samemu. Część z nich będzie ściśle związana z jakaś biblioteką (do nauki konkretnych bibliotek).

Standardowe wprowadzenie do języka potrwa do XXXX do mniej więcej YYYY. Pozostały czas będzie można przeznaczyć na ćwiczenie tego co udało się nauczyć na prostych przykładach (to jest jedyny skuteczny sposób nauki programowania).

Hackaton również zacznie się o XXXX i potrwa do końca wydarzenia, czyli około ZZZZ.
Przygotujemy listę problemów (o różnym poziomie trudności) nad którymi będzie można posiedzieć w grupach albo samemu. Część z nich będzie związana z wykorzystaniem jakiś konkretnych bibliotek, więc jest szansa na zapoznanie się z tymi które uznacie za interesujące.

Przez cały czas trwania wydarzenia będzie dostępnych kilka osób, które bedą mogły wam pomóc z powstałymi trudnościami.

## Co mam zrobić przed warsztatami?

Osoby przychodzące prosimy przynieść własne komputery, najlepiej z zainstalowaną (i działającą) Julią.
Sprawdzałem i na Windowsie instalacja zajmuje 5 minut (kilka kliknięć myszką). Na komputerach (linux/macOS) też.
Bardzo proszę to zrobić PRZED warsztatami, oszczędzimy w ten sposób bardzo dużo czasu (3 lata temu straciliśmy na to 1.5h).
- **Julia**: https://julialang.org/install/ albo https://docs.julialang.org/en/v1/manual/installation/
Jeśli ktoś ma problem z instalacją, to zachęcam do kontaktu z organizatorami PRZED warsztatami.
Dla osób z Windowsem, które nie miały wcześniej do czynienia z komputerami zapraszam do [prostego opisu instalacji ponizej](Instalacja Julii)

Zalecane (ale opcjonalne): Fajnie jest mieć jakiś edytor do pisania inny niż notatnik.
Większość community korzysta z edytora **VSCode**: https://www.julia-vscode.org/docs/dev/gettingstarted/
Proszę zwrócić uwagę, że powyższy link sugeruje instalację Julii ze strony zaczynającej się od **This page is not for most users**. Wy jesteście most users więc klikacie link here.

Jak ktoś nie chce instalować Julii u siebie, to można korzystać z Julii online. Proponuję https://juliahub.com
Trzeba się zalogować, co zajmuje chyba więcej czasu niż instalacja lokalnie.

W dalszej części kursu przydadzą się dodatkowe biblioteki. Można je instalować w tracie kursu.
Ich kompilacja zajmie pewnie kilkanaście minut, bo nie wszyscy mamy szybkie komputery :(.
Jak ktoś chce oszczędzić czas, to zachęcam do instalacji tych pakietów:
* StatsKit
* CairoMakie
* DifferentialEquations
* QuadGK
* Plots

Można to zrobić uruchamiając Julię i wpisując w REPL (ten prompt julia>) taką linijkę:
```julia
import Pkg; Pkg.add(["StatsKit", "CairoMakie", "DifferentialEquations", "QuadGK", "Plots"])
```

## Instalacja Julii
1. Zainstaluj `Julia` z Microsoft Store.
2. Zainstaluj `Visual Studio Code` z Microsoft Store.
3. Zainstaluj rozszerzenie Julia w VS Code (używając menu po lewej).
4. Utwórz plik `dodawanie.jl` o treści
```5+7```
i uruchom go.

Masz 15 minut.
