The Neural Network (NN) based Speech Synthesis System
=====================================================

This repository contains the Neural Network (NN) based Speech Synthesis System  
developed at the Centre for Speech Technology Research (CSTR), University of 
Edinburgh.

To build the toolkit: see `./INSTALL`.  These instructions are valid for UNIX
systems including various flavors of Linux;

To run the example system builds, see `egs/README.txt`

As a first demo, please follow the scripts in `egs/slt_arctic`

Setup
-----

``` shell
virtualenv venv -p python2
source venv/bin/activate
pip install -U numpy scipy theano lxml matplotlib bandmat
cd egs/slt_arctic/s1
./run_demo.sh
```

Synthetic speech samples
------------------------

Listen to [synthetic speech samples](https://cstr-edinburgh.github.io/merlin/demo.html) from our demo voice.

Development pattern for contributors
------------------------------------

1. [Create a personal fork](https://help.github.com/articles/fork-a-repo/)
   of the [main Merlin repository](https://github.com/CSTR-Edinburgh/merlin) in GitHub.
1. Make your changes in a named branch different from `master`, e.g. you create
   a branch `my-new-feature`.
1. [Generate a pull request](https://help.github.com/articles/creating-a-pull-request/)
   through the Web interface of GitHub.

Contact Us
----------

Post your questions, suggestions, and discussions to [GitHub Issues](https://github.com/CSTR-Edinburgh/merlin/issues).

Citation
--------

If you publish work based on Merlin, please cite:

Zhizheng Wu, Oliver Watts, Simon King, "Merlin: An Open Source Neural Network Speech Synthesis System" in Proc. 9th ISCA Speech Synthesis Workshop (SSW9), September 2016, Sunnyvale, CA, USA
