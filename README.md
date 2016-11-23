# Metro Ideas Project icons

Metro Ideas Project icons and markup reference.

## Logo

Includes standard logo, inverse logo with white fill on transparent background, and a social media avatar.

[Markup for SVG and image fallback](https://css-tricks.com/a-complete-guide-to-svg-fallbacks/):

``` html
<object type="image/svg+xml" data="/logo/logo.svg">
    <img src="/logo/logo.png" alt="Metro Ideas Project logo">
</object>
```

``` css
.logo {
    background: url(/logo/logo.png);
    background: url(/logo/logo.svg), linear-gradient(transparent, transparent);
}
```

## Favicon

Icons and markup via [Favicon Generator](http://realfavicongenerator.net):

``` html  
<link rel="apple-touch-icon" sizes="180x180" href="/favicon/apple-touch-icon.png">  
<link rel="icon" type="image/png" href="/favicon/favicon-32x32.png" sizes="32x32">  
<link rel="icon" type="image/png" href="/favicon/favicon-16x16.png" sizes="16x16">  
<link rel="manifest" href="/favicon/manifest.json">  
<link rel="mask-icon" href="/favicon/safari-pinned-tab.svg" color="#5bbad5">  
<link rel="shortcut icon" href="/favicon/favicon.ico">  
<meta name="msapplication-config" content="/favicon/browserconfig.xml">  
<meta name="theme-color" content="#ffffff">  
```