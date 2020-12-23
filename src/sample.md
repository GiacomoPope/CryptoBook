# Sample of features

## Code highlighing

```py
def testing_code_highlighting(arg1: str, arg2: int, arg3=True) -> str:
	if arg3:
		return f'Hello {arg1}'
	else:
		return 'Hello world\n'*arg2
```

## MathJax

Inline maths can be made using: \\( x^n + y^n = k \\)

```
Inline maths can be made using: \\( x^n + y^n = k \\)
```

Display maths is currently rendered using the dollar sign:

$$ \mathcal{C}: y^2 = x^7 + x $$

```
$$ \mathcal{C}: y^2 = x^7 + x $$
```

This **should** also work for 

```
\\[ \mathcal{C}: y^2 = x^7 + x \\]
```

but the preprocessor we use to make the warning labels below breaks this. I have made an issue with the preprocessor and hopefully this is fixed soon.


## Notes, tips and warnings

{:.note}
This is a note about functionality

```
{:.note}
This is a note about functionality
```

{:.tip}
This is a tip about functionality

```
{:.tip}
This is a tip about functionality
```

{:.warning}
This is a warning about functionality

```
{:.warning}
This is a warning about functionality
```

{:.caution}
This is a caution about functionality

```
{:.caution}
This is a caution about functionality
```

