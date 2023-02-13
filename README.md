# CERN-miniprosjekt

This code requires to have downloaded files from https://zenodo.org/record/573298#.Y-pAJnaZNtZ

Also a enviroment with python 3.9.16 with necessary libraries installed

Install cuda, tensorflow-gpu using anaconda

Change jupyter_notebook_config.py add these lines
-c.Session.gpu_id = 0
-c.Session.use_gpu = True

You cna find gpu_id using nvidia-smi command usually its equals 0

If cant find jupyter config file run following code in therminal (anaconda)
-jupyter notebook --generate-config
