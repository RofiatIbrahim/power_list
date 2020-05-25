# power_list
def power_list(s): 
#function name : power_list
 #parameters : s is a a list
# returns the subsets of the elements in s
 power_set=[[]] 
 for elem in s: 
  for sub_set in power_set: 
   power_set=power_set+[list(sub_set)+[elem]] 
 return power_set
print(power_list([1,2,3]))
