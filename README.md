# deepFace

Bu kod, "DeepFace" adlı bir Python kütüphanesini kullanarak bir resmin yüz analizini gerçekleştiriyor. Bu kütüphane, yüz tanıma, hissedarlık analizi, cinsiyet tahmini, yaş tahmini ve ırk tahmini gibi çeşitli yüz analizi görevlerini gerçekleştirmek için kullanılır.

İlk olarak, cv2 (OpenCV) kütüphanesi kullanılarak bir resim dosyası (images.jpg) okunur ve daha sonra matplotlib kütüphanesi kullanılarak bu resim ekranda gösterilir.

Sonrasında, DeepFace.analyze() fonksiyonu kullanılarak resmin yüz analizi yapılır. Bu fonksiyon, resimdeki yüzleri tanır ve çeşitli özellikleri (duygular, cinsiyet, yaş, ırk vb.) tahmin eder. Bu analiz sonuçları resp adlı bir değişkende saklanır.

Son olarak, analiz sonuçları ekrana yazdırılır.
