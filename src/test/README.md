The idea of this test program is to characterise the speed of the IMBE vocoder on different platforms and CPUs.

As supplied it is written to run under Linux, and was tested on a fast laptop. It makes use of standard POSIX functions to get the elapsed time and to output the result.

The test data is the word "one" from the en_GB IMBE voice file from the P25 Gateway.

On my laptop the decoding takes less than one millisecond, and encoding typically takes five milliseconds.

