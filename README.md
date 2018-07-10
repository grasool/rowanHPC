# Setup Rowan RUCC  
Setup instructions for Rowan University Computational Cluster (RUCC)

After you have been granted access to rucc, please follow the step below:
1.	Download and install putty (for Wondows system) 
2.	Connect to http://rucc.rowan.edu/.
3.	When prompted, use Rowan username and password.
4.	Please verify and confirm if you are in the _**bash**_ shell. You can use: 
    * ```echo $0 ```
    * if the output is not _**bash**_, use ```bash```
5.	If you are working with Dr. Bouaynaya, you have dedicated access to GPU node **coe-gpu-002**.
6.  SSH to GPU node using ```ssh -X coe-gpu-002```
7.	Load appropriate modules for TensorFlow
    ```module load shared
    module load cuda80/toolkit/8.0.61
    module load cudnn/7.0.2
    module load tensorflow/tensorflow_r1.8
8.	Your linux prompt should change to indicate tensorflow environment
9.  Confirm that you have correct python in your path: 
    ```which python```
    
    The path should indicate tensorflow module installation directory
8.	Run the CIFAR_10 test file.

