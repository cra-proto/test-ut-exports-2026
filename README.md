# Test UT exports

*description of the project*

**Timeframe** 2026-07-16 - 2026-10-22

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-ut-exports-2026](https://cra-test-arc.canada.ca/test-ut-exports-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-07-30

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Tax credits and benefits for individuals)
    node4(Canada child benefit #40;CCB#41;)
    node5(Keep getting your payments)
    node6(Who can apply)
    node7(How to apply)
    node8(How much you can get)
    node9(Canada child benefit #40;CCB#41; calculation sheets)
    node10(Canada child benefit #40;CCB#41; - calculation sheet for the July 2025 to June 2026 payments #40;2024 base year#41;)
    node11(Canada child benefit #40;CCB#41; and the child disability benefit #40;CDB#41; payment amounts #40;base years 2022-2024#41;)
    node12(Contact us)
    node13(Payment dates)
    node14(Free bananas)
    node15(Overview of child and family benefits)
    node16(Keep your information up to date)
    node17(How to apply for child and family benefits when registering the birth of your newborn with the Automated Benefits Application)
    node18(Child and family benefits calculator)
    node19(Payment dates for CRA administered benefits and credits)
    node20(Canada Revenue Agency #40;CRA#41;)
    node21(CRA Forms and publications)
    node22(CRA forms listed by number)
    node23(CTB9 Income of Non-Resident Spouse or Common-Law Partner for the Canada Child Benefit)
    node24(RC66 Canada Child Benefit Application includes federal, provincial, and territorial programs)
    node25(RC66SCH Status in Canada and Income Information for the Canada Child Benefit Application)
    node26(CRA publications listed by number)
    node27(RC4476-AB Birth Registration and Canada Child Benefits - Alberta)
    node28(Birth Registration and Canada Child Benefits - Alberta)
    node29(RC4476-BC Birth Registration and Canada Child Benefits - British Columbia)
    node30(Birth Registration and Canada Child Benefits - British Columbia)
    node31(RC4476-NT Birth Registration and Canada Child Benefits - Northwest Territories)
    node32(Birth Registration and Canada Child Benefits - Northwest Territories)
    node33(RC4476-YT Birth Registration and Canada Child Benefits - Yukon)
    node34(Birth Registration and Canada Child Benefits - Yukon)
    node35(T4114 Canada Child Benefit and related provincial and territorial programs)
    node36(Canada Child Benefit)
    node37(CRA Multimedia library)
    node38(Podcasts)
    node39(Taxology – Episode 7: Parenting Perks: About the Canada Child Benefit)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node4 --> node6
    node4 --> node7
    node4 --> node8
    node4 --x node9
    node9 --x node10
    node9 --x node11
    node4 --> node12
    node4 --> node13
    node4 --> node14
    node3 --> node15
    node15 --> node16
    node15 --> node17
    node15 --> node18
    node15 --> node19
    node1 --x node20
    node20 --> node21
    node21 --> node22
    node22 --> node23
    node22 --> node24
    node22 --> node25
    node21 --> node26
    node26 --> node27
    node27 --> node28
    node26 --> node29
    node29 --> node30
    node26 --> node31
    node31 --> node32
    node26 --> node33
    node33 --> node34
    node26 --> node35
    node35 --> node36
    node20 --x node37
    node37 --> node38
    node38 --> node39

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6,node7,node8,node9,node10,node11,node12,node13,node14,node15,node16,node17,node18,node19,node23,node24,node25,node27,node28,node29,node30,node31,node32,node33,node34,node35,node36,node39 inscope
    classDef isnew fill:#00706f,color:#fff
    class node14 isnew
    classDef ismoved fill:#eab308,color:#000
    class node10,node11 ismoved
```
