from tkinter import *

# Create a window
root = Tk()
root.title("Blake's a PP head")

label1 = Label(root, text="My GUI APP!",
wraplength=100, justify="center", fg="Red", bg="Gray")
label1.pack()

label2 = Label(root, text="Whatever you want but make it a longer sentence!", wraplength=100, justify="left", fg="black", bg="yellow")
label2.pack()

# Run the main window loop
root.mainloop ()
