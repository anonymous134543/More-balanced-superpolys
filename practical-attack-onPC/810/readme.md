## 1 Structure of the reference codes

810_phase1:  calculate the value of 40 superpolys by 2^44 Trivium calls.  
810_phase2:  recover the correct key by 2^41 Trivium calls.


##2 Usage of the codes 
1. Set the key in nvcc 810_phase1.cu

2. 'nvcc 810_phase1.cu -o main'  &&  'nohup ./main &'

3. Input the values of 40 equations and the key streams (832-896 rounds) corresponding to the correct key to 810_phase2.cu

4. 'nvcc 810_phase2.cu -o main'  &&  'nohup ./main &'
