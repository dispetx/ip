# Dispet server i gk-dispet Git repozitorij
[dispet: IP adresa](ip-adresa)

## Stablo gk-dispet (git usluga)

Repozitorij mozete klonirati sa:

```bash
$ git clone git://ipadresa/gk-dispet
```

## Dispet server (ssh usluga) 

## Korisnicka imena i lozinke:

```bash
root root
dado dado
filip filip
toni toni
joso joso
mario mario
``

Prijaviti se mozete sa:

```bash
$ ssh imekorisnika@ipadresa
```

Usluge, programi i protokoli pod imenima ssh i git najsigurniji su na svijetu. Ako sa Dispet serverom ili dispet repozitorijem radite pomocu ta dva programa, rizik je zanemariv. 

Ako koristite internetski pretrazivac za pristup internetskoj stranici preko http protokola, tada ne postoji garancija da netko nije nesto promijenio sto bi vas moglo ugroziti. Iako je realan rizik takoder zanemariv.

Dakle, ssh i git sigurni su za koristenje. Sigurno koristenje web stranice je lokalno koristenje. Naime, kada na siguran nacin klonirate Dispetov Git repozitorij gk-dispet tada mozete uci u direktorij `dokumentacija/build/html` i pokreniti web server na vasem lokalnom racunalu ili na cijeloj vasoj lokalnoj mrezi:

```bash
$ python -m http.server
```
