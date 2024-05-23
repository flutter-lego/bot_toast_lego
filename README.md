[![pub package](https://img.shields.io/pub/v/bot_toast_lego.svg)](https://pub.dartlang.org/packages/bot_toast_lego)

# bot_toast_lego
lego about [bot_toast](https://pub.dev/packages/bot_toast) for [lego](https://lego.junestory.com/).

##  Installation
1. open terminal in the lego project root directory, enter the following command for install cli.
```bash
flutter pub global activate lego_cli
```
2. in terminal, enter the following command for add lego to project.
 ```bash
 june add bot_toast_lego
 ```

## Usage
```dart
var cancel = BotToast.showText(text:"xxxx");

var cancel = BotToast.showSimpleNotification(title: "init");
```
