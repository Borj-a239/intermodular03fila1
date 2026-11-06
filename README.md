# Equip Fila 01 · Cartellera

Pràctica 3 (GitHub Projects) del **Projecte Intermodular · 1r DAM · Curs 2026/2027**.

Lloc web estàtic amb **quatre títols** (tres pel·lícules i una sèrie). La portada mostra una fitxa de cada
títol i cada fitxa porta a una pàgina pròpia amb **imatge**, **sinopsi**, **fitxa tècnica** i **enllaç a
IMDb**. Només HTML i CSS propi, sense JavaScript ni dependències.

- **Repositori:** https://github.com/intermodular03/intermodular03fila1
- **GitHub Project (Kanban):** https://github.com/orgs/intermodular03/projects/1

## Membres

| Membre | Usuari GitHub | Responsabilitat |
| --- | --- | --- |
| Gabi | [@gabi37smx](https://github.com/gabi37smx) | Repositori, Project, estructura, portada i lliurament |
| Borja | [@Borj-a239](https://github.com/Borj-a239) | Pàgina *El Senyor dels Anells* i primera versió de la web |
| Sergio | [@SergioCHP](https://github.com/SergioCHP) | Pàgina *John Wick 4* |
| Salva | [@SalvaLlacer26](https://github.com/SalvaLlacer26) | Pàgina *Resident Evil* |
| Javier | [@javiersansano222](https://github.com/javiersansano222) | Pàgina *El cuento de la criada* |

## Tasques

Cada tasca és una issue amb responsable assignat i es mou al Project per les columnes
**To Do → In Progress → Done**. Els canvis entren a `main` des de forks mitjançant Pull Requests.

| Issue | Tasca | Responsable |
| --- | --- | --- |
| #1 | Crear el repositori públic | @gabi37smx |
| #2 | Afegir els membres com a col·laboradors | @gabi37smx |
| #3 | Crear el GitHub Project amb vista Kanban | @gabi37smx |
| #4 | Organitzar el treball en To Do, In Progress i Done | @gabi37smx |
| #5 | Pàgina web (portada) | @gabi37smx |
| #6 | Crear l'estructura inicial de la web | @Borj-a239 |
| #7 | Crear el README | @Borj-a239 |
| #8 | Donar accés d'administració al Project a tots els membres | @gabi37smx |
| #9 | Treballar mitjançant forks i pull requests | Tot l'equip |
| #10 | Reestructurar carpetes i crear les pàgines de detall | @gabi37smx |
| #11 | Pàgina *El Senyor dels Anells* | @Borj-a239 |
| #12 | Pàgina *John Wick 4* | @SergioCHP |
| #13 | Pàgina *Resident Evil* | @SalvaLlacer26 |
| #14 | Pàgina *El cuento de la criada* | @javiersansano222 |
| #15 | Lliurament: PR al repositori del professor | @gabi37smx |

## Contingut

| # | Títol | Format | Any | Pàgina | IMDb |
| --- | --- | --- | --- | --- | --- |
| 1 | El Senyor dels Anells: La Germandat de l'Anell | Pel·lícula | 2001 | [senyor-anells.html](html/senyor-anells.html) | [tt0120737](https://www.imdb.com/title/tt0120737/) |
| 2 | John Wick 4 | Pel·lícula | 2023 | [john-wick-4.html](html/john-wick-4.html) | [tt10366206](https://www.imdb.com/title/tt10366206/) |
| 3 | Resident Evil | Pel·lícula | 2026 | [resident-evil.html](html/resident-evil.html) | [tt35538033](https://www.imdb.com/title/tt35538033/) |
| 4 | El cuento de la criada | Sèrie | 2017–2025 | [cuento-criada.html](html/cuento-criada.html) | [tt5834204](https://www.imdb.com/title/tt5834204/) |

## Estructura

```
.
├── index.html            # Portada amb les quatre fitxes
├── README.md
├── css/
│   └── styles.css        # Estils propis (portada i pàgines de detall)
├── html/
│   ├── senyor-anells.html
│   ├── john-wick-4.html
│   ├── resident-evil.html
│   └── cuento-criada.html
└── img/
    ├── peli1.jpg         # El Senyor dels Anells
    ├── peli2.jpg         # John Wick 4
    ├── peli3.jpg         # Resident Evil
    └── peli4.webp        # El cuento de la criada
```

## Com veure-la

Totes les rutes són relatives, així que n'hi ha prou amb obrir `index.html` al navegador.

## Com col·laborar

1. Fes un **fork** del repositori i clona'l.
2. Crea una rama per a la teva tasca: `git checkout -b pagina-john-wick-4`.
3. Fes els canvis, `git commit` i `git push` al teu fork.
4. Obre un **Pull Request** cap a `intermodular03/intermodular03fila1:main` amb `Closes #N` a la descripció.
5. Mou la targeta de la issue al Project (In Progress mentre treballes, Done quan es fusiona).
