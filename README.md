# AlterTLMS
Alternative thread local memory storage
Navid Nazari
======================================================

- What is AlterTLMS?
its a replacement for tls api/posix, you can use it to prevent unfree'ed memory issues on some thread-situations, for example, clearing memory after termination of threads.
AlterTLMS keeps memory addresses to itself.

