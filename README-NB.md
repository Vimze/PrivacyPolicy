# Personvernerklæring

_Sist oppdatert: 2026-09-21_

Vimse ("appen") er en app for oppskrifter og handlelister, bygget for å fungere offline med valgfri skysynkronisering.

## Hva vi samler inn

- **Kontoinformasjon**: e-postadresse og passord (via Supabase Auth) når du oppretter en konto, eller identitetsinformasjon fra en tredjepartstjeneste hvis du logger inn med OAuth.
- **Profilinformasjon**: visningsnavn og profilbilde, hvis du velger å angi dette.
- **Appinnhold**: oppskrifter, handlelister og relatert data du oppretter i appen. Dette lagres lokalt på enheten din (SQLite) og synkroniseres til vår backend (Supabase, driftet på AWS/EU-infrastruktur) når du er innlogget og har nett, slik at dataene dine er tilgjengelige på tvers av enheter.
- **Oppskriftsbilder**: lagres kun lokalt på enheten din.

Vi samler ikke inn analysedata, annonse-ID-er eller annen bruksstatistikk. Appen har ingen annonser eller tredjeparts sporingsverktøy.

## Hvordan vi bruker det

Utelukkende for å levere appens kjernefunksjonalitet: autentisere deg, lagre dataene dine, og synkronisere dem på tvers av enhetene dine.

## Deling av data

Vi selger eller deler ikke dataene dine med tredjeparter. Data lagres hos vår backend-leverandør, Supabase, med radnivå-sikkerhet (row-level security) slik at kun du har tilgang til dine egne data.

## Lagring og sletting av data

Dataene dine lagres frem til du sletter dem eller sletter kontoen din. Du kan slette brukeren din i appen.
