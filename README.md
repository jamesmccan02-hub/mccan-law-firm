# mccan-law-firm

## Google Tag Manager Integration

This site integrates Google Tag Manager (GTM) on all pages.

Replace the placeholder container ID in both snippets with your real GTM container ID.

- Placeholder used: `GTM-XXXXXXX`
- Real ID example: `GTM-ABCDE12`

### Snippets inserted

1) In the <head> of every HTML page, before </head>:

```html
<!-- Google Tag Manager -->
<script>
  (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
  new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
  j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
  'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
  })(window,document,'script','dataLayer','GTM-XXXXXXX');
</script>
<!-- End Google Tag Manager -->
```

2) Immediately after the opening <body> tag:

```html
<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-XXXXXXX"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->
```

### Files updated
- index.html
- about.html
- contact.html
- services.html
- privacy.html
- terms.html

After deployment, verify GTM is firing using the Tag Assistant Chrome extension or GTM Preview mode.
