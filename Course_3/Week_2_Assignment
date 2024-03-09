import csv
import re

filename = r'C:\Users\theth\Desktop\regex_sum_1992830.txt'
f = open(filename)
d = f.read()
y = re.findall('[0-9]+', d)
sum = 0
for i in range(len(y)):
    c = int(y[i])
    sum += c

print(sum)
