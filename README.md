# kalitim
Python' da Class Oluşturma


Python' da bir obje oluşturacağımız zaman bunu şablon olarak sınıf yapılarıyla gerçekleştirebiliriz. Obje, bir sınıf örneğidir ve sınıf tarafından tanımlanan veri, fonksiyon ya da methot içerir. Sınıflar bize objeyi şekillendirmede veri ve methotların tanımlanmasına izin verir ayrıca, aynı karakteristikler ya da özellikler ile çoklu objeler yaratmak için kullanılır.

Örnek bir kod bloğu ile bunu inceleyelim:
```python
class Cat: # sınıfın tanımlanma şekli
    def __init__(self, isim, renk): #Cat sınıfına isim ve renk verilerini tanımladık
      self.isim=isim #atama
      self.renk=renk #atama
    
    def sesi(self): #sesi methodunu tanımladık
      print("miyav!")

benim_kedim= Cat("Maviş","Beyaz") #Cat sınıfından oluşan obje
print(benim_kedim.isim)
print(benim_kedim.renk)
benim_kedim.sesi()
```
