# import turtle
# turtle.setup(1000,450,100)
# turtle.penup()
# turtle.forward(-250)
# turtle.pendown()
# turtle.pensize(25)
#
# turtle.seth(-40)
# for i in range(5):
#     turtle.pencolor((256,256,100))
#     turtle.circle(40,50)
#     turtle.circle(-40,50)
# turtle.circle(40,80/2)
# turtle.forward(40)
# turtle.circle(16)
# turtle.forward(-90)
# #
# import turtle as tu
# tu.pensize(10)
# tu.pencolor('red')
# #tu.circle(40)
# tu.circle(-90,90)
# # for i in range(1,10):
# #     tu.penup()
# #     tu.forward(10*i)
# #     tu.pendown()
# #     tu.circle(10*i)
# #     tu.penup()
# #     tu.seth(180)
# #     tu.fd(10*i)
# #     tu.pendown()
# import time
from turtle import *
# pencolor('red')
# seth(0)
# forward(100)
# seth(120)
# forward(100)
# seth(-120)
# forward(100)

# pencolor('red')
# for i in range(4):
#     forward(100)
#     penup()
#     circle(20,90)
#     pendown()

# for i in range(3):
#     seth(30-i*120)
#     forward(100)
# penup()
# seth(60)
# forward(50*2/3**0.5)
# pendown()
# for i in range(3):
#     seth(-90+120*i)
#     forward(100)

# forward(100)
# penup()
# circle(20,90)
# pendown()
# forward(100)
# penup()
# penup()
# circle(20,90)
# pendown()
# forward(100)
# penup()
# circle(20,90)
# pendown()
# forward(100)


# for i in range(50):
#     seth(90-90*i)
#     forward(100-2*i)
# a =pow(2,3)
# print(a)

# a=1
# a*=3+5**2
# print(a)
from math import *
# a=sin(2*pi)
# print(a)
# b=floor(-2.5)
# print(b)
# c=ceil(3.5+floor(-2.5))
# print(c)
# d=round(fabs(-2.5))
# print(d)
# # e=int(sqrt(pow(2,4)))
# # print(e)
# f=log(e)
# print(f)
# g=gcd(12,9)
# print(g)
# h=fmod(36,5)
# print(h)
# dayup=pow((1+0.001),365)
# daydown=pow((1-0.001),365)
# print('up= {:.2f} down= {:.2f}'.format(dayup,daydown),end=" ")
import math
# def dayup(df):
#     dayup = 1.0
#     for i in range(365):
#         if i % 7 in [0,6]:
#             dayup *= (1-0.01)
#         else:
#             dayup *= (1+df)
#     return dayup
# dayfactor = 0.01
# while (dayup(dayfactor) < 37.78):
#     dayfactor += 0.001
# print('每天的参数是：{:.3f}'.format(dayfactor))
#
# def dayUP(df):
#     dayup = 1.0
#     for i in range(365):
#         if i % 7 not in [0,6]:
#             dayup *=(1+df)
#     return dayup
# dayfactor = float(input("a number:"))
# print("results = {:.3f}".format(dayUP(dayfactor)))

# s='hello'
# t='world'
# s+=t
# print(s,s[-1],s[2:8],s[::3],s[-2::-1])
# s='Python String'
# print(s.upper(),s.lower(),s.find('i'),s.replace('ing','gni'),s.split(' '))
# print('Hello'>'hello')

# s='python'
# print('{0:30}'.format(s))
# print('{0:*<30}'.format(s))
# print('{0:3}'.format(s))

# print('{0:-^20,}'.format(1234.56789))
# print('{:->15s}:{:-<8.2f}'.format('Length',23.87501))
# print('{0:b},{0:c},{0:d},{0:o},{0:x}'.format(389))
# print('{:.4f}'.format(0.002178))
# print('{:.4e}'.format(0.002178))
# print('{:.4%}'.format(0.002178))

# import time
# scale = 10
# print('------执行开始------')
# for i in range(scale+1):
#     a,b = '*'*i,'-'*(scale+1)
#     c=(i/scale)*100
#     print('{:^3.0f}%[{}->{}]'.format(c,b,a))
# time.sleep(0.1)
# print('end')

# import time as tm
# for i in range (101):
#     print('\r{:3}%'.format(i),end=' ')
#     tm.sleep(0.05)

# import time as tm
# scale=50
# print('执行开始'.center(scale//2,'-'))
# for i in range(scale+1):
#     a = "*"*i
#     b = "-"*(scale-i)
#     c = (i/scale)*100
#     print("\r{:3.0f}% [{}->{}]".format(c,a,b),end=' ')
#     tm.sleep(0.05)
# print('\n'+'执行结束'.center(scale//2,'-'))

weight_one=float(input('请输入你的体重='))
weight_onm = 0.0
for i in range(11):
    weight_one+=0.5
    weight_onm=weight_one*0.165
    print('\n在地球上第{}年的体重是{:3.4f}kg,在月球上第{}年的体重是{:3.4f}kg'.format(i,weight_one,i,weight_onm),end=" ")


