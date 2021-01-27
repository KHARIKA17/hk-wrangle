# hk-wrangle

1. My assigned play is: The Merchant of Venice
1. My speaker 1 is: LORENZO
1. My speaker 2 is: BASSANIO
1. The question was to count number of times Speaker 1 and Speaker 2 words present in the file.

## List of commands used:
- To get the content from the URL and to put that content in a file.
```
curl "http://shakespeare.mit.edu/merchant/full.html" -o demo.txt
```

- To count the number of times the word is present in file ignoring the case
```
grep -i "LORENZO" demo.txt -c > spkone.txt
```

- To count the number of times the word is present in file ignoring the case
```
grep -i "BASSANIO" demo.txt -c > spktwo.txt
```

### Output:

- The speaker 1 is present 80 times
- The speaker 2 is present 122 times




