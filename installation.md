# Windows:

# Linux:
Open terminal and run the below command:  

`sudo apt install build-essential`  

## Handling errors:
While trying the above command if you got any error like **broken dependencies** then try the below commands:  

`sudo apt install aptitude`  

`sudo aptitude install g++`  

### Important:
* It asks to enter [Y/N/Q] - type N and hit enter  
* Hence it now asks for version downgrade of dependencies  
* It again asks to enter [Y/N/Q] - Now enter Y and hit enter  

`sudo aptitude -f install build-essential`  

## Verify installation:
`gcc --version`  

Should return the gcc version  

`sudo aptitude search build-essential`  

Should return **i build-essential** instead of **p build-essential** after installation
