﻿# java-Interview-Question
 
1)	What are static blocks and static initializers in Java ?

Static blok və ya static initializer-I biz static deyerlerimizi gostermek ucun istifade edirik ,
yəni eger blokun qarşısında static açar sözü varsa ozaman bu blok class cağrıldığı
zaman işə düıəcəkdir amma blokun qarşısında static açar sözü yoxdursa ozaman
onu işə düşməsi üçün biz blokun aid olduğu classin obyektini yaradaraq bu bloku işə sala bilərik.

2)	How to call one constructor from the other constructor ?

Eger eyni clasin icindeki 2 kostruktorun birinde digerini cagirmaq isteyirikse ozaman this();
methodundan istifade edirik yox eger extends etdiyimiz clasin construktorunu cagirmaq isteyirikse ozaman super(); methodundan istifade edirik .
Ve her zaman this() ve super() methodlari ilk setirde gosterilmelidirler :

3)	What is method overriding in Java ?

EGER BIZIM SUBCLASIMIZDA VE SUPERCLASIMIZDA Eyni adda (eyni tipde,eyni return tipinde )
method varsa ozaman deyirik ki, subclass superclasin methodunu overrideing edib.
Biz overridenig –I ozaman istifade edirik ki , supperclassin methodunun daxilini deyisdirerek
istifade etmek ucun amma bizim bu deyisikliklerimizin  superclassin methoduna hecbir tesiri olmasin.
