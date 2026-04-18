# Structuring-Jupyter-Files-Using-Rapids-cuML-based-on-the-relevant-repositories-MBSGDClassifier
Separating the MBSGDClassifier because of the time and hardware consumption to support more practical use of cuml. 

https://docs.rapids.ai/api/cuml/stable/api/generated/cuml.linear_model.mbsgdclassifier/#cuml.linear_model.MBSGDClassifier

As it says:
"The MBSGD Classifier implementation is experimental and and it uses a different algorithm than sklearn’s SGDClassifier."

Therefore it should be separated for now and run it with the experimental label. It is time consuming but nonless interesting and a good to know method. 
The same file structure should be sufficient for backend purposes but for deploying an GUI environment it is not practically available becuase of the high level of consumption and the need to restart the kernels more often. The simple limitations of the consumers' GPUs. 

Using the same codes because they are reusabale and the same Ubuntu 22.04 with the relevant virtualenv. 

Installation guide:

https://github.com/bigyobogyo-git/RAPIDS-cuML/blob/master/Installation%20Guide

All the codes should be available for donwload and free to modify of course as it serves nothing but educational and testing purposes. 

The data I used can be downloaded from here:


https://drive.google.com/file/d/1lozVDu93DYuUPyuDZIPYcxsiPzVCI4n3/view?pli=1

Have fun! 
