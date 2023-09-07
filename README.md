# Cricket-Match
# cook your dish here
for _ in range(int(input())):
    n, m = map(int, input().split())
    if m*36 >= n:
        print("YES")
    else:
        print("NO")
