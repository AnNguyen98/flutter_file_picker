# file_picker_af

This Go package implements the host-side of the Flutter [file_picker_af](https://github.com/AnNguyen98/flutter_file_picker_af) plugin.

## Usage

Modify your applications `options.go`:

```
package main

import (
	... other imports ....
	file_picker_af "github.com/AnNguyen98/flutter_file_picker_af/go"
)

var options = []flutter.Option{
	... other plugins and options ...

	flutter.AddPlugin(&file_picker_af.FilePickerPlugin{}),
}
```
