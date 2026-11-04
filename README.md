# PhantomNode

Tanımı olmayan bağımlılık isimlerini toplar.

## Girdi

Bileşen → bağımlılıklar.

## Kullanım

Python 3.11+, standart kütüphane.

```sh
python phantomnode.py input.json
python verify.py
```

Dosya verilmezse stdin okunur. Sonuç stdout üzerinde JSON olarak yazılır. Girdi hatası çıkış kodu 2 üretir.

Örnek sonuç:

```json
[
  "auth"
]
```
