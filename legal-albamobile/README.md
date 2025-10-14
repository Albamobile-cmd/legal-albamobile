# AlbaMobile · Legal Pages
Bilingual legal pages for **A Contratiempo – by AlbaMobile**.

## Structure
```
/ES
  aviso_legal.html
  politica_de_privacidad.html
  politica_cookies.html
  terminos_de_uso.html

/EN
  legal_notice.html
  privacy_policy.html
  cookies_policy.html
  terms_of_use.html
```

## GitHub Pages
1. Go to **Settings → Pages**.
2. Source: **Branch = main** and **Folder = /(root)**.
3. Your site will be live at: `https://<your-user>.github.io/legal-albamobile/`

## Suggested URLs
- ES Privacy: `/ES/politica_de_privacidad.html`
- EN Privacy: `/EN/privacy_policy.html`

## In‑App linking (Flutter)
```dart
final langCode = Localizations.localeOf(context).languageCode.toUpperCase();
final privacyUrl = 'https://albamobile-cmd.github.io/legal-albamobile/$langCode/'
                   + (langCode == 'ES' ? 'politica_de_privacidad.html' : 'privacy_policy.html');
```

_Last updated: October 2025_
