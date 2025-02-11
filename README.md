# VHDL Counter Bug
This repository demonstrates a common but subtle bug in VHDL code: an off-by-one error in a counter and the omission of a sensitivity list item, affecting the proper operation of a counter. 
The `bug.vhdl` file contains the buggy code.  The `bugSolution.vhdl` file provides the corrected code. 
The bug is related to the counter's reset condition and a possible integer overflow issue. Additionally, missing sensitivity list items can lead to unexpected behavior. The solution addresses both aspects to ensure the counter functions reliably.
