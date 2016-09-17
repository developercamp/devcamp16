# shell:

* Bedienung:
  * Autocompletion: TAB
  * Rückwärtsscuhe: Strg+R
  * Navigation durch History: hoch/runter
  * letzten Befehl noch mal ausführen: !!
  * history anzeigen: `history`
  * schnell nach links/rechts: alt+richtung
* Ausgabe aus einem Programm als Eingabe in ein anderes Programm `programm1 | programm2`
* Ausgabe eines Programmes als Parameter für anderes Programm: `programm1 $(programm2)`
* Ausgabe eines Programmes als Eingabedatei für ein anderes Programm: `programm1 <(programm2)`
* Job-Management: Strg-z, bg, fg, jobs, disown - oder gleich mit nohup starten
* screen, tmux
* pipen nach files, stdout, stderr: &gt;filename, >&1, >&2
* pipen aus files: &lt;filename
* alles über bash: http://tldp.org/LDP/abs/html/

## Ordner wechseln:
* cd
  cd -
  cd ~
* pushd
  popd
  dirs -v

## Dateien lesen

* cat
* echo
* head
* tail
* less (+lesspipe)
* more
* most
* vimpager

##Dateien finden
* find
* locate  (bitte nur single-user-systeme)
* xargs

##Strings suchen
* grep
* ack2
* sed -n '/suchstring/p'

##Strings manipulieren
* cut
* paste
* sed
* tr
* awk
* jq (json-query)
* expr

* test

## Dateien kopieren
* cp
* scp
* rsync
* dd
* cpio

## Dateien verschieben
* mv
* mmv
* rename

## Verschlüsselte Verbindungen testen
* openssl s_client
* testssl.sh

## Netzwerkverbindungen testen/weiterleiten etc.
* nc
* socat
* stunnel
* mtr
* tcpdump

## Web
* curl
* wget

## auf anderen Rechner wechseln
* ssh

## Editoren
* nano, pico
* vim
* emacs
* joe
* jed

## Doku
* pandoc
* dot

## Archive
* tar
* gzip
* zip
* bzip2
* 7zip
* cpio
* pax

## Passwörter
* pass

## Versionsverwaltung
* git
* hg
* svn

# anderer Kram
* ddrescure
* mc
* z
* fzf

## Software mit erhöhten Rechten ausführen:
* sudo
* unter Windows: eldo

# Windows:
* msys2 als Unix-Umgebung
  * bringt pacman als Paketmanager mit (Software installieren mit `pacman -S paketname`, für alles andere siehe Arch-Wiki)
  * am besten einmal `mkpasswd > /etc/passwd` ausführen und dann homedir auf /c/users/_username_ anpassen
* Conemu als Konsolen-Emulator
  * optional, experimentell: kombinieren mit conemu-msy2
* evtl TERM auf 'cygwin' setzen
* sehr empfehlenswert: die sysinternals-suite im PATH
