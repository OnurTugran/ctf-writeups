# Level 5 ➜ Level 6

## Görev
**Bir sonraki seviyenin şifresi, inhere dizininin altında bir yerde bir dosyada saklanır ve aşağıdaki özelliklerin tümüne sahiptir:  
human-readable  
1033 bytes in size  
not executable**

## SSH ile Bağlantı
```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
```
Password:
  ```bash
  4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
  ```
## Kullanılan Komutlar
```bash
find inhere -type f -size 1033c ! -executable -exec file {} \; | grep "ASCII text"
```
- **Verdiği özellikleri Girip Hangi Dosyan konumunda buldum.**
```bash
cat ./.file2
```
- **./file2 Nin içini okumana yarar**
```bash
cat ./-file07
```
-**File07 dosyasını okur.**

## Çözüm Adımları:
- 1- ssh bandit5@bandit.labs.overthewire.org -p 2220 ( Bağlantı kuruldu.)
- 2- cd inhere (Gizli dizinler ve dizinler detaylı görünebilir.)
- 3- find inhere -type f -size 1033c ! -executable -exec file {} \; | grep "ASCII text" (İle  bize verdiği bilgileri girip bulduk.)
- 4- cat ./.file2 (İçini Okumak için)  
  
Password =
```bash
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```

