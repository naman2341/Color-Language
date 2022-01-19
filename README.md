# Color-Language
This is a language written entirely in colour

Let me explain:
The colors will represent a character in Octal
The langauge written in Octal could be reffered to as `ColorOct`

<hr>

### Color Table
For `ColorOct` using ROYGBIV
|Octal| Color      | RGB           | Hex     | Color                                                                   |
|-----| -----------|:-------------:| :------:|-------------------------------------------------------------------------|
| 0   | White      | 0,0,0         | #FFFFFF |![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+) `#FFFFFF`|
| 1   | Red        | 255,0,0       | #FF0000 |![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+) `#FF0000`|
| 2   | Orange     | 255, 127, 0   | #FF7F00 |![#FF7F00](https://via.placeholder.com/15/FF7F00/000000?text=+) `#FF7F00`|
| 3   | Yellow     | 255, 255, 0   | #FFFF00 |![#FFFF00](https://via.placeholder.com/15/FFFF00/000000?text=+) `#FFFF00`|
| 4   | Green      | 0, 255, 0     | #00FF00 |![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+) `#00FF00`|
| 5   | Blue       | 0, 0, 255     | #0000FF |![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+) `#0000FF`|
| 6   | Indigo     | 75, 0, 130    | #4B0082 |![#4B0082](https://via.placeholder.com/15/4B0082/000000?text=+) `#4B0082`|
| 7   | Violet     | 148, 0, 211   | #9400D3 |![#9400D3](https://via.placeholder.com/15/9400D3/000000?text=+) `#9400D3`|

#### Example Code
Lets consider a simple program in python

`
print("Hello World")
`

After ASCII conversion
The following code when converted to Decimal, will look something like this :
```
112 114 105 110 116 40 34 72 101 108 108 111 32 87 111 114 108 100 34 41
```

In `Octal`, it will look something like this :
```
160 162 151 156 164 050 042 110 145 154 154 157 040 127 157 162 154 144 042 051
```

This Code, now in `ColorOct` (text-only) will look like:
```
Red Indigo White Red Indigo Orange Red Blue Red Red Blue Indigo Red Indigo Green White Blue White White Green Orange Red Red White Red Green Blue Red Blue Green Red Blue Green Red Blue Violet White Green White Red Orange Violet Red Blue Violet Red Indigo Orange Red Blue Green Red Green Green White Green Orange White Blue Red
```

This Code, now in `ColorOct` (text-only) will look like:
<br>
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#4B0082](https://via.placeholder.com/15/4B0082/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#4B0082](https://via.placeholder.com/15/4B0082/000000?text=+)
![#FF7F00](https://via.placeholder.com/15/FF7F00/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#4B0082](https://via.placeholder.com/15/4B0082/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#4B0082](https://via.placeholder.com/15/4B0082/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FF7F00](https://via.placeholder.com/15/FF7F00/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#9400D3](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#FF7F00](https://via.placeholder.com/15/FF7F00/000000?text=+)
![#9400D3](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#9400D3](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#4B0082](https://via.placeholder.com/15/4B0082/000000?text=+)
![#FF7F00](https://via.placeholder.com/15/FF7F00/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#00FF00](https://via.placeholder.com/15/00FF00/000000?text=+)
![#FF7F00](https://via.placeholder.com/15/FF7F00/000000?text=+)
![#FFFFFF](https://via.placeholder.com/15/FFFFFF/000000?text=+)
![#0000FF](https://via.placeholder.com/15/0000FF/000000?text=+)
![#FF0000](https://via.placeholder.com/15/FF0000/000000?text=+)

<hr>
<hr>

## Extension (WIP)
Using more colours, to represent the language in hexadecimal
The colors will represent a character in Hexadecimal
The langauge written in Hexadecimal could be reffered to as `ColorHex`

<hr> 

### Color Table
For `ColorHex`
```
WIP
```
<!--
|Octal| Color      | RGB           | Hex     | Color                                                                   |
|-----| -----------|:-------------:| :------:|-------------------------------------------------------------------------|
| 0   | White      | 0,0,0         | #FFFFFF |![#90B3A4](https://via.placeholder.com/15/FFFFFF/000000?text=+) `#FFFFFF`|
| 1   | Red        | 255,0,0       | #FF0000 |![#779977](https://via.placeholder.com/15/FF0000/000000?text=+) `#FF0000`|
| 2   | Orange     | 255, 127, 0   | #FF7F00 |![#364844](https://via.placeholder.com/15/FF7F00/000000?text=+) `#FF7F00`|
| 3   | Yellow     | 255, 255, 0   | #FFFF00 |![#1c1c1c](https://via.placeholder.com/15/FFFF00/000000?text=+) `#FFFF00`|
| 4   | Green      | 0, 255, 0     | #00FF00 |![#90B3A4](https://via.placeholder.com/15/00FF00/000000?text=+) `#00FF00`|
| 5   | Blue       | 0, 0, 255     | #0000FF |![#779977](https://via.placeholder.com/15/0000FF/000000?text=+) `#0000FF`|
| 6   | Indigo     | 75, 0, 130    | #4B0082 |![#364844](https://via.placeholder.com/15/4B0082/000000?text=+) `#4B0082`|
| 7   | Violet     | 148, 0, 211   | #9400D3 |![#1c1c1c](https://via.placeholder.com/15/9400D3/000000?text=+) `#9400D3`|
-->

#### Example Code
Lets consider a same program in python

`
print("Hello World")
`

After ASCII conversion
The following code when converted to Decimal, will look something like this :
```
112 114 105 110 116 40 34 72 101 108 108 111 32 87 111 114 108 100 34 41
```

In `HexaDecimal`, it will look something like 
```
70 72 69 6E 74 28 22 48 65 6C 6C 6F 20 57 6F 72 6C 64 22 29
```

This Code, now in `ColorHex` will look like:


<hr>

- This is a fun project , to make a language written entirely in color
- **The language might be further extended by writing a whole new language purely in colours(with its own syntax, like BrainF\*ck or BeFungue) , rather than relying on ascii conversions**
- Another fun project could be `Greys` where the same concept is converted into different shades of grays, starting from White all the way to Black

<hr>
