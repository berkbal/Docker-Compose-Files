# Docker-Compose Dosya Arşivi

Bu repo, Docker Compose kullanılarak hızlıca ayağa kaldırılabilecek hazır servis yapılarını içerir. Her `docker-compose.yml` dosyası açıklamalarla birlikte sunulmuştur, böylece hem yeni başlayanlar hem de ileri düzey kullanıcılar kolayca anlayabilir ve kendi ihtiyaçlarına göre özelleştirebilir.

## İçerik

Bu repoda farklı kullanım senaryolarına uygun birden fazla `docker-compose.yml` dosyası bulunmaktadır. Her biri belirli bir amaca hizmet eder. Dosyalar genellikle şu yapıyı içerir:

- Gerekli servis tanımları (örneğin: `web`, `db`, `redis`)
- Ağ ve hacim tanımları
- Ortam değişkenleri
- Sağlık kontrolleri
- Açıklayıcı yorum satırları

## Gereksinimler

Bu projeyi kullanmadan önce aşağıdaki yazılımların sisteminizde kurulu olduğundan emin olun:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Kullanım

1. Repoyu klonlayın:
   ```bash
   git clone https://github.com/berkbal/Docker-Compose-Dosya-Arsivi
   cd dizin
   ```
2. Kullanmak istediğiniz docker-compose.yml dosyasının bulunduğu dizine gidin.
3. `docker-compose up -d` komutu ile servisleri başlatabilirsiniz. Başlatmadan önce kendi sisteminize göre ayarlayıp, güçlü parolalar oluşturduğunuza emin olun. 
