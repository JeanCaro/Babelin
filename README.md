# Babelin Speach
It is a simple html file for voice recognition and real-time translation of files videos or audio, Use the services offered by web browsers(Chrome current).
It is possible to see the subtitles in real time (delay minus 1 second), in any video and in any language that the browser supports.

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/Q-7P6Xgqwb0/0.jpg)](http://www.youtube.com/watch?v=Q-7P6Xgqwb0)

## Features⚙️
* Transcription and translation in real time.
* Allows you to set the time to divide sentences.
* It allows to edit the subtitles using the generated table.
* Import and export in three subtitle formats vtt, ass, srt.
* Allows to join/splits adjacent lines
* Shortcuts for time correction, recognition start and stop, forward and backward to the next subtitle cue, video advance in 500ms, 1sec, and 10sec.
* Option to translate the text with other translators such as DeepL, Yandex, Bing. With copy and paste, and a word counter to facilitate this.
* Time correction for recognition delay.

### Requirements 📋
* [Chrome browser (last version)](https://www.google.com/intl/en_us/chrome/).

* Your audio card must support the Mix Stereo option for recording.

* Test only windows 10.

### Installation 🔧

* Download the [BabelinSpeech.html](https://raw.githubusercontent.com/JeanCaro/Babelin/main/BabelinSpeech.html) file anywhere on your computer and open it in your browser, in this case it only works with Chrome. (Maybe Microsoft Edge in the future)
* [Enable Stereo Mix](https://thegeekpage.com/stereo-mix/)

## Built with 🛠️

* [Speech Recognition](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognitionEvent).- Speech Recognition
* [Speech Api](https://wicg.github.io/speech-api/).- Speech Api
* [Video](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) - Element Video
* [APIS](https://developer.mozilla.org/en-US/docs/Web/API).- Apis Web

## Download 📌

[V 1.0](https://github.com/JeanCaro/Babelin/releases).

## Online

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
* Use Edge/Microsoft performs better transcription and Chrome/Google for It better recognizes the start and end times of the voice, but its transcription is regular. .
* There are two important CPSs, the source CPS and the destination CPS. For example, languages like Japanese, Korean, Chinese can have CPS of 4-6, while languages like English 8-12, or Spanish/Portugues of 10-14.
* Once the whole transcription is finished, if colored lines appear, easily by pressing the "Fix Time Start (CPS)" button, correct the start times of the lines with short time problems.

# Subtitles and CPS
https://captiz.com/wp-content/themes/captiz/SubtitlingGuidelinesCaptiz.pdf
https://partnerhelp.netflixstudios.com/hc/en-us/articles/215758617-Timed-Text-Style-Guide-General-Requirements
https://www.authot.com/en/2022/02/10/synchronisation-of-subtitles/
