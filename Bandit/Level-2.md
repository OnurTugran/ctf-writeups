# Level 2 ➜ Level 3

## Görev
**Level 3'e geçmek için "spaces in this filename " adlı dizinde saklanıyor.**

## SSH ile Bağlantı
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
```
- password:
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

-- Şifre = 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
