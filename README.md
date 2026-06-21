# Festiwale — statyczny eksport

Statyczna migawka kalendarza/cockpitu festiwalowego (HTML + JSON), generowana
skryptem `freeze.py` z aplikacji Flask. Serwowana przez GitHub Pages.

- `index.html` — lista festiwali (landing)
- `map/` — mapa
- `festival/<slug>/` — strony festiwali
- `organizer/<id>/` — strony organizatorów
- `api/*.json` — dane czytane przez front (read-only migawka)

To migawka — żeby odświeżyć dane, uruchom `python freeze.py` i wypchnij ponownie.
