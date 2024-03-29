# Philo 
Philo, felsefecilerin bir masanın etrafında oturduğu ve birlikte yemek yediği bir simülasyon programıdır.  
## İçindekiler  
1. [Proje Tanımı](#proje-tanımı) 
2. [Kurulum](#kurulum) 
3. [Kullanım](#kullanım)
## Proje Tanımı  
Philo, belirli sayıda felsefeciye sahip bir simülasyon programıdır. Her felsefeci, yemek yemek, düşünmek veya uyumak için farklı zaman dilimlerinde etkinliklerde bulunur. Ayrıca, her bir felsefeci bir çift çatala ihtiyaç duyar ve bu çataları diğer felsefecilerle paylaşır. Program, felsefecilerin durumlarını ve etkinliklerini zaman damgaları ile kaydeder ve belirli koşullar altında simülasyonu sonlandırır.  
## Kurulum  
Philo programını çalıştırmak için bilgisayarınızda C derleyicisi (gcc) ve geliştirme kütüphaneleri (pthread) gereklidir. Kurulum adımları şu şekildedir:  
1. Bu depoyu klonlayın: `git clone https://github.com/kullanici/philo.git` 
2. `philo` dizinine gidin: `cd philo` 
3. Programı derlemek için Makefile'ı kullanın: `make`  
## Kullanım  
Philo programını kullanmak için aşağıdaki komutu kullanabilirsiniz:

`./philo number_of_philosophers time_to_die time_to_eat time_to_sleep number_of_times_each_philosopher_must_eat(opsiyanel)`

Burada:  
- `number_of_philosophers`: Felsefecilerin sayısı ve aynı zamanda çatal sayısıdır. 
- `time_to_die`: Bir felsefeci, son yemeğinden veya simülasyonun başlamasından bu kadar milisaniye sonra yemek yemezse, ölür. 
- `time_to_eat`: Bir felsefeci yemek yemek için bu kadar milisaniye harcar. 
- `time_to_sleep`: Bir felsefeci bu kadar milisaniye uyur. 
- `number_of_times_each_philosopher_must_eat` (isteğe bağlı): Tüm felsefeciler en az bu kadar kez yemek yediğinde simülasyon durur.  