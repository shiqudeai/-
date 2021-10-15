# -求两个数的最大值
def max(num1, num2):
    if num1 > num2:
        result = num1
    else:
        result = num2
    return result
def main():
    i,j = eval(input("请输入两个数i和j:"))
    k = max(i, j)
    print("i 和 j之间最大的数是",k)
main()
