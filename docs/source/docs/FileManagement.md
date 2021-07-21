# File Management

This is the file management section of FruitScript, where your files can be well, managed? lol.

## `class fileM():`

### Create

`fileM.create(filename)`  
This will create a file in your directory with whatever name you give it, if you find a way to loop this use with caution as you could maybe break your computer or your project.

``Example``

```py
import ext.FruitScript
from ext.FruitScript import fileM

fileM = ext.FruitScript.fileM

fileM.create('data.fruitscript')
```

### Append

`fileM.append(fileName, toAppend)`  
This will append/upgrade the file that is provided with new content, use with caution as it will delete all file content for updating. (This is very similar to the write function, it just doesn't repeat it.)

``Example``

```py
import ext.FruitScript
from ext.FruitScript import fileM

fileM = ext.FruitScript.fileM

fileM.append('data.fruitscript', 'Fruity!')
```

### Write
`fileM.write(filename, data)`  
This will write something in the given file with the text you give it, but use with caution as it will repeat if you keep running the project. (If its a one time think, I recommend **removing** the function out of your code before using it again.)

``Example``

```py
import ext.FruitScript
from ext.FruitScript import fileM

fileM = ext.FruitScript.fileM

fileM.write('data.fruitscript', 'Fruity!')
```

### Delete

`fileM.delete(toDelete)`  
This will delete the given filename toDelete, as soon as you run your project the file should be deleted and gone, no getting it back.

``Example``

```py
import ext.FruitScript
from ext.FruitScript import fileM

fileM = ext.FruitScript.fileM

fileM.delete('data.fruitscript')
```

### ContentDelete

`fileM.contentDelete(file)`  
This will delete all content in a file, use with caution to not accidently delete content that is important..you can not get it back.

``Example``

```py
import ext.FruitScript
from ext.FruitScript import fileM

fileM = ext.FruitScript.fileM

fileM.contentDelete('data.fruitscript')
```

### Duplicate
`fileM.duplicate(filename, duplicateName)`  
This will duplicate the given file name, but you must also provide a name for the duplicated file. If you find a way to loop this duplicate function to where it makes a bunch of duplicated files, I recommend not as I can not imagine what that could do to your computer.

``Example``

```py
import ext.FruitScript
from ext.FruitScript import fileM

fileM = ext.FruitScript.fileM

fileM.duplicate('data.fruitscript', 'newdata.fruitscript')
```

### Rename
`fileM.rename(filename, newName)`  
This will rename the given file to the provided new name.

``Example``

```py
import ext.FruitScript
from ext.FruitScript import fileM

fileM = ext.FruitScript.fileM

fileM.rename('data.fruitscript', 'newdata.fruitscript')
```

### CompressDir
`fileM.compressDir(nameOfZip)`  
This will compress your entire project into a .zip file, there may be a .zip file inside after compressing but don't worry, its empty so you can just delete it.

``Example``

```py
import ext.FruitScript
from ext.FruitScript import fileM

fileM = ext.FruitScript.fileM

fileM.compressDir('FruitScript')
```
