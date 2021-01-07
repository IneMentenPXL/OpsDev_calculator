[![Build Status](https://travis-ci.com/IneMentenPXL/OpsDev_calculator.svg?branch=main)](https://travis-ci.com/IneMentenPXL/OpsDev_calculator)

## a) Inventariseer kort in oplossing.md waarvoor travis-ci en heroku gebruikt worden. Wie zit er achter deze toepassingen? Wat is het doel?



## b) Na het verkennen van Travis-CI zal je merken dat er gebruikgemaakt wordt van yaml files. Wat voor soort files zijn dit? Hoe zijn die opgebouwd? Hoe zit een yaml syntax/structuur eruit?

Het zijn configuratiefiles. Het lijkt op Python.

## c) Met welke file uit jenkins kan je de .travis.yml file vergelijken?

Een .jenkinsfile.

## d) Wat zijn de limitaties van de “free” versie van Travis-CI juist? Bekijk ook zeker eens de integratie van Travis-CI & pull requests!



## e) Licht toe hoe de webhook integratie van travis en discord werkt. Wat heeft dit jou geleerd over het gebruiken van externe scripts?

Je kan een bericht van travis naar discord sturen.

## f) Wat is heroku juist? Waarvoor kunnen we dat gebruiken?

Het deployen van een app.

## g) Waarom maken we voor het gebruik van de API key & webhook URL gebruik van environment variabelen? Wat is daar het voordeel van? Zijn er nog andere manieren waarop je dit kon doen?

Dan kan je ze niet zien in de pipeline. Als je ze meerdere keren wil gebruiken, moet je ze maar 1 keer ingeven.
