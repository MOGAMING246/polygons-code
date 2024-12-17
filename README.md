import turtle


screen = turtle.Screen()
screen.bgcolor("green")


pen = turtle.Turtle()

pen.color("yellow")


pen.penup()
pen.goto(0, -100)
pen.pendown()
pen.circle(100) 


pen.hideturtle()


screen.mainloop()
