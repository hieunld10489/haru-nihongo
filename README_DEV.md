# システムを使用する。
    Apache 2.4.33
    Mysql 5.7.21
    Framework CakePHP 3.6.11 Red Velvet.
        Version 5.6.0 or higher [detected 7.2.4].
        Has the mbstring, openssl, intl extension loaded.
    
## Folder permission
    webroot, logs, tmp directory are writable && readable.
    permission 777

## Sql database
    src: db/structure.sql (structure and insert user)
    run all sql
    login user
        super|123456
        admin|123456

## Config connect [db && mail]
    src: config/app.php
        DEBUG: status = false (on svn version)
        Datasources [config username, password]
        EmailTransport[default][config username, password]
        Email[from] -> mail address
        
## Config paths [logs && tmp]
    src: config/paths.php
        if want to change
        LOGS [config LOGS routes]
        TMP [config TMP routes]
        ...

## Url test
    test: ...
    honban: ...
    
## 本番revision && last svn up
    date svn up  | rv
    -------------------
    2018/06/28   | 1470
