# laser500

Follow this procedure:

* laser2cas -t -b demo.bin --audio
* sox demo.wav demo.voc
* direct demo.voc demo_7200Hz.tzx
* direct /t 974 demo.voc demo_3600Hz.tzx  

Or better with tzx id11:

1)laser2cas -t -b loop.bin --audio
2)Remove middle silences with audacity from loop.wav, export the result as wav 8 bit mono loop2.wav
3)wav2tzx -pilot 0 loop2.wav loop2_id11.tzx

