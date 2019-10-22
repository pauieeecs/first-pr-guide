
# İlk PR'ım (Pull Request)

### Github Desktop kullanarak ilk PR'ım

### Projeyi Forklama

<img align="right" width="300" src="assets/forking.png" alt="repoyu forklama" />

GitHubda, herhangi bir açık kaynak projenin kopyasını, kendi hesabımıza ekleyebiliriz.
Bu işleme **fork** denir.




## Projeyi Klonlama

<img align="right" width="300" src="assets/clon.png" alt="repoyu klonlama" />

<img align="right" width="300" src="assets/clon2.png" alt="repoyu klonlama 2" />

Artık projeyi forkladığımıza göre, üzerinde çalışmak için projeyi lokalimize çekmeli, yani dosyaları indirmeliyiz.
Bu işleme de **clone** denir.


## Yeni Branch'a Geçme

<img align="right" width="300" src="assets/newbranch.png" alt="yeni dal" />

<img align="right" width="300" src="assets/newbranc.png" alt="yeni dal 2" />

Geliştireceğimiz özellik veya yapacağımız işlem için, yeni bir branch'a geçmeliyiz.
Branch, aynı repo üzerinde, kendimizde özel bir dallanmadır.
Bu dalda geçerek, orjinal dala zarar vermeden veya başka birinin kodumuzu değişikliğe uğratma kaygısı olmadan çalışabiliriz.

Şimdi add_*kullanıcı_adınız* isimli bi branch oluşturup bu brancha geçelim:


## Gerekli değişiklikleri yapıp bu değişiklikleri commitleme

Artık tek yapmamız gereken kodda gerekli değişiklikleri yapmak.

    README.md dosyasının sonuna ekleyiniz.
    [@isminiz](https://github.com/isminiz "İsminiz")

<img align="right" width="300" src="assets/commit.png" alt="commit" />

Gerekli değişiklikleri istediğimiz herhangi bir text editörü veya IDE'de yaptıktan sonra, bu değişikikleri commitliyoruz.

Commitleri, kodun gelişim çizelgesindeki işaretlemelere benzetebilirsiniz.
Bu işaretler sayesinde nerde neyin yapıldığını inceleyebilir veya istersek bu işaretlemeler geri dönebiliriz.

Şimdi kullanıcı adımızı ve linkimizi ekleyip commitleyelim.
Commit mesajımıza ise "Add *kullanıcı_adınız* info" yazalım:



### Değişiklikleri GitHub'a Pushlama

<img align="right" width="300" src="assets/push.png" alt="push" />

Lokalimizde yaptığımız değişiklikleri GitHubdaki repomuza gönderebiliriz.
Bu gönderme işlemine ise **push** denir.

Değişikliklerimizi pushlayalım:


------------
### Pull Request (PR) Açma


<img align="right" width="300" src="assets/pr.png" alt="pr" />
<img align="right" width="300" src="assets/pr2.png" alt="pr" />

Artık tek yapmamız gereken, kendi forkumuzdaki branch'ı, orjinal repoyla birleştirmek.
Ama tabiki proje bizim olmadığı için bu işi pat diye yapamayız (Ama nazikçe isteyebiliriz :smile: ).
İşte bu nazik isteğe **pull request** denir.
İşin özünde, bizim forkumuzdaki branch ile ana projenin asıl branchını birleşitirmek istiyoruz k,i yaptığımız değişiklikler asıl projeyi de etkilesin.
Bu branch birleştirme işlemine ise **merge** denir (Hatta bu yüzden, bazı platformlar pull request'e *merge request* der).

Şimdi, ilk Pull Requestimizi açalım:

---
[@yunusemredilber](https://github.com/yunusemredilber "Yunus Emre Dilber")






