#Commands-Used
conda create -n DVC-ML python=3.7 -y

conda activate DVC-ML

git init

git remote add origin https://github.com/Prakhar2295/DVC-ML-demo.git

git checkout -b main

touch requirements.txt

pip install requirements.txt
