# Verilog A Manuals & Tips

(1) Lexical Conventions

* Comments

* Identifier

* Number
  * Integer
  * Real

(2) Datatypes, Expressions

(3) Net

(4) Modules, Ports

(5) Parameters

(6) Paramset

(7) Procedural Programming

(8) Branches

(9) Derivative, Intergral

(10) Math Functions

(11) User-Defined Functions

(12) LUT

(13) Small Signal Functions

(14) Filters

(15) Events

(16) Runtime Support

(17) 


Digital Circuit Design Flow

: Design Spec > High-Level Design > Testbench Development > Behavioral Simul \>

                  (          Verilog HDL Coding       )
                
Gate-Lv Design > Timing Simul > Board Implem > Testing

     (   Netlist Synthesis   )

(2) Hardware Description Language
* Definition: Programming language for description of digital hardware
  * Hardware inherently PARALLEL, CONCURRENT
* Advantages
  * highly portable: simple text file(*.v) w/ standard language format
  * behavioral description: can describe intended behavior of circuit w/out any structural detail
  * automatic synthesis: HDL code synthesized to “automatically” produce circuits; less human errors
  * portable for testing: test bench also written using HDL, compatibility and portability
* Methods
  * Behavioral: Procedural description of actual operation (pseudocode descript)
