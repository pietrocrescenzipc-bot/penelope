# Galleon Club
Back office CRM, promozioni e privacy GDPR del The Galleon Pub & Pizzeria.
Usa lo stesso database Firebase di Penelope ("galleon-club"): clienti, prenotazioni, promo e coupon sono condivisi. Penelope resta attiva e invariata.

- `index.html` – back office: Panoramica, Clienti (scheda con consensi e storico), Segmenti, Promozioni, Privacy GDPR (richieste interessati, conservazione, registro attività, registro trattamenti), Staff e ruoli
- Pagine pubbliche coupon/scanner/informativa: per ora quelle di Penelope (coupon.html, scansiona.html, privacy.html), indirizzo impostabile in Privacy → Impostazioni
- `firestore-regole.txt` – regole da aggiungere in Firebase

Ruoli: `admin` = titolari (tutto), `sala` = staff (niente esportazioni, niente privacy, niente ruoli).
