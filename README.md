import turtle

# Tạo màn hình vẽ
screen = turtle.Screen()
screen.bgcolor("white")
screen.title("Turtle Example")

# Tạo một con rùa
pen = turtle.Turtle()
pen.shape("turtle")
pen.color("blue")
pen.speed(1)

# Vẽ hình vuông
for _ in range(4):
    pen.forward(100)
    pen.left(90)

# Kết thúc
turtle.done()
