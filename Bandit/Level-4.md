# Level 4 ➜ Level 5

## Görev
**Only-Human Readable dosyayı inhere klasöründe bul.**

## SSH ile Bağlantı
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
```
Password:
  ```bash
  2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
  ```
## Kullanılan Komutlar
```bash
ls -la
```
- **Gizli ve normal dizinleri detaylı listeler.**
```bash
file -- ./*
```
- **File komutu,dosyanın içeriğine bakar ve ne tür bir dosya sözyler. **
- **(--) - ile başlayan dosya adları için gereklidir yoksa komut sanar.**
- **(./*) Mevcut klasördeki tüm dosyaları ifade eder.**
```bash
cat ./-file07
```
-**File07 dosyasını okur.**

## Çözüm Adımları:
- 1- ssh bandit4@bandit.labs.overthewire.org -p 2220 ( Bağlantı kuruldu.)
- 2- ls -la (Gizli dizinler ve dizinler detaylı görünebilir.)
- 3-  file -- ./* (İle file isimli dosyaların içeriğinin ne olduğunu gösterir.)
- 4- ASCII text hangi dosyada yazıyor bakıyoruz.
- 5- cat ./-file07 ile dosyayı okutup şifremizi alıyoruz.
  
Password =
```bash
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```
