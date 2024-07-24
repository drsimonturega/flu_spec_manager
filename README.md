# flu_spec_manager
## A description of the project: what it does, the aim of the project, and what you learned

This project involves the devlopment of code for the storage retival and manipulation of fluorescence spectra for data analysis and machine learning purposes.   The core aims for this work are:

One. Converting fluorescence spectra from manifacturer and instrument specific formats into a common, commer separated value format (*.csv) with annotation that can be used in downstream applications. Many of these scripts can be used with absorbance spectra also.

Two. Produce accessible Python algorithms for the processing and manipulation of spectra for example solvent subtraction or baseline corrections.

Three.  Produce Python scripts that allow the storage,  annotation, manipulation and retrieval of spectra from storage databases.


## Scripts
### clariost2tlt.ipynb
A google colab script that takes the *.csv outout with a single ID from a clariostar plate reader and transopses it to a long thin (yes I know) *.csv with a well_id column, a value column and a sample_id column. The value column is a place holder this can be renamed, removed and further value coluns can be added to suit the upstream nature of your expeimental datas and downstream use of your procesed data.
## Usage instructions
The scripts and algorithms will be made available in three different formats  the first is fire Jupyter notebooks run on Google collab the second is via a bioinformatics (Galaxy) server  and the third is via a use of Python scripts.
## File structure of the project
## License information

This is availible through a GNU General Public License, version 3.
