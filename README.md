# Babelin Speach
It is a simple html file for voice recognition and **Real-time translation**of files videos or audio, use the services offered by web browsers (Chrome/Edge current).
It is possible to see the subtitles in real time (delay minus 1 second), in any video and in any language that the browser supports.

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/Q-7P6Xgqwb0/0.jpg)](http://www.youtube.com/watch?v=Q-7P6Xgqwb0)

## Features⚙️
* Transcription and translation in real time.
* Creation subtitles.
* Allows you to set the time to divide sentences.
* It allows to edit the subtitles using the generated table.
* Import and export in three subtitle formats vtt, ass, srt.
* Allows to join/splits adjacent lines
* Shortcuts for time correction, recognition start and stop, forward and backward to the next subtitle cue, video advance in 500ms, 1sec, and 10sec.
* Option to translate the text with other translators such as DeepL, Yandex, Bing. With copy and paste, and a word counter to facilitate this.
* Time correction for recognition delay.
* Create line new empty press key c.


### Requirements 📋
* [Chrome browser (last version)](https://www.google.com/intl/en_us/chrome/).
* [Edge browser (last version)](https://www.microsoft.com/en-us/edge/).

* Your audio card must support the Mix Stereo option for recording.

* Test only windows 10.

### Installation 🔧

* Download the [BabelinSpeech.html](https://raw.githubusercontent.com/JeanCaro/Babelin/main/BabelinSpeech.html) file anywhere on your computer and open it in your browser or [Test Online](https://jeancaro.github.io/Babelin/BabelinSpeech.html), in this case it only works with Chrome/Edge.
* [Enable Stereo Mix](https://thegeekpage.com/stereo-mix/)


![](https://thegeekpage.com/wp-content/uploads/2020/06/enable-stereo-mix.png)


## Built with 🛠️

* [Speech Recognition](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognitionEvent).- Speech Recognition
* [Speech Api](https://wicg.github.io/speech-api/).- Speech Api
* [Video](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) - Element Video
* [APIS](https://developer.mozilla.org/en-US/docs/Web/API).- Apis Web

## Download 📌

[V 1.0](https://github.com/JeanCaro/Babelin/releases).

##  Test online with the latest version 1.1

* [Babelin Online](https://jeancaro.github.io/Babelin/BabelinSpeech.html)

# All audio is sent to google/cloud servers for processing.

# Version 1.1
* Colors are added to the table based on CPS.
* Button "Fix Time Start" lines short time.
* Add Button for Download Table or Track of subtitle.
* Compatible Edge/Chrome
* By default, groups of statements/sentence/phrases are handled.
* Many bugs are fixed

*CPS stands for "characters per second". It therefore measures the speed at which words appear in subtitles or captions. 

# Recommendations
* **Use Edge/Microsoft** performs **better transcription** and Chrome/Google for It better recognizes the start and end times of the voice, but its transcription is regular. 

* There are two important CPSs, the source CPS and the destination CPS. For example, languages like Japanese, Korean, Chinese can have CPS of 4-6, while languages like English 8-12, or Portugues/Spanish of 10-14.

* Once the whole transcription is finished, if colored lines appear, easily by pressing the "Fix Time Start (CPS)" button, correct the start times of the lines with short time problems.
### Shortcuts General
* Ctrl+Q: Start/Stop	 Recognition Speech
* alt + PageDown: Next cue
* alt + PageUp:	Previous cue

### SHORTCUTS IN TABLE
* Ctrl+alt+ArrowUp: Join row previous
* Ctrl+alt+ArrowDown: Join row next
* Ctrl+alt+J: Split row in cursor or selection

### SHORTCUTS IN CELLS TIME 
* minus (-): rest 100 ms to start time
* plus (+): add 100 ms to start time

### SHORTCUTS IN VIDEO
* Q: Start/Stop	 Recognition Speech
* P: Play/Stop video
* C: Hold down the key C, create a new subtitle line empty
* Alt + ArrowUp: Forward 5 seconds
* Alt + ArrowDown:	Rewind 5 seconds
* Ctrl + ArrowUp: Forward 10 seconds
* Ctrl + ArrowDown:	Rewind 10 seconds
* PageDown: Next cue
* PageUp:	Previous cue
* M: Forward 1 second
* Shift + M:  Forward 500 ms
* N: Rewind 1 second
* Shift + N: Rewind 500 ms
* Del: Delete cue(s) active
* Ctrl + Del: Delete all cue(s) active

* +: add 100 ms to start time of last cue active.
* -: rest 100 ms to star time of last cue active.
* Alt + +: add 100 ms to start time of last cue active(All).
* Alt + -: rest 100 ms to star time of last cue active(All).
* ctrl + +: add 100 ms to end time of last cue active.
* ctrl + -: rest 100 ms to end time of last cue active.

# Subtitles and CPS
https://captiz.com/wp-content/themes/captiz/SubtitlingGuidelinesCaptiz.pdf

https://partnerhelp.netflixstudios.com/hc/en-us/articles/215758617-Timed-Text-Style-Guide-General-Requirements

https://www.authot.com/en/2022/02/10/synchronisation-of-subtitles/
