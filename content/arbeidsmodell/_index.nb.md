---
# id: auto-generert – kopierte verdier overskrives automatisk ved push
id: 93229e72-4a63-467c-8171-175d413d1275
# id: auto-generert – kopierte verdier overskrives automatisk ved push
title: Arbeidsmodell
weight: 20
toc: true
lastmod: 2026-11-20T00:22:22+01:00
last_editor: Erik Hagen

---

Denne siden beskriver hvordan SAMT-BU foreløpig arbeider med å kartlegge behov og prøve ut løsninger. Modellen er bevisst forenklet, og den vil bli videreutviklet.

## Case og pilot

Prosjektet skiller mellom to ting som lett blandes sammen, og som i prosjektets egne dokumenter ofte omtales om hverandre:

- Et **case** beskriver et **behov** – en situasjon som ikke fungerer godt nok i dag. Casene ligger under [Behov](https://docs.samt-bu.no/behov/use-cases/).
- En **pilot** er et **gjennomføringstiltak** – et konkret forsøk på å gjøre noe med ett eller flere behov. Pilotene ligger under [Piloter](https://docs.samt-bu.no/pilotering/).

Forholdet mellom dem er **mange-til-mange**. Én pilot kan adressere flere caser, og ett case kan bli berørt av flere piloter – helt eller delvis, i ulike faser. To praktiske konsekvenser følger av dette:

- **Caser slås ikke sammen.** At to caser inngår i det samme pilotforslaget gjør dem ikke til ett case. De beholder hver sin beskrivelse og får i stedet en relasjon.
- **Caser «utgår» ikke fordi de dekkes et annet sted.** Et behov som blir håndtert gjennom en pilot knyttet til et annet case, er fortsatt et reelt behov. «Utgår» bør forbeholdes behov som faktisk er forkastet.

## Case-beskrivelsen som forenklet behovsbeskrivelse

Behov kartlegges i dag gjennom **case-beskrivelser** – korte, fritekstbaserte beskrivelser av en situasjon som ikke fungerer godt nok. Formatet er valgt fordi det er lavterskel: det lar mange bidra tidlig, uten å måtte forholde seg til en formell modell.

Prisen for den enkelheten er at case-beskrivelsene ikke skiller systematisk mellom behov, mål, løsningsforslag og leveranse. Flere av casene i registeret inneholder alle fire om hverandre. Dagens register følger heller ikke skillet over konsekvent – enkelte caser er merket som innarbeidet i eller erstattet av andre.

Dette er kjent, og aksepteres inntil videre.

## Gjennomføring av piloter

Pilotene er SAMT-BUs viktigste måte å prøve ut løsninger på. Et av prosjektets mest sentrale produkter er MVP-er og utprøving av informasjonsmodeller og tjenester, og pilotene skal gjennomføres smidig: med nysgjerrighet og læring gjennom utprøving i korte iterasjoner, slik at vi raskt kan vise reell verdi og like raskt finne ut hva som ikke fungerer (fail fast). Hver pilot tar utgangspunkt i ett eller flere case, se [Case og pilot](#case-og-pilot).

Dette kapitlet beskriver det som er felles for alle pilotene. Det som gjelder den enkelte piloten – behov, mål, avgrensning, deltakere og leveranser – står under [Piloter](/pilotering/).

### Dreieboka

Prosjektet har laget en «dreiebok» for gjennomføring av piloter. Den følger et kjent mønster for gjennomføring av prosjekter, i sju faser:

![Dreieboka i sju faser: 1 Velge pilot, 2 Oppstart, 3 Drømmereise, 4 Velge MVP, 5 Lage MVP, 6 Evaluering, 7 Videreføring](dreiebok-faser.png)

1. **Velge pilot:** hvilke behov (case) piloten skal adressere.
2. **Oppstart:** mål, produkter, avgrensning, bemanning og plan.
3. **Drømmereise:** hvordan det bør fungere for brukeren når alt er på plass.
4. **Velge MVP:** hva som skal lages eller prøves ut først.
5. **Lage MVP**
6. **Evaluering**
7. **Videreføring:** forslag til neste fase.

Fasene beskriver en rekkefølge, men arbeidet er iterativt, og enkelte faser gjentas ved behov. Erfaringene fra hver pilot skal brukes til å oppdatere dreieboka.

### Organisering

For hver pilot etableres et eget, autonomt team med en pilotleder. Teamet settes sammen etter hva piloten trenger av kompetanse, typisk fagfolk fra de virksomhetene som eier data og tjenester, arkitekter og jurister, og representanter for kommuner, fylkeskommuner og leverandører der det er relevant.

Hver pilot har en plan for gjennomføring, med bakgrunn (case), målsetning, produkter, avgrensning, bemanning, arbeidspakker og milepæler. Planen er grunnlaget for siden «Om pilot N».

### Arbeidsform

- Piloten gjennomføres iterativt etter smidige prinsipper, i sprinter på to eller tre uker.
- Hver sprint starter med et planleggingsmøte og avsluttes med en demo. Det vurderes å kjøre felles demo i SAMT-BU-regi for alle pilotene.
- I utgangspunktet er det ønskelig med standup for hele piloten annenhver dag. Etter hvert kan det være tilstrekkelig at arbeidet koordineres i hver arbeidspakke.
- Det bør gjennomføres minst én retrospektiv i løpet av pilotperioden.

### Oppgaver, dokumentasjon og kommunikasjon

- Hver pilot har et eget repo i GitHub med oppgavene som issues og et eget brett. Se [Oppgaver og oppfølging](/styring/oppgaver-og-oppfolging/).
- Pilotens dokumentasjon og leveranser publiseres på [docs.samt-bu.no](/pilotering/), under piloten.
- Kommunikasjonsaktiviteter samordnes med kommunikasjonsrådgiveren i SAMT-BUs kjerneteam.

### Dokumentasjon av piloter

Hver pilot har samme struktur på nettstedet. De generelle konvensjonene for sider står i [Sider og struktur](/prosjektleveranser/loesninger/samhandlingsplattform/samt-bu-docs/brukerveiledning/sider-og-struktur/).

| Side | Innhold |
|---|---|
| **Forsiden** (Pilot N) | Bare en kort ingress. Undersidene listes automatisk |
| **Om pilot N** | Kort og saklig, skal stå seg over tid: behov (med lenke til case), mål, omfang og avgrensning, deltakere og roller. Ikke metode (står her), periode, status eller arbeidspakker |
| **Leveranser** | Ingress med løpende oversikt over leveransene, og én underside per leveranse (for eksempel drømmereise, arkitektur, juridiske behov) |
| **Resultater og veien videre** | Når piloten har noe å vise: hovedresultater, gevinster, forutsetninger og neste steg, kort og med lenker til leveransene |
| **Oppgaver og framdrift** | Periode, status og arbeidspakker: brettet, tidslinjen og eventuelt den opprinnelige planen |

Status per leveranse (fra planlagt til levert) er ikke på plass ennå. Eksempel på strukturen: [Pilot 4](/pilotering/pilot-4/).

## Videre arbeid

Arbeidsmodellen her er et **arbeidsgrunnlag, ikke en vedtatt metamodell**. Et mer presist begrepsapparat for behov, løsning, mål og leveranse er under utvikling, og vil kunne endre både hvordan behov beskrives og hvordan de knyttes til tiltak.

Begrepsarbeidet finner du under [Begrepsapparat og konsepter](https://docs.samt-bu.no/innsikt/begrepsapparat-og-konsepter/). At det arbeidet utvikler seg, gjør ikke beskrivelsen på denne siden feil – den beskriver praksis slik den er i dag, og oppdateres når praksis faktisk endres.
