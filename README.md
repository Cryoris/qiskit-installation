# Installing Qiskit via Conda

[Conda](https://conda.io/projects/conda/en/latest/) provides a potential solution to this struggle.
As a package and environment managment system that's its job.
By specifying the packages we want (qiskit) and where from (github's master branch) in an `environment.yml` Conda takes care of all the installation.

Instructions:
1. Install [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) (comes automatically if [Anaconda](https://www.anaconda.com/distribution/) is installed)

2. Run 
```
conda env create -f qiskit-environment.yml
```
If errors occur, go to the known errors section and try again.

3. Test if Qiskit is installed
```
conda activate qiskit-dev
python
>>> import qiskit
```

