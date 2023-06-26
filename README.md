# Test Halaman Detail

![preview](https://github.com/ihsanunot/halaman_simple_satu/assets/127992374/56423eff-dfb1-450a-9401-4c796417ec75)


Checkbox, Radio, Slider, InkWell, Form, and TextField are examples of stateful widgets. 

Stateful widgets subclass StatefulWidget.

The FavoriteWidget class manages its own state, so it overrides createState() to create a State object.

The _FavoriteWidgetState class stores the mutable data that can change over the lifetime of the widget,
---

The class also defines a build() method, which creates a row containing a red IconButton, and Text. 

You use IconButton (instead of Icon) because it has an onPressed property that defines the callback function (_toggleFavorite) for handling a tap.

About widget state:
https://docs.flutter.dev/ui/interactive#stateful-and-stateless-widgets

most common ways to manage state:

* The widget manages its own state
https://docs.flutter.dev/ui/interactive#self-managed
* The parent manages the widget’s state
https://docs.flutter.dev/ui/interactive#parent-managed
* A mix-and-match approach
https://docs.flutter.dev/ui/interactive#mix-and-match
---

ihsanunot
