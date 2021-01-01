## Given-a-list-iterate-it-and-count-the-occurrence-of-each-element-and-create-a-dictionary-to-show-the details 
## Sample code to check the details for the occurance
```sh
countDict = dict()
for item in sampleList:
  if(item in countDict):
    countDict[item] += 1
  else:
    countDict[item] = 1
```
## Example Output
Original list  [11, 45, 8, 11, 23, 45, 23, 45, 89]
Printing count of each item   {11: 2, 45: 3, 8: 1, 23: 2, 89: 1}
