# Operation-practice
基本運算練習
# -*- coding: cp950 -*-

print "這是一個能分辨是五的整數還是二的整數的程式"

number = eval(raw_input("Enter some word :"))
if number % 5 == 0:
    print "GREAT 5"

if number % 2 == 0:
    print "GREAT 2"
    
print"-----------------------------------------------------"

print "輸入兩數並分辦大小，並判斷加檢是否錯誤"

import random

num1 = eval(raw_input("Enter a number1 :"))
num2 = eval(raw_input("Enter a number2 :"))

if num1 < num2:
    num1, num2 = num2, num1

answer = eval(raw_input("what is " + str( num1 ) + " - " + str( num2 ) + " ? "))

if num1 - num2 == answer:
    print "Yeah you are great"

else:
    print "oops your answer is wrong\n", num1 , "-", num2, "is", num1 - num2, "."

print"-----------------------------------------------------"

print "隨機製造兩個一到一百的數字進行加減，並檢查是否正確"


num3 = random.randint(0,100)
num4 = random.randint(0,100)

if num3 < num4:
    num3 ,num4 = num4 ,num3

answer = eval(raw_input("WHAT IS " + str( num3 ) + " - "   +str( num4 ) + " ? "))

if num3 - num4 == answer:
    print "you are right"

else:
    print "you are wrong\n" ,num3 ,"-", num4, "=", num3 - num4, ":D"

print"-----------------------------------------------------"

print"徒法煉鋼 -> 判斷10筆成績並顯示其級數"

score1 = eval(raw_input("enter a number1 between 0 to 100 :"))
score2 = eval(raw_input("enter a number2 between 0 to 100 :"))
score3 = eval(raw_input("enter a number3 between 0 to 100 :"))
score4 = eval(raw_input("enter a number4 between 0 to 100 :"))
score5 = eval(raw_input("enter a number5 between 0 to 100 :"))
score6 = eval(raw_input("enter a number6 between 0 to 100 :"))
score7 = eval(raw_input("enter a number7 between 0 to 100 :"))
score8 = eval(raw_input("enter a number8 between 0 to 100 :"))
score9 = eval(raw_input("enter a number9 between 0 to 100 :"))
score10 = eval(raw_input("enter a number10 between 0 to 100 :"))




if score1 >= 90:
    grade1 = 'A'
elif score1 >= 80:
    grade1 = 'B'
elif score1 >= 70:
    grade1 = 'C'
elif score1 >= 60:
    grade1 = 'D'
else:
    grade1 = 'F'



if score2 >= 90:
    grade2 = 'A'
elif score2 >= 80:
    grade2 = 'B'
elif score2 >= 70:
    grade2 = 'C'
elif score2 >= 60:
    grade2 = 'D'
else:
    grade2 = 'F'



if score3 >= 90:
    grade3 = 'A'
elif score3 >= 80:
    grade3 = 'B'
elif score3 >= 70:
    grade3 = 'C'
elif score3 >= 60:
    grade3 = 'D'
else:
    grade3 = 'F'



if score4 >= 90:
    grade4 = 'A'
elif score4 >= 80:
    grade4 = 'B'
elif score4 >= 70:
    grade4 = 'C'
elif score4 >= 60:
    grade4 = 'D'
else:
    grade4 = 'F'



if score5 >= 90:
    grade5 = 'A'
elif score5 >= 80:
    grade5 = 'B'
elif score5 >= 70:
    grade5 = 'C'
elif score5 >= 60:
    grade5 = 'D'
else:
    grade5 = 'F'



if score6 >= 90:
    grade6 = 'A'
elif score6 >= 80:
    grade6 = 'B'
elif score6 >= 70:
    grade6 = 'C'
elif score6 >= 60:
    grade6 = 'D'
else:
    grade6 = 'F'



if score7 >= 90:
    grade7 = 'A'
elif score7 >= 80:
    grade7 = 'B'
elif score7 >= 70:
    grade7 = 'C'
elif score7 >= 60:
    grade7 = 'D'
else:
    grade7 = 'F'



if score8 >= 90:
    grade8 = 'A'
elif score8 >= 80:
    grade8 = 'B'
elif score8 >= 70:
    grade8 = 'C'
elif score8 >= 60:
    grade8 = 'D'
else:
    grade8 = 'F'



if score9 >= 90:
    grade9 = 'A'
elif score9 >= 80:
    grade9 = 'B'
elif score9 >= 70:
    grade9 = 'C'
elif score9 >= 60:
    grade9 = 'D'
else:
    grade9 = 'F'



if score10 >= 90:
    grade10 = 'A'
elif score10 >= 80:
    grade10 = 'B'
elif score10 >= 70:
    grade10 = 'C'
elif score10 >= 60:
    grade10 = 'D'
else:
    grade10 = 'F'
print grade1 , grade1, grade2, grade3, grade4, grade5, grade6, grade7, grade8, grade9, grade10
