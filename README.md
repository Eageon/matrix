matrix
======

Matrix multiplication by using multi-thread

#Source File List#
    ##CC source file##
        * matrix.cc 
        * prog1.cc 
        * prog2.cc

    ##Header##
        * common.h
        * matrix.h
        * prog2.h
        
    ##Makefile##
    
#How to compile#
    With a Makefile, which is also written by Jun Yu, attached to the project, 
    you can easily compile this project by execute `make`
    
#Sample Running#
    ##What machine were the programs running at##
        cs1.utdallas.edu
        
    ##Compiler##
        * g++
        * To see more details, please check Makefile
        
    ##Output##
        ###Why the prog1 has no output?###
            To compute the multiplication of two 10000 x 10000 matrices by single thread strategy, 
            I had run the prog1 on cs1.utdallas.edu for one full day and on my own computer for 
            more than two days, without seeing any indication that it will end in appreciable hours
            
        ###The output of prog2###
            `run.bash` include: 
                $ date
                $ ./prog2
                $ date
            
            Then we can see the output below:
                $ Mon Oct 21 15:15:40 CDT 2013
                $ Multi-Thread matrix multiplication complete!
                $ Mon Oct 21 16:30:23 CDT 2013
