The following line:
```bash
export PATH=your/new/bin:$PATH
```

will result in your/new/bin to be added to your PATH variable, however if you exit and reopen terminal, your PATH will be reset. 

The way to resolve this (in zshell) is to add the line 
```bash 
export PATH=your/new/bin:$PATH
``` 
at the end of the file 

```bash
~/.zshrc
```.

Other remarks: 
1)
```bash
echo $PATH
``` 
lets you check your current PATH variable 

2)
```bash 
export PATH=usr/...
``` 
This command should contain no spaces around the = sign.  
