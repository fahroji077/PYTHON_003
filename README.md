# PYTHON_003

1. PERCABANGAN IF

```y
is_day = False
is_night = True

if is_day:
    print("selamat siang")

elif is_night: 
    print("selamat malam")

else:
    print("selamat suka-suka")

print("selamat menikmati harimu")
```
![image](https://user-images.githubusercontent.com/93015185/140761883-fdf02f92-023f-41a2-b614-7bcf8417e6aa.png)

2. Operator Perbandingan

```y
grade = 7

if grade >= 8:
    print("nilai kamu a")
elif grade >= 7:
    print("nilai kamu b")
elif grade >= 6:
    print("nilai kamu c")
else:
    print("nilai kamu selain a")
```
![image](https://user-images.githubusercontent.com/93015185/140762246-3699bbc5-150a-4c5a-b55d-66329bc3366b.png)


3. Operator Logika

```y
nama = "muhammad fahroji"
by_pass_validation = False

if len(nama) > 3 or by_pass_validation :
    print("selamat datang")
else:
    print("nama terlalu pendek")


#False or true
#True or False
#True and False
#False and True
#True and True
```
![image](https://user-images.githubusercontent.com/93015185/140762320-edbda9d9-bf93-4239-8693-ad8c3e0e4c1d.png)

4. Perulangan While

```y
index = 1

while index <= 5 :
    print("*" * index)
    index += 1

print("finis")

```
![image](https://user-images.githubusercontent.com/93015185/140762536-0bf54c0f-6c9c-4a2d-939c-82d0c97250dd.png)

5. Game Tebak Angka
```y
trying = 0
secret_number = 7
limit = 3

while trying < limit:
    guess_number = input("masukkan angka (1-9) :")
    guess_number = int(guess_number)

    if guess_number == secret_number:
        print("selamat kamu menang")
        break 

trying += 1
```
![image](https://user-images.githubusercontent.com/93015185/140763092-9776cf69-3ed8-46df-b0ae-2ffbd3b69c48.png)

6. Aplikasi Kalkulator
```y
# (+ - * / exit)
command = ""

while command != "exit" :
    command = input("perintah :")

    if command == "exit":
        break

    if command != "+" and command != "-" and command != "*" and command != "/":
        print("perintah tidak dikenal")
        continue
    a = int(input("angka pertama : "))
    b = int(input("angka kedua : "))

    if command == "+":
        risult = a + b
    elif command == "-":
        risult = a - b
    elif command == "*":
        risult = a * b
    elif command == "/":
        risult = a / b

    print(f"hasil : {risult}")

print("terimakasih sudah menggunakan aplikasi ini")
```
![image](https://user-images.githubusercontent.com/93015185/140763290-18c44b04-941b-4683-9375-bfdfa8645061.png)

