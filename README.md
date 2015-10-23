# My custom `.keylayout` files

This repository contains customized QWERTY keyboard layouts in `.keylayout` format, for use on OS X. Every `.keylayout` file has its own README, with details on what changed.

## How to install a new keyboard layout

1. Copy the `.keylayout` file to the `Keyboard Layouts` folder within `/Library` or `~/Library`.
2. Reboot, or log out and log in again.
3. Enable the new keyboard layout via _System Preferences_ › _Language & Text_ › _Input Sources_.

OS X has supported `.keylayout` files since version 10.2 (Jaguar).

## How to use comma dead keys

The `,` key (comma) is a dead key that enables a second keyboard layout in order to quickly access common developer symbols without needing to reach up to the number line. For example, to quickly type the `=` character, you would press `,` (to enter the developer keyboard state) and then press `d` (which produces the `=` character and exits the developer keyboard state).

The cheat sheet is below:

    1 2 3 4 5 6 7 8 9 0 - =
    Q W E R T Y U I O P [ ] \
    A S D F G H J K L ; '
    Z X C V B N M , . /

        ~ `     # ^
    % & ? + @ $ _ - / !
    [ ( = 0 { } 1 * ) ] "
    6 7 8 9 | , 2 3 4 5

What if you want a comma? The space bar and the return key are mapped to produce `, [space]` and `, [return]` so you will get what you expect in those scenarios. If you need a comma without a comma or return (which is pretty rare, other than numbers like 1,000), you can either type `, [space] [backspace]` or `, n`.

Furthermore, there is a second level to this madness. After you have pressed the `,` key, if you then hold down ⌥ (option) you get access to some additional developer shortcuts at the right-hand side of the keyboard:

    Y   U   I   O   P
    H   J   K   L
    N   M   ,   .

        <=  >=
    === ==  !=
        +=

## Credits

Created using [Ukelele.app](http://scripts.sil.org/ukelele).

## Original Author

| [![twitter/mathias](https://gravatar.com/avatar/24e08a9ea84deb17ae121074d0f17125?s=70)](https://twitter.com/mathias "Follow @mathias on Twitter") |
|---|
| [Mathias Bynens](https://mathiasbynens.be/) |

## License

These keyboard layouts are available under the [MIT](http://mths.be/mit) license.
