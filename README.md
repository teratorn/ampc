# ampc
AMP (command) Compiler -- See AMP: https://amp-protocol.net

Takes specifications of AMP Commands in JSON and compiles to appropriate Twisted implementations in Python.

May support other persistence formats besides JSON in the future, and additional implementations of AMP, not just Twisted's.

The idea is the keep the specification of your AMP Commands and any other portable metadata related to your AMP "dialect" (and implementation of your application in AMP) in a portable format such as JSON. Other formats are expected to be supported in the future.

Hopefully moving this work from Twisted branch will encourge independent development and encourage further development of the AMP ecosystem! Please have safe and responsible fun with that.
