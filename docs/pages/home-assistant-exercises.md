---
layout: page
title: Exercises
permalink: /home-assistant/exercises
---

# 🤸📖 Home Assistant Exercises
{: .pt-3 }

Dit zijn slechts enkele voorstellen, gebruik zeker je eigen verbeelding om leuke ideeën uit te werken.
(of laat ChatGPT iets voor jou verzinnen 😉)

## ESPHome

De oplossingen voor deze oefeningen worden tijdens het bootcamp geüpload.

1. Voeg een nieuw ESP32 device toe in ESPHome and give it a manual IP adress.
2. Voeg 'left button' en 'right button' toe respectievelijk op poorten GPIO16 en GPIO27.
3. Voeg de 'steam' sensor toe op poort GPIO34.
4. Voeg de 'Motion' sensor toe op poort GPIO14.
5. Voeg de 'Led' toe op poort GPIO12.
6. Voeg een switch 'Buzzer' toe op poort GPIO25 (zet de buzzer op 2000Hz en 15% volume).
7. Voeg de 'RGB Led' toe op poort GPIO26, zorg voor een slider van 0 tot 255 om de helderheid te bepalen, probeer zeker ook eens de effects toe te voegen als opties.
8. Voeg de 'Humidity & Temprature' toe op poort GPIO13.
9. Voeg de 'Deur' servo motor toe op poort GPIO13. Zorg dat je deze kunt instellen tussen de -100 en 100 die zich vertaalt naar -1 en +1 voor de servo motor.
10. Voeg de 'Window' servo motor toe op poort GPIO05. Zorg dat je deze kunt instellen tussen de 0 en 100 die zich vertaalt naar +1 voor de servo motor.
11. Voeg de 'Fan' motor toe op poort GPIO18 en GPIO19. Zorg dat je deze kunt instellen tussen de -100 en 100 die zich vertaalt naar max speed counter clockwise en max speed clockwise

## Home Assistant Automation

### Automations

- Voeg een automation toe waarbij als je op de 'left button' drukt de 'LED' aangaat en op de 'right button' terug uit.
- Voeg een automation toe waarbij om de minuut de 'buzzer' even afgaat.
- Voeg een automation toe waarbij als ik thuis kom de deur opendraait. (Pas dit later aan zodat je bij toekomen of weggaan bepaalde scripts uitvoert.)

### Scenes

- Ochtend: raam open, buzzer gaat af en alle lichten vol aan.
- Avond: raam dicht, en lichten op 20%.
- Buitenshuis: raam dicht, alle lichten en fan uit.

### Scripts

- Maak een script voor een alarm: 1sec buzzer gevolgd door 3sec 'RGB Led' in rainbow effect en dit on repeat.
- Maak een script dat checkt als de juist badge gescant wacht op input van één van de buttons en dan de deur in gepaste richting doet draaien.
- Maak een script voor een brand routine.

## Home assistant dashboards

- Gebruikt `card-mod` om de css van de cards aan te passen. Pas de kleur van de tekst aan, maak de background transparant, ... . 
- Gebruik de `button-card` om zelf knoppen te designen.
- Gebruik de `mini-graph-card` om een grafiek van de tempratuur te tonen.
- Gebruik de `swipe-card` om alle sensor cards achter elkaar te steken.
- Gebruik de `stack in card` om enkele cards samen te voegen zonder randen. Denk bijvoorbeeld aan de tempratuur en humidity die samen horen.
- Gebruik `sweet home 3D` om een floorplan te maken en dat toe te voegen als dashboard m.b.v. NdR91.
