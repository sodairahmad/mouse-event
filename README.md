# mouse-event
use mouse event in python 

from tkinter import *
def dosomthing(af):
    print("you pressed something   : at axis  : "+str(af.x)+" at y axis is : " +str(af.y))


window=Tk()
window.bind("<Motion>",dosomthing)

window.mainloop()
END()..................................................

