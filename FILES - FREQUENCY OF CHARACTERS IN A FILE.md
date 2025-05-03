# Exp.No:18  
## FILES - FREQUENCY OF CHARACTERS IN A FILE

---

### AIM  
To write a Python program to read a file and count the frequency of each character in it.


### ALGORITHM

1.Create a File: Write the provided content into a file.

2.Open the File: Read the content of the file.

3.Count Characters: For each character, count how many times it appears.

4.Store Counts: Use a dictionary (defaultdict) to store the character counts.

5.Return the Result: Return the dictionary containing character frequencies.



### PROGRAM
# REG NO:212223090008
# NAME:Harinishri S

```
from collections import defaultdict
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def char_frequency(file_path):
    with open(file_path,'r') as f1:
        content=f1.read()
    d1=defaultdict(int)
    for ch in content:
        d1[ch]+=1
    return d1    


```


### OUTPUT


![Filee](https://github.com/user-attachments/assets/63b5c56b-74e8-4098-8d2e-2e54bf784d1a)


### RESULT
The program efficiently counts the frequency of each character in a file, including spaces and punctuation. It uses a defaultdict to automatically handle character counts and ensure accuracy.









