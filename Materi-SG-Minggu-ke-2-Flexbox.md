# Pengenalan Flexbox

- Flex container: Parent atau pembungkusnya
- Flex items: Child atau yang berada di dalam flex container
- Ini adalah pondasi buat memahami flexbox lebih lanjut

# Menggunakan Flexbox

- Untuk menggunakan flexbox kalian harus mendekrasikan property *display: flex;* pada pada parent elemen/flex container nya.

## The Flex Container Properties / Parent

- Flex-direction: || Flex-wrap || Flex-flow || Justify-content || Align-items || Align-content

### Flex direction: column, row, row-reverse, column-reverse

- Untuk menentukan posisi nya horizontal atau vertical
- Cara pake: flex-direction: column

### Flex wrap: wrap, nowrap, wrap-reverse

- Untuk pindah ke elemen bawahnya jika elemen sudah tidak mempunyai cukup ruang, ata kata lain membuat multi lines

### Flex flow: penyingkat untuk flex direction dan flex wrap

- Jadi multiple nilai dideklarasikan dalam satu nilai
- Cara pake: flex-flow: row wrap

### Justify Content

- Digunakan untuk memposisikan sebuah elemen flex secara horizontal
- justify-content: flex-start || flex-end || center || space-between || space-around 

### Align Items

- Untuk memposisikan elemen flexbox secara vertical
- flex-start || flex-end|| center || stretch || baseline

### Align Content

- Untuk memposisikan elemen pada multi lines elemen dan posisi defaultnya adalah horizontal, nilainya dan cara pakenya sama dengan align items


## The Flex Items Properties / Child

- Order || Flex-grow || Flex-shrink || Flex-basis

### Order 

- Digunakan untuk memposisikan sebuah elemen, misalnya yg tadinya posisinya pertama kita pindah ke posisi 3 misalnya tanpa harus mengubah kode htmlnya
- order: 1 //atau nilai lainnya, default nilai 0

### Flex grow

- Digunakan untuk mengatur gimana seberapa banyak elemen pada flex items seharusnya tumbuh atau di exntend jika ada ruang kosong, default nilai 0
- Cara pake: flex-grow: 0 - angka positif

### Flex shrink 

- Digunakan untuk membuat elemen lebarnya menyusut ketika dibutuhkan, kebalikan dari flex  grow yang meluas nilai default 1

### Flex Basis 

- Untuk mengatur lebar awal sebuah elemen, nilai defaultnya auto mengikuti isi content di dalam elemennya


### Flex 

- Untuk penyingkat penulisan properti grow, shrink dan basis, 
- Cara pake: flex: 0 1 auto; //nilai defaultnya


### Auto Margin Elemen / Alignment Pada Flex Items

- Ketika menggunakan auto margin maka justify-content tidak akan bekerja pada flex-items 
- margin-right: auto //contoh penggunaan auto margin

### Auto Margin untuk Navigation System 

- Contoh Lihat Navigasi Twitter atau Instagram


### Referensi Lebih Tentang Flexbox

- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://medium.freecodecamp.org/the-complete-illustrated-flexbox-tutorial-d35c085dbf35
