# Übung 4
```bash
#File ertstellen:
echo "alpha1:1alpha1:alp1ha
beta2:2beta:be2ta
gamma3:3gamma:gam3ma
obelix:belixo:xobeli
asterix:sterixa:xasteri
idefix:defixi:ixidef" > text.txt

#Suche nach Obelix
grep obelix text.txt

#Suche nach 2
grep 2 text.txt

#Suche nach e
grep e text.txt

#Suche nach nicht gamma
grep -v gamme text.txt

#Suche nach 1,2 oder 3
grep -E [1,2,3] text.txt

#Alle Begriffe vor dem ersten :-Zeichen
cut -d ':' -f 1 text.txt

#Alle Begriffe vor dem ersten :-Zeichen
cut -d ':' -f 1 text.txt

#Alle Begriffe vor dem ersten :-Zeichen
cut -d ':' -f 1 text.txt

```