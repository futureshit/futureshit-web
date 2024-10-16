---
sidebar:
  nav: "docs"
categories: anleitung 
tags: passwörter sicherheit
title: Sichere Passwörter
toc: true
toc_label: "Inhalt"
toc_icon: "star"
---

Ein Passwort hier, ein Passwort da. Überall sind wir auf Passwörter angewiesen, egal ob bei der Bank, Krankenkasse, Email oder auf Arbeit. Wir müssen uns eine Menge merken, denn: niemals ein Passwort mehrfach verwenden! Wird zB. ein Onlineshop gehackt, bei dem du mal bestellt hast, dann kann dabei dein Passwort zusammen mit deiner verwendeten Email-Adresse ausgelesen werden. Ist das Passwort dann dasselbe wie das deines Email-Postfaches, dann kann der Angreifer sehr einfach deinen Account übernehmen. Oder natürlich auch andere mit der Email-Adresse registrierte Dienste.

Überprüfe ob deine Email-Adresse schon einmal in einem Hack vorgekommen ist: https://haveibeenpwned.com  

## Sichere Passwörter

Um sich sichere Passwörter zu generieren und vor allem komfortabel speichern zu können, sollte man einen Passwortmanager (zB. KeePassXC) benutzen. Dort kann man alle seine Logins verwalten und sich sehr komplexe  (=sichere) Passwörter generieren lassen. Der Vorteil dabei ist auch, das man sich lediglich ein Passwort - nämlich das für den Passwortmanager - merken muss.

Was ein sicheres Passwort ausmacht: Groß/klein, Buchstaben, Zahlen, Zeichen, Länge, Komplexität, keine privaten Daten

## Unsicherhere Passwörter

Ein unsicheres Passwort ist mit relativ wenig Aufwand schnell zu "knacken":

6-stelliges Passwort: 	0,006 Minuten
7-stelliges Passwort	: 	0,47 Minuten
8-stelliges Passwort	: 	33,9 Minuten
9-stelliges Passwort: 	40,7 Stunden
10-stelliges Passwort: 	122,1 Tage

Mit heutigen Rechenkapazitäten bei den Behörden oder in der Cloud ist es auch möglich komplexe Passwörter mit entsprechen Leistung in kurzer Zeit zu brechen.

## Merkbare, sichere Passwörter bilden

Merkbare Passwörter kann man sich zB. wie folgt bilden:

1. einen Satz bilden (mittlere Sicherheit):

Am liebsten esse ich Pizza mit vier Zutaten und extra Käse!
= 
AleiPm4Z+eK!

2. zufällige Wörter aus dem Wörterbuch + Zeichen (höhere Sicherheit):

Montag armes Pferd Diesel klein Nasa warum
= 
Montag_armes_Pferd_Diesel_klein_Nasa_warum?

## Passwordmanager

Der Passwortmanager lässt sich auch mit dem Browser verknüpfen, so dass man automatisch bei bekannten Websites eingeloggt werden kann. Diese Funktion ist sicherer als die im Browser integrierten Passwortmanager zu benutzen, denn auch dieser kann von Hackern über bösartige Websites oder Trojaner ausgelesen werden.

KeePassXC (oder auch andere) Passwortmanager lassen sich in der Regel auch auf mobilen Geräten benutzen, so kann man alle genannten Funktionen auch unterwegs benutzen. Auch Smartphones und Tablets sind durch den Zugang zum Internet Hackern ausgesetzt, also sollte natürlich auch dort auf eine sichere Benutzung geachtet werden.

## Weitere Hinweise zum sicheren Umgang mit Passwörtern

- wenn möglich Zwei-Faktor-Authentifizierung benutzen
- Passkeys (Hardwaretoken) zur Authentifizierung statt Passwort benutzen
- Passwort nicht analog aufschreiben & ablegen
- Passwort nicht in Textdateien unverschlüsselt speichern
- Passwörter regelmäßig wechseln

## Tools
- Offline Wörterbuch-Passwort Generator mit Würfeln: Diceware 
- Online Wörterbuch-Passwort Generator mit Erklärung: https://diceware.rempe.us
- DIY-Passwortmanager zum selber betreiben: Vaultwarden