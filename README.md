# Uninitialized Property Access in C#

This example demonstrates a common error in C#: accessing a property that hasn't been initialized.  This can lead to unexpected behavior, such as exceptions or incorrect calculations.

## Bug

The `MyMethod` in `bug.cs` attempts to use `MyProperty` before it's assigned a value. This will result in `MyProperty` having its default value (0 for integers) which may not be the expected behavior. 

## Solution

The `bugSolution.cs` file shows how to fix this by initializing `MyProperty` before using it.

This simple fix ensures that the property has a defined value, preventing unexpected outcomes. 