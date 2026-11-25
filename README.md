# Gemeentemonitor Hoorn

Volgt automatisch wat de gemeente Hoorn publiceert, besluit en wijzigt, en wat de media erover schrijven.
Dashboard: https://martijnstb.github.io/monitor-hoorn/

Bronnen:
- Officiële bekendmakingen (KOOP): vergunningen, verordeningen, besluiten uit het Gemeenteblad
- Raad: vergaderingen van de gemeenteraad en de Algemene Raadscommissie, raadsstukken en overzichten
  (iBabs, hoorn.bestuurlijkeinformatie.nl)
- College: 'Brieven College' uit hetzelfde portaal
- Nieuws van hoorn.nl (RSS)
- Woo-publicaties (open.overheid.nl)
- In de media: Google Nieuws op Hoorn, Blokker en Zwaag

De monitor draait elke 15 minuten (GitHub Actions, aangezet via cron-job.org).
Trefwoorden voor directe pushmeldingen staan in `trefwoorden.txt`.
