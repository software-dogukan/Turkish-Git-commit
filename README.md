Mkdir git_deneme ------ git_deneme diye bir klasör oluşturdu

Cd git_deneme ---- klasöre girer 

Git status -------- güncel git durumunu gösteriyor

Git init ---------- git kurulumunu yapıyoruz klasöre

Ls -la ------- gizli klasörleri görmek için

Rm -rf git_deneme --------- diyerek klasörü siler

Touch deeplearning.py --------- py uzantılı dosya oluşturdun

Git add deepleaarning.py----- dosyayı ekledin ama gite kaydetmedin sadece eklenecek diye belirttin

Git commit -m”first file creating” -------- commit attın ve mesaaj olarakta belirttin ne yaptığını her commit yaparken belirtmek zorundasın 

Git log ---------- bütün commitleri gösteriyor

Git add . ------- nokta koyarak her şeyi eklersin

Git commit -m”first line write”------ mesaj ekliyerek son add git yüklemiş olduk. 

Touch .gitignore ------ .gitignore dosyası oluşturduk çünkü gözükmesini istemediğimiz dosyaları buraya atacağız

.gitignore dosyaasına gidip görmesini istemediğimiz dosyanın uzantısıyla beraber yazıp kaydediyoruz.
Bu şekilde add yaptığımızda onu almayarak dosyaları ekleme yapar





GİT branch

Git branch ------ bütün dalları gösterir 

Git branch feature-------- feature adında bir dal oluştururuz

Git switch feature -------- feature dalına geçeriz

Branch değiştirdiğinde commit attığında masterda gözükmeyecektir

Git merge feature----------- branchleri birleştirdin master hepsini görebilecek.

Git stash ------- branch yaptığım bir şeyleri commit etmeden branch değiştirirsin 

Git stash pop ------ stash yaaptığımız değişiklikleri tekrar geri getirir commit edebilirsin daha sonra


GİT Geçmişe Dönme

Git restore backend.py ---- dediğinde son attığın commite geri dönüyor 

Git checkout ******************  ------- comitlerinde bulnunan kodu vererek istediğin commite geri dönebiliyorsun

Git switch master -------- checkout ile gittiğin commit sadece geçici olarak gidiyorsun master yine en son noktadır eğer istediğini yaptıysan bu comitte switch ile en son ki durumuna geri dönersin 

Git reset *********************************--------------------  commite gidiyor ve gittiğin commiten sonrakileri siliyor fakat diğer commitlerde yaptığın bütün her şey duruyor. Yani sadece commitleri siliyor proje olduğu gibi duruyor.

Git reset - -hard ******************* ------- bu sefer commitleride yaptığın işlemlerin hepsini silerek o comiite gidiyor

Git revert ******************--------------------- bu sefer yaptığımızda commitleri silmeden loglar duruyor ama projemizde o commit içeriğini siliyor istediğimiz taktirde log ile geri gelebiliyoruz.

Git diff --------------- committen sonra yaptığımız değişiklilikleri görmek için 

git diff ******************** ----- 2 farklı commit numarası verirsen iki commit arasında ne farklılıklar var onu gösterecektir.



GİT-GİTHUB

Git remote add origin http*******------- burada hangi repo olursa onu belirtiyoruz

Git push -u origin master ------------------ yaptığımızda giriş yapmamız gerekecek. Ve izin veriyorsunuz ve yüklemeleri yapıyoruz.

git config - - global user.name “Doğukan”---------------- kullanaıcı ismini Doğukan olarak değiştirdik
git config - - global user.email “alkn19063@gmail.com” --------- mail adresimizi gitde değiştiriyoruz bunu yapmamızın sebebi github kullanırken attığımız configleri githuba kim tarafından atıldığını anlamak adına yapılmaktadır

git push --------- direk yaptığımızda commitleri atıyoruz ek olarak aynı adaımları yapmamıza gerek kalmayacaktır.

Git push origin origin feat ----------- feat brench pushluyor origin dememiz aslında ilk remote yani kanalı aslında belirtiyoruz farklı repolarda olucaksan origin yerine farklı isimler kullana bilirsin ve isim vererek push yaparsın

Git fetch origin master------------- githubda yaptığımız değişiklikleri getiriyoruz ama getirdiğini gerçekleştirmek için

Git pull origin master ------ yaptığımızda açekitğimiz githubdaki değişikliği merge ediyor dosyamıza yani birleştiriyor kısaca github ile aynı olmuş oluyoruz

Git clone https****************------ verdiğimizde istediğimiz repoyu çekebiliyoruz

Fork yap repoyu githubdan kendi repona eklersin. Fork yaparak üzerindeki değişikliği githuba pushlaman için clonu fork sonrası yaptığında olur.
