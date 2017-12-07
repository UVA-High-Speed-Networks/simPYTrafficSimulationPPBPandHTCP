Execute the program as:

stdbuf -o0 -e0 time python multiFlowProcess.py 0.1 700000000 6.1 327868852 7 > op-file.txt
parameters to the program are:

argv[1]: RTT of the HTCP flow in seconds (i.e., 0.1 sec)
argv[2]: Bottleneck link rate of the TCP flow in bps (i.e., 700000000 bps)
argv[3]: burst arrival rate of the PPBP process (i.e., 6.1 per second)
argv[4]: constant bit rate per burst of the PPBP (i.e., 327868852)
argv[5]: random SEED value (i.e., 7) for reproducibility of the test.

The other simulation parameters can be found in globals.py.
