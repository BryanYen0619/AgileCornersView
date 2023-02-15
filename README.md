# AgileCornersView

[![license](https://img.shields.io/github/license/:user/:repo.svg)](LICENSE)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)


Android 靈活的切圓角元件(Layout)

## Table of Contents

- [Security](#security)
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [API](#api)
- [Contributing](#contributing)
- [License](#license)

## Security
	Android 支援版本 21 ~ 32 (Android 5.0 ~ Android Sv2)

## Background
	無，純UI客製元件。

## Install
```groovy
dependencies {
	implementation 'io.github.bryanyen0619.agileCornersView-lib:0.1.0'
}

```

## Usage

### Demo截圖
<img src="https://github.com/BryanYen0619/AgileCornersView/blob/main/app/src/main/java/com/cathaysec/view/agilecorners/screenshot/Screenshot_20230213_092150.png" height="640px" width="288px" >

* 適用於Android項目的UI切圓角元件。

### 元件參數說明
| 參數名 | 型態 | 功能 | 
| -------- | -------- | -------- |
| corner | dimension| 4個角全部切成圓角|
| leftTopCorner | dimension| 左上角部切成圓角|
| rightTopCorner | dimension| 右上角切成圓角|
| leftBottomCorner | dimension| 左下角切成圓角|
| rightBottomCorner | dimension| 右下角切成圓角|

## API
```xml
<com.cathaysec.view.agilecorners.CornersLinearLayout
	android:id="@+id/button1"
	android:layout_width="wrap_content"
	android:layout_height="wrap_content"
	android:background="@drawable/img_header_bg_more"
	android:gravity="center"
	android:minWidth="100dp"
	android:minHeight="50dp"
	android:orientation="vertical"
	app:corner="8dp">

	<TextView
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:text="全部圓角"
		android:textColor="@color/white"
		android:textSize="24sp" />
</com.cathaysec.view.agilecorners.CornersLinearLayout>
```

## Contributing

無

## License
```
 Copyright 2023 Bryan Yen

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
[Apache License 2.0](../main/LICENSE)
