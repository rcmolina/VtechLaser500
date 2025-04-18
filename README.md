# laser500

Follow this procedure:

* laser2cas -t -b demo.bin --audio
* sox demo.wav demo.voc
* direct demo.voc demo_7200Hz.tzx
* direct /t 974 demo.voc demo_3600Hz.tzx  

or even better with tzx id11:

* wav2tzx -pilot 0 %1.wav %1_id11.tzx


