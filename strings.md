# python1
#%s,%d is used to put in text or numbers in STRINGS只能用于字符串中
## %s allows to put in string,%d allows to put in number
s = "My name is %s"%"Jevin"
ss = "I'm %d years old"%21
print(s,',',ss)
##Match each %s,%d for every one you have in a string
s = "My name is %s, I'm %d years old"
print(s%('Jevin',21))
 >>>My name is Jevin , I'm 21 years old
 >>>My name is Jevin, I'm 21 years old
 
-------------------------------------------
#formar函数格式化字符串
##same as %s,%d but useing{} instead
##same as above it is used in strings
##remember how the syntax is  , add .format() to input text or number
s = "I love {}".format("her")
print(s)
##with multiple values, format syntax is used as follow:
ss = "I am {0} years old, My name is {1},I love being {0}".format(21,"jevin")#remember starts with 0
print(ss)
-------------------------------------------------------
#None
##表示什么都没有
##若函数没有返回值，可以返回None
##可以用来占位置
##用来解除变量的绑定
