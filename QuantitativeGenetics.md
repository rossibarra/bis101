#Quantitative traits

####qualitative traits

- red or green, wrinkled vs. round, etc. 
- discrete states
- usually simple genetic basis -- one or two genes

####quantitative traits

- height, IQ, etc. not discrete 
- usually complex genetic basis -- many genes or QTL
- each QTL is a normal Mendelian locus, but their effects combine to form phenotype
- Simple example w/ two loci. each big allele adds 1 to phenotype

A cross AABB with aabb and look at F2 (draw out A's and B's). Showing possible genos/phenos, 

A locus | B locus | Phenotype
---|---|---
1	1	|1	1	| 41	1	|1	0|	31	1	|0	0|	21	0	|1	1|	3
1	0	|1	0|	21	0	|0	0|	1
0	0	|1	1|	20	0	|1	0|	10	0	|0	0|	0
 
but there will be 2 of each het (1:2:1 Mendel), so distribution of phenos will be:

and it looks like (draw): ![Alt text](/Users/jri/src/bis101/phenos1.pdf)

As you get more and more loci, becomes normal. 

This is for a cross where at each het we have 1:2:1 segregation in F2, but in a population what determines the distribution? (allele freqs)

Popgen!  So distribution would be freq. of genotype * value, e.g.

@ locus A p_A=0.2 and at locus B p_B 0.3

![Alt text](/Users/jri/src/bis101/phenos2.pdf)

Most phenotypes of interest are quantitative.

- Even color (how much of the pigment)
- Disease: Diabetes not all the same

Statistically, you assume a quant. trait is controlled by an infinite number of genes

- obv. not infinite, but in many cases (human height) it's probably hundreds or thousands
- not all have to have same effect as above. e.g fw2.2 tomato size

####Phenotypic variation 
 
The equation: V_P = V_G + V_E (what is variance?)

- ![Variance](./images/var.png)
- explain genetic variance, what is environmental variance
- V_P we can measure: Sum(x-xbar)^2/n
What does V_E mean? 

Redraw histogram w/ variation around values due to environment. 

- e.g. take identical twin mice and I give one lots of food, and the other none. V_E will determine all of phenotypic difference!

####Heritability
           
H^2=V_G/V_P = broad sense heritability 

heritability is the % of phenotypic variation due to variation in genes

- NOT whether or not a trait varies
- NOT whether or not it's genetic
	- e.g. fitness in natural populations
	- in humans reproduction: lots of choice/culture/economy going into how many kids	
	- doesn't mean ability to reproduce has no genes, just that much of the variance is V_E
	- keep the genes the same, but increase environmental variance, heritability goes down
- NOT explain between group differences
	- because environments may differ & depends on environ
	- if we take mouse weight, heritability in mouse weight will differ in an environment where mice are starved and in an environment where there is lots of food (perhaps)
- NOT % due to genes
	- 80% narrow sense heritability for height NOT mean 20% of your height is environmental
	- means 20% of the total variation seen among population is due to environment
- even when high, doesn't mean all change due to genes
	- Dutch height has increased maybe 16cm over last 150 years
	- not very long for nat. selection to work (~7 generations)
	- probably mostly due to improved health care, food, etc.
- V_G may change as allele frequencies change (popgen)

####How to estimate

One way to estimate broad sense, in humans, is looking at twins separated. 

Genes identical, environment diff. Similarity must be due to genes.

Covariance in phenotype: (Sum(X-Xbar)(Y-Ybar))/n  <- first and second twin

From twin studies:

Trait | H^2
--- | ---
Height | 0.88
Waist circumference | 0.25
IQ | 0.69
alcoholism | 0.5
autism | 0.9
religiosity | 0.4

#### Additive genetic variance

V_G = V_A + V_D +V_I  
- V_A additive -- stuff we most care about b/c responds easily to selection and easy to model and work with, dominance, interaction b/t genes)

h^2=V_A/V_P = narrow sense heritability -> can calculate from phenotypic means of progeny

narrow sense is what geneticists care about, what responds to selection, etc.

Can estimate by covariance between parents and offspring

- same environment, offspring inherit 1/2 genes from parent
- so COV(p-o)=1/2 V_A

####Breeder's equation
R=h^2*S

![Alt text](/Users/jri/src/bis101/response_selection.jpg)

If you know heritability (from some other estimate) you can predict response to selection on quant. trait

Different from response to selection on a single locus (what we talked about in popgen)

But also if I select on a trait, can use response to estimate narrow sense heritability.

What does low h^2 mean?  means that won't respond to selection well b/c most of phenotype is not due to additive genetic effects
            
####Mapping QTL

looking for statistical association between a genetic marker and a phenotype

Draw cross between fluffy rabbit and hairless rabbit

- draw 1 pair of chromosomes w/ markers
- phenotype varying among offspring
- harder than finemapping case where we had yes/no
- statistical association that everytime you see marker X, ~10% fluffier

Can you cross 2 parents w/ same phenotype and get variation?

- yes, think two people exactly 5'7"
- Example w/ our two allele system

Parents can harbor alleles that don't make initial sense

- AABBcc x aabbCc (4 x 1 phenotype)
- new allele in low parent that not present in high parent!

We can't do this in humans obviously.

Association mapping you genotype a large number of unrelated individuals and look for the correlation there 



