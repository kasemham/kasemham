while True :
    try:
        age = int(input("ادخل عمر : "))
        print("ur age is : " , age)
        break
    except Exception as ex :
        print("wrong age")
