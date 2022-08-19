s1 = 1
while True:
    s = s1
    n = 50
    while n > 0:
        n = s // n
        s = s // 2
    if s > 10000:
        print(s1)
        break
    s1 += 1
