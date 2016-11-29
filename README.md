# Q
core java I

##page 478 : 
why these "Layout" need int parameter? what that for?
A: maybe it's the relative position between two components 
PS: the "calculator" program is robust!

##page 555
ensure the parent component in this way:
'''
if(parent instanceof Frame)
  owner = (Frame) parent;
else
  owner = (Frame) SwingUtilities.getAncestorOfClass(Frame.class,parent)
'''
