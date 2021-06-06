from tkinter import *
from tkinter.font import Font


room = Tk()
room.title('Keynote')
room.geometry("1100x700+120+15")
room.configure(bg = '#021819')

senha = StringVar()
loginfont = Font(
    family= "Helvetica",
    size= 42,
    weight = "bold"
)


def entrar():
        if senha.get() == 'cancelar11':
            room.destroy()
            window = Tk()

            window.title('Tkinter App Test')
            window.geometry("1100x700+120+15")
            window.configure(bg = '#021819')

            linha = IntVar()
            password = StringVar()
            email = StringVar()
            nome = StringVar()

            wall = Canvas(window, width=490, height=657, bg='#021819').place(x=590, y=20)

            def choice(option):
                if option == 'yes':
                    pop.destroy()
                    if hide.get() == 1:
                        wall = Canvas(window, width=490, height=657, bg='white').place(x=590, y=20)
                    if linha.get() == 1:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg= 'white').place(x=580, y=55)
                    if linha.get() == 2:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=580, y=85)
                    if linha.get() == 3:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=580, y=115)
                    if linha.get() == 4:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=580, y=145)
                    if linha.get() == 5:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=580, y=175)
                    if linha.get() == 6:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=580, y=205)

                    if linha.get() == 7:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=580, y=235)
                    if linha.get() == 8:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=580, y=265)
                    if linha.get() == 9:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=580, y=295)
                    if linha.get() == 10:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=325)
                    if linha.get() == 11:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=355)
                    if linha.get() == 12:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=385)
                    if linha.get() == 13:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=415)
                    if linha.get() == 14:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=445)
                    if linha.get() == 15:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=475)
                    if linha.get() == 16:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=505)
                    if linha.get() == 17:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=535)
                    if linha.get() == 18:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=565)
                    if linha.get() == 19:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=595)
                    if linha.get() == 20:
                        label = Label(window,
                                      text=nome.get() + '  -  ' + email.get() + '  -  ' + password.get(),
                                      font=('Arial', 15),
                                      bg='white').place(x=592, y=625)
                    if hide.get() == 0:
                        wall = Canvas(window, width=490, height=657, bg='#021819').place(x=590, y=20)

                else:
                    pop.destroy()

            def add():
                global pop
                pop = Toplevel(window)
                pop.title('Warning')
                pop.geometry('300x150+510+250')
                pop_label = Label(pop, text='Tem certeza?', font=('Arial', 12)).place(x=100, y=25)
                yes_opt = Button(pop, text='Yes', command=lambda: choice('yes')).place(x=110, y=90)
                no_opt = Button(pop, text='Cancel', command=lambda: choice('no')).place(x=150, y=90)

            back = Canvas(window, width = 520, height = 657, bg ='white').place(x= 20, y = 20)

            wall = Canvas(window, width=520, height=657, bg='white').place(x=560, y=20)

            numbers = Label(window, text='1', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=55)
            numbers = Label(window, text='2', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=85)
            numbers = Label(window, text='3', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=115)
            numbers = Label(window, text='4', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=145)
            numbers = Label(window, text='5', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=175)
            numbers = Label(window, text='6', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=205)
            numbers = Label(window, text='7', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=235)
            numbers = Label(window, text='8', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=265)
            numbers = Label(window, text='9', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=295)
            numbers = Label(window, text='10', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=325)
            numbers = Label(window, text='11', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=355)
            numbers = Label(window, text='12', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=385)
            numbers = Label(window, text='13', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=415)
            numbers = Label(window, text='14', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=445)
            numbers = Label(window, text='15', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=475)
            numbers = Label(window, text='16', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=505)
            numbers = Label(window, text='17', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=535)
            numbers = Label(window, text='18', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=565)
            numbers = Label(window, text='19', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=595)
            numbers = Label(window, text='20', font=(loginfont, 15), bg='white', fg='black').place(x=560, y=625)


            title = Label(window,
                          text= 'New account',
                          font= (loginfont, 50),
                          bg = 'white',
                          fg = 'green').place(x= 30, y= 20)

            Name_Site = Label(window,
                              text = 'Name:',
                              fg = 'black',
                              bg= 'white',
                              font=('Arial Bold', 20)).place(x= 30, y= 100)

            name_input = Entry(window,
                               bg = '#EAEAEA',
                               width = 83,
                               textvariable=nome
                               ).place(x=30, y=140, height = 36)

            emaill = Label(window,
                              text = 'Email:',
                              fg = 'black',
                              bg= 'white',
                              font=('Arial Bold', 20)).place(x= 30, y= 175)

            email_input = Entry(window,
                               bg='#EAEAEA',
                               width=83,
                               textvariable=email
                               ).place(x=30, y=210, height=36)

            key = Label(window,
                              text = 'Password:',
                              fg = 'black',
                              bg= 'white',
                              font=('Arial Bold', 20)).place(x= 30, y= 245)

            key_input = Entry(window,
                                bg='#EAEAEA',
                                width=83,
                                textvariable=password
                                ).place(x=30, y=285, height=36)

            show_word = Label(window,
                              text= 'Show',
                              bg = 'white',
                              fg = 'black',
                              font=('Arial Bold', 20)).place(x=75, y = 340)

            line_word = Label(window,
                              text='Line:',
                              bg='white',
                              fg='black',
                              font=('Arial Bold', 20)).place(x=400, y=340)

            line_indicator = Entry(window, bg='#EAEAEA',
                                   width = 9,
                                   textvariable=linha).place(x=473, y=340, height=36)
            hide = IntVar()

            show_hide = Checkbutton(window,
                                variable= hide).place(x=35, y=346)

            add_btn = Button(window,
                             text='Add',
                             width='10',
                             height='2',
                             bg='green',
                             fg='white',
                             command = add,
                             font=12
                             ).place(x= 227, y=498)

            window.mainloop()
        else:
            tstt = Label(room, text='Senha incorreta. Tente novamente!', bg= 'white', fg= 'red').place(x = 330, y = 295)

square = Canvas(room, width = 450, heigh = 400, bg = 'white'). place(x = 325, y = 140)

register_phrase = Label(room,
                        text= 'Login',
                        bg = ('white'),
                        font = loginfont,
                        fg = 'green',
                        ).place(x = 473, y = 140)

initial_password = Label(room,
        text=('Password:'),
        bg=('white'),
        font = ('Arial Bold', 15),
        fg =('black')
    ).place(x = 330, y = 215)

enter_password = Entry(room,
        bg = '#EAEAEA',
        width = 73,
        textvariable=senha,
        show = '•'
    ).place(x = 332, y = 250, height = 40)

submit_button = Button(room,
        text= 'Submit',
        width = '10',
        height = '2',
        bg = 'green',
        fg = 'white',
        command = entrar,
        font = 12
    ).place(x = 498, y = 385)

room.mainloop()
