##### working directory: 
cd /home/user/wrf

##### prepare environment
sudo apt-get install cmake
sudo apt-get install gfortran
sudo apt-get install m4
sudo apt-get install csh

##### get source code
git clone https://github.com/david-github-dev/wrf_install.git

##### install
source SOURCEME
./download_app.sh all
./build_app.sh all
