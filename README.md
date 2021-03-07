# usageOfWebpack

This is a simple explanation for Webpack.

**Webpack is a static module bundler.🚀**

# Webpack'in sağladığı bazı avantajlar :

🎯 Webpack,modern Javascript uygulamaları için üretilen bir modül paketleyicisidir.

🎯 Webpack sayesinde bir projede çok sayıda bulunan js dosyalarının birbirine importundan veya exportundan oluşturarak tek bir js dosyası haline getiririz.

🎯 Ve biz bu js dosyalarını index.html'e çevirdiğimiz zaman Webpack burada performansı arttırarak aslında istediğimiz zaman ```daha hızlı yükleme``` işlemini gerçekleştirecek.

🎯 Yani webpack ile ```performans kaybı önleniyor```,bu işlemler çok daha ```düzenli bir şekilde``` ve ```tek bir dosya halinde``` oluşturulabiliyor.

# npm run build ne işe yarıyor?

🎯 Öncelikle projemizde terminali açıp ```npm init``` komutunu çalıştırdığımızda ```package.json``` dosyamız oluşur.

🎯 Ve Webpack'in babel ile iletişime geçebilmesi için gerekli modülleri ```npm install @babel/core```,async ve await'in çalışması için ```npm install @babel/polyfill```, ES6'dan

sonra gelen standartları yüklemek için ```npm install @babel/preset-env``` şeklinde bir modül, Webpack ile babel arasındaki ilişi için ```npm install babel-loader``` komutunu

çalıştırırız.



