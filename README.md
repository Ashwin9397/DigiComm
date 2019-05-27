# Approaching the Guassian Capacity
Amplitude and phase-shift keying or asymmetric phase-shift keying
(APSK) is a digital modulation scheme that conveys data by changing,
or modulating, both the amplitude and the phase of a reference signal
(the carrier wave). In other words, it combines both amplitude-shift
keying (ASK) and phase-shift keying (PSK) to increase the symbol-set. It
can be considered as a superclass of quadrature amplitude modulation
(QAM). The advantage over conventional QAM, for example 16-QAM, is
lower number of possible amplitude levels.
Bandwidth is a very precious resource when it comes to communication
and must be used carefully. And hence we come up with various
measure such that we transmit only those information which are useful.
Entropy is nothing but
the least average number of bits required to transmit the signal. Now
when the input follow equiprobable or uniform distribution, by applying
the above equation we can find that the value of entropy is maximum.
But if we can convert it into Guassian the entropy of the signal
decreases and leads to the better utilization of the available bandwidth.
Moreover, a careful design of the constellation geometry can approach
the Gaussian capacity as the constellation size grows to infinity. To
show the implementation we take a sample image input. The input
sample is large such that is can be approximated as a uniform
distribution. These values are then mapped to a variable U and V and so
they also do follow uniform distribution. But using Box-Muller
transformation these symbols are then mapped to Another set ,say X
and Y which follow Guassian distribution.Equiprobable signals are the worst case scenario when transmission is
considered, sop we can convert then to guassian so as to utilize the
available bandwidth is a better way.
