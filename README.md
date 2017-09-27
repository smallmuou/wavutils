# wavutils

wavutils is a tool set that process wav file. like follow:

```bash
bin/
├── pcm2wav - convert pcm to wav
├── wav2pcm - convert wav to pcm
└── wavinfo - show info of wav
```

## install

```bash
git clone https://github.com/smallmuou/wavutils
cd wavutils
sudo ./install.sh
```

## usage
* pcm2wav - convert pcm to wav

```bash
pcm2wav channel samplerate bitspersample pcmfile wavfile
```

* wav2pcm - convert wav to pcm

```bash
wav2pcm wavfile pcmfile
```

* wavinfo - show information of wav

```bash
wavinfo wavfile
```

## samples

also i provide some sample files for your test. like follow: 

```
samples/
├── sample1.pcm     - channel: 2  samplerate: 44100 bitspersample: 16
├── sample1.wav     - channel: 2  samplerate: 44100 bitspersample: 16
├── sample2.pcm     - channel: 1  samplerate: 8000 bitspersample: 16
└── sample2.wav     - channel: 1  samplerate: 8000 bitspersample: 16
```

## license

The script follow MIT license.
