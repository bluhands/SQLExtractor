# SQLExtractor
Simple static web page to extract SQL query located in String 


<hr>
## Manual
> 1. Copy the whole String.
> 2. Paste it into the textbox of SQLExtractor
> 3. Press Enter


<hr>
## Detail
> * Extractor can ignore both '//'comments and '/* */' comments
> * If you want to finish line, Use a key binding of "Shift + Enter"


<hr>
## Example
```
 String sql = " select                       "
            + "   empName,                   "
      //    + "   empAddr,                   "
            + "   empNo                      "
            + " from emp                     ";  
```

to

```
 select
    empName,
    empNo
 from emp
```


<hr>
## Purpose
The Web application I manage is an old system. So lots of SQL queries are inserted into java String variable.


<hr>
## Contact
neta6603@naver.com
