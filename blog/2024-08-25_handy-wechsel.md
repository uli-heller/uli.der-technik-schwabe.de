Handy-Wechsel
=============

Grob von Samsung S9 auf S23.

Nuki
----

Aus der Erinnerung:

- Wechsel auf's neue Handy ging "erstmal" problemlos
- Danach funktioniert das alte Handy mit dem Nuki nicht mehr
- Neuen Nuki mit altem Handy eingerichtet -> der ist auf
  dem neuen dann nicht sichtbar

Übertragung neuer Nuki:

- Altes Handy
  - Nuki starten
  - Benutzer einladen -> QR-Code wird angezeigt
- Neues Handy
  - QR-Code scannen -> neuer Nuki ist sichtbar und funktioniert
  - Einstellungen - PIN -> klappt

Garmin
------

Paypal
------

Aus der Erinnerung: Keine Aktion erforderlich.

Kopfhörer
---------

Die Kopfhörer tauchen im Bluetooth-Menü auf mit dem Hinweis: Gekoppelt mit dem alten Telefon.
Also: Dort entkoppeln und mit dem neuen Telefon koppeln!

- Shokz OpenRun Pro: Ausschalten und dann beim Einschalten den Anschalt-Knopf gedrückt halten bis "Kopplung" angesagt wird

Google Authenticator
--------------------

Microsoft Authenticator
-----------------------

[Anleitung von Microsoft](https://support.microsoft.com/en-us/account-billing/back-up-account-credentials-in-microsoft-authenticator-bb939936-7a8d-4e88-bc43-49bc1a700a40#ID0EBF=Android)

Ablauf:

- Altes Handy
  - Authenticator starten
  - Oben rechts: Sicherung aktivieren
  - Anmelden

- Neues Handy
  - Microsoft Authenticator deinstallieren
  - Microsoft Authenticator installieren
  - Microsoft Authenticator starten
  - **Vor der Anmeldung**: Aus Sicherung reestaurieren
  - Anmelden
  - "Wiederherstellung nach Sicherung" wird durchgeführt
  - Bei vielen Konten wird angezeigt: "Aktion erforderlich"
    - Wenn man "drauf" geht, dann erscheint "Scannen Sie den von Ihrer Organisation bereitgestellten QR-Code"
    - Bei mir erfolgt diese Anzeige bei drei Konten
    - QR-Code-Handhabung: Siehe unten
    - Danach klappt die Anmeldung mit beiden Handys

- QR-Code für Konto anzeigen
  - Im Browser anmelden mit dem betreffenden Konto - net.uli.heller@xxx.com
  - Wechsel auf [Grundansicht - https://myapplications.microsoft.com/](https://myapplications.microsoft.com/)
  - Oben rechts - Nutzer - Konto anzeigen
  - Sicherheitsinformationen
  - Anmeldemethode hinzufügen - Authenticator-App -> mehrfach "weiter" -> QR-Code wird angezeigt
  - QR-Code mit neuem Handy scannen -> "Aktion  erforderlich" vwrschwindet
  - Browser: Weiter -> Eieruhr -> Timeout
    - Mehrfach ausprobiert
    - Immer Fehler
    - Bei neuer Anzeige der Sicherheitsinformationen sind beide Handys hinterlegt

- Microsoft-Account
  - uli.heller@daemons-point.com - persönlicher Account - Anmeldung via Browser klappt
  - uli.heller@daemons-point.com - geschäftlicher Account - Anmeldung via Browser klappt nicht

VPN
---

Das VPN von net.uli.heller@xxx.com funktioniert automatisch mit
dem neuen Handy sobald Microsoft Authenticator dort funktioniert!

PingID
------

Ablauf:

- Altes Handy
  - PingID-Anwendung öffnen
  - Gerät wechseln -> QR-Code wird angezeigt

- Neues Handy
  - PingID-Anwendung öffnen
  - QR-Code scannen

- Danach funktioniert PingID nur noch auf dem neuen Handy!

Links
-----

- [Anleitung von Microsoft](https://support.microsoft.com/en-us/account-billing/back-up-account-credentials-in-microsoft-authenticator-bb939936-7a8d-4e88-bc43-49bc1a700a40#ID0EBF=Android)

Historie
--------

- 2024-08-26 - Handhabung Microsoft Authenticator und PingID
- 2024-08-25 - Erste Version
