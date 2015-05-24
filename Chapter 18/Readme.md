English Questions

1) Show me the lines in foo.txt that have "ERROR" in them.

   first I create new foo.txt and bar.txt files from earlier chapters.
   
    Allens-MacBook-Pro:Chapter 18 allenkrauskopf$ cp ../"Chapter 12"/ex12_b.txt foo.txt
    Allens-MacBook-Pro:Chapter 18 allenkrauskopf$ cp ../"Chapter 13"/ex13.txt bar.txt
    

    Allens-MacBook-Pro:Chapter 18 allenkrauskopf$ grep ERROR foo.txt
    Begin ERROR Text File "B"
    Trenette pasta al ceppo ERROR chifferi tortellini vermicelli mafalde perciatelli tripoline foglie d'ulivo spaghetti alla chitarra creste di galli pappardelle.
    Spaghetti ERROR alla chitarra foglie d'ulivo lasagnette foglie d'ulivo bucatini ciriole pizzoccheri chifferi gemelli.
    penne gomito ricciutelle ERROR pennette gomito tuffoli. Cavatappi lasagnette fettuccine mezzani pasta calamarata lumache.
    Mezzi ERROR bombardoni lagane taglierini calamarata penne rigate corzetti rotini trenne capelli d'angelo pillus capunti cellentani. Capelli d'angelo torchio lanterne mezzani pasta radiatori.
    Foglie ERROR d'ulivo lagane spaghettoni sorprese penne lisce rigatoni spaghetti elicoidali fiorentine fettuccine lumache.
    - -  End Of ERROR Foo File - -
    
2) Show me the lines in bar.txt that have "davinci" in them

    Allens-MacBook-Pro:Chapter 18 allenkrauskopf$ grep davinci bar.txt
    Begin Chapter 18  davinci bar File
    Pasta ipsum dolor davinci sit amet ricciolini scialatelli gomito
    Spaghetti davinci croxetti ziti trennette lanterne fiori penne zita bucatini gigli campanelle.
    timpano davinci spaghetti alla chitarra fusilli bucati bavette linguettine mostaccioli perciatelli mezzani pasta mezzelune fiori pillus fusilli cellentani.
    timpano spaghetti davinci alla chitarra fusilli bucati bavette linguettine mostaccioli perciatelli mezzani pasta mezzelune fiori pillus fusilli cellentani.
    - -  End of Chapter 18 davinci bar File - -
    
3)Can you print all the lines in text files that have your first and last name in them?

    Allens-MacBook-Pro:Chapter 18 allenkrauskopf$ grep "Allen Krauskopf" *.txt
    
    
  Can't figure out how to start the search from the home directory...  Below didn't seem to work.
  
    Allens-MacBook-Pro:Chapter 18 allenkrauskopf$ grep "Allen Krauskopf" ~/*.txt
    
4) What does the -i option accomplish for grep.

   'grep' is case sensitive by default. The -i option tells 'grep' to be case insensitive.
    
   
   
