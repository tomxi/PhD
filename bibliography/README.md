# Annotated Bibliography

## Forawrd
My research intuition has led me to the crossroads where **music theory**, **graph theory**, **psychoacoustics**, and **computational audio informatics** meet.
There would naturally be holes in my current grasp of each topics listed above, nonetheless I would like to first build a convincing narrative that showcases the tremendous potential where these topics meet.

### Current Hypothesis
At first glimps, music seem to have several orthalgonal spaces:

- Pitch-Space
    - melody
    - harmony
    - Neo-Riemmanian, post Transformation Theory
    - timbre (in terms of Fundamental/Harmonics relationships)
    - Frequency-Domain Envolopes, MFCC  
- Rythm-Space
    - syncapation/surface rythm
    - grove/meter
    - dynamic
    - articulation
    - Time-Domain Waveform Envolope, ADSR
- Formal/Structral-Space
    - Schenkerian

Each of the above elements have rich structure, and graphs are natural ways of expressing the essence of these relationship.
The fact mathematical graph theory can be successfully used to understand musical relationships has deep roots, making it's way into major branches of contemporary music theory: Neo-Riemannian theories showcase an aspect of the sturcture in the pitch space, while Schenkerian thoeries showcase the sturcture that is the form of a piece of music.

Upon further inspection: pitch, rythm, and form seem to be simply highlight different strctures of the same continuous time-space, understood as oscilliatory patterns in time with different time-scales.
However, being a percieved phenomenon, music is understood through the prism that is the human mind.
While theoretical structures in time-space can exist on any scale, the ~~limitations~~ characteristics of human auditory perception helps delignate the boundries and channels our focus and attention.
The boundry between pitch and rythm, the boundry between rythm and form, I believe, are key psychoacoustic results that can help me better understand music, the phenomenon.

While recognizing the unity of all musical elements, I aim to **promote the individualities** of each of the identified elements, and build different graphs that captures the essense of the strucutre of that individual element.
I aim to understand a musical performance as **~~walks~~ dances on graphs**, with each elements dancing individually in their own relational space that is distilled as a graph/topology that features some relationships of interest. 
In other words, a piece of music can be perceived as multiple independent walks on different graphs all at once. 
Each of these trajectories in the element space might seem trivial, but I argue that music is essentially the multimodal congrunencies/counterpoints that happens between the trajectory of each separable elements in their respective relational space.

Computationally, this could motivate a princle for using existing **digitial representations** of graphs to represent musical pieces as **multi-walks-on-graphs**. 
Many contemporary **Music Informatics** techniques, including neural nets, could be meaningfully applied as soon as an appropriate digital represnetation of music can be codified as concurrent patterned trajectories on meaningful graphs, each capturing the most important relationships of a single element of music.

### Other important themes
- Duality/Multiplicity
    - Chord to Note = Note to Spectrum (French Spectralism Music)
    - Each graph have a dual graph: Note as vertices, Triades as faces = Note as faces, Triades as vertices. 
- All about the Distance
    - Tonnetz can bu put on a torus
    - The vertices of my graphs are really lattice points on a topology, which features a certain aspect of the pitch space's structure.
    - if our current 12-tone systems are lattices points on a continuous space... other tuning systems?
    - once we have a topology, we can quantatativly compare different trajectories on such a topology. 
    These topologies, such as the tonnetz, are what I consider to be the language of a certain musical tradition.
- Equality for All elements
    - One mission of my work is to promote the indepence of each separable musical elements by study their trajectory in their respective spaces individually first before considering the guestault effect that is the multimodal coungruency/counterpoint that is made up of these individual trajectories.

### Bottom line:
A music performance is like a ribbon dance in a (high dimentional) space, and when viewed from different perspectives produces different beautiful patterns, each making sense in their own right.
The beauty of music is such that we can percieve all of these dimensions at once, with ease, and the meaning of music comes from the intereactions between these perspectives.


## Bibliography
---------

### Music Theory

- [x] Cohn, R. L. (2012). _Audacious euphony : chromaticism and the triad's second nature._ New York, Oxford University Press.

    This work establishes the topology of the harmony space by formalizing the concept of distance between triads. 
    Many musical examples and examples of useful graph formulations in the harmony space that is the tonnetz. 
    My foundational text in the Neo-Riemmanian tradition.

- [x] Tymoczko, Dmitri. "A geometry of music: Harmony and counterpoint in the extended common practice." (2010).

- [ ] Tymoczko, Dmitri. "The Generalized Tonnetz." Journal of Music Theory 56.1 (2012).

    The face-vertices, chord-note duality of the pitch space is explicitly stated and explored in this work.
    This work confirms my intuition that there are multiple perspectives of the pitch/harmony space, and the classic tonnetz is just one of many.
    The multiplicity theme applies here, in which I would argue for simutaneous appreciations in all percievalbe tonnetz.
    I would consider recognizing an organization of the pitch space alla tonnetz style as understanding a perticular musical "language". IE chromatic mediants slowly became a part of the chromatisism language by showcasing the relationship embodied by the classic Tonnetz.

- [x] Tymoczko, Dmitri, and Jason Yust. "Fourier phase and pitch-class sum." International Conference on Mathematics and Computation in Music. Springer, Cham, 2019.

    This is my reference text on traditional Schenkerian analysis.

- [x] Yust, J. (2018). Organized time : rhythm, tonality, and form. New York, Oxford University Press.

    This text heavily influenced my understanding of music.
    A relativly new, but highly insirational text that formalizes and promotes the independence of separable elements of music.
    Extending from Neo-Riemmanian and Schenkerian traditions, this work formalizes the use of graph for multiple dimentions of music systematically.

- [ ] Yust, Jason. "Schubert’s harmonic language and Fourier phase space." Journal of Music Theory 59.1 (2015): 121-181.

- [ ] Callender, Clifton. "Continuous harmonic spaces." Journal of Music Theory 51.2 (2007): 277-332.

- [ ] Krumhansl, C. L. and L. L. Cuddy (2010). A theory of tonal hierarchies in music. Music perception, Springer: 51-87.

    This text talks about some relationship in the tonal space that I can leverage to build relational spaces (graphs on topologies).
    This is inline with the Position-finding Pattern-matching philosophy of understanding music, and musical spaces.

- [x] Kopp, David. "On Performing Chopin’s Barcarolle." Music Theory Online 20.4 (2014).

    How neo-riemmanian theory can influence performance.

- [ ] Amiot, Emmanuel. Music through Fourier space. Springer International Publishing Switzerland, 2016.

- [ ] Quinn, Ian. "A unified theory of chord quality in equal temperaments." (2004).

- [ ] Quinn, Ian. "General equal-tempered harmony: parts 2 and 3." Perspectives of New Music (2007): 4-63.

- [ ] Callender, Clifton, Ian Quinn, and Dmitri Tymoczko. "Generalized voice-leading spaces." Science 320.5874 (2008): 346-348.

- [ ] Multivalence stuff

- [ ] Tuning Theory

- [ ] Multimodal stuff
    Congruency and Counterpoint

- [ ] Montiel, Mariana, and Robert W. Peck, eds. "Mathematical Music Theory: Algebraic, Geometric, Combinatorial, Topological and Applied Approaches to Understanding Musical Phenomena." (2018).

- [ ] Eleain Chew
- [ ] GTTM
- [ ] Tonal Pitch Space 

### Graph Theory and Topology
- [ ] [Spectral clustering Tutorial](https://link.springer.com/article/10.1007/s11222-007-9033-z)
- [ ] Fan Chung Spectral graph theory

- [ ] Dan's book

- [ ] Chris Trallie's Trajectory stuff

- [ ] Spectral graph theory and spectral clustering

- [ ] Spectral drawing and distance.

- [ ] Measure Theory

- [ ] Isomap - manifold learning Vincent

- [ ] William: Harmonicity, spectral flux on intervals

### Psychoacoustics
- [ ] human frequency resolution, basis for defining intervals in the pitch space.

- [ ] Krumhansl, Carol L.. Cognitive Foundations of Musical Pitch. United States, Oxford University Press, 2001.

- [ ] Radocy, Rudolf E., and J. David Boyle. "Psychological foundations of musical behavior." (2012).

- [ ] When does pitch turn to rythm? 

- [ ] How out of tune does a interval needs to be? 

### Music Informatics
- [ ] Katie Kinnard Heiarchy

- [ ] Structure Uri

- [ ] Recurence Plot Xerra

- [ ] Footes method

- [ ] Meuller 

- [ ] Brian's structure stuff

- [ ] Modeling the multiscale structure of chord sequences using polytopic graphs [Louboutin]

- [ ] - David Temperley - Rochester Rock Corpus


### Digital Representation
- [ ] Jams

- [ ] NetworkX library

- [ ] [GNN lib for pytorch](https://atcold.github.io/pytorch-Deep-Learning/en/week13/13-3/)

- [ ] Microsoft - GNN [model](https://github.com/microsoft/ptgnn)

- [ ] Multi-task Training

- [ ] Probablity Calibration

- [ ] walk-on-Graph Representation?


## People and Society of Interest
- Mathematics and Computation in Music
- SMPC