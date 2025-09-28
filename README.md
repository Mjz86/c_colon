# c\_colon


![Logo](https://github.com/Mjz86/c_colon/blob/main/icon/c_colon.png)


a new programming language frontend for c++ made by mjz86





currently this is still experimental, but i aim to make  the "C:" language in hopes of a fully bi-directional interop language for c++ with backwards compatibility.

i first wanted to make a rust to c++ transpiler but i think that i cannot cooperate with the rust trademark.

so i will make my own language. 



this respository currently has no source code forthe transpiler ,

but i will develop the standard c colon draft here and eventually when i make a conforming implementation, i will publish the code as open source 





the file extensions would be:

".mjc" for the souce files

".mjcpm" for the intermidite abstract syntax tree object files

".mjc.cpp" and or ".mjc.hpp" for the generated c++ code







this language aims to:

1. free the burnden of ABI compatibility from c++
2. introduce  borrow checker , contracts and more 

3\. compile to fully constexpr friendly c++20 code

4\. make most easily checkable undefined behavior a contract violation defined by violated behavior 

5\. make some changes to what is considered a violation.

6\. if possible have most or all the flexibility of c++

7\. make code that is not constexpr friendly unsafe.





what this language is not aiming for:

1. replacement of c++ ( because the generated code would need to binf through c++)
2. replace rust 
3. unconditionally pay for safety ( contract violations can be ignored)
4. support legacy code  











