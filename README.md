---<<<{ Linux für Blinde und Sehbehinderte }>>>---


|=========== Screenreader unter Linux ===========|

Ein Screenreader ist Standardmäßig in Gnome, KDE und allen darauf aufbauenden Desktops integriert. 

|=========== Starten und Konfigurieren ===========|

Screenreader Einstellungen in Cinnamon öffnen 
    Alt + F2 drücken
    In das Fenster "orca -s" eingeben und Enter drücken

Hier kann dann der Screenreader Konfiguriert werden.

    Um diesen einfach nur zu starten
    Alt + F2 
    "orca" 
    Dann wird nur der Screenreader gestartet.

|=========== Braillie ===========|

Um Brailliezeilen nutzen zu können wird noch zusätzlich das Paket "brltty" benötigt.

|=========== Bildschirmvergrößerung ===========|

Die derzeit besten Tools sind die, die unter Barrierefreiheit in den Einstellungen verfügbar sind, 
alle anderen Bildschirmlupen für Linux sind mehr oder weniger unbrauchbar. 

In den meisten Fällen lässt sich das Menü für Barrierefreiheit auch in die Taskleiste integrieren, 
um den Zugang zu erleichtern.

Ich habe jetzt viele unterschieldiche aussagen zu der Bildschirmvergrößerung unter Linux gehört.
Vorallem die Punkte zur schlechten Darstellungsqualität (also Verpixeltes bild) lassen sich leider nicht beheben.
Die Standard Windows Bildschirmlupe kann das leider auch nicht besser. 
Programme wie ZoomText gibt es unter Linux nicht und selbst wenn man diese Installieren könnte,
würden diese nicht funktionieren. Sie greifen nämlich Maßgeblich auf Windowsschnittstellen zurück umd Texte etc skallieren zu können.
Die Linuxlupen können das nicht und setzen maximal auf Kantenglättungstechnologien.

Am ehsten kann man das mit dem unterschield zwischen einem Optischen und einem Digitalem zoom bei einer Kamera vergleichen.
Linux kann quasi nur Digital zoomen. 

|=========== Probleme die ich noch nicht Lösen konnte ===========|

Probleme mit dem Screenreader sind die sehr veralteten Sprachmodelle, die ein ordentliches Arbeiten erschweren. 
Ich konnte bis jetzt noch keine Methode finden dort halbwegs vernünftige Modelle einzupflegen. 

Das sind Pakete au die ich gestoßen bin, dort sind unterschieldiche Sprachmodelle dabei:
    - speech-tools 
    - speech-dispatcher  
    - speech-dispatcher-espeak  
    - speech-dispatcher-espeak-ng  
    - espeak  
    - espeak-ng 

|=========== diverse Resourcen aus meiner Recherche ===========|

Die meisten sachen beziehen sich hier auf meine Probleme mit den Stimmen.

Anleitungen: 

    - https://help.gnome.org/users/orca/unstable/introduction.html.de  
    - https://techblog.wikimedia.org/2020/07/02/an-orca-screen-reader-tutorial/  
    - https://espeak.sourceforge.net/index.html  
    - https://github.com/linux-speakup/espeakup  
    - https://github.com/GNOME/orca  

Foren Beiträge: 

    - https://help.ubuntu.com/community/TextToSpeech  
    - https://help.ubuntu.com/community/Accessibility  
    - https://wiki.ubuntuusers.de/eSpeak/  
    - http://5in4.de/blog/2010/01/16/text-to-speech-mit-espeak-und-mbrola/  
    - https://askubuntu.com/questions/11448/festival-on-orca 
    - https://forums.linuxmint.com/viewtopic.php?t=348355 
    - https://www.mikrocontroller.net/topic/488756 (deutsche Stimmen) 

Beste Seite für Infos rund um das Thema (bis jetzt): 

    - http://www.linux-fuer-blinde.de/ 

YouTube Kanal mit 1-2 interessanten Beiträgen zu Orca (Englisch): 

    - https://www.youtube.com/@zaccess73/videos  
