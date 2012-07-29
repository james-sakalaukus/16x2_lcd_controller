How to run the demo:
- create a new project in the ISE project navigator
- add files (Project>Add Source):
	+ lcd16x2_ctrl.vhd
	+ lcd16x2_ctrl_demo.vhd
	+ pin_locations.ucf
- if you use the ML501 board you can leave pin_locations.ucf unchanged, otherwise you
  have to adjust the locations for your board (see your board's schematics)
- implement the design and program FPGA
