# 201600041KangSaewoon
Assignment for Class 'Logic and Basic Programming'

#Assignment No.1(22.09.18)
a=1
b=2
print(a+b)

#Assignment No.3 & 4(22.09.18)

try:
  Answer = int(input ('정수를 입력하세요.: '))

  # 조건 분기문
  if Answer <= 30:
    for i in range(1, Answer+1) :
      for j in range(1, i+1) :
        print(j, end="")
      print()
  else :
      print('숫자가 너무 큽니다.')
      

except ValueError :
  print('정수를 입력하세요.')    
