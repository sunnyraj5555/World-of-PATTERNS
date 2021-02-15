# World-of-PATTERNS

## 1. PATTERN 1

```
*
* *
* * *
* * * *
* * * * *
```

```cpp
       for (int i=1; i<=n; i++)
       {
		
		for (int j=1; j<=n; j++)
              {
			
			if (j<=i) 
				cout <<"*";
			else
				cout <<" ";
		}
		cout <<endl;		
	}
```
## 2. PATTERN 2

```
        *
      * *
    * * *
  * * * *
* * * * *
```

```cpp
       for (int i=1; i<=n; i++)
       {
		
		for (int j=1; j<=n; j++)
              {
			
			if (j>=(n+1)-i) 
				cout <<"*";
			else
				cout <<" ";
		}
		cout <<endl;		
	}
```

## 3. PATTERN 3

```
* * * * *
  * * * *
    * * *
      * *
        *
```

## 4. PATTERN 4

```
* * * * *
* * * *
* * *
* *
*
```
