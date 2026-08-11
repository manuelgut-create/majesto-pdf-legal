# Majesto PDF – statische Rechtsseiten

Dieser Ordner enthält eine vollständig statische, zweisprachige Website für das geplante GitHub-Pages-Repository `majesto-pdf-legal`.

## Inhalt

- `index.html` – zweisprachige Einstiegsseite
- `privacy.html` – Datenschutzerklärung für App und Website in Deutsch und Englisch
- `imprint.html` – Impressum/Anbieterinformationen in Deutsch und Englisch
- `styles.css` – responsives, barrierearmes Layout mit Hell-/Dunkelmodus
- `.nojekyll` – verhindert eine unnötige Jekyll-Verarbeitung bei GitHub Pages

Die Seiten verwenden kein JavaScript, keine Cookies aus eigenem Code, keine Analyse, keine externen Schriftarten und keine externen Medien. Zusätzliche externe Verbindungen entstehen erst, wenn ein Nutzer einen gekennzeichneten Link zu GitHub, Google oder dem LfDI BW öffnet. Die Bereitstellung selbst über GitHub Pages führt technisch schon beim Seitenabruf zu einer Verbindung mit GitHub; dies ist in der Datenschutzerklärung beschrieben.

Der App-Text grenzt zwischen Majesto und eingebundenen Bibliotheken ab: Die App enthält keine Werbung und keine eigenen Analyse-, Tracking- oder Crash-Reporting-SDKs. Google Play Billing Library 9.1.0 erzeugt jedoch beim automatischen Start-/Resume-Verbindungsablauf Betriebsdiagnostik und übermittelt sie per HTTPS über Google DataTransport/CCT an Google. Die zweisprachige Erklärung benennt Datenkategorien, die lokale CCT-SQLite-Queue (maximal 10 MiB, lokaler Sieben-Tage-Cleanup und Retry), die nicht aus dem SDK bestimmbare Google-Serveraufbewahrung sowie den Ausschluss von PDF-, Such- und Notizinhalten.

## Veröffentlichung über GitHub Pages

Die Seiten wurden am 11.08.2026 im öffentlichen Repository
`manuelgut-create/majesto-pdf-legal` (Commit
`a50ad524454c59eada91c81d25e0454dd5e8ea82`) aus `main`/`root`
über GitHub Pages veröffentlicht. Der Pages-Workflow lief erfolgreich durch;
Startseite, Datenschutz und Impressum wurden anschließend live geprüft:

- `https://manuelgut-create.github.io/majesto-pdf-legal/`
- `https://manuelgut-create.github.io/majesto-pdf-legal/privacy.html`
- `https://manuelgut-create.github.io/majesto-pdf-legal/imprint.html`

Die Datenschutz-URL ist außerdem als gespeicherte Änderung in der Google Play
Console hinterlegt. Die HTML-Dateien verwenden relative interne Links und
funktionieren damit auch unter einer späteren eigenen Domain.

## Prüfung vor externer Veröffentlichung

Diese Texte bilden den technisch bekannten Stand vom 11.08.2026 ab, ersetzen aber keine individuelle Rechtsberatung. Eingetragen beziehungsweise bei nicht einschlägigen Pflichtfeldern bewusst nicht öffentlich aufgeführt wurden folgende bestätigte Angaben:

- Anbieter ist Manuel Gut als Einzelunternehmer; „Alpha02“ ist kein Handelsname, sondern erscheint ausschließlich als Domain der Kontaktadresse;
- es besteht keine Handelsregistereintragung;
- eine Umsatzsteuer-Identifikationsnummer wurde nicht erteilt und die Kleinunternehmerregelung gemäß § 19 UStG wird in Anspruch genommen;
- der Betrieb hat keine Beschäftigten; damit greift derzeit die Ausnahme des § 36 Abs. 3 VSBG von der allgemeinen Informationspflicht nach § 36 Abs. 1 Nr. 1 VSBG;
- die App-Entwicklung und der App-Vertrieb sind keine in diesem Projekt erkennbare zulassungspflichtige oder berufsrechtlich geregelte Tätigkeit;
- als unmittelbar erreichbarer elektronischer Kontakt wird `info@alpha02.de` verwendet; eine Telefonnummer wird auf diesen Rechtsseiten nicht veröffentlicht.

Mit jeder wesentlichen Produkt- oder Unternehmensänderung und vor einem
öffentlichen Play-Release sollte der Herausgeber insbesondere erneut prüfen:

- ob Name, ladungsfähige Anschrift und Kontaktadresse exakt und dauerhaft erreichbar sind;
- ob die bestätigten Anbieter-, Steuer- und Kontaktdaten unverändert sind;
- ob im ELSTER-Postfach beziehungsweise durch das BZSt inzwischen eine
  Wirtschafts-Identifikationsnummer zugeteilt wurde; eine vorhandene W-IdNr.
  muss gegebenenfalls ergänzt werden, persönliche Steuer-ID und Steuernummer
  dürfen dagegen nicht veröffentlicht werden;
- ob neben E-Mail ein zweiter tatsächlich schneller, unmittelbarer und
  wirksamer Kontaktweg bereitgestellt werden muss. Eine Telefonnummer ist nach
  der EuGH-Rechtsprechung nicht zwingend, E-Mail allein ist für diesen zweiten
  Weg jedoch nicht rechtssicher belegt; ein echtes, überwachtes Kontaktformular
  wäre eine mögliche Alternative;
- ob inzwischen eine besondere Verpflichtung zur Teilnahme an einer Verbraucherschlichtung besteht oder sich die Beschäftigtenzahl geändert hat;
- ob inzwischen ein Datenschutzbeauftragter benannt wurde oder aufgrund geänderter Verarbeitungsvorgänge benannt werden muss;
- ob Google-Play-Verkäuferdaten, steuerliche Einordnung und tatsächlicher Kaufablauf mit dem Text übereinstimmen;
- ob das finale Billing-Artefakt weiterhin dieselben Betriebsdiagnosedaten, Endpunkte, lokalen Queue-Grenzen und Aufbewahrungsregeln verwendet;
- ob der lokale Google-Play-Prüfzugang genauso implementiert ist wie beschrieben;
- ob GitHub Pages, E-Mail-Anbieter und mögliche Drittlandübermittlungen unverändert sind;
- ob die endgültigen Play-Data-Safety-Angaben denselben Produktstand beschreiben.

Die öffentliche Fassung enthält weder eine Registerangabe noch eine Aufsichtsbehörde, berufsrechtliche Angaben, einen Datenschutzbeauftragten oder eine allgemeine Erklärung zur Verbraucherstreitbeilegung, weil diese Angaben nach dem bestätigten Stand nicht einschlägig sind. Werden später Beschäftigte eingestellt, ein Datenschutzbeauftragter benannt, eine Register- oder Steuer-ID erteilt oder eine besonders regulierte Tätigkeit aufgenommen, müssen die Seiten vor der nächsten Veröffentlichung aktualisiert werden. Bei weltweiter IAP-Ausspielung ist unabhängig vom deutschen Impressum zusätzlich zu prüfen, ob einzelne Play-Store-Märkte – insbesondere Japan – eine öffentliche Telefonnummer verlangen.

Zugangsdaten, Reviewer-Passwörter, Signierschlüssel und andere Geheimnisse dürfen weder in dieses Repository noch in die öffentlichen Seiten aufgenommen werden.

## Lokale Prüfung

Die Seiten können direkt im Browser geöffnet werden. Für eine Prüfung mit normalen HTTP-Links kann im Ordner ein beliebiger lokaler statischer Webserver gestartet werden. Es gibt keinen Build-Schritt und keine Laufzeitabhängigkeit.
