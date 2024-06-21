# Spinner
The spinner is an indeterminate animated semi circle which can have two distinct sizes.
The spinner has both an implementation for UIKit and SwiftUI.

## Specifications
The spinner specifications on Zeroheight is [here](https://spark.adevinta.com/1186e1705/p/7651da-spinner).

![Figma anatomy](https://github.com/adevinta/spark-ios-component-spinner/blob/main/.github/assets/anatomy.png)

## SpinnerView/SpinnerUIView Initialization
Initialization Parameters
* `theme: Theme` The general theme.
* `intent: SpinnerIntent`. The intent defining the color of the spinner. The default value is `main`.
* `spinnerSize: SpinnerSize`. The size of the spinner. The default value is `small`. 

## SpinnerUIView Public Properties
* `theme: Theme` The general theme.
* `intent: SpinnerIntent`. The intent defining the color of the spinner. The default value is `main`.
* `spinnerSize: SpinnerSize`. The size of the spinner. The default value is `small`. 

## SpinnerView Public Modifiers
* `spinnerSize(_ spinnerSize: SpinnerSize)`. Change the spinner size of the view
* `intent(_ intent: SpinnerIntent)`. Change the intent of the view.

## License

```
MIT License

Copyright (c) 2024 Adevinta

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```