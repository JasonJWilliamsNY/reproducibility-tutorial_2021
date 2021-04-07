# reproducibility-tutorial_2021    1  pwd

## Clone Github repo
git clone https://github.com/JasonJWilliamsNY/-reproducibility-tutorial-foss-2021.git

## Install the latest version of miniconda
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda

### use symbolic links to add conda packages to the bin
ln -s /opt/conda/pkgs/*/bin/* /bin
ln -s /opt/conda/pkgs/*/lib/* /usr/lib


   26  clear
   27  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   28  clear
   29  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   30  clear
   31  /opt/conda/bin/pip install bash_kernel
   32  /opt/conda/bin/pip install ipykernel
   33  clear
   34  /opt/conda/bin/python3 -m bash_kerne
   35  /opt/conda/bin/conda search fastx
   36  /opt/conda/bin/conda search -c bioconda fastx
   37  clear
   38  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   39  clear
   40  ls reproducibility-tutorial/
   41  sudo apt-get update
   42  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   43  clear
   44  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   45  add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   46   $(lsb_release -cs) \
   47   stable"
   48  clear
   49  sudo apt-get update
   50  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   51  clear
   52  docker run hello-world
   53  clear
   54  ls
   55  cp reproducibility-tutorial/my_test_notebook.ipynb .
   56  rm -rf reproducibility-tutorial/
   57  mv \-reproducibility-tutorial-foss-2021 reproducibility-tutorial
   58  git clone https://github.com/JasonJWilliamsNY/reproducibility-tutorial-foss-2021.git
   59  mv reproducibility-tutorial-foss-2021/ reproducibility-tutorial
   60  mv my_test_notebook.ipynb reproducibility-tutorial/
   61  clear
   62  cd /scratch/reproducibility-tutorial/
   63  ls
   64  history
   65  clear
   66  history >>README.md 
   67  nano README.md 
   68  git status
   69  git add my_test_notebook.ipynb 
   70  git status
   71  clear
   72  git commit -m "set up Atmosphere for tutorial"
   73  git push
   74  clear
   75  cd ..
   76  l
   77  ls
   78  ls -l reproducibility-tutorial/
   79  ls -l .
   80  chown -R williams /scratch/reproducibility-tutorial/
   81  ls -l .
   82  clear
   83  ls
   84  cd reproducibility-tutorial/
   85  ks
   86  ls
   87  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   88  cd /scratch
   89  df -h
   90  clear
   91  git clone https://github.com/JasonJWilliamsNY/reproducibility-tutorial_2021.git
   92  ls
   93  mv reproducibility-tutorial_2021/ reproducibility-tutorial
   94  l
   95  ls
   96  clear
   97  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   98  clear
   99  ls
  100  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
  101  rm -rf /opt/conda
  102  clear
  103  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
  104  clear
  105  python
  106  ln -s /opt/conda/pkgs/*/bin/* /bin
  107  clear
  108  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
  109  clear
  110  python
  111  python3
  112  /opt/conda/pkgs/python-3.8.5-h7579374_1/bin/python3
  113  clear
  114  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
  115  clear
  116  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
  117  clear
  118  /opt/conda/bin/pip install bash_kernel
  119  /opt/conda/bin/pip install ipykernel
  120  /opt/conda/bin/python3 -m bash_kernel.install
  121  clear
  122  /opt/conda/bin/conda search fastx
  123  clear
  124  /opt/conda/bin/conda search -c bioconda fastx
  125  clear
  126  clear
  127  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  128  clear
  129  ls
  130  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
  131  clear
  132  docker --version
  133  sudo apt-get update
  134  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
  135  clear
  136  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  137  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
  138  sudo apt-get update
  139  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
  140  clear
  141  docker run hello-world
  142  cd /scratch/reproducibility-tutorial/
  143  clear
  144  ls
  145  history
  146  clear
  147  history >>README.md 
