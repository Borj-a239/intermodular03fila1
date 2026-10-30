# Cartellera

Pàgina estàtica amb **4 títols** (3 pel·lícules i 1 sèrie). Cada fitxa mostra
**imatge**, **sinopsi** i **enllaç directe a IMDb**, amb **estils CSS propis**.
Només HTML i CSS — sense JavaScript ni dependències.

## Estructura
. ├── index.html # Estructura i contingut
  ├── styles.css # Estils propis
  └── images/
            ├── peli1.jpg # El Senyor dels Anells: La Germandat de l'Anell
            ├── peli2.jpg # John Wick 4
            ├── peli3.jpg # Resident Evil (2026)
            └── peli4.webp # El cuento de la criada

## Com veure-la

Obre `index.html` directament al navegador.

> **Important:** les rutes comencen amb `/` (`/images/peli1.jpg`), així que cal
> servir-ho amb un servidor local perquè les imatges es carreguen. Obert amb
> doble clic (`file://`) no funcionaran.

Qualsevol d'aquestes opcions:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve .
O bé l'extensió Live Server de VS Code (clic dret → Open with Live Server). Després entra a http://localhost:8000.

Si vols obrir-ho sense servidor, canvia les rutes a index.html traient la barra inicial: src="images/peli1.jpg".

Contingut
#	Títol	Format	Any	IMDb
1	El Senyor dels Anells: La Germandat de l'Anell	Pel·lícula	2001	tt0121765
2	John Wick 4	Pel·lícula	2023	tt10366207
3	Resident Evil	Pel·lícula	2026	tt34263280
4	El cuento de la criada	Sèrie	2017–	tt7081030
Personalització
Canviar títols: edita els <article class="card"> de index.html (imatge, text i URL d'IMDb).
Colors i tipografia: es controlen des de les variables de :root a styles.css (--bg, --amber, --display, etc.).
Idioma: el contingut és en català (<html lang="ca">); el README en castellà.
Notes
Resident Evil encara no té puntuació a IMDb; apareix com a n/d. Actualitza el número quan estigui disponible.
Les imatges han de mantenir una relació 2:3 perquè la graella no es mogui.
Els enllaços IMDb s'obren en una pestanya nova (target="_blank").
