1. Bir sınıfın tüm özel üye işlevlerini listeleyiniz. İsimlerini İngilizce ifade ediniz .Bu işlevlerin derleyici tarafından yazılması durumunda (derleyicinin bu işlevleri *default* etmesi durumunda) bu işlevlerin parametrik yapılarını belirtiniz.

*T, U* ve *X* türler olmak üzere:

```
class Myclass {
public:
  //...
private:
  T t;
  U u;
  X x;
  
 };
 ```
 
Yukarıdaki *Myclass* sınıfı için derleyicinizin yazdığı tüm özel üye işlevleri derleyicinizin tanımladığı biçimde tanımlayınız.

2. Tanımladığınız bir sınıfı kopyalamaya kapatmak ancak taşımaya izin vermek istiyorsunuz? Bunu nasıl gerçekleştirebilirsiniz?  

3. Tanımladığınız bir sınıfı taşımaya kapatmak ancak kopyalamaya izin vermek istiyorsunuz? Bunu nasıl gerçekleştirebilirsiniz?  

4. Tanımladığınız bir sınıfı hem kopyalamaya hem de taşımaya kapatmak istiyorsunuz? Bunu nasıl gerçekleştirebilirsiniz?  

5. Bir özel üye işlevi *(special member function)* *private* yapmak ile onu *delete* etmek arasında ne farklar vardır?
