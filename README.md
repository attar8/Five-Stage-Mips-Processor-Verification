# Five-Stage-Mips-Processor-Verification
The MIPS processor this project intends to verify is a 16 bit, 5 staged pipelined processor. It provides 16 instructions with 49 variants. This verification process of this design involves first verifying individual blocks of each stage and then verifying the overall working of the design.

Although this remains a two-step process this is done by automating the verification process and making use of only one testing system which has interfaces to all the internal blocks as well as the main input-output blocks. By this process, the verification can be highly automated, high-speed and accurate.

An agent is a container that holds all the needed components for a particular protocol. A typical UVM agent might contain a driver, monitor, and sequencer.
The sequencer controls the flow of sequences that are created either with constrained random or directed data. You can think of a sequence as a packet of data that represents a transaction or protocol. Essentially, a sequencer passes a transaction to the driver.
The driver then drives the interface based on the bus protocol with that transaction. The driver can also send a response to the sequencer, if necessary.
The monitor captures the transactions based on the protocol and can implement checkers to verify the protocol

Functional coverage in UVM is a user-defined metric that measures how much of the design specification that are captured in the test plan has been exercised.
Used to measure whether interesting scenarios, corner cases, specification invariant have been observed, validated, and tested.
It is used to access that the random and focused tests adequately exercise the design.
System Verilog has a rich set of coverage construct to enable functional coverage collection
Focus of functional coverage in UVM is on the inputs to the DUT. To check if all the valid combinations of inputs/stimulus were exercised.

