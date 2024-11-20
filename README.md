## disable builtin translation tool

about:config and set both to false

browser.translations.automaticallyPopup

browser.translations.enable

alternative less intrusive plugin: 
https://github.com/FilipePS/Traduzir-paginas-web

## add custom search engine

about:config and set to true by clicking on the + to the right

browser.urlbar.update2.engineAliasRefresh

## template for custom search engines

https://sitehere.com/search/?q={searchTerms}

## remove "sign in with google" prompt

1. install uBlock Origin
2. select gear icon, select Import and append the following, apply changes

||id.google.com^

||accounts.google.com/gsi/$3p

||smartlock.google.com^

! Block "Sign in with Google" iframe in top right corner of websites ||accounts.google.com/gsi/iframe 
