# odev1_2kume
1-)Algoritmanın Amacı ne için kullanıldığı/kullanılabileceği:
Bu programın amacı, verilen bir dizinin iki alt kümesine bölünebilir olup olmadığını belirlemektir. Bu amaçla, dinamik programlama yöntemi kullanılmıştır.

Program, kullanıcının girdiği bir tam sayı dizisini ikiye bölünebilirlik kriterlerine göre kontrol eder. Eğer toplamı çift sayı değilse, dizi ikiye bölünemez
ve program sonlandırılır. Daha sonra, dizinin elemanlarını iki alt kümeye ayırarak her iki alt kümeye ait toplamların eşitliği kontrol edilir. Bu işlem dinamik
programlama yöntemiyle yapılır.

Bu program, maliyet optimizasyonu gibi alanlarda kullanılabilir. Örneğin, bir işin yapılması için belirli bir kaynağın iki farklı alt kümeye ayrılması gerekiyorsa,
bu program, kaynağın uygun şekilde ayrılabilir olup olmadığını belirleyebilir. Benzer şekilde, bu program, kaynakların iki alt küme arasında nasıl paylaştırılacağına 
karar verirken işbirliği yapmak zorunda olan iki grup arasındaki kaynak bölüşümünün adil olup olmadığını belirlemek için de kullanılabilir.

2-)Programın çalışma şekli :
Bu program, kullanıcının girdiği bir dizinin iki alt kümesine bölünebilir olup olmadığını belirlemek için dinamik programlama yöntemini kullanır. 
Aşağıdaki şekilde programın çalışma şekli özetlenmiştir:


Kullanıcıya, dizinin eleman sayısı sorulur ve girilen sayıya göre bir dizi oluşturulur.
Kullanıcıdan, dizinin elemanlarını tek tek almaları istenir ve her bir eleman, dizinin ilgili indisine atanır.
Dizinin elemanlarının toplamı alınarak, toplamın çift sayı olup olmadığı kontrol edilir. Eğer toplam çift sayı değilse, dizi ikiye bölünemez ve program sonlandırılır.
Eğer toplam çift sayı ise, dinamik programlama yöntemi kullanılarak, dizinin elemanlarının iki alt kümesine bölünebilirliği kontrol edilir.
Bu amaçla, öncelikle bir boolean tipinde iki boyutlu bir dizi oluşturulur ve her bir elemanı false olarak atanır.
Ardından, iki alt kümenin eşit toplama sahip olup olmadığı, dizinin elemanlarının iki alt kümede nasıl dağıtılacağı sorununu bir alt problem olarak ele alınarak,
alt kümelerin toplamlarının eşit olup olmadığına karar vermek için dinamik programlama yöntemi kullanılır.
Bu işlem, alt küme elemanlarının toplamlarının eşit olup olmadığını kontrol etmek için alt kümelerin her birindeki elemanların toplamı hesaplanarak yapılır.
Program, son olarak, dizinin iki alt küme olarak bölünebilir olup olmadığını belirler ve sonuca göre ekrana bir mesaj yazdırır.
Programın genel olarak çalışma şekli bu şekildedir.
