Created a structure with character pointer and integer and created the dynamic array 
Got the text input of indefinite length using the getline from the tale file given

Compared the words and incremented the count wherever the word is found using the string compare

if (strcmp(word, Arr[i].keyWord) == 0) // Comparing keywords and updating word count
            {
                
                Arr[i].kw_Count++;
            }

Have done the string tokenization as well using;  wrd = strtok(NULL, " ");

Give the words to be identified in the given text as below
   ./a.out or for and from to it was is <tale.txt
   
   The output will be as follows for the above words in the file tale.txt
or                      358
for                     948
and                     4931
from                    514
to                      3460
it                      2003
was                     1763
is                      818

