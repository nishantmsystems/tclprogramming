contact nishant11mittal@gmail.com

Setting Design Name as 'openMSP430'

Setting Output Directory as './outdir_openMSP430'

Setting Netlist Directory as './verilog'

Setting Early Library Path as 'osu018_stdcells.lib'

Setting Late Library Path as 'osu018_stdcells.lib'

Setting Constraints File as 'openMSP430_design_constraints.csv'

Info: Below are the list of initial variables and their values. User can use these variables for further debug. Use 'puts <variable name>' command to query value of below variables
DesignName = openMSP430
OutputDirectory = /home/vsduser/vsdsynth/outdir_openMSP430
NetlistDirectory = /home/vsduser/vsdsynth/verilog
EarlyLibraryPath = /home/vsduser/vsdsynth/osu018_stdcells.lib
LateLibraryPath = /home/vsduser/vsdsynth/osu018_stdcells.lib
ConstraintsFile = /home/vsduser/vsdsynth/openMSP430_design_constraints.csv

Info: Output directory found in path /home/vsduser/vsdsynth/outdir_openMSP430

Info: Early cell library found in path /home/vsduser/vsdsynth/osu018_stdcells.lib

Info: Late cell library found in path /home/vsduser/vsdsynth/osu018_stdcells.lib

Info: RTL netlist directory found in path /home/vsduser/vsdsynth/verilog

Info: Constraints file found in path /home/vsduser/vsdsynth/openMSP430_design_constraints.csv

 Info: Dumping SDC constraints for openMSP430

rows = 57

columns = 11

clock_start = 0

clock_start_column = 0
clock_period = 1

input_ports_start = 4

output_ports_start = 27

Info-SDC: Working on clock constraints.....

Info-SDC: Working on IO constraints.....

Info-SDC: Categorizing input ports as bits and bussed

Info-SDC: Working on IO constraints.....

Info-SDC: Categorizing output ports as bits and bussed

Info: SDC created. Please use constraints in path  /home/vsduser/vsdsynth/outdir_openMSP430/openMSP430.sdc

Info: Creating hierarchy check script to be used by Yosys

Info: Checking hierarchy .....

Info: Hierarchy check PASS

Info: Please find hierarchy check in details in /home/vsduser/vsdsynth/outdir_openMSP430/openMSP430.hierarchy_check.log for more info

Info: Creating main synthesis script to be used by Yosys

Info: Synthesis script created and can be accessed from path /home/vsduser/vsdsynth/outdir_openMSP430/openMSP430.ys

Info: Running synthesis.............

Info: Synthesis finished successfully

Info: Please refer to /home/vsduser/vsdsynth/outdir_openMSP430/openMSP430.synthesis.log

info: Please find the synthesized netlist for openMSP430 at below path. You can use this netlist for STA or PNR

/home/vsduser/vsdsynth/outdir_openMSP430/openMSP430.final.synth.v

Info: Timing Analysis Started ... 

Info: initializing number of threads, libraries, sdc, verilog netlist path...





FINAL OUTPUT
vsduser@vsduser-tclworkshop:~/vsdsynth$ ./vsdsynth openMSP430_design_details.csv >test.log

Info: enable prelayout_timing is 1. Enabling zero-wire load parasitics

Info: STA finished in 3sec seconds


						****PRELAYOUT TIMING RESULTS**** 					
     ----------         -------  --------------       ---------       ---------        --------        --------         -------         -------
     DesignName         Runtime  Instance Count       WNS Setup       FEP Setup        WNS Hold        FEP Hold         WNS RAT         FEP RAT
     ----------         -------  --------------       ---------       ---------        --------        --------         -------         -------
     openMSP430            3sec            6845               -               0      -1.6e-05ns               1               -               0
     ----------         -------  --------------       ---------       ---------        --------        --------         -------         -------
