# fizzbuzz
def fizzbuzz(n):
    for i in range(1,n):
        if i%3==0 and i%5==0:
            print("FizzBuzz")
        elif i%3==0 and i%5!=0:
            print("Fizz")
        elif i%3!=0 and i%5==0:
            print("Buzz")
        elif i%3!=0 and i%5!=0:
            print(i)
    else:
        print("NONE")
fizzbuzz(20)


            
