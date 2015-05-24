Dore More

1)  Try 'cat' multiple files

    Allens-MacBook-Pro:Chapter 13 allenkrauskopf$ cat ex13.txt ../"Chapter 12"/ex12_b.txt
    Begin Chapter 13 Text File
    Pasta ipsum dolor sit amet ricciolini scialatelli gomito
    timpano spaghetti alla chitarra fusilli bucati bavette linguettine mostaccioli perciatelli mezzani pasta mezzelune fiori pillus fusilli cellentani.
    Spaghetti croxetti ziti trennette lanterne fiori penne zita bucatini gigli campanelle.
    Ricciolini ditalini spaghettini calamarata fettuce torchio marziani lasagne ricciutelle croxetti fusilli perciatelli garganelli gomito.
    Pasta ipsum dolor sit amet ricciolini scialatelli gomito
    timpano spaghetti alla chitarra fusilli bucati bavette linguettine mostaccioli perciatelli mezzani pasta mezzelune fiori pillus fusilli cellentani.
    Spaghetti croxetti ziti trennette lanterne fiori penne zita bucatini gigli campanelle.
    Ricciolini ditalini spaghettini calamarata fettuce torchio marziani lasagne ricciutelle croxetti fusilli perciatelli garganelli gomito.
    Pasta ipsum dolor sit amet ricciolini scialatelli gomito
    timpano spaghetti alla chitarra fusilli bucati bavette linguettine mostaccioli perciatelli mezzani pasta mezzelune fiori pillus fusilli cellentani.
    Spaghetti croxetti ziti trennette lanterne fiori penne zita bucatini gigli campanelle.
    Ricciolini ditalini spaghettini calamarata fettuce torchio marziani lasagne ricciutelle croxetti fusilli perciatelli garganelli gomito.
    
    - -  End of Chapter 13 Text File - -
    Begin Chapter 12 Text File "B"
    
    Fettucelle pici ziti rotini zitoni gramigna vermicelli fiori mafaldine cannelloni sagnarelli tripoline capelli d'angelo pastina pappardelle pennette.
    Trenette pasta al ceppo chifferi tortellini vermicelli mafalde perciatelli tripoline foglie d'ulivo spaghetti alla chitarra creste di galli pappardelle.
    Spirali cellentani spaghetti alla chitarra corzetti linguine ravioli torchio farfalline trenette. Fusilli lunghi tagliatelle torchio pizzoccheri torchio
    stringozzi sorprese lisce vermicelli vermicelli conchiglie pici fettuccine mafaldine.
    
    Spirali croxetti bavettine stringozzi sorprese lisce capelli d'angelo perciatelli farfalloni rigatoncini tortellini rotini pici calamarata gomito stringozzi maccheroncelli.
    Spaghetti alla chitarra foglie d'ulivo lasagnette foglie d'ulivo bucatini ciriole pizzoccheri chifferi gemelli.
    Perciatelli bavettine mezzani pasta paccheri calamaretti spaghettoni radiatori. Spaghetti linguine ricciolini cannelloni penne spiralini gnocchi pasta al ceppo cellentani
    rigatoncini spaghetti alla chitarra campanelle gomito mezzelune mezzi bombardoni. Pastina gramigna sorprese lisce trenette pici chifferi penne ciriole cavatappi tripoline mezze
    penne gomito ricciutelle pennette gomito tuffoli. Cavatappi lasagnette fettuccine mezzani pasta calamarata lumache.
    Sacchettini penne lasagnette fiorentine mafaldine acini di pepe tortiglioni capelli d'angelo cavatelli.
    
    Mezzi bombardoni lagane taglierini calamarata penne rigate corzetti rotini trenne capelli d'angelo pillus capunti cellentani. Capelli d'angelo torchio lanterne mezzani pasta radiatori.
    Lasagnotte perciatelli capelli d'angelo conchiglioni lumache spaghettini cavatelli.
    Foglie d'ulivo lagane spaghettoni sorprese penne lisce rigatoni spaghetti elicoidali fiorentine fettuccine lumache.
    Spaghetti croxetti ziti trennette lanterne fiori penne zita bucatini gigli campanelle.
    Ricciolini ditalini spaghettini calamarata fettuce torchio marziani lasagne ricciutelle croxetti fusilli perciatelli garganelli gomito.
    
    - -  End Of Chapter 12 - -
    Allens-MacBook-Pro:Chapter 13 allenkrauskopf$
 
English Questions

1) Can you show me the contents of database.yml?

   Instead I'll show you the contents of a different yml file I have.
    
    Allens-MacBook-Pro:Chapter 13 allenkrauskopf$ cat ~/TCPJ_Project/trunk/db/migrate/dev_data/coop_apps.yml
    
    CORE:
        id: 1
        name: Core System
        abbrev: CORE
        is_available: 1
        owner_id: 33
        is_beta: 0
        is_folderable: 1
    
    CLASSROOM:
        id: 2
        name: Class Offering
        abbrev: CLASSROOM
        is_available: 1
        owner_id: 33
        is_beta: 0
        is_folderable: 1
    
    IFA:
        id: 3
        name: Integrated Formative Assessment
        abbrev: IFA
        is_available: 1
        owner_id: 33
        is_beta: 0
        is_folderable: 0
    
    ITA:
        id: 4
        name: Integrated Teacher Assessment
        abbrev: ITA
        is_available: 0
        owner_id: 33
        is_beta: 1
        is_folderable: 0
    
    BLOG:
        id: 5
        name: Blogs
        abbrev: BLOGS
        is_available: 1
        owner_id: 33
        is_beta: 0
        is_folderable: 0
    
    CTL:
        id: 6
        name: Collaborative Time In Learning
        abbrev: CTL
        is_available: 1
        owner_id: 33
        is_beta: 0
        is_folderable: 0
    
    DLE:
        id: 7
        name: Discovery & Action Learning Process
        abbrev: PD
        is_available: 0
        owner_id: 33
        is_beta: 0
        is_folderable: 0
    
    STAT:
        id: 8
        name: School Time Analysis
        abbrev: STAT
        is_available: 1
        owner_id: 33
        is_beta: 1
        is_folderable: 0
    
    CM:
        id: 9
        name: Client Management
        abbrev: CM
        is_available: 1
        owner_id: 33
        is_beta: 1
        is_folderable: 0
    
    ELT:
        id: 10
        name: Expanded Learning Time
        abbrev: ELT
        is_available: 1
        owner_id: 33
        is_beta: 1
        is_folderable: 0
   
    Allens-MacBook-Pro:Chapter 13 allenkrauskopf$
    
    
2)  What is in your Gemfile?

   Couldn't find a Gemfile. Need to learn more what they look like.  So I just made a sample for Chapter 13.
   
    Allens-MacBook-Pro:Chapter 13 allenkrauskopf$ cat Gemfile_sample.txt
    
    This is a sample Gemfile for Chapter 13
    Allens-MacBook-Pro:Chapter 13 allenkrauskopf$
                      
                      
