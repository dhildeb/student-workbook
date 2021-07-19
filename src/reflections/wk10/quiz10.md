# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
namespace encapsulates code into a group to allow ease of accessing, protecting, and writing code.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
a class is a reference type and a struct is a value type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
static void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
it indicates the return type of the Start method
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
REVIEW
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
REVIEW
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, inherit, abstract
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
just that class or region
```