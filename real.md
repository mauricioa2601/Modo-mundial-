# Modo-mundial-
proyecto 
from tkinter import *
import time
from tkinter import font
def mostrarlista():
    print("")
def ordenar():
    print("")
def crud():
    print("")
def cargardatos():
    print("")
def grabardatos():
    print("hola")
ventana = Tk()
ventana.title("Estrellas del mundial")
ventana.geometry("800x800")
ventana.config(background='white')
etiqueta1= Label(ventana,text="Escoja sus opciones ",font="Helvetica",).place(x=25,y=50)
boton_showlist= Button(ventana,text="Mostrar lista",command=mostrarlista,font="Helvetica").place(x=25,y=100)
boton_order=Button(ventana,text="Ordenar",command= ordenar, font="Helvetiva").place(x=25,y=150)
boton_crud= Button(ventana,text="Crud",command=crud,font="Helvetica").place(x=25,y=200)
boton_cargardatos=Button(ventana,text="Cargar datos",command= cargardatos, font="Helvetiva").place(x=25,y=250)
boton_grabardatos= Button(ventana,text="Grabar datos",command=grabardatos,font="Helvetica").place(x=25,y=300)
boton_salir=Button(ventana,text="Salir",command= ventana.quit , font="Helvetiva").place(x=25,y=350)
ventana.mainloop()
