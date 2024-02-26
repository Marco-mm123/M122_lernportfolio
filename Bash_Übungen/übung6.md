# Übung 6

 ## Aufgabe a:

 ```bash
 cat << END > text.txt
 > a
 > b
 > c
 > d
 > e
 > END
 ```

 ## Aufgabe b:

 ```bash
 sudo -s
 ls -z 2> /root/errorsLs.log
 exit
 ```

 ## Aufgabe c:

Wenn man > benutzt dann wird das ganze file überschrieben und der vorherige inhalt ist weg. Wenn man hingegen >> nutzt dann wird der output nur angefügt und der vorherige inhalt ist immernoch darüber zu finden.

## Aufgabe d:

```bash
whoami > info.txt
```

## Aufgabe e:

```bash
id >> info.txt
```

## Aufgabe f:

```bash
wc -w < info.txt
```