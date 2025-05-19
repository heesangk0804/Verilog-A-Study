# Verilog A Manuals & Tips

## Verilog Basics

(1) Lexical Conventions

* Comments

* Identifier

* Number
  * Integer
  * Real

(2) Datatypes

* Number
  * Integer
  * Real

* Parameters

* Paramsets

* Genvars

* Nets
 * Definition
 * Signal Natures
 * Net Disciplines

(3) Operators

* Unary

* Binary

* Tenary

* String Operator

## Modules, Modeling

(4) Modules, Ports

* Module

* Declaration

* Instantiation

* Ports


(5) Statement Types

* Assignment

* Sequential Block Statement

* Conditional Statement

* Case Statement

* Repeat Statement

* While Statement

* For Statement


(6) Statement Styles

* Procedural = Behavioral

* Structural


(7) Special Functions

* Derivative, Integral
 * Derivative: ``ddt``
 * Integral: ``idt``


* Mathematical

* User-Defined


## Simulation




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
