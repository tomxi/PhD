# Annotated Bibliography [WIP, abandoned, see new Annotated Bibliography]

## Preface
My research intuition has led me to the crossroads where **music theory**, **graph theory**, **psychoacoustics**, and **computational audio informatics** meet.
There would naturally be holes in my current grasp of each topics listed above, nonetheless I would like to first build a convincing narrative that showcases the potential where these topics meet.

### Current Hypothesis
At first glimps, music seem to have several orthalgonal spaces:

- Pitch-Space
    - melody
    - harmony
    - Neo-Riemmanian, post Transformation Theory
    - timbre (in terms of Fundamental/Harmonics relationships)
    - Frequency-Domain Envolopes, MFCC  
- Rhythm-Space
    - syncapation/surface rhythm
    - grove/meter
    - dynamic
    - articulation
    - Time-Domain Waveform Envolope, ADSR
- Formal/Structral-Space
    - Schenkerian

Each of the above elements have rich structure, and graphs are natural ways of expressing the essence of these relationship.
The fact mathematical graph theory can be successfully used to understand musical relationships has deep roots, making it's way into major branches of contemporary music theory: Neo-Riemannian theories showcase an aspect of the sturcture in the pitch space, while Schenkerian thoeries showcase the sturcture that is the form of a piece of music.

I aim to **promote the individualities** of each of the identified elements by building different graphs that captures the essense of the strucutre of each individual element.
I aim to understand a musical performance as **~~walks~~ dances on graphs**, with each elements dancing individually in their own relational space that is distilled as a graph/topology that features some relationships of interest. 
Each of these trajectories in their element space might seem trivial, but I argue that music is essentially the multimodal congrunencies/counterpoints that happens between the trajectory of each separable elements in their respective relational spaces.

Computationally, this could motivate a princle for using existing **digitial representations** of graphs to represent musical pieces as **multi-walks-on-graphs**. 
Many contemporary **Music Informatics** techniques, including neural nets, could be potentially meaningfully applied if an appropriate digital represnetation of music can be codified as concurrent patterned trajectories on meaningful graphs, each capturing the most important relationships of a single element of music.

Upon further inspection: pitch, rhythm, and form seem to be simply highlight different strctures of the same continuous time-space, understood as oscilliatory patterns in time with different time-scales.
However, being a percieved phenomenon, music is understood through the prism that is the human mind.
While theoretical structures in time-space can exist on any scale, the ~~limitations~~ characteristics of human auditory perception helps delignate the boundries and channels our focus and attention.
The boundry between pitch and rhythm, the boundry between rhythm and form, I believe, are key psychoacoustic results that can help me better understand music, the phenomenon.

### Other important themes
- Duality/Multiplicity
    - Chord to Note = Note to Spectrum (French Spectralism Music)
    - Each graph have a dual graph: Note as vertices, Triades as faces = Note as faces, Triades as vertices. 
- All about the Distance
    - Tonnetz can be put on a torus
    - The vertices of my graphs are really lattice points on a topology, which features a certain aspect of the pitch space's structure.
    - if our current 12-tone systems are lattices points on a continuous space... other tuning systems?
    - once we have a topology, we can quantatativly compare different trajectories on such a topology. 
    These topologies, such as the tonnetz, are what I consider to be the language of a certain musical tradition.
- Equality for All elements
    - I'd like to promote the indepence of each separable musical elements by study their trajectory in their respective spaces individually first before considering the guestault effect that is the multimodal coungruency/counterpoint, made up of many individual trajectories.

### Bottom line:
A music performance is like a ribbon dance in a (high dimentional) space, and when viewed from different perspectives produces different beautiful patterns, each making sense in their own right.
The beauty of music is such that we can percieve all of these dimensions at once, with ease, and the meaning of music comes from the intereactions between these perspectives.

## Bibliography
---------
NYU Community can access PDFs of (almost) all the following reference via this [shared folder](https://drive.google.com/drive/folders/1SjnwrZBhSEoDpko6KiZn446aZdOYKT_5?usp=sharing) on google drive. 
Access for these PDFs were provided via NYU library.

### Music Theory
Lerdahl, F., & Jackendoff, R. S. (1996). A Generative Theory of Tonal Music, reissue, with a new preface. MIT press. 
> .

Chew, E. (2002). The spiral array: An algorithm for determining key boundaries. International Conference on Music and Artificial Intelligence, Edinburgh, Scotland, UK.
> .

Smith, N. A., & Cuddy, L. (2003). Perceptions of musical dimensions in Beethoven's Waldsiein sonata: An application of Tonal Pitch Space theory. Musicae Scientiae, 7(1), 7-34. 
> .

Lerdahl, F. (2004). Tonal pitch space. Oxford University Press. 
> .

Quinn, I. (2006). General equal-tempered harmony (introduction and part I). Perspectives of New Music, 114-158. 
> .

Szeto, W. M., & Wong, M. H. (2006). A graph-theoretical approach for pattern matching in post-tonal music analysis. Journal of New Music Research, 35(4), 307-321. 
> .

Callender, C. (2007). Continuous harmonic spaces. Journal of Music Theory, 51(2), 277-332. 
> .

Lerdahl, F., & Krumhansl, C. L. (2007). Modeling Tonal Tension. Music Perception: An Interdisciplinary Journal, 24(4), 329-366. https://doi.org/10.1525/mp.2007.24.4.329 
> .

Quinn, I. (2007). General equal-tempered harmony: parts 2 and 3. Perspectives of New Music, 4-63. 
> .

Callender, C., Quinn, I., & Tymoczko, D. (2008). Generalized voice-leading spaces. Science, 320(5874), 346-348. 
> .

Krumhansl, C. L., & Cuddy, L. L. (2010). A theory of tonal hierarchies in music. In Music Perception (pp. 51-87). Springer. 
> .

Tymoczko, D. (2010). A geometry of music: Harmony and counterpoint in the extended common practice. Oxford University Press. 
> .

Cadwallader, A. C., & Gagné, D. (2011). Analysis of tonal music : a Schenkerian approach (3rd ed.). Oxford University Press. 
> .

Cohn, R. L. (2012). Audacious euphony : chromaticism and the triad's second nature. Oxford University Press. 
> .

Tymoczko, D. (2012). The generalized tonnetz. Journal of Music Theory, 1-52. 
> .

Akhmedov, A., & Winter, M. (2014). Chordal and timbral morphologies using Hamiltonian cycles. Journal of Mathematics and Music, 8(1), 1-24. 
> .

Chew, E. (2014). Mathematical and Computational Modeling of Tonality. Springer. 
> .

Kopp, D. (2014). On Performing Chopin’s Barcarolle. Music Theory Online, 20(4). http://www.mtosmt.org/issues/mto.14.20.4/mto.14.20.4.kopp.php 
> .

Yust, J. (2015). Schubert’s harmonic language and Fourier phase space. Journal of Music Theory, 59(1), 121-181. 
> .

Amiot, E. (2016). Music through Fourier space. Springer. 
> .

Brody, C. (2016). Parametric Interaction in Tonal Repertoires. Journal of Music Theory, 60(2), 97-148. 
> .

Herremans, D., & Chew, E. (2016). Tension ribbons: Quantifying and visualising tonal tension. idea, 501, 2. 
> .

Montiel, M., & Peck, R. W. (2018). Mathematical Music Theory: Algebraic, Geometric, Combinatorial, Topological and Applied Approaches to Understanding Musical Phenomena. World Scientific Publishing. 
> .

Yust, J. (2018). Organized time : rhythm, tonality, and form. Oxford University Press. 
> .

Tymoczko, D., & Yust, J. (2019). Fourier Phase and Pitch-Class Sum Mathematics and Computation in Music: 7th International Conference, Madrid, Spain. 
> .

Yust, J. (2020). Generalized Tonnetze and Zeitnetze, and the topology of music concepts. Journal of Mathematics and Music, 14(2), 170-203. 
> .

### Graph Theory and Topology
Chung, F. R., & Graham, F. C. (1997). Spectral graph theory. American Mathematical Soc. 
> Main reference on spectral graph theory. Chapter 1-4 seems perticularly relavent.
> Prio: ch.1-4, High; else, Reference.

Chung, F. (2005). Laplacians and the Cheeger inequality for directed graphs. Annals of Combinatorics, 9(1), 1-19.
> How to form Laplacians for directed graph, if I decided to apply spectral techniques with directed graphs.
> Prio: Low

Von Luxburg, U. (2007). A tutorial on spectral clustering. Statistics and computing, 17(4), 395-416. 
> Consice introduction to spectral clustering.
> Prio: High

Demaine, E. D., Gomez-Martin, F., Meijer, H., Rappaport, D., Taslakian, P., Toussaint, G. T., Winograd, T., & Wood, D. R. (2009). The distance geometry of music. Computational geometry, 42(5), 429-454. 
> Similar to Groove Pizza, this paper talks about rythmic patterns as trajectroy on a circular graph, with the concept of maximually even set.
> Prio: High

Toussaint, G. T. (2013). The Geometry of Musical Rhythm: What Makes a" Good" Rhythm Good? CRC Press. 
> Extendeds the idea from (Demaine et al, 2009). Rhythmic patterns viewed through graphs.
> Prio: Ref

Hughes, J. R. (2015). Using fundamental groups and groupoids of chord spaces to model voice leading. International Conference on Mathematics and Computation in Music, London, UK.
> Introduced how algebraic topology tools (groups, category, homotopy), and how they can work with Music. Studies paths in different musical topologies.
> Prio: High

Bergomi, M. G., Baratè, A., & Di Fabio, B. (2016). Towards a topological fingerprint of music. International Workshop on Computational Topology in Image Context, Springer, Cham.
> Infuses duration into tonnetz, and heavily uses the concept of persistent homology. It is able to generate a digital representation of a musical passage.
> Prio: Med

Cohn, R. (2016). A platonic model of funky rhythms. Music Theory Online, 22(2). https://mtosmt.org/issues/mto.16.22.2/mto.16.22.2.cohn.html
> Using trajectory on simple circle graphs to understand the conception of "funky" rhythm that pervades world music and jazz.
> Prio: Low

Tralie, C. (2016). High-dimensional geometry of sliding window embeddings of periodic videos. 32nd international symposium on computational geometry (socg 2016), Boston, USA.
> By studying sliding window embeddings (short continous segments) of periodic videos with topological tools, repeatable segments can be understood as loops on hypertorus.
> Prio: Med

Louboutin, C., & Bimbot, F. (2017). Modeling the multiscale structure of chord sequences using polytopic graphs. ISMIR, Suzhou, China.
> A graph that showcases metrical positions relationships is used to study heiarchecal relationships of chords.
> Prio: Med

Bendich, P., Gasparovic, E., Harer, J., & Tralie, C. J. (2018). Scaffoldings and spines: organizing high-dimensional data using cover trees, local principal component analysis, and persistent homology. In Research in computational topology (pp. 93-114). Springer. 
> A topological technique of organizing point cloud data, with applications on Music data. 
> Prio: Low

Spielman, D. (2019). Spectral and algebraic graph theory http://cs-www.cs.yale.edu/homes/spielman/sagt/sagt.pdf
> Reference on Spectral Graph Theory.
> Prio: Ref

Wu, Z., Pan, S., Long, G., Jiang, J., & Zhang, C. (2019). Graph WaveNet for Deep Spatial-Temporal Graph Modeling. IJCAI, Macao, China.
> While the graph formulated in this work is a bit different from what's in my conception, it still provides a way of formulating GNNs to perform similar transformations as the WaveNet. WaveNet to me seems like a "unrolled" graph.
> Prio: Low

Xu, B., Tralie, C. J., Antia, A., Lin, M., & Perea, J. A. (2019). Twisty takens: A geometric characterization of good observations on dense trajectories. Journal of Applied and Computational Topology, 3(4), 285-313. 
> Following up on (Tralie, 2016), this is a more general study of trajectory formed in different topologies by sliding window embeddings of time series.
> Prio: Low

Yao, L., & Bendich, P. (2020). Graph Spectral Embedding for Parsimonious Transmission of Multivariate Time Series. 2020 IEEE Aerospace Conference, Big Sky, Montana, USA.
> A little bit outside of my comfort zone, this one introduces a technique called Laplacian Events Signal Segmentation, which is a unsupervised technique that segments time series into events.
> Prio: Med

Wu, Z., Pan, S., Chen, F., Long, G., Zhang, C., & Yu, P. S. (2021). A Comprehensive Survey on Graph Neural Networks. IEEE transactions on neural networks and learning systems, 32(1), 4-24. https://doi.org/10.1109/TNNLS.2020.2978386 
> A survey on what's happening in the GNN world.
> Prio: Ref

### Psychoacoustics
Bregman, A. S. (1994). Auditory scene analysis: The perceptual organization of sound. MIT press.
> Talks about integration of auditory events either temporally or harmonically. Will skim to find more relevant passages.
> Prio: Ref

Thompson, W. F., & Parncutt, R. (1997). Perceptual judgments of triads and dyads: Assessment of a psychoacoustic model. Music Perception, 14(3), 263-280. 
> Perception study of the pitch space taken into account fundamentals, overtones, and subharmonics.
> Prio: Med

Large, E. W., & Jones, M. R. (1999). The dynamics of attending: How people track time-varying events. Psychological review, 106(1), 119. 
> Tackles the issues of how human perceive priodic events with varying rates. How a expressive musical performance doesn't lie on "the grid", nevertheless, the rhythmic relationships can still be clearly perceived.
> Prio: Med

Krumhansl, C. L. (2001). Cognitive foundations of musical pitch. Oxford University Press. 
> .

Large, E. W., & Palmer, C. (2002). Perceiving temporal regularity in music. Cognitive science, 26(1), 1-37. 
> .

Moore, B. C., & Gockel, H. (2002). Factors influencing sequential stream segregation. Acta Acustica United with Acustica, 88(3), 320-333. 
> .

Desain, P., & Honing, H. (2003). The formation of rhythmic categories and metric priming. Perception, 32(3), 341-365. 
> .

Kvifte, T. (2007). Categories and timing: On the perception of meter. Ethnomusicology, 51(1), 64-84. 
> .

McDermott, J. H., Keebler, M. V., Micheyl, C., & Oxenham, A. J. (2010). Musical intervals and relative pitch: Frequency resolution, not interval resolution, is special. The Journal of the Acoustical Society of America, 128(4), 1943-1951. 
> .

Farbood, M. M. (2012). A parametric, temporal model of musical tension. Music Perception, 29(4), 387-428. 
> .

Radocy, R. E., & Boyle, J. D. (2012). Psychological foundations of musical behavior. Charles C Thomas Publisher. 
> .

Parncutt, R., & Hair, G. (2018). A psychocultural theory of musical interval: Bye bye Pythagoras. Music Perception: An Interdisciplinary Journal, 35(4), 475-501. 
> .

### Music Informatics
Yeung, M. M., Foote, J. T., Lienhart, R. W., Cooper, M. L., & Li, C.-S. (2003). Media segmentation using self-similarity decomposition Storage and Retrieval for Media Databases 2003,  Santa Clara, CA, USA.
> .

Serra, J., Serra, X., & Andrzejak, R. G. (2009). Cross recurrence quantification for cover song identification. New Journal of Physics, 11(9), 093017.
> .

Bello, J. P. (2011). Measuring structural similarity in music. IEEE Transactions on Audio, Speech, and Language Processing, 19(7), 2013-2025.
> .

Temperley, D., & Clercq, T. d. (2013). Statistical analysis of harmony and melody in rock music. Journal of New Music Research, 42(3), 187-204.
> .

McFee, B., & Ellis, D. (2014). Analyzing Song Structure with Spectral Clustering. ISMIR, Taipei, Taiwan.
> .

Müller, M. (2015). Fundamentals of music processing: Audio, analysis, algorithms, applications. Springer. 
> Foundational reference in MIR, the chapter 4 is especailly relevant.

Kinnaird, K. M. (2016). Aligned Hierarchies: A Multi-Scale Structure-Based Representation for Music-Based Data Streams. ISMIR, New York City, USA.
> .

Oord, A. v. d., Dieleman, S., Zen, H., Simonyan, K., Vinyals, O., Graves, A., Kalchbrenner, N., Senior, A., & Kavukcuoglu, K. (2016). Wavenet: A generative model for raw audio. arXiv preprint arXiv:1609.03499. 
> .

Kinnaird, K. M. (2017). Examining Musical Meaning in Similarity Thresholds. ISMIR, Suzhou, China.
> .

McFee, B., & Bello, J. P. (2017). Structured Training for Large-Vocabulary Chord Recognition. ISMIR, Suzhou, China.
> .

Bittner, R. M., McFee, B., & Bello, J. P. (2018). Multitask learning for fundamental frequency estimation in music. arXiv preprint arXiv:1809.00381. 
> .

Lostanlen, V. (2018). Eigentriads and Eigenprogressions on the Tonnetz. arXiv preprint arXiv:1810.00790. 
> .

McFee, B., & Kinnaird, K. M. (2019). Improving Structure Evaluation Through Automatic Hierarchy Expansion. ISMIR, Delft, Netherlands.
> .

Tralie, C. J., & McFee, B. (2019). Enhanced hierarchical music structure annotations via feature level similarity fusion. ICASSP 2019-2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Brighton, UK. 
> .

Lostanlen, V., Sridhar, S., McFee, B., Farnsworth, A., & Bello, J. P. (2020). Learning the helix topology of musical pitch. ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Barcelona, Spain. 
> .

Nieto, O., Mysore, G. J., Wang, C.-i., Smith, J. B. L., Schlüter, J., Grill, T., & McFee, B. (2020). Audio-Based Music Structure Analysis: Current Trends, Open Challenges, and Applications. Transactions of the International Society for Music Information Retrieval, 3(1), 246-263. https://doi.org/10.5334/tismir.54 
 > .

### Digital Representation
- [ ] NetworkX library

- [ ] [GNN lib for pytorch](https://atcold.github.io/pytorch-Deep-Learning/en/week13/13-3/)

- [ ] Microsoft - GNN [model](https://github.com/microsoft/ptgnn)