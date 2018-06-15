# python   1   INPUTS AND OUTPUTS:
# 符  號	描述
     %c	 格式化字元及其ASCII碼
     %s	 格式化字串
     %d	 格式化整數
     %u	 格式化無符號整型
     %o	 格式化無符號八進位數
     %x	 格式化無符號十六進位數
     %X	 格式化無符號十六進位數（大寫）
     %f	 格式化浮點數字，可指定小數點後的精度
     %e	 用科學計數法格式化浮點數
     %E	 作用同%e，用科學計數法格式化浮點數
     %g	 %f和%e的簡寫
     %G	 %f 和 %E 的簡寫
     %p	 用十六進位數格式化變數的位址
prompt(提示):# Input(輸入):Prompt the user to enter a radius
radius = eval(input("Enter a number for radius: "))

# Processing(處理):Compute area
area = radius * radius * 3.1415962

# Output(輸出):Display results
print("The area for the circle of radius", radius, "is", area)

試驗:
>>> radius = eval(input("Enter a number for radius: "))
Enter a number for radius: 8
>>> area = radius * radius * 3.1415962
>>> print("The area for the circle of radius", radius, "is", area)
The area for the circle of radius 8 is 201.0621568
得半徑8長度單位之圓面積:201.0621568平方單位
   
     
     
# output(輸出):print
     >>> q = 259
     >>> p = 0.038
     >>> print(q, p, p * q)
         output: 259 0.038 9.842
     >>> print(q, p, p * q, sep=",")
         output: 259,0.038,9.842
     >>> print(str(q) + " " + str(p) + " " + str(p * q))
         output: 259 0.038 9.842
     >>> print(q, p, p * q, sep=" :-) ")
         output: 259 :-) 0.038 :-) 9.842
         
   備註:  eval() arg 1 must be a string or code object
          Eval（）arg 1必須是字符串或代碼對象
-------------------------------------------------------------------------------------------------------------------------
Python   2   資料型態(data type)及其運算
 2-2
   餘數運算子 (remainder|modulo)
  
   題目:將以秒表示的總時間長，分別取得分鐘數及剩餘的秒數
   
   prompt(提示):seconds = eval(input("Enter an integer for seconds: "))
minutes = seconds // 60     # Find minutes in seconds
remainingSeconds = seconds % 60   # Seconds remaining
print(seconds, "seconds is", minutes, "minutes and", remainingSeconds, "seconds")

試驗:
>>> seconds = eval(input("Enter a number for seconds: "))
Enter a number for seconds: 610
>>> minutes = seconds//60
>>> remainingseconds = seconds%60print(seconds, "seconds is", minutes, "minutes and", remainingseconds, "seconds")
610 seconds is 10 minutes and 10 seconds
得610秒是10分10秒


2-3(待試驗)
ython有許多內建函數(built-in functions)
https://docs.python.org/3/library/functions.html網址
https://docs.python.org/2/library/functions.html網址
https://www.programiz.com/python-programming/methods/built-in網址

2.4. 字串(string)資料型態及其運算
>* 為了效率最佳化，若字串內容相同，則Python只使用一物件


宣告格式:
string = "__"
stringa = str(__)
id(string)
id(stringa)
試驗:string = "fire tornado"


*replace()取代
試驗:
string.replace("fire","ice")
'ice tornado'

str 類別有許多方法(運算子)與函數
len(stringb)
max(stringb)
min(stringb)

試驗:
'ice tornado'
>>>len(string)
12
>>> max(string)
't'
>>> min(string)
' '------------>二進位	十進位	十六進位	圖形
                0010 0000	32	20	(space)
 
 
*join()即在每個字元間加入想加之字元 

試驗:
'_'.join("Dragon")
'D_r_a_g_o_n'
>>> 'x'.join("Dragon")
'Dxrxaxgxoxn'

split()即分裂以空白格分開之字元組

試驗:string1 = "I love you"
>>> string1.split()
['I', 'love', 'you']
>>> string2 = 'x'.join("Dragon")
>>> string2.split(sep='x')
['D', 'r', 'a', 'g', 'o', 'n']

                








   
   
    
    

