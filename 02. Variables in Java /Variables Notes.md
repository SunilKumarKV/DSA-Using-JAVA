# Types of Variables
1. **Local Variables:**
   - **Scope:** Declared within a method, constructor, or block, and can only be used within that method, constructor, or block.
   - **Initialization:** Must be initialized before use.
   - **Example:**
   ```
    public void myMethod() {
    int localVar = 5; // Local variable
    System.out.println(localVar);
   }
   ```

3. **Instance Variables:**
   - **Scope:** Declared inside a class but outside any method, constructor, or block. Each instance of the class has its own copy of the instance variable.
   - **Initialization:** Automatically initialized to default values (e.g., 0 for integers, null for objects) if not explicitly initialized.
   - **Example:**
    ```
    public class MyClass {
    int instanceVar; // Instance variable
    
    public void printVar() {
        System.out.println(instanceVar);
    }
    }
    ```


4. **Class Variables (Static Variables):**
   - **Scope:** Declared with the static keyword inside a class but outside any method. There is only one copy of a static variable shared among all instances of the class.
   - **Initialization:** Like instance variables, static variables are automatically initialized to default values if not explicitly initialized.
   - **Example:**

   ```
   public class MyClass {
    static int staticVar = 10; // Static variable
    
    public void printVar() {
        System.out.println(staticVar);
    }
   }
   ```
