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

# sample
pcm2wav 2 44100 16 samples/sample1.pcm out.wav
```

* wav2pcm - convert wav to pcm

```bash
wav2pcm wavfile pcmfile

#sample
pcm2wav samples/sample1.wav out.pcm
```

* wavinfo - show information of wav

```bash
wavinfo wavfile

#sample
wavinfo samples/sample1.wav

++++++++++++++++++++++++++++++++++++++++++++++
+          WAVEFORM INFORMATION              +
++++++++++++++++++++++++++++++++++++++++++++++
    Audio Format:   1 (0x0001)
    Num Channels:   2 (0x0002)
     Sample Rate:   44100 (0x0000ac44)
 Bits Per Sample:   16 (0x0010)
        PCM Size:   622592 (0x00098000)
```

## samples

also I provide some sample files for your test. like follow: 

```
samples/
├── sample1.pcm     - channel: 2  samplerate: 44100 bitspersample: 16
├── sample1.wav     - channel: 2  samplerate: 44100 bitspersample: 16
├── sample2.pcm     - channel: 1  samplerate: 8000 bitspersample: 16
└── sample2.wav     - channel: 1  samplerate: 8000 bitspersample: 16
```

## license

The script follow MIT license.
