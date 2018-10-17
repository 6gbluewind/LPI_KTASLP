# LPI_KTASLP
## Method for identifying lncRNA-protein interaction with Kernel Target Alignment based on Semi-supervised Link Prediction Identifying LncRNA-Protein Interaction with Kernel Ridge Regression based on Fast Kernel Learning

Input: The similarity of lncRNAs and the similarity of proteins are presented in the form of matrices,<br />
       Gauss similarity matrix is constructed by the kernel_gip.m,<br />
       Kernels in the lncRNA or the protein space are fusing with the Kernel Target Alignment; Core method codes corresponds to LapkronrlsMF.m file. <br />
In practice, all the codes and results are packing in the form of .rar files to faciliate uploading or downloading. 
       
### Software
To run our program, put the .mat files and the code files under the same directory.
The 5-fold cross-validation demo is "sample1.m"
The leave one out cross-validation demo is "sample1_loo.m"
       
#### Environment
* MATLAB 
* 4-core CPU
* 20 GB memory
* 64-bit Windows Operating Systems

### Data
* Benchmark dataset is illustrated in [1]. This dataset contains 4158 lncRNA-protein interactions, 990 lncRNAs and 27 proteins.

### Result
AUC.fig, AUPR_loo.fig, AUC_loo.fig, AUPR.fig and results_TKA_LapMFsum.mat are the outcomes. <br />
Also, we give the case study results in local_cases folder.

### References:
[1] W. Zhang, Q. Qu, Y. Zhang, W. Wang, W. Zhang, Q. Qu, Y. Zhang, and W. Wang, “The linear neighborhood propagation method for predicting
long non-coding RNA-protein interactions,” Neurocomputing, vol. 273, pp. 526–534, 2017.

