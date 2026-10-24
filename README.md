# Invitasjon: frokostseminar 18. november 2026

**Erfaringer fra virkeligheten: AI-agenter i daglig drift og utvikling**

Yne × Ægis, Akersgata 32, Oslo. 08.30–10.30. Påmeldingsfrist 17. november.

## Innhold

- `index.html` – invitasjonssiden med program, innledere og påmelding. Selvstendig fil uten avhengigheter utover Google Fonts.

## Slik oppdaterer du siden

Alt som endres ofte ligger øverst i `<script>`-blokken nederst i `index.html`:

| Variabel    | Hva den styrer                                                                 |
|-------------|--------------------------------------------------------------------------------|
| `REG_EMAIL` | E-postadressen som vises for spørsmål om seminaret og for sletting av opplysninger |

Lenken til Google-skjemaet står direkte i de to «Meld deg på»-knappene i HTML-en.

Dato, sted og frist står i faktastripen øverst på siden. Program og innledere står i egne seksjoner i HTML-en.

## Publisering

Siden kan legges rett ut med GitHub Pages: Settings → Pages → Deploy from branch `main`, mappe `/ (root)`. Da blir den tilgjengelig på `https://selinaserephina-star.github.io/Invitasjon_frokostseminar/`.

Skal den inn på Ynes eget nettsted, kan webansvarlig i tillegg bygge Google-skjemaet inn direkte på siden i stedet for å lenke ut.
