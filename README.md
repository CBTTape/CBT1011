# CBT1011
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE1011 is from Dana Mitchell and contains an SDSF exit that  *   FILE1011
//*           tells SDSF to ignore RMF if it is not present.  This  *   FILE1011
//*           has presented a problem when converting from z/OS     *   FILE1011
//*           2.2 to z/OS 2.4.  See members $$NOTE01 and $$REAADME  *   FILE1011
//*           for more details.                                     *   FILE1011
//*                                                                 *   FILE1011
//*           It seems that (lately) when you do a DA under SDSF,   *   FILE1011
//*           then SDSF will sometimes try to use RMF control       *   FILE1011
//*           blocks instead of MVS control blocks.  This causes    *   FILE1011
//*           a nasty message, and we want to get rid of it.        *   FILE1011
//*                                                                 *   FILE1011
//*           email:  Dana Mitchell <mitchdana@gmail.com>           *   FILE1011
//*                                                                 *   FILE1011
//*     Note from Sam Golob:  I have included a "pure assembly      *   FILE1011
//*           and linkedit" job, without SMP/E involvement, so      *   FILE1011
//*           that you can see the structure of the assembly        *   FILE1011
//*           clearly.  This is member ISFUSER$ in this pds.        *   FILE1011
//*                                                                 *   FILE1011
```
