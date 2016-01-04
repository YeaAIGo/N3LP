# N3LP
C++ implementation for Neural Network-based NLP, such as LSTM machine translation!

This project ONLY requires a template library for linear algebra, Eigen (http://eigen.tuxfamily.org/index.php?title=Main_Page)

## Long Short-Term Memory (LSTM)
The LSTM implemented in this project employs a variant of the major LSTM's gate computation where previous cell states are used to compute input/output gates.
See [1, 2] for the simplified version of the LSTM implemented here.

[1] http://arxiv.org/abs/1410.4615
[2] http://nlp.stanford.edu/pubs/tai-socher-manning-acl2015.pdf

## USAGE ##
1) modify the line in Makefile to use Eigen<br>
EIGEN_LOCATION=$$HOME/local/eigen_new #Change this line to use Eigen

2) run the command "make"

3) ./run the command "n3lp", and then the seq2seq model training starts (currently)
