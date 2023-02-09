from turtle import Turtle, Screen

d = Turtle()


def move_forward():
    d.forward(10)


def move_backward():
    d.backward(10)


def move_right():
    new_heading = d.heading() - 10
    d.setheading(new_heading)


def move_left():
    new_heading = d.heading() + 10
    d.setheading(new_heading)


def clear_screen():
    d.clear()
    d.penup()
    d.home()
    d.pendown()

screen = Screen()
screen.listen()
screen.onkey(move_forward, "f")
screen.onkey(move_backward, "b")
screen.onkey(move_right, "r")
screen.onkey(move_left, "l")
screen.onkey(clear_screen,"c")
screen.exitonclick()
