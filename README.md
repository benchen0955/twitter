# twitter
##### conda 虛擬環境
conda –V  ==>檢查目前版本
conda update conda==>進行更新
conda env list ==>系統安裝幾個虛擬環境
conda create --name myenv python=3.5 ==>建立一個叫做myenv的虛擬環境，並且是安裝python 3.5的版
activate myenv==>啟動虛擬環境(source activate myenv ==>如果你是LINUX或macOS，那你所需輸入啟動的方式將會是)
conda list  ==>虛擬環境中已經先安裝了那些東西
conda install numpy ==>虛擬環境下安裝所需套件，例如numpy
deactivate ==>離開虛擬環境(source deactivate ==>如果你是LINUX或macOS，那你所需輸入啟動的方式將會是)
conda remove --name myenv numpy ==>刪除虛擬環境中某個package(例如在剛剛建立的虛擬環境myenv中的numpy)
conda env remove --name myenv  ==>如果是要刪除整個虛擬環境
#####

#####python虛擬環境virtualenv,pip(已經內建在python3.6裡)
pip install virtualenv
mkdir testdemo==>建立資料夾進入資料夾
virtualenv env001==>產生一個名為env001的環境
\Scripts\activate ==>啟用虛擬環境env001
==>可在虛擬環境安裝件
\Scripts\deactivate =>離開
#####

#####目前使用
conda create --name demo python=3.6 (environment location: C:\Users\Ben\Anaconda3\envs\demo)
