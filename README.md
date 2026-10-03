while True:
    try:
        Height = int(input("Height: "))
        if(Height >= 1 and Height <= 8):
            for i in(range(Height)):
                print(" " * (Height - i - 1) + "#" * (i + 1) + "  " + "#" * (i + 1))
            break
    except ValueError:
        pass
