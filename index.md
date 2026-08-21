---
title: Datenschutzerklärung — Feldnotiz
---

# Datenschutzerklärung — Critique Incognito

Stand: 2026-08-19 · gilt ab Version 1.0.0

> Diese Datei liegt unter einer öffentlich erreichbaren URL; dieselbe URL steht in App Store
> Connect als *Privacy Policy URL*. Der Wortlaut hier und der Text in
> `Feldnotiz/Settings/PrivacyView.swift` sagen dasselbe aus und müssen dasselbe sagen — wer eines
> ändert, ändert beides.

## Kurzfassung

Le Critique erhebt keine personenbezogenen Daten. Es gibt kein Konto des Anbieters, keinen Server des
Anbieters, keine Analyse-Werkzeuge und keine Werbung. Alles, was du erfasst, bleibt auf deinem
Gerät.

**Eine Ausnahme, und nur du kannst sie einschalten:** Hinterlegst du deinen eigenen
OpenAI-API-Schlüssel und tippst bei einem Besuch auf „Mit Modell überarbeiten", werden die Daten
genau dieses Besuchs an OpenAI gesendet, damit ein Sprachmodell deinen Entwurf umformuliert. Ohne
Schlüssel geschieht das nie, und ohne diesen Tipp geschieht es auch mit Schlüssel nicht.
Einzelheiten in Abschnitt 6.

## 1. Verantwortlicher

Leon Köllerwirth
Paracelsusweg 5, 33689 Bielefeld, Deutschland
mhlihel@gmail.com

## 2. Welche Daten die App verarbeitet

Ausschließlich das, was du selbst einträgst:

- **Besuche und Beobachtungen** — Betriebsname, Zeitpunkt, Checklistenwerte, freie Notizen.
- **Bewertungen und Entwurfstexte** — deine Note und der Text, den du daraus schreibst.
- **Standortdaten** — nur wenn du die Umgebungssuche startest, siehe Abschnitt 4.
- **Diktierte Notizen** — als Text, siehe Abschnitt 5.
- **Dein OpenAI-API-Schlüssel** — nur wenn du ihn einträgst, siehe Abschnitt 6.

Diese Daten liegen im geschützten Speicherbereich der App auf deinem Gerät; der Schlüssel liegt im
Schlüsselbund des Geräts. An den Anbieter werden sie nicht übermittelt. An Dritte werden sie nur
übermittelt, wenn du die Entwurfshilfe aus Abschnitt 6 selbst einrichtest und auslöst.

## 3. Rechtsgrundlage und Zweck

Die Verarbeitung erfolgt allein auf deinem Gerät zur Erfüllung des Zwecks, den du mit der Nutzung
verfolgst (Art. 6 Abs. 1 lit. b DSGVO): das Festhalten eigener Beobachtungen und das Verfassen
eigener Texte daraus. Eine Übermittlung an den Anbieter findet nicht statt, weshalb der Anbieter
über diese Inhalte auch keine Auskunft geben kann — er hat sie nicht. Für die Übermittlung an
OpenAI in Abschnitt 6 ist die Rechtsgrundlage deine Einwilligung (Art. 6 Abs. 1 lit. a DSGVO),
erteilt durch das Hinterlegen des Schlüssels und den einzelnen Tipp auf „Mit Modell überarbeiten";
du widerrufst sie, indem du den Schlüssel entfernst.

## 4. Standort

Die App fragt den Standort nur, wenn du in der Ansicht „Neuer Besuch" die Umgebungssuche
ausdrücklich startest, und nur für die Dauer dieser Suche. Der Standort dient dazu, dir Betriebe in
der Nähe vorzuschlagen, damit du den Namen nicht abtippen musst. Er wird nicht an den Anbieter
übermittelt und nicht dauerhaft gespeichert; lediglich die Koordinaten eines von dir gewählten
Betriebs werden dem Besuch beigelegt.

Die Suche selbst läuft über Apple Karten (MapKit). Dabei gelten ergänzend Apples Bestimmungen für
Kartendienste. Verweigerst du die Freigabe, funktioniert die App vollständig weiter — der Name wird
dann eingetippt.

## 5. Diktat

Eine diktierte Notiz wird auf diesem Gerät in Text umgewandelt (Apples Spracherkennung, ausdrücklich
auf dem Gerät angefordert). Der Ton wird nicht gespeichert, und weder Ton noch Text werden
übertragen. Steht die geräteinterne Spracherkennung nicht zur Verfügung, unterbleibt das Diktat —
ein Ausweichen auf eine Servererkennung findet nicht statt.

## 6. Entwurfshilfe mit deinem eigenen OpenAI-Schlüssel

Diese Funktion ist **standardmäßig aus**. Die App bringt keinen Schlüssel mit, verkauft keinen und
verlinkt keinen. Sie tut nichts, solange du keinen eigenen hinterlegst.

**Was übermittelt wird**, und zwar erst beim Tippen auf „Mit Modell überarbeiten" bei einem
einzelnen Besuch: die Beobachtungen dieses Besuchs, deine freie Notiz dazu, der von der App aus der
Checkliste gebaute Entwurf und dein Stilprofil. **Nicht übermittelt werden** Fotos, Belege,
Standortdaten, andere Besuche und alles, was du nicht selbst ausgelöst hast.

**An wen.** An OpenAI, über deinen eigenen API-Schlüssel und damit über deinen eigenen Vertrag mit
OpenAI. Es gilt zusätzlich deren Datenschutzerklärung und deren Umgang mit API-Daten. Der Anbieter
dieser App sieht die Übermittlung nicht, protokolliert sie nicht und verdient daran nichts; die
Kosten rechnet OpenAI unmittelbar mit dir ab.

**Wo der Schlüssel liegt.** Im Schlüsselbund dieses Geräts, gerätegebunden
(`kSecAttrAccessibleWhenUnlockedThisDeviceOnly`). Er wandert nicht über den iCloud-Schlüsselbund auf
andere Geräte, steht in keiner Sicherung, die auf fremder Hardware wiederhergestellt wird, und
erscheint in keiner Fehlermeldung. Unter „Mehr → Entwurfshilfe" entfernst du ihn jederzeit; danach
verlässt wieder nichts das Gerät.

**Was die Funktion nicht darf.** Das Modell überarbeitet ausschließlich einen Entwurf, der bereits
aus deinen Beobachtungen gebaut wurde. Jeder zurückgegebene Satz muss auf eine deiner Beobachtungen
zeigen; ein Satz ohne Beleg wird verworfen, bevor du ihn zu sehen bekommst. Die App veröffentlicht
nichts, nirgendwo, unter keinen Umständen.

## 7. Tracking, Analyse, Werbung

Keine. Die App enthält keine Analyse- oder Werbe-SDKs, keine Fremdbibliotheken mit Netzzugriff und
keine geräteübergreifende Kennung. Das App-Tracking-Transparency-Fenster erscheint nicht, weil
nichts getrackt wird.

## 8. iCloud

Ein Abgleich über deine **private iCloud-Datenbank** ist geplant und derzeit ausgeschaltet. Wird er
aktiviert, liegen die Daten in deinem eigenen iCloud-Konto; der Anbieter hat darauf keinen Zugriff.
Es gilt dann ergänzend Apples Datenschutzerklärung. Diese Erklärung wird vor dieser Änderung
angepasst.

## 9. Deine Rechte

Gegenüber dem Anbieter dieser App laufen Auskunft, Berichtigung und Löschung ins Leere, weil er
nichts von dir hat. Du übst sie unmittelbar in der App aus:

- **Einsehen und berichtigen** — jeder Besuch ist jederzeit zu öffnen und zu ändern.
- **Einzeln löschen** — Besuche lassen sich einzeln entfernen.
- **Vollständig löschen** — „Mehr" → „Alle Daten löschen" entfernt alles auf einmal. Die App zu
  deinstallieren entfernt ebenfalls alles.

- **Übermittlung beenden** — „Mehr" → „Entwurfshilfe" → „Entfernen" löscht deinen OpenAI-Schlüssel
  aus dem Schlüsselbund. Danach verlässt wieder nichts das Gerät.

Hast du die Entwurfshilfe genutzt, liegen die dabei übermittelten Texte zusätzlich bei OpenAI.
Diese Rechte machst du dort über dein eigenes OpenAI-Konto geltend — der Anbieter dieser App hat
darauf keinen Zugriff und kann dort nichts für dich löschen.

Darüber hinaus stehen dir die Rechte aus Art. 15–21 DSGVO zu sowie ein Beschwerderecht bei einer
Aufsichtsbehörde.

## 10. Speicherdauer

Solange du die Daten behältst. Der Anbieter löscht nichts und kann nichts löschen. Für Texte, die
du über deinen eigenen Schlüssel an OpenAI geschickt hast, gilt die Aufbewahrungsfrist deines
OpenAI-Kontos.

## 11. Kinder

Die App richtet sich an Erwachsene und erhebt keine Daten von Kindern.

## 12. Änderungen

Änderungen werden hier mit neuem Datum veröffentlicht. Wesentliche Änderungen — insbesondere die
Aktivierung des iCloud-Abgleichs oder eine Server-Komponente — werden zusätzlich in der App
angekündigt.
