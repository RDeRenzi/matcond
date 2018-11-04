# matcond
Concept map of a Condensed Matter course, in Italian

Should this evolev in a sort of course wiki?

Should be written in rst. A copy of the plan from Pmwiki/dispense below

This course is part of the Parma condensed matter master suite of courses, with two specialisations and two subtopics each:  ''crystalline'' (I. magnets and superconductors, II. semiconductors) and ''soft'' matter (I. biophysics, II. other soft structures). The course provides the foundations for the crystalline condensed matter syllabus and is recommended also for the ''soft'' specialisation. Since there is a separate ''Semiconductor Physics and Applications'' course, these special topics are avoided in the present course. Magnetism is also partially covered by ''Statistical Physics'' and ''Magnetism and Quantum Computation''. Therefore the present course contains four general chapters (Crystal Symmetries, Band Theory, Order and Excitations and Hands-on DFT), but focuses on two 
topics (Metals and Metal-Insulator transitions, Superfluids and Superconductors).

The approach includes general surveys of phenomena and properties, the main models and conceptual ideas, simple-case exercises, hands-on with software and web applications, illustration of main experimental techniques to measure the properties.

This course and the wiki are a work in progress. A very first draft is described [[CondensedMatter.CondensedMatter|here]]
This is a [[CondensedMatter.Template|page template]] for internal use.

'''Main textbooks:'''
# U. Rössler  Solid State Theory, An Introduction. Springer Verlag (with physical intuition, good overview; with problems and solutions)
# J.F. Annett  Superconductivity, Superfluids and Condensates. Oxford Master Series (with physical intuition, specific for VI; with exercises and solutions)
# G. Grosso G Parravicini Solid State Physics. Academic Press (more formal, oriented towards semiconductors, good for II. and V.;  with a few solved exercises)
# D. Khomskii Basic Aspects of the Quantum Theory of Solids, Order and Elementary Excitations. Cambridge Press  (mixes physical intuition and a consistent theoretical approach, oriented towards strongly correlated materials, good for IV.)

'''Tentative Lecture List''' (the number.Ch refers to the main textbook inspiration):

* I. Introduction, the viewpoint of this course. Recap on crystals (4 hours 1.Ch1)
** I.1 Crystal symmetries, CIF, The Bilbao Crystallographic Server (1.Ch1.2, 3.Ch2.1-3),
** I.2 Reciprocal lattice (3.Ch.2.4-5), diffraction, VESTA (jmol, xcrystden, ...)

*II. Band Theory (10 hours: 3.Ch4,3.Ch5,1.Ch4.,1.Ch5)
** II.1 Introduction, nanostructures and their bricks. Recap of Tight-Binding and the manybody problem
** II.2 Hartree
** II.3 Slater determinants, Hartree Fock, phase diagram of electron gas
** II.4 LCAO, OPW, Pseudopotentials, APW.
** II.5 Simple examples (3.Ch.6)

* III. Orders and Excitations. (12 hours 1.Ch.)
** III.1 Introduction, excitations as quasiparticles, a founding idea. Recap of Born Oppenheimer approximation linear chains, Einstein e Debye.
** III.2 3d phonons, density of states
** III.3 Magnetic orders 
** III.4 Experimental techniques: thermodynamical, neutrons, X rays, magnetic resonance (3.Ch.10.2)
** III.5 Spin waves 
** III.6 Experimental techniques  (3.Ch.10.4)

* IV. Metals and Metal-Insulator Transitions (8 hour) 
** IV:1 Introduction: the metal as a quantum state and how to break it. Drude and Sommerfeld models (4.Ch.7 )
** IV.2 Dielectric response function: Thomas Fermi and Lindhard (RPA), charge screening
** IV.3 The Landau Fermi liquid and the measurements of fermiology (4.Ch.10)
** IV.3 Heavy fermions (1.Ch7.5)
** IV.4 The Metal-Insulator Transition, with hints on quantum phase transitions (4.Ch12.6-11 and 1.Ch9.2-5)

* V. DFT (8 hours, 3.Ch4, 1.Ch5)
** V.1 Introduction, the importance of computational methods. Kohn-Hohemberg-Sham theorems. Koopmans theorem. Special k-points (3.Ch.2.6.4)
** V.2 Installation of a DFT suite.
** V.3 Hands-on
** V.4 Hellman-Feynman theorem (virtual forces), Hands-on

* VI Superfluids, Condensates and Superconductors (9.5 ore lezione, 4.5 di esercitazione. umbers in parenthesis refer to 2.Ch)
** V.1 Introduction, condensation in composite systems as a new paradigm. Bose-Einstein Condensation, van del Waals classical and quantum fluid (1.3,2.1-2)
** V.2 Macroscopic wave function, properties, flux quantization, vortices, moment distribution and quasiparticles (2.3-7)
** V.3 Zero resistance, Meissner effect, susceptibility, classification and critical fields (3.1-7)
** V.4 London Equations, penetration depth (3.8-9)
** V.5 Ginzburg-Landau Equations, coherence length and gap, macroscopic coherence, Josephson effect (4.1-4,4.6-11,5.8)
** V.6 BCS model, the gap and coherence length (6.1-7, also 1.Ch8.5-6 and 4.Ch11.5)
** V.7 Non-conventional superconductors and future research (7.6, also 4.Ch
