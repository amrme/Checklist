Create a dictionary with all the {"user": id} pairs
prompt the user for his name and id
if the id matches the given name
if the user is admin give him options
1- add items
2- delete items
3- edit items
if 1 selected 
append the input to the list
else if 2 selected 
ask for the item number
remove the item from the list
else if 3 selected 
ask for the item id
ask for the new edited item "string"
overwrite the item in the list

==============================================================================================

else if the user is normal user
create a copy of the list
print the list to the user
prompt the user for done tasks "number of the item done"
remove the item done from his list-copy

===============================================================================================

in the end to know which user finished which tasks, 
loop over the original list
compare each value of the list to the value in the list-copy
if they are available then it's not done
