# Base 69

Base 69 becuse cool kids only count in funny internet numbers


### Functions:
**All base 69s will start with `69*|`**

`encode_base69` Will return a string in base 69  
`decode_base69` Will return a int

## Support
 
 If this made you laugh and you want to get me a cup of tea: https://www.buymeacoffee.com/Michaelrbparker


### Example
```c
#include <stdio.h>
#include "base69.h"

int main() {
    int input = 100;
    char output[24]; // Allocate enough space for the output including the prefix

    encode_base69(input, output);

    printf("Encoded: %s\n", output);

    int decoded = decode_base69(output);
    printf("Decoded: %d\n", decoded);

    return 0;
}

```

```
gcc test.c base69.c -o base69_test
```


### Conversion Table:

```py
0:'0',1:'1',2:'2',3:'3',4:'4',5:'5',6:'6',7:'7',8:'8',9:'9',10:'A',11:'B',12:'C',13:'D',14:'E',15:'F',16:'G',17:'H',18:'I',19:'J',20:'K',21:'L',22:'M',23:'N',24:'O',25:'P',26:'Q',27:'R',28:'S',29:'T',30:'U',31:'V',32:'W',33:'X',34:'Y',35:'Z',36:'a',37:'b',38:'c',39:'d',40:'e',41:'f',42:'g',43:'h',44:'i',45:'j',46:'k',47:'l',48:'m',49:'n',50:'o',51:'p',52:'q',53:'r',54:'s',55:'t',56:'u',57:'v',58:'w',59:'x',60:'y',61:'z',62:'+',63:'/',64:'=',65:'@',66:'*',67:'-',68:'!',69:'#'
```

| Number | Value |
| ------ | ----- |
| 0      | 0     |
| 1      | 1     |
| 2      | 2     |
| 3      | 3     |
| 4      | 4     |
| 5      | 5     |
| 6      | 6     |
| 7      | 7     |
| 8      | 8     |
| 9      | 9     |
| 10     | A     |
| 11     | B     |
| 12     | C     |
| 13     | D     |
| 14     | E     |
| 15     | F     |
| 16     | G     |
| 17     | H     |
| 18     | I     |
| 19     | J     |
| 20     | K     |
| 21     | L     |
| 22     | M     |
| 23     | N     |
| 24     | O     |
| 25     | P     |
| 26     | Q     |
| 27     | R     |
| 28     | S     |
| 29     | T     |
| 30     | U     |
| 31     | V     |
| 32     | W     |
| 33     | X     |
| 34     | Y     |
| 35     | Z     |
| 36     | a     |
| 37     | b     |
| 38     | c     |
| 39     | d     |
| 40     | e     |
| 41     | f     |
| 42     | g     |
| 43     | h     |
| 44     | i     |
| 45     | j     |
| 46     | k     |
| 47     | l     |
| 48     | m     |
| 49     | n     |
| 50     | o     |
| 51     | p     |
| 52     | q     |
| 53     | r     |
| 54     | s     |
| 55     | t     |
| 56     | u     |
| 57     | v     |
| 58     | w     |
| 59     | x     |
| 60     | y     |
| 61     | z     |
| 62     | +     |
| 63     | /     |
| 64     | =     |
| 65     | @     |
| 66     | *     |
| 67     | -     |
| 68     | !     |
| 69     | #     |