# Übung 2

## 2.1
    mkdir ~/Docs

## 2.2
    Für das erstellen von 10 files names file1 - file10 habe wir:
- cd Docs
- touch script.sh
- in script vongeden code:
```console
for i in $(seq 1 10);
do
touch file$i
done
```
- chmod 777 script.sh
- sudo ./script.sh

    oder man kann einfach:

```console
touch file{1..10}
```

## 2.3
    rm -f ./*1*

## 2.4
    rm file{2,4,7}

## 2.5
    rm -f ./file*

## 2.6
    mkdir ~/Ordner

## 2.7
    touch ~/Ordner/file{1..10}

## 2.8
    cp -r ~/Ordner/ ~/Ordner2/

## 2.9
    cp -r ~/Ordner/ ~/Ordner2/Ordner3/

## 2.10
    mv ~/Ordner ~/Ordner1

## 2.11
    rm -r ./Ordner*