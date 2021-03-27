Task 1a DCA)
Unable to setting it up and running. Here are the steps which I tried to get it up running:
* Clone the Repo
*	Download the data
*	Download the Python 3.6 version and set the precedence of it above in the system path.
*	Pytorch 0.3 was not available for Windows (Didn’t find binaries/whl download files to install it)
*	Downloaded and install WSL(Windows Subsystem for Linux) and using Ubuntu 18.04LTS as OS.
*	Installing Pytorch 0.3 successfully with help of whl/binaries
*	Faced problems with CUDA toolkit version 8. Fixed some of the problems with help from stackoverflow. One of them was: 
1. Can’t locate InstallUtils.pm in @INC (you may need to install the InstallUtils module) 
  Steps to resolve:
    1. unpack .run file ./cuda*.run --tar mxvf
    2. copy InstallUtils.pm to /usr/lib/x86_64-linux-gnu/perl-base
    3. export $PERL5LIB
*	Ultimately stuck after the CUDA toolkit reported the system drivers problem. 
