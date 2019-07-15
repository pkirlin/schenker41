# schenker41

This repository contains 41 excerpts of common practice period music, along with machine-readable Schenkerian analyses for 
those excerpts.  These are the data used for Phillip Kirlin's Ph.D. dissertation, *A Probabilistic Model of Hierarchical Music Analysis* (University of Massachusetts Amherst, February 2014).  The dissertation can be downloaded from http://www.cs.rhodes.edu/~kirlinp/diss.html. 

Each piece of music has a MusicXML file that contains the notes of the excerpt, and an analysis file with the Schenkerian analysis of the excerpt. The analyses mainly list the prolongations present in the music. Each prolongation is in the form X (Y) Z where X and Z are lists of notes that are prolonged by the notes in Y. One of X and Z may be absent. The notes in X, Y, and Z are given so that they may be easily located in the MusicXML file. Each note is specified with a measure number, pitch, octave, and occurrence. For instance, 4f#5-2 specifies the second occurrence of the F# in the fifth octave (using scientific pitch notation) of the fourth measure.

```
mozart1	Piano Sonata 11 in A major, K. 331, I, mm. 1-8
mozart2	Piano Sonata 13 in B-flat major, K. 333, III, mm. 1-8
mozart3	Piano Sonata 16 in C major, K. 545, III, mm. 1-8
mozart4	Six Variations on an Allegretto, K. Anh. 137, mm. 1-8
mozart5	Piano Sonata 7 in C major, K. 309, I, mm. 1-8
mozart6	Piano Sonata 13 in B-flat major, K. 333, I, mm. 1-4
mozart7	7 Variations in D major on "Willem van Nassau," K. 25, mm. 1-6
mozart8	Twelve Variations on "Ah vous dirai-je, Maman," K. 265, Var. 1, mm. 23-32
mozart9	12 Variations in E-flat major on "La belle Francoise," K. 353, Theme, mm. 1-3
mozart10	Minuet in F for Keyboard, K. 5, mm. 1-4
mozart11	8 Minuets, K. 315, No. 1, Trio, mm. 1-8
mozart12	12 Minuets, K. 103, No. 4, Trio, mm. 15-16
mozart13	12 Minuets, K. 103, No. 3, Trio mm. 7-8,
mozart14	Untitled from the London Sketchbook, K. 15a, No. 1, mm. 12-14
mozart15	9 Variations in C major on "Lison dormait," K. 264, Theme, mm. 5-8
mozart16	12 Minuets, K. 103, No. 12, Trio, mm. 13-16
mozart17	12 Minuets, K. 103, No. 1, Trio, mm. 1-8
mozart18	Piece in F for Keyboard, K. 33B, mm. 7-12
schubert1	Impromptu in B-flat major, Op. 142, No. 3, mm. 1-8
schubert2	Impromptu in G-flat major, Op. 90, No. 3, mm. 1-8
schubert3	Impromptu in A-flat major, Op. 142, No. 2, mm. 1-8
schubert4	Wanderer's Nachtlied, Op. 4, No. 3, mm. 1-3
handel1	Trio Sonata in B-flat major, Gavotte, mm. 1-4
haydn1	Divertimento in B-flat major, Hob. 11/46, II, mm. 1-8
haydn2	Piano Sonata in C major, Hob. XVI/35, I, mm. 1-8
haydn3	Twelve Minuets, Hob. IX/11, Minuet No. 3, mm. 1-8
haydn4	Piano Sonata in G major, Hob. XVI/39, I, mm. 1-2
haydn5	Hob. XVII/3, Variation I, mm. 19-20
haydn6	Hob. I/85, Trio, mm. 39-42
haydn7	Hob. I/85, Menuetto, mm. 1-8
bach1	Minuet in G major, BWV Anh. 114, mm. 1-16
bach2	Chorale 233, Werde munter, mein Gemute, mm. 1-4
bach3	Chorale 317 (BWV 156), Herr, wie du willt, so schicks mit mir, mm. 1-5
beethoven1	Seven Variations on a Theme by P. Winter, WoO 75, Variation 1, mm.1-8
beethoven2	Seven Variations on a Theme by P. Winter, WoO 75, Theme, mm. 1-8
beethoven3	Ninth Symphony, Ode to Joy theme from finale (8 measures)
beethoven4	Piano Sonata in F minor, Op. 2, No. 1, Trio, mm. 1-4
beethoven5	Seven Variations on God Save the King, Theme, mm. 1-6
chopin1	Mazurka, Op. 17, No. 1, mm. 1-4
chopin2	Grande Valse Brilliante, Op. 18, mm. 5-12
clementi1	Sonatina for Piano, Op. 38, No. 1, mm. 1-2
```
