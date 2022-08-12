# Instructions  

#### In a Caesar shift code, each letter in a message is shifted n places later in the alphabet (with Z wrapping around to A). 

#### For example, if n = 1, the word example becomes fybnqmf. 
#### If n = 2, the word python becomes ravjqp. 

#### Write a function called caesar_shift() that takes two parameters. 
The first is a word to encode. 

The second is the number of places to shift. 

It returns the shifted text. 

You can assume the first parameter is a single word with no spaces or other punctuation. 

You may also assume it is all lowercase. 

Some sample calls: 

```>>> caesarShift(’example’, 1) ’fybnqmf’ ```

```>>> caesarShift(’example’, -1) ’dwzlokd’ ```

```>>> caesarShift(’python’, 2) ’ravjqp’ ```

```>>> caesarShift(’pecan’, 4) ’tiger’```
