#macsim
#### Simulator for Heterogeneous Architecture

## Introduction

* MacSim is a heterogeneous architecture timing model simulator that is developed from Georgia Institute of Technology.
* It simulates x86 and NVIDDIA PTX instructions and it is a trace driven cycle level simulator. It models detailed mico-architectural behaviors, including pipeline stages, multi-threading, and memory systems.
* MacSim is capable of simulating a variety of architectures, such as Intel's Sandy Bridge and NVIDIA's Fermi. It can simulate homogeneous ISA multicore simulations as well as heterogeneous ISA multicore simulations. It also supports asymmetric multicore configurations (small cores + medium cores + big cores) and SMT or MT architectures as well.
* Currently interconnection network model (based on IRIS) and power model (based on McPAT) are connected.
* ARM ISA support is on-progress.
* MacSim is also one of the components of SST, so muiltiple MacSim simulatore can run concurrently.


## Note

* Currently, we are developing a power model for GPUS, but the model is not ready to release yet.

 
## Documentation

Please see [MacSim documentation file](http://macsim.googlecode.com/files/macsim.pdf) for more detailed descriptions.


## Download

* You can download tagged versions from [the Releases header item](https://github.com/macsimgt/macsim/releases) of this repository.
* or you can download the latest copy from our svn repository.

```
   svn co https://svn.research.cc.gatech.edu/macsim/trunk macsim --username readonly
   When you prompt password, please enter (there is no password).
```


## People

* Prof. Hyesoon Kim (Project Leader)
* Jaekyu Lee (Main developer)
* Nagesh B. Lakshminarayana (Main developer)
* Jieun Lim (Power Modeling)
* Tri Pho (SST-Macsim)


## Mailing list

If you have a question, feel free to send an email to macsim-dev@googlegroups.com.


## Tutorial

* We had a tutorial in HPCA-2012. Please visit [here](http://comparch.gatech.edu/hparch/OcelotMacsim_tutorial.html) for the slides.
* We had a tutorial in ISCA-2012, Please visit [here](http://comparch.gatech.edu/hparch/isca12_gt.html) for the slides.

