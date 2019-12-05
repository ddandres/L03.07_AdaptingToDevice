# L03.07_AdaptingToDevice
Lecture 03 - 07 Adaptation to the device, DISCA - UPV, Development of apps for mobile devices.

MainActivity displays a flag and 6 buttons with texts from "First" to "Sixth".

The flag displayed changes according to the default language selected in the device (UK - default, Spain, Germany, France).
Several different drawables have been created to support screen densities from medium (mdpi) to extra-extra-extra high (xxxhdpi).

All the strings of the application (TextView and Buttons) are also displayed in the default language selected in the device (English - default, Spanish, German, French).

The default layout displays the Buttons vertically one below de other (like a 6 x 1 matrix).
Another layout will display the Buttons like a 2 x 3 matrix when the device is set in a landscape orientation (landscape).

In case of being a device with an extra large screen (xlarge) a different layout will increase the text size of all the strings and display the Buttons like a 3 x 2 matrix.
