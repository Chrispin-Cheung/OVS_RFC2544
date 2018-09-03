# OVS_RFC2544
 Test suite for openvswitch RFC2544 performance test on IBM Power systems(Power9 and Power8) 
 

Suite with 2544 all 0 loss and 0.002 loss rates

64, 128, 256, 1500 Bytes 60 second trials with RFC 2544

64, 576, 1218, 1500 Bytes 120 second trials with a 10 minute verify step.

Jumbo Frames 2000, 9000

Binary search all these tests above are with 1k flows. 1024

Add tests for 64, 1500 bytes with flow counts of 10000, 100000, and 1 Million, 60 second trials
