Bootstrap: docker
From: ubuntu:xenial

%labels
Author "Randall Cab White - rcwhite@stanford.edu"


#########
#%setup
#########

#Downlaod packages
%post
  apt-get -ym update
  apt-get -ym install wget curl git git-all subversion python python3 language-pack-en-base
  
%environment
  export IMAGE_NAME="git_and_subversion"
  export LC_ALL=C
%runscript
