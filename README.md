# CBT534
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 534 contains the SPACE TSO command from Paul Dion.  This  *   FILE 534
//*           is a very full-featured LSPACE type command which     *   FILE 534
//*           tells you how much free space is on your disk packs.  *   FILE 534
//*                                                                 *   FILE 534
//*      Paul Dion    pdion@canada.com                              *   FILE 534
//*                                                                 *   FILE 534
//*      Fixed for EAV volumes by Ralf Mahler.                      *   FILE 534
//*                   Ralf.Mahler@rewe-group.com                    *   FILE 534
//*                                                                 *   FILE 534
//*      Fixed for large TSO screens and SMS by EWP.                *   FILE 534
//*                                                                 *   FILE 534
//*       This is (yet) another version of the ubiquitous SPACE     *   FILE 534
//*       command that displays DASD volume usage statistics.       *   FILE 534
//*       It can:                                                   *   FILE 534
//*                                                                 *   FILE 534
//*       - cope with DASD devices RESERVEd on other systems        *   FILE 534
//*         without hanging                                         *   FILE 534
//*       - run as a TSO command or batch program                   *   FILE 534
//*       - use EDIF or BRIF to display results                     *   FILE 534
//*       - create machine-readable output (UCB, DCE, LSPACE        *   FILE 534
//*         data, F4DSCB)                                           *   FILE 534
//*       - select devices based on UCB address, Volser,            *   FILE 534
//*         Esoteric or Mount Attribute                             *   FILE 534
//*       - sort results by any of the displayed fields             *   FILE 534
//*                                                                 *   FILE 534
//*       The data presented by the command are:                    *   FILE 534
//*       - UCB address                                             *   FILE 534
//*       - Volser                                                  *   FILE 534
//*       - Device Type                                             *   FILE 534
//*       - Use Attribute                                           *   FILE 534
//*       - Free Trks, Cyls, %                                      *   FILE 534
//*       - Largest Trks, Cyls                                      *   FILE 534
//*       - VTOC Trks, free DSCBs, % free                           *   FILE 534
//*       - VTOC Index status                                       *   FILE 534
//*       - Fragmentation Index                                     *   FILE 534
//*       - SMS Storage Class                                       *   FILE 534
//*       - SMS Volume Status                                       *   FILE 534
//*       - CHPIDs                                                  *   FILE 534
//*                                                                 *   FILE 534
//*         This version of the SPACE command seems to be able      *   FILE 534
//*      to cope with DASD RESERVEd on another system.  This is a   *   FILE 534
//*      non-issue for those installations that have IBM APAR       *   FILE 534
//*      OW48527 installed, which allows the invoker of LSPACE      *   FILE 534
//*      to specify a time-out value (in seconds).  For those       *   FILE 534
//*      installations that do not have the APAR installed, the     *   FILE 534
//*      matter becomes somewhat complicated.                       *   FILE 534
//*                                                                 *   FILE 534
```
