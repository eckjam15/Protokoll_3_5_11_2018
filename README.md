# Protokoll_3_5_11_2018

* mit 'passwd' kann man das Passwort ändern
* wenn man keinen Zugang auf das Sysstem mit dem Terminal hat muss man sich physischen Zugang verschaffen
   * Speichermedium auf einem anderen PC-System konfigurieren
* Informationen zu den Benutzerbezogenen Dateien erhält man mit 'man' + Dateiname

### ssh 
* wird aufgeteilt in:
   * programm
   * Übertragungsprotokoll
      * Tcp
   * Shell
   * Secure
### Sicherheit
* mit Passwort ist die Sicherheit nicht gegeben
   * man-in-the-middle attack
* Sicherer ist es mit einem Schlüsselpaar
   * werden mit 'ssh-keygen' erstellt
   * kein man-in-the-middle mmöglich

### Befehle
* 'ssh-keygen' erstellt Schlüsselpaar
* 'cat .ssh/id-rsa.pub'
* 'ssh-copy-id pi@ip-Adresse'
* '~/.ssh/id/rsa'
* '~/.ssh/id-rsa.pub
* '~/.ssh/config'
