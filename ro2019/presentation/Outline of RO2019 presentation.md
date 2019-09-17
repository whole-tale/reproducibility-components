## Outline of RO2019 presentation

### Quiz - Most effective way to make your science reproducible?
- Keep very good records of your work.
- Only use open source software, and make any new or modified code freely available.
- Employ the latest interoperability standards for scientific data, metadata, software, and Research Objects.
- Do all of your work in software containers.
- Focus your research on  intrinsically reproducible phenomena.

### Reproducibility in the natural sciences
* Assumption of repeatability of observations, procedures, experiments, results by original researcher.
* Degrees of reproducibility?
* Hierarchy of natural laws, hierarchy of reproducibility?
* Logic -> Math -> Physics -> Chemistry -> Biology -> ... 
* Actual limits on repeatability not so simple.
* Rare events, past events, costly experiments, unique instruments...
* Transparency is critical--always possible, always required.

### Natural sciences are not about exactly repeatability
- The universe is not a digital computer--it's more of an entropy generator.
- A good experiment is one that holds part of the universe as still as possible so that a natural phenomenon can be observed clearly--good experiments are very hard to design.
- Even under ideal conditions uncertainty is intrinsic to measurement.
- Exactly repeating experimental procedures is impossible.
- Natural history is characterized by contingency.
- Steven J. Gould:  rerunning evolution would yield different results.
	
### Replicates in experimental biology
- In experimental sciences it is essential to assess how repeatable an experiment is. 
- Next Generation Sequencing
- Biology -> sample prep -> instrument -> data reduction -> data analysis
- Claims about reproducibility span experiment and computation.
- Implications for terminology.
- Technical replicates
- Biological replicates
- In this sense, replication of experiments and results is intrinsic to modern biology.
- Question: Why are these called replicates rather than reproductions?

### Replication and reproduction 
- Scientists (especially biologists) have been using the words on a daily basis for a long time.
- For biologists replication and reproduction are processes that occur in nature--they are matters for study.
- Life is a very special phenomenon in its achievement of near-exact copy of information.
- Replication of DNA (in the replisome where error correction is performed) is fundamentally high-fidelity.
- Replication, error rates, error catastrophes, and the origin of life. 
- Dawkins' Replicators (see Stanford Encylcopedia of Philosophy: Replication and Reproduction).
- Reproduction of organisms is lower fidelity, variation is expected and valuable.
- Why does this matter?  Relationship to FASEB definitions of reproducibility and replicability.

### Digital computing enables exact repeatability.
- Digital computers use logic gates to achieve replication of information at such a low error rate it can be referred to as *exact*.
- Computers pull the exactness of logic and discrete mathematics up to the level of macroscale phenomena--quite a feat.
- Exact repeatability is achievable in practice for:
	- computer hardware
	- mathematical calculations performed by hardware
	- sequences of bits representing a program executed by hardware,
	- sequences of operations performed by a (simple) CPU
	- bits representing computing environments

### Chaos is a ladder.  Is reproducibility a staircase?
- Littlefinger might say that folks who give talks about reproducibility are using the terminological crisis as a ladder.
- Staircase model of reproducibility
- Vector space model of reproducibility.
- Transparency and exact repeatability appear to be orthogonal.
- What are the dimensions of scientific reproducibility?
- Reproducibility, replicability, exact-repeatability, reviewability, reusability--but maybe also correctness, robustness? 

### Transparency and exact repeatability are orthogonal
- Possible to achieve either without the other.
- We know that exact repeatability is out of question for many aspects of the natural sciences.
- For even purely computational research a particular component of a study can contribute only to transparency or only to repeatability.
- A call to web service that operates as a black box is repeatable (but for how long?) but not transparent.
- Source code for a program that runs on esoteric hardware, or requires weeks of time on a supercomputer might be considered transparent but not exactly-repeatable.
- Fortunately, Transparency is far more important to reproducibility in science.

### Resolving the R* terminology conundrum
- Modeling reproducibility as a multidimensional space may offer a way out of the terminology quagmire.
- Recognize that different terminologies are *not* all talking about the same set of dimensions; different communities focus on different subspaces.
- If we can find the independent dimensions of reproducibility space, we can map different definitions onto those dimension and thereby convert claims made using one terminology to claims using a different terminology.
- Each community need focus only on the dimensions of interest to them.
- Research Objects can play a key role in keeping claims about reproducibility with research, and disambiguating these claims.

### Reproducible vs Replicable
- The only consensus on the meaning of these terms is that the confusion is harmful.
-  FASEB definitions of reproducibility, replicability, transparency.
- NAS definitions reverse relative fidelity of reproducibility and replicability
- NAS requires code from reproducibility and transparency
- NAS explicitly equates reproducibility and computational reproducibility
- NAS definitions leave non-computational research with only one word: replicability, analogous to FASEB's reproducibility--no way of expressing FASEB's notion of replicability, experimental replicates, etc.

### What about using namespaces?
- This admittedly sounds naive, and many (e.g. Reviewer 2) would argue unnecessary.
- However, the NAS report makes it clear that different communities of have different needs for the meanings of the words reproducibility, replicability, etc.
- Not surprising if there are more dimensions to reproducibility space than there are nice words to assign to them. 
- Namespaces would let different communities define the words appropriately for their domains without (as much) confusion.

### Mappings between terminologies
- But namespaces would need to be complemented with unambiguous mappings between terminologies.
- And these mappings would not be simple--even when describing the same subspaces of reproducibility different communities may have chosen different axes, so to speak, not just assigned different names to the same axes.
- We would have to identify the fundamental axes of this space and map each community's definitions to them so that claims (or queries) phrased in terms of one set terms can be transformed to use another set of terms.

### Reproducibility badges and verification workflows 
- It turns out we need namespaces even within domains.
- ACM SIGMOD defines a defines a procedure for assessing database research reproducibility.
- The ACM parent organization awards four different reproducibility badges distinct from the SIGMOD reproducibility assesment.
- ACM has defined 8 versions of the guidelines for awarding its four badges since 2015.
- The workflow used by the American Journal of Political Science (AJPS) to verifying computational artifacts also is versioned.
- The meaning of reproducibility badges changing from year to year even within a single organization, with no end in sight.
- If we want these badges to have any meaning at all they have to be mapped to something that isn't changing constantly.
- Users of these badges and the studies they are awarded to must be able to choose which definition of reproducibility, badges, and verification workflows studies are viewed through--not forced to assess each study by the particular definitions that applied to it at the time it was assessed.

### Limits on computational reproducibility
- Already mentioned the need for definitions that span computational and non-computational components of studies.
- Even within purely computational elements of studies, the dimensions of reproducibility remain to be explored.
- This is another subspace in which change is rapid.
- Current approaches for preserving computing environments may not work for long.
- A Dockerfile that builds correctly today might not do so a year from now--if it builds at all.
- Transitive dependencies on 3rd-party shared libraries lead to particularly fragile software builds--even if you pin the versions of your dependencies, their dependencies might not.
- So what do we really mean when we say have made our computing environments, our software, or our computational productions "reproducible"?

### Describing computational reproducibility

### Science-oriented provenance queries

### Research Objects to the rescue 


