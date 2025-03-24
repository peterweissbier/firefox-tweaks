## disable builtin translation tool

* about:config and set both to false

* browser.translations.automaticallyPopup

* browser.translations.enable

* alternative plugin: 
* https://github.com/FilipePS/Traduzir-paginas-web

## remove "sign in with google" prompt

  1. install uBlock Origin
  2. select gear icon, select Import and append the following, apply changes

||id.google.com^

||accounts.google.com/gsi/$3p

||smartlock.google.com^

! Block "Sign in with Google" iframe in top right corner of websites ||accounts.google.com/gsi/iframe 
