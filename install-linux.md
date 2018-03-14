# Instalace (domácí příprava) – Linux

Pro ušetření času na workshopu tě prosíme, aby sis předem
nainstalovala na počítač, který budeš na workshopu používat,
potřebné programy.

Kdyby se ti to nepovedlo, nebo kdybys měla nějaké otázky,
dej vědět – rádi poradíme podrobněji.
Tohle není zkouška tvých schopností :)


## Instalace Pythonu

Otevři si příkazovou řádku.
Konkrétní program se na různých variantách Linuxu jmenuje různě;
zkus „Terminal“ „Terminál“, „Console“ nebo „Konsole“.
Mělo by se objevit okýnko s kouskem textu, který končí dolarem (`$`).
Za dolar napiš `python3 --version` a zmáčkni <kbd>Enter</kbd>.
Výsledek by měl vypadat zhruba takto:

```console
$ python3 --version
Python 3.6.4
```

Objeví-li se ve výpisu „Python“ a číslo verze 3.6 nebo vyšší,
máš Python nainstalovaný. Gratuluji!
Přeskoč na výběr editoru níže.

Objeví-li se „Python“ a verze nižší než 3.6, aktualizuj systém
a zkus to znovu.
Pokud to neumíš nebo to nepomáhá, kontaktuj prosím organizátory.
(Budeme to muset zohlednit v přípravě,
což rádi uděláme, ale musíme o tom vědět.)

Jestli se objeví chybová hláška jako `bash: python3: command not found`,
doinstaluj Python.
Konkrétní příkaz záleží na distribuci:

* Fedora:

  ```console
  $ sudo dnf install python3
  ```

* Ubuntu:

  ```console
  $ sudo apt-get install python3
  ```

* Používáš-li jinou distribuci, předpokládám, že instalovat programy
  už umíš :)


## Výběr editoru

Pusť programátorský editor – program jménem „Gedit“ nebo „Kate“.
Pokud jeden z nich máš, nebo ho umíš standardním způsobem nainstalovat,
nastav si ho podle tohoto návodu:

* [nastavení Gedit](http://naucse.python.cz/lessons/beginners/install-editor/gedit/)
* [nastavení Kate](http://naucse.python.cz/lessons/beginners/install-editor/kate/)

Jestli nemáš ani jeden, kontaktuj prosím organizátory.


## Zpětná vazba

Až budeš mít hotovo, ozvi se prosím organizátorce.
Napiš že máš Linux a sděl který editor používáš.
