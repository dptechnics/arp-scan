# arp-scan

This ARP scanner is forked from the royhills/arp-scan repository. 
The fork removed cross-platform support to simplify the build. The
GNU autotools are replaced by CMake. 

Compiling
---------

This arp-scan fork uses CMake as the build system. To build the 
tool just execute the following commands:

 - Run ```git clone https://github.com/dptechnics/arp-scan.git``` to obtain the project source code
 - Run ```cmake CMakeLists.txt``` to generate the Makefile
 - Run ```sudo make install``` to install the program onto your computer

 
