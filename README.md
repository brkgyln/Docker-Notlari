# dockercommand 
- **docker ps** || çalışan contanierleri listelemek için 
- **docker ps -a** || tüm contanierleri listemek için docker stop [contanier_id] || çalışan contanieri durdurmak için 
- **docker rm [contanier_id]** || contanier silme işlemi
- **docker rmi** [imajin adi] 
- **dockercompose image** kullanıcak imaj adı ya da ID’si belirtilir. build Dockerfile’ın bulunduğu dizin belirtilir.(çalıştığımız dizin ile aynı konumda ise "." ile belirtilir.) 
- **dockerfile** default değeri Dockerfile ‘dır. Dosya ismi farklı ise ya da farklı bir dizinde ise bu anahtar kelime kullanılır. ports yönlendirme yapılacak portları belirtmek için kullanılır. volumes dosya dizinlerini ilişkilendirmek için kullanılır. Erişim modu da belirtilebilir. (ro: read only gibi) volumes_from diğer bir servisin veya konteynerin dosya dizinini eklemek için kullanılır. links bağlantı yapılacak konteynerleri belirtmek için kullanılır. command çalıştırılacak komutu belirtmek için kullanılır.

- **FROM** >temelde kullanılacak imaj belirtmek için 
- **MAINTAINER** > Dockerfile'ı oluşturan kişi bilgisi 
- **VOLUME** > dosya sistemine dizin eklemek 
- **RUN** > çalıştırılacak komutlar CMD RUN komutu gibi çalışır ama CMD parametresi alır. - ENTRYPOINT >container çalıştırılırken parametre verilerek çalıştırılmak istenirse kullanılır. 
- **ENV** > çevresel değişkenleri tanımlamak için kullanılır.
