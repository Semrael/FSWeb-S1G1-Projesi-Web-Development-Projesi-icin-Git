# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir
   Merkezi olamayan bir sürüm kontrol sistemi ve yazılım geliştirme projelerinde dosyaların takibini sağlayan bir araçtır. GGit geliştiricilere kod tabanı geçmişini kaydetme iş birliği yapma ve projeleri yönetme imkanı sağlar.

2. Git ile GitHub arasında ne fark var?
   GitHUb git tabanlı projelerin barındırılabildiği bir web tabanlı platform.

3. Neden bir branch oluşturuyoruz?
   Ana kod tabanını etkilemeden kod yazmak içindir.

4. Pull Request'in amacı nedir?

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   Bir branch üzerinde yapılacn değişiklileri ana kod tabanına birleştirmek için diğer geliştiricilerden inceleme, geri bildirim ve onay almayı sağlayan mekanizma
   git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git merge: iki veya daha fazla branch'i birleştirmek için kullanılır.

git pull: uzak sunucudaki en son değişiklikleri çekmeyi ve yerel branch ile birleştirmeyi sağlar.

git fetch: uak sunucudaki en son değişiklikleri görüntülemek veya farklı bir branch ile çalışmak için kullanılır.

7. Merge conflict nedir?
   farklı branclerde yapılan çakışan(conflicting) değişikliklerin birleştirilmesi sırasında oluşan çakışmaları ifade eder.

8. Merge conflict'i nasıl çözeriz?
   çakışmaları elle düzenleyerek, çakışan kısımları çözerek ardından tekrar birleştirerek.
   tekrar birleştirme----
   --git add dosya-adı
   --git commit -m "Merge conflict çözüldü"
   --git push origin main
