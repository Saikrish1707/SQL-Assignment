1 : ```SELECT * FROM CITY WHERE COUNTRYCODE  = 'USA' AND POPULATION > 100000;```

2: ```SELECT NAME FROM CITY WHERE COUNTRYCODE="USA" AND POPULATION > 120000;```

3: ```SELECT * FROM CITY;```

4: ```SELECT * FROM CITY WHERE ID =1661;```

5: ```SELECT * FROM CITY WHERE COUNTRYCODE = "JPN";```

6: ```SELECT NAME FROM CITY WHERE COUNTRYCODE="JPN";```

7: ```SELECT CITY, STATE FROM STATION;```

8: ```SELECT DISTINCT CITY FROM STATIONWHERE MOD(ID,2)=0;```

9: ```SELECT COUNT(CITY) - COUNT(DISTINCT CITY) FROM STATION;```

10: ```select CITY,LENGTH(CITY) from STATION order by LENGTH(CITY),CITY ASC LIMIT 1;```<br>
$~~~~~~$```select CITY,LENGTH(CITY) from STATION order by LENGTH(CITY) DESC, CITY LIMIT 1;```

11: ```SELECT DISTINCT CITY FROM STATION WHERE CITY RLIKE '^[aeiouAEIOU]';```

12: ```SELECT DISTINCT CITY FROM STATION WHERE CITY RLIKE '[aeiouAEIOU]$';```

13: ```SELECT DISTINCT CITY FROM STATION WHERE CITY NOT REGEXP '^[aeiouAEIOU]'```

14: ```SELECT DISTINCT CITY FROM STATION WHERE UPPER(SUBSTR(CITY, LENGTH(CITY), 1)) NOT IN ('A','E','I','O','U') AND LOWER(SUBSTR(CITY, LENGTH(CITY),1)) NOT IN ('a','e','i','o','u');```

15: ```SELECT DISTINCT CITY FROM STATION WHERE LOWER(SUBSTR(CITY,1,1)) NOT IN ('a','e','i','o','u') OR LOWER(SUBSTR(CITY, LENGTH(CITY),1)) NOT IN ('a','e','i','o','u'); ```

16: ```SELECT DISTINCT CITY FROM STATION WHERE LOWER(SUBSTR(CITY,1,1)) NOT IN ('a','e','i','o','u') AND LOWER(SUBSTR(CITY,LENGTH(CITY),1)) NOT IN ('a','e','i','o','u');```

17: ``` ```

18: ``` ```

19: ``` ```

20: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```

2: ``` ```
