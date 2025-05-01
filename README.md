# C Standard Data Structure Headers

A personal collection of reusable, header-only implementations of standard data structures in C.

This repository is designed for fast and clean development in C, especially for competitive programming or algorithm study.  
It aims to reduce the overhead of rewriting common data structures by providing ready-to-use `.h` files.

## Features

- Header-only implementations in pure C99
- No external dependencies
- Simple APIs, easily modifiable
- Focused on readability and reusability

## Available Headers

| File           | Description                    |
|----------------|--------------------------------|
| `mydeque.h`    | Double-ended queue (array-based) |
| `mytree.h`     | Segment tree (pointer-based)   |
| `mygraph.h`    | Graph traversal (DFS/BFS)      |
| `mystack.h`    | Stack (array-based)            |
| `myqueue.h`    | Queue (array-based)            |
| `mymath.h`     | Math utilities (GCD, modpow)   |

*(More will be added as needed)*

## Example Usage

```c
#include "mydeque.h"

int main() {
    Deque dq;
    initDeque(&dq);
    pushBack(&dq, 1);
    pushFront(&dq, 2);
    printf("%d\n", popFront(&dq)); // 2
    return 0;
}
