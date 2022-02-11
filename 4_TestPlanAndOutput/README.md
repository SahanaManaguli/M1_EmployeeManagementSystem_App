# Test Plan 

TEST ID| TEST CASE OBJECTIVE| INPUT DATA   | EXPECTED OUTPUT| ACTUAL OUTPUT| STATUS|
|:-----|:-------------------|:-------------|:---------------|:-------------|:------|
|TC_1  |for entering name   |enter name:abc|  xyz           | xyz          |PASS   |
|TC_2  |for entering name   |enter name:abc|xyz             |-             |FAIL   |
|TC_3  |for entering age    |enter age:22  |22              |22            |PASS   |
|TC_4  |for entering age    |enter age:22  |22              |-             |FAIL   |
|TC_5  |for entering salary |enter salary:10000|10000       |10000         |PASS   |
|TC_6  |for entering salary |enter salary:10000|10000       |-             |FAIL   |
|TC_7  |for listing record  |xyz 22 10000  |xyz 22 10000    |xyz 22 10000  |PASS   |
|TC_8  |for listing record  |xyz 22 10000  |xyz 22 10000    |xyz 10000 22  |FAIL   |
|TC_9  |for listing record  |xyz 22 10000  |xyz 22 10000    |22 xyz 10000  |FAIL   |
|TC_10 |for deleting record |xyz           |xyz             |xyz           |PASS   |
|TC_11 |for deleting record |xyz           |xyz             |pqr           |FAIL   |
