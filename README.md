# laser500

Follow this procedure:

* laser2cas -t -b demo.bin --audio
* sox demo.wav demo.voc
* direct demo.voc demo_7200Hz.tzx
* direct /t 974 demo.voc demo_3600Hz.tzx  

Or even better with tzx id11:

* Remove middle silences with audacity from loop.wav, export the result as wav 8 bit mono loop2.wav. Also possible from laser2cas:
* laser2cas -t -b loop2.bin --audio --nogap
* wav2tzx -pilot 0 loop2.wav loop2_id11.tzx

