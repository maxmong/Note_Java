


----------

Some notes
---------


----------
1.oracle date

    SELECT TO_CHAR
    (SYSDATE, 'MM-DD-YYYY HH24:MI:SS') "NOW"
     FROM DUAL;


----------
2.check current oracle version

    SELECT * FROM V$VERSION
    
    SELECT version FROM V$INSTANCE
    BEGIN
     
    DBMS_OUTPUT.PUT_LINE(DBMS_DB_VERSION.VERSION || '.' ||     DBMS_DB_VERSION.RELEASE); 
    END;
    


----------
VFDV


  

    


