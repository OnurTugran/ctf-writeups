# Level 4 ➜ Level 5

## Görev
**İnhere Klasörü İçindeki gizli dizimi bulmak.**

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
ls
```
- **Dizinleri listeler.**
```bash
cd inhere
```
- **Cd Komutu ile inhere klasörüne girer. **
```bash
ls -a
```
-**Gizli olan dizinler görüntülenir.**
```bash
cat ...Hiding-From-You
```
-**Hidding-From-You dizini okunur.**

## Çözüm Adımları:
- 1- ssh bandit3@bandit.labs.overthewire.org -p 2220 ( Bağlantı kuruldu.)
- 2- ls  (Dizin görünebilir.)
- 3- cd inhere (Klasöre girilir.)
- 4- ls -a (Gizli dizinleri gösterilir.)
- 5- cat ...Hiding-From-You  (Dosya içeriğini okur)
  
Password =
```bash
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```
