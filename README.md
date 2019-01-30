# Parser for TINY language
## Interfaces
#### Inputs: A program written in TINY language.
#### Outputs: A syntax tree for this program.
## How to run Parser
#### 1- Download .exe file 
#### 2- Download grahviz library exe files as .zip file from "https://www.graphviz.org/download/"
#### 3- Extract .zip and put the extracted file, executable file in the same directoy.
#### 4- Open the .exe file.
## Samples
##### GUI
![gui](https://user-images.githubusercontent.com/33963542/51975541-2ae1b580-248b-11e9-9efa-6e034059ab2f.PNG)
#### Code
[test1.txt](https://github.com/mohamedsaberibrahim/parser_tiny/files/2812135/test1.txt)  
x:=2;  
y:=32436;  
z:=5;  
a:=x-y-z+2+1+3;  
if z <8 then  
	repeat  
		a:=a * 2;  
		z:=z-1;  
		repeat  
			read x;  
			write x;  
			if((x<4)) then  
				x:=x+1+2+3+4+s  
			else  
				x:=x-1  
			end  
		until x<5  
	until z=0;  
	write a;  
	read b  
else  
	read b;  
	if b = -1 then  
		write b * (x-y);  
		if x = 1 then  
			x:=x+1  
		else  
			read x  
		end  
	else  
		write a;  
		write z  
	end;  
	read b  
end;  
write z;  
write x * x * x;  
read x;  
x:= x * 4 / 2 * s  
#### Syntax Tree
![syntax-tree gv](https://user-images.githubusercontent.com/33963542/51975597-4ea4fb80-248b-11e9-9552-f327bd279d7e.png)
