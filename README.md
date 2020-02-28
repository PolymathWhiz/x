# x
⛅️ *Tentative name: Sky*

Sky is a modern reinvention of C++.

## Syntax
```dart
import "@net/http"
import "organism.sky"

class Animal extends Organism {
  public:
    constructor(int weight) : super(weight * 2) {
      foo.bar = "baz"
    }

    fn goDbar() -> Bar {
      return foo.bar
    }

    fn doIt(obj: Object&) -> int {
      return obj.x * obj.y
    }

    fn notConst(obj: mut X&) -> void {
      obj.x *= 2
    }

  private:
    Foo foo
}

class MyArr<T> {
  public:
    constructor(int size) {
      data = new T[size]
      this->size = size
    }

    destructor {
      delete data
    }

  private:
    data: T*
    size: int
}

fn main(int argc, u8** argv) -> int {
  var dog = Animal(24)
  return dog.goDbar().baz
}
```
