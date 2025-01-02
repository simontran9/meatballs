# Generic implementation

Generics were implemented using C's preprocessor macros.

This was chosen because using `void *` pointers, another technique to implement generics in C, can incur runtime overhead. 
Also, preprocessor macros provides slightly better type safety compared to using `void *`, considering the macros will
generate type-specific implementations based off a general "template" data structure code.  

Sources:
- https://github.com/attractivechaos/klib?tab=readme-ov-file
- https://github.com/openssl/openssl/blob/a28d06f3e9cbc5594c7985c99a0c6bac5261ae67/doc/man3/DEFINE_STACK_OF.pod
- https://iafisher.com/blog/2020/06/type-safe-generics-in-c#:~:text=Safe%20generic%20stack%20using%20macros
