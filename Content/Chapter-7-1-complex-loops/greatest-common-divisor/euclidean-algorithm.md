### Алгоритъм на Евклид

В следващата задача ще използваме един от първите публикувани алгоритми за намиране на НОД - **алгоритъм на Евклид**:

**Докато** не достигнем остатък 0:

* Делим по-голямото число на по-малкото.
* Вземаме остатъка от делението.

**Псевдо-код** за алгоритъма на Евклид:

```csharp
while b ≠ 0
  var oldB = b;
  b = a % b;
  a = oldB;
print а;
```