# errors


# error 1

File "/usr/lib64/python2.7/lib-tk/Tkinter.py", line 1745, in __init__
    self.tk = _tkinter.create(screenName, baseName, className, interactive, wantobjects, useTk, sync, use)
_tkinter.TclError: no display name and no $DISPLAY environment variable

solution :  


  export DISPLAY=:0.0
