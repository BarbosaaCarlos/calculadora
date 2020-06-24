

from tkinter import*

janela = Tk()
janela.title("calculator")
e = Entry(janela, width=35, borderwidth=5)
e.grid(row=0, column=0, columnspan=3, padx=10, pady=10 )

def buttonFuction(number):
    current= e.get()
    e.delete(0,END)
    e.insert(0,str(current) + str(number))

def button_clear():
    e.delete(0,END)

def button_add():
  first_number = e.get()
  global f_numb
  global math
  math = "add"
  f_numb= int(first_number)
  e.delete(0,END)

def button_sub():
  first_number = e.get()
  global f_numb
  global math
  math = "sub"
  f_numb = int(first_number)
  e.delete(0, END)

def button_multiply():
  first_number = e.get()
  global f_numb
  global math
  math = "multiply"
  f_numb = int(first_number)
  e.delete(0, END)

def button_divide():
  first_number = e.get()
  global f_numb
  global math
  math = "divide"
  f_numb = int(first_number)
  e.delete(0, END)

def button_equal():
  second_button = e.get()
  e.delete(0,END)
  if math == "add":
   e.insert(0, f_numb + int(second_button))
  if math == "sub":
    e.insert(0, f_numb - int(second_button))
  if math == "multiply":
    e.insert(0, f_numb * int(second_button))
  if math == "divide":
    e.insert(0, f_numb / int(second_button))


B1 = Button(janela, text="0", padx=20, command=lambda: buttonFuction(0))
B2 = Button(janela, text="1", padx=20, command=lambda: buttonFuction(1))
B3 = Button(janela, text="2",  padx=20,command=lambda: buttonFuction(2))
B4 = Button(janela, text="3",  padx=20,command=lambda: buttonFuction(3))
B5 = Button(janela, text="4",  padx=20,command=lambda: buttonFuction(4))
B6 = Button(janela, text="5",  padx=20,command=lambda: buttonFuction(5))
B7 = Button(janela, text="6",  padx=20,command=lambda: buttonFuction(6))
B8 = Button(janela, text="7",  padx=20,command=lambda: buttonFuction(7))
B9 = Button(janela, text="8",  padx=20,command=lambda: buttonFuction(8))
B10 = Button(janela, text="9",  padx=20,command=lambda: buttonFuction(9))


B11 = Button(janela, text="+",  padx=20,command=button_add)
B12 = Button(janela, text="=",  padx=20,command=button_equal)
B13 = Button(janela, text=" ",  padx=21,command=button_clear)
B14 = Button(janela, text="-",  padx=21,command=button_sub)
B15 = Button(janela, text="*",  padx=21,command=button_multiply)
B16 = Button(janela, text="/",  padx=21,command=button_divide)


B1.grid(row=4, column=0)

B2.grid(row=1, column=0)
B3.grid(row=1, column=1)
B4.grid(row=1, column=2)

B5.grid(row=2, column=0)
B6.grid(row=2, column=1)
B7.grid(row=2, column=2)

B8.grid(row=3, column=0)
B9.grid(row=3, column=1)
B10.grid(row=3, column=2)

B11.grid(row=3, column=2)#+
B12.grid(row=4, column=1)#=
B13.grid(row=5, column=0)#clear
B14.grid(row=4, column=2)#-
B15.grid(row=5, column=2)#*
B16.grid(row=5, column=1)#/


janela.mainloop()
