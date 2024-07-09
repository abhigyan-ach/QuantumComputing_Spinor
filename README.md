# QuantumComputing_Spinor


This was a project to create a simple code to rotate spinor rotations. Spinors are mathematical entities similar to tensors that allow for a more comprehensive treatment of invariance under rotation and Lorentz boosts. Each tensor of rank k corresponds to a spinor of rank 2k, and some tensors can be associated with spinors of the same rank. For instance, a general 4-vector corresponds to a Hermitian spinor of rank 2, representable by a 2 × 2 Hermitian matrix of complex numbers. A null 4-vector can also be linked to a rank 1 spinor, representable by a complex vector with two components.

# Quantum Computing Final Project
The quickest way to run the file would be to clone the project onto Google Collab-clone into GDrive-and run the file on collaboratory. Simply navigate to the following page:
'''
collab.research.google.com
'''
Under the notebooks , click on Upload, and upload the .py file. Under runtime, click on runtime, and feed an angle when prompted.

# Alternate: Running it locally.
Navigate to your favored command line interface-for Windows this would be
PowerShell and for Mac it would be Terminal. Navigate to the location of the project file using:
```
cd path/to/project
```
Once there, check for the requirements.txt file. This contains all the dependencies to run the file. Run the file using the following command:

```
pip install -r requirements.txt
```

Once the above command finishes running, you are ready to run our project. Run the following command:
```
python3 spinor_rotation.py
```
On running the code, you will be prompted to enter an angle of your choice, to see the visualization.
