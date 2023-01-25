# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.

## Step 2:
Using keyword "with" to open the requied file.

## Step 3:
Again using the with keyword to open the empty file.

## Step 4:
The empty file is open by using 'W' which is used to write only.

## Step 5:
The four function is used to take each line from the main file.

## Step 6:
The four function is used to take each line from the main file.

## step 7:
Print the output.

## PROGRAM:
``` python
developde by: Koti Sai Sankar
registered number: 22001315
with open("git.txt","r") as f1:
    with open("MyFile.txt","a") as f2:
        for line in f1:
            f2.write(line)

```

### OUTPUT:
![giy](https://user-images.githubusercontent.com/118344248/214654707-d421820c-cedd-4226-8bdb-b915f03ef6d5.png)

![ghu](https://user-images.githubusercontent.com/118344248/214654839-ddf1e414-1a51-4a08-8000-6bdceaa83180.png)

![pli](https://user-images.githubusercontent.com/118344248/214654937-d52d6e5c-ed88-42cd-88e3-e6c33d70decc.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
