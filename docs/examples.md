# Add Two Numbers Example

Here is an example to add 2 numbers:
```cpp
#include <iostream>

#include "add.hpp"

int main() {
    std::cout << "Add ints: " << add(2, 3) << std::endl;
    std::cout << "Add floats: " << add(2.5f, 3.1f) << std::endl;
    return 0;
}

```

The add function is templated, so it can work with any numeric type (int, float, double, etc.).