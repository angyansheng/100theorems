AYS's Top 100 Theorems in Mathematics (in progress)
======

Triggered by Paul and Jack Abad's 1999 list of [The Hundred Greatest Theorems](http://pirate.shu.edu/~kahlnath/Top100.html), I have ventured to compile my own Top 100 list.\
Since I'm not the Fields Medal Committee (and even if I were), I make no claim to objectivity. Indeed, this list reveals much more about my math education and exposure than the 'intrinsic worth' of the theorems (whatever that means).\
My criteria for selection are roughly: historical significance of the result; connections to different areas of math; relevance to current research; but most importantly, whether I've heard of it before.

Perhaps unconventionally, dates generally refer to discovery, not publishing.\
/ indicates independent discovery, while , indicates building on top of previous work.\
? indicates that I'm not sure if the result belongs in the final list.

As of 2020-05-14, there are 66 theorems on this list.

------

## Antiquity (6)

__Thales's theorem__ (~600 BC)\
_"If C is a point on a semicircle with diameter AB, then ACB is a right angle."_
- Earliest mathematical theorem attributed to a person
- According to legend, Thales sacrificed an ox for the occasion of proving this result

__Pythagoras's theorem__ (~500 BC)\
_"In a right triangle, the square of the hypotenuse is equal to the sum of the squares of the other sides."_
- Theorem with the largest number of known proofs
- Known to many cultures in antiquity, eg. Mesopotamia, India, China
- According to legend, Pythagoras sacrificed an ox for the occasion of proving this result

__Irrationality of sqrt(2)__ (~500 BC)\
_"There does not exist two integers whose ratio has square equal to 2."_
- Throwing a wrench in the Pythagorean doctrine that 'all is [rational] number'
- According to legend, Pythagoras sacrificed Hippasus for the occasion of proving this result

__Classification of Platonic solids__ (Theaetetus ~400 BC)\
_"There are exactly 5 regular convex polyhedra."_
- Construction is non-trivial, eg. why does the dodecahedron close up properly?
- The final book of Euclid's Elements was devoted to proving this

__Area of a circle__ (Archimedes ~250 BC)\
_"The area of a circle is equal to the area of a right triangle with the radius as height and the circumference as base."_
- Archimedes's method of exhaustion anticipates infinitesimal calculus
	- _"The area of a parabolic segment is 2/3 the area of its bounding parallelogram"_
	- _"3 + 10/71 < π < 3 + 1/7,"_ using regular 96-gons
	- _"The volume of a sphere is 2/3 the volume of its circumscribing cylinder;"_ according to legend, the diagram was engraved on his tombstone.

__Quadratic formula__ (various, eg. Brahmagupta 628, al-Khwarizmi ~825)\
_"Solving the equation ax<sup>2</sup>+bx+c = 0"_
- Completing the square was known to Babylonians (~1700 BC)
- Brahmagupta gave the first formula in words, equivalent to: _"The solution to ax<sup>2</sup>+bx = c is x = (sqrt(b<sup>2</sup>+4ac)-b)/(2a)."_
- al-Khwarizmi first considered all cases (ax<sup>2</sup> = bx, ax<sup>2</sup> = c, bx = c, ax<sup>2</sup>+bx = c, ax<sup>2</sup>+c = bx, bx+c = ax<sup>2</sup>)
- This was before the invention of zero and negative numbers
- Modern form _"x = (-b+-sqrt(b<sup>2</sup>-4ac))/(2a)"_ first given by Heaton (1896)

------

## 16<sup>th</sup> Century (1)

__Solution of the cubic__ (Tartaglia 1530)\
_"Solving the equation x<sup>3</sup>+ax<sup>2</sup>+bx+c = 0"_
- First derived for a cubic-solving contest (!)
- Tartaglia divulged his method to Cardano in 1539, but died before he could publish it himself
- Cardano's student Ferrari used this to solve the quartic equation in 1540
- Led to the development of the theory of complex numbers (Cardano 1545, Bombelli 1572)

------

## 17<sup>th</sup> Century (5)

__Logarithms__ (Napier 1614)\
_"There is a function log:R<sup>+</sup>→R such that log(ab) = log(a) + log(b)."_
- Reduces multiplication to addition in hand calculations (using tables of logarithms and antilogarithms)
- Napier's first table took 20 years to compute (!)
- The idea of logarithms as exponents of a fixed base came much later (Euler ~1730)
- Slide rules operate on the same principle, and were widely used calculational aids into the 1970s

__Fermat's right triangle theorem__ (<1665)\
_"The area of a right triangle with integer sides cannot be a square."_
- Proof discovered posthumously in his copy of Diophantus's Arithmetica (along with his Last Theorem)
- Only known complete proof by Fermat (!)
- Equivalent to _"the difference of two fourth powers cannot be a positive square,"_ which implies the n = 4 case of Fermat's last theorem
- Illustrates the method of infinite descent, which he extensively developed

__Fundamental theorem of calculus__ (various, eg. Newton 1665-66, Leibniz 1675)\
_"Differentiation and integration are inverse to each other."_
- cf. __Generalised Stokes's theorem__

__Taylor's theorem__ (Gregory 1671/Taylor 1715)\
_"If f:R→R is n-times differentiable at x, then
f(x+h) = a<sub>0</sub> + a<sub>1</sub>h + ... + a<sub>n</sub>h<sup>n</sup> + g(h)h<sup>n</sup>,
where a<sub>i</sub> = f<sup>(i)</sup>(x)/i! (f<sup>(i)</sup> denotes the i<sup>th</sup> derivative of f), and g(h) → 0 as x → 0."_
- Generalises best linear approximation to f(x+h) (namely f(x) + f'(x)h)
- Previously known special cases: 
	- trigonometric functions (Parameshvara ~1400)
	- logarithm (Mercator 1668)
	- binomial series (Newton 1670)
- Remainder term only obtained later (eg. Lagrange 1797, Cauchy 1825)

__Brachistochrone problem__ (Bernoulli/Bernoulli/Leibniz/Newton/de l'Hopital 1697)\
_"The curve of fastest descent between two points is the cycloid."_
- Posed by Galileo in 1638, where he (incorrectly) derived the answer as the arc of a circle; posed again by Johann Bernoulli in 1696
- Solved by Newton in one night; he published this anonymously, but Bernoulli 'recognised a lion from his claw mark'
- The ensuing dispute between brothers Johann and Jakob Bernoulli sowed the seeds for the calculus of variations
- Led to the development of the Euler-Lagrange equations (Euler 1744, Lagrange 1760)

------

## 18<sup>th</sup> Century (3)

__Konigsberg bridges problem__ (Euler 1735)\
_"A graph contains a path passing through each edge exactly once if and only if it has exactly 0 or 2 vertices of odd degree."_
- Pioneering result in graph theory; first use of the concept of a graph
- Proof of 'if' direction first given by Hierholzer (<1871)

__Euler product for the zeta function__ (Euler 1737)\
_"The sum of n<sup>-s</sup> over the positive integers is equal to the product 1/(1-p<sup>-s</sup>) over the primes."_
- Corollary: _"The sum of 1/p over the primes is divergent."_
- Precursor to analytic number theory
- cf. __Dirichlet's theorem on arithmetic progressions__, __Prime number theorem__

__Bayes's theorem__ (Bayes 1763/Laplace 1774)\
_"P(A|B) = P(B|A)P(A)/P(B)."_
- Introduced concept of conditional probability
- Used in Bayesian inference: update probability of hypothesis given state of knowledge
- Laplace also developed the Bayesian interpretation of probability (What is probability? Baby don't hurt me)

------

## 19<sup>th</sup> Century (21)

__Fundamental theorem of arithmetic__ (Euclid ~300 BC, al-Farisi ~1300, Gauss 1801)\
_"Every integer greater than 1 can be uniquely written as a product of primes."_
- Key lemmas were present in Euclid's Elements
- First clearly stated and proved in Gauss's Disquisitiones Arithmeticae

__Quadratic reciprocity__ (Gauss 1801)\
_"Let p and q be distinct odd primes, and consider the equations
x<sup>2</sup> = p (mod q), y<sup>2</sup> = q (mod p).
If at least one of p,q is 1 (mod 4), then either both equations have solutions or both do not. If p = q = 3 (mod 4), then exactly one of the two equations has a solution."_
- Theorem with second largest number of known proofs, after Pythagoras's theorem (Gauss himself had 8)
- Attempts to generalise this result motivated developments in algebraic number theory

__Fundamental theorem of algebra__ (Argand 1806)\
_"Every non-constant polynomial with complex coefficients has at least one complex root."_
- Corollary: _"Every non-constant polynomial of degree n with complex coefficients has exactly n complex roots (counted with multiplicity)."_
- Gauss's 1799 thesis contains a proof attempt, but assumes a topological result

__Fourier series__ (1807)\
_"Any 2π-periodic function f:R→R can be represented as
f(x) ~ a<sub>0</sub>/2 + [a<sub>1</sub>cos(x) + b<sub>1</sub>sin(x)] + [a<sub>2</sub>cos(2x) + b<sub>2</sub>sin(2x)] + ...,
where a<sub>n</sub> is twice the average value of f(x)cox(nx), and b<sub>n</sub> is twice the average value of f(x)sin(nx)."_
- ie. Periodic functions can be decomposed as a sum of sines and cosines
- Fourier used this to solve the boundary value problem for the heat equation
- Analogue for continuous frequency gives the Fourier transform
- Equivalently: _"f can be expressed as
  f(x) ~ ... + f<sub>-1</sub>e<sup>-ix</sup> + f<sub>0</sub> + f<sub>1</sub>e<sup>ix</sup> + ...,
  where f<sub>n</sub> is the average value of f(x)e<sup>-inx</sup>."_
- Developments in analysis guided by search for sufficient conditions for the convergence of Fourier series:
	- Riesz-Fischer (1907): If f is in L<sup>2</sup>, then the Fourier series converges in L<sup>2</sup> norm.
	- Carleson (1966), Hunt (1968): If f is in L<sup>p</sup>, then the Fourier series converges pointwise almost everywhere.
- Modern viewpoint: eigenfunction decomposition for the Laplace operator

__Insolubility of the quintic__ (Ruffini 1799, Abel 1824)\
_"There is no general solution in radicals to polynomial equations of degree at least 5."_
- The end of an era in algebra, which was concerned with solving polynomial equations (hence the name '__Fundamental theorem of algebra__')
- cf. __Fundamental theorem of Galois theory__

__Cauchy integral theorem__ (Cauchy 1825, Goursat 1900)\
_"For any holomorphic function defined on a simply-connected region in C, the contour integral along any closed rectifiable curve is equal to 0."_
- Holomorphic: complex differentiable
- Corollaries:
	- _"Every holomorphic function is infinitely differentiable."_
	- _"Every holomorphic function is complex analytic, ie. is equal to its power series about an interior point of its domain."_
	- Cauchy integral formula (in particular, _"The values of a holomorphic function inside a disk is determined by its values on the boundary."_)
	- Cauchy residue theorem
- Fundamental result in complex analysis

__Theorema Egregium__ (Gauss 1827)\
_"The Gaussian curvature of a surface is invariant under local isometries."_
- Latin for 'Remarkable Theorem'
- Gaussian curvature: product of maximum and minimum curvature at a point on a surface
- ie. Gaussian curvature is an intrinsic property of a surface, independent of its embedding into the ambient space
- Corollary: _"There is no map projection preserving all distances."_
- Fundamental result in differential geometry

__Fundamental theorem of Galois theory__ (1830)\
_"The intermediate fields of a finite Galois field extension correspond to subgroups of its Galois group."_
- Abel-Ruffini left open the question of characterising equations which admit solutions by radicals
- That was solved in spectacular fashion by Galois, pioneering methods in group theory
- Galois then promptly died from a duel, at age 20, for a girl who didn't even like him (What is love? Baby don't hurt me)
- Modern reformulation, in terms of field extensions instead of roots of polynomials, due to Weber (1895) and Artin (1942)
- cf. __Insolubility of the quintic__

__Independence of the parallel postulate__ (Gauss ~1813/Bolyai 1823/Lobachevsky 1826, Beltrami 1868)\
_"The parallel postulate cannot be proven from the other axioms of Euclidean geometry."_
- Parallel postulate: given a line and a point not on it, there exists exactly one line through the given point parallel to the given line; equivalent to Euclid's fifth axiom
- Thought to be less self-evident than Euclid's other axioms, so many attempts were made to prove it
- Saccheri (1733) proved many theorems assuming that the parallel postulate is false, but thought they were 'repugnant to the nature of straight lines'
- The idea of a consistent non-Euclidean geometry (ie. without the parallel axiom) was first conceived by Gauss, but never published
- First published independently by Lobachevsky (1829) and Bolyai (1832)
- Beltrami constructed an Euclidean model of hyperbolic geometry, showing that Euclidean and non-Euclidean geometry have equal logical validity
- Effect of this paradigm shift was felt in philosophy, physics, and theology, in re-evaluating the status of Euclidean geometry as absolute truth

__Dirichlet's theorem on arithmetic progressions__ (1837)\
_"If a and d are coprime integers, then there are infinitely many primes congruent to a (mod d)."_
- Proof by investigating properties of Dirichlet L-functions, a generalisation of the zeta function
- Pioneering result in analytic number theory: using methods of analysis to solve number theory problems
- cf. __Euler product for the zeta function__

__Riemann-Roch theorem__ (Riemann 1857, Roch 1865)\
_"Calculating the dimension of the space of meromorphic functions on a Riemann surface with prescribed zeros and poles"_
- Spawned many generalisations, eg. to algebraic curves (Schmidt 1931), algebraic varieties (Hirzebruch 1954), coherent cohomology (Grothendieck 1957), differential topology (Atiyah-Singer 1963)
- cf. __Atiyah-Singer index theorem__

__Unique factorisation of ideals__ (Kummer 1847, Dedekind 1871)\
_"Every nonzero proper ideal in the ring of integers of a number field admits a unique factorisation into a product of nonzero prime ideals."_
- Motivated by Fermat's last theorem, Kummer introduced 'ideal numbers' to account for failure of unique factorisation in rings of integers, and proved the result for cyclotomic fields
- cf. __Fermat's last theorem__

__Nowhere differentiable functions__ (Weierstrass 1872)\
_"The Weierstrass function is continuous but nowhere differentiable."_
- The concept of a function had shifted in the past century, from 'analytic expression' to 'continuous function' to the modern definition
- This result contradicted the widely held belief that continuous functions were differentiable at almost all points
- Weierstrass is widely regarded as the father of modern analysis, placing it on rigorous foundations

? __Jordan curve theorem__ (1887)\
_"Any simple closed curve in the plane divides it into exactly two connected regions."_
- Dramatic example of an intuitively obvious statement which is hard to prove
- Main difficulty lies in pathological examples, eg. nowhere-differentiable curves (Weierstrass function, 1872; Koch curve, 1904), curves with positive area (Osgood curves, 1903)
- Demonstrates the rise of rigour in late 19<sup>th</sup> century development of analysis

__Cantor's theorem__ (1891)\
_"There is no surjection from any set to its power set."_
- ie. there are 'different sizes' of infinity
- Corollary: _"The set of real numbers is uncountable"_ (Cantor 1874)
- Short proof using the now-famous diagonal argument
- Leads to Cantor's paradox (the collection of all sets is not a set), foreshadowing the foundational crisis in mathematics (What is a set? Baby don't hurt me)

__Arzela-Ascoli theorem__ (Ascoli 1883-84, Arzela 1895)\
_"A family of continuous real-valued functions on [a,b] is uniformly bounded and equicontinuous if and only if every sequence has a uniformly convergent subsequence."_
- Introduced notion of equicontinuity
- A compactness result for function spaces, anticipating the development of functional analysis

__Hilbert basis theorem__ (1888)\
_"If R is a Noetherian ring, then the polynomial ring R[X] is also Noetherian."_
- Invariant theory: studies invariants of algebraic expressions under linear change of variables
	- eg. _"The discriminant b<sup>2</sup>-4ac of the binary quadratic form ax<sup>2</sup> + bxy + cy<sup>2</sup> is invariant under a linear change of coordinates for (x,y) with determinant 1. In fact, every such invariant is a polynomial in the discriminant."_
- Hilbert used this result to show that every space of invariant polynomials is finitely generated
- On the non-constructive nature of Hilbert's proof, Gordan famously remarked: 'This is not mathematics, it is Theology!'
- (Who would win? 20 years of calculations  or  3 pages of abstraction)

__Minkowski's convex body theorem__ (1889)\
_"Every convex body in R<sup>n</sup> which is symmetric with respect to the origin and has volume greater than 2<sup>n</sup> contains a nonzero point with integer coordinates."_
- Foundational result for Minkowski's geometry of numbers, studying rings of algebraic integers

__Generalised Stokes's theorem__ (Volterra 1889)\
_"The integral of a differential form over the boundary of an orientable manifold is equal to the integral of its exterior derivative over the manifold."_
- Special cases: fundamental theorem of calculus, divergence theorem, Green's theorem, Stokes's theorem
- Differential form: something that can be integrated over a manifold (eg. line, surface)
- Introduced by Cartan (1899), differential forms are fundamental in the study of smooth manifolds
- cf. __Fundamental theorem of calculus__

__Hilbert's Nullstellensatz__ (1893)\
_"There is a one-to-one correspondence between algebraic varieties in C<sup>n</sup> and radical ideals in C[X<sub>1</sub>,...,X<sub>n</sub>]."_
- German for 'zero-locus theorem'
- (Affine) algebraic variety: common zero locus of a set of polynomials in n variables
- Corollary: _"If f, f<sub>1</sub>, ..., f<sub>k</sub> are n-variable polynomials over C, such that f vanishes identically on the common zero locus of f<sub>1</sub>, ..., f<sub>k</sub>, then
  f<sup>r</sup> = g<sub>1</sub>f<sub>1</sub> + ... + g<sub>k</sub>f<sub>k</sub>
  for some integer r and polynomials g<sub>1</sub>, ..., g<sub>k</sub>."_
- Corollary: _"Affine algebraic varieties are determined up to isomorphism by their coordinate rings (polynomials restricted to the variety)."_
- Fundamental result in algebraic geometry, linking algebraic varieties (geometry) with coordinate rings (algebra)

__Classification of semisimple Lie algebras__ (Killing 1888-90, Cartan 1894)\
_"Every simple Lie algebra over C either lies in one of the infinite families A<sub>n</sub>, B<sub>n</sub>, C<sub>n</sub>, D<sub>n</sub>, or is one of E<sub>6</sub>, E<sub>7</sub>, E<sub>8</sub>, F<sub>4</sub>, or G<sub>2</sub>."_
- Lie group: smooth manifold with compatible group structure
- Lie algebra: corresponds to tangent space at identity; 'infinitesimal transformations'
- Fundamental result in Lie theory; leads to classification of semisimple Lie groups
- Can be stated in simpler terms with Dynkin diagrams (1947)

? __Picard-Lindelof theorem__ (1894)\
_"The initial-value problem
y'(t) = f(t,y(t)), y(t<sub>0</sub>) = y<sub>0</sub>
has a unique solution around t0 if f is uniformly Lipschitz in y and continuous in t."_
- aka. the existence and uniqueness theorem for first-order ODEs

__Prime number theorem__ (Hadamard 1896/de la Vallee Poussin 1896)\
_"The number of prime numbers up to N is asymptotic to N/ln N."_
- Carrying out Riemann's programme from his seminal 1859 paper: properties of the analytic extension of the zeta function yield prime asymptotics
- The crowning achievement of 19<sup>th</sup> century analytic number theory
- Later proofs (Erdos 1948/Selberg 1948) circumvent the use of complex analytic methods
- cf. __Euler product for the zeta function__

------

## Early 20<sup>th</sup> Century (13)

__Central limit theorem__ (various, eg. Cauchy 1853, Chebyshev 1887, Markov 1898, Lyapunov 1901)\
_"The sum of n independent random variables with mean 0 and variance 1, divided by sqrt(n), is distributed as the standard normal in the limit (under certain conditions)."_
- Independent of the distribution of the given random variables; explains the universality of the bell curve in statistics
- Successive weakening of hypotheses, eg. finiteness of support, finiteness of moments
- Different versions track the development of classical and modern probability theory

__Classification of compact surfaces__ (various, eg. Dehn-Heegaard 1907)\
_"Compact surfaces are determined (up to homeomorphism) by orientability and Euler-Poincare characteristic."_
- Topology: the study of properties of geometrical objects preserved under continuous deformation (homeomorphism)
- Several proof attempts were made previously (eg. Mobius 1863, Jordan 1866, von Dyck 1888); rigour was difficult to achieve, since the modern concepts of 'surface' and 'homeomorphism' weren't definitively reached until 1930
- Classification of families of spaces is a central goal of topology; the classification of higher dimensional manifolds is considerably harder

__Uniformisation theorem__ (Poincare 1907/Koebe 1907)\
_"Every simply connected Riemann surface is biholomorphic to the plane, the open disc, or the sphere."_
- Riemann surface: complex manifold of (complex) dimension 1
- Motivated by the problems of parametrising algebraic curves over C (Klein), and discrete subgroups of PSL(2,R) (Poincare)
- Corollary: _"Every Riemann surface admits a conformal metric of constant curvature."_

__Lebesgue dominated convergence theorem__ (1908)\
_"Let (f<sub>n</sub>) be a sequence of real-valued measurable functions which converge pointwise to f. If there exists an integrable function g such that |f<sub>n</sub>| ≤ g for all n, then the Lebesgue integral of |f<sub>n</sub>-f| tends to 0."_
- In his 1902 thesis, Lebesgue introduces measure theory and a new notion of integration
- Lebesgue integration is more general and has better properties than Riemann integration (such as this result)

__Noether's theorem__ (1915)\
_"Every continuous family of symmetries of a physical system gives rise to a conservation law."_
- Examples:
	- translational invariance → conservation of momentum
	- rotational invariance → conservation of angular momentum
	- time invariance → conservation of energy
- Illustrates the fundamental importance of symmetry in physics
- Gauge theories are based on 'gauge symmetries' built into the theory, and are among the most successful physical theories (eg. the Standard Model)

? __Polya enumeration theorem__ (Redfield 1927/Polya 1937)\
_"Counting the number of orbits of a group action"_
- Generalises Burnside's lemma (Cauchy 1845/Frobenius 1887)

__Ramsey's theorem__ (1928)\
_"For any k, every colouring of edges of a sufficiently large complete graph in two colours contains a monochromatic clique of size k."_
- eg. _"In any group of 6 people, either 3 of them are mutual friends or 3 of them are mutual strangers."_
- First result in Ramsey theory, the study of existence of given substructures

__Godel's incompleteness theorems__ (Godel 1931)\
_"If a consistent axiomatic system is strong enough to express elementary arithmetic, then there are statements it can neither prove nor disprove; in particular, it cannot prove its own consistency."_
- Arithmetisation of logic: statements and proofs can be represented as numbers, and thus can be discussed within the system itself
- Dooming Hilbert's program of formalising all of mathematics in a complete, consistent and decidable way
- cf. __Halting problem__

__Halting problem__ (Turing 1936)\
_"There is no general algorithm to decide whether a Turing machine halts on a given input in finite time."_
- One of the first problems proven to be undecidable; shows the limits of computability
- Especially significant in the context of the Church-Turing thesis: _"everything that is intuitively computable is computable with a Turing machine"_ (What is computability? Baby don't hurt me)
- cf. __Godel's incompleteness theorems__

__Sobolev embedding theorem__ (1938)\
_"Conditions for embedding one Sobolev space into another"_
- Sobolev space: (completion of) the space of functions with bounds on derivatives up to some order
- Sobolev inequalities: trade smoothness for integrability
- Important in the theory of weak solutions of PDEs

__Ito's lemma__ (1944)\
_"If X<sub>t</sub> is a Wiener process and F(x,t) is a twice-differentiable function, then dF(X<sub>t</sub>,t) = F<sub>t</sub> dt + F<sub>x</sub> dX + F<sub>xx</sub>/2 dt."_
- ie. Chain rule for stochastic calculus
- Stochastic calculus: extension of calculus to random processes
- Wiener process: Brownian motion, the continuous-time analogue of a random walk
- First two terms are same as ordinary chain rule; quadratic correction term arises from Var(X<sub>t</sub>) = t
- Applications in mathematical finance, eg. Black-Scholes equation for options (1970)

__Shannon's noisy channel coding theorem__ (1944)\
_"Any noisy communications channel has a maximum rate of information transmission, below which there exist error-correcting codes such that the probability of error at the receiver can be made arbitrarily small, and above which no such codes exist."_
- Introduced the notion of entropy from statistical mechanics to quantify information
- Shannon's 1948 paper single-handedly created the field of information theory
- Direct applications to coding theory, including data compression and error detection/correction

__Erdos's lower bound for Ramsey numbers__ (1947)\
_"There exists a 2-coloring of the edges of any complete graph on C*k*2<sup>k/2</sup> vertices with no monochromatic k-clique."_
- Proof sketch: almost every random colouring works
- Early example of Erdos's powerful probabilistic method
- The current best known lower bound is only a factor of 2 bigger than this! (Compare to the upper bound, which is ~4<sup>k</sup>)

__Existence of Nash equilibria__ (von Neumann-Morgenstern 1944, Nash 1950)\
_"Any n-player game with a finite set of actions has a mixed-strategy Nash equilibrium."_
- Foundational result in game theory
- von Neumann-Morgenstern's 1944 text created the field of game theory, and proved this for 2-player zero-sum games
- Nash proves this generalisation in his one-page long (!!) 1950 paper
- Applications in diverse fields, such as evolutionary biology and economics

------

## Late 20<sup>th</sup> Century (17)

__Cartan's theorems A and B__ (1951)\
_"A: A coherent sheaf F over a Stein manifold X is locally finitely generated by its local sections.
 B: The sheaf cohomology H<sup>p</sup>(X,F) is zero in dimensions p > 0."_
- Foundational in the theory of functions in several complex variables, and in sheaf cohomology
- Immediately solved the two Cousin problems (1895) for several complex variables
- Partial progress by the German complex analysts using technical arguments were rendered obsolete: 'the French have tanks and we have bows and arrows!'

__Yoneda lemma__ (1954)\
_"For any functor F from a locally small category C to Set, and any object A in C, the natural transformations Nat(Hom(A,-),F) are in bijection with the elements of F(A), and this bijection is natural in A and F."_
- 'The hardest triviality in mathematics'
- Corollary: _"The maps out of an object uniquely determine the object (up to unique isomorphism),"_ ie. 'Tell me who your friends are, and I will tell you who you are.'
- Category theory: abstracts mathematical structures (eg. sets, groups, topological spaces) to categories, containing objects and morphisms
- Categorical concepts and language are now indispensable in mathematics

? __Roth's theorem__ (1955)\
_"For any irrational algebraic number x and any c > 0, there are only finitely many integer solutions to |x-p/q| < 1/q^(2+c)."_
- ie. algebraic numbers cannot be too well-approximated by rationals

__Long exact sequence of a derived functor__ (Cartan-Eilenberg 1956)\
_"Given a left-exact functor F, any short exact sequence
0 → A → B → C → 0
gives rise to a long exact sequence
0 → F(A) → F(B) → F(C) → R<sup>1</sup>F(A) → R<sup>1</sup>F(B) → R<sup>1</sup>F(C) → R<sup>2</sup>F(A) → ..."_
- R<sup>i</sup>F: i<sup>th</sup> derived functor of F
- Unified various examples where a short exact sequence gives rise to a long exact sequence, eg. in homology
- More broadly, their text Homological Algebra unified previous homology theories and revolutionised the field

? __GAGA theorem__ (Serre 1956)\
_"The category of coherent algebraic sheaves on a complex projective variety is equivalent to the category of coherent analytic sheaves on the corresponding analytic space."_
- Corollary: (Chow 1949) _"Analytic subvarieties of complex projective n-space are algebraic sets."_

__Feit-Thompson theorem__ (1963)\
_"Every finite group of odd order is solvable."_
- Proof was 255 pages long, which was unprecedented in group theory
- Provided a plausible opening to attack the full classification of finite simple groups
- cf. __Classification of finite simple groups__

__Independence of the continuum hypothesis__ (Godel 1940, Cohen 1963)\
_"The continuum hypothesis can neither be proven nor disproven from the axioms of Zermelo-Fraenkel set theory (assuming these are consistent)."_
- Godel showed that CH holds in the constructible universe, a model of the ZF axioms, so it is impossible to disprove CH from ZF
- Cohen introduced the method of forcing, used to construct models of axioms with specific properties
- Forcing remains a fundamental technique in set theory and logic

__Atiyah-Singer index theorem__ (1963)\
_"For an elliptic differential operator on a compact manifold, the difference between the dimensions of the kernel and cokernel is a topological invariant."_
- ie. _"The analytical index is equal to the topological index"_
- Subsumes many major theorems, eg. Chern-Gauss-Bonnet (1944), Hirzebruch-Riemann-Roch (1954), Hirzebruch signature theorem (1954), ...
- Cross-fertilisation with physics, eg. string theory (Witten), instantons and 4-manifolds (Donaldson)

__KAM theorem__ (Kolmogorov 1954, Moser 1962, Arnold 1963)\
_"Small perturbations of an integrable Hamiltonian system preserve most invariant tori."_
- An almost-periodic orbit can be destroyed by small perturbations, if they are in resonance
- If the frequencies are 'sufficiently irrational,' the orbit remains quasi-periodic
- Applications to stability of n-body problem (eg. the solar system) and the onset of chaos in dynamical systems

__Hironaka's resolution of singularities__ (1964)\
_"Every algebraic variety over a field of characteristic 0 admits a proper birational map from a non-singular variety."_
- ie. The solutions of a system of polynomial equations can be parametrised by a smooth manifold
- Introduced new techniques in algebraic geometry and commutative algebra

__Mostow rigidity theorem__ (Mostow 1968, Prasad 1971)\
_"Complete finite-volume hyperbolic manifolds of dimension at least 3 are completely determined up to isometry by their fundamental group."_
- For high-dimensional hyperbolic manifolds, topology determines geometry
- Contrast with 2-dimensional case: the hyperbolic surfaces with genus g > 1 form a (6g-6)-parameter family
- Applications to hyperbolic geometry and low-dimensional topology

__Cook-Levin theorem__ (1971)\
_"The Boolean satisfiability problem (SAT) is NP-complete."_
- P: decision problems that can be solved in polynomial time by a Turing machine
- NP: decision problems with proofs verifiable in polynomial time by a Turing machine
- NP-complete: in NP, and every NP problem can be reduced to it in polynomial time by a Turing machine
- Corollary: _"If SAT can be solved in polynomial time, so can every problem in NP, ie. P = NP."_
- Karp (1972) lists 21 NP-complete problems
- P ?= NP remains one of the most important open problems in theoretical computer science

__Weil conjectures__ (Dwork 1960, Grothendieck 1965, Deligne 1974)\
_"The local zeta function of a variety over a finite field is rational, has a functional equation, satisfies the Riemann hypothesis, and is related to the complex Betti numbers."_
- Surprising connection to algebraic topology: Weil noted that the conjectures follow from constructing a 'cohomology theory,' with appropriate analogues for the Lefschetz fixed point theorem and Poincare duality
- Grothendieck developed the theory of etale cohomology (Grothendieck-Artin 1960) to prove 3 of the 4  conjectures, and envisioned an approach with his 'standard conjectures'
- Deligne used an analytic estimate to prove the Riemann hypothesis analogue, much to the disappointment of Grothendieck

__Szemeredi's theorem__ (1975)\
_"Any subset of the positive integers with positive upper density contains arbitrarily long arithmetic progressions."_
- First proven with intricate combinatorial arguments
- Later proofs link to diverse areas such as ergodic theory (Furstenberg 1977) and Fourier analysis (Gowers 2001)

__Four colour theorem__ (Appel-Haken 1976)\
_"The vertices of any planar graph can be coloured with at most 4 colours such that no two adjacent vertices are the same colour."_
- First major theorem proven with computer assistance (What is proof? Baby don't hurt me)

? __Takens's theorem__ (1981)\
_"If x is a generic observable function of a dynamical system, then for k large enough, (x(t),x(t+1),...,x(t+k-1)) is an embedding of the attractor into R<sup>k</sup>."_
- ie. _"The attractor of a generic dynamical system can be reconstructed from the time-delay plot of a single observable."_
- Applications to time-series analysis, eg. computing the fractal dimension of attractors

__Classification of finite simple groups__ (various, 1983)\
_"Every finite simple group is either a cyclic group, an alternating group, a group of Lie type, or one of 26 sporadic groups."_
- aka. 'The Enormous Theorem,' or 'The Thirty Years' War' (Gorenstein)
- Finite simple groups are the 'building blocks' of all finite groups (Jordan-Holder theorem)
- Gorenstein announced (prematurely) the completion of the proof in 1983; the quasithin case was only resolved in 2004
- Longest proof of a single theorem: 10,000+ pages, 500+ papers, 100+ authors
- cf. __Feit-Thompson theorem__

__Jones polynomial__ (1984)\
_"The Jones polynomial of a knot is a knot invariant."_
- Derived from operator algebras
- First knot invariant which detects that the trefoil knot is chiral, ie. it is not isotopic to its mirror image
- Can be computed recursively from simple skein relations; similar relations were found by Conway (1969) for the Alexander polynomial
- Led to the discovery of the HOMFLY-PT polynomial (1985)

__Gromov non-squeezing theorem__ (1985)\
_"There is no symplectomorphism in R<sup>2</sup>n mapping a ball to a cylinder of smaller radius."_
- aka. 'it is impossible to squeeze a symplectic camel into the eye of a needle'
- An example of a symplectomorphism: time evolution in phase space
- Corollary: _"if the initial states of a physical system in phase space are spread out over the unit ball in R<sup>2</sup>n, then these cannot be squeezed into a state where the coordinates of the first particle (q<sub>1</sub>,p<sub>1</sub>) spreads out less than initially."_
- First restriction on symplectomorphisms (other than being volume-preserving)
- Introduced concept of pseudoholomorphic curves, which led to symplectic invariants such as Floer homology (1988)

__Fermat's last theorem__ (Wiles 1993, Taylor-Wiles 1994)\
_"For n at least 3, no two positive n<sup>th</sup> powers sum to an n<sup>th</sup> power."_
- First stated by Fermat in an infamous note in Diophantus's Arithmetica: 'I have discovered a truly remarkable proof which this margin is too small to contain'
- A major impetus for algebraic number theory in the 19<sup>th</sup> and 20<sup>th</sup> century, cf. __Unique factorisation of ideals__
- Proved an important case of the modularity theorem (Breuil-Conrad-Diamond-Taylor 2001), relating elliptic curves to modular forms; part of the Langlands programme

------

## In progress

? Chinese remainder theorem\
? Basel problem (Euler 1734)\
_"The sum of reciprocals of squares 1+1/4+1/9+... is equal to π<sup>2</sup>/6."_
	- Euler also evaluated the sums of reciprocals of even powers up to 26
	- Justification of Euler's original argument had to wait a century
? Fermat's two-squares theorem (Euler 1749)\
_"An odd prime is the sum of two squares if and only if it is congruent to 1 mod 4."_
	- Stated by Girard in 1625 and Fermat in 1640, without proof
Least squares regression (Gauss 1795/Legendre 1805)
? Cauchy-Schwarz inequality\
? Intermediate value theorem (Bolzano 1817/Cauchy 1821)\
_"A continuous real-valued function f on [a,b] attains all values between f(a) and f(b)."_
? Elliptic integrals\
? Principle of inclusion-exclusion\
? Pigeonhole principle (Dirichlet 1834)\
_"If there are more pigeons than holes, then some hole has more than one pigeon."_
	- Or, _"If there are more holes than pigeons, then some pigeon has more than one hole in it."_
? Matrix-tree theorem (Borchardt 1860)\
_"The number of spanning trees in a graph is equal to any cofactor of its Laplacian matrix."_
? Lindermann-Weierstrass theorem (Lindermann 1882, Weierstrass 1885)\
? Cayley-Hamilton theorem (Frobenius 1878)\
? Fredholm alternative (1903)\
? Classification of finitely generated modules over a PID\
? Perron-Frobenius theorem (Perron 1907/Frobenius 1912)\
? Brouwer's fixed point theorem\
? Banach fixed point theorem\
? Banach-Tarski paradox (1924)\
? Spectral theorem for self-adjoint operators (Stone/von Neumann 1929-32?)\
? Radon-Nikodym theorem (Radon 1913, Nikodym 1930)\
? Birkhoff's ergodic theorem (1931)\
? Whitney embedding theorem (1930s?)\
? Sard's theorem (Morse 1939, Sard 1942)\
_"The set of critical values of a smooth function between manifolds has Lebesgue measure zero."_
? Nakayama lemma (Krull 1951, Azumaya 1951/Nakayama 1951)\
? Selberg trace formula (1956)\
? Exotic spheres (Milnor 1956)\
_"There is a smooth manifold which is homeomorphic to, but not diffeomorphic to, the standard 7-sphere."_
	- Open problem: (smooth Poincare conjecture) Is there an exotic 4-sphere?
? Lax-Milgram theorem\
? Hartman-Grobman theorem\
? Hoeffding's inequality (1963)\
? Max-flow min-cut theorem\
? Baker's theorem (1966)\
? Carleson's theorem (1966)\
? CHSH inequality (1969)\
? Hilbert's tenth problem (Matiyasevich 1970)\
_"Every computably enumerable set is Diophantine."_
? No-cloning theorem (Park 1970/Wootters-Zurek 1982/Dieks 1982)\
_"You cannot make a copy an arbitrary unknown quantum state."_
? Lovasz local lemma\

------

## Bonus: 21st C

? PRIMES is in P (Agrawal-Kayal-Saxena 2002)\
Poincare conjecture/Thurston geometrisation conjecture (Perelman 2003)\
? Robertson-Seymour graph minor theorem (2004)\
? Virtually Haken conjecture (Agol 2012)\
? Bounded prime gaps (Zhang 2013)