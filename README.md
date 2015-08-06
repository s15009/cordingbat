# cordingbat

## sleep_in 

寝たいので翌日が平日か祝日かでTrue,Falseを返す

```
def sleep_in(weekday, vacation):
  return (not weekday or vacation)
```

## monkey_trouble

二匹の表情が一緒ならTrue, 違うとFalse返す

```
def monkey_trouble(a_smile, b_smile):
  return (a_smile == b_smile)
```

## sum_double

二つ整数をたす。二つ整数が同じなら２倍にする

```
sum = a + b
 
 if a == b:
  sum = sum * 2
 return sum
 ```
 
 ## diff21 

```
def diff21(n):
 if n <= 21:
  return 21 - n
 else:
  return (n - 21) * 2
```

## parrot_trouble

```
def parrot_trouble(talking, hour):
  return (talking and (hour < 7 or hour > 20))
```





