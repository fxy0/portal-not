Kurulum
============
Portal not formu modülünü, portal web uygulamasına eklemek için /portal dizininde bulunan composer.json dosyasına gidilerek, aşağıdaki kod parçaları repositories ve require kısımlarına eklenir. Portal dizininde composer update işlemi yapılarak modül yüklenir.


```
"repositories": [
.....
 {
            "type": "vcs",
            "url": "https://github.com/fxy0/portal-not.git"
 }
 ....
],

"require": {
        .....
        "kouosl/portal-not": "dev-master"
        
        .....
    },



```


Kullanıcı Paneli:http://portal.kouosl/not

![portal](https://user-images.githubusercontent.com/32413273/50727411-812d3400-112b-11e9-9baf-966cfa61df32.png)
![admin](https://user-images.githubusercontent.com/32413273/50727582-09143d80-112e-11e9-809c-4946712f710f.png)

