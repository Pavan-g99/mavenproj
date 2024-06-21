<html><body><h1 style="font-size:50px;color:blue;">WEZVA TECHNOLOGIES (ADAM) <br> <font style="color:red;"> www.wezva.com <br> <font style="color:green;"> +91-9739110917 </h1>
<h1> PLEASE LIKE & SUBSCRIBE TO OUR YOUTUBE CHANNEL - DevOpsLearnEasy
    https://www.youtube.com/c/DevOpsLearnEasy </h1> </body></html>
              


# TEST CI JOB ##
# mavenbuild
This Repo consists of 2 Maven projects:
 1. samplejar: Build a standard jar devlierable
 2. samplewar: Build a standar war delvierable
 

BUILDING SAMPLEJAR COMPONENT
$ cd samplejar

# build only the jar deliverable
$ mvn package

# build jar with codecoverage
$ mvn package -Pcodecoverage


BUILDING SAMPLEWAR COMPONENT
$ cd samplewar
$ mvn package

###############
