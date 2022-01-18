# Introduction to Systems Engineering

## Systems

****

### Overviews

#### Trend of Today's World -- 5 factors

**Systematisation**: There are two directions, one is called macro-systematisation, that is to make the research of system larger and larger; even beyond earth or a system integrated by many other systems, another is called micro-systematisation that the research of system is smaller and smaller that may in the molecular or atom level.

**Engineeringisation**: There are more and more, larger and larger engineering projects in the world. Engineering are not only use to solve traditional industrial manufacturing problems but also introducing to solve some social system problems.

**Informationisation**: By organise and manage a huge-scale, complex-structured system, develop  large and complex engineering project. It is necessary to deal and utilise massive information. 

**Intellectualisation**: Under the supporting  of computer networks, big data and artificial intelligence, systems are given attributes that should satisfied different kinds of requirements of human. Characteristics of intellectualisation is the three-in-one of big data, big computation and big decision.

**Meta-syntheses**: Proposed by academician Qian Xuesen, it is a combination of qualitative and quantitative research. It includes functional syntheses, technology syntheses, management method syntheses,  qualitative research syntheses and quantitative research syntheses. 

### Understanding of System Engineering

Without Engineering, system will lose its application objects and become some abstract concepts. Without information, engineering will just a framework without any products. Information is existing in both system and engineering, its processing and application consists systems and engineerings.

Meta-syntheses is a trend performances in many different ways, mostly it is the multi-functional syntheses in equipment. That it is to combined many different functions in one equipment or system. Intellectualisation is one of the achievement method so that can satisfied more requirements of human.

It also included in system that a system is a combination of different equipment, different equipment will satisfied different requirements. In engineering, nearly all kinds of huge engineering projects are meta-syntheses.

A big system usually included many small systems. Sometime there are some inverse trend for small subsystems in a big system. But the general trend is fixed and systematical. Meta-syntheses allowed decompositions and differentiations in a small part for a system to make the general systematic.

**System Engineering** can be regards as the productions of meta-syntheses, it use system methods to develop engineering projects and solving systematic problems by applying engineering methods.

****

### Systems

#### Definition

System is a complex of many interrelating and interacting factors with specific functions. The complex is called ensemble or population, factors in it are called parts, elements or subsystems. Note that the complex and factors are relative. Since system is usually a system-consisted system nowadays.

#### Attributes

**Collectivity**: System must combine by two or more than two different features.

**Relativity**: There are many connections between features, systems, system and its related environment.

**Hierarchy**: A huge and complex system must have different levels, the relationship between two levels are include and included.

**Entirety**: System appears, exists and affects to environment as a entirety. Any factors or parts that will consisting a system cannot study independently.

**Emergence**: When each parts consist a entirety, it will appear some new features or functions that those parts didn't had. It also appears in different levels inside of a system. When some low level elements consist a high level part, there may have some new features or functions.

**Purpose**: A system must have purposes for system engineering study. It must confirm purposes before build it.

**Adaptability**: In order to survive and develop, a system must adapt its environment.

#### Types

**According to natural qualities:** 

            Natural System: Naturally formed                    

            Social System: Formed when people intervened in nature and play a leading role

    Natural systems and its rules are the basic of social systems.

**According to material properties:**

            Entity System (Hard System): Consist by material entity

            Concept System (Soft System): Some techniques, programs without material entity.

   Entity systems are the basic of concept systems. Concept systems provides guides and services for entity systems.

**According to motion attributes:**

        Open System: There has exchanges and flow  in material, energetic and informative between system and its environment.  

        Closed System: There  is no exchanges between system and environment.

It is hard to find a strict closed system. We sometime ignore some minority exchange phenomenon. There are two kind of flow phenomenons, one is called input or interference that it is the flow from environment to system; another is called output that it is the flow from system to environment. It can be shows as following figure:

<img title="" src="file:///D:/文件/系统工程/1.png" alt="" width="437" data-align="center">

**According to feedback attributes:**

When a system's output influence input, it is called feedback, a feedback that will enhance its input is called negative feedback; a feedback that will reduce its input is called positive feedback. 

        Open Loop System: It is a system without feedback.

        Closed Loop System: It is a system with feedback.

<img title="" src="file:///D:/文件/系统工程/2.png" alt="" data-align="center">

**According to the attributes that the work of human in system:**

        Operational Activities: It is the basic activities for human life and products, it act directly on environments or people themselves; it can also be called "category 1 activities".

        Management Activities: It act on operational activities, it is the layout or organise of operations. it take operational activities as its objects.

**According to their complexity:**

        The system can divided into three types nine levels: 

                1. Physical System: framework, clock, control machinery

                2. Biological System: cell, plant, animal

                3. Human and universe: human, society, universe

**Academician Qian Xuesen's Classify:**

        According to the scale of system, it can divided as: little system, large system and giant system. 

        According to the complexity of system, it can divided as: simple system and complex system.

$$

\text{System}\begin{cases}
  \text{Simple System}\begin{cases}
    \text{Little System}\\
    \text{Large System}\\
    \text{Gaint System}
  \end{cases}\\
  \text{Complex System}\begin{cases}
    \text{Large System}\\
    \text{Gaint System}\begin{cases}
      \text{General Gaint Complex System}\\
      \text{Special Gaint Complex System}
    \end{cases}
  \end{cases}
\end{cases}
$$

It also can be represent as a 3D Cartesian coordinate system:

<img title="" src="file:///D:/文件/系统工程/3.png" alt="" width="290" data-align="center">

According to whether the system is continuous, it can divided into continuous system and discrete system; furthermore, according to the relations between variables, it can divided into linear system and non-linear system.

#### Structures

Generally, a system can be represent as the following equations:

$$
\bm{S}=\left\{\bm{E},\bm{R}\right\} \qquad or \quad \bm{S}=\left\{\bm{E} | \bm{R}\right\}
$$

Here, $\bm{S}$ is called the system, $\bm{E}$ represent the set of elements and $\bm{R}$ represent the relations set above $\bm{E}$.

The set of elements can be divided into many different subset $\bm{E_i}$:

$$
\bm{E}=\bm{E_1} \cup \bm{E_2} \cup ... \cup \bm{E_t}\\
\bm{E_1}=\bm{E_{11}} \cup \bm{E_{12}} \cup ... \cup \bm{E_{1t}}\\
...\\
\bm{E_t}=\bm{E_{t1}} \cup \bm{E_{t2}} \cup ... \cup \bm{E_{tt}}\\
$$

Different have different elements' set, but for relations, it is similar between each element in a system:

$$
\bm{R}=\bm{R_1} \cup \bm{R_2} \cup \bm{R_3} \cup \bm{R_4}
$$

Here, 

        $\bm{R_1}$ is the relations between elements or parts (transversal connections)

        $\bm{R_2}$ is the relations between parts and entirely, low level and high level (vertical connections)

        $\bm{R_3}$ is the relations between system and its environment

        $\bm{R_4}$ is any other relations

Under a scenario that elements is given, by adjusting these relations, it can improve the functions of system. This is the key points of system engineering. 

#### Functions

The functions of a system including the receiving of outside input (matter, energy and information), the processing and transfer inside of system, the output (products, services and etc.).  It can be represent as the following equations:

$$
\bm{Y}=\bm{F}(\bm{X})
$$

Where $\bm{X}$ is the input matters, $\bm{Y}$ is the output services and products, all of these variables: $\bm{X}$, $\bm{Y}$, $\bm{F}$ are vectors, which means a system can have multi-inputs, multi-outputs and multi-processes and transfers methods.

The mission of system engineering is to improve the functions of system, especially the functions of its processes or transfers efficiency. It can be represents as Aristotle's judgements that is the whole is more than the sum of parts:

$$
F > \sum f_i
$$

Where $F$ is the general function of system and $f_i$ is the functions of each independent part.

Note that the optimum of general function of system doesn't means each function in each part of the system must be the best. Furthermore, the optimum in every function for every part does not mean it can get the optimal general function of the whole system.
