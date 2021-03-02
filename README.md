# Implementation-of-TensorFlow-GPU-CUDA-in-Windows

Documentation: Implementation of TensorFlow GPU (CUDA) in Windows

Environment Setup<br/>
1.	Download Anaconda from https://www.anaconda.com/products/individual and Python from https://www.python.org/downloads/. Once Anaconda has been downloaded, run the command
conda install -y jupyter <br/>
#Suggestion: Remember to TICK set-up the environment path during the installation process of Anaconda 
<br/>
2.	To set-up the TensorFlow GPU (CUDA) and its compatible environment, please refer to this YouTube link https://www.youtube.com/watch?v=qrkEYf-YDyI&list=PLjy4p-07OYzulelvJ5KVaT2pDlxivl_BN.<br/>
<br/>
3.	Copy the script from https://github.com/JJLim99/Implementation-of-TensorFlow-GPU-CUDA-in-Windows/blob/master/gpu.yml and save it as gpu.yml. (Remember where you save this file)<br/>
<br/>
4.	Open cmd, go to the file location where you save gpu.yml. Then, run the following command:<br/>
conda env create -v -f gpu.yml <br/>
conda activate gpu<br/>
python -m ipykernel install --user --name gpu --display-name "Python (GPU)" <br/>
<br/>
# To test your environment, copy the script from https://github.com/JJLim99/Implementation-of-TensorFlow-GPU-CUDA-in-Windows/blob/master/Version.ipynb and paste it to your new python script in jupyter notebook. (Remember that you must in the tensorflow environment) 


