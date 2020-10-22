# test_cul
Test for the lane detection that convert the lane data

It could:  
(a) generate per-pixel labels from original annotation files.  
(b) generate list files for training.  

2. Clone and build
    ```Shell
    git clone https://github.com/XingangPan/seg_label_generate.git
    cd seg_label_generate
    
    # if you prefer makefile
    make
    
    # or, if you prefer cmake
    rm -rf build
    mkdir build && cd build
    cmake .. && make
