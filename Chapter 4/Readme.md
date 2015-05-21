1) Can you make a temp directory?

   Yes. I first made the Chapter 4 directory, then the Temp directory.  
   Followed by a bunch of other subdirectories

    Allens-MacBook-Pro:learn_command_line_exercise allenkrauskopf$ cd Chapter\ 4
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ ls
    Readme.md
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir temp
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir temp/stuff
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir temp/stuff/thing
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir temp/stuff/things
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/stuff/things/frank/joe/alex/john
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/stuff/thing_2
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/stuff/thing_3
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/stuff/thing_3/t01
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/stuff/thing_3/t02
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/stuff/thing_3/t03
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/stuff/thing_2/t212
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/stuff/thing_2/t22
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir temp/"morestuff"
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir temp/"more stuff"
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir temp/"more stuff"/things/jeff
    mkdir: temp/more stuff/things: No such file or directory
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$ mkdir -p temp/"more stuff"/things/jeff
    Allens-MacBook-Pro:Chapter 4 allenkrauskopf$


2) Can you make a log directory in your class directory?


  Yes. I first change my directory (using cd) to go to the class directory. 
  Then I mkdir log
  
    Allens-MacBook-Pro:davinci_coders_t2_2015 allenkrauskopf$ mkdir log
    Allens-MacBook-Pro:davinci_coders_t2_2015 allenkrauskopf$ ls
    Icon?				log
    building_the_toolbelt_t2_2015	my_name.txt
    homework			practice
    in_class
    Allens-MacBook-Pro:davinci_coders_t2_2015 allenkrauskopf$
