# Scope_of_Variable
Scope of variable and hoisting in Javascript
Hello Rajni here. In my first project, Scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. The two types of scope are local and global.
HOISTING : JavaScript in which variable and function declarations are moved to the top of their scope. Since only the actual declaration is hoisted, not the initialization
Variables can be initialized in 3 ways : var, let, const. These variables have different scopes in code.
Type Conversions are generally of two types: Implicit or Explicit.
Implicit conversion means that the compiler is going behind your back to convert something you give it without you explicitly saying it. This is also known as Type Coercion.
Explicit coercion happens when you explicitly tell the compiler what type to convert to. This is popularly known as type casting.
If conversion is not possible, it is converted to NaN, which you need to be very vary as it is very inconsistent in it's behavior
If objects have a valueOf function, it is called for conversion to number, otherwise NaN is returned.
Arrays have a valueOf function defined by default, but as you can guess it works only when there is a single element in the array.
One special detail to remember:
	null is converted to 0
	false is converted to 0
	undefined is converted to NaN
The object implements toString() function, that is returned on converting to string. Otherwise, you get the infamous [object Object].
ES Spec defines falsy values as:
	null
	undefined
	false
	0, +0, -0
	""
NaN
Falsy values are coerced into false when applying a boolean type conversion
