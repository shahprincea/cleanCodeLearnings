#Variables

#### Use Intention-Revealing Names
> Variables should be self explanatory.

```
    Bad code : 
        int d = 100;
        
    Good code:
        int deposit = 100;
```

#### Avoid Disinformation 
> If a variable names starts with list assumption is that it is a list.
follow that rule. Alternatively you can use plural form of the variable

```
    Bad code : 
        Account listAccount = new Account(); 
        
    Good code : 
        List<Account> listAccount = List.newArrayList();
        List<Account> accounts = List.newArrayList();

```

#### Make Meaningful Distinctions
> Make clear distinction with variable names so that its obvious. 

```
    Bad Code: 
        PersonInfo, PersonData, PersonDetails
    
    Good Code:
        Person
        
```

#### Use Pronounceable Names
> It helps with reading code and remembering flow

```
    Bad Code: 
        Date mmddyy = new Date();
        
    Good code:
        Date date = new Date();
        
```

#### Use Searchable Names
> Most of the modern ide intellij or eclipse supports camel case searching

```
    Bad Code:
        int xbyy = x/y;
        
    Good Code:
        int result = x/y;
```

#### Avoid Encoding
> We have enough to deal with last thing we want is ecoded variable names

```
    Bad Code:
        int xrootminusyroot = Math.sqrt(x) - Math.sqrt(y);
        
    Good code:
        int result = Math.sqrt(x) - Math.sqrt(y);
```

#### Classes name should be a noun 
> e.g. Person, Car, Customer, Dispatcher etc 

#### Method name should be verb 
> retrieve, fetch, transform, parse, normalize etc 

