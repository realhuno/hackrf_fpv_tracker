# hackrf_fpv_tracker

simple test
based on the hackrf_sweep code
https://github.com/mossmann/hackrf
https://github.com/mossmann/hackrf/tree/master/host
just replace the hackrf_sweep.c and compile
Change this lines with your racegod IP
system("curl -d 'deviceId=0' http://10.0.0.22:8080/api/trackers/detection");


scan raceband with
hackrf_sweep -f5658:5940 -w100000 -l32 -g8  >scan.csv


