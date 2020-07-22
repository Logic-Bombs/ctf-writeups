# Alien transmission 1

## Description
  I was listening to my radio the other day and received this strange message... I think it came from an alien?
   
  [squeakymusic.wav](https://mega.nz/file/IQIngaQJ#RrS4SkG8yWLqRGWMmEFzYXn2eFkJR0m4PIJH2v3-SqI)

## Writeup
   First thing I do is pop it open in Sonic Visualizer to see if anything pops up in the spectrogram or if I can see anything interesting like a pattern in the frequencies, but nothing special there.

  After a little digging, I remembered there is a thing called Slow-Scan Television (SSTV)! This is a form of steganography used nowadays to hide JPEGs or PNGs in WAV audio files, but it was originally used to transmit images via radio signals from the moon and back.
   There’s a tool on GitHub [(xdsopl/robot36)](https://github.com/xdsopl/robot36) to encode/decode SSTV in a mode called Robot36. After compiling the tool, we run it against the file and grab our flag!
   
     $ ./decode squeakymusic.wav output.ppm
    
## Flag

rgbCTF{s10w_2c4n_1s_7h3_W4V3}
