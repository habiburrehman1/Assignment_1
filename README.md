# Assignment_1
english = int(input("marks of english:"))
biology = int(input("marks of biology:"))
islamiat = int(input("marks of islamiat:"))
urdu = int(input("marks of urdu:"))
math = int(input("marks of math:"))
marks_obtained = english + biology + islamiat + urdu + math
print(marks_obtained)
percentage = (marks_obtained/500*100)
print(percentage)
if (percentage >= 85) :
    print("grade A+1")
elif (percentage >= 70) :
    print("grade A")
elif (percentage >= 60) :
    print("grade B")
elif (percentage >= 50) :
    print("grade C")
elif (percentage >= 40) :
    print("grade D")
else :
    print("fail")
