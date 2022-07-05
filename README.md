# VisImageNavigator

**VisImageNavigator (VIN)** a lightweight online browser to view and query the dataset and its metadata. VIN
can be used to explore VIS figures and tables, VIS publication venues, keywords, and authors over time.


### How to run

VIN is developed using HTML, CSS and Javascript and is based solely on standard features available in modern web browsers. VIN does not rely on any frameworks or back-end servers. However, you need to [create a simple local HTTP server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server) to load local data files. 

For example, you could run the program by creating a simple python server as follows:

1. Clone the VIN repository:

```
git clone https://github.com/VisImageNavigator/VisImageNavigator.Release.git
```

2. Create the server and run the program

```
cd $VisImageNavigator.Release
python -m SimpleHTTPServer 7800 
```

### Licence

VIN is released under the MIT License (refer to the [LICENSE](https://github.com/VisImageNavigator/VisImageNavigator.Release/blob/main/LICENSE) file for details).

### Citing VisImageNavigator

If you find VIN useful in your research, please consider citing:

```
@article{chen2021vis30k,
  title={{VIS30K}: A collection of figures and tables from {IEEE} visualization conference publications},
  author={Chen, Jian and Ling, Meng and Li, Rui and Isenberg, Petra and Isenberg, Tobias and Sedlmair, Michael and Moller, Torsten and Laramee, Robert S and Shen, Han-Wei and Wunsche, Katharina and others},
  journal={IEEE Transactions on Visualization and Computer Graphics},
  year={2021},
  publisher={IEEE},
  volume    = {27},
  number    = {9},
  pages     = {3826--3833},
  doi="10.1109/TVCG.2021.3054916"
}
```

### Contact

Contact [Rui Li](https://web.cse.ohio-state.edu/~li.8950/) for any queries or feedback related to this application.

### Acknowledgements

This work was partly supported by NSF OAC-1945347, NIST
MSE-10NANB12H181, NSF CNS-1531491, NSF IIS-1302755 and
the FFG ICT of the Future program via the ViSciPub project (no.
867378).
