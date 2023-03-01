## 1 Structure of the reference codes

825_phase1:  calculate the value of 33 superpolys by 2^53 Trivium calls.  
825_phase2:  recover the correct key by 2^49 Trivium calls.


##2 Usage of the codes 
1. Set the key in nvcc 825phase1.cu

2. 'nvcc 825_phase1.cu -o main'  &&  'nohup ./main &'

3. Input the values of 33 equations and the key streams corresponding to the correct key to 825_phase2.cu

4. 'nvcc 825_phase2.cu -o main'  &&  'nohup ./main &'
