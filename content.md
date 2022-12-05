# Integrating OneDAL with ML.NET

It has become increasingly obvious that, along with the digitization of the world, comes the pervasiveness of Machine Learning (ML)/AI on all applications and services, the so-called "operationalization" of AI.  By some accounts [by the end of 2024, 75% of enterprises will shift from piloting to operationalizing AI](https://www.gartner.com/smarterwithgartner/gartner-top-10-trends-in-data-and-analytics-for-2020).  

This is indicative that the vast majority of existing applications and services (a sizeable fraction of which are written in .NET), as well as those in development will need to carry out some ML task,  and that more and more hardware resources will be used in this area.  In this environment, the combination of the ML.NET library and Intel's optimized libraries for AI present a powerful pair.   ML.NET presents a uniform API to a wide variety of ML libraries (as well as including a plethora of built-in algorithms itself), which enables developers that may not be very familiar with the details of the ML domain to have their applications include ML functionality nonetheless.  To this variety of "backend engines" ML.NET exposes, we now add now two: [Intel's OneDAL](https://github.com/oneapi-src/onedal) and [XGBoost](https://github.com/oneapi-src/onedal). 

## Intel OneDAL and other optimized libraries

As more and more computational resources are dedicated to ML/AI, Intel has increased its commitment to creating domain-specific libraries that provide this functionality while making best use of Intel's hardware products.  This work started long before the current ML trend, with MKL, the Math Kernel Library, which you can see integrated in many ML libraries in various high-level languages (including, by the way, ML.NET).  With time, this effort has increased, and now the suite of optimized libraries that Intel offers, as well as those libraries from other sources Intel contributes to (like XGBoost, Pytorch, Tensorflow, ONNXRuntime, to mention a few) is vast.

## Using our integration in ML.NET

### OneDAL
### XGBoost

## What comes next

We're actively looking to continue this work, broadening the surface of the Intel optmized libraries we expose to ML.NET or adding to the set of libraries currently exposed.  Since the possibilities are so vast, we're trying to carefully prioritize our work based on use cases, so as to start with issues people are experiencing right now and postpone technically-feasible-but-who-would-use-it applications.  If you have a suggestion, please feel free to reach us!
