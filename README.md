# mydig DNS resolver
A custom DNS resolver that takes as input a domain name, and resolves the query by contacting the root server, the top level domain,
all the way to the authoritative name server.

## External Libraries
- dnspython
- datetime

## Instructions
1. From your terminal, change your directory to `root`
2. Run the command `python mydig.py`
3. Input a valid website, such as `www.cnn.com`
4. mydig will display an output similar to the one shown below:

```
QUESTION SECTION: www.cnn.com. IN A
ANSWER SECTION:
www.cnn.com. 262 IN A 151.101.209.67
Query time: How much time it took to resolve the query
WHEN: Date and time of request
```

