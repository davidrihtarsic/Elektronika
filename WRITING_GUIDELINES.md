---
published: false
---

# Pravila pisanja univerzitetne skripte

Ta dokument določa način pisanja celotne skripte. Namenjen je zagotavljanju enotnega sloga, terminologije in načina razlage skozi celotno knjigo.

Ta pravila veljajo za vsa poglavja.

---

# Osnovno vodilo

Bralec naj po branju poglavja ne pozna le novih definicij, ampak predvsem razume pojav in zna razložiti njegovo delovanje.

Cilj skripte ni prenos informacij, temveč razvoj razumevanja.

---

# Organizacija podpoglavja

Vsako podpoglavje odgovarja na eno pomembno strokovno vprašanje.

To vprašanje praviloma ni zapisano v naslovu.

Naslov ostane strokoven.

Primer:

## Električni tok

Prvi odstavek pa odpre vprašanje.

Na primer:

Kako je mogoče, da žarnica zasveti skoraj v istem trenutku, čeprav se elektroni po vodniku premikajo zelo počasi?

Šele nato se začne razlaga.

---

# Prvi odstavek

Prvi odstavek ima vedno enak namen.

Bralcu mora pojasniti:

- zakaj je tema pomembna,
- katero vprašanje bomo rešili,
- zakaj obstoječe razumevanje ni dovolj.

Prvi odstavek praviloma ne vsebuje definicij.

Ne vsebuje enačb.

Ne vsebuje zaključkov.

---

# Potek razlage

Kadar je mogoče, naj razlaga sledi naslednjemu zaporedju.

1. pojav
2. opazovanje
3. vprašanje
4. demonstracija
5. razmislek
6. fizikalni model
7. matematični model
8. primer uporabe
9. omejitve modela

Posamezne stopnje se lahko po potrebi združujejo ali izpustijo, vendar je priporočljivo ohraniti naravni tok razmišljanja.

---

# Demonstracije

Demonstracije niso ločeno poglavje.

Vključene so neposredno v razlago.

Njihov namen je:

- vzbuditi vprašanje,
- preveriti napoved,
- potrditi model,
- pokazati omejitve modela.

Demonstracije niso namenjene zgolj presenečenju.

Vsaka demonstracija mora imeti jasen strokovni razlog.

---

# Impresivne demonstracije

V posameznih poglavjih je priporočljivo vključiti tudi demonstracije, ki si jih študent zapomni za vse življenje.

Primeri:

- pregoretje upora,
- uničenje LED zaradi prevelikega toka,
- napačno priključen elektrolitski kondenzator,
- induktivni napetostni sunek,
- elektromagnet,
- vrtinčni tokovi.

Vsaka taka demonstracija mora neposredno podpirati razlago.

Nikoli ni sama sebi namen.

---

# Kognitivni konflikt

Kognitivnega konflikta ne omenjamo.

Bralec ga mora doživeti sam.

Namesto:

"Mnogi napačno mislijo..."

raje napišemo:

"Na prvi pogled bi pričakovali ..., meritev pa pokaže ..."

---

# Matematika

Matematika ni izhodišče razlage.

Najprej mora obstajati razlog za uvedbo enačbe.

Vsaka enačba odgovarja na konkretno vprašanje.

Če enačba ne prispeva k razumevanju, je ne vključimo.

---

# Definicije

Definicije uvajamo šele, ko jih bralec potrebuje.

Ne začnemo poglavja z definicijo.

Definicija naj bo kratka.

Po definiciji vedno sledi razlaga njenega pomena.

---

# Novi pojmi

Nove pojme uvajamo postopoma.

Za vsak nov pojem odgovorimo na naslednja vprašanja:

Zakaj ga potrebujemo?

Kaj opisuje?

Kako ga izmerimo?

Kaj nam pove?

Katere so njegove omejitve?

---

# Fizikalni in matematični modeli

Dosledno ločujemo:

opazovani pojav

↓

fizikalni model

↓

matematični model

↓

eksperimentalno preverjanje

Matematični model nikoli ni predstavljen kot resničnost.

Vedno gre za opis modela.

---

# Analogije

Analogije uporabljamo previdno.

Pomagajo pri začetnem razumevanju.

Nikoli jih ne uporabljamo kot dokaz.

Ko analogija preneha veljati, to jasno povemo.

---

# Zgodovinski razvoj

Kadar je smiselno, predstavimo tudi zgodovinski razvoj modela.

Ne zaradi zgodovine same,

temveč zato,

ker je zgodovina pogosto najbolj naravna pot do razumevanja.

---

# Inženirski pogled

Pri vsakem pomembnem pojmu se vprašamo tudi:

Kaj se zgodi, če naredimo napako?

Zakaj komponenta odpove?

Kako bi to preprečili?

Kako bi vezje izboljšali?

S tem razvijamo inženirski način razmišljanja.

---

# Praktični primeri

Primeri naj bodo realni.

Po možnosti iz:

- gospodinjskih naprav,
- avtomobilov,
- obnovljivih virov energije,
- robotike,
- merilnih naprav,
- šolskih projektov.

Primeri morajo biti dovolj preprosti, da jih lahko študent analizira.

---

# Slog pisanja

Pišemo strokovno.

Ne pišemo suhoparno.

Besedilo mora teči.

Izogibamo se:

- nepotrebnim alinejam,
- nepotrebnim okvirčkom,
- pogostim prekinitvam.

Kadar je mogoče, pišemo v povezanih odstavkih.

---

# Dolžina odstavkov

Odstavki naj praviloma obravnavajo eno idejo.

Če odstavek odgovarja na več vprašanj, ga razdelimo.

Če je krajši od dveh stavkov, preverimo, ali ga lahko združimo.

---

# Slike

Vsaka slika mora imeti namen.

Pred vključitvijo slike se vprašamo:

Ali razumevanje brez slike bistveno trpi?

Če ne, slike ne vključimo.

Slike hranimo v mapi `chapters/figures/`. Imena datotek so opisna, zapisana z malimi črkami in podčrtaji, na primer `zaporedna_vezava_uporov.svg`.

Slike vključujemo s sintakso Pandoc Markdown. Vsaka slika mora imeti opisni napis (*caption*) in oznako oblike `#fig:...`; po potrebi določimo tudi njeno širino. V besedilu se na sliko vedno sklicujemo z navzkrižnim sklicem `@fig:...`. Ne uporabljamo zapisov »na spodnji sliki« ali »na naslednji sliki«, saj se lahko položaj slike med pripravo različnih izhodnih oblik spremeni.

Primer pravilnega zapisa:

```markdown
Kot prikazuje @fig:zaporedna-vezava, sta upora vezana zaporedno.

![Zaporedna vezava dveh uporov.](figures/zaporedna_vezava_uporov.svg){#fig:zaporedna-vezava width=70%}
```

---

# Sheme

Električne sheme pripravljamo v KiCadu.

Vse električne sheme pripravi avtor. Codex električnih shem ne izdeluje, temveč pripravi le njihovo pravilno vključitev v Markdown, vključno z napisom, oznako in navzkrižnim sklicem. Za sheme uporabljamo enake oznake `#fig:...` kot za druge slike.

Sheme naj bodo:

- pregledne,
- standardizirane,
- brez nepotrebnih elementov.

---

# Grafi

Grafe pripravi avtor. Codex grafov ne ustvarja, temveč pripravi samo njihovo pravilno vključitev v Markdown. Grafi uporabljajo napise, oznake `#fig:...` in navzkrižne sklice enako kot druge slike.

Osi grafov morajo vsebovati oznake prikazanih veličin in pripadajoče enote SI. Za grafe imajo prednost vektorski zapisi SVG oziroma PDF.

---

# Simulacije

Za simulacije uporabljamo SimulIDE.

Simulacija ni nadomestilo za eksperiment.

Je pomoč pri razumevanju modela.

Simulacije pripravi avtor v SimulIDE. Codex simulacij ne izdeluje, temveč pripravi le ustrezno vključitev rezultata simulacije v Markdown. Posnetke in druge prikaze simulacij obravnavamo kot slike, zato morajo imeti napis, oznako `#fig:...` in navzkrižni sklic.

---

# Fotografije

Kadar je mogoče uporabljamo lastne fotografije.

Prednost imajo fotografije:

- laboratorijskih postavitev,
- demonstracij,
- dejanskih komponent,
- meritev.

Fotografije pripravi avtor. Codex fotografij ne generira, temveč pripravi samo njihovo ustrezno vključitev v Markdown. Vsaka fotografija mora imeti opisni napis in oznako `#fig:...`; v besedilu se nanjo sklicujemo z navzkrižnim sklicem.

---

# Tabele

Tabele uporabljamo le, kadar izboljšajo preglednost podatkov ali primerjave. Tabela ni nadomestilo za razlago, zato morata biti njen namen in pomen razvidna tudi iz spremljajočega besedila.

Vsaka tabela mora imeti napis in oznako oblike `#tbl:...`. V besedilu uporabljamo navzkrižne sklice `@tbl:...`; tabel ne številčimo ročno.

Primer Pandoc tabele:

```markdown
Izmerjene vrednosti so zbrane v @tbl:meritve-upora.

| Napetost $U$ | Tok $I$ |
|-------------:|--------:|
| 3 V          | 0,03 A  |
| 6 V          | 0,06 A  |

Table: Izmerjena napetost in tok. {#tbl:meritve-upora}
```

---

# Terminologija

Uporabljamo dosledno slovensko strokovno terminologijo.

Angleške izraze uporabljamo le:

- kadar so splošno uveljavljeni,
- ali kadar jih kasneje uporabljajo tudi razvojna okolja.

---

# Enote

Dosledno uporabljamo enote SI.

Oznake veličin so zapisane po mednarodnih standardih.

Med številčno vrednostjo in enoto vedno uporabimo nedeljivi presledek, na primer `9 V`. V matematičnem zapisu uporabimo ustrezen razmik, na primer `$U = 9\,\mathrm{V}$`. Za veličine in enote uporabljamo standardne mednarodne oznake.

---

# Enačbe

Vsaka enačba mora biti v besedilu pojasnjena.

Bralec nikoli ne sme ostati z občutkom, da se je enačba pojavila brez razloga.

Vsaka veličina, uporabljena v enačbi, mora biti v besedilu razložena. Enačbi, na katero se sklicujemo, dodamo oznako oblike `#eq:...`, sklic pa zapišemo kot `@eq:...`. Enačb ne številčimo ročno.

Primer:

```markdown
Povezava med napetostjo, tokom in upornostjo je zapisana v @eq:ohmov-zakon.

$$
U = R I
$$ {#eq:ohmov-zakon}
```

---

# Reference

Za navajanje literature uporabljamo izključno sistem Pandoc Citation. Codex pripravi ustrezen sklic v Markdown in dopolni datoteko `chapters/references.bib` z bibliografskim zapisom. Literature v besedilu ali na koncu poglavja nikoli ne zapisujemo ročno; seznam literature izdela Pandoc.

Primer sklica v oklepaju:

```markdown
[@Novak2024]
```

Primer vključitve avtorja v poved:

```markdown
Kot ugotavlja @Novak2024 ...
```

---

# Navzkrižni sklici

Poglavja, slike, tabele in enačbe označimo z enoličnimi oznakami ter se nanje sklicujemo s Pandocovimi navzkrižnimi sklici:

- poglavja: oznaka `#sec:...` in sklic `@sec:...`,
- slike: oznaka `#fig:...` in sklic `@fig:...`,
- tabele: oznaka `#tbl:...` in sklic `@tbl:...`,
- enačbe: oznaka `#eq:...` in sklic `@eq:...`.

Številk poglavij, slik, tabel ali enačb nikoli ne zapisujemo ročno, saj jih določi Pandoc pri pripravi izhodnega dokumenta.

---

# Opombe pod črto

Opombe pod črto uporabljamo zelo redko in le za kratka dodatna pojasnila, ki bi prekinila glavni tok besedila. Niso namenjene citiranju literature; za vire vedno uporabljamo sistem Pandoc Citation.

---

# Izvorna koda

Programsko kodo zapisujemo v označenih Markdown blokih, pri katerih vedno navedemo programski jezik. Kode ne vključujemo kot sliko.

Primer:

````markdown
```cpp
int vrednost = analogRead(A0);
```
````

---

# Zaključek podpoglavja

Na koncu podpoglavja mora biti jasno odgovorjeno na vprašanje iz uvoda.

Bralec mora dobiti občutek zaključene zgodbe.

---

# Osrednje načelo

Pri pisanju si ves čas zastavljamo vprašanje:

"Ali ta odstavek pomaga bralcu razumeti pojav?"

Če je odgovor ne,

odstavek popravimo ali odstranimo.

Razumevanje ima vedno prednost pred količino informacij.

# Kontrolni seznam poglavja

Ta kontrolni seznam ni obvezna predloga za pisanje poglavij. Namenjen je kot pomoč pri preverjanju, ali je poglavje vsebinsko zaključeno in ali naravno vodi bralca od začetnega vprašanja do razumljivega odgovora.

Pri pregledu poglavja preverimo, ali so smiselno vključeni:

* motivacija,
* uvodno vprašanje,
* pojav,
* demonstracija ali primer,
* razmislek,
* fizikalni model,
* matematični model,
* primer uporabe,
* omejitve modela,
* odgovor na uvodno vprašanje.

---

# Odgovornosti Codexa pri pripravi gradiva

Codex ne pripravlja fotografij, grafov, električnih shem, simulacij, ilustracij ali diagramov. To vizualno gradivo pripravi avtor.

Codex pripravi:

- pravilno vključitev gradiva v Markdown,
- opisni napis,
- ustrezno oznako,
- navzkrižne sklice,
- strukturo poglavij.

Izjema so reference. Pri referencah Codex pripravi sklice v Markdown, dopolni datoteko `chapters/references.bib` in poskrbi za pravilno citiranje s sistemom Pandoc Citation.
