<?php

// Menampilkan teks
echo "Hello World";

echo "\n";

// Variabel
$nama = "ALSHAYNA";
$umur = 17;

echo "Nama saya " . $nama;

echo "\n";

echo "Umur saya " . $umur;

echo "\n";

// Percabangan
if ($umur >=16) {
    echo "Sudah dewasa";
} else {
    echo "Masih anak-anak";
}

echo "\n";

// Perulangan
for ($i = 1; $i <= 3; $i++) {
    echo "Belajar PHP";
    echo "\n";
}

// Array
$buah = ["Apel", "Mangga", "Jeruk"];

echo $buah[0];

echo "\n";

// Function
function salam() {
    echo "Selamat Datang";
}

salam();

?>
