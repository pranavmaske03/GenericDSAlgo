# C++ Data Structures & Algorithms Library (dsalgo.h)

🚀 A **single-header, templated** C++ library implementing essential data structures and algorithms. Perfect for learning, competitions, and embedded systems!

## Features

### Data Structures
- **Linear Structures**:
  - Singly/Doubly Linked Lists (`SinglyLL`, `DoublyLL`)
  - Stack (`Stack`) & Queue (`Queue`)
- **Circular Structures**:
  - Singly/Doubly Circular Linked Lists (`SinglyCL`, `DoublyCL`)
- **Trees**:
  - Binary Search Tree (`BST`) with traversals (Inorder/Preorder/Postorder)
 
### Algorithms
- **Array Operations** (`ArrayX`):
  - Sorting: BubbleSort, SelectionSort, InsertionSort **(NEW: Benchmarks coming soon!)**
  - Searching: Linear, Bidirectional, Binary Search
- **Utility Methods**:
  - `Minimum()`, `Maximum()`, `Summation()`
  - Frequency counting (`CountFrequency()`), Position-based search

**Key Advantages**  
✔ **Zero dependencies** (Beyond STL)  
✔ **Templated** for any data type (`int`, `string`, custom objects)  
✔ **Memory-safe** with destructors  
✔ **Competition-ready** (Minimal overhead)  

## Usage Examples

### Linked List
```cpp
#include "dsalgo.h"

int main() {
    SinglyLL<std::string> list;
    list.InsertFirst("Hello");
    list.InsertLast("World");
    list.Display();  // Output: |Hello|->|World|->NULL
}
