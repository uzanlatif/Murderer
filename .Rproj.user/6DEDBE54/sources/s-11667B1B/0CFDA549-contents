library(dslabs)
data(murders)
class(murders)

#1
str(murders)
  #A. Variabel yang terdiri dari 51 negara
  #> Salah, Hanya State

  #B. Variabel yang berisi tingkat pembunuhan pada 50 negara bagian dan DC
  #> Salah karena berisi dari 51 negara bagian

  #C. Terdiri Nama negara bagian, singkatan negara bagian, wilayah negara bagian,
  #> Benar

  #D. Str tidak menunjukkan informasi relevan
  #> Salah


#2 nama kolom yang digunakan pada data frame
  names(murders)
  #> state, abb, region, population, dan total 

#3 aksesor($) untuk mengekstrak dari singkatan negara dan disimpan di objek "a", sebutkan jenis class objeck tsb
  a=murders$abb
  class(a)
  
  #jenis class adalah "character"

#4 Gunakan kurung siku untuk mengekstrak singkatan negara dan menyimpan di  variable b, apakah a dan b sama?

  b = murders[2]
  
  print(a)
  print(b)
  
  c = b == a
  print(c)
  #a dan b memiliki isi yang sama
  
  class(a)
  class(b)
  #a dan b berbeda jenis karena a memiliki class "character" sedangkan b memiliki class"data.frame"
  
#5 Dengan sebaris kode gunakan fungsi level dan lengt untuk menentukan jumlah region yg dimiliki dataset
  levels(murders$region)
  #berisi "Northeast"     "South"         "North Central" "West" 
  
  length(levels(murders$region))
  #berisi 4 lokasi

#6 Gunakan fungsi table dalam sebaris code untuk menampilkan table baru yang berisi jumlah state tiap region

  table(state.region)
  