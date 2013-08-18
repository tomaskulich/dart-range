Usage:

[![Build Status](https://drone.io/github.com/ilyakharlamov/dart-range/status.png)](https://drone.io/github.com/ilyakharlamov/dart-range/latest)


```dart
import "package:range/range.dart";

main() {
  for (int i in range(3)) {
    print (i); //0,1,2
  }
  for (int i in range(1,5)) {
    print (i); //1,2,3,4
  }
  for (int i in range(0, 8, 2)) {
    print (i); //0,2,4,6
  }
  for (int i in range(0, 10, 3)) {
    print (i); //0,3,6,9
  }
}
```
