# Cython-numpy-awesome-template

It is a template of python package that is considered to be very friendly in terms of using.

So the main point it to satisfy the next requirements:
1. Package can be easily installed by `pip install package`. If user doesn't have cython or doesn't have C++ compiler (what is usually a case on Windows), then cython will be not used, but the whole package falling back to python implementations
2. Multithreading in cython
3. Provide nice typing and doc-strings
4. Write generic code, decrease code duplication
