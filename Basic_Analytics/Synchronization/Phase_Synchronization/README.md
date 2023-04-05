# Phase Synchronization

### Attention

Other names in literature for the same analysis (formula): 

- Phase-locking value
- Phase-locking factor
- Phase correlation
- Synchronization
- Phase clustering

  The consensus of a name sometimes is confusing, because the same concept can evolve differently in diverse knowleged areas. Bringing the mindset of math, the name that best approach the logic of synchronization is:

**Inter-site phase clustering**

$$(\varphi_i^t)= arctan (\widetilde{Y}_i^t)/ Y_i^t)$$  



$$ISPC_{Y_{1},Y_{2}}= \frac{1}{L} \vert \sum_{t=1}^{L} e^{j(\varphi_1^t - \varphi_2^t)} \vert $$

Y = univariate time series.
$\widetilde{Y}_i^t$= Hilbert transform.
j= imaginary unit.
L= length.

## Inter-site Phase Clustering

In this analysis we are looking for patterns of "phases" in waves. Remember that a phase is a cycle repetition dependent of time, period, amplitude and frequency and can be represented using angles diagrams:

![Figure 1](https://upload.wikimedia.org/wikipedia/commons/9/92/Phase_shifter_using_IQ_modulator.gif "Figure 1")
