# Python-problem
pandas series example in python


# create a pandas series from different data types like list,numpy array and
 dictionary.
# import pandas as pd
import pandas as pd
  
# simple list
lst = ['G','E','E','K','S','F',
       'O','R','G','E','E','K','S']
  
# forming series
s = pd.Series(lst)
  
# output
print(s)

#this creates a big series of random numbers
import numpy as np
s = pd.Series(np.random.randint(0,1000,10000))
s.head()

#query from series
sports = {'Archery':'Bhutan',
          'Golf': 'Scotland',
          'Sumo': 'Japan',
          'Taekwondo': 'South Korea'}
s = pd.Series(sports, index=['Golf','Sumo','Hockey'])
s    

2) sports = {'Archery': 'Bhutan',
          'Golf':'Scotland',
          'Taekwondo':'South Korea'}
s = pd.Series(sports)
s 



 
