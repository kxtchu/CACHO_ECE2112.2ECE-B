PA #1
Nathan Josh Cacho


Alphabet Soup

- For this task, I needed to take a word from the user and return the letters in alphabetical order. My first idea was to use Python’s built-in tools instead of writing my own sorting code. I discovered that sorted() could do the job of arranging the letters. The output of sorted() is a list, so I used "".join() to stick the letters back together into a single string. I wrapped everything in a function called alphabetSoup and tested it with words like hello, which correctly turned into ehllo.

Emoticons

- The second task asked me to change words into their emoticon equivalents inside a sentence. To handle this, I created a dictionary where each word is connected to its matching emoticon. I looped through the dictionary and replaced the words one by one in the user’s input. I also added checks for capitalized and uppercase versions so it would still work even if the word wasn’t written in lowercase. After running it, a sentence like I want to smile but I am sad turned into I want to :) but I am :( (. This showed the replacement logic was working properly.

Unpacking List

- The last task involved breaking down a list into three parts: the first value, the values in the middle, and the last value. I made a list with the numbers 1 through 6. Using indexing and slicing, I took out the first element, stored the middle slice, and then took the last element. Printing them separately showed me: First: 1, Middle: [2, 3, 4, 5], and Last: 6. This confirmed that the list was unpacked the way I expected.

      
