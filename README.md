# six_stage_pipeline_sim-main

**Description:** Our project is the implementation of six stage pipelined microprocessor. The
architecture is modified to increase the speed of operation. The architecture of our
microprocessor includes the ALU, Pipelined data-path, Data forwarding unit, Control logic, data
and program memories, and Hazard control unit. Hazard detection unit and data forwarding unit
have been included for efficient implementation of the pipeline. In our microprocessor, every
instruction is divided into several parts and each part is called as a stage. This implemented
microprocessor have six-stage pipeline architecture, namely instruction fetch(IF) ,instruction
decode(ID), register read(RR), execution(EXEC), Data memory(MEM) and write back(WB).

**The final branch predictor** shows an average prediction accuracy of 96-97%. Instruction
Encoding Format to simplify the encoding/decoding process, the format is different from the
standard MIPS instruction encoding format.
OP=1 bytes, RS=1 bytes, RT=1 bytes, RD=1 bytes, constant=4 bytes, offset=4 bytes,
address=4 bytes, total=4 bytes.
Each instruction is stored in memory as 16 bytes of binary digits.
The default value of rd, rs, and rt is 255 so that:
In some instructions, Src2 may either be a register rt or an immediate number constant,
and if Scr2 is constant, rt == 255.
For mul, mulu, div and divu, if the instruction is in the format of op rs rt, rd == 255.
Five Stage Pipeline
**Instruction guidelines of project:**
In the Project Zip file, all the instructions are given in the Readme folder. Please have a
look to run our project. Besides that, I am also including the instruction details.
