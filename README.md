#DareDevil Kernel For Aquaris E4.5

BUILD INSTRUCTIONS?
===================

First open a terminal and clone the project:

	$ git clone https://github.com/Pablito2020/DareDevil-Kernel.git

After it, enter to the folder where the DareDevil is located:

	$ cd DareDevil-Kernel

Build the kernel/Zimage:

	$ ./makeMtk -t krillin n k

Build boot.img :

        $ ./pack_bootimage.sh

FEATURES
===================
.-Latest linux kernel source code (3.4.112)

.-Added CPU GOVERNORS

.-Added I/O

.-Added Security Patches

.-Added FastCharge

.-Added F2FS support (must be included in recovery too)

.-Deleted MTK Stuff

.-Added Selinux to Permissive

.-Much More!
