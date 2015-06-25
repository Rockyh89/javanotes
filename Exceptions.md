#Exceptions
- A Method can throw an exception when something fails at runtime
- Exceptions are of type **Exception**
- **RuntimeException vs Checked Exception**

- Runtime Exception
	- Ignored by compiler
	- Does not have to be declared or wrapped in try/catch

- Compiler Checked Exception
	- A method throws and exception
	```Java
		throw new NoCaffeineException();
	```
	- Methods that might throw a checked exception must announce it with a throws Exception declaration
	```Java
		public void writeList() throws IOException, IndexOutOfBoundsException {
	```
	- If you're not prepared to handle the exception, 'duck' the exception.
		- Pass the exception to the method that called *you* by only declaring the exception