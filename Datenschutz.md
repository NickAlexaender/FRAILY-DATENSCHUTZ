# Datenschutzerklärung für die App Fraily

Stand: 27. November 2026

## 1. Verantwortlicher

Nick Lehmacher (Kleinunternehmer)  
Gustavstraße 1  
90762 Fürth  
E-Mail: nick.lehmacher@gmx.de

## 2. Das Wichtigste in Kürze

- Fraily ist ein persönliches Gedächtnis für dein berufliches Netzwerk. Was du einträgst, entscheidest du.
- Deine Daten liegen auf deinem Gerät und, damit sie einen Gerätewechsel überstehen, bei Google Firebase in Frankfurt am Main.
- Deine Notizen wertet Fraily mit KI von OpenAI aus. Das passiert erst, wenn du in der App zustimmst.
- Eine Nutzungsstatistik erfasst Fraily nur, wenn du zustimmst.
- Fraily zeigt keine Werbung, verkauft keine Daten und schreibt nie in deinem Namen.
- Du kannst dein Konto mit allen Daten jederzeit in der App löschen.

## 3. Was du in Fraily einträgst

**Welche Daten:** Angaben über dich (Name, Beschreibung, eigene Kontaktdaten, was du suchst und was du kannst, deine Antworten im Einstieg wie deine Rolle). Personen aus deinem Netzwerk mit Namen, Kontaktdaten, Geburtstag, Foto, Notizen und Stichworten. Begegnungen, offene Fäden wie Zusagen und Pläne, wer wen kennt, Gruppen und Termine. Einstellungen wie Sprache, Zeitzone und Erinnerungszeit.

**Wo sie liegen:** auf deinem Gerät und zusätzlich bei Google Firebase (Cloud Firestore und Cloud Storage) in Frankfurt am Main, verknüpft mit deinem Konto. So bleiben deine Daten bei einem Gerätewechsel erhalten, und Fraily kann deine Vorschläge berechnen.

**Wozu:** damit Fraily funktioniert. Rechtsgrundlage ist Art. 6 Abs. 1 lit. b DSGVO (Nutzungsvertrag).

**Wie lange:** bis du den Eintrag oder dein Konto löschst.

## 4. Angaben über andere Menschen

Wer Fraily nutzt, schreibt über andere Menschen. Diese Menschen haben Fraily nicht selbst zugestimmt. Deshalb gilt:

- Fraily nutzt diese Angaben nur, um dir deine eigenen Notizen und Vorschläge zu zeigen. Andere Nutzer sehen sie nicht. Fraily nimmt keinen Kontakt zu diesen Menschen auf und führt sie nicht kontoübergreifend zusammen.
- Rechtsgrundlage ist Art. 6 Abs. 1 lit. f DSGVO. Das berechtigte Interesse liegt darin, dir eine Gedächtnisstütze für deine beruflichen Kontakte zu bieten. Die Angaben bleiben in deinem Konto, sind nur für dich sichtbar und lassen sich jederzeit löschen.
- Bitte schreib nur auf, was du für deine Kontaktpflege brauchst. Lass besonders sensible Angaben weg, etwa zu Gesundheit, Religion, politischer Meinung oder Sexualleben.

## 5. Konto und Anmeldung

Beim ersten Start legt Fraily ein anonymes Konto bei Google Firebase Authentication an. Dafür reicht eine zufällige Kennung, die Nutzer-ID. Wenn du dein Konto mit Apple oder Google verbindest, speichert Firebase zusätzlich die Kennung und die E-Mail-Adresse, die Apple oder Google übermitteln. Bei Apple kannst du deine E-Mail-Adresse verbergen.

Anbieter ist Google. Die Kontodaten verarbeitet Google auch in den USA. Google LLC ist nach dem EU-US Data Privacy Framework zertifiziert. Rechtsgrundlage ist Art. 6 Abs. 1 lit. b DSGVO. Die Daten bleiben bis zur Löschung deines Kontos.

## 6. Auswertung mit KI (OpenAI)

**Wann:** nur nach deiner Zustimmung in der App. Ohne Zustimmung geht nichts an OpenAI, und du trägst Begegnungen von Hand ein.

**Welche Daten:** Notizen, die du tippst, einfügst oder diktierst. Sprachaufnahmen, die in Text umgewandelt werden. Die Namen deiner Kontakte, damit Fraily Personen zuordnen kann, und dein Name. Die Stichworte unter „kann“ und „sucht“, ohne Namen. In Fraily Pro die Notizen zu einer Person, aus denen Fraily eine Zusammenfassung schreibt. Texte, die du im Feedback veröffentlichst, zur Prüfung auf Missbrauch.

**Wie:** Die App schickt die Daten verschlüsselt an den Fraily-Server bei Render in Frankfurt am Main. Der Server leitet sie an OpenAI weiter. Deine Nutzer-ID bekommt OpenAI nicht. Sprachaufnahmen speichert der Fraily-Server nicht, er verarbeitet sie nur im Arbeitsspeicher. Die Ergebnisse speichert Fraily in deinem Konto.

**Anbieter:** OpenAI Ireland Limited, die Verarbeitung erfolgt auch durch OpenAI in den USA. Grundlage für die Übermittlung in die USA sind die Standardvertragsklauseln der EU-Kommission. OpenAI nutzt Daten aus seiner API laut eigenen Angaben nicht zum Training und speichert sie zur Missbrauchskontrolle bis zu 30 Tage.

**Rechtsgrundlage:** deine Einwilligung nach Art. 6 Abs. 1 lit. a DSGVO. Für Angaben über andere Menschen in deinen Notizen gilt zusätzlich Abschnitt 4. Du kannst die Einwilligung jederzeit in den Einstellungen unter „KI-Auswertung“ widerrufen. Der Widerruf gilt ab diesem Zeitpunkt.

## 7. Vorschläge und Benachrichtigungen

Der Fraily-Server liest die Daten deines Kontos aus Firestore, je nach Tarif einmal am Tag oder einmal pro Woche, und berechnet daraus deine Vorschläge. Er speichert sie in deinem Konto und löscht Vorschläge, die älter als 14 Tage sind. Betreiber des Servers ist Render Services, Inc. mit Servern in Frankfurt am Main. Render ist nach dem EU-US Data Privacy Framework zertifiziert. Rechtsgrundlage ist Art. 6 Abs. 1 lit. b DSGVO.

Wenn du Benachrichtigungen erlaubst, speichert Fraily ein Geräte-Token in deinem Konto. Darüber schickt der Fraily-Server einen kurzen Hinweis wie „Morgen gibt es 3 Anlässe aus deinem Netzwerk.“ Namen stehen darin nicht. Zugestellt wird er über den Push-Dienst von Expo (650 Industries, Inc., USA, nach dem EU-US Data Privacy Framework zertifiziert) und über Apple oder Google. Erinnerungen, die die App selbst plant, bleiben auf deinem Gerät. Benachrichtigungen schaltest du in den Einstellungen deines Geräts ab.

## 8. Server-Protokolle

Der Fraily-Server protokolliert technische Angaben zu jeder Anfrage, etwa Zeitpunkt, aufgerufene Funktion, Ergebnis und IP-Adresse. Inhalte deiner Notizen stehen nicht darin. Zweck sind Betrieb, Fehlersuche und Schutz vor Missbrauch, etwa durch eine Begrenzung der Anfragen. Rechtsgrundlage ist Art. 6 Abs. 1 lit. f DSGVO. Render speichert die Protokolle je nach Tarif 7 bis 30 Tage.

## 9. Fraily Pro und Käufe

Käufe wickeln der Apple App Store oder Google Play ab. Zahlungsdaten sehen wir nicht. Den Abo-Status verwaltet RevenueCat, Inc. (USA) mit deiner Nutzer-ID, den gekauften Produkten, Zeitpunkten, Status und Plattform. RevenueCat meldet Änderungen am Abo an den Fraily-Server, der den Pro-Status in deinem Konto speichert. Grundlage für die Übermittlung in die USA sind die Standardvertragsklauseln der EU-Kommission. Rechtsgrundlage ist Art. 6 Abs. 1 lit. b DSGVO. Die Daten bleiben bis zur Löschung deines Kontos, Kaufbelege bei Apple und Google nach deren Regeln.

## 10. Nutzungsstatistik (PostHog)

Nur wenn du zustimmst, erfasst Fraily, wie die App genutzt wird. Gefragt wirst du einmal im Einstieg, ändern kannst du es jederzeit in den Einstellungen unter „Nutzungsstatistik“. Standardmäßig ist sie aus.

Erfasst werden zum Beispiel App-Starts, aufgerufene Screens, abgeschlossene Schritte im Einstieg mit deinen Antworten (etwa Rolle und wie du von Fraily erfahren hast), die Zahl deiner Kontakte und ob du Benachrichtigungen erlaubt oder Fraily Pro gekauft hast. Namen und Notizen gehören nicht dazu, Berührungen und Bildschirmtexte erfasst Fraily nicht. Die Daten sind mit deiner Nutzer-ID verknüpft, damit wir Abläufe über mehrere Tage verstehen.

Anbieter ist PostHog, Inc. (USA), nach eigenen Angaben nach dem EU-US Data Privacy Framework zertifiziert. Rechtsgrundlage ist deine Einwilligung nach Art. 6 Abs. 1 lit. a DSGVO und § 25 Abs. 1 TDDDG. Du kannst sie jederzeit widerrufen, dann sendet die App nichts mehr. Die bereits erfassten Daten bleiben bis zur Löschung deines Kontos.

## 11. Feedback

Was du im Bereich Feedback veröffentlichst, sehen andere Fraily-Nutzer, ebenso deine Stimmen. Technisch wird dabei die Nutzer-ID des Autors mitgeliefert, einen Namen zeigt Fraily nicht an. Vor dem Veröffentlichen prüft OpenAI den Text auf Missbrauch (Abschnitt 6). Rechtsgrundlage ist Art. 6 Abs. 1 lit. b DSGVO. Die Beiträge bleiben, bis du sie oder dein Konto löschst.

## 12. Konto löschen

In der App unter Einstellungen, „Konto löschen“. Gelöscht werden dein Konto bei Firebase, alle Daten deines Kontos in Firestore und Storage, deine Person und deine Ereignisse bei PostHog, dein Kundeneintrag bei RevenueCat und alle Daten auf deinem Gerät. Eine Anmeldung mit Apple wird widerrufen. Ein laufendes Abo kündigst du getrennt bei Apple oder Google.

Manche Daten verschwinden zeitversetzt: PostHog löscht Ereignisse im Hintergrund, Sicherungskopien bis zu zwei Wochen später. Bei OpenAI gelten bis zu 30 Tage Missbrauchskontrolle, bei Render die Aufbewahrung der Protokolle aus Abschnitt 8.

Wechselst du auf einem Gerät in ein bestehendes Konto, löscht Fraily das vorherige anonyme Konto samt Daten, sobald der Server bestätigt hat, dass deine Daten im neuen Konto liegen. In seltenen Fällen bleibt es bestehen, etwa wenn die App vorher beendet wird, die Verbindung fehlt oder ein Abo am alten Konto hängt. Dann löschen wir es auf Anfrage per E-Mail.

Hast du die App nicht mehr, schreib uns eine E-Mail. Wir löschen dein Konto dann für dich.

## 13. Deine Rechte

Du hast das Recht auf Auskunft (Art. 15 DSGVO), Berichtigung (Art. 16), Löschung (Art. 17), Einschränkung der Verarbeitung (Art. 18), Datenübertragbarkeit (Art. 20) und Widerspruch gegen Verarbeitungen auf Grundlage berechtigter Interessen (Art. 21). Eine Einwilligung kannst du jederzeit für die Zukunft widerrufen (Art. 7 Abs. 3). Das gilt auch für Menschen, über die in Fraily geschrieben wird. Schreib dafür an nick.lehmacher@gmx.de.

Du kannst dich außerdem bei einer Datenschutz-Aufsichtsbehörde beschweren. Zuständig ist das Bayerische Landesamt für Datenschutzaufsicht, Promenade 18, 91522 Ansbach.

## 14. Keine Werbung, keine automatisierten Entscheidungen

Fraily zeigt keine Werbung und gibt keine Daten zu Werbezwecken weiter. Die Vorschläge berechnet Fraily automatisch. Sie haben keine rechtliche Wirkung und beeinträchtigen dich nicht in ähnlicher Weise, eine automatisierte Entscheidung nach Art. 22 DSGVO findet nicht statt.

## 15. Sicherheit

Alle Verbindungen sind verschlüsselt. Auf die Daten deines Kontos in Firestore kommt nur, wer mit deinem Konto angemeldet ist. Geheime Schlüssel, etwa für OpenAI, liegen nur auf dem Fraily-Server und nicht in der App.

## 16. Änderungen

Wenn sich Fraily ändert, passen wir diese Erklärung an. Die aktuelle Fassung steht in der App und unter https://github.com/NickAlexaender/FRAILY-DATENSCHUTZ/blob/main/Datenschutz.md.
