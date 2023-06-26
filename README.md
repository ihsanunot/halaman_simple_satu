# Belajar Flutter Layout

- Identifikasi Row dan Column yang dibutuhkan
- Cek apa layout nya termasuk Grid?
- Cek Ada Elemen yang Overlapping atau tidak
- Apakai UI nya butuh Tabs?
- perhatikan area yang membutuhkan alignment, padding, or borders.

## Catatan

```
        // BAGIAN UTAMA HALAMAN !
        body: Column(
          children: [
            Image.asset(
              'images/gambar1.jpg',
              width: 600,
              height: 240,
              fit: BoxFit.cover,
            ),
            titleSection,
            buttonSection,
            textSection,
          ],
          // body pakai Column terus children biar bisa masukin beberapa widget mirip component lego
          // di dalam children kita berurutan section nya
```
<br>
Checkbox, Radio, Slider, InkWell, Form, and TextField are examples of stateful widgets. 

Stateful widgets subclass StatefulWidget.

The FavoriteWidget class manages its own state, so it overrides createState() to create a State object.

The _FavoriteWidgetState class stores the mutable data that can change over the lifetime of the widget,
---

The class also defines a build() method, which creates a row containing a red IconButton, and Text. 

You use IconButton (instead of Icon) because it has an onPressed property that defines the callback function (_toggleFavorite) for handling a tap.

https://docs.flutter.dev/ui/interactive#stateful-and-stateless-widgets

most common ways to manage state:

The widget manages its own state
https://docs.flutter.dev/ui/interactive#self-managed
The parent manages the widget’s state
https://docs.flutter.dev/ui/interactive#parent-managed
A mix-and-match approach
https://docs.flutter.dev/ui/interactive#mix-and-match
---