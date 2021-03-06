wavesurfer.js changelog
=======================

1.2.7 (03.12.2016)
------------------
- Timeline bugfixes: correctly unsubscribe on destroy and re-render on zoom (#825, #848)

1.2.6 (19.11.2016)
------------------
- Solve the disappearing canvas problem on zoom (#825)

1.2.5 (19.11.2016)
------------------
- WebAudio backend closes the AudioContext when it is destroyed, unless the AudioContext was passed in as a parameter (params.audioContext)
- The AudioContext is no longer cached in WebAudio.audioContext, use the getter-function WebAudio.getAudioContext. (#862)

1.2.4 (11.11.2016)
------------------
- Fix a problem of Web Audio not playing in Safari on initial load (#749)

1.2.3 (09.11.2016)
------------------

- Add a 'waveform-ready' event, triggered when waveform is drawn with MediaElement backend (#736)
- Add a 'preload' parameter to load function to choose the preload HTML5 audio attribute value if MediaElement backend is choosen (#854)

1.2.2 (31.10.2016)
------------------

- Determistic way to mute and unmute a track (#841)
- Replace jasmine with karma / jasmine test suite (#849)
- Regions plugin: fix a bug when clicking on scroll-bar in Firefox (#851)

1.2.1 (01.10.2016)
------------------

- Added changelog (#824)
- Correct AMD module name for plugins (#831)
- Fix to remove small gaps between regions (#834)
