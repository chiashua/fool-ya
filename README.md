import turtle

screen = turtle.Screen()
screen.bgcolor("skyblue")
screen.title("明年會去學插花 🌸")

pen = turtle.Turtle()
pen.speed(10)
pen.color("pink")

for i in range(36):
    pen.circle(50, 60)
    pen.left(120)
    pen.circle(50, 60)
    pen.left(10)

pen.penup()
pen.goto(0, -10)
pen.pendown()
pen.color("yellow")
pen.begin_fill()
pen.circle(10)
pen.end_fill()

pen.hideturtle()
turtle.done()
