Javascript: Was ist...

1. React Suspense
2. React.StrictMode
3. React Helmet
4. Outlet?
5. Warum haben manche Routen das Attribut "Index"?
6. Forms Controller

TODO: Sachen, die wir explizit gefunden haben, die getan werden müssen:

- Die Email zum laufen bekommen

TODO: Verbindungen mit Front- und Backend verstehen:

- Wie Funktionieren die CheckinCookies
- Sollten CheckinCookies länger existieren als SessionEnde?
- Wie werden hier Forms verwendet
- bookingTypes, was ist das?

TODO: Sachen, die wir Christian fragen müssen:

- Wie Online-Checkout aussehen lassen?
- DSGVO?!?!?!?
- Sollen alle Boote am Ende des Tages zurückgegeben werden?
- Hey, können wir die Anforderungen haben?

TODO: Sachen, die ich im Server nicht kenne:
- server.ts: Was macht express.static?
- warum führt eine Falsche URL nicht zur Hauptseite sonder zu einer weißen Seite?


# Meeting 01: 16.02.2023

Fragen:

- Anforderungsdokuemnte?
- Checkout:
  - Alle am Ende des Tages zurückgeben lassen?
  - Cookie-Checkout gerade nur bis Sessionende oder länger?
  - Checkin von mehreren Booten?
    - Gerade wird man zum Checkout gezwungen, wenn man die Seite nach Buchung neu aufruft. Soll das so sein?
  - Cookie-unabhängiges Checkout?
- DSGVO? Namen? Speicherung?
- Statistiken sind gerade noch sehr unklar, Erklärtext?
- Adminseiten, um alle Checkouts zu betrachten?

Sachen, die noch so anstehen:
- Toasts auf der Admin-Startseite
- Confirm-Dialoge fürs Löschen von Sachen
- Statistiken

Antworten:

- Bei Bootrückgabe: Willst du? Ja/Nein
- Zu Admin: Bootsschäden melden!
- Kommentar -> Schaden melden!
- Zeiten checken, nur so lange wie ein Tag
- Buchungsarchiv mit Buchungen älter als vier Wochen