# August
Solution to Hack The Box Challenge - August

### Problem

August left Chris in America. Can you get the flag and reunite them?

### Solution

Viewing the flag it doesn't have any sense. There is a hiding clue in the problem. August, Chris, left, an america are keywords. 

Searching on the forum the creator throw a more confident clue...

>  Keyboards.
That's the field that august and christopher both worked in.
should get the individuals with some google searches and then make your own cipher ((:

So searching...

- [August](https://en.wikipedia.org/wiki/Dvorak_keyboard_layout) Created the DVORAK keyboard
- [Chris](https://en.wikipedia.org/wiki/Christopher_Latham_Sholes) Created the QWERTY keyboard

So "August left Chris" might be **"DVORAK LEFT QWERTY"**. Using this [tool](https://www.geocachingtoolbox.com/index.php?lang=en&page=dvorakKeyboard) you can convert it. That gives a Base64 string, only decode and get the flag.
