#how to run a N-body simulation



- step 1: Install PKDGRAV on your computer.

 Make sure you have gsl installed at some location.
 You can download it from https://www.gnu.org/software/gsl/
 then, 
 cd your-gsl
 ./configure --prefix=/home/yourname/your-gsl
 make
 make check
 make install


 

mkdir build
cd build
CXX=$(which CC) CC=$(which cc) cmake -DGSL_ROOT_DIR=/home/yourname/your-gsl/install ..

CXX=$(which CC) CC=$(which cc) cmake -DGSL_ROOT_DIR=/Users/mgatti29/Desktop/PKDGRAV_tests/gsl-2.7.1/install ..
