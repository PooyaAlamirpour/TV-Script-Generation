[image1]: ./Images/Poster.jpg "Poster"
[image2]: ./Images/Result.png "Result"
## Deep Learning: TV Script Generation RNN

In this project, I'll generate Seinfeld TV scripts using RNNs. I'll be using a Seinfeld dataset of scripts from 9 seasons. The Neural Network I'll build will generate a new, "fake" TV script.
For implementing this project we have some topics as below:
* Natural language processing (NLP)
* RNN (LSTM, GRU)
* Word embedding

![Sample Output][image1]

## Installation
For running this project you should install some requirements such as [Anaconda](http://conda.pydata.org/docs). 
> Conda is an open source package management system and environment management system 
for installing multiple versions of software packages and their dependencies and 
switching easily between them. It works on Linux, OS X and Windows, and was created 
for Python programs but can package and distribute any software.

Download the latest version of `miniconda` that matches your system.

|        | Linux | Mac | Windows | 
|--------|-------|-----|---------|
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe
[win32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86.exe
[mac64]: https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
[lin64]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
[lin32]: https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86.sh

Before start to work you should define an **Environment** on the Anaconda. You can put this command either on the terminal window such CMD or in the **Anaconda Console Application**.

* __Linux__ or __Mac__: 
	```
	conda create -n tv-script python=3.6
	source activate tv-script
	```
* __Windows__: 
	```
	conda create --name tv-script python=3.6
	activate tv-script
	```
	
Next step is installing `PyTorch` and `torchvision`. 

* __Linux__ or __Mac__: 
	```
	conda install pytorch torchvision -c pytorch 
	```
* __Windows__: 
	```
	conda install pytorch -c pytorch
	pip install torchvision
	```
	
Now it is time to clone the repositort and run it.
```
git clone https://github.com/PooyaAlamirpour/TV-Script-Generation.git
cd TV-Script-Generation
jupyter notebook
```
The below image indicates the result

![Sample Output][image2]
