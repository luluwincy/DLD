OPEN UP UBUNTU
ls
verilog_DLD
cd verilog_DLD
code .

[make code changes]

TO RUN
iverilog -g2012 -o simulation thing.sv thing_tb.sv
vvp simulation
gtkwave thing.vcd
