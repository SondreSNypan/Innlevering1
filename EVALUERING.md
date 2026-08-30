# Evaluering – rubrikk for MatteHjelpen

Dette er rubrikken læreren (eller en KI-assistent på lærerens vegne) bruker
ved sensur. Bruk den selv som sjekkliste før innlevering – da blir det ingen
overraskelser.

## Slik brukes dette dokumentet ved sensur

> Be Copilot/en språkmodell fylle ut kopien av denne rubrikken for én gruppe
> om gangen, med repoet åpent i VS Code:
>
> "Gå gjennom dette repoet opp mot `EVALUERING.md`. Kjør
> `python scripts/selftest.py --strict`, les `EKSPERIMENT.md`,
> `backend/`-filene og commit-historikken (`git log --oneline`). Fyll ut
> hver rad i tabellene under med status og en kort, konkret begrunnelse
> (1–2 setninger). Vær ærlig – ikke gi status 'Bestått' uten dekning."

Resultatet er en kort, konsistent tilbakemelding per gruppe, uten løpende
API-kostnad (kjøres manuelt av læreren når sensur faktisk skjer).

## Del A: Fungerende app (40 %)

| Kriterium | Bestått krever | Status | Begrunnelse |
|---|---|---|---|
| Selvtest | `scripts/selftest.py --strict` gir 0 ❌ og 0 ⏳ | | |
| Tool-bruk | All regning skjer om mulig i `tools.py` via SymPy, ikke i modellens tekst | | |
| Stegvis forklaring | `/solve` returnerer reelle, forståelige steg – ikke bare svaret | | |
| Formelreferanser | Hvert relevant steg peker til en reell formel-ID i `formelsamling.py`, med navn og bok/kapittel, eller med tydelig markering av hvilke steg som mangler dette | | |
| Numerisk validering | `validert` reflekterer en faktisk utført sjekk, ærlig når den ikke er mulig | | |
| Egne krav | Gruppen har fylt ut `[FYLL INN SELV]`-feltene i `PROMPTS/` bevisst, ikke bare kopiert | | |
| Commit-historikk | Reelle, jevnlige commits fra flere gruppemedlemmer | | |

## Del B: Eksperiment (30 %)

| Kriterium | Bestått krever | Status | Begrunnelse |
|---|---|---|---|
| To modeller | Minst to modeller av ulik kvalitet faktisk testet og dokumentert | | |
| 10 oppgaver | Tabellen i `EKSPERIMENT.md` er fylt ut for alle 10 rader | | |
| Tools på/av | Forskjellen med og uten tools er dokumentert, ikke bare påstått | | |
| Kostnad | Tokenforbruk og kostnadsestimat er regnet ut og ekstrapolert til 1000 studenter | | |
| Aha-brytere | Minst 3 av de 5 aha-bryterne i `OPPGAVE.md` er faktisk prøvd og beskrevet | | |

## Del C: Refleksjonsnotat (30 %)

| Kriterium | Bestått krever | Status | Begrunnelse |
|---|---|---|---|
| Kalkulator-analogi | Egen, begrunnet stillingtagen – ikke bare gjengivelse | | |
| Hva kreves for å oppdage feil | Konkret, koblet til egne funn fra Del B | | |
| Tillit ("dimensjonere en bro") | Klar begrunnet posisjon, ikke bare "det kommer an på" uten videre | | |
| Hva betyr "flink til å kode" i 2026? | Egen refleksjon, ikke oppramsing av kjente KI-nyheter | | |

## Samlet tilbakemelding (fylles ut til slutt)

- **Sterkeste del:**
- **Viktigste forbedringspunkt:**
- **Foreløpig karakter/status:**
