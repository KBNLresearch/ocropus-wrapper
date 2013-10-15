ocropus-wrapper
===============

Simple Python wrapper for [OCRopus](https://code.google.com/p/ocropus/) command line invocation.

Usage:

    ocropus-wrapper [operation] [path_to_input] [path_to_output]
    
Where: 
operation = one of the following:

    either    '-bin=sauvola'  for Sauvola binarization
    or        '-bin=nlbin'    for non-linear binarization
    or        '-dewarp'       for dewarping
    or        '-segmentation' for segmentation
    or        '-hocr'         for recognition and results in hOCR format
    or        '-all'          to subsequently apply all steps in a full process

