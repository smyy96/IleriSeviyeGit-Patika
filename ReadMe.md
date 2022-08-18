# Git Komutları
```
• git status   =>   değişiklik yapılan dosyayı gösteriyor

• git log   =>   yapılan commitlerin listesini verir.

• git commit --amend   =>   bir önceki yaptıgın commitle ilgili değişiklik yapmak istenirse 
kullanılır.

• git commit --amend -m "degiştirilecek mesaj"  =>  bir önceki yaptıgın commitin açıklamasını 
degiştirmek istiyorsan kullanılır.

• git revert commit_id  =>  git log ile commitimizin idsini alıp revert yaptıgımız zaman o 
commiti geri alıyor. yanlışlıkla commit işlemi yaparsak eğer.

• git reset -- hard commit_id  =>  yapılan bütün revertleri kaldırır eski haline gelir.

• git diff commit_id..baskabircommit_id readme.md  =>  readme deki verilen iki commit arasında 
yapılan degişiklikleri gösterir.
```