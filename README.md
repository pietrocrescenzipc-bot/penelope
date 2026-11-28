# Penelope
Prenotazioni, clienti e fidelity del The Galleon Pub & Pizzeria.

- App telefono (stile Pienissimo Lite): index.html
- Versione precedente: classica.html
- Back office (PC): backoffice.html
- Menu digitale pubblico: menu.html
- Prenotazione online per i clienti: prenota.html (regola Firestore in firestore-regola-prenota.txt)
- Tablet sala e tavoli: sala.html
- Coupon per i clienti (link promo → QR personale): coupon.html?p=ID_PROMO
- Scansione coupon per lo staff (telefono/tablet): scansiona.html
- Informativa privacy: privacy.html (completare i dati in giallo)
- Regole Firestore per promo/coupon/registro: firestore-regole-promo.txt

Ruoli: "admin" (titolari) crea promo ed esporta dati; gli altri utenti staff vedono, prenotano e scansionano. Ogni esportazione viene scritta nella collezione "registro".
