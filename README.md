# TexPreambleStandard

## What is this?
This is a LaTex preamble template for math students, people who find LaTex's preamble creation tedious, and me!<br>
I am using jlreq for documentclass because I am Japanese. You can change it or just copy my definitions.

## Some usage for declared unique commands
### Math Symbols

Add a prefix before "S" for specific Symbols.

| command | description |
|----|-----| 
|\rS{expr}| Roman form of {expr}|
|\iS{expr}| Italic form of {expr}|
|\frkS{expr}| Fraktur form of {expr}|
|\calS{expr}| Caligraphy form of {expr}|
|\scrS{expr}| Script form of {expr}|

### Bold Symbols (like Vectors)

Add a prefix before "V" for specific Symbols.

| command | description |
|----|-----| 
|\rV{expr}|Roman Bold form of {expr}|
|\iV{expr}|Italic Bold form of {expr}|
|\gV{expr}|Greek Bold form of {expr}|
|\bV{expr}|Blackboard Bold form of {expr}|
|\oV{expr}|Other Bold form of {expr} (Not Recommended)|

### Set Symbols

Add a name after "set" for specific blackboard bold set letter.

| command | description |
| ---- | ---- |
| \setReal | Blackboard bold symbol of "R" |
| \setRational | Blackboard bold symbol of "Q" |
| \setComplex | Blackboard bold symbol of "C" |
| \setInteger | Blackboard bold symbol of "Z" |
| \setNatural | Blackboard bold symbol of "N" |

### Brackets

You can easily express various kinds of math brackets.<br>
Basic components used in this template are below.

| command | output |
| ---- | ---- |
| \SBrac*{expr} | (expr) |
| \MBrac*{expr} | {expr} |
| \LBrac*{expr} | \[expr\] |
| \AngBrac*{expr} | \<expr\> |
| \AbsBrac*{expr} | \|expr\| |
| \NormBrac*{expr}| \|\|expr\|\| |

If you want to disable auto brackets size fitting, you simply need to delete * in the command.<br>
(\AbsBrac can be written as \Abs, \NormBrac can be written as \Norm alternatively.)

### Functions

You can easily express various kinds of math functions.

| command | output |
| ---- | ---- |
|\fnS{f}{x}| f(x)|
|\fnM{f}{x}| f{x}|
|\fnL{f}{x}| f\[x\]|
|\fnAng{f}{x}| f\<x\>|
|\fnAbs{f}{x}| f\|x\| |
|\fnNorm{f}{x}| f\|\|x\|\| |

### Another useful commands

By using commands declared in this README, there are some more useful commands for Analysis, LinearAlgebra, Statistics and so on.<br>
You can check it in standard.tex file.
