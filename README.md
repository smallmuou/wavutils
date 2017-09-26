# pcm2wav

pcm2wav is a tool that can convert pcm to wav, or convert wav to pcm.

## install

copy pcm2wav to /usr/local/bin

```bash
git clone https://github.com/smallmuou/pcm2wav
cd pcm2wav
cp pcm2wav /usr/local/bin
chmod +x /usr/local/bin/pcm2wav
```

## usage

```bash
# convert pcm to wav
pcm2wav [OPTIONS] channel samplerate bitdepth pcmfile wavfile

# convert wav to pcm
pcm2wav [OPTIONS] -r wavfile pcmfile
```

## samples

also i provide some sample files for your test. like follow: 

```
samples/
├── sample1.pcm     - channel: 2  samplerate: 44100 bitdepth: 16
├── sample1.wav     - channel: 2  samplerate: 44100 bitdepth: 16
├── sample2.pcm     - channel: 1  samplerate: 8000 bitdepth: 16
└── sample2.wav     - channel: 1  samplerate: 8000 bitdepth: 16
```

## license

The script follow MIT license.
