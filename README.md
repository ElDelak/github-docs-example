# Writing good Documentation

## step 1 - using CodeBlocks.

Codeblocks in markdow make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not yo be confused with quotation (')
```
import java.util.Date;
import java.util.function.Supplier;

public class SupplierDemo {

	public static void main(String[] args) {
		Supplier<String> sup = () -> "4";
		Supplier<Date> supDate = () -> new Date();
		
		
		System.out.println(sup.get());
		System.out.println(supDate.get());

	}

}
```

- When you can you should attempt to apply syntax highlighting to your codeblocks
```java
import java.util.Date;
import java.util.function.Supplier;

public class SupplierDemo {

	public static void main(String[] args) {
		Supplier<String> sup = () -> "4";
		Supplier<Date> supDate = () -> new Date();
		
		
		System.out.println(sup.get());
		System.out.println(supDate.get());

	}

}
```
example of img
![aws_img](https://github.com/ElDelak/github-docs-example/assets/5153700/ae39035b-1450-4553-94ba-0b7319ea8a61)

