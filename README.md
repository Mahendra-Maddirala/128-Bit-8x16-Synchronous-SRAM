# 128-Bit-8x16-Synchronous-SRAM

Inputs

» A<4:0>–address

» D<3:0>–writedata

» WENB – write-enable bar (low indicates write)

» CLK–clock

Outputs

» Q<3:0>–readdata

Inputs & Outputs

» Allinputswillbeconnectedtobuffers(twoinverterswith2NMOSfins and 4 PMOS fins) to model the output of the flip-flops at the previous stage of the pipeline. These buffers will be included in the provided test-bench.

» Inputvectorsmustbesynchronizedtotherisingedgeoftheclock.

» Outputvectorsmaybedelayedbyanyamountthatallowssuccessful simulation.

» Theoutputmustbeheldsteadyuntilthenextvaluearrives,witha maxiumum rise above GND (dip below VDD) of 100 mV.

» Outputs must be loaded with 5 fF capacitors. These loads will be included in the provided test-bench.

» InputandOutputpinsmustbeontheboundaryofthedesign.

» The clock input will be buffered with a minimum-sized inverter, just as the other inputs. You must insert progressively-sized buffers for larger clock loads yourself, if necessary.


Supply Voltage

» ActiveSupplyvoltagemustbe0.8V 

» Inputandoutputsignalsmustbe0.8Vsignals

*Credits*
****It is a team project done by me(mmaddir@ncsu.edu) and my teammate Sri Sai Sampath Puppala(spuppal@ncsu.edu)****
