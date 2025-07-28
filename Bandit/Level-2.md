# Level 2 ➜ Level 3

## Görev
**Level 3'e geçmek için "spaces in this filename " adlı dizinde saklanıyor.**

## SSH ile Bağlantı
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
```
Password:
  ```bash
  263JGJPfgU6LtdEvgfWU1XP5yac29mFx
  ```
## Kullanılan Komutlar
```bash
ls
```
- **Dosya Konumunun içeriğini listeler.**
```bash
cat "spaces in this filename"
```
- **Dosya içeriğini okur (Tek Başına cat -.) **

## Çözüm Adımları:
- 1- ssh bandit2@bandit.labs.overthewire.org -p 2220 ( Bağlantı kuruldu)
- 2- ls -a (Gizli dizin görünebilir)
- 3- cat ./- (Dosya içeriğini okur)

Password =
```bash
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```
