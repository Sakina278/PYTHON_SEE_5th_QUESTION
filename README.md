# PYTHON_SEE_5th_QUESTION
Program is given in debug_exam.py and Instructions are given in ReadMe file.
# Fork the repository and commit the changes.
# Answers should be given for all three questions here.
5a:
3
1 2
2 2
8 7
2
3 3
4 4
When key does not exist in data 1, the key value pair is not added to it
5b:
def uniqueUpdate(data1, data2):
    # Initially empty dictionary
    dupKeys = {}

    # Examine every (k, v2) pair in data2
    for [k, v2] in data2:
        # Check if there is a key-value
        # pair with key = k in data1
        if k in data1:
            v1 = data1[k]
            # (k, v1) in dict1
            # Check if v1 != v2
            
        if k in data1:
                v1 = data1[k]
           if v1 != v2:
               dupKeys[k] = [v1, v2]
               del data1[k]
           else:
               data1[k] = v2
          return dupKeys
5c:
Test case one
4
1 2
3 3
3 8
4 9
2
3 3
4 4
Test case two
4
1 2
2 2
3 3
4 19
2
3 3
4 19
Test case 3
5a which breaks the code 
