Raspberry Pi Framebuffer Copy
=============================
This program used for copy primary framebuffer to secondary framebuffer (eg. FBTFT). It require lastest raspberry pi firmware (> 2013-07-11) to working properly.

Build
-----

    $ mkdir build
    
    $ cd build
    
    $ cmake ..
    
    $ make 

Directly use the Binary
=======================

Copy to the fat32 portion ie /boot/ directory and then copy it to usr/local/bin via ssh
