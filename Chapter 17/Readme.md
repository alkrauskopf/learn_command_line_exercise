
English Questions

1)  Can you show me all the files in slash temp slash foo?

   First I needed to recreate foo directory and add some files in it.
   
    Allens-MacBook-Pro:Chapter 17 allenkrauskopf$ mkdir /tmp/foo
    Allens-MacBook-Pro:Chapter 17 allenkrauskopf$ cp ../*.txt /tmp/foo
    Allens-MacBook-Pro:Chapter 17 allenkrauskopf$ ls /tmp/foo
    mpg_list.txt	txt_list.txt	txt_list_2.txt	yml_list.txt
    Allens-MacBook-Pro:Chapter 17 allenkrauskopf$ find /tmp/foo -name "*.txt" -print
    /tmp/foo/mpg_list.txt
    /tmp/foo/txt_list.txt
    /tmp/foo/txt_list_2.txt
    /tmp/foo/yml_list.txt
    Allens-MacBook-Pro:Chapter 17 allenkrauskopf$
    

2) What log files are in your log directory?

    Allens-MacBook-Pro:Chapter 17 allenkrauskopf$ find ~/console/log -name "*.log" -print
    /Users/allenkrauskopf/console/log/production.log
    /Users/allenkrauskopf/console/log/server.log
    /Users/allenkrauskopf/console/log/test.log
    Allens-MacBook-Pro:Chapter 17 allenkrauskopf$
    
