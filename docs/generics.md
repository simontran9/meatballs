# generics

A single `# define DEFINE_<adt><data structure>(type)`, where the user passes in their desired type. Although this pattern to create generics in C is ugly to read, I prefer it over using `void *` because it's type-safe and faster than the alternative solution. This pattern is seen in some BSD data structures (e.g. [OpenBSD's red-black tree](https://github.com/openbsd/src/blob/c1d6f13173b788e34852a303bda0c5a53861979e/sys/sys/tree.h)), and [OpenSSL](https://github.com/openssl/openssl/blob/a28d06f3e9cbc5594c7985c99a0c6bac5261ae67/doc/man3/DEFINE_STACK_OF.pod).

**Note**\
An alternative option might be to create [intrusive linked lists](https://www.data-structures-in-practice.com/intrusive-linked-lists/) or intrusive trees.
