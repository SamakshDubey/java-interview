Classloader = Component of JVM which Functions to load the ByteCode in Main Memory. It does three functions:

1. Loading
2. Linking
3. Initialisation



**Loading**


| Types of ClassLoader |                                                                      |
| -------------------- | -------------------------------------------------------------------- |
| Bootstrap Loader     | Load runtime classes required by JVM = All classes required by Java  |
| Extension Loader     | Load runtime classes required by JVM = Providing runtime environment |
| Application Loader   | Loads classes which belong to our application                        |



**Linking** = It verifies, prepares and resolves.

1. Verification involves checking if the code is perfect bytecode or not.
2. Prepare will allocate memory for static variables
3. Linking involves writing the reference of a method in place of method call.



**Initialisation**

1. Initialise static variables
2. Execute static blocks
