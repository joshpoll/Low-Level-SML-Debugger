# Low-Level SML Debugger

A low-level SML Debugger that produces all information about SML run-time state as described by [The Definition of Standard ML (Revised)](http://sml-family.org/sml97-defn.pdf).

This is accomplished by using the [Poly/ML](https://www.polyml.org/) debugger on a modified version of the [HaMLet SML reference interpreter](https://people.mpi-sws.org/~rossberg/hamlet/) with improved pretty printing.


## Usage
Requires Poly/ML.
`cd hamlet`
`poly --use "test.sml"`

Within the Poly/ML REPL, call
`Sml.evalString "<your SML program here>";`

and debug as normal. More info to come about how to print info exactly.
