# How to Create a BungeeCord Server on Debian 9!
### Hier zeige ich wie man einen BungeeCord Server ganz einfach für Debian 9 installiert :D


``BungeeCord.jar`` von [__*md-5.net*__](https://ci.md-5.net/job/BungeeCord/lastSuccessfulBuild/artifact/bootstrap/target/BungeeCord.jar "BungeeCord hier Downloaden!")

``Spigot.jar`` von [__*GetBukkit*__](https://cdn.getbukkit.org/spigot/spigot-1.8.8-R0.1-SNAPSHOT-latest.jar "Spigot 1.8.8 hier Downloaden!")

dann (**falls vorhanden**) auf dem (S)FTP bzw. **vServer** anmelden!

*Ich finde da:* <a href="https://minehub.de/v-server/v-server-mieten/"><img src="https://minehub.de/static/web/img/meta/favicon-32x32.png" alt="Minehub.de"></a> (*Minehub.de*) <font color="#ff000">empfehlenswert!</font>

Wenn du angemeldet bist, klickst du oben auf die 2 ``.`` und nun sind ganz viele Ordner zu sehen!
Dann suchst du nach einem Ordner namens: ``home`` und klickst da drauf!
<br>
dann in den ``/home/`` danach erstellst du den nächsten Ordner namens: ``Minecraft`` dann navigierst du in diesen Ordner!<br>
Dann erstellst du im ``/home/Minecraft/`` Ordner einen ``Bungeecord`` Ordner!
dann navigierst du ebenfalls da rein

da dann die ``BungeeCord.jar`` hochladen!

danach wieder zum ``/home/Minecraft`` ordner navigieren!
dann einen Ordner namens: ``/home/Minecraft/Lobby/`` erstellen!
da dann die ``spigot-1.8.8-R0.1-SNAPSHOT-latest.jar`` hochladen & zu ``spigot.jar`` umbenennen!
dann einen Ordner namens: ``/home/Minecraft/Gameserver/`` erstellen!
und da ebenfalls die ``spigot-1.8.8-R0.1-SNAPSHOT-latest.jar`` hochladen & zu ``spigot.jar`` umbenennen!

dann bei ``/home/Minecraft/Bungeecord/`` die ``startBungeeCord.sh`` hochladen!

und dann wenn ihr mit Putty eingeloggt seit: ``chmod 777 startBungeeCord.sh``

[__*startBungeeCord.sh*__](https://workupload.com/file/U9KuZCsX "startBungeeCord.sh hier Downloaden!")
<br>*Passwort:* ``bungee``

<br><br>

danach wieder zum ``/home/Minecraft/`` Ordner navigieren!
dann bei ``/home/Minecraft/Lobby/`` die ``startSpigot.sh`` hochladen!

<br><br>
[__*startSpigot.sh*__](https://workupload.com/file/3gUtTvEn "startSpigot.sh hier Downloaden!")
<br>*Passwort:* ``spigot``



# Programme für die Installation eines BungeeCord Server's!

### Putty

[*Putty für x64*](https://the.earth.li/~sgtatham/putty/latest/w64/putty-64bit-0.73-installer.msi "Putty hier für x64 Downloaden!")
<br>
[*Putty für x32*](https://the.earth.li/~sgtatham/putty/latest/w32/putty-0.73-installer.msi "Putty hier für x32 Downloaden!")

### WinSCP
*Ich denke mal das die für* __*x64 & x32*__ *verfügbar sein wird!*
<br>[_**WinSCP für x64**_](https://winscp.net/download/WinSCP-5.15.9-Setup.exe "WinSCP hier für die x64 & x32 Downloaden!")

### FTP Client
<br>[_**FileZilla für x64**_](https://dl4.cdn.filezilla-project.org/client/FileZilla_3.46.3_win64-setup.exe?h=AyHjXFMbBd0yn3lVyK7Srg&x=1577704964 "FileZilla hier für die x64 Downloaden!")
<br>[_**FileZilla für x32**_](https://dl4.cdn.filezilla-project.org/client/FileZilla_3.46.3_win32-setup.exe?h=AiH3P_5I3NthQ9c3A5wIjw&x=1577704964 "FileZilla hier für die x32 Downloaden!")
