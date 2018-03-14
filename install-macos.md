# Instalace (domácí příprava) – macOS

Pro ušetření času na workshopu tě prosíme, aby sis předem
nainstalovala na počítač, který budeš na workshopu používat,
potřebné programy.

Kdyby se ti to nepovedlo, nebo kdybys měla nějaké otázky,
dej vědět – rádi poradíme podrobněji.
Tohle není zkouška tvých schopností :)


## Instalace Pythonu


Otevři si příkazovou řádku (terminál) pomocí
*Applications* → *Utilities* → *Terminal*.
Mělo by se objevit okýnko s kouskem textu, který končí dolarem (`$`).
Tam zkopíruj následující příkaz:

```plain
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

a zmáčkni <kbd>Enter</kbd>.
Ono to něco vypíše. Až to skončí a zase se objeví řádek končící dolarem,
zkopíruj další příkaz, a zase potvrď pomocí <kbd>Enter</kbd>:

```plain
brew install python
```

Až skončí i tento, zadej poslední příkaz a <kbd>Enter</kbd>:

```plain
python3 --version
```

Po zadání posledního příkazu by počítač měl vypsat „Python“ a číslo verze
3.6 nebo vyšší.
Pokud to tak není, kontaktuj prosím organizátory
(a nejlépe pošli screenshot).


## Instalace editoru

Druhý program, který budeme potřebovat, je programátorský editor.
Pokud už programátorký editor máš a používáš, instalaci přeskoč;
jinak doporučujeme *Atom*.
Ten si stáhni z jeho [domovské stránky](https://atom.io/) a nainstaluj.


## Zpětná vazba

Až budeš mít hotovo, ozvi se prosím organizátorce.
Napiš že máš macOS a sděl který editor používáš.
