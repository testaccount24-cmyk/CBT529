# CBT529
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 529 is from Matthew Stitt, and contains some programs     *   FILE 529
//*           to report CICS statistics, and some other programs.   *   FILE 529
//*           Most of these programs are written in COBOL, but      *   FILE 529
//*           they are very useful, for people who need this        *   FILE 529
//*           information.                                          *   FILE 529
//*                                                                 *   FILE 529
//*           There is also a program, CATLIST, to report on        *   FILE 529
//*           the contents of old-style VSAM catalogs, without      *   FILE 529
//*           using IBM's LISTCAT.                                  *   FILE 529
//*                                                                 *   FILE 529
//*           email:  Matthew Stitt <mathwstitt@bellsouth.net>      *   FILE 529
//*                                                                 *   FILE 529
//*   - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -   *   FILE 529
//*                                                                 *   FILE 529
//*   NOTE --  programs in this file reference programs in          *   FILE 529
//*            file 527 on the same CBT mods tape                   *   FILE 529
//*                                                                 *   FILE 529
//*   - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -   *   FILE 529
//*                                                                 *   FILE 529
//*   - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -   *   FILE 529
//*                                                                 *   FILE 529
//*      CATLIST    --     VSAM CATALOG REPORT.  DIRECT ACCESS      *   FILE 529
//*                        TO THE VSAM CATALOG WITHOUT USING        *   FILE 529
//*                        LISTCAT OUTPUT.                          *   FILE 529
//*      CICSMTH    --     CICS STATISTICS REPORTING PROGRAM.       *   FILE 529
//*                        REPORTS ON TRANSACTIONS, TERMINALS,      *   FILE 529
//*                        PROGRAMS, AND FILES ON A MONTHLY         *   FILE 529
//*                        ACCUMULATING BASIS.  FOR CICS/ESA        *   FILE 529
//*                        4.1.                                     *   FILE 529
//*      CICSMTH5   --     CICS STATISTICS REPORTING PROGRAM.       *   FILE 529
//*                        REPORTS ON TRANSACTIONS, TERMINALS,      *   FILE 529
//*                        PROGRAMS, AND FILES ON A MONTHLY         *   FILE 529
//*                        ACCUMULATING BASIS.  FOR CICS/ESA        *   FILE 529
//*                        5.3.                                     *   FILE 529
//*      CICSSMF4   --     PROGRAM TO EXTRACT CICS STATISTICS       *   FILE 529
//*                        RECORDS FROM SMF DATA.  UNLOADS ALL      *   FILE 529
//*                        RECORD TYPES KNOWN.  FOR CICS/ESA        *   FILE 529
//*                        4.1.                                     *   FILE 529
//*      CICSSMF5   --     PROGRAM TO EXTRACT CICS STATISTICS       *   FILE 529
//*                        RECORDS FROM SMF DATA.  UNLOADS ALL      *   FILE 529
//*                        RECORD TYPES KNOWN.  FOR CICS/ESA        *   FILE 529
//*                        5.3.                                     *   FILE 529
//*      CICSYRLY   --     CICS STATISTICS REPORTING PROGRAM.       *   FILE 529
//*                        REPORTS ON TRANSACTIONS, TERMINALS,      *   FILE 529
//*                        PROGRAMS, AND FILES ON A YEARLY          *   FILE 529
//*                        ACCUMULATING BASIS.                      *   FILE 529
//*      CICSMTHJ   --     SAMPLE JCL TO RUN CICSMTH PROGRAM.       *   FILE 529
//*      CICSSMFJ   --     SAMPLE JCL TO RUN CICSSMF PROGRAM.       *   FILE 529
//*      CISIZE     --     VSAM CI SIZE REPORT.  GIVES INDICATION   *   FILE 529
//*                        OF OPTIMUM CI SIZES FOR VSAM DATASETS.   *   FILE 529
//*      DFHCFS6D   --     COPY BOOK.                               *   FILE 529
//*      DFHCFS7D   --     COPY BOOK.                               *   FILE 529
//*      DFHCFS8D   --     COPY BOOK.                               *   FILE 529
//*      DFHCFS9D   --     COPY BOOK.                               *   FILE 529
//*      DFHNCS4D   --     COPY BOOK.                               *   FILE 529
//*      DFHNCS5D   --     COPY BOOK.                               *   FILE 529
//*      DFHSMFDS   --     COPY BOOK.                               *   FILE 529
//*      DFHXQS1D   --     COPY BOOK.                               *   FILE 529
//*      DFHXQS2D   --     COPY BOOK.                               *   FILE 529
//*      DFHXQS3D   --     COPY BOOK.                               *   FILE 529
//*      SMFLST04   --     PROGRAM TO REPORT ON SMF TYPE 04         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*      SMFLST06   --     PROGRAM TO REPORT ON SMF TYPE 06         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*      SMFLST14   --     PROGRAM TO REPORT ON SMF TYPE 14         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*      SMFLST17   --     PROGRAM TO REPORT ON SMF TYPE 17         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*      SMFLST18   --     PROGRAM TO REPORT ON SMF TYPE 18         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*      SMFLST30   --     PROGRAM TO REPORT ON SMF TYPE 30         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*      SMFLST60   --     PROGRAM TO REPORT ON SMF TYPE 60         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*      SMFLST64   --     PROGRAM TO REPORT ON SMF TYPE 64         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*      SMFLST65   --     PROGRAM TO REPORT ON SMF TYPE 65         *   FILE 529
//*                        RECORDS.                                 *   FILE 529
//*                                                                 *   FILE 529
```
