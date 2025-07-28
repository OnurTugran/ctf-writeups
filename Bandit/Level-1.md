# Level 1 ➜ Level 2

## Görev
**Level 2'ye geçmek için gizlenmiş dosyayı oku.**

## SSH ile Bağlantı
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```
- Password:
  ```bash
  ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
  ```
## Kullanılan Komutlar
```bash
ls -a
```
- **Dosya Konumunun içeriğini listeler (-a Gizli dizinleride listeler)**
```bash
cat ./-
```
- **Dosya içeriğini okur (Tek Başına cat - algılamaz [-] bit syntaxdır bu neden ile başına [./] Konur.) **

## Çözüm Adımları:
- 1- ssh bandit1@bandit.labs.overthewire.org -p 2220 ( Bağlantı kuruldu)
- 2- ls -a (Gizli dizin görünebilir)
- 3- cat ./- (Dosya içeriğini okur)

Password = 
```bash
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```
