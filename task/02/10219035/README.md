# 10219035
Dinda Fahrila Suci Ramadhani


## materi sebelumnya
+ Dasar-dasar coding (string, tuples, list, range, lopping, dll)
+ Step pembuatan grafik di python
+ Memasukkan rumus dalam phython (bola) dan membuat matriks
+ Rekursif dan Fraktal
+ Persamaan Lorentz
+ Runge-Kutta Orde 4
+ Euler
+ Osilasi Harmonik Sederhana
+ Monte Carlo 


## materi paling menarik
+ Materi yang paling menarik menurut saya yaitu materi Runge-Kutta Orde 4, hal ini dikarenakan saya baru pertama kali mengetahui metode Runge-Kutta. Selain itu, dalam pembelajaran SPSF, penggunaan Runge-Kutta ini cukup banyak dan hasilnya lebih baik daripada menggunakan metode Euler.


## materi paling membosankan
+ Materi mengenai Osilasi Harmonik Sederhana, hal tersebut dikarenakan pada OHS terdapat beberapa macam kasus, seperti overdamped, critically damped, dan underdamped, sehingga cukup banyak yang harus dipelajari. 


## materi yang sudah dipami
+ Materi yang saya pahami yaitu penggunaan Monte Carlo, dikarenakan penggunaan Monte Carlo ini cukup sederhana dalam pembuatan codingnya, dan kasus pada Monte Carlo ini tidak terlalu banyak jenisnya.


## materi yang belum dipahami
+ Sama seperti materi yang paling membosankan, hal tersebut membuat saya menjadi kurang memahami mengenai materi Osilasi Harmonik Sederhana. Saya kurang memahami mengenai pembuatan coding pada materi tersebut, sehingga saya ingin lebih memahami materi OHS dalam hal codingannya. 


## contoh program
+ Buat suatu contoh program dalam Python dan sertakan di sini dengan hasil keluarnnya.

```python
# contoh program python

import matplotlib.pyplot as plt
import random 

inside = 0 
n = 10000

x_inside=[]
y_inside=[]
x_outside=[]
y_outside=[]

for _ in range(n):
    x=random.uniform(-1.0,1.0)
    y=random.uniform(-1.0,1.0)
    if x**2+y**2<=1:
        inside+=1
        x_inside.append(x)
        y_inside.append(y)
    else:
        x_outside.append(x)
        y_outside.append(y)

pi=4*inside/n
print(pi)
        
fig, ax=plt.subplots()
ax.set_aspect('equal')
ax.scatter(x_inside, y_inside, color='g', marker='s')
ax.scatter(x_outside, y_outside, color='r', marker='s')

plt.draw()

```

Hasilnya adalah

3.132
![alt text](https://github.com/dindafahrila/fi4002-01-2022-1/blob/main/task/02/10219035/monte_carlo_phi.jpeg?raw=true)


## cara perkuliahan
+ Perkuliahan selama ini sudah baik, dan mudah dimengerti, hal ini dikarenakan, sebelum mengerjakan suatu tugas, sudah terdapat materi yang dijelaskan sebelumnya, seperti telah diberikan contoh mengenai program yang nantinya akan digunakan. Untuk perkuliahan seterusnya, mungkin dapat juga untuk tetap mencantumkan atau menjelaskan mengenai pemograman yang akan digunakan.


## topik sistem fisis
+ Sistem fisis yang menurut saya menarik yaitu mengenai osilasi, namun saya masih belum terlalu paham dalam penggunaan programnya. Sistem fisis pada osilasi menarik dikarenakan merupakan persamaan diferensial, yang mana dalam penyelesaiannya menggunakan metode Runge-Kutta.


## simulasi dan visualisasi
+ Saya tertarik dengan simulasi dan visualisasi pada materi Monte Carlo, hal ini dikarenakan cukup mudah dalam memahami pemogramannya, simulasi monte carlo juga cukup mudah karena menggunakan bilangan random yang mana langsung dapat di input dari library phythonnya. Pustaka atau library python yang diguanakn yaitu matplotlib.pyplot untuk menampilkan plot grafik dan menggunakan random untuk menampilkan angka yang acak pada input yang digunakan. 
