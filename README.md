# PS3-CODE-
P1.
#This code is for opening the file : file = open('/ufrc/bsc4452/share/Class_Files/data/CO-OPS__8729108__wl.csv')   
 
#loop for water level LARGEST
for line in rrl: 
ident = line.split(',') [0]
water = line.split (',') [1]
if float (maxvalue) < float(water) :
maxvalue = float (water)

maxvalue = float(0)          #create a variable 
maxident = ''

maxident = indent

except:
continue
print (maxvalue, 'at' maxident)
#prints answer to water level

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
df.nlargest (1, [ ' Water Level '])
maxValue = df[' Water Level'] 
print("Maximum value in column ' Water Level': ")
print(maxValue)
print(datetime)

P3.
*object is to create a new column that will caluclate the differences in rows for the water level column
my_data = pd.read_csv('/ufrc/bsc4452/share/Class_Files/data/CO-OPS__8729108__wl.csv')
df = pd.DataFrame(my_data)
df['New_column'] = df[' Water_level'].diff(1)
df['rise'] = df[' Water Level']
df.nlargest (1, ['rise']
print(df)
fhand = df
count = 0
n = 'New_column'
for n in df:
if n > max_value:
max_value = n
print (line)
