# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git bir versiyon kontrol sistemi olarak geçer. Git kullanarak, herhangi bir projenin herhangi bir adımında ilgili projenin kopyasını oluşturabilir, daha sonra gerektiğinde bu kopyalara dönebiliriz.


2. Git ile GitHub arasında ne fark var?

GitHub aslında kullanıcılara web tabanlı bir repo olanağı sağlar. Git'in tüm özellikleri GitHubta da vardır. GitHub'ta ekstradan kendi özellikleri de bulunur. Kullanıcılar online ortamda birlikte çalışma fırsatı yakalar.

3. Neden bir branch oluşturuyoruz?

Elimizde bulunan esas kodun üzerinde bir değişiklik yapmak istediğimizde ve esas kodun bir kopyası üzerinde çalışabilmemizi ve test edebilmemizi sağlar. Sonrasında esas kod ile birleştiririz.

4. Pull Request'in amacı nedir?

Güncellemesini tamamlayan developerın bu güncellemeyi diğer ekip arkadaşları ile paylaşmasını sağlar. Tüm ekip için ilgili kod ile çalışan herkesin bu güncellemeyi inceleyip main branchle birleştirmeleri gerektiğini bildirir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Terminalde git chechout komutunu girerek main branchimize geçebiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

fetch işlemi yapılan güncellemeyi update eder fakar merge etmez. git pull ise önce fetch eder, sonra merge eder.

7. Merge conflict nedir?

birleşme çakışması aslında birleştirilen ögenin aynı satırında iki ayrı kişinin farklı değişiklik yapması durumda oluşur ve bilgisayar bize hangi güncellemenin alınması gerektiğini sorar.

8. Merge conflict'i nasıl çözeriz?

her iki güncellemeyi de içeren yeni bir kod yazıp o şekilde kaydederiz.
