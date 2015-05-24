Do More:

1) 'Allens-MacBook-Pro:Chapter 12 allenkrauskopf$ less /tmp/ex12.txt'


    Pasta ipsum dolor sit amet ricciolini scialatelli gomito
    
    timpano spaghetti alla chitarra fusilli bucati bavette linguettine mostaccioli perciatelli mezzani pasta mezzelune fiori pillus fusilli cellentani.
    
    Spaghetti croxetti ziti trennette lanterne fiori penne zita bucatini gigli campanelle.
    
    Ricciolini ditalini spaghettini calamarata fettuce torchio marziani lasagne ricciutelle croxetti fusilli perciatelli garganelli gomito.
    
    
    Mezze penne fiorentine conchiglioni linguine sorprese ciriole lasagnotte orzo conchiglioni conchiglie gnocchi penne rigate. Timpano pennette gramigna strozzapreti
    
    ciriole sacchettini maccheroncelli mezzani pasta maltagliati rotini.
    
    Mezzi bombardoni fagioloni tortellini pizzoccheri radiatori orzo farfalloni farfalle casarecce sacchettoni linguettine.
    
    Farfalloni tuffoli spirali trenne spaghetti alla chitarra fettucelle corzetti rigatoncini tortelloni perciatelli rotelle. Pasta al ceppo capelli d'angelo
    
    
    
    Pasta ipsum dolor sit amet ricciolini scialatelli gomito
    
    timpano spaghetti alla chitarra fusilli bucati bavette linguettine mostaccioli perciatelli mezzani pasta mezzelune fiori pillus fusilli cellentani.
    
    Spaghetti croxetti ziti trennette lanterne fiori penne zita bucatini gigli campanelle.
    
    Ricciolini ditalini spaghettini calamarata fettuce torchio marziani lasagne ricciutelle croxetti fusilli perciatelli garganelli gomito.
    
    
    Mezze penne fiorentine conchiglioni linguine sorprese ciriole lasagnotte orzo conchiglioni conchiglie gnocchi penne rigate. Timpano pennette gramigna strozzapreti
    
    ciriole sacchettini maccheroncelli mezzani pasta maltagliati rotini.
    
    Mezzi bombardoni fagioloni tortellini pizzoccheri radiatori orzo farfalloni farfalle casarecce sacchettoni linguettine.
    
    Farfalloni tuffoli spirali trenne spaghetti alla chitarra fettucelle corzetti rigatoncini tortelloni perciatelli rotelle. Pasta al ceppo capelli d'angelo
    
    /tmp/ex12.txt

   
    Allens-MacBook-Pro:Chapter 12 allenkrauskopf$ more /tmp/ex12.txt
    Pasta ipsum dolor sit amet ricciolini scialatelli gomito
    
    timpano spaghetti alla chitarra fusilli bucati bavette linguettine mostaccioli perciatelli mezzani pasta mezzelune fiori pillus fusilli cellentani.
    
    Spaghetti croxetti ziti trennette lanterne fiori penne zita bucatini gigli campanelle.
    
    Ricciolini ditalini spaghettini calamarata fettuce torchio marziani lasagne ricciutelle croxetti fusilli perciatelli garganelli gomito.
    
    
    Mezze penne fiorentine conchiglioni linguine sorprese ciriole lasagnotte orzo conchiglioni conchiglie gnocchi penne rigate. Timpano pennette gramigna strozzapreti
    
    ciriole sacchettini maccheroncelli mezzani pasta maltagliati rotini.
    
    
    
    Mezzi bombardoni fagioloni tortellini pizzoccheri radiatori orzo farfalloni farfalle casarecce sacchettoni linguettine.
    
    Farfalloni tuffoli spirali trenne spaghetti alla chitarra fettucelle corzetti rigatoncini tortelloni perciatelli rotelle. Pasta al ceppo capelli d'angelo
    
    ricciutelle spaghetti pizzoccheri lagane campanelle pennette fettuce occhi di lupo rotelle gigli gramigna pici. Trenette mezzelune linguine lumaconi orzo
    
    sorprese stringozzi penne rigate. Maltagliati fiorentine pillus ditalini fiori fedelini gemelli paccheri fagioloni taglierini.
    
    
    Fettucelle pici ziti rotini zitoni gramigna vermicelli fiori mafaldine cannelloni sagnarelli tripoline capelli d'angelo pastina pappardelle pennette.
    
    Trenette pasta al ceppo chifferi tortellini vermicelli mafalde perciatelli tripoline foglie d'ulivo spaghetti alla chitarra creste di galli pappardelle.
    
    Spirali cellentani spaghetti alla chitarra corzetti linguine ravioli torchio farfalline trenette. Fusilli lunghi tagliatelle torchio pizzoccheri torchio
    
    stringozzi sorprese lisce vermicelli vermicelli conchiglie pici fettuccine mafaldine.


2) Try an empty file

    Allens-MacBook-Pro:Chapter 12 allenkrauskopf$ less ../"Chapter 10"/second_temp/awesome.txt
    ../Chapter\ 10/second_temp/awesome.txt (END)
    
    
English Questions

1) Can we see what's in our production log?

   This time I will look at the production.log in  /console/log
   
   YES. But it's empty.
   
    Allens-MacBook-Pro:Chapter 12 allenkrauskopf$ less ~/console/log/production.log
    /Users/allenkrauskopf/console/log/production.log (END)
    
2) What does our database.yml look like?

   I will look in our /console/config/database.yml

    Allens-MacBook-Pro:Chapter 12 allenkrauskopf$ less ~/console/config/database.yml
    
    # SQLite version 3.x
    #   gem install sqlite3-ruby (not necessary on OS X Leopard)
    development:
      adapter: sqlite3
      database: db/development.sqlite3
      pool: 5
      timeout: 5000
    
    # Warning: The database defined as "test" will be erased and
    # re-generated from your development database when you run "rake".
    # Do not set this db to the same as development or production.
    test:
      adapter: sqlite3
      database: db/test.sqlite3
      pool: 5
      timeout: 5000
    
    production:
      adapter: sqlite3
      database: db/production.sqlite3
      pool: 5
      timeout: 5000
    /Users/allenkrauskopf/console/config/database.yml (END)
    
