---
published: false
---

# Odločitve pri razvoju skripte

Ta dokument vsebuje pomembne vsebinske, pedagoške in tehnične odločitve, sprejete med razvojem univerzitetne skripte. Namen dokumenta je zagotoviti dolgoročno doslednost pri pisanju, tudi če projekt traja več let ali pri njem sodeluje več avtorjev.

---

## 2026-07-19 — Osnovna filozofija skripte

### Ciljna skupina

Skripta je namenjena predvsem študentom študijskih programov za bodoče učitelje tehnike na univerzitetni ravni.

---

### Temeljni cilj

Glavni cilj skripte ni predstaviti elektronskih komponent, temveč razviti razumevanje električnih pojavov, fizikalnih modelov in načrtovanja elektronskih vezij.

---

### Organizacija vsebine

Vsebina je organizirana okoli fizikalnih pojavov in vprašanj, ne okoli elektronskih komponent.

Vsako podpoglavje odgovarja na eno pomembno strokovno vprašanje.

---

### Struktura razlage

Razlage praviloma sledijo zaporedju:

1. opazovanje pojava,
2. demonstracijski eksperiment ali meritev,
3. razlaga pojava,
4. oblikovanje fizikalnega modela,
5. matematični opis,
6. uporaba modela,
7. omejitve modela.

---

### Uporaba matematike

Matematični modeli se uvajajo šele po vzpostavitvi intuitivnega razumevanja pojava.

Matematika je orodje za opis in napovedovanje, ne izhodišče razlage.

---

### Demonstracijski eksperimenti

Demonstracijski eksperimenti predstavljajo sestavni del razlage.

Njihov namen ni popestritev besedila, temveč:

* ustvarjanje motivacije,
* preverjanje napovedi,
* razumevanje fizikalnih zakonitosti,
* razvoj inženirskega načina razmišljanja.

---

### Inženirski pogled

Poseben poudarek je namenjen vprašanjem:

* zakaj vezje deluje,
* zakaj lahko odpove,
* kako odpoved preprečiti,
* kako načrtovati robustnejše rešitve.

---

### Pisni slog

Besedilo je napisano v obliki zveznega strokovnega besedila.

Uporaba okvirjev, opomb in naštevanj je omejena na primere, kjer bistveno izboljšajo preglednost.

---

### Vizualno gradivo

Za izdelavo slik se uporabljajo predvsem:

* KiCad,
* SimulIDE,
* lastne fotografije laboratorijskih poskusov,
* lastni grafi in ilustracije.

---

### Enoten vir gradiva

Markdown predstavlja izvorno obliko vseh vsebin.

Iz istega gradiva se pripravljajo:

* spletna različica (GitHub Pages),
* PDF,
* DOCX,
* druge izhodne oblike.

---

## 2026-07-19 — Organizacija projekta

### Struktura repozitorija

Vsa vsebina knjige je zbrana v mapi `chapters/`.

Podporna dokumentacija projekta ostaja v korenu repozitorija.

---

### Slike

Vse slike se hranijo v mapi:

`chapters/figures/`

---

### Datoteke poglavij

Glavna poglavja uporabljajo obliko:

`2.0_ELEKTRICNI_NABOJ_TOK_NAPETOST.md`

Podpoglavja uporabljajo obliko:

`2.1_Elektricni_naboj.md`

---

## Pravilo za prihodnje odločitve

Vsaka pomembna sprememba koncepta, organizacije ali načina pisanja se najprej zapiše v ta dokument.

Ta dokument predstavlja referenčno zbirko odločitev, ki zagotavlja dolgoročno enotnost celotne skripte.

---

## 2026-07-19 — Zbirka napačnih predstav in kognitivnih konfliktov

V `notes/misconceptions.md` se vodi interna avtorska zbirka pogostih napačnih predstav s področja elektronike. Zbirka se uporablja pri načrtovanju vprašanj, demonstracij, meritev in razlag.

Napačnih predstav v skripti praviloma ne naštevamo neposredno. Namesto tega jih pretvorimo v kognitivni konflikt, pri katerem bralec najprej oblikuje napoved, nato pa z demonstracijo, meritvijo ali analizo odkrije omejitve svojega začetnega modela.

Ta pristop je povezan z implicitno uporabo Kolbovega učnega cikla: konkretna izkušnja, refleksija, konceptualizacija in uporaba.
