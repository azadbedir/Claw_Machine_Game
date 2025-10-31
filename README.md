# 🕹️ Pixel Claw Machine

## 🎯 Proje Hakkında

Bu proje, HTML, CSS ve JavaScript kullanılarak oluşturulmuş, etkileşimli, piksel sanat tarzında bir **Pençe (Claw) Makinesi** oyunudur. Kullanıcılar, makinenin pençesini hareket ettirerek içerideki sevimli oyuncakları yakalamaya çalışabilirler. Oyun, gerçek bir arcade makinesinin mekanik hareketlerini ve deneyimini taklit etmeyi amaçlamaktadır.

## ✨ Özellikler

* **Piksel Sanat Stili:** Tüm makine ve oyuncaklar için `image-rendering: pixelated;` ve özel hazırlanmış sprite resimleri kullanılarak nostaljik bir piksel sanat görünümü elde edilmiştir.
* **İnteraktif Kontroller:** Yatay ve dikey hareketler için aktifleşen düğmeler (`.hori-btn`, `.vert-btn`) ile pençe kontrolü.
* **Gerçekçi Mekanik:**
    * Pençenin yatay ve dikey hareketleri.
    * Pençenin inme, kapanma (yakalama/kaçırma), yükselme ve bırakma animasyonları.
    * Yakalama mantığı (`getClosestToy` fonksiyonu ile).
* **Oyuncak Koleksiyonu:** Başarıyla yakalanan oyuncaklar, makinenin altındaki koleksiyon kutusuna (`.collection-box`) eklenir.
* **Çeşitli Oyuncaklar:** Ayı, tavşan, golem, salatalık, penguen ve robot gibi farklı türde oyuncaklar mevcuttur.

## 🛠️ Kurulum

Bu proje herhangi bir derleme aracı gerektirmez. Projeyi çalıştırmak için aşağıdaki adımları izleyin:

1.  Proje dosyalarını ( `index.html`, `style.css`, `script.js` ve resim dosyalarını) yerel bilgisayarınıza indirin.
2.  `index.html` dosyasını tercih ettiğiniz herhangi bir web tarayıcısında açın.

## 🎮 Nasıl Oynanır?

1.  **Yatay Hareket:** Makine üzerindeki **yatay düğmeye** tıklayarak pençeyi sağa doğru hareket ettirin. Düğmeyi bıraktığınızda hareket durur.
2.  **Dikey Hareket (İndirme):** Yatay hareket bittiğinde, **dikey düğme** aktifleşir. Bu düğmeye basılı tutarak pençeyi makinenin içine doğru hareket ettirebilirsiniz.
3.  **Yakalama/Bırakma:** Dikey düğmeyi bıraktığınızda, pençe otomatik olarak aşağı iner, kapanır (oyuncak yakalamaya çalışır) ve tekrar yukarı çıkar.
4.  **Koleksiyon:** Pençe yakaladığı oyuncağı başlangıç noktasına geri getirir ve makinenin sağ altındaki toplama alanına bırakır. Başarılı bir yakalamadan sonra oyuncak koleksiyon kutusunda görünür.
5.  **Tekrar Oynama:** Oyuncak bırakıldıktan sonra, yatay düğme tekrar aktifleşir ve yeni bir deneme yapabilirsiniz.

## 💻 Kullanılan Teknolojiler

* **HTML5** (Yapılandırma)
* **CSS3** (Stil ve Animasyonlar, özellikle piksel görünümü ve hareket geçişleri için `transition` kullanılmıştır.)
* **JavaScript (ES6+)** (Oyun mantığı, pençe hareketi, çarpışma tespiti ve DOM manipülasyonu için)

## 👤 Yazar

[Azad Bedir]

---

Daha fazla detay veya kişiselleştirme için **`script.js`** ve **`style.css`** dosyalarını inceleyebilirsiniz.
