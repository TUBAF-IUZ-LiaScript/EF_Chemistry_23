<!--
author:   Dr. Mark Jacob
email: mark.jacob@iuz.tu-freiberg.de
version:  0.0.1
language: en
narrator: UK English Female
comment: Content of week 3 WS 2023/2024
icon: https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/TUBAF_Logo.svg/800px-TUBAF_Logo.svg.png
script:   https://cdn.jsdelivr.net/npm/mermaid@10.5.0/dist/mermaid.min.js
import: https://raw.githubusercontent.com/liaScript/mermaid_template/master/README.md
-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://github.com/TUBAF-IUZ-LiaScript/EF_Chemistry_23/blob/main/Chemistry_concept_maps.md)

# Concept maps

## sample map

```mermaid @mermaid
flowchart TB
    classDef someclass fill:#f96;
    A[Concrete] --> B
    A:::someclass --> C
    C[Language] --> V[Words]
    C --> W[Interaction]
    V --> I[Etymology]
    I --> AD[com lat. = together]
    AD:::someclass --> AK
    I --> AE(cretus lat. = grown)
    AE:::someclass --> AK[grown together]
    AK:::someclass
    
    V --> J[Collocations]
    J --> I
    J --> reinforced:::someclass 
    P --> R[Processes]
    R --> AK
    R --> AP[Inputs & Outputs]
    W --> P[Describing]
    J --> P
    W --> Q[Discussing]
    Q --> AG[Argumentation]
    AG --> AP
    AP --> S[Presentations]
    AP --> AQ[Texts]
    AQ <--> AR[Concept maps]
    S --> AI
    S <--> AR
    
    B[Subject] --> D[Composition]
    D --> N[Aggregate]:::someclass 
    D --> O[Cement]:::someclass 
    B --> E[Production]
    E --> L[Mixing]:::someclass 
    E --> M[Curing]:::someclass 
    B --> F[Structure]
    F --> AA[Homogeneity]:::someclass 
    F --> AB[Porosity]:::someclass 
    B --> G[Properties]
    G --> X[high compressive strength]:::someclass 
    G --> Y[Water resistant]:::someclass 
    B --> H[Applications]
    H --> Z[Dams]:::someclass 
    H --> AC[Furnaces]:::someclass 
    D --> E
    E --> F
    F --> G
    G --> H
    B --> AH
    H --> AH[Impacts]
    AH --> AJ[Economic]:::someclass    
    AH --> AI[Environmental]:::someclass 
    X --> Z
    Y --> Z
```

## Concept map AJ

```mermaid @mermaid
flowchart TD
    A{Tiktaalik} -->|ancient fish| B(dead by now)
    D --> C(clearly an intermediate between fish & vertebrates)
    A --> D(fins becoming connected to spine)
    D-->|had|F(wrist & elbow joints)
    C -->|unexpected | E[different from past reconstruction]
A-->G(fossil embedded in rock)
  G-->H(new x-ray scans on spine)
   H-->E
   H-->|spotted|I(new features)
   I-->J(pelvis and spine close together)
   J-->K(like fish)
   J-->|but|L(similar to land animal)
   K-->M{perfectly positions tiktaalik as intermediate in evolutionary tree}
   L-->M
```

## Concept map JH

```mermaid @mermaid
flowchart TD
    A[endometriosis]-->D[hormonal conditions ]
    B[premenstrual syndrome]--> D[hormonal conditions]
    C[polycystic ovary syndrome PCOS]--> D[hormonal conditions]
    D-->|poorly understood| E[problems that affect the female body]
    E-->|not all are neglected| F[breast cancer more funded than prostate cancer]
    D-->|effect quality if life|G[unpredictable periods]
    G-->|or|H[weight gain]
    H-->|or|I[excess body hair PCOS]
    I-->|or|J[excruciating pian of endometriosis]
    C-->K[long term consequences]
    D-->|complex|L[acting in different cells in different ways]
    L--> M[difficult for studies]
    M-->|but with tools today|N[find ways to improve the lives of millions of people]
    J-->|but eith tools today|N
```

## Concept map MKl

```mermaid @mermaid

```

## Concept map MZ

```mermaid @mermaid
flowchart TD
    A{Soil bacteria
     enzyme generates 
    electrcity from hydrogen
     in the air} -->|make energy| B(could power fuel cells or generators)
     A -->|called| C[Huc]
    A --> D[consume hydrogen to make their energy take in about
     60 million tonnes of gas globally each year]

    C -->|Melbourne university| E[iron and nickel based enzyme]
    E --> H[unclear how it works]
    H--> |scientific analysis| F
    H --> |scientific analysis|G[resistant to gases like oxigen and carbon monoxide]
    C -->|able to| F[break down hydrogen into electrons]
    H--> |scientific analysis| I[works in temperatures from freezing to 80°C]
    H --> |scientific analysis|J[consruction of electrical curcuits]
    J--> B 
```

## Concept map SJ

```mermaid @mermaid

```

## Concept map LF

![c](images/concept_map_1.png)

## Concept map JK

```mermaid @mermaid
flowchart TD
A[mystery about photosynthesis] --> B(4 particles of light) 
    B --> C[hit protein complex - PSII]-->D[H2O -> O2] --> E{What happens after 4th photon
    hits PSII?}-->|x-rays|F[delay between splitting H2O and formation of O2]-->G[oxygen forms new structure]--> H[O bound to another part of PSII]-->|computer simulations|I[new step: O and PSII exchange three protons for one electron]
```

## Concept map LL

```mermaid @mermaid
mindmap
  root((Depression))
    Symptoms
      Core features: low mood and not enjoying usual activities
      ::ico
      physical symptoms 
        apppetite loss, fatigue, insomnia
    Cause 
      Theory of "chemical imbalance"
        long time treated with chemical antidepressants increas level of specific brain chemical
        low levels of serotonin in the brain contributes to depression 
            considered false due to new studies
      Theory of "inflamed brains"
        simply explained due to a systemic inflammation the whole body responds with the urge to rest und protect the whole body 
```

## Concept map NW

```mermaid @mermaid
flowchart TD
    A[SpaceX] --> |developes|B{Project Starship}
    I[Elon Musk] --> |oversees|B
    I --> |Founder|A
    B --> G[Early Prototypes]
    B --> D{First Test Fail}
    C[Organsisations] --> |Founding|B
    G --> E(Tests)
    F --> |Redesign|G
    E --> |Failure|F[Analysis]
    E --> |Success|H[Full Scale Prototype]
    H --> J[Tests]
    J --> D
    A --> |expected|D
    D --> L[Identify Problem]
    D --> |Liftoff|K[Proof of Concept]
    L --> |Redesign|J
```

## Concept map SR

```mermaid @mermaid

```

## Concept map CK

```mermaid @mermaid
flowchart TD
    A[gender equality in science ] -->|90% by men | B(publishing papers )
    B -->|percentage of articles from woman increasing | C(years that this field reach gender parity )
    C -->|biology| D[2069]
    C -->|chemistry| E[2087]
    C -->|physics | F[2158]
    C --> |engineering| G[2144]
    C --> |other fields | H[2146-2158]
    B --> I(solutions for equality )
    I --> J[change in recruiting and promoting ] 
    B --> K(benefits of equality )
    K--> |more presentable |L[changes in research ]
```

## Concept map HB

```mermaid @mermaid
flowchart TD
    A[Plant spotting apps] --> B[identify plants from photos]
    B --> C[mostly less than 90% accuracy]
    C -->|can lead to| E[Poisoning]
    C ---> D[Ai isn´t trained perfectly]
    C -->|can lead to| F[killing important species]
    D -->|due to| G[few data for many species]
    D -->|due to| H[wrong labelled data from the internet] 
```

## Concept map FB

```mermaid @mermaid
flowchart TD

    B{Toxoplasma gondii} ---> |to be found in| A[Cat faeces]
    B ---> E[deadly parasite]
    E --->F[marine animals]
    E --->G[land animals]
    F ---H[Otters]
    A ---->|when rainy/stormy|I[Parasite into groundwater/rivers]
    I ---> |vector infection|J[bivales]
    J ---> |gets eaten|H
    H ---> |chronicial infection|O[first 4 Otters died]
    O ---> |found, 170km apart from eachother|M[California]
    H---> |on land|GH[gets infection directly by contact]
    GH --->|chronicial infection|O

```

## Concept map SG

```mermaid @mermaid

```

## Concept map MKa

```mermaid @mermaid

```