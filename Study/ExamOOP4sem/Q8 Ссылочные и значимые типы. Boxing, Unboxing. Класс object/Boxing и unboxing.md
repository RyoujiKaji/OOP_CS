
# **Упаковка (boxing)**
— это процесс, который преобразует переменную [[Значимые типы|типа значения]] в переменную [[Ссылочные типы|типа ссылки]]

# **Распаковка (unboxing)**
— это процесс извлекает исходный тип значения из объекта и преобразует его обратно.

Упаковка и распаковка обеспечивают единое представление системы типов, в которой значение любого типа может рассматриваться как объект

```cs
// Boxing and Unboxing in C#

using System;

public class Geeks 
{
	public static void Main(string[] args)
	{
		// Value type variable
		int n = 357; 

		// Boxing
		object box = n; 

		Console.WriteLine("Boxed value: " + box);

		// Unboxing
		int unbox = (int)box; 
		Console.WriteLine("Unboxed value: " + unbox);
	}
}

//Boxed value: 357 
//Unboxed value: 357
```

