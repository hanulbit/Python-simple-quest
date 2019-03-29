# Python-simple-quest

연습문제 1. 사용자에게 시간과 시급을 입력 받아
급여를 계산하는 프로그램을 작성하시오.

```python
a = input('Enter hour : ')
b = input('Enter rate : ')
c = int(a)*int(b)
print('Pay: ',c)
```


연습문제 2. 1부터 10까지 출력하는 프로그램을 작성하시오.

```python
i = 1
while i<=10:
     print(i)
     i+=1
```

연습문제 3. 0부터 10까지의 수중에서 짝수만 출력하는 프로그램을 작성하시오.

```python
for X in range(2,11,2):
     print(X)
```

연습문제 4. 입력한 숫자에 해당하는 구구단을 출력하는 프로그램을 작성하시오.

```python
while True:
    a = input("몇 단?")
    for i in range(1, 10):
        print(a, "x", i, "=", int(a)*i) 
```
