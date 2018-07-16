## LambdaToDelegate

Provides a way to wrap an unmanaged lambda with a delegate in C++/CLI.

Usage:
```
delegate String^ AddNewLine(String^ s);
AddNewLine^ del = CreateDelegate<AddNewLine>([&](String^ s) -> String^ { return s + "\n";});
```
