The following line:
```bash
export PATH=your/new/bin:$PATH
```

will result in your/new/bin to be added to your PATH variabel, however if you exit and reopen terminal, your PATH will be reset. 

The way to resolve this (in zshell) is to add the line export PATH=your/new/bin:$PATH at the end of the file ~/.zshrc.

Other remarks: 

echo $PATH lets you check your current PATH variable 

export PATH=usr/... this command should contain no spaces around the = sign.  
