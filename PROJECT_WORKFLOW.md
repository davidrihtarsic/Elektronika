---
published: false
---

# Workflow razvoja projekta

## Namen dokumenta

Ta dokument opisuje način razvoja projekta in sodelovanja med avtorjem, ChatGPT, Codexom in GitHubom. Namenjen je temu, da so vloge, odgovornosti in potek sprememb jasni tudi pri dolgoročnem razvoju univerzitetne skripte.

GitHub predstavlja edini vir resnice za stanje projekta. Zgodovina pogovorov, predlogi in delovne razprave so lahko koristni pri razvoju idej, vendar je referenčna različica vedno tista, ki je zapisana v repozitoriju.

---

## Vloge

### Avtor

Avtor:

* sprejema strokovne in pedagoške odločitve,
* potrjuje spremembe,
* pregleduje PR-je.

### ChatGPT

ChatGPT:

* pomaga razvijati ideje,
* opozarja na nedoslednosti,
* pripravlja navodila za Codex,
* ne spreminja neposredno repozitorija.

### Codex

Codex:

* izvaja spremembe v repozitoriju,
* pripravlja commite,
* pripravlja Pull Requeste,
* brez izrecnega navodila ne spreminja arhitekture projekta.

---

## Razvojni cikel

Tipičen razvojni cikel poteka po naslednjem zaporedju:

1. oblikuje se ideja,
2. ideja se razpravlja in preveri z vidika vsebine, pedagogike in organizacije projekta,
3. sprejme se odločitev,
4. pripravijo se jasna navodila za Codex,
5. Codex izvede spremembe in pripravi commit,
6. Codex pripravi Pull Request,
7. avtor pregleda spremembe,
8. potrjene spremembe se združijo v glavno vejo,
9. GitHub postane nova referenčna različica projekta.

---

## Pravila

* GitHub je vedno pomembnejši od zgodovine pogovorov.
* Novi pogovori se začnejo s pregledom dokumentov v repozitoriju.
* Pomembne konceptualne spremembe se dokumentirajo.
* Večje spremembe potekajo preko Pull Requestov.
* Manjše tehnične spremembe lahko ostanejo v enem commitu.
* ChatGPT nikoli ne predpostavlja stanja repozitorija, ampak ga preveri.
