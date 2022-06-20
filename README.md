```
This CBTTAPE File was converted from the CBTTAPE distribution format
so that it could be mirrored for access using GitHub. This is a partially
automated process with some manual adjustments as required by each
individual CBT file.

The Git repository was then created using ZIGI, the z/OS ISPF Git
Interface, which can be found at https://zigi.rocks and which uses the
z/OS OMVS port of Git provided by Rocket software.

Because of this process, any installation documentation or automation
provided with the file may not work as provided and may require some
adjustments.

The CBTTAPE file is distributed as a ZIP file that contains, typically,
an XMIT file. This XMIT file must then be received using TSO RECEIVE to
create a PDS that contains the contents of the CBTTAPE file. Some of the
PDS members are also in the XMIT format.

The 'mirror' process performed the following after the PDS was created:

Automated:
1. Copied the original PDS into a PDS using the Git HLQ
2. The @FILEnnn, or @FILnnnnn, members were copied into a
readme.text dataset (see below under Manual for more on this)
3. Any members with PDF, PPT, ZIP, DOCX, etc. were copied into
individual datasets (see below under Manual for more on this)
4. Any members in XMIT format were processed using TSO RECEIVE into
datasets under the Git HLQ, using the member name as a qualifier.
5. Any members with (4) in XMIT format were also processed using TSO
RECEIVE.
6. All members that were copied out to individual datasets were
deleted, including the XMIT members.

Manual (using ZIGI):
1. The Git repository was created on GitHub without adding any files
so that it is empty on GitHub for now.
2. ZIGI was used to create the repository by adding the datasets
under the Git HLQ to the repository.
3. The ZIGI repository is updated with the GitHub SSH Git URL (1)

Manual (under OMVS):
1. The readme dataset was renamed to README.md for use by Git
2. PDF, PPT, ZIP, etc. were renamed to more meaningful file names with
an appropriate suffix in lower case

Manual (using ZIGI):
1. ZIGI now performs the Git Add, Commit, and Push to the GitHub
repository.


--------------------------------------------------------------------------------
//***FILE 417 is from a team working to make RACF Administration    *   FILE 417
//*           easy for the z/OS Security Administrator.             *   FILE 417
//*                                                                 *   FILE 417
//*  Version 35.3 - Updated 03/18/2022                              *   FILE 417
//*                                                                 *   FILE 417
//*  RACFADM is an open source ISPF Application that makes RACF     *   FILE 417
//*  Administration easy.                                           *   FILE 417
//*                                                                 *   FILE 417
//*  *-----------------------------------------------------*        *   FILE 417
//*  *                   Introduction                      *        *   FILE 417
//*  *-----------------------------------------------------*        *   FILE 417
//*  RACF Administration (RACFADM) makes many security tasks        *   FILE 417
//*  simple.  It lists user, group, data set, and general           *   FILE 417
//*  resource profiles by means of a user-friendly,                 *   FILE 417
//*  menu-driven interface; it provides interactive                 *   FILE 417
//*  modification of most fields.                                   *   FILE 417
//*                                                                 *   FILE 417
//*  Among its features are: connecting groups to a user,           *   FILE 417
//*  adding permissions, user authorization searching across        *   FILE 417
//*  classes, and displaying the group from which an                *   FILE 417
//*  authorization is granted.                                      *   FILE 417
//*                                                                 *   FILE 417
//*  Written in customizable Rexx, RACFADM includes an exec         *   FILE 417
//*  to automate creation of aliases or data sets when              *   FILE 417
//*  creating a new TSO user and can browse all RACF system         *   FILE 417
//*  options from a single, scrollable display.                     *   FILE 417
//*                                                                 *   FILE 417
//*  To begin using execute the RACFADM member found in the         *   FILE 417
//*  EXEC library.                                                  *   FILE 417
//*                                                                 *   FILE 417
//*  *-----------------------------------------------------*        *   FILE 417
//*  *                   Contributors                      *        *   FILE 417
//*  *-----------------------------------------------------*        *   FILE 417
//*                                                                 *   FILE 417
//*            Name                     Website                     *   FILE 417
//*    ----------------------    ---------------------------        *   FILE 417
//*    Nico Rizzuto (Creator)    http://www.rizzuto.it              *   FILE 417
//*    Bruce Koss                                                   *   FILE 417
//*    Bill Smith                                                   *   FILE 417
//*    John Kalinich             http://www.cbttape.org/            *   FILE 417
//*    Lionel B. Dyck            http://www.lbdsoftware.com/        *   FILE 417
//*                              http://github.com/lbdyck           *   FILE 417
//*                              http://www.cbttape.org/            *   FILE 417
//*                                                                 *   FILE 417
//*       NAME       VER.MOD   LAST MODIFIED     SIZE   ID          *   FILE 417
//*       $$README    01.18   2020/06/25 08:54     44 README        *   FILE 417
//*       $DOC        01.02   2020/02/06 09:42     17 INTRO         *   FILE 417
//*       $INSTALL    01.16   2020/06/30 11:45    116 RUNME         *   FILE 417
//*       $MACSTUB    01.00   2020/06/29 10:56      4 ELEMENT       *   FILE 417
//*       $STUB       01.02   2020/06/12 16:30     29 SAMPLE        *   FILE 417
//*       EXEC        01.00   2022/03/28 08:55  20705 XMIT          *   FILE 417
//*       INTRO       01.01   2021/01/04 06:17     31 README        *   FILE 417
//*       MSGS        01.00   2022/03/28 08:55     24 XMIT          *   FILE 417
//*       PANELS      01.00   2022/03/28 08:55   9886 XMIT          *   FILE 417
//*       README      01.00   2020/03/12 06:33     31 README        *   FILE 417
//*       SKELS       01.00   2022/03/28 08:55   2914 XMIT          *   FILE 417
//*                                                                 *   FILE 417
```
