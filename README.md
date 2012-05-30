fpss-2012
=========

Presentations - Functional Programming Summer School
Politehnica University of Bucharest - 2012

http://theoretical.cs.pub.ro/fpss12/

1. Functional Programming in the Real World
-------------------------------------------

Functional Programming was never in the commercial products development “prime time”. 
It was considered many times more as an academic approach of the software development. 
Still there were companies that understood the real potential that functional programming 
has and have built successful products and businesses based on these concepts.
Even if it has more than fifty years it was and it feels even today ahead of its time.

This presentation will cover the most important products that were implemented in a functional 
programming language and used in the real world. I will also present the competitive advantage 
that helped these products to be successful.
It will cover products developed in languages like lisp – common lisp, scheme, clojure, haskell, 
erlang, scala and others.

2.  Erlang – Concurrent Programming Language and Runtime System
---------------------------------------------------------------

What if I need to build a product that needs to follow these characteristics:
- highly concurrent an distributed systems
- thousands of simultaneous transactions
- support cluster architectures and changes in the cluster topology at runtime
- support may OS’s – Solaris, VxWorks, Windows, Linux, Mac OS X - 32bit, 64bit with SMP support
- no down time ( actually uptime of 99.999% which means maximum downtime of 5 minutes / year)
- highly “expressive” programming language
- recovery from software errors
- recovery from hardware errors
- trace & debug code at runtime
- update code at runtime

Do I have many choices? No, we have only one – which is Erlang. In this presentation I will cover the concepts behind the Erlang programming language and its runtime system that allows an application to have all these key characteristics
described before.