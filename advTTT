from tkinter import *
from tkinter import messagebox
window=Tk()

#Creating Window
window.title("TIC-TAC-TOE")
window.resizable(width=False, height=False)
window.geometry("1055x750+0+0")
window.configure(background= 'light salmon')

tops=Frame(window, bg='light salmon', pady= 2, width=1350, height=100, relief= RIDGE)
tops.grid(row=0, column=0)

lb1 = Label(tops, text='Advance Tic-Tac-Toe!!', bd=21, bg='light salmon', fg='dark green', justify=CENTER, font=('Times','50','bold'))
lb1.grid(row=0,column=0)

main=Frame(window, bg='light salmon', pady= 2, bd=10, width=1200, height=600, relief= RIDGE)
main.grid(row=1, column=0)

left = Frame(main, bd=10, bg='light salmon', pady= 2, padx=10, width=750, height=500, relief= RIDGE)
left.pack(side=LEFT)

right = Frame(main, bd=10, bg='light salmon', pady= 2, padx=10, width=560, height=500, relief= RIDGE)
right.pack(side=RIGHT)

right1 = Frame(right, bd=10, bg='light salmon', pady= 2, padx=10, width=560, height=200, relief= RIDGE)
right1.grid(row=0, column=0)

right2 = Frame(right, bd=10, bg='light salmon', pady= 2, padx=10, width=560, height=200, relief= RIDGE)
right2.grid(row=1, column=0)

playerX=IntVar()
playerO=IntVar()
playerX.set(0)
playerO.set(0)

buttons=StringVar()

#logic of game
turn=True
def click(buttons):
    global turn
    if buttons["text"]==" " and turn==True:
        buttons["text"]='X'
        turn=False
        scorekeeper()
    elif buttons["text"]==" " and turn==False:
        buttons["text"]='O'
        turn=True
        scorekeeper()

def scorekeeper():
    if btn1['text']=='X' and btn2['text']=='X' and btn3['text']=='X':
        btn1.configure(background="gold")
        btn2.configure(background="gold")
        btn3.configure(background="gold")
        n=float(playerX.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player X won!")

    if btn4['text']=='X' and btn5['text']=='X' and btn6['text']=='X':
        btn4.configure(background="deep pink")
        btn5.configure(background="deep pink")
        btn6.configure(background="deep pink")
        n=float(playerX.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player X won!")

    if btn7['text']=='X' and btn8['text']=='X' and btn9['text']=='X':
        btn7.configure(background="gold")
        btn8.configure(background="gold")
        btn9.configure(background="gold")
        n=float(playerX.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player X won!")

    if btn1['text']=='X' and btn4['text']=='X' and btn7['text']=='X':
        btn1.configure(background="deep pink")
        btn4.configure(background="deep pink")
        btn7.configure(background="deep pink")
        n=float(playerX.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player X won!")

    if btn2['text']=='X' and btn5['text']=='X' and btn8['text']=='X':
        btn2.configure(background="gold")
        btn5.configure(background="gold")
        btn8.configure(background="gold")
        n=float(playerX.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player X won!")

    if btn3['text']=='X' and btn6['text']=='X' and btn9['text']=='X':
        btn3.configure(background="deep pink")
        btn6.configure(background="deep pink")
        btn9.configure(background="deep pink")
        n=float(playerX.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player X won!")

    if btn7['text']=='X' and btn5['text']=='X' and btn3['text']=='X':
        btn7.configure(background="gold")
        btn5.configure(background="gold")
        btn3.configure(background="gold")
        n=float(playerX.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player X won!")

    if btn9['text']=='X' and btn5['text']=='X' and btn1['text']=='X':
        btn9.configure(background="deep pink")
        btn5.configure(background="deep pink")
        btn1.configure(background="deep pink")
        n=float(playerX.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player X won!")
        
#maintaining score for player O
    if btn1['text']=='O' and btn2['text']=='O' and btn3['text']=='O':
        btn1.configure(background="tomato")
        btn2.configure(background="tomato")
        btn3.configure(background="tomato")
        n=float(playerO.get())
        score=n+1
        playerO.set(score)
        messagebox.showinfo("Congrats!", "Player O won!")

    if btn4['text']=='O' and btn5['text']=='O' and btn6['text']=='O':
        btn4.configure(background="SeaGreen1")
        btn5.configure(background="SeaGreen1")
        btn6.configure(background="SeaGreen1")
        n=float(playerO.get())
        score=n+1
        playerO.set(score)
        messagebox.showinfo("Congrats!", "Player O won!")

    if btn7['text']=='O' and btn8['text']=='O' and btn9['text']=='O':
        btn7.configure(background="tomato")
        btn8.configure(background="tomato")
        btn9.configure(background="tomato")
        n=float(playerO.get())
        score=n+1
        playerO.set(score)
        messagebox.showinfo("Congrats!", "Player O won!")

    if btn1['text']=='O' and btn4['text']=='O' and btn7['text']=='O':
        btn1.configure(background="SeaGreen1")
        btn4.configure(background="SeaGreen1")
        btn7.configure(background="SeaGreen1")
        n=float(playerO.get())
        score=n+1
        playerO.set(score)
        messagebox.showinfo("Congrats!", "Player O won!")

    if btn2['text']=='O' and btn5['text']=='O' and btn8['text']=='O':
        btn2.configure(background="tomato")
        btn5.configure(background="tomato")
        btn8.configure(background="tomato")
        n=float(playerO.get())
        score=n+1
        playerO.set(score)
        messagebox.showinfo("Congrats!", "Player O won!")

    if btn3['text']=='O' and btn6['text']=='O' and btn9['text']=='O':
        btn3.configure(background="SeaGreen1")
        btn6.configure(background="SeaGreen1")
        btn9.configure(background="SeaGreen1")
        n=float(playerO.get())
        score=n+1
        playerX.set(score)
        messagebox.showinfo("Congrats!", "Player O won!")

    if btn7['text']=='O' and btn5['text']=='O' and btn3['text']=='O':
        btn7.configure(background="tomato")
        btn5.configure(background="tomato")
        btn3.configure(background="tomato")
        n=float(playerO.get())
        score=n+1
        playerO.set(score)
        messagebox.showinfo("Congrats!", "Player O won!")

    if btn9['text']=='O' and btn5['text']=='O' and btn1['text']=='O':
        btn9.configure(background="SeaGreen1")
        btn5.configure(background="SeaGreen1")
        btn1.configure(background="SeaGreen1")
        n=float(playerO.get())
        score=n+1
        playerO.set(score)
        messagebox.showinfo("Congrats!", "Player O won!")
        
def new():
    reset()
    playerX.set(0)
    playerO.set(0)

def reset():
    btn1['text']=" "
    btn2['text']=" "
    btn3['text']=" "
    btn4['text']=" "
    btn5['text']=" "
    btn6['text']=" "
    btn7['text']=" "
    btn8['text']=" "
    btn9['text']=" "

    btn1.configure(background="peach puff")
    btn2.configure(background="peach puff")
    btn3.configure(background="peach puff")
    btn4.configure(background="peach puff")
    btn5.configure(background="peach puff")
    btn6.configure(background="peach puff")
    btn7.configure(background="peach puff")
    btn8.configure(background="peach puff")
    btn9.configure(background="peach puff")
    
lbplayerX = Label(right1, text="Player X : ", bg='light salmon', fg="Dark Green", pady= 2, padx=2, font=('Times','39','bold'))
lbplayerX.grid(row=0, column=0, sticky=W)
txtplayerX = Entry(right1, font=('Times','25','bold'), bd=2, fg="dark green", width=15, textvariable= playerX, justify=LEFT).grid(row=0, column=1)

lbplayerO = Label(right1, text="Player O : " , bg='light salmon', fg="Dark Green", pady= 2, padx=2, font=('Times','39','bold'))
lbplayerO.grid(row=1, column=0, sticky=W)
txtplayerO = Entry(right1, font=('Times','25','bold'), bd=2, fg="dark green", width=15, textvariable= playerO, justify=LEFT).grid(row=1, column=1)


#Adding buttons(3X3 grid)
btn1 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn1)) 
btn1.grid(row=1,column=1, sticky = S+N+E+W)
btn2 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn2))
btn2.grid(row=1,column=2, sticky = S+N+E+W)
btn3 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn3))
btn3.grid(row=1,column=3, sticky = S+N+E+W)
btn4 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn4)) 
btn4.grid(row=2,column=1, sticky = S+N+E+W)
btn5 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn5))
btn5.grid(row=2,column=2, sticky = S+N+E+W)
btn6 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn6))
btn6.grid(row=2,column=3, sticky = S+N+E+W)
btn7 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn7)) 
btn7.grid(row=3,column=1, sticky = S+N+E+W)
btn8 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn8))
btn8.grid(row=3,column=2, sticky = S+N+E+W)
btn9 = Button(left, text= " ", bg="peach puff", fg="dark green", width=8, height=3, font=('Times','20', 'bold'), command=lambda:click(btn9))
btn9.grid(row=3,column=3, sticky = S+N+E+W)

#Adding Reset and New Game Buttons
btnreset = Button(right2, text= "RESET GAME", bg="peach puff", fg="dark green", width=31, height=1, font=('Times','20', 'bold'), command=reset) 
btnreset.grid(row=1,column=1)
btnnew = Button(right2, text= "NEW GAME", bg="peach puff", fg="dark green", width=31, height=1, font=('Times','20', 'bold'), command=new)
btnnew.grid(row=2,column=1)

window.mainloop()
