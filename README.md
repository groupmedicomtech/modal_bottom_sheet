<The Problem >
Error (Xcode): ../../.pub-cache/hosted/pub.dev/modal_bottom_sheet-2.1.2/lib/src/bottom_sheets/bar_bottom_sheet.dart:102:13: Error: 'ModalBottomSheetRoute' is imported from both 'package:flutter/src/material/bottom_sheet.dart' and 'package:modal_bottom_sheet/src/bottom_sheet_route.dart'.

<Solution 1 >
    dependency_overrides:	
        modal_bottom_sheet:		
            git:			
                url: https://github.com/danReynolds/modal_bottom_sheet.git			
                path: modal_bottom_sheet

<Solution 2 >
dependency_overrides:
  modal_bottom_sheet: ^3.0.0-pre

<a href="https://jamesblasco.github.io/modal_bottom_sheet/#/"><img src="https://github.com/jamesblasco/modal_bottom_sheet/blob/screenshots/preview.png?raw=true"></a>

# A modal bottom sheet for your Flutter app

[![Awesome Flutter](https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square)](https://github.com/Solido/awesome-flutter)
[![Pub](https://img.shields.io/pub/v/modal_bottom_sheet.svg?logo=flutter&color=blue&style=flat-square)](https://pub.dev/packages/modal_bottom_sheet)

Check the package [README](https://github.com/jamesblasco/modal_bottom_sheet/tree/main/modal_bottom_sheet) for more information

### Sheet (Experimental)

[Sheet](https://github.com/jamesblasco/modal_bottom_sheet/tree/main/sheet) is a new package that reimplements the modal bottom sheet behavior from scratch. It is expected to be easier to use, more performant, more stable, more customaziable and with more features. It is used in several released apps already. If you want to be part of it, I encourge you to give it a try and provide any feedback you might have :)




