# Q
core java I

##page 478 : 
why these "Layout" need int parameter? what that for?   
A: maybe it's the relative position between two components    
PS: the "calculator" program is robust!

##page 555
ensure the parent component in this way:
```
if(parent instanceof Frame)
  owner = (Frame) parent;
else
  owner = (Frame) SwingUtilities.getAncestorOfClass(Frame.class,parent)
```

##page 564
PropertyChangeListener?   
```
event.getPropertyName() == JFileChooser.SELECTED_FILE_CHANGED_PROPERTY
```
##so many in chapter 12
```
***.this //*** is always the class itself?
```
