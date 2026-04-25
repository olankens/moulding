<hr>

<div align="center">
  <p><img src="assets/icon.png" width="128"/></p>
  <h1>FLUTTER</h1>
  <p>Laborum qui natus adipisci mollit ex labore esse ipsa voluptas beatae ducimus quaerat consectetur irure architecto non eius totam explicabo amet fugiat enim duis eiusmod similique doloremque occaecati dolorem modi incidunt blanditiis adipiscing excepturi quibusdam ab eaque commodo deserunt aliquip et assumenda incididunt temporibus tempor vitae maxime aperiam consequuntur nostrud iste quia cupidatat.</p>
</div>

<hr>

<p align="center">
  <picture><source srcset="assets/android-dark.png" media="(prefers-color-scheme: dark)"><img src="assets/android-light.png" width="56"></picture>&nbsp;
  <picture><source srcset="assets/apple-dark.png" media="(prefers-color-scheme: dark)"><img src="assets/apple-light.png" width="56"></picture>&nbsp;
  <picture><source srcset="assets/flutter-dark.png" media="(prefers-color-scheme: dark)"><img src="assets/flutter-light.png" width="56"></picture>&nbsp;
  <picture><source srcset="assets/windows-dark.png" media="(prefers-color-scheme: dark)"><img src="assets/windows-light.png" width="56"></picture>&nbsp;
  <picture><source srcset="assets/ios-dark.png" media="(prefers-color-scheme: dark)"><img src="assets/ios-light.png" width="56"></picture>
</p>

<hr>

### UML Diagram

<p><img src="assets/1000x416.png" width="100%"/></p>

<hr>

### Main Features

Here is a non-exhaustive feature list:

- Quisque a lectus id sapien porta
- Sed imperdiet felis porttitor
- Aliquam tristique tortor in ultricies
- Pellentesque laoreet lorem
- Fusce cursus nibh vel commodo
- Quisque sed augue non leo
- Vivamus congue enim sit amet
- Mauris non erat aliquam cursus nisi

<hr>

### Add Flutter Package

Here is how to install the package:

```shell
flutter pub add adbready
```

<hr>

### Get ADB Executable

Here is how to retrieve the ADB path:

```dart
final starter = await Adbready().deploy();
```

<hr>

### Run ADB Command

Here is how to invoke a command to target:

```dart
final address = '192.168.1.10';
final command = ['-s', address, 'shell', 'getprop ro.product.model'];
final process = await Adbready().invoke(command)
final product = process.stdout;
```

<hr>