
# AnimatedConnectingButtonWidget
AnimatedConnectingButtonWidget is a simple and customizable animated connecting button widget [AnimatedConnectingButtonWidget](https://github.com/Sorbh/AnimatedConnectingButtonWidget)

The source code is **100% Dart**.

[![pub package](https://img.shields.io/pub/v/kdgaugeview.svg?style=flat-square)](https://pub.dartlang.org/packages/AnimatedConnectingButtonWidget)  ![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg?style=flat-square)


# Motivation

I need some clean animated connectingbuttong widget my Flutter application.

# Getting started

## Installing
Add this to your package's pubspec.yaml file:

This library is posted in pub.dev

#### pubspec.yaml
```dart
dependencies:  
	animated_round_button_flutter: ^1.0.0
```

# Usage

After Importing this library, you can directly use this view in your Widget tree

```dart
import 'package:animated_round_button_flutter/animated_round_button_flutter.dart';
```


```dart
AnimatedConnectingButtonWidget(
          width: 220,
          height: 220,
          onConnectingButtonTap: () {
            print("got button clicked");
          },
          buttonText: TextSpan(
              text: 'GO', style: TextStyle(color: Colors.black, fontSize: 32)),
        )
```

# Customization
  Depending on your view you may want to tweak the UI. For now you can these custom attributes

  | Property | Type | Description |
  |----------|------|-------------|
  | 'width' | double | width for connecting button |
  | 'height' | double | height for connecting button |
  | 'buttonText' | TextSpan | TextSpan Widget to add custom text on connecting button |



# Screenshots
![Screenshot 2021-08-02 at 9 50 43 PM](https://user-images.githubusercontent.com/14270768/127892988-5e3b9500-17c1-48b5-9e0e-7a8c60b35d32.png)    
![rounded button animation](https://user-images.githubusercontent.com/14270768/127893714-492072a4-6a5a-4276-9bdf-30947ecda280.gif)







# Author
  * **Saurabh K Sharma - [GIT](https://github.com/Sorbh)**
  
      I am very new to open source community. All suggestion and improvement are most welcomed. 
      


# Contributors

<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/Sorbh>
            <img src=https://avatars.githubusercontent.com/u/8159377?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Sorabh/>
            <br />
            <sub style="font-size:14px"><b>Sorabh</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/RohitKumarMishra>
            <img src=https://avatars.githubusercontent.com/u/14270768?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Rohit Kumar Mishra/>
            <br />
            <sub style="font-size:14px"><b>Rohit Kumar Mishra</b></sub>
        </a>
    </td>
</tr>
</table>
 
  
 
## Contributing

1. Fork it (<https://github.com/sorbh/animated_round_button_flutter/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

