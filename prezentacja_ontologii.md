---
author: Bartłomiej Kokoszka
title: Sprawozdanie z zajęć 
subtitle: 8.12.2017r
date: 08.11.2020
theme: Lublin
output: beamer_presentation
header-includes: 
    \usepackage{xcolor}
    \usepackage{listings}
---



## Podstawa Linked Open Data

![](pics/obrazek1.png){}

* Podmiot - subject
* Orzeczenie - predicate
* Dopełnienie lub obiekt - object

Składając te trójki razem uzyskujemy coraz bardziej złożone grafy.

<!---  Zajęcia zaczęliśmy od powtórzenia czym jest URI, IRI. URI- Uniform Resource Identifier- służy do identyfikacji zasobów w sieci. IRI- Internationalized Resource Identifier- również identyfikuje zasoby, ale uwzględnia jeszcze inne znaki niż te w alfabecie łacińskim. Podstawą Open linked data są trójelementowe grafy składające się z: ●Podmiot - subject; ●Orzeczenie - predicate; ●Dopełnienie lub obiekt - object. Składając te trójki razem uzyskujemy coraz bardziej złożone grafy  -->


## Sieć semantyczna

![](pics/obrazek2.png){} ![](pics/obrazek3.png){}

Języki RDF powstały do opisu sieci semantycznej.

1. RDF- Resource Description Framework

2. RDFs- Resource Description Framework Schema

3. RDFa- Resource Description Framework in Attributes

<!--- RDF- Resource Description Framework- jest środowiskiem(wzorcem języków) dla wyrażania informacji o zasobach, opracowana przez W3C. Zasobem może być wszystko np. dokumenty, ludzie, przedmioty fizyczne, pojęcia abstrakcyjne. RDF jest przeznaczony dla aplikacji, które przetwarzają informacje w Internecie. RDF jest wspólnym środowiskiem pomiędzy komputerami, w którym można wymieniać informacje w taki sposób, że jej wymiana nie prowadzi do utraty sensu.  -->

## Przykład grafu RDF



Z naszego przykładu:

1. Subject: http://dbpedia.org/resource/Poland

2. Predicate: \textcolor{yellow}{http://dbpedia.org/ontology/officialLanguage}

3. Object: **http://dbpedia.org/resource/Polish_language**

