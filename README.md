# yaz
A modified version of Yaz, an available bandwidth estimation tool

Yaz is modified to handle packets from previous streams without aborting the measurement. 
Simply, if packets from old streams arrive after some packets of a new one, they are discarded and the measurement goes on considering only packets for the current stream.
