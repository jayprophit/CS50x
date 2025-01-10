Here’s a structured, formatted, and workflow-oriented version of the content rewritten for a project folder, portfolio, or coursework submission. The format is aligned with a professional GitHub-style documentation approach.

A rewritten and formatted version, designed for a coursework-oriented GitHub book:

---

# CS50x  

## CS50x:   
**Course Type**: Full University Course  

---

# **CS50x**



## **Course Overview**
This document serves as a guide to fundamental concepts in programming, based on the CS50x University course. The course covers the following topics:

| **Topic**| **Description**|
|----------------------------|--------------------------------------------------------------------------------------------------|
| **Scratch**||
| **C**||
| **Arrays**||
| **Algorithms**||
| **Memory**||
| **Data**||
| **Python**||
| **Artificial Intelligence**||
| **SQL**||
| **HTML, CSS, JavaScript**||
| **Flask**||
| **CyberSecurity**||

---

## **Key Resources**
- **Documentation:** [](https://)

---



## youtube video links
- **CS50x 2025 Course on YouTube:** [CS50x 2024 Course](https://youtube.com/playlist?list=PLhQjrBD2T383q7Vn8QnTsVgSvyLpsqL_R&si=yxVeX8c6N51aPj3i)

- **CS50x 2024 Course on YouTube:** [CS50x 2024 Course](https://youtube.com/playlist?list=PLhQjrBD2T381WAHyx1pq-sBfykqMBI7V4&si=Ym_8loqix5-P03fy)  

---


## online course
- **Online Course:** [CS50x on edX](https://www.edx.org/learn/computer-science/harvard-university-cs50-s-introduction-to-computer-science)

- **cs50x course**[cs50x on harvard extension school](https://cs50.harvard.edu/extension)

- **cs50x course** [cs50x harvard summer school](https://cs50.harvard.edu/summer)

- **cs50x course** [cs50x opencourseware](https://cs50.harvard.edu/x)

---



## --Lecture 0 --: Scratch

### solving problems
        ---------
input   |problem|   output = result
        ---------

### binary
computers speak in 0's and 1's

### unary
counting on your fingers, meaning each finger/ tendem is a unit

### base-1
if the fingers is there or its not.  on a single hand if used in the correct way can give 31 outputs

### base-2 Binary Digit
just needs 2 digits,  this can be called or known as:-

- 1 & 2
- A & B
- Black & white
- etc

this is defined as 2 words to describe two pieces of information.  in onputers its known as Binary, 0 and 1, off and on

### bit
a single binary digit which is a 0 or 1, known as a 2 bit system, this is contrast to a system which is known as a decimal system, Dec implying 10,  in the real world,  dialy use of 0-9 which is 10 possibilities

### transistors
are like a switch or like a light bulb storing electricity, switched/ turned on or off

- if there is no current/ electricity then its OFF and is also represented by the digit 0
- if there is a flow of current/ electricity then it is ON and this is also represented by a 1 meaning there is a flow or current available or ready to use, or its active

### base 10
0-9 theres is 10 units.

e.g.
0, 1, 2, 3, 4, 5, 6, 7, 8, 9

### decimal
are single digits in a pattern
123

3 is a single unit - 1's column
2 is a tenth unit - 10's column
1 is a hundredth unit - 100's column

digits to the left have more weight then the digits to the right.  meaning the left digits are higher and have more value then the left digits

$10^{2}$ $10^{1}$ $10^{0}$

$x^{n}$  this means x to the power of

in binary just using 3 digits

001 = 1
010 = 2
011 = 3
100 = 4
101 = 5
110 = 6
111 = 7

in coimputers to get a higher then 7 we need another digit and continue the pattern to get higher and so on.

1000 = 8

### byte
in a byte there are 8 bits, which is to the power of 2

128, 64, 32, 16, 8, 4, 2, 1
 0    0   0   0  0  0  0  0

 which is seen as:-

 00000000

 11111111

is actually 255 bits but if you add the o then it equals 256 total possibilities

there is acutally turnary computers that use 3 values that use 0, 1 and 2, which is somewhere between binary and decimal.  which a simple on and off

### letters
capital letter A = 01000001, which is 65 meaning 64 + 1
lowercase a = 01100001, which is 97

### ASCII
American Standard Code for Information Interchange

#### ASCII Table with Binary Values for Letters, Numbers, and Symbols

| **Character** | **ASCII** | **Binary**      | **Character** | **ASCII** | **Binary**      |
|---------------|-----------|-----------------|---------------|-----------|-----------------|
| **a**         | 097       | 0110 0001       | **A**         | 065       | 0100 0001       |
| **b**         | 098       | 0110 0010       | **B**         | 066       | 0100 0010       |
| **c**         | 099       | 0110 0011       | **C**         | 067       | 0100 0011       |
| **d**         | 100       | 0110 0100       | **D**         | 068       | 0100 0100       |
| **e**         | 101       | 0110 0101       | **E**         | 069       | 0100 0101       |
| **f**         | 102       | 0110 0110       | **F**         | 070       | 0100 0110       |
| **g**         | 103       | 0110 0111       | **G**         | 071       | 0100 0111       |
| **h**         | 104       | 0110 1000       | **H**         | 072       | 0100 1000       |
| **i**         | 105       | 0110 1001       | **I**         | 073       | 0100 1001       |
| **j**         | 106       | 0110 1010       | **J**         | 074       | 0100 1010       |
| **k**         | 107       | 0110 1011       | **K**         | 075       | 0100 1011       |
| **l**         | 108       | 0110 1100       | **L**         | 076       | 0100 1100       |
| **m**         | 109       | 0110 1101       | **M**         | 077       | 0100 1101       |
| **n**         | 110       | 0110 1110       | **N**         | 078       | 0100 1110       |
| **o**         | 111       | 0110 1111       | **O**         | 079       | 0100 1111       |
| **p**         | 112       | 0111 0000       | **P**         | 080       | 0101 0000       |
| **q**         | 113       | 0111 0001       | **Q**         | 081       | 0101 0001       |
| **r**         | 114       | 0111 0010       | **R**         | 082       | 0101 0010       |
| **s**         | 115       | 0111 0011       | **S**         | 083       | 0101 0011       |
| **t**         | 116       | 0111 0100       | **T**         | 084       | 0101 0100       |
| **u**         | 117       | 0111 0101       | **U**         | 085       | 0101 0101       |
| **v**         | 118       | 0111 0110       | **V**         | 086       | 0101 0110       |
| **w**         | 119       | 0111 0111       | **W**         | 087       | 0101 0111       |
| **x**         | 120       | 0111 1000       | **X**         | 088       | 0101 1000       |
| **y**         | 121       | 0111 1001       | **Y**         | 089       | 0101 1001       |
| **z**         | 122       | 0111 1010       | **Z**         | 090       | 0101 1010       |


#### Numbers and Special Characters

| **Character** | **ASCII** | **Binary**      | **Character** | **ASCII** | **Binary**      |
|---------------|-----------|-----------------|---------------|-----------|-----------------|
| **0**         | 048       | 0011 0000       | **1**         | 049       | 0011 0001       |
| **2**         | 050       | 0011 0010       | **3**         | 051       | 0011 0011       |
| **4**         | 052       | 0011 0100       | **5**         | 053       | 0011 0101       |
| **6**         | 054       | 0011 0110       | **7**         | 055       | 0011 0111       |
| **8**         | 056       | 0011 1000       | **9**         | 057       | 0011 1001       |
| **!**         | 033       | 0010 0001       | **@**         | 064       | 0100 0000       |
| **#**         | 035       | 0010 0011       | **$**         | 036       | 0010 0100       |
| **%**         | 037       | 0010 0101       | **^**         | 094       | 0101 1110       |
| **&**         | 038       | 0010 0110       | *****        | 042       | 0010 1010       |
| **(**         | 040       | 0010 1000       | **)**         | 041       | 0010 1001       |
| **-**         | 045       | 0010 1101       | **_**         | 095       | 0101 1111       |
| **=**         | 061       | 0011 1101       | **+**         | 043       | 0010 1011       |
| **{**         | 123       | 0111 1011       | **}**         | 125       | 0111 1101       |
| **[**         | 091       | 0101 1011       | **]**         | 093       | 0101 1101       |
| **:**         | 058       | 0011 1010       | **;**         | 059       | 0011 1011       |
| **"**         | 034       | 0010 0010       | **'**         | 039       | 0010 0111       |
| **<**         | 060       | 0011 1100       | **>**         | 062       | 0011 1110       |
| **/**         | 047       | 0010 1111       | **\**        | 092       | 0101 1100       |
| **?**         | 063       | 0011 1111       | **space**     | 032       | 0010 0000       |

**Please refer to the ASCII md file for the complete 0-255 directory**

if a message is sent, here is an example of what it looks like before its converted into human readable language:-

ASCII:          01001000        01001001        00100001
HEX:            72              73              33
Conversion:     H               I               !
Message:        hi!

as language structure is vast in a variety across multiple regions and is a stuctred form of communication, 

now computers dont use 7 or 8 bits
they might use 8 bits for english language letters
they might use 16 bits for certain other languages
maaybe 24 or 32 bits two bit two.
if you have 32 bits you can represent 4 billion possible characters.

a newer standard is unicode which is backwards compatible with ASCII
which is our 16, 24, 32 bits to represent digitally to represent all human languages past, present and future and pictograms, like smiley faces, people, places, emotions, than transend human language.

an example is an emoji.  unicode standadise exmaple this pattern:-

1111000010011111100110010000010

which represents the decimal 4036991106 😂
the face with tears of joy
its more like a font 
the computer is storing be it MAC OS, Windows, IOS, Andriod, is programmed to display this to represnt the decimal number.  the Pictures might look different depending on hte hardware.  this is because of companies like google, Micorosoft, Meta, and others that have there own artist reresentation.
as with any sdevice or oftware it has updates and it can change  over time depending on the manufacture. which is really a place holderr to represent that digital number

### RGB
Red, Green, blue, represents a single dot which is allocated on a screen, which will represent some number of bits or some number of bytes to represent the color of that dot, which is also known as a Pixel.
Pixels havebecome so common in use its on phones, T.V, Digitsal Watches or any smart device with a screen to represnt some type of image.
the devices use 3 numbers in total, 3 bytes, which represents 24 bits per pixel
for example.
a software that is designed to recognise these colours as maybe these numbers:-

Red     Green   Blue    =       yellow
72      73      33      =       🟨

this as well as not just text
like medium amount of red, a medium amout of green, and a small amount of blue.
the highest we could count is 255 plus 0 is 256, which repsents the colour yellow.

so any digital photo or image is represented by a pixal and each colour has a repesentative of three sets of seperated digits to represent colours on a screen.
now large images are made from mega bytes which is millions of bytes to represent pixels on a screen, to represent the 3 sets of digits.  with compression software theres even fewer of those bytes.

### Videos
are still images which is about 30 frames of images per second, or made 24 frames of images per second.

videos are giga bytes, which is large and can take type to download

### Sound
which is analogue as digital. so each number stored in a computer can represent a specific freaqunecy, which has a direct anotation to the sound or the pitch of a note.
this can be represent just as with ASCII, unicode or and other software developer we can say this digital number set represent this pattern be it volume, length of key duration, pictch , modulation or any other effect.
we can use 3 bytes to represent every musical note in some piece.  or use a 4 byte to represent a different instrument

the unsivseral language comes back to 0 & 1 which is used to solve the problem, gose back to the 1st:-

input    -->    problem    -->    output
              (Algorithm)

### Algorithm
step by step instructions of solving some problem



---



## --Lecture 1 --: c

###


---



## --Lecture 2 --: Arrays

###

---



## --Lecture 3 --: Algorithms


###


---



## --Lecture 4 --: Memory

###

---



## --Lecture 5 --: Data

###

---



## --Lecture 6 --: Python

###

---



## --Lecture 7 --: Artificial Intyelligence

###

---



## --Lecture 8 --: Sql

###

---



## --Lecture 9 --: Html, CSS, JavaScript

###

---



## --Lecture 10 --: Flask

###

---



## --Lecture 11 --: CyberSecurity

###