# IVUBUS.pl — strona na GitHub Pages

## Pliki
- `index.html` — cała treść strony i kod widgetu EasyRent
- `style.css` — wygląd strony
- `assets/busy-ivubus.jpg` — zdjęcie busów
- `CNAME` — domena `ivubus.pl`

## Publikacja na GitHub Pages
1. Utwórz nowe repozytorium, np. `ivubus-site`.
2. Wrzuć do repo wszystkie pliki z tego folderu.
3. Wejdź w `Settings → Pages`.
4. Ustaw `Deploy from a branch`, branch `main`, folder `/root`.
5. W sekcji `Custom domain` wpisz `ivubus.pl`.
6. U operatora domeny ustaw DNS pod GitHub Pages.

## Widget EasyRent
W `index.html` jest już wstawiony widget dla auta z ID `1565`:

```html
<div id="widget-easyrent-1565"></div>
```

W skrypcie podmieniono placeholdery z panelu EasyRent:
- `SELECTOR` → `"#widget-easyrent-1565"`
- `CARID` → `1565`

Przy kolejnych busach najlepiej wygenerować osobny kod w panelu EasyRent i wkleić nowy widget albo zmienić obecny kod według instrukcji panelu.
