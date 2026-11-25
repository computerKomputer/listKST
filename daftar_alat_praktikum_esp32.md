# Daftar Alat Praktikum Sistem Tertanam (ESP32)

Daftar komponen, estimasi harga, dan link pembelian untuk praktikum sistem tertanam berbasis ESP32.

> **Update harga:** November 2026 · **Sumber:** listing Tokopedia · **Mata uang:** Rupiah (Rp)

---

## Daftar Isi

1. [Cara Membaca Tabel](#cara-membaca-tabel)
2. [Hasil Verifikasi Harga](#hasil-verifikasi-harga)
3. [Bagian A: Kebutuhan Praktikum Inti](#bagian-a-kebutuhan-praktikum-inti)
4. [Bagian B: Sensor dan Aktuator Tambahan](#bagian-b-sensor-dan-aktuator-tambahan)
5. [Rekapitulasi Anggaran](#rekapitulasi-anggaran)
6. [Perangkat Lunak dan Dokumentasi](#perangkat-lunak-dan-dokumentasi)
7. [Catatan Penting dan Keselamatan](#catatan-penting-dan-keselamatan)

---

## Cara Membaca Tabel

| Simbol | Arti                                                                                                             |
|:------:|:---------------------------------------------------------------------------------------------------------------- |
| ✔      | Harga sudah dicek langsung pada listing Tokopedia dan shopee                                                     |
| ~      | Harga **perkiraan** umum pasar, belum dicek. Cek lagi lewat link sebelum membeli                                 |
|cek     |tes                                |
| Link   | Berupa **link pencarian** (bukan produk tertentu), jadi tetap berlaku. Bandingkan rating toko dan ulasan sendiri |

Ongkir tidak termasuk dalam harga. Untuk pengiriman jauh, ongkir bisa signifikan, jadi sebaiknya belanja dari satu toko.
tes 
tess




---

## Hasil Verifikasi Harga

Rentang harga dari listing Tokopedia yang sudah dicek:

| Komponen                           | Rentang Harga        | Dipakai di Tabel |
|:---------------------------------- |:-------------------- | ----------------:|
| ESP32 DevKit V1                    | Rp59.000 - Rp120.000 | Rp75.000         |
| DHT22 (modul)                      | Rp35.000 - Rp45.500  | Rp40.000         |
| HC-SR04                            | Rp10.500 - Rp18.000  | Rp15.000         |
| MPU6050 (GY-521)                   | Rp18.900 - Rp40.000  | Rp30.000         |
| OLED 0,96" I2C                     | Rp27.500 - Rp48.000  | Rp35.000         |
| L298N (modul penuh)                | Rp25.845             | Rp26.000         |
| L298N (versi mini)                 | Rp7.000              | -                |
| Servo SG90                         | Rp18.000 - Rp26.500  | Rp20.000         |
| RFID RC522 + tag                   | Rp12.500 - Rp29.000  | Rp20.000         |

| Stepper 28BYJ-48 + ULN2003 (paket) | Rp17.250             | Rp17.250         |

> **Catatan:** Abaikan listing dengan harga tidak wajar (misalnya jutaan rupiah untuk satu modul). Biasanya itu produk impor pre-order atau paket banyak pcs.

---

# Bagian A: Kebutuhan Praktikum Inti

Jumlah dan subtotal adalah **per mahasiswa/kelompok**, kecuali bagian A5 (per lab).

## A1. Perangkat Utama dan Komponen Dasar

| No  | Komponen             | Spesifikasi                   | Jml     | Harga Satuan | Subtotal      | Link                                                                                                                                                        |
|:---:|:-------------------- |:----------------------------- |:-------:| ------------:| -------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | ESP32 DevKit V1      | ESP32-WROOM-32, 30/38 pin     | 1       | Rp75.000 ✔   | Rp75.000      | [Tokopedia](https://www.tokopedia.com/search?q=esp32+devkit+v1) · [Shopee](https://shopee.co.id/search?keyword=esp32%20devkit%20v1)                         |
| 2   | Kabel USB data       | Micro-USB/USB-C sesuai board  | 1       | Rp15.000 ~   | Rp15.000      | [Tokopedia](https://www.tokopedia.com/search?q=kabel+micro+usb+data) · [Shopee](https://shopee.co.id/search?keyword=kabel%20micro%20usb%20data)             |
| 3   | Breadboard           | 830 titik                     | 1       | Rp20.000 ~   | Rp20.000      | [Tokopedia](https://www.tokopedia.com/search?q=breadboard+830+titik) · [Shopee](https://shopee.co.id/search?keyword=breadboard%20830%20titik)               |
| 4   | Kabel jumper         | M-M, M-F, F-F                 | 1 set   | Rp30.000 ~   | Rp30.000      | [Tokopedia](https://www.tokopedia.com/search?q=kabel+jumper+dupont+set) · [Shopee](https://shopee.co.id/search?keyword=kabel%20jumper%20dupont%20set)       |
| 5   | LED 5 mm             | Merah, hijau, kuning          | 10      | Rp500 ~      | Rp5.000       | [Tokopedia](https://www.tokopedia.com/search?q=led+5mm+set) · [Shopee](https://shopee.co.id/search?keyword=led%205mm%20set)                                 |
| 6   | Resistor kit         | 220Ω, 330Ω, 1k, 2k, 4,7k, 10k | 1 paket | Rp10.000 ~   | Rp10.000      | [Tokopedia](https://www.tokopedia.com/search?q=resistor+1%2F4w+set) · [Shopee](https://shopee.co.id/search?keyword=resistor%201%2F4w%20set)                 |
| 7   | Push button          | Tactile switch 4 pin          | 4       | Rp1.000 ~    | Rp4.000       | [Tokopedia](https://www.tokopedia.com/search?q=push+button+tactile+switch) · [Shopee](https://shopee.co.id/search?keyword=push%20button%20tactile%20switch) |
| 8   | Potensiometer        | 10 kΩ                         | 2       | Rp4.000 ~    | Rp8.000       | [Tokopedia](https://www.tokopedia.com/search?q=potensiometer+10k) · [Shopee](https://shopee.co.id/search?keyword=potensiometer%2010k)                       |
| 9   | Buzzer aktif         | 3,3 V / 5 V                   | 1       | Rp4.000 ~    | Rp4.000       | [Tokopedia](https://www.tokopedia.com/search?q=buzzer+aktif+5v) · [Shopee](https://shopee.co.id/search?keyword=buzzer%20aktif%205v)                         |
| 10  | Transistor NPN       | BC547 / 2N2222                | 2       | Rp1.000 ~    | Rp2.000       | [Tokopedia](https://www.tokopedia.com/search?q=transistor+bc547) · [Shopee](https://shopee.co.id/search?keyword=transistor%20bc547)                         |
| 11  | Dioda                | 1N4007                        | 2       | Rp500 ~      | Rp1.000       | [Tokopedia](https://www.tokopedia.com/search?q=dioda+1n4007) · [Shopee](https://shopee.co.id/search?keyword=dioda%201n4007)                                 |
| 12  | Kapasitor elektrolit | 100 µF, 470 µF                | 2       | Rp1.500 ~    | Rp3.000       | [Tokopedia](https://www.tokopedia.com/search?q=kapasitor+elco+100uf+470uf) · [Shopee](https://shopee.co.id/search?keyword=kapasitor%20elco%20100uf%20470uf) |
|     | **Subtotal A1**      |                               |         |              | **Rp177.000** |                                                                                                                                                             |

## A2. Sensor

| No  | Komponen                  | Spesifikasi                                   | Jml | Harga Satuan | Subtotal      | Link                                                                                                                                                                  |
|:---:|:------------------------- |:--------------------------------------------- |:---:| ------------:| -------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 13  | Modul LDR                 | Sensor cahaya                                 | 1   | Rp8.000 ~    | Rp8.000       | [Tokopedia](https://www.tokopedia.com/search?q=modul+sensor+ldr) · [Shopee](https://shopee.co.id/search?keyword=modul%20sensor%20ldr)                                 |
| 14  | DS18B20                   | Suhu, versi waterproof                        | 1   | Rp20.000 ~   | Rp20.000      | [Tokopedia](https://www.tokopedia.com/search?q=ds18b20+waterproof) · [Shopee](https://shopee.co.id/search?keyword=ds18b20%20waterproof)                               |
| 15  | DHT22 modul               | Suhu dan kelembapan                           | 1   | Rp40.000 ✔   | Rp40.000      | [Tokopedia](https://www.tokopedia.com/search?q=dht22+modul) · [Shopee](https://shopee.co.id/search?keyword=dht22%20modul)                                             |
| 16  | HC-SR04                   | Ultrasonik (Echo 5 V, perlu pembagi tegangan) | 1   | Rp15.000 ✔   | Rp15.000      | [Tokopedia](https://www.tokopedia.com/search?q=hc-sr04) · [Shopee](https://shopee.co.id/search?keyword=hc-sr04)                                                       |
| 17  | MPU6050 (GY-521)          | IMU, I2C                                      | 1   | Rp30.000 ✔   | Rp30.000      | [Tokopedia](https://www.tokopedia.com/search?q=mpu6050+gy-521) · [Shopee](https://shopee.co.id/search?keyword=mpu6050%20gy-521)                                       |
| 18  | BMP280 *(opsional)*       | Tekanan dan suhu, I2C                         | 1   | Rp30.000 ~   | Rp30.000      | [Tokopedia](https://www.tokopedia.com/search?q=bmp280) · [Shopee](https://shopee.co.id/search?keyword=bmp280)                                                         |
| 19  | Soil moisture             | Tipe capacitive                               | 1   | Rp20.000 ~   | Rp20.000      | [Tokopedia](https://www.tokopedia.com/search?q=capacitive+soil+moisture+sensor) · [Shopee](https://shopee.co.id/search?keyword=capacitive%20soil%20moisture%20sensor) |
| 20  | PIR HC-SR501 *(opsional)* | Sensor gerak                                  | 1   | Rp15.000 ~   | Rp15.000      | [Tokopedia](https://www.tokopedia.com/search?q=pir+hc-sr501) · [Shopee](https://shopee.co.id/search?keyword=pir%20hc-sr501)                                           |
|     | **Subtotal A2**           |                                               |     |              | **Rp178.000** |                                                                                                                                                                       |

## A3. Aktuator dan Display

| No  | Komponen             | Spesifikasi                 | Jml | Harga Satuan | Subtotal      | Link                                                                                                                                                      |
|:---:|:-------------------- |:--------------------------- |:---:| ------------:| -------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 21  | OLED SSD1306         | 0,96", 128x64, I2C          | 1   | Rp35.000 ✔   | Rp35.000      | [Tokopedia](https://www.tokopedia.com/search?q=oled+0.96+i2c+ssd1306) · [Shopee](https://shopee.co.id/search?keyword=oled%200.96%20i2c%20ssd1306)         |
| 22  | LCD 16x2 + modul I2C | PCF8574                     | 1   | Rp40.000 ~   | Rp40.000      | [Tokopedia](https://www.tokopedia.com/search?q=lcd+16x2+i2c) · [Shopee](https://shopee.co.id/search?keyword=lcd%2016x2%20i2c)                             |
| 23  | Servo SG90           | Micro servo 9 g             | 1   | Rp20.000 ✔   | Rp20.000      | [Tokopedia](https://www.tokopedia.com/search?q=servo+sg90) · [Shopee](https://shopee.co.id/search?keyword=servo%20sg90)                                   |
| 24  | Motor DC + gearbox   | 3-6 V                       | 2   | Rp20.000 ~   | Rp40.000      | [Tokopedia](https://www.tokopedia.com/search?q=motor+dc+gearbox+3v+6v) · [Shopee](https://shopee.co.id/search?keyword=motor%20dc%20gearbox%203v%206v)     |
| 25  | Driver motor L298N   | Modul penuh                 | 1   | Rp26.000 ✔   | Rp26.000      | [Tokopedia](https://www.tokopedia.com/search?q=driver+motor+l298n) · [Shopee](https://shopee.co.id/search?keyword=driver%20motor%20l298n)                 |
| 26  | Modul relay          | 1 channel, 5 V, optocoupler | 1   | Rp12.000 ~   | Rp12.000      | [Tokopedia](https://www.tokopedia.com/search?q=modul+relay+1+channel+5v) · [Shopee](https://shopee.co.id/search?keyword=modul%20relay%201%20channel%205v) |
| 27  | Pompa air mini       | 3-6 V                       | 1   | Rp20.000 ~   | Rp20.000      | [Tokopedia](https://www.tokopedia.com/search?q=pompa+air+mini+dc+3v+6v) · [Shopee](https://shopee.co.id/search?keyword=pompa%20air%20mini%20dc%203v%206v) |
|     | **Subtotal A3**      |                             |     |              | **Rp193.000** |                                                                                                                                                           |

## A4. Penyimpanan, Identifikasi, dan Catu Daya

| No  | Komponen                               | Spesifikasi                 | Jml   | Harga Satuan | Subtotal      | Link                                                                                                                                                    |
|:---:|:-------------------------------------- |:--------------------------- |:-----:| ------------:| -------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 28  | Modul microSD                          | SPI                         | 1     | Rp8.000 ~    | Rp8.000       | [Tokopedia](https://www.tokopedia.com/search?q=modul+micro+sd+card+spi) · [Shopee](https://shopee.co.id/search?keyword=modul%20micro%20sd%20card%20spi) |
| 29  | Kartu microSD                          | 16 GB, FAT32                | 1     | Rp50.000 ~   | Rp50.000      | [Tokopedia](https://www.tokopedia.com/search?q=micro+sd+16gb) · [Shopee](https://shopee.co.id/search?keyword=micro%20sd%2016gb)                         |
| 30  | RFID RC522 + tag                       | 13,56 MHz, kartu + keychain | 1 set | Rp20.000 ✔   | Rp20.000      | [Tokopedia](https://www.tokopedia.com/search?q=rfid+rc522) · [Shopee](https://shopee.co.id/search?keyword=rfid%20rc522)                                 |
| 31  | RTC DS3231 *(opsional)*                | I2C                         | 1     | Rp25.000 ~   | Rp25.000      | [Tokopedia](https://www.tokopedia.com/search?q=rtc+ds3231) · [Shopee](https://shopee.co.id/search?keyword=rtc%20ds3231)                                 |
| 32  | Adaptor                                | 5 V 2 A                     | 1     | Rp30.000 ~   | Rp30.000      | [Tokopedia](https://www.tokopedia.com/search?q=adaptor+5v+2a) · [Shopee](https://shopee.co.id/search?keyword=adaptor%205v%202a)                         |
| 33  | Step-down                              | LM2596 / MP1584             | 1     | Rp12.000 ~   | Rp12.000      | [Tokopedia](https://www.tokopedia.com/search?q=step+down+lm2596) · [Shopee](https://shopee.co.id/search?keyword=step%20down%20lm2596)                   |
| 34  | Baterai 18650 x2 + holder *(opsional)* | Li-ion                      | 1 set | Rp60.000 ~   | Rp60.000      | [Tokopedia](https://www.tokopedia.com/search?q=baterai+18650+holder) · [Shopee](https://shopee.co.id/search?keyword=baterai%2018650%20holder)           |
| 35  | Charger TP4056 *(opsional)*            | USB Type-C                  | 1     | Rp8.000 ~    | Rp8.000       | [Tokopedia](https://www.tokopedia.com/search?q=tp4056+type+c) · [Shopee](https://shopee.co.id/search?keyword=tp4056%20type%20c)                         |
|     | **Subtotal A4**                        |                             |       |              | **Rp213.000** |                                                                                                                                                         |

## A5. Alat Ukur dan Perkakas (per lab)

| No  | Alat                      | Spesifikasi                 | Jml   | Harga Satuan | Subtotal      | Link                                                                                                                                                                          |
|:---:|:------------------------- |:--------------------------- |:-----:| ------------:| -------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 36  | Multimeter digital        | Tegangan, arus, kontinuitas | 1     | Rp120.000 ~  | Rp120.000     | [Tokopedia](https://www.tokopedia.com/search?q=multimeter+digital) · [Shopee](https://shopee.co.id/search?keyword=multimeter%20digital)                                       |
| 37  | Logic analyzer            | USB 8 ch, 24 MHz            | 1     | Rp100.000 ~  | Rp100.000     | [Tokopedia](https://www.tokopedia.com/search?q=logic+analyzer+24mhz+8+channel) · [Shopee](https://shopee.co.id/search?keyword=logic%20analyzer%2024mhz%208%20channel)         |
| 38  | Osiloskop mini            | DSO138 atau sejenis         | 1     | Rp350.000 ~  | Rp350.000     | [Tokopedia](https://www.tokopedia.com/search?q=osiloskop+digital+mini) · [Shopee](https://shopee.co.id/search?keyword=osiloskop%20digital%20mini)                             |
| 39  | Solder + timah            | 30-60 W                     | 1     | Rp120.000 ~  | Rp120.000     | [Tokopedia](https://www.tokopedia.com/search?q=solder+set+60w) · [Shopee](https://shopee.co.id/search?keyword=solder%20set%2060w)                                             |
| 40  | Tang potong + kupas kabel | Set perkakas                | 1 set | Rp60.000 ~   | Rp60.000      | [Tokopedia](https://www.tokopedia.com/search?q=tang+potong+kupas+kabel+elektronik) · [Shopee](https://shopee.co.id/search?keyword=tang%20potong%20kupas%20kabel%20elektronik) |
|     | **Subtotal A5**           |                             |       |              | **Rp750.000** |                                                                                                                                                                               |

---

# Bagian B: Sensor dan Aktuator Tambahan

Komponen yang sering dipakai di proyek lanjutan. Semua harga adalah **perkiraan (~)** kecuali yang bertanda ✔.

## B1. Sensor Lingkungan

| No  | Komponen               | Kegunaan                             | Interface         | Perkiraan Harga     | Catatan ESP32                                       | Link                                                                                                                                                        |
|:---:|:---------------------- |:------------------------------------ |:-----------------:| -------------------:|:--------------------------------------------------- |:----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | BME280                 | Suhu, kelembapan, tekanan            | I2C               | Rp40.000 - 70.000   | 3,3 V, alamat 0x76/0x77                             | [Tokopedia](https://www.tokopedia.com/search?q=bme280) · [Shopee](https://shopee.co.id/search?keyword=bme280)                                               |
| 2   | AHT10 / AHT20          | Suhu dan kelembapan (alternatif DHT) | I2C               | Rp15.000 - 30.000   | 3,3 V                                               | [Tokopedia](https://www.tokopedia.com/search?q=aht20+modul) · [Shopee](https://shopee.co.id/search?keyword=aht20%20modul)                                   |
| 3   | MQ-2                   | Gas LPG, asap                        | Analog + digital  | Rp15.000 - 25.000   | Output 5 V, pakai pembagi tegangan; perlu pemanasan | [Tokopedia](https://www.tokopedia.com/search?q=sensor+gas+mq-2) · [Shopee](https://shopee.co.id/search?keyword=sensor%20gas%20mq-2)                         |
| 4   | MQ-135                 | Kualitas udara                       | Analog + digital  | Rp20.000 - 35.000   | Sama seperti MQ-2                                   | [Tokopedia](https://www.tokopedia.com/search?q=sensor+mq-135) · [Shopee](https://shopee.co.id/search?keyword=sensor%20mq-135)                               |
| 5   | MQ-7                   | Gas CO                               | Analog + digital  | Rp20.000 - 35.000   | Sama seperti MQ-2                                   | [Tokopedia](https://www.tokopedia.com/search?q=sensor+mq-7) · [Shopee](https://shopee.co.id/search?keyword=sensor%20mq-7)                                   |
| 6   | Sensor api (flame)     | Deteksi api                          | Analog + digital  | Rp5.000 - 10.000    | Aman di 3,3 V                                       | [Tokopedia](https://www.tokopedia.com/search?q=sensor+api+flame) · [Shopee](https://shopee.co.id/search?keyword=sensor%20api%20flame)                       |
| 7   | Sensor hujan           | Deteksi hujan                        | Analog + digital  | Rp8.000 - 15.000    | Aman di 3,3 V                                       | [Tokopedia](https://www.tokopedia.com/search?q=sensor+hujan+rain) · [Shopee](https://shopee.co.id/search?keyword=sensor%20hujan%20rain)                     |
| 8   | KY-038 / LM393         | Deteksi suara                        | Analog + digital  | Rp5.000 - 10.000    | Aman di 3,3 V                                       | [Tokopedia](https://www.tokopedia.com/search?q=sensor+suara+ky-038) · [Shopee](https://shopee.co.id/search?keyword=sensor%20suara%20ky-038)                 |
| 9   | BH1750                 | Intensitas cahaya (lux)              | I2C               | Rp15.000 - 25.000   | 3,3 V                                               | [Tokopedia](https://www.tokopedia.com/search?q=bh1750) · [Shopee](https://shopee.co.id/search?keyword=bh1750)                                               |
| 10  | Water level            | Level air sederhana                  | Analog            | Rp5.000 - 10.000    | Cepat korosi, nyalakan sesaat saat membaca          | [Tokopedia](https://www.tokopedia.com/search?q=sensor+water+level+arduino) · [Shopee](https://shopee.co.id/search?keyword=sensor%20water%20level%20arduino) |
| 11  | Soil moisture resistif | Kelembapan tanah (murah)             | Analog            | Rp5.000 - 10.000    | Cepat berkarat, tipe kapasitif lebih awet           | [Tokopedia](https://www.tokopedia.com/search?q=soil+moisture+sensor+yl-69) · [Shopee](https://shopee.co.id/search?keyword=soil%20moisture%20sensor%20yl-69) |
| 12  | Water flow YF-S201     | Debit air                            | Pulsa (interrupt) | Rp35.000 - 60.000   | Output 5 V, pakai pembagi tegangan                  | [Tokopedia](https://www.tokopedia.com/search?q=water+flow+sensor+yf-s201) · [Shopee](https://shopee.co.id/search?keyword=water%20flow%20sensor%20yf-s201)   |
| 13  | Turbidity              | Kekeruhan air                        | Analog            | Rp50.000 - 80.000   | Output hingga 4,5 V, pakai pembagi tegangan         | [Tokopedia](https://www.tokopedia.com/search?q=sensor+turbidity+arduino) · [Shopee](https://shopee.co.id/search?keyword=sensor%20turbidity%20arduino)       |
| 14  | TDS meter              | Kualitas air minum                   | Analog            | Rp70.000 - 120.000  | Gunakan pin ADC1                                    | [Tokopedia](https://www.tokopedia.com/search?q=sensor+tds+meter+arduino) · [Shopee](https://shopee.co.id/search?keyword=sensor%20tds%20meter%20arduino)     |
| 15  | Sensor pH + probe      | Keasaman air                         | Analog            | Rp150.000 - 300.000 | Perlu kalibrasi larutan buffer                      | [Tokopedia](https://www.tokopedia.com/search?q=sensor+ph+4502c+arduino) · [Shopee](https://shopee.co.id/search?keyword=sensor%20ph%204502c%20arduino)       |
| 16  | MAX6675 + termokopel K | Suhu tinggi (hingga 1000 °C)         | SPI               | Rp40.000 - 70.000   | 3,3 V                                               | [Tokopedia](https://www.tokopedia.com/search?q=max6675+thermocouple+k) · [Shopee](https://shopee.co.id/search?keyword=max6675%20thermocouple%20k)           |

## B2. Sensor Jarak, Gerak, dan Posisi

| No  | Komponen                     | Kegunaan                     | Interface           | Perkiraan Harga    | Catatan ESP32                                    | Link                                                                                                                                                        |
|:---:|:---------------------------- |:---------------------------- |:-------------------:| ------------------:|:------------------------------------------------ |:----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 17  | VL53L0X                      | Jarak laser (ToF) presisi    | I2C                 | Rp40.000 - 70.000  | 3,3 V                                            | [Tokopedia](https://www.tokopedia.com/search?q=vl53l0x) · [Shopee](https://shopee.co.id/search?keyword=vl53l0x)                                             |
| 18  | IR obstacle FC-51            | Deteksi halangan jarak dekat | Digital             | Rp5.000 - 10.000   | Aman di 3,3 V                                    | [Tokopedia](https://www.tokopedia.com/search?q=sensor+infrared+fc-51) · [Shopee](https://shopee.co.id/search?keyword=sensor%20infrared%20fc-51)             |
| 19  | TCRT5000                     | Line follower                | Analog + digital    | Rp5.000 - 10.000   | Aman di 3,3 V                                    | [Tokopedia](https://www.tokopedia.com/search?q=sensor+tcrt5000) · [Shopee](https://shopee.co.id/search?keyword=sensor%20tcrt5000)                           |
| 20  | Rotary encoder KY-040        | Putaran dan knob menu        | Digital (interrupt) | Rp8.000 - 15.000   | Gunakan interrupt                                | [Tokopedia](https://www.tokopedia.com/search?q=rotary+encoder+ky-040) · [Shopee](https://shopee.co.id/search?keyword=rotary%20encoder%20ky-040)             |
| 21  | Joystick                     | Kontrol 2 sumbu              | Analog + tombol     | Rp8.000 - 15.000   | Gunakan pin ADC1                                 | [Tokopedia](https://www.tokopedia.com/search?q=joystick+module+arduino) · [Shopee](https://shopee.co.id/search?keyword=joystick%20module%20arduino)         |
| 22  | ADXL345                      | Akselerometer 3 sumbu        | I2C / SPI           | Rp25.000 - 45.000  | 3,3 V                                            | [Tokopedia](https://www.tokopedia.com/search?q=adxl345) · [Shopee](https://shopee.co.id/search?keyword=adxl345)                                             |
| 23  | QMC5883L (GY-271)            | Kompas digital               | I2C                 | Rp20.000 - 35.000  | Banyak modul berlabel HMC5883L ternyata QMC5883L | [Tokopedia](https://www.tokopedia.com/search?q=gy-271+qmc5883l) · [Shopee](https://shopee.co.id/search?keyword=gy-271%20qmc5883l)                           |
| 24  | GPS NEO-6M                   | Lokasi dan waktu             | UART                | Rp70.000 - 120.000 | Uji di luar ruangan                              | [Tokopedia](https://www.tokopedia.com/search?q=gps+neo-6m) · [Shopee](https://shopee.co.id/search?keyword=gps%20neo-6m)                                     |
| 25  | Hall sensor KY-003 / A3144   | Deteksi magnet, hitung RPM   | Digital             | Rp5.000 - 10.000   | Aman di 3,3 V                                    | [Tokopedia](https://www.tokopedia.com/search?q=sensor+hall+ky-003) · [Shopee](https://shopee.co.id/search?keyword=sensor%20hall%20ky-003)                   |
| 26  | Reed switch module           | Deteksi pintu/magnet         | Digital             | Rp5.000 - 10.000   | Aman di 3,3 V                                    | [Tokopedia](https://www.tokopedia.com/search?q=reed+switch+module) · [Shopee](https://shopee.co.id/search?keyword=reed%20switch%20module)                   |
| 27  | Touch TTP223                 | Tombol sentuh kapasitif      | Digital             | Rp3.000 - 8.000    | Aman di 3,3 V                                    | [Tokopedia](https://www.tokopedia.com/search?q=touch+sensor+ttp223) · [Shopee](https://shopee.co.id/search?keyword=touch%20sensor%20ttp223)                 |
| 28  | Sensor getar SW-420          | Deteksi getaran              | Digital             | Rp5.000 - 10.000   | Aman di 3,3 V                                    | [Tokopedia](https://www.tokopedia.com/search?q=sensor+getar+sw-420) · [Shopee](https://shopee.co.id/search?keyword=sensor%20getar%20sw-420)                 |
| 29  | Keypad 4x4                   | Input angka/password         | Matriks 8 pin       | Rp8.000 - 15.000   | Butuh 8 GPIO                                     | [Tokopedia](https://www.tokopedia.com/search?q=keypad+4x4+membrane) · [Shopee](https://shopee.co.id/search?keyword=keypad%204x4%20membrane)                 |
| 30  | IR receiver VS1838B + remote | Kontrol remote IR            | Digital             | Rp5.000 - 15.000   | 3,3 V                                            | [Tokopedia](https://www.tokopedia.com/search?q=ir+receiver+vs1838b+remote) · [Shopee](https://shopee.co.id/search?keyword=ir%20receiver%20vs1838b%20remote) |

## B3. Sensor Daya, Beban, dan Biometrik

| No  | Komponen               | Kegunaan                | Interface      | Perkiraan Harga     | Catatan ESP32                                        | Link                                                                                                                                          |
|:---:|:---------------------- |:----------------------- |:--------------:| -------------------:|:---------------------------------------------------- |:--------------------------------------------------------------------------------------------------------------------------------------------- |
| 31  | INA219                 | Tegangan dan arus DC    | I2C            | Rp20.000 - 40.000   | 3,3 V                                                | [Tokopedia](https://www.tokopedia.com/search?q=ina219) · [Shopee](https://shopee.co.id/search?keyword=ina219)                                 |
| 32  | ACS712 (5A/20A/30A)    | Arus AC/DC              | Analog         | Rp20.000 - 35.000   | Output 5 V, pakai pembagi tegangan. ⚠️ Bahaya listrik | [Tokopedia](https://www.tokopedia.com/search?q=acs712+30a) · [Shopee](https://shopee.co.id/search?keyword=acs712%2030a)                       |
| 33  | ZMPT101B               | Tegangan AC             | Analog         | Rp25.000 - 45.000   | ⚠️ Bahaya listrik, wajib hati-hati                    | [Tokopedia](https://www.tokopedia.com/search?q=zmpt101b) · [Shopee](https://shopee.co.id/search?keyword=zmpt101b)                             |
| 34  | PZEM-004T v3           | Monitor daya AC lengkap | UART (Modbus)  | Rp100.000 - 180.000 | ⚠️ Bahaya listrik; aman jika dipasang benar           | [Tokopedia](https://www.tokopedia.com/search?q=pzem-004t+v3) · [Shopee](https://shopee.co.id/search?keyword=pzem-004t%20v3)                   |
| 35  | Load cell 5 kg + HX711 | Timbangan digital       | Serial 2 kabel | Rp35.000 - 60.000   | 3,3 V                                                | [Tokopedia](https://www.tokopedia.com/search?q=load+cell+5kg+hx711) · [Shopee](https://shopee.co.id/search?keyword=load%20cell%205kg%20hx711) |
| 36  | MAX30102               | Detak jantung dan SpO2  | I2C            | Rp40.000 - 80.000   | 3,3 V                                                | [Tokopedia](https://www.tokopedia.com/search?q=max30102) · [Shopee](https://shopee.co.id/search?keyword=max30102)                             |
| 37  | AD8232                 | EKG                     | Analog         | Rp90.000 - 150.000  | Hanya untuk edukasi, bukan alat medis                | [Tokopedia](https://www.tokopedia.com/search?q=ad8232+ecg) · [Shopee](https://shopee.co.id/search?keyword=ad8232%20ecg)                       |
| 38  | Fingerprint R307       | Sidik jari              | UART           | Rp120.000 - 200.000 | Untuk kunci pintu/absensi                            | [Tokopedia](https://www.tokopedia.com/search?q=fingerprint+r307) · [Shopee](https://shopee.co.id/search?keyword=fingerprint%20r307)           |

## B4. Aktuator

| No  | Komponen                      | Kegunaan                              | Interface        | Perkiraan Harga     | Catatan ESP32                                   | Link                                                                                                                                                                  |
|:---:|:----------------------------- |:------------------------------------- |:----------------:| -------------------:|:----------------------------------------------- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 39  | Stepper 28BYJ-48 + ULN2003 ✔  | Gerakan presisi (tirai, dispenser)    | 4 GPIO           | Rp17.250 (paket)    | Catu 5 V terpisah                               | [Tokopedia](https://www.tokopedia.com/search?q=stepper+28byj-48+uln2003) · [Shopee](https://shopee.co.id/search?keyword=stepper%2028byj-48%20uln2003)                 |
| 40  | NEMA17 + driver A4988         | Stepper torsi besar (CNC, 3D printer) | Step/Dir         | Rp100.000 - 180.000 | Butuh catu 12 V dan heatsink                    | [Tokopedia](https://www.tokopedia.com/search?q=nema17+a4988) · [Shopee](https://shopee.co.id/search?keyword=nema17%20a4988)                                           |
| 41  | Servo MG996R                  | Servo torsi besar (robot arm)         | PWM              | Rp50.000 - 90.000   | Catu 5-6 V eksternal, ground disambung          | [Tokopedia](https://www.tokopedia.com/search?q=servo+mg996r) · [Shopee](https://shopee.co.id/search?keyword=servo%20mg996r)                                           |
| 42  | PCA9685                       | Kontrol 16 servo/LED                  | I2C              | Rp30.000 - 50.000   | Catu servo terpisah                             | [Tokopedia](https://www.tokopedia.com/search?q=pca9685) · [Shopee](https://shopee.co.id/search?keyword=pca9685)                                                       |
| 43  | Driver TB6612FNG              | Driver motor efisien                  | PWM + dir        | Rp20.000 - 35.000   | Lebih hemat dari L298N                          | [Tokopedia](https://www.tokopedia.com/search?q=tb6612fng) · [Shopee](https://shopee.co.id/search?keyword=tb6612fng)                                                   |
| 44  | Driver BTS7960                | Motor DC arus besar (43 A)            | PWM              | Rp50.000 - 90.000   | Untuk motor berat                               | [Tokopedia](https://www.tokopedia.com/search?q=driver+motor+bts7960) · [Shopee](https://shopee.co.id/search?keyword=driver%20motor%20bts7960)                         |
| 45  | Relay 4 channel               | Kontrol beberapa beban                | Digital          | Rp25.000 - 40.000   | Pilih tipe optocoupler; beberapa aktif LOW      | [Tokopedia](https://www.tokopedia.com/search?q=relay+4+channel+5v+optocoupler) · [Shopee](https://shopee.co.id/search?keyword=relay%204%20channel%205v%20optocoupler) |
| 46  | Solid State Relay (SSR)       | Switching AC tanpa suara              | Digital          | Rp30.000 - 60.000   | ⚠️ Bahaya listrik, wajib hati-hati               | [Tokopedia](https://www.tokopedia.com/search?q=ssr+25da+solid+state+relay) · [Shopee](https://shopee.co.id/search?keyword=ssr%2025da%20solid%20state%20relay)         |
| 47  | Modul MOSFET IRF520 / IRLZ44N | Switching beban DC dengan PWM         | PWM              | Rp8.000 - 20.000    | IRF520 kurang ideal di 3,3 V, pilih logic-level | [Tokopedia](https://www.tokopedia.com/search?q=modul+mosfet+irlz44n) · [Shopee](https://shopee.co.id/search?keyword=modul%20mosfet%20irlz44n)                         |
| 48  | Solenoid valve 12 V           | Buka tutup aliran air                 | Via relay/MOSFET | Rp40.000 - 70.000   | Perlu dioda flyback                             | [Tokopedia](https://www.tokopedia.com/search?q=solenoid+valve+12v) · [Shopee](https://shopee.co.id/search?keyword=solenoid%20valve%2012v)                             |
| 49  | Solenoid door lock 12 V       | Kunci pintu elektronik                | Via relay/MOSFET | Rp50.000 - 90.000   | Cocok dengan RFID/fingerprint                   | [Tokopedia](https://www.tokopedia.com/search?q=solenoid+door+lock+12v) · [Shopee](https://shopee.co.id/search?keyword=solenoid%20door%20lock%2012v)                   |
| 50  | Kipas DC 5 V / 12 V           | Pendingin/ventilasi                   | Via MOSFET       | Rp10.000 - 25.000   | Bisa diatur dengan PWM                          | [Tokopedia](https://www.tokopedia.com/search?q=kipas+dc+5v+fan+mini) · [Shopee](https://shopee.co.id/search?keyword=kipas%20dc%205v%20fan%20mini)                     |
| 51  | Motor getar (vibration)       | Umpan balik haptic                    | Via transistor   | Rp3.000 - 8.000     | Pakai transistor + dioda                        | [Tokopedia](https://www.tokopedia.com/search?q=motor+getar+vibration+mini) · [Shopee](https://shopee.co.id/search?keyword=motor%20getar%20vibration%20mini)           |
| 52  | Pompa peristaltik             | Dosing cairan presisi                 | Via driver       | Rp40.000 - 80.000   | Cocok untuk nutrisi hidroponik                  | [Tokopedia](https://www.tokopedia.com/search?q=pompa+peristaltik+12v) · [Shopee](https://shopee.co.id/search?keyword=pompa%20peristaltik%2012v)                       |
| 53  | Buzzer pasif                  | Nada/melodi                           | PWM              | Rp2.000 - 5.000     | Bisa memainkan nada dengan LEDC                 | [Tokopedia](https://www.tokopedia.com/search?q=buzzer+pasif) · [Shopee](https://shopee.co.id/search?keyword=buzzer%20pasif)                                           |
| 54  | WS2812B (strip/ring)          | LED RGB addressable                   | 1 kabel data     | Rp30.000 - 80.000   | Data 3,3 V sering cukup; catu 5 V terpisah      | [Tokopedia](https://www.tokopedia.com/search?q=ws2812b+led+ring) · [Shopee](https://shopee.co.id/search?keyword=ws2812b%20led%20ring)                                 |

## B5. Display, Audio, dan Komunikasi

| No  | Komponen                        | Kegunaan                             | Interface | Perkiraan Harga    | Catatan ESP32                       | Link                                                                                                                                                                |
|:---:|:------------------------------- |:------------------------------------ |:---------:| ------------------:|:----------------------------------- |:------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 55  | TM1637 4 digit                  | Tampilan angka/jam                   | 2 pin     | Rp8.000 - 15.000   | Aman di 3,3 V                       | [Tokopedia](https://www.tokopedia.com/search?q=tm1637+4+digit) · [Shopee](https://shopee.co.id/search?keyword=tm1637%204%20digit)                                   |
| 56  | MAX7219 dot matrix 8x8 (4 in 1) | Running text                         | SPI       | Rp25.000 - 45.000  | Catu 5 V, data 3,3 V umumnya bisa   | [Tokopedia](https://www.tokopedia.com/search?q=max7219+dot+matrix+4+in+1) · [Shopee](https://shopee.co.id/search?keyword=max7219%20dot%20matrix%204%20in%201)       |
| 57  | LCD 20x4 + I2C                  | Tampilan teks lebih lebar            | I2C       | Rp60.000 - 90.000  | Backlight/logika 5 V                | [Tokopedia](https://www.tokopedia.com/search?q=lcd+20x4+i2c) · [Shopee](https://shopee.co.id/search?keyword=lcd%2020x4%20i2c)                                       |
| 58  | TFT 1.8" ST7735                 | Display warna kecil                  | SPI       | Rp40.000 - 70.000  | 3,3 V                               | [Tokopedia](https://www.tokopedia.com/search?q=tft+1.8+st7735) · [Shopee](https://shopee.co.id/search?keyword=tft%201.8%20st7735)                                   |
| 59  | TFT 2.4" ILI9341 (touch)        | Display warna + sentuh               | SPI       | Rp70.000 - 130.000 | 3,3 V                               | [Tokopedia](https://www.tokopedia.com/search?q=tft+2.4+ili9341+touch) · [Shopee](https://shopee.co.id/search?keyword=tft%202.4%20ili9341%20touch)                   |
| 60  | DFPlayer Mini                   | Pemutar MP3                          | UART      | Rp20.000 - 35.000  | Perlu microSD dan speaker           | [Tokopedia](https://www.tokopedia.com/search?q=dfplayer+mini) · [Shopee](https://shopee.co.id/search?keyword=dfplayer%20mini)                                       |
| 61  | ESP32-CAM                       | Kamera streaming                     | WiFi      | Rp70.000 - 110.000 | Butuh adaptor FTDI/programmer       | [Tokopedia](https://www.tokopedia.com/search?q=esp32-cam) · [Shopee](https://shopee.co.id/search?keyword=esp32-cam)                                                 |
| 62  | LoRa SX1278 (RA-02)             | Komunikasi jarak jauh tanpa internet | SPI       | Rp70.000 - 110.000 | 3,3 V; wajib pasang antena          | [Tokopedia](https://www.tokopedia.com/search?q=lora+sx1278+ra-02) · [Shopee](https://shopee.co.id/search?keyword=lora%20sx1278%20ra-02)                             |
| 63  | NRF24L01 + adaptor              | Komunikasi nirkabel 2,4 GHz          | SPI       | Rp15.000 - 30.000  | Sensitif tegangan; tambah kapasitor | [Tokopedia](https://www.tokopedia.com/search?q=nrf24l01+adaptor) · [Shopee](https://shopee.co.id/search?keyword=nrf24l01%20adaptor)                                 |
| 64  | MAX485 (RS485)                  | Komunikasi industri (Modbus)         | UART      | Rp8.000 - 15.000   | Pakai tipe 3,3 V atau level shifter | [Tokopedia](https://www.tokopedia.com/search?q=modul+max485+rs485) · [Shopee](https://shopee.co.id/search?keyword=modul%20max485%20rs485)                           |
| 65  | Level shifter 4 channel         | Konversi 3,3 V ↔ 5 V                 | -         | Rp5.000 - 10.000   | Sangat berguna untuk sensor 5 V     | [Tokopedia](https://www.tokopedia.com/search?q=level+shifter+4+channel+logic) · [Shopee](https://shopee.co.id/search?keyword=level%20shifter%204%20channel%20logic) |

### Tambahan yang Paling Direkomendasikan

| Prioritas | Komponen                                           | Alasan                               |
|:---------:|:-------------------------------------------------- |:------------------------------------ |
| 1         | Level shifter (B5 no. 65)                          | Semua sensor 5 V jadi aman dipakai   |
| 2         | BME280 (B1 no. 1)                                  | Lebih akurat dari DHT22              |
| 3         | Relay 4 channel (B4 no. 45) dan MOSFET (B4 no. 47) | Kontrol beban AC dan DC              |
| 4         | INA219 (B3 no. 31)                                 | Praktikum monitoring daya            |
| 5         | MQ-2, sensor api, buzzer pasif                     | Proyek sistem alarm                  |
| 6         | Stepper 28BYJ-48 (B4 no. 39)                       | Praktikum motor stepper, harga murah |

---

# Rekapitulasi Anggaran

| Kelompok                                                             | Estimasi      |
|:-------------------------------------------------------------------- | -------------:|
| A1. Komponen dasar                                                   | Rp177.000     |
| A2. Sensor                                                           | Rp178.000     |
| A3. Aktuator dan display                                             | Rp193.000     |
| A4. Penyimpanan, RFID, catu daya                                     | Rp213.000     |
| **Total per mahasiswa/kelompok (lengkap)**                           | **Rp761.000** |
| Dikurangi item opsional (BMP280, PIR, DS3231, baterai 18650, TP4056) | − Rp138.000   |
| **Total per mahasiswa/kelompok (tanpa opsional)**                    | **Rp623.000** |
| A5. Alat ukur dan perkakas (per lab, bukan per mahasiswa)            | Rp750.000     |

> Komponen di Bagian B bersifat tambahan, jadi tidak dimasukkan ke total di atas. Tambahkan sesuai proyek yang dipilih.

---

# Perangkat Lunak dan Dokumentasi

| No  | Nama                  | Fungsi                      | Link                                                                                                |
|:---:|:--------------------- |:--------------------------- |:--------------------------------------------------------------------------------------------------- |
| 1   | Arduino IDE           | Pemrograman ESP32           | [arduino.cc/en/software](https://www.arduino.cc/en/software)                                        |
| 2   | PlatformIO            | Alternatif IDE (VS Code)    | [platformio.org](https://platformio.org)                                                            |
| 3   | Arduino core ESP32    | Board package ESP32         | [github.com/espressif/arduino-esp32](https://github.com/espressif/arduino-esp32)                    |
| 4   | Dokumentasi Espressif | ESP-IDF dan referensi ESP32 | [docs.espressif.com](https://docs.espressif.com)                                                    |
| 5   | Datasheet ESP32       | Spesifikasi resmi           | [PDF Espressif](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf) |
| 6   | Driver CP210x         | USB-UART (CP2102)           | [silabs.com](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)                      |
| 7   | Wokwi                 | Simulator ESP32 online      | [wokwi.com](https://wokwi.com)                                                                      |
| 8   | Adafruit SSD1306      | Library OLED                | [GitHub](https://github.com/adafruit/Adafruit_SSD1306)                                              |
| 9   | DHT sensor library    | Library DHT11/22            | [GitHub](https://github.com/adafruit/DHT-sensor-library)                                            |
| 10  | ESP32Servo            | Library servo               | [GitHub](https://github.com/madhephaestus/ESP32Servo)                                               |
| 11  | MFRC522               | Library RFID RC522          | [GitHub](https://github.com/miguelbalboa/rfid)                                                      |
| 12  | PubSubClient          | Library MQTT                | [GitHub](https://github.com/knolleary/pubsubclient)                                                 |
| 13  | Mosquitto             | Broker MQTT lokal           | [mosquitto.org](https://mosquitto.org)                                                              |
| 14  | HiveMQ                | Broker MQTT cloud           | [hivemq.com](https://www.hivemq.com)                                                                |
| 15  | Node-RED              | Dashboard dan alur data IoT | [nodered.org](https://nodered.org)                                                                  |
| 16  | Blynk                 | Dashboard IoT mobile        | [blynk.io](https://blynk.io)                                                                        |
| 17  | ThingsBoard           | Platform IoT                | [thingsboard.io](https://thingsboard.io)                                                            |

---

# Catatan Penting dan Keselamatan

| Topik           | Penjelasan                                                                                                                                                    |
|:--------------- |:------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Level logika    | ESP32 bekerja di **3,3 V**. Sensor 5 V (misalnya pin Echo HC-SR04, output MQ) perlu pembagi tegangan atau level shifter                                       |
| ADC dan WiFi    | **Pin ADC2 tidak bisa dipakai saat WiFi aktif.** Gunakan pin ADC1 (GPIO 32-39) untuk sensor analog                                                            |
| Pin terlarang   | GPIO 6-11 terhubung ke flash internal dan **tidak boleh dipakai**                                                                                             |
| Catu daya motor | Jangan menyuplai motor/servo dari pin 3,3 V ESP32. Pakai catu daya terpisah dan **sambungkan ground bersama**                                                 |
| Listrik AC      | Komponen ACS712, ZMPT101B, PZEM-004T, dan SSR berhubungan dengan **220 V AC**. Kerjakan dengan pengawasan, jangan menyentuh rangkaian saat tersambung listrik |
| Sensor gas MQ   | Memakai elemen pemanas dengan arus cukup besar. Beri catu daya memadai dan tunggu beberapa menit sebelum membaca                                              |
| Cadangan        | Siapkan cadangan komponen murah (LED, resistor, jumper) dan 1-2 board ESP32 karena sering rusak atau hilang                                                   |
| Kualitas        | Komponen clone sangat bervariasi. Cek rating toko dan ulasan sebelum membeli                                                                                  |
