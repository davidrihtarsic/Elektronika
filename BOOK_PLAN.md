# Univerzitetna skripta: Elektronika

## Vizija projekta

Namen tega projekta je pripraviti sodobno univerzitetno skripto s področja elektronike za študente študijskega programa, ki izobražuje bodoče učitelje tehnike. Skripta ni namenjena izobraževanju inženirjev elektrotehnike, temveč razvijanju dovolj poglobljenega razumevanja elektronskih pojavov, da bodo diplomanti sposobni strokovno pravilno poučevati tehniko, načrtovati preproste elektronske sisteme ter razumeti delovanje sodobnih elektronskih naprav.

Skripta želi preseči tradicionalni način poučevanja elektronike, ki pogosto temelji na zaporednem predstavljanju elektronskih komponent in njihovih enačb. Namesto tega bo znanje organizirano okoli razumevanja fizikalnih pojavov, razvoja modelov in njihove uporabe pri reševanju praktičnih problemov.

Gre za avtorsko zasnovano skripto, katere osrednja vrednost ni zgolj podajanje informacij, temveč sistematično razvijanje načina razmišljanja, ki je značilen za naravoslovje in inženirstvo.

---

# Ciljna skupina

Primarna ciljna skupina so študenti študijskega programa za bodoče učitelje tehnike.

Predpostavlja se:

- osnovno srednješolsko znanje fizike,
- osnovno matematično znanje,
- zelo malo ali nič predhodnega znanja elektronike.

Skripta ni učbenik didaktike tehnike. Didaktične metode se uporabljajo kot organizacijsko načelo razlage, vendar niso predmet obravnave.

---

# Temeljna filozofija knjige

Najpomembnejše vodilo knjige je naslednje:

> Elektronike ne učimo kot zbirke definicij, formul in komponent, ampak kot proces razumevanja naravnih pojavov s pomočjo vedno boljših modelov.

To pomeni, da se novi pojmi vedno pojavijo kot odgovor na smiselno vprašanje.

Bralec naj ne dobi občutka, da si mora zapomniti definicije, ampak da postopoma gradi vedno boljši model sveta.

---

# Epistemološki okvir

Celotna knjiga temelji na jasnem razlikovanju med štirimi ravnmi razlage.

1. Opazovani pojav
2. Fizikalni model
3. Matematični model
4. Meje veljavnosti modela

Ta razmejitev je ena izmed osrednjih značilnosti knjige in mora biti dosledno prisotna skozi vsa poglavja.

Matematične enačbe niso predstavljene kot resničnost, temveč kot opis modela, ki pojasnjuje opazovane pojave.

---

# Zgodovinski razvoj kot naravna pot do modelov

Kjer je smiselno, se posamezni modeli predstavijo po podobni poti, kot so nastali v zgodovini znanosti.

Zaporedje je praviloma:

- opazovanje,
- meritev,
- iskanje zakonitosti,
- oblikovanje modela,
- matematični opis,
- preverjanje modela.

Zgodovina ni sama sebi namen, temveč služi razumevanju razvoja znanstvenega mišljenja.

---

# Kolbov učni cikel

Kolbov učni cikel predstavlja nevidno organizacijsko načelo knjige.

Ne omenja se eksplicitno.

Posamezna poglavja praviloma sledijo zaporedju:

- konkreten pojav,
- razmislek,
- oblikovanje abstraktnega modela,
- uporaba modela v novi situaciji.

Kolb ni uporabljen mehanično, ampak kot pomoč pri naravnem razvoju razlage.

---

# Kognitivni konflikt

Kognitivni konflikt ni nikoli predstavljen neposredno.

Namesto naštevanja napačnih predstav se uporablja naslednji pristop:

- predstavitev pojava,
- napoved bralca,
- demonstracija,
- ugotovitev, da obstoječa razlaga ni zadostna,
- uvedba novega modela.

Bralec sam odkrije omejitve intuitivnega razmišljanja.

---

# Demonstracijski eksperimenti

Demonstracijski eksperimenti imajo v knjigi pomembno vlogo.

Niso laboratorijske vaje.

Niso predstava.

Njihov namen je:

- motivacija,
- sprožitev vprašanja,
- preverjanje napovedi,
- razlaga modela,
- povezava teorije s prakso.

Eksperiment je vedno sestavni del razlage.

Posebej se zbirajo tudi ideje za izrazite demonstracije, ki si jih študent zapomni za vse življenje (npr. pregoretje upora, uničenje LED zaradi prevelikega toka, induktivni sunek pri tuljavi ipd.), vendar imajo vedno jasen strokovni namen in niso same sebi namen.

---

# Inženirski pogled

Knjiga ne razlaga le pravilnega delovanja elektronskih vezij.

Pomemben del razlage predstavljajo tudi:

- odpovedi komponent,
- preobremenitve,
- dimenzioniranje,
- robustnost rešitev,
- varnost,
- preprečevanje napak.

Odpoved elektronske komponente ni obravnavana kot zanimivost, temveč kot pomemben vir razumevanja delovanja elektronskih sistemov.

---

# Organizacija poglavij

Vsako podpoglavje odgovarja na eno pomembno strokovno vprašanje.

To vprašanje praviloma ni zapisano v naslovu.

Naslov ostane strokoven.

Vprašanje se pojavi v uvodnem odstavku.

Primer:

Naslov:

> Električna upornost

Uvod:

> Pri enaki napetosti skozi različne vodnike ne teče enak električni tok. Od česa je to odvisno?

Celotno podpoglavje nato sistematično odgovori na to vprašanje.

---

# Slog pisanja

Besedilo mora biti podobno kakovostnim univerzitetnim učbenikom.

Značilnosti:

- zvezno besedilo,
- čim manj drobljenja,
- malo okvirčkov,
- malo nepotrebnih alinej,
- strokovni slog,
- jasna terminologija,
- postopno razvijanje idej.

Vsak odstavek mora imeti jasno funkcijo.

Ne pišemo odstavkov, ki ne prispevajo k razumevanju.

---

# Vloga matematike

Matematika ni izhodišče razlage.

Pojavi se šele, ko obstaja potreba po kvantitativnem opisu pojava.

Zaporedje je praviloma:

pojav

↓

model

↓

matematika

↓

uporaba modela

---

# Vizualni elementi

Sheme:

- KiCad

Simulacije:

- SimulIDE

Fotografije:

- lastne fotografije demonstracij

Grafi:

- meritve iz eksperimentov

TikZ se ne uporablja.

---

# Organizacija projekta

Primarni zapis knjige predstavljajo Markdown datoteke.

PDF je rezultat prevajanja s Pandocom.

Repozitorij GitHub predstavlja osrednje mesto razvoja projekta.

---

# Predlagana struktura repozitorija

Elektronika/

BOOK_PLAN.md

BOOK_STRUCTURE.md

book/

figures/

kicad/

simulations/

references/

notes/

templates/

build/

---

# Pomembne pomožne datoteke

BOOK_PLAN.md

Opis filozofije knjige.

BOOK_STRUCTURE.md

Kazalo knjige.

DECISIONS.md

Zgodovina pomembnih odločitev.

notes/demonstrations.md

Ideje za demonstracije.

notes/ideas.md

Sproti nastajajoče ideje.

notes/analogies.md

Primerjave in analogije.

notes/common_questions.md

Tipična vprašanja študentov.

---

# Dolgoročni cilj

Končni cilj ni le priprava univerzitetne skripte.

Iz istega projekta morajo biti z minimalnimi prilagoditvami izvedljivi tudi:

- predavanja,
- demonstracijski eksperimenti,
- laboratorijske vaje,
- SimulIDE simulacije,
- zbirke nalog,
- izpitna vprašanja,
- predstavitve,
- spletna različica gradiva.

Markdown predstavlja izvorno obliko vseh učnih gradiv.

---

# Delovno načelo

Celoten projekt obravnavamo podobno kot razvoj kakovostne programske opreme.

Markdown datoteke predstavljajo izvorno kodo.

Git hrani zgodovino razvoja.

Pandoc izdela končne dokumente.

Vsaka pomembna odločitev se dokumentira.

Glavni cilj ni čim hitrejše pisanje knjige, temveč priprava dolgoročno vzdržnega, strokovno kakovostnega in avtorskega univerzitetnega učbenika.
