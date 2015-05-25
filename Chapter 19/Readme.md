
English Quateions

1) What option to ls tells it to output file size in human readable form?

         -h      When used with the -l option, use unit suffixes: Byte, Kilobyte,
                 Megabyte, Gigabyte, Terabyte and Petabyte in order to reduce the
                 number of digits to three or less using base 2 for sizes.
                 
2) Is there a case insensitive option to grep?

         -i, --ignore-case
                 Perform case insensitive matching.  By default, grep is case sen-
                 sitive.
                 
3) What does the -r and -f options to rm do exactly?

         -f          Attempt to remove the files without prompting for confirma-
                     tion, regardless of the file's permissions.  If the file does
                     not exist, do not display a diagnostic message or modify the
                     exit status to reflect an error.  The -f option overrides any
                     previous -i options.
                     
         -r          Equivalent to -R.
         
         -R          Attempt to remove the file hierarchy rooted in each file
                     argument.  The -R option implies the -d option.  If the -i
                     option is specified, the user is prompted for confirmation
                     before each directory's contents are processed (as well as
                     before the attempt is made to remove the directory).  If the
                     user does not respond affirmatively, the file hierarchy
                     rooted in that directory is skipped.
                     
   Maybe you can discuss the term "file hierarchy" just to make sure it's understood in the context of 'rm'

4)  What does the ifconfig command do?

    NAME
         ifconfig -- configure network interface parameters
    
    DESCRIPTION
         The ifconfig utility is used to assign an address to a network interface
         and/or configure network interface parameters.

