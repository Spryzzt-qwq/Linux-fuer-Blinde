---

## Linux für Blinde und Sehbehinderte

### Screenreader unter Linux

Ein Screenreader ist standardmäßig in Gnome, KDE und allen darauf aufbauenden Desktops integriert.

### Starten und Konfigurieren

Um die Screenreader-Einstellungen in Cinnamon zu öffnen:

1. Alt + F2 drücken.
2. In das Fenster "orca -s" eingeben und Enter drücken.

Hier kann dann der Screenreader konfiguriert werden.

Um den Screenreader einfach nur zu starten:

1. Alt + F2 drücken.
2. "orca" eingeben.
3. Der Screenreader wird gestartet.

### Braille

Um Braillezeilen nutzen zu können, wird zusätzlich das Paket "brltty" benötigt.

### Bildschirmvergrößerung

Die derzeit besten Tools sind die, die unter "Barrierefreiheit" in den Einstellungen verfügbar sind. Alle anderen Bildschirmlupen für Linux sind mehr oder weniger unbrauchbar.

In den meisten Fällen lässt sich das Menü für Barrierefreiheit auch in die Taskleiste integrieren, um den Zugang zu erleichtern.

Ich habe viele unterschiedliche Aussagen zur Bildschirmvergrößerung unter Linux gehört. Vor allem die Punkte zur schlechten Darstellungsqualität (also verpixeltes Bild) lassen sich leider nicht beheben. Die Standard-Windows-Bildschirmlupe kann das leider auch nicht besser. Programme wie ZoomText gibt es unter Linux nicht, und selbst wenn man diese installieren könnte, würden sie nicht funktionieren. Sie greifen nämlich maßgeblich auf Windows-Schnittstellen zurück, um Texte etc. skalieren zu können. Die Linux-Lupen können das nicht und setzen maximal auf Kantenglättungstechnologien.

Am ehesten kann man das mit dem Unterschied zwischen einem optischen und einem digitalen Zoom bei einer Kamera vergleichen. Linux kann quasi nur digital zoomen.

### Probleme, die ich noch nicht lösen konnte

Probleme mit dem Screenreader sind die sehr veralteten Sprachmodelle, die ein ordentliches Arbeiten erschweren. Ich konnte bisher noch keine Methode finden, dort halbwegs vernünftige Modelle einzupflegen.

Das sind die Pakete, auf die ich gestoßen bin, die verschiedene Sprachmodelle beinhalten:

- speech-tools
- speech-dispatcher
- speech-dispatcher-espeak
- speech-dispatcher-espeak-ng
- espeak
- espeak-ng

### Diverse Ressourcen aus meiner Recherche

Die meisten Informationen beziehen sich auf meine Probleme mit den Stimmen.

#### Anleitungen:

- [Orca Screen Reader Einführung (deutsch)](https://help.gnome.org/users/orca/unstable/introduction.html.de)
- [Orca Screen Reader Tutorial (Englisch)](https://techblog.wikimedia.org/2020/07/02/an-orca-screen-reader-tutorial/)
- [eSpeak Webseite](https://espeak.sourceforge.net/index.html)
- [espeakup Projekt auf GitHub](https://github.com/linux-speakup/espeakup)
- [Orca Projekt auf GitHub](https://github.com/GNOME/orca)

#### Forenbeiträge:

- [Ubuntu TextToSpeech Community](https://help.ubuntu.com/community/TextToSpeech)
- [Ubuntu Accessibility Community](https://help.ubuntu.com/community/Accessibility)
- [eSpeak auf Ubuntuusers](https://wiki.ubuntuusers.de/eSpeak/)
- [Text-to-Speech mit eSpeak und Mbrola (Blog)](http://5in4.de/blog/2010/01/16/text-to-speech-mit-espeak-und-mbrola/)
- [Festival auf Orca (Ask Ubuntu)](https://askubuntu.com/questions/11448/festival-on-orca)
- [Screenreader auf Linux Mint Forum](https://forums.linuxmint.com/viewtopic.php?t=348355)
- [Deutsche Stimmen auf Mikrocontroller.net](https://www.mikrocontroller.net/topic/488756)

Beste Seite für Infos rund um das Thema (bis jetzt):

- [Linux für Blinde](http://www.linux-fuer-blinde.de/)

YouTube-Kanal mit 1-2 interessanten Beiträgen zu Orca (Englisch):

- [Zaccess73 auf YouTube](https://www.youtube.com/@zaccess73/videos)

