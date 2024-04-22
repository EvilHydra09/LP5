# Semester 8
# SPPU Computer Engineering 2019 Pattern Final Year-Sem 2 Lab Assignments. (If this repo helped you, do star it! :)
Update Package Index: Make sure your package index is up-to-date by running:
bash
Copy code
`sudo apt update`
Install pip: pip is a package management system used to install and manage software packages written in Python. If you don't have it installed, you can install it with:
bash
Copy code
`sudo apt install python3-pip`
Install Jupyter Notebook: Once pip is installed, you can use it to install Jupyter Notebook:
bash
Copy code
`sudo -H pip3 install jupyter`
Run Jupyter Notebook: After installation, you can start Jupyter Notebook by running the following command in your terminal:
bash
Copy code
`jupyter notebook`
## For Installing the Python in Ubuntu

 `sudo apt install python3`

## For Installing the pip package

 `pip install -r requirements.txt`


## Install G++ in Ubuntu:
 `sudo apt install build-essential` <br>
 
# For running C++ programs run commands:-
## Compile: `g++ file_name.cpp -o file_name`

## Compile: `g++ file_name.cpp -fopenmp`

## Execute: `./file_name.out` [Linux] or `./file_name.exe` [Windows]

## HPC Vector Addition and Multiplication output
(https://colab.research.google.com/drive/1vQefPvH2Ycq5FaDDwqTX0iQppDQROD_i?usp=sharing)

### Steps to run CUDA programs on Google Collab:
1. [Go to Google Collab](https://colab.research.google.com)
2. Create a new Notebook(.ipynb file).
3. Click on Runtime and change runtime type to GPU.
4. Now run `!pip install git+https://github.com/afnan47/cuda.git` in a cell.
5. On a new cell run `%load_ext nvcc_plugin`
6. Test the following code
```
%%cu
#include <iostream>
int main(){
  std::cout << "Hello World\n";
  return 0;
}
```

7. Remember to add `%%cu` before writing the C++ code for every CUDA program. CUDA is now set.
