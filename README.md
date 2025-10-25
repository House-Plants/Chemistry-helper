This code was created in Google Colab, so the current code only works on that site.
You can manually edit the code so that it is usable on other compilers or sites.
Here is current version link:
https://colab.research.google.com/drive/1nLMeATPg07cPCmy4LkyTdgqEZm_nrYf8#scrollTo=DG_N9wXq4eYd

Currently, the code is on version 2.4

List of updates

V1.0
  - Automatically balances chemical equations
  - Calculates molar ratio and guesses states

V2.0
  - Redid the chemical equation balancer, calculator for molar ratio, and state guesser.
  - Included an algorithm that guesses the type of chemical reaction.
  - Added a main lobby

V2.1
  - Added the ability for one to draw organic structures

V2.2
  - Added a programme that displays the electron clouds

V2.3
  - Added a programme that displays the probability density of a particle in a potential well
  - Added formula sheet

V2.4
  - Refurbished the graphing calculator and fixed some bugs

V3.0
  - Added an improved version of the drawer (alpha)
      - It now show the molecules in 3D
      - It can use both CSAL and TSAL
          - CSAL being raw data with angle coordinates.
               - i.e:
               - Chlorobenzene - C*90[C:50[C*90[Cl]*310[C:270[C*230[C:130[C*90[C]]]]]]]
               - PH4+          - P*Z90[H]*z340.5[H]*120z340.5[H]*240z340.5[H]
               - H2O           - O*106z320[H]*z320[H]
               - Glucose (IMPV)- C*300[C*Z90[O*225[H]]*0[C*Z270[O*300z330[H]]*Z90[H]*60[C*Z270[O*35z330[H]]*Z90[H]*120[O*180[C*Z90[C*90[H]*z340[H]*180z30[O*180z330[H]]]*240[C*Z90[H]]]]]]]*Z270[O*195z330[H]]
          - TSAL being only bonding data.
               - i.e:
               - Benzene       = C[H,C[H,C[H,C[H,C[H,C[H,C]]]]],C]
               - Pentane       = C[H,H,C[H,C[H,H,C[H,C[H,H,H],H]],H],H]
               - Glucose       = O[X,C[X,C[X,X,H,O[H,X,X]],C[H,O[X,H,X],H],H],C[C[C[C,X,O[X,X,H],H],X,H,O[X,H,X]],X,H,O[X,H,X]]]
               - X being a lone pair

