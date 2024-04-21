# Lamport-Mutual-Exclusion

The project requires implementation of lamport's Mutual exclusion using logical clock. The project has to be implemented via sockets because you need to communicate between 3 devices. The critical section can be assumed to be access to a file on any one of the 3 machines. There need to be two threads per device. One thread shall create local event and send event; the send event should only be for mutual exclusion request. The other thread need to act as port listener and hence, receiver thread. The only catch here is to synchronize between sender and receiver thread to update the logical clock. 
