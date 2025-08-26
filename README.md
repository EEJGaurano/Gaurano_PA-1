Gaurano_PA-1
1. Alphabet Soup Problem
``` python
s = "hello" #assign the string

sorted_s = ''.join(sorted(s)) #function to sort the string in alphabetical order

sorted_s #output

'ehllo'

s = "hacker"

sorted_s = ''.join(sorted(s))
sorted_s

'acehkr'
```

2. Emoticon Problem
``` python
def emotify(s): #function to assign emoticons
    s = s.replace ("Smile", ":)")
    s = s.replace ("Grin", ":D)")
    s = s.replace ("Sad", ":((")
    s = s.replace ("Mad", ">:(")
    return s
    
#Print the output of the function
print(emotify("Make me Smile"))
print(emotify("I am Mad"))

Make me :)
I am >:(
```

3. Unpacking List Problem
``` python
def unpack_list(lst):
    first = lst[0] #first element
    middle = lst[1:-1]  #Middle element
    last = lst[-1]   #Last element
    
    print ("first: {},   middle: {},   last: {}". format(first, middle, last)) #Output

unpack_list (lst = [1, 2, 3, 4, 5, 6])

first: 1,   middle: [2, 3, 4, 5],   last: 6
