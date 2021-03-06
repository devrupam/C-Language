Exercise 5
---------- 

The **filelib.h** interface exports several functions that make it easy to work with filenames. Two functions that are particularly useful are **getRoot** and **getExtension**, which divide a function into its *root*, which is the identifying part of the filename, and the *extension* which indicates the type. For example, given the filename **Middlemarch.txt** used in the preceding example, the root is **Middlemarch** and the extension is **.txt** (note that **filelib.h** defines the extension to include the dot). Write the code necessary to implement these functions. To find out how to handle special cases, such as filenames that don't include a dot, consult the **filelib.h** interface in Appendix A.

---

Note: This program requires linking with the Stanford C++ Libraries:

http://www.stanford.edu/class/cs106b/materials/cppdoc/