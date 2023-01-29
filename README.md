# Assingment
## AIM :

 This code defines a module called "logic_function" with three input signals (a, b, c) and one output signal
## EQUIPMENT REQUIRED

Hardware-PCs,Cyclone II, USB Flasher
Software- Quatrus prime

## PROCUDRE

Check all the gates following the same inputs "A" and "B". The switch is ON state when I is pressed. The switch is OFF state wh Connect the supply (+5V) to the circuit Switch ON the main switch Press the switches for


## EXPLANATION

The equation f = x'y'z' is a Boolean expression that represents a logical function. The variables x, y, and z are 
binary inputs that can have a value of either 0 or 1. The apostrophes (') indicate the logical negation of 
the variable, also known as the NOT operator. Therefore, x' represents the negation of x, y' represents
the negation of y, and z' represents the negation of z.

The function f is equal to the logical AND of x', y' and z'. The logical AND operation returns a 
value of 1 if and only if all its inputs are 1, otherwise it returns 0. Therefore, the function f 
will only output a 1 when all of x, y, and z are 0.

In other words, f = x'y'z' is a logical expression that describes the condition when all of x, y, and z are 0

## PROGRAM

module logic_function(input x, y, z, output F);
assign F = !x & !y & !z;
endmodule

## OUTPUT:
## RTL:

![RTL](https://user-images.githubusercontent.com/119393642/215339732-8afd3412-b542-4dc2-9ad9-62d0a702e178.jpg)

## TIMING DIAGRAM:

![TT](https://user-images.githubusercontent.com/119393642/215339909-05836199-9ccc-4c19-a16d-ec7adfa5802c.jpg)


## TRUTH TABLE:

![55 dd](https://user-images.githubusercontent.com/119393642/215339960-b5b16545-7e79-478e-8aaa-2534b8725f5f.jpg)



## RESULT:

The program executed by verilog code successfully.
