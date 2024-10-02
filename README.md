# Postman_staj
# Staj Projesi - Postman Testleri

Bu proje, **Akım Metal Arge Merkezi**'nde staj sırasında yazdığım **Postman** test koleksiyonlarını ve entegrasyon sürecini içerir. Backend testleri **Postman** kullanılarak yazılmış ve **Newman CLI** aracı ile CI/CD süreçlerinde kullanıma hazır hale getirilmiştir.

## Gereksinimler

Bu projeyi kullanabilmek için aşağıdaki araçların sisteminizde kurulu olması gerekmektedir:

- [Node.js](https://nodejs.org/)
- [Postman](https://www.postman.com/)
- [Newman](https://github.com/postmanlabs/newman)

## Kurulum

1. Projeyi yerel makinenize klonlayın:

   ```bash
   git clone https://github.com/sedenuzumculer/staj.git
   cd staj
  

##newman yükleyin
 npm install -g newman

Testlerin Çalıştırılması

Postman Koleksiyonunu Çalıştırma
Postman testlerini Newman kullanarak kolayca çalıştırabilirsiniz. Koleksiyon ve ortam dosyalarını proje klasöründe bulabilirsiniz. Aşağıdaki komutları kullanarak testleri çalıştırın:

newman run ./collections/YourCollection.json -e ./environments/YourEnvironment.json

