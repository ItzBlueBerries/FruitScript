# Script

This is the script section of FruitScript, where some things are I guess more code related? lol.

## `class script():`

### Mush

`script.mush(input1, input2)`  
Mushes anything you put inside together, including numbers(Will automatically add them together.)

``Example``

```py
import ext.FruitScript
from ext.FruitScript import script

script = ext.FruitScript.script

script.mush(1, 1) # You could also do script.mush('hello', ' world')
```

### Execute

`script.execute(input)`  
Executes anything you put inside, use with caution as this will **ACTUALLY** execute anything you put inside, so be very careful with what you execute with this function.

``Example``

```py
import ext.FruitScript
from ext.FruitScript import script

script = ext.FruitScript.script

script.execute('print(\'Hello Fruity World!\')')
```
