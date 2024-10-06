all: syn

syn:
	BASENAME=mavg \
		CLOCKPERIOD=1.5 \
		TIMINGPATH=/opt/cadence/libraries/gsclib045_all_v4.7/gsclib045/timing \
		TIMINGLIB=slow_vdd1v0_basicCells.lib \
		VERILOG='../rtl/mavg.sv' \
		genus -f genus_script.tcl

clean:
	rm -rf outputs reports genus.log* genus.cmd* *~ fv

