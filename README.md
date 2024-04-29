# AudioSync

A Swift package for determining the time offset between two audio files.

Ported to Swift from original objC implementation by Patrick Vaberer:
[Vaberer/audio_time_shifting](https://github.com/Vaberer/audio_time_shifting/)

Usage:
```
let audioSync = AudioSync()
let timeOffset = audioSync.getSyncOffsetBetweenAudioFiles(audioFile1Path, audioFile2Path)
```

