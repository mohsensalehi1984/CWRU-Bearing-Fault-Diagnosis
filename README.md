# CWRU-Bearing-Fault-Diagnosis

Deep learning-based fault diagnosis of rolling element bearings using the **Case Western Reserve University (CWRU) Bearing Dataset**.

** Please click on CWRU_NN.ipynb file to see the code and documentations.**

### Dataset
Uses the standardized NumPy version of the CWRU Bearing Dataset:  
https://github.com/srigas/CWRU_Bearing_NumPy

- Drive End (DE) accelerometer signals only
- 9 fault classes (7, 14, 21 mil faults for IR, Ball, OR + Normal)


### Installation
```bash
git clone https://github.com/yourusername/CWRU-Bearing-Fault-Diagnosis.git
cd CWRU-Bearing-Fault-Diagnosis
pip install -r requirements.txt
