[english version below](#Introduction)

# Einleitung
Viele (aktuell so angesagte) smarte Assistenten wie Amazon Alexa, Google Home, Apple Siri und Microsoft Cortana benötigen zwingend eine Internetverbindung um u.a. die Funktionen STT (Sprache in Text) und TTS (Text in Sprache) in ordentlicher Qualität anzubieten. Es gibt aber auch Open Source Projekte die alternative Assistenten entwickeln, die teils offline funktionieren.

Für den Bereich "STT/TTS" werden dazu jedoch gute Trainings-Testdaten (bspw. zum Deep-Learning) benötigt. Hier kommt das Projekt Mozilla Common Voice ins Spiel.

# Und?!
Ich möchte meinen kleinen bescheidenen Beitrag leisten und stelle meine Stimme unter der CC0 Lizenz zur Verfügung. Die notwendigen Sätze entstammen dem Mozilla Common Voice Projekt und die Aufzeichnung der Stimme habe ich mit Mimic-Recording-Studio (von MyCroft) vorgenommen.

# Klingt gut. Was genau gibt es hier.
* Der Corpus als CSV Format, so dass er vom Mimic-Recording-Studio verwendet werden kann (Datenquelle: Mozilla commion voice (anteilig))
* Die LJSpeech-1.1 Struktur (metadata.csv und zugehörige WAV-Dateien) zur Verarbeitung mit mimic2 (basiert auf Tacotron)
> Aufgrund von Github-Größenbeschränkung liegen die gezippten WAV-Dateien im Google Drive ([Download-Link](https://drive.google.com/open?id=1NTi-4r3EWl5dw0k2o4Xh92G0OHvhoxAJ)

# Beispiele
## Orinalaufnahme
Um einen Eindruck von meiner Stimme zu bekommen habe ich einige Original Aufnahmedateien als Beispiel im Ordner /samples/original_recording bereitgestellt.

* [Das Teilen eines Benutzerkontos ist strengstens untersagt.](./samples/original_recording/recorded_sample_01.wav )
* [Der Prophet spricht stets in Gleichnissen.](./samples/original_recording/recorded_sample_02.wav )
* [Bitte schmeißt euren Müll nicht einfach in die Walachei.](./samples/original_recording/recorded_sample_03.wav )
* [So etwas würde mir nie in den Sinn kommen.](./samples/original_recording/recorded_sample_04.wav )
* [Sie klettert auf einen Stein und nimmt eine Denkerpose ein.](./samples/original_recording/recorded_sample_05.wav )
* [Jede gute Küchenwaage hat eine Tara-Funktion.](./samples/original_recording/recorded_sample_06.wav )
* [Jeden Gedanken kannst du hier loswerden.](./samples/original_recording/recorded_sample_07.wav )

# Sonstiges
Bitte verwende es nicht für Böses!
Solltest Du meine (konkrete) TTS Stimme verwenden wäre ich für eine Info zum Projekt und eine Demo dankbar

Außerdem gilt mein Dank an die Projekte/Communities von Mozilla Common Voice und MyCroft / Mimic.
Besonds an Lindsay Saunders (Mozilla) für den netten Kontakt und eltocino, gras64, dominik von der MyCroft Community für die Gedult meine Anfängerfragen gedultig zu beantworten :-).

# Introduction
Many (currently so hip) smart assistants like Amazon Alexa, Google Home, Apple Siri and Microsoft Cortana need an internet connection to offer the functions STT (speech in text) and TTS (text in speech) in decent quality. But there are also open source projects that develop alternative wizards, some of which work offline.

For the area "STT / TTS", however, good training test data (eg for deep learning) are required. This is where the Mozilla Common Voice project comes into play.

# And?!
I want to make my small modest contribution and make my voice available under the CC0 license. The necessary sentences came from the Mozilla Common Voice project and I recorded the voice with Mimic Recording Studio (by MyCroft).

# Sounds good. What exactly is here.
* The Corpus as a CSV format that can be used by the Mimic recording studio (datasource is partial mozilla common voice project)
* The LJSpeech-1.1 structure (metadata.csv and associated WAV files) for processing with mimic2 (based on Tacotron)
>> Due github size restrictions the compressed wav-files can be downloaded from google drive ([Download-Link](https://drive.google.com/open?id=1NTi-4r3EWl5dw0k2o4Xh92G0OHvhoxAJ)


# Miscellaneous
Please do not use it for evil!
If you use my (concrete) TTS voice I would be grateful for an info about the project and a demo.

Also, my thanks go to the projects / communities of Mozilla Common Voice and MyCroft / Mimic. Especially to Lindsay Saunders (Mozilla) for nice contact and eltocino, gras64, dominik from the MyCroft community for the patience to patiently answer my beginner questions :-).

# Mimic analyze(.py) results (after 12000 spoken phrases)
![char_len_vs_avg_secs](./img/12000_phrases_char_len_vs_avg_secs.png?raw=true "char_len_vs_avg_secs")
![char_len_vs_med_secs](./img/12000_phrases_char_len_vs_med_secs.png?raw=true "char_len_vs_med_secs")
![char_len_vs_mode_secs](./img/12000_phrases_char_len_vs_mode_secs.png?raw=true "char_len_vs_mode_secs")
![char_len_vs_num_samples](./img/12000_phrases_char_len_vs_num_samples.png?raw=true "char_len_vs_num_samples")
![char_len_vs_std](./img/12000_phrases_char_len_vs_std.png?raw=true "char_len_vs_std")

# Links
* https://voice.mozilla.org/
* https://github.com/mozilla/CorporaCreator
* https://raw.githubusercontent.com/mozilla/voice-web/master/server/data/de/sentence-collector.txt
* https://community.mycroft.ai/
* https://github.com/MycroftAI/mimic2
* https://github.com/MycroftAI/mimic-recording-studio
* https://github.com/gras64/corpus-file-gen
