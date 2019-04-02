# Formatters

This is a brief guide to using Python formatters. I don't touch the old formatters e.g. `'%s' % 'string'`  __anymore so this just refers to the new formatters. 

#### Basic formatters

Fairly simple...

```python
'{}'.format('string') # would produce: 'string' (print as string)
'{}'.format(1) # would produce: 1 (print as integer)
```

#### Format as percentage

This is a pretty typical reporting task - presenting your data as a percentage, fairly easy to deal with...

```python
# lets make a decimal output
example_decimal = 0.13515112
print(example_decimal) # gives us: 0.13515112

# Lets turn it to percentage
'{:.2%}'.format(example_decimal) # which returns: '13.52%'

# no decimals?
'{:.0%}'.format(example_decimal) # returns: '14%'

# note we rounded it up, this formatter uses the closest integer
example_decimal = 0.1341651
'{:.0%}'.format(example_decimal) # returns: '13%'
```

So the only parts we need to understand is the `'{:.p%}'`section which just sets the precision of the percentage, with some \`p\` in place the function will take the decimal, multiply it by 100 and trim the decimals \(and round to the nearest integer\) to the precision level. 

#### Further reading:

* [https://pyformat.info/](https://pyformat.info/)

