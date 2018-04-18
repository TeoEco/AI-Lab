##TO record in Linux

##test the mic
arecord test_output.wav
##record
arecord -r 16000 test_output.wav
##playback
aplay test_output.wav 