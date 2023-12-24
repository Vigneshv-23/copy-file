# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file using notepad with extenstion.txt
### Step 2: 
 open google colab and mount the drive for using the created file
### Step 3: 
now open the text file and store the data in variable 
### Step 4:  
then read the content in the file and store the data in variable
### Step 5: 
now open the new uncreated file or an empty file using a different file object by "w+" mode and write the content derieved from first file using write().
### Step 6: 
end of the program
## PROGRAM:
```
#to copy a file
#Developed by: vignesh v
#register number: 23002301

f=open("record file.txt","r")
content=f.read()
f1=open("record file updated.txt","w+")
f1.write(content)
print("the content that has been copied to the new file is",content)
```
### OUTPUT:
<img width="689" alt="image" src="https://github.com/Vigneshv-23/copy-file/assets/110780412/a10461f9-d28f-4195-9de5-a2eb248e577a">




## RESULT:
Thus the program is written to copy the contents from one file to another file.
