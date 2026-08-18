# lp-beratung-galabau

Landingpage für **kostenloses Beratungsgespräch** – Zielgruppe: GaLaBau-, GartenpfleGe- und Baumpflege-Inhaber.

**Live:** https://beratung-galabau.green-careers.de
**Repo:** github.com/frdlnk-gc/lp-beratung-galabau (TODO Push)

## Inhalt
- `index.html` – Hauptlandingpage
- `danke/index.html` – Thank-you-Page mit Recruiting-Report-Geschenk
- `hero-images/hero-galabau-team.jpg` – Hero-Hintergrund (Team-Foto)
- `logo-white-sm.png`, Favicons, `cust-logos/` – Brand-Assets

## Make-Webhook Setup

In `index.html`, suche `MAKE_WEBHOOK_URL = 'HIER_MAKE_WEBHOOK_URL_EINTRAGEN'`
und ersetze mit der URL aus dem Make-Szenario "Beratungstermin-Lead-GaLaBau".

## Supabase
Tabelle: `beratungstermine` (siehe SQL im Setup-Doc)

## DSGVO
- Kein automatischer WhatsApp-Versand an Lead
- Telefonnummer geht nur in Retargeting-Liste (Tag: `retargeting_whatsapp`)
- Sales meldet sich manuell innerhalb 24-48h
