# D-PPIsite: 
Improving Protein-Protein Interaction Site Prediction Using Deep Residual Neural Network.

## Pre-requisite:
    - Python3,Pytorch
    - SANN (https://github.com/newtonjoo/sann)
	- NCBI nr database (https://ftp.ncbi.nlm.nih.gov/blast/db/FASTA/)
    - Linux system 
	
## Installation:

*Install and configure the softwares of Python3, SANN. Please make sure that python3 includes the modules of 'os', 'math', 'numpy', 'random', 'subprocess', 'sys', 'torch' and 'shutil'. If any one modules does not exist, please using 'pip3 install XXXX' command install the python revelant module. Here, "XXXX" is one module name.

*Download this repository at  https://github.com/MingDongup/D-PPIsite for academic use. Then, uncompress it and run the following command lines on Linux System.

*The file of "Config.ini" should be set as follows:
~~~
Sann_Runner_Path = xx/SANN/sann/bin/sann.sh
Psi_Blast_Path = xx/blast-2.2.26/
DB_PATH =xx/nr/
Result_Path = xx/out/
~~~
Note that "xx" represent the absolute path.

## Run 
~~~
  $ cd xxxx/D-PPIsite
  $ python D-PPIsite.py xxxx
~~~
NOTE THAT, "xxxx" represent the absolute path to the protein sequence. For example, D-PPIsite.py xxxx/example/2dvwA.fasta

## The prediction result
The prediction results of protein-protein interaction sites are output in each protein file, the PredictionResult file represents the prediction results of protein-protein interaction sites.

## References

Jun Hu, Ming dong, Yu-Xuan Tang, Dong-jun Yu and Gui-Jun Zhang. Improving Protein-Protein Interaction Site Prediction Using Deep Residual Neural Network.