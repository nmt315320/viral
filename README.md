# viral


the coronaviruses SARS-CoV-1 and SARS-CoV-2 (SARS-CoV-1/2) that emerged in recent years have high infectivity and strong case fatality rates. Based on RNA-seq data from viral infections, we used existing circRNA identification tools to identify circRNAs encoded by SARS-CoV-1/2.

#Type: Package

Files: 
1.data

SARS-CoV-1/2 dataset:SARS_coronavirus_FRA.fasta  

SAR-Cov-1/2 sequence dataset;

2.code

shapexample.py  

It is used for interpretable analysis of features and can replace its own model. 

usage: python shapexample.py

shap.summary_plot  Important feature ranking

csv2visual.py

The important features are analyzed and the violin diagram is drawn.

usage: python csv2visual.py -i intput.csv -o 1.png -n 2

tsne_pro.py

Feature dimensionality reduction using t-SNE.

usage: tsnepro [-h] -i INFILE -o OUTFILE [-l LAYOUT] [-d DPI]

Visualzes the features based on t-sne in a 2D feature space

optional arguments:
  -h, --help            show this help message and exit
  -i INFILE, --infile INFILE
                        The input file should be csv format, and multiple file
                        should be separated by commas
  -o OUTFILE, --outfile OUTFILE
                        The name of output picture
  -l LAYOUT, --layout LAYOUT
                        The layout of subplots, please input row,column
                        number, default 1,1
  -d DPI, --dpi DPI     The dpi of output picture, default is 300dpi
  example:python3 tsne_pro.py -i test1.csv -o test.png

Pse-in-one coda package

A package for sequence feature extraction.

3.supplements

The tool is developed for circRNA-RBP interaction sites identification using deep hierarchical network
![image](https://github.com/nmt315320/GMNN2CD/blob/f40f59746ae71cbba63b9d411f5b31bb9371ef66/Architecture.png)
# Requirements
- Python 3.7 (64-bit)
- shap
- matplotlib
- Keras 2.2.0 in Python
- TensorFlow-GPU 1.14.0 in Python
- Numpy 1.18.0 in Python
- Gensim 3.8.3
- Ubuntu 18.04 (64-bit)
- 
# Usage

command: python fivefold.py 

You can train the model of 5-fold cross-validation with a very simple way by the command blow:  


 If you have any suggestions or questions, please email me at *yunzeer@gmail.com*.

#License
Copyright (C) 2023 Mengting Niu(yunzeer@gmail.com) 
It can be used for free academically, if there is commercial use, you can contact us by email.
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, see http://www.gnu.org/licenses/.
