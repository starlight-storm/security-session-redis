# security-session-redis
目的：  
Spring Security, Spring Session, redisを検証する。  

というつもりだったけど、JDBC(H2)も追加してしまった。ので今となってはタイトルは間違っている(^^;)  

検証内容：  
・セッションをredisもしくはH2に格納する。  
・セッション数を制限し、多重ログインを禁止する。  
