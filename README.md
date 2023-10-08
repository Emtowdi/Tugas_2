# Tugas_2
membuat contoh program javascript dengan menggunakan: if,else,nested if , switch case, for statement, while, do while , function.
// Contoh penggunaan if-else dan nested if
let nilai = 75;

if (nilai >= 90) {
  console.log("Nilai Anda A");
} else if (nilai >= 80) {
  console.log("Nilai Anda B");
} else if (nilai >= 70) {
  console.log("Nilai Anda C");
} else {
  console.log("Nilai Anda D");
}

// Contoh penggunaan switch case
let hari = "Selasa";
let aktivitas = "";

switch (hari) {
  case "Senin":
    aktivitas = "Kerja";
    break;
  case "Selasa":
    aktivitas = "Rapat";
    break;
  case "Rabu":
    aktivitas = "Presentasi";
    break;
  default:
    aktivitas = "Libur";
}

console.log(`Hari ${hari} adalah hari ${aktivitas}`);

// Contoh penggunaan for statement
for (let i = 0; i < 5; i++) {
  console.log(`Iterasi ke-${i}`);
}

// Contoh penggunaan while loop
let counter = 0;
while (counter < 3) {
  console.log(`Perulangan ke-${counter}`);
  counter++;
}

// Contoh penggunaan do-while loop
let angka = 1;
do {
  console.log(`Angka: ${angka}`);
  angka++;
} while (angka <= 5);

// Contoh penggunaan function
function tambah(a, b) {
  return a + b;
}

let hasilPenambahan = tambah(5, 3);
console.log(`Hasil penambahan: ${hasilPenambahan}`);
