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
