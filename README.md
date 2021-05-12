# Flutter Catalog

An app showcasing Flutter components, with side-by-side source code view.

**🚀🚀 New: Flutter Catalog is now available in the browser! Check it out [here](https://x-wei.github.io/flutter_catalog/).**
And note there are some [limitations](https://github.com/X-Wei/flutter_catalog/issues/31#issuecomment-615964713) to the web variant.

## Screenshots

<img src="screenshots/Screenshot_1546722517.png" width="240px" />
<img src="screenshots/Screenshot_1541613187.png" width="240px" />
<img src="screenshots/Screenshot_1541613193.png" width="240px" />
<img src="screenshots/Screenshot_1541613197.png" width="240px" />
<img src="screenshots/Screenshot_1546722832.png" width="240px" />
<img src="screenshots/Screenshot_1546722852.png" width="240px" />


## How to contribute by adding a new example page

1. Create a dart file under `lib/route/` (or just duplicate a file, e.g. `cp widgets_icon_ex.dart new_example.dart`);
2. In the new file, create a class that extends MyRoute;
3. Add  constructor, the convention is to use the file path as constructor's default parameter;
4. (Optional) override getters: `title`, `description`, `links`;
5. Override `buildMyRouteContent()`, try to make the code simple, as it'll be shown on phone screens;
6. Open `lib/my_app_meta.dart`, import the new file at the beginning of file;
7. In `kMyAppRoutesStructure`, add an instantiation of the new class under the appropriate item group.

## Credits

This app is written with reference to many resources, including:

* Offical gallery app: https://github.com/flutter/flutter/tree/master/examples/flutter_gallery