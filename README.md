# Homework-1
a = 0*1*2*3*4*5*6*7*8*9*10 #Bai 1 tính và in ra tích các số tự nhiên [0-10].
print(a)
n = int(input("Nhập số cần tính giai thừa: ")) #Bài 2 - Tính và in ra giai thừa 
def giaithua(n):
    if n == 0:
        return 1
    return n * giaithua(n-1)
print (giaithua(n))
#Bài 3: Nhập vào số nguyên dương n từ bàn phím. Kiểm tra xem số n có phải là số nguyên tốt hay không

def is prime(n):
    count = 0
    for i in range(1, n+1):
        if n % i == 0:
            count +=1
    if count == 2:
        return True
    return False
n = int(input())
print(is_prime(n))
#Bài 4 Nhập vào từ bàn phím số nguyên n. In ra tổng của các số thỏa mã hai điều kiện nhỏ hơn n và là số chẵn
a=int(input("Nhập một số nguyên a"))
if a%2==0:
    tổng_số_chẵn=((a-2)*a)/4
    print(tổng_số_chẵn)
elif a%2==1:
    tổng_số_lẻ=((a-2)*a)/4
    print(tổng_số_lẻ)
    #Bài 5: Nhập số nguyên từ bàn phím, in ra tích của 2 nhân vois các giá trị nhỏ của n
a = int(input("Nhập số nguyên"))
a=1
for a in range(1, a+1):
    print('2*',a,'=',2*i)
    #Bài 6 In ra các số trong khoảng từ 10->50 chia hết cho 2 và 3
for i in range(10, 50):
    if i % 2 != 0 and i % 3 != 0:
        print (i)
        #Bài 7 chuyển chữ thường sang in hoa
print("hello world".upper())

print('practice makes perfect'.upper())
#Bài 8 từ một chuỗi các từ riêng biệt, loại bỏ trùng lặp và in chúng
n=input('Nhập một chuỗi')
i=getattr(a,'split')()
def cau_moi(b):
    chuỗi=''
    for từ in i:
        if từ not in chuỗi:
            chuỗi = chuỗi + từ
    return chuỗi
print(cau_moi(i))
        #Bài 9 kiểm tra chuỗi palindrome
try:
    string = raw_input('\n-Nhap chuoi:')
    string_lo = string lower()
    string_re = string_lo[::-1]
    if tring_lo==string_re:
        print '\n=>',string,'la mot palindrome\n'
    else:
        print'\n=>',string,'khong phai la mot palindrome\n'
