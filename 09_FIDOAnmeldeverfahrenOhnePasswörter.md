# FIDO - Anmeldeverfahren ohne Passwörter
-------------------------------------------

## Warum sind Passwörter unsicher?
Passwörter sollten nur von Zwei parteien aufbewahrt werde. Bei Hackangriffen oder sobald es eine Dritte Person mitbekommt ist es unsicher. Passwörter sollten immer unterschiedlich sein.


## Wie geht ein passwortloses Anmeldeverfahren?
Man nutzt ein Externes gerät um sich einzuloggen z.B. mit Gesichtserkennung oder Fingerabdruck.


## Warum ist eine Anmeldung mit einem PIN auch gut?
Der PIN weiss immer nur eine Partei und der PIN funktioniert nur mit einem Gerät.


## Was sind die "Faktoren" für ein Anmeldeverfahren?
Haben: Man braucht ein Gerät
Wissen: Man muss das Passwort wissen.




# Passkey - Wie kann man Passwörter ersetzen?
-------------------------------------------

## Wie funktioniert das Public-/Private-Key-Verfahren
Public: Kennt jeder, jeder hat darauf Zugriff. Verschlüsselt Daten und verifiziert Signaturen.
Private: Kenne nur ich. Entschlüsselt Daten oder Erstellt SIgnaturen.

## Wie geht das digitale unterschreiben?
--> machen Sie eine Zeichnung davon, wie das geht.

![image](https://github.com/user-attachments/assets/1106dddf-87ae-41a5-952a-0b3419d75d1c)

Hash erstellen

Die Daten werden in eine Art "Fingerabdruck" umgewandelt, den man Hash nennt.
Der Hash ist eine kurze, einmalige Zahl, die die Nachricht repräsentiert.
Mit Private Key unterschreiben

Der Absender verschlüsselt den Hash mit seinem geheimen Private Key.
Das Ergebnis ist die digitale Unterschrift.
Versenden

Der Absender schickt die Nachricht zusammen mit der digitalen Unterschrift an den Empfänger.
Überprüfung durch den Empfänger

Der Empfänger entschlüsselt die Unterschrift mit dem Public Key des Absenders.
Dadurch erhält er den ursprünglichen Hash.
Vergleichen

Der Empfänger erstellt selbst einen Hash der erhaltenen Nachricht.
Stimmen die Hashes überein, ist die Unterschrift echt und die Nachricht unverändert.
Zusammengefasst:
Der Absender "verschließt" die Nachricht mit einem geheimen Schlüssel, und der Empfänger prüft mit dem passenden öffentlichen Schlüssel, ob alles passt.



## Was ist der Vorteil dieses FIDO-Verfahrens?

- **Sicherheit:**
Schützt vor Phishing, da der private Schlüssel niemals geteilt wird.

- **Benutzerfreundlichkeit:**
Nutzer brauchen sich keine komplexen Passwörter zu merken.

- **Biometrie:**
Authentifizierung kann über Fingerabdruck oder Gesichtserkennung erfolgen.

- **Keine zentralen Passwortspeicher:**
Reduziert die Gefahr von Datenlecks durch kompromittierte Server.

## Warum ist dieses System noch nicht so verbreitet?
Firmen haben noch keine Pläne es zu ändern, die schon Pläne haben oder es planen das System zu nutzen haben noch keinen Zeitplan.

