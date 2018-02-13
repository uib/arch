---
title: Krypterte forbindelser
date: 2018-02-09
uibstatus: accepted
---

Krypterte forbindelser brukes til all kommunikasjon ut mot brukerene.

### Begrunnelse

Vi ønsker å sikre at informasjon som sendes ut fra UiBs servere når brukerene
uten å være modifisert på veien. Brukerene skal kunne stole på at det er trygt
å besøke våre sider.

Fra september 2017 har dette vært en [anbefaling fra Difi](https://www.difi.no/fagomrader-og-tjenester/digitalisering-og-samordning/standarder/referansekatalogen/grunnleggende-datakommunikasjon-0#Weboverføring).

Se utdyping [https everywhere](https://www.eff.org/https-everywhere).

### Konsekvens

For webtjenester betyr det at det må anskaffes sertifikat til alle tjenester
og at henvendelser på `http` alltid skal omdirigeres til `https`.

For API-kall kan fremdeles `http` brukes for ikke-sensitiv informasjon som ikke
forlater vårt nett.
