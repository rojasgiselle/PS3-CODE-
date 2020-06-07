# PS3-CODE-
P1.
This code is for opening the file : fhand = open('/ufrc/bsc4452/share/Class_Files/data/CO-OPS__8729108__wl.csv')
Use open.py
fhand = open('/ufrc/bsc4452/share/Class_Files/data/CO-OPS__8729108__wl.csv')
count = 0
for line in fhand:
count = count + 1
print('Line Count:', count)

fhand = open('/ufrc/bsc4452/share/Class_Files/data/CO-OPS__8729108__wl.csv')
count = 0
n = 'Water Level'
for line in fhand:
if n > max_value:
max_value = n
print (line)

P2.
Import pandas as pd
df=pd.read_csv('/ufrc/bsc4452/share/Class_Files/data/CO-OPS__8729108__wl.csv')
columns= ['Date Time',' Water level']
maxValue = df[' Water Level'] 
print("Maximum value in column ' Water Level': ")
print(maxValue)
print(datetime)

P3.
*object is to create a new column that will caluclate the differences in rows for the water level column
my_data = pd.read_csv('/ufrc/bsc4452/share/Class_Files/data/CO-OPS__8729108__wl.csv')
df = pd.DataFrame(my_data)
df['New_column'] = df[' Water_level'].diff(1)
print(df)
fhand = df
count = 0
n = 'New_column'
for n in df:
if n > max_value:
max_value = n
print (line)
