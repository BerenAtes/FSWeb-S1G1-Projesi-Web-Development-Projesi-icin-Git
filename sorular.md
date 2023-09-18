# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
   Git, açık kaynak kodlu,güncellemeleri kaydeden, kodlara erişim sağlayan ve bir kod üzerinde birden çok kişiye çalışma olanağı sunan bir sistemdir.

2. Git ile GitHub arasında ne fark var?
   Git yukarıda anlatılan olanakları sunan sistem iken Github bu imkanları kullanarak Git sistemi ile projelerimizi paylaşabildiğimiz,
   depolayabildiğimiz bir portaldır.

3. Neden bir branch oluşturuyoruz?
   Projede yaptığımız çalışma ile projemizi olumsuz etkilememek adına projeyi bozmamak için kullanırız.Projenin kopyası üzerinde çalışmak gibi düşünebiliriz.

4. Pull Request'in amacı nedir?
   Pull request olarak gönderdiğimizde projede çalışan başka biri için değişiklik yaptığımızı belli ederiz ve bu değişikleri kişiler kendi projelerine merce edebilirler.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   'git checkout' komutu ile branch değiştirebiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
   'git fetch' uzaktaki deponun dosyalarını local depoya kopyalar,'git merge' çatallanmış geçmişi bir araya getirme yöntemidir,'git pull' remotedeki değişiklikleri local projemize almamızı sağlar.
7. Merge conflict nedir?
   Çakışmadır.Aynı anda aynı dosyadaki aynı satır başka kişiler tarafından değiştirilirse bu durum ortaya çıkar.
8. Merge conflict'i nasıl çözeriz?
   İlk olarak merge conflict tespit edilmeli ve daha sonra bu kısımlar manuel olarak düzeltilerek tekrar mergelenmeli.
