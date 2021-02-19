# Tensorflow 2 and Keras install

## Create environment:

Here tf2 is an arbitrary name for our environment.

     conda create -n tf2 python=3.8

## Activate environment.

    activate tf2
## install tensorflow - GPU enabled

    pip install tensorflow-gpu

if there is no CUDA support:
    
    pip install tensorflow



![alt text](/img/tf_install1.png)

## install sympy (if not installed previously):

    pip install pip sympy
    
## install Keras
    pip install keras

![alt text](/img/tf_install2.png)

## if you don't want to see deprecation warning:

There is a deprecation warning as below:

     C:\ProgramData\Anaconda3\envs\tf2\lib\site-packages\sympy\deprecated\class_registry.py:33: SymPyDeprecationWarning: 

     C, including its class ClassRegistry, has been deprecated since SymPy
     1.0. It will be last supported in SymPy version 1.0. Use direct
     imports from the defining module instead. See
     https://github.com/sympy/sympy/issues/9371 for more info.

       SymPyDeprecationWarning(
  
  
 Open class_registry.py where located. You see the location in the warning
 
 In my computer it is located at: C:\ProgramData\Anaconda3\envs\tf2\lib\site-packages\sympy\deprecated\class_registry.py
 
 
 
  
