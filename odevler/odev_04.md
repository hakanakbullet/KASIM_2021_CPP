#### C dili tekrarı için sorulmaktadır. Aşağıdaki kod hakkında yorum yapınız. Bu kodda bir sentaks hatası var mı? Yok ise, bu kod çalıştırılırsa standart çıkış akımına ne yazılır? Bir derleyici ya da IDE kullanmadan yanıt veriniz.


```
#include <stdio.h>

int main()
{
	const int x = 55;
	int *ptr = (int *)&x;
	*ptr = 99;

	printf("x = %d\n", x);
}
```


[Ödevin cevabı](https://vimeo.com/432190808)
