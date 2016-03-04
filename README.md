# pyspark

'''
In []: data = {'state': ['Ohio', 'Ohio', 'Ohio', 'Nevada', 'Nevada'],
        'year': [3000, 4000, 5000, 6000,7000],
        'pop': [1.5, 1.7, 3.6, 2.4, 2.9]}、
        
In []: data0 = {'state': ['Ohio', 'Ohio', 'Ohio', 'Nevada', 'Nevada'],
        'year': [3000, 4000, 5000, 6000,7000],
        'pop': [1.5, 1.7, 3.6, 2.4, 2.9]}
        
In []: frame = DataFrame(data)

df3 = sdf.createDataFrame(frame)

In []: df = sdf.createDataFrame(DataFrame(data0))

df3.show()
+---+------+----+
|pop| state|year|
+---+------+----+
|1.5|  Ohio|3000|
|1.7|  Ohio|4000|
|3.6|  Ohio|5000|
|2.4|Nevada|6000|
|2.9|Nevada|7000|
+---+------+----+




'''
