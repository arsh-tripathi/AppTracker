# AppTracker

Here is a small utility script I built in python which helps me keep track of my job applications

I used the following libraries:
sys
openpyxl
datetime 

## Usage

Just create an excel file with these values in the first row

Sr.No.
Company
Position
Date Updated
Status
__
__
0

And then replace the path to your file in the python file

After that run the following command to add an application:

```
python ./add.py a company position 
```

Do this to update the status:

```
python ./add.py u company status
```
