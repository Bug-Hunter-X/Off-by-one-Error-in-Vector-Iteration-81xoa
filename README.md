# Off-by-one Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error when iterating over a `std::vector` in C++.  The error arises from incorrectly using `<=` instead of `<` in the loop condition, leading to an access beyond the valid range of the vector and undefined behavior. 

The `bug.cpp` file contains the erroneous code.  The `bugSolution.cpp` file provides the corrected version.