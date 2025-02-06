# Geometric Problems

Bu proje çeşitli geometrik şekiller ve doğru parçaları ile ilgili işlemleri gerçekleştiren C++ sınıflarını içerir. Proje, Nokta, DoğruParçası, Daire ve Üçgen sınıflarını ve bu sınıfların çeşitli özelliklerini ve metotlarını içerir.

## 📋 Proje Açıklaması
Proje geometrik şekillerin ve doğru parçalarının çeşitli özelliklerini ve işlemlerini simüle etmek için tasarlanmıştır. Her sınıf ilgili geometrik şeklin veya doğru parçasının özelliklerini ve işlemlerini içerir.

## Sınıflar ve Özellikleri

### Nokta Sınıfı
- **Nesne Değişkenleri**: x ve y koordinatları (double tipinde)
- **Yapıcılar**:
  - Parametresiz yapıcı: Noktanın koordinatlarını orijine ayarlar.
  - Tek parametreli yapıcı: İki koordinata aynı değeri atar.
  - İki parametreli yapıcı: x ve y koordinatları için sırasıyla iki double değişken alır.
  - Başka bir noktayı alıp o noktanın bir kopyasını yeni nokta olarak üreten yapıcı.
  - Başka bir nokta ve iki double değişken alarak yeni bir nokta üreten yapıcı.
- **Metotlar**:
  - getX, getY, setX, setY: x ve y koordinatları için get ve set metotları.
  - set: Aynı anda iki koordinat alan ve noktanın x ve y koordinatlarının değerlerini değiştiren metot.
  - toString: Noktanın koordinatlarının String gösterimini döndürür.
  - yazdir: toString metodunu kullanarak ekrana koordinatları yazdırır.

### DoğruParçası Sınıfı
- **Nesne Değişkenleri**: İki nokta (Nokta nesnesi olarak)
- **Yapıcılar**:
  - İki uç noktayı Nokta nesnesi olarak alan yapıcı.
  - Başka bir DoğruParçası nesnesi alıp onun bir kopyasını yeni bir DoğruParçası nesnesi olarak oluşturan yapıcı.
  - Bir Nokta nesnesi, parçanın uzunluğu ve eğimi değerlerini alarak doğru parçasının uç noktalarını hesaplayan yapıcı.
- **Metotlar**:
  - get ve set metotları.
  - uzunluk: DoğruParçası nesnesinin uzunluğunu hesaplar ve döndürür.
  - kesişimNoktası: Bir Nokta nesnesini parametre olarak alır ve kesişme noktasını hesaplar.
  - ortaNokta: Doğru parçasının orta noktasını hesaplar ve döndürür.
  - toString: DoğruParçası nesnesinin String gösterimini döndürür.
  - yazdir: İki uç noktayı toString metodunu kullanarak ekrana yazdırır.

### Daire Sınıfı
- **Nesne Değişkenleri**: Merkez (Nokta nesnesi olarak) ve yarıçap
- **Yapıcılar**:
  - Merkez ve yarıçapı parametre olarak alan yapıcı.
  - Başka bir Daire nesnesi alıp onun bir kopyasını yeni bir Daire nesnesi olarak oluşturan yapıcı.
  - Başka bir Daire nesnesi ve pozitif bir x değeri alarak, yarıçapı x ile çarpılmış olarak kopyalayan yapıcı.
- **Metotlar**:
  - alan: Dairenin alanını döndürür.
  - cevre: Dairenin çevresini döndürür.
  - kesisim: Bir Daire nesnesi alır ve kesişim durumunu belirler.
  - toString: Dairenin merkezi ve yarıçapını String olarak döndürür.
  - yazdir: toString metodunu kullanarak ekrana bilgileri yazdırır.

### Üçgen Sınıfı
- **Nesne Değişkenleri**: Üç Nokta nesnesi
- **Yapıcılar**:
  - Üç Nokta nesnesi alan yapıcı.
- **Metotlar**:
  - get ve set metotları.
  - toString: Üçgenin String temsilini döndürür.
  - alan: Üçgenin alanını hesaplar ve döndürür.
  - cevre: Üçgenin çevresini hesaplar ve döndürür.
  - acilar: Üçgenin açılarını hesaplar ve döndürür.

## 🚀 Başlarken
Bu projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin.

### Kurulum
1. Repoyu klonlayın:
    ```bash
    git clone https://github.com/kullanici_adi/proje_adi.git
    ```
2. Proje dizinine gidin:
    ```bash
    cd proje_adi
    ```
3. Projeyi derleyin:
    ```bash
    g++ -o proje_adi main.cpp
    ```
4. Projeyi çalıştırın:
    ```bash
    ./proje_adi
    ```

## 🛠️ Kullanım
Proje, çeşitli geometrik şekiller ve doğru parçaları ile ilgili işlemleri gerçekleştiren sınıfları içerir. Her sınıfın metotlarını kullanarak ilgili işlemleri gerçekleştirebilirsiniz.

## 📄 Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.
