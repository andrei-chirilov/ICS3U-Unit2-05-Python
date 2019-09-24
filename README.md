#!/usr/bin/env python 3

# Created by: Andrei Chirilov
# This program shows how local and global variables work

# global variable
variable_X = 25

def local_variable():
    # This shows what happens with local variables
    
    variable_X = 10
    variable_Y = 30
    variable_Z = variable_X + variable_Y
    print("Local variable_X, variable_Y, variable_Z: {0} + {1} + {2}".
    format(variable_X, variable_Y, variable_Z))
    
