# Softdev hw2

In this homework, we are going to implement a simple calculator!

In previous homework, we implement two different color themes.

In this homework, just choose the theme you like.

If you have any concern about spec, you could refer Windows10's Programmer calculator.

# Grading policy

- Negative Number [10]

- Basic Arithmetic [40]

	- ``+`` [10]
	- ``-`` [10]
	- ``*`` [10]
	- ``%`` [10]

- Further Arithmetic [10]

	- ``Mod`` [10]

- Conversion and able to input between different numeral system [20]

	- Hexadecimal [5]
	- Decimal [5]
	- Octal [5]
	- Binary [5]

The default numeral is decimal, you should be able to switch numeral by click text like HEX,DEC,OCT,BIN.

The number is 2 byte WORD.

If the number is -1, you should display FFFF in the hex.

- Operator Precedence [10]

- Backspace ``<-`` [5]

- Clear `C` `CE` [5]

If you have concern about functionality, you could take a look of Windows calculator.

# Submission

If your student id is 0115678, then your file name should be 0115678.zip

We don't need another branch in this homework, just leave master branch.

Your website entry should be `index.html`.

# Example Inputs

Press buttons by order.

## Negative Number [10]

- `-1+5` = 4
- `-1*6` = -6
- `-2*6` = -12
- `-6/3` = -2

## Basic Arithmetic [40]

- `7*2-3` = 11
- `1+2*3` = 7
- `5-6/2` = 2
- `6/3+2` = 4

## Further Arithmetic [10]

- `5*3 Mod 4` = 3
- `56 Mod 13` = 4

## Conversion and able to input between different numeral system [20]

- `10`
change to hex numeral
`+B` = 15 (hex)
- `26`
In conversion list should display: 
HEX: 1A
DEC: 26
OCT: 32
BIN: 00011010
- `6`
change to oct numeral
`+7` = 15 (oct)
- `5`
change to oct numeral
`+1111` = 10100 (bin)

## Operator Precedence [10]

- `2*5+3*4` = 22
- `6-2*5` = -4

## Backspace ``<-`` [5]

- `115 <- + 7` = 18

## Clear `C` `CE` [5]

- `5+6+7 CE` = 11
- `5+6+7 C` = 0 
