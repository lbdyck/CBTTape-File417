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
