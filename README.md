# java-Interview-Question
 
1)	**What are static blocks and static initializers in Java ?

Static blok və ya static initializer-I biz static deyerlerimizi gostermek ucun istifade edirik ,
yəni eger blokun qarşısında static açar sözü varsa ozaman bu blok class cağrıldığı
zaman işə düıəcəkdir amma blokun qarşısında static açar sözü yoxdursa ozaman
onu işə düşməsi üçün biz blokun aid olduğu classin obyektini yaradaraq bu bloku işə sala bilərik.

2)	**How to call one constructor from the other constructor ?

Eger eyni clasin icindeki 2 kostruktorun birinde digerini cagirmaq isteyirikse ozaman this();
methodundan istifade edirik yox eger extends etdiyimiz clasin construktorunu cagirmaq isteyirikse ozaman super(); methodundan istifade edirik .
Ve her zaman this() ve super() methodlari ilk setirde gosterilmelidirler :

3)	**What is method overriding in Java ?

EGER BIZIM SUBCLASIMIZDA VE SUPERCLASIMIZDA Eyni adda (eyni tipde,eyni return tipinde )
method varsa ozaman deyirik ki, subclass superclasin methodunu overrideing edib.
Biz overridenig –I ozaman istifade edirik ki , supperclassin methodunun daxilini deyisdirerek
istifade etmek ucun amma bizim bu deyisikliklerimizin  superclassin methoduna hecbir tesiri olmasin.

4) **What is super keyword in java ?

super acar sözü superclass-a refrans göstərir yəni
super açar sözü subcllass və superclass da olan eyni adlı metodulardan superclassin metodunu çağırmaq istədikdə istifadə edirik.
və hər zaman super acarsözü metodun ilk sətirində olmalıdır.

5) **Difference between method overloading and method overriding in java ?

* Overloading bir class daxilində baş verir amma Overriding 2 class(subclass və superclass) arasinda baş verir .
* Overloading bir class daxilində baş vrdiyi üçün miras almaq (inheritance) ilə əlaqəli deyil 
  amma Overriding 2 class(subclass və superclass) arasinda baş erdiyi üçün miras almaq (inheritance) ilə əlaqəlidir.
* Overloading-də return tiplər eyni olmaqi vacib deyil amma Overriding-də return tiplər eyni olmalıdır.
* Overloading-də metodun qəbul etdiyi parametrlər fərqli olmalidir amma Overriding-də parametrlər eyni olmalıdır.
* Overloading-də bir metod digərini gizlədə bilmir amma Overriding-də subclass-ın metodu superclass-ın eyni adlı metodunu gizlədir.

6) **Difference between abstract class and interface ?

* Abstract class abstract və abstract olmayan metodlardan ibarətdir amma
İnterface isə ancaq abstract metodlardan ibarətdir (amma Java 8-dən bəri İnterface-ə default və static metodlarda yaratmaq oldu və 
Java 9-dan bəri privite metodlarda yaratmaq oldu.

* Abstract class da static, non-static, final, non-final deyerlər ola bilər amma
İnterface-də yalnız final və static dəyərlər ola bilər 

* Abstract class-ı miras almaq üçün extend açar sözündən istifadə edilir ,
İnterface-i miras lmaq üçün implement açar sözündən istifadə edilir 

* Abstract class çoxlu miras almani(multiple inheritance) dəstəkləmir amma İnterface dəstəkləyir

7) **Why java is platform independent?

* Java msüteqil platormadır çünki JVM(Java Virtual Machine) istifadə edir və 
JVM vasitəsi ilə java bytecodları butun platformalarda çalışdırmaq olar.

8) **What is method overloading in java ?

* Overloading bir class daxilində eyni ada mexsus amma muxtelif parametrlər qəbul edən metodlar varsa buna Overloading deyilir.
* Overloading olunmus metodu daxil etdikdə Java ilk öncə metodun adını sonra inputlarin sayını və daha sonra inputların tiplərini yoxlayır.

9) **What is difference between c++ and Java ?

* Java müstəqil platformadır amma C++ aslı bir platformadır.

10) **What is JIT compiler ?

* JİT (Java-in-Time) Bytecodalar(.class) JVM vasitəsilə oxunulur və osonra JİT vasitəsi ilə bu kodlar native code-a (machine-readable code) çevrilir və bunun sayəsində daha yuksək prformasa nail olmuş olunur və zamana qənaət edilir və s.

11) **What is bytecode in java ?

* 
