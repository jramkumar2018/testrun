# testrun
To create VM and configure Ansible and store the play book

BUILDING THE ENVIRONMENT
------------------------
Clone this repository:

  $ git clone https://github.com/jramkumar2018/testrun.git

Change to the application folder:

  $ cd Bptest
  
Start the Vagrant machine:

  $ vagrant up
  
  
  
ACCESSING THE HELLO WORLD PAGE
-------------------------

The Hello world page  can be accessed at http://localhost:18081

TESTING THE ENVIRONMENT
-----------------------

From Bptest directory, run the run-tests.sh script:

  $ ./run-tests.sh
  
The tests check for the following:

The Vagrant host is listening on port 18081

Docker is installed and running on Vagrant guest

Docker host is listening on port 18081
