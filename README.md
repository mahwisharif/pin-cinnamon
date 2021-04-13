**pin-cinnamon**

This repository contains template and place holders for cinnamon code to be intergated witin pin tool.

Copy ``MyDSLTool`` folder under

``path-to-your-pin-root-dir/source/tools``

Now your ``PinPATH`` in ``compileToPin.py`` will be ``your-pin-root-dir/source/tools/MyDSLTool``

compile using 

``$ cd your-pin-root-dir/source/tools/MyDSLTool``

``$ make obj-intel64/MyDSLTool.so``

run the tool using the following command

``$ your-pin-root-dir/pin -t obj-intel64/MyDSLTool.so -- <target_binary>``

