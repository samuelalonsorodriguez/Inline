# Inline
Alice Inline

# Location
"base_alice"\Core\Inline.hpp

# Description
Avoid generating call/ret instructions by inlining the function code

# Macros (1)
1º:

AliceInline

Usage¬
```
#include <Core\Inline.hpp>

AliceInline void foo(){}

AliceInline constexpr void foo2(){}

template<class T> AliceInline void foo3(){}

int main()
{
  foo();
  foo2();
  foo3<void>();
}
```
