# Variant report 2022-08-17

## S:R346T confers significant growth advantage to BA.4/5, projected to become dominant in October

BA.4 and BA.5 lineages that have the S:R346T substitution continue to grow faster than their siblings without the substitution. (S:R346K was the defining mutation of BA.1.1 that became dominant in a large number of countries before BA.2 took over)

The substitution S:R346T and related ones to I, S and K have appeared numerous times independently in BA.4 and BA.5. These are the ones designated by Pango thus far:

- BA.4.6 (T)
- BA.4.1.8 (T)
- BA.4.7 (S)
- BF.7 (T, alias for BA.5.2.1.7)
- BF.11 (T, alias for BA.5.2.1.11)
- BF.13 (S, alias for BA.5.2.1.13)
- BE.1.2 (T, alias for BA.5.3.1.2)
- BA.5.9 (I)

While BA.4.6 is the single most common BA.4/5 lineage with S:346, it has a growth disadvantage compared to BA.5 lineages with the same mutation, due to the fact that BA.4 has a general growth disadvantage against BA.5. This is immediately evident considering that BA.4\* started out slightly more common than BA.5\* in April 2022 it is now more than 10 times less common.

Globally, BA.5 with S:R346T is expected to become more common than BA.4 with S:R346T in sequences from this month - although there are naturally regional variations. For example, in Belgium BA.5 with S:R346T is already much more common than BA.4 with S:R346T while in the US the BA.4 lineages are still more frequent.

![Comparison of BA.4 and BA.5 with S:346T](../images/4c15fb1b1b4fed15805df44719b8887f9dec50e695efeaf9af61e178592ce3f6.png)
*Figure 1: BA.5 with S:R346T is overtaking BA.4 with S:R346T on a global level, source [covSpectrum](https://cov-spectrum.org/explore/World/AllSamples/Past6M/variants?variantQuery=nextcladePangoLineage%3ABA.4*+%26+S%3A346T&variantQuery1=nextcladePangoLineage%3ABA.5*+%26+S%3A346T&analysisMode=CompareEquals&)*

If evolution was frozen with only existing lineages, BA.5 + S:346T would be expected to become the dominant variant approximately in October 2022. BA.5 + S:346T made up around 1% in European countries at the end of July.

Of course, other fitter lineages, be it sublineages of BA.4/5, of BA.2 (e.g. BA.2.75) or other variants may evolve at any time so these projections need to be read with appropriate caution.

## BA.2.75 now dominant in India, has acquired extra spike mutations in some lineages

### Global spread of BA.2.75

BA.2.75 has continued growing in share in India and has been dominant since the end of July, despite the presence of BA.5.

Other countries where BA.2.75 has established itself at levels >1% at the beginning of August are:
- Nepal (>50%)
- Singapore (~10%)
- Australia (~2%)
- Japan (~1%)

![BA.2.75 in Asia/Oceania](../images/408d6c8c64aff85e5e0f7fc8435cc538161837fb6a6f276e84b792b6f2ec21e8.png)  

While BA.2.75 is most common in Asia and Oceania, its share is increasing in all countries that have submitted large amounts of recent sequences. However, the share of BA.2.75 in Europe and North America is too small (~0.1-1%) to be able to confidently compare growth advantages of BA.2.75 and the fittest BA.5 lineages.

![BA.2.75 in Rest of World](../images/34b6ed1f3040198a0e95d3aadc3b21447d907b1fbf88fe6af1c734b5c876ce30.png)  

### Extra spike mutations in BA.2.75

With more than 3000 sequences of BA.2.75 available, it is now possible to analyse intra-lineage diversity. Due to challenging sequence quality, only 1 sublineage has been designated so far (BA.2.75.1 with S:D574V).

BA.2.75 with S:D574V, designated as BA.2.75.1, is apparently increasing in share making up ~40% of recently uploaded BA.2.75\*. Based on relatively noisy data, BA.2.75.1 seems to have a growth advantage of ~4-6% - corresponding to a doubling in share every 2-3 weeks. This lineage is not localized in any particular country and has been detected in most places that have sequenced BA.2.75. S:574 substitutions have only rarely been observed in the pandemic thus far - usually as S:D574Y in a handful of Delta sublineages in countries like Portugal, France and Denmark. In more than 12 million sequences, S:D574V has occurred less than 200 times outside of BA.2.75.

Maybe unsurprisingly, BA.2.75\* has already independently acquired S:346T twice, once in BA.2.75, once in BA.2.75.1. With less than 100 BA.2.75 + S:346T sequenced to date, it is too early to estimate the growth advantage (or disadvantage) this mutation might confer - but it is not unlikely to be of similar magnitude as in BA.4/5*. S:346T is present in around 3% of all BA.2.75\*.

Other notable spike mutations detected internationally and at least ~15 times (i.e. in >0.5% of BA.2.75\*) are:

- S:K356T (~1%)
- S:L452R (~0.5%, known from Delta)
- S:F486S (~1%, similar to S:F486V known from BA.4/5)

Even if no other novel variant evolves, the large number of sublineages that have arisen and will arise in BA.5 and BA.2.75 make it difficult to predict with confidence whether a BA.5 or BA.2.75 lineage becomes dominant in Autumn/Winter in Europe. Both outcomes seem possible though BA.5 has a considerable head start - being the currently dominant variant in Europe.

## Developments outside of BA.4/5 and BA.2.75

Some of the novel lineages that have been discussed in the previous report have recently been designated:
- BA.2.10.4: BA.2.10 + W64R, 141-144del, 243-244del, G446S, F486P, R493Q, S494P, P1143L ([Pango issue #898](https://github.com/cov-lineages/pango-designation/issues/898))
- BA.2.38.2: BA.2.38 (=S:417T) + 157S, 444N ([Pango issue #828](https://github.com/cov-lineages/pango-designation/issues/828))
- BA.2.38.3: BA.2.38 (=S:417T) + 69/70del, 71F, 452Q, 446S, 478R, 1264L ([Pango issue #840](https://github.com/cov-lineages/pango-designation/issues/840))

In addition, the following recently designated lineage is of interest due to its large number of Spike mutations:
- BJ.1: BA.2.10.1 + S:V83A, H146Q, Q183E, V213E, G339H, R346T, L368I, V445P, G446S, V483A, F490V, G798D, S1003I ([Pango issue #915](https://github.com/cov-lineages/pango-designation/issues/915))

None of these seem to show rapid growth but it is too early to exclude the possibility that they may be or become competitive with BA.4/5 and BA.2.75.

# Variant report 2022-08-03

## BA.2.75 outcompetes BA.5 in India

BA.5 continues to dominate in all countries with recent sequences apart from India/Nepal where BA.2.75 is becoming dominant.

As of 2022-08-03, there are around 1400 sequences of BA.2.75 on GISAID, almost 3 times as many as 14 days ago.

In India BA.2.75 has a large growth advantage over its ancestor BA.2 (16-17%/day) and a modest growth advantage over BA.5 (4-6%) as shown by [Tom Wenseleers](https://twitter.com/TWenseleers) using a hierarchical regression model that has performed well with past variants. For countries outside of India sequence numbers are still too small to distinguish conclusively between growth due to important and intrinsic growth advantage.

![Growth advantage of BA.2.75](images/growth-advantage-ba2-75.png)

To put this into context, for BA.2.75 to grow from 0.1% to 50% in a background of BA.2 it would take around a month (this is approximately what is happening in India). In a background of BA.5, assuming growth advantages globally are the same as in India, it would take BA.2.75 about 3 months to grow from 0.1% of all sequences to 50%.

So while BA.2.75 seems to start driving a wave as visible in positivity rate attributed to variants, any potential BA.2.75 wave in e.g. Europe is still 2-3 months away and would be much less drastic than the wave caused by BA.1 vs Delta (~20% daily growth advantage), BA.2 vs BA.1 (~10% daily growth advantage) and BA.4/5 vs BA.2 (~10% daily growth advantage). Of course, it is possible that the BA.2.75 growth advantage vs BA.5 is India-specific and/or that another variant will evolve (either from BA.2, from BA.5, even BA.1 or non-Omicron) so that there will never be a BA.2.75 wavelet.

![BA.2.75 positivity wave in India](images/positivityba275.png)

[Cov-Spectrum link with BA.2.75 in India](https://cov-spectrum.org/explore/India/AllSamples/Past3M/variants?variantQuery=NextcladePangoLineage%3ABA.2.75)

[Link to Twitter thread with figures](https://twitter.com/TWenseleers/status/1554189987586908161)

## Intra-Omicron recombinants keep appearing but so far with limited growth advantages

Recombinants containing BA.4/5-Spike have been identified recently but until now, no identifiable recombinants have become dominant at least regionally. It is possible that the various BA.1/2/3/4/5 involve recombination events but in these cases the parents are not clearly identifiable, separate lineages.

## BA.5 has small but definite growth advantage over BA.4

Despite BA.5 and BA.4 being very closely related, BA.5 has become dominant over the past few months. When BA.4 and BA.5 were first discovered, BA.4 was about 3 times more common than BA.5. This has now inverted, with BA.5 being 2-10x more common than BA.4, depending on the region. This translates to a daily growth advantage of about 1-3%.

## BA.4/5 sublineages with small to moderate growth advantages are appearing

A number of BA.4/5 sublineages that seem to show growth advantages compared to their parents have been identified.

BA.4.6 has an additional S:R346T (S:R346K was what conferred BA.1.1 a moderate growth advantage over BA.1) and seems to grow about 5%/day faster than BA.4. BA.4.6 is most common in North America (~3000 sequences as of 2022-08-03), making up around 20% of BA.4 in the US mid July, up from 1% mid May. Prevalence is around 1% in Europe in mid July.

Importantly, the growth advantage that BA.4.6 has over BA.4 (~5%/day) outweighs the growth disadvantage that BA.4 has against BA.5 (~1-3%/day), making BA.4.6 fitter than basic BA.5. BA.4.1.8, an independent BA.4 sublineage also has S:R346T and the concomitant growth advantage but has not been sequenced as often. It is most common in South Africa.

There are a number of BA.5 sublineages that have independently acquired mutations at S:346, e.g. BF.7 (=BA.5.2.1.7, S:346T) with ~600 sequences mostly from Belgium, BA.5.9 (S:346I) with ~600 sequences mostly from Germany.

Generally, BA.5.2.1 (aliased to BF for sublineages) seems to have a slight growth advantage over other BA.5 branches - despite not having any additional Spike mutations.

There are BA.4/5 sublineages with other Spike mutations, sometimes multiple Spike mutations, but the pattern is so far not as clear as for S:346 and all these lineages have not yet surpassed 1% even in the countries where they are most common.

## BA.2 with multiple spike mutations keep emerging

BA.2 sublineages with multiple Spike mutations keep emerging, mostly from India, but none of these seem to be able to compete with BA.5 and BA.2.75. In some cases the clusters are too small to be able to reliable say anything about the growth advantage.

To give some idea of the Spike profiles, here are a few interesting lineages:
- BA.2.10 + W64R, 141-144del, 243-244del, G446S, F486P, R493Q, S494P, P1143L [Pango issue #898](https://github.com/cov-lineages/pango-designation/issues/898)
- BA.2.38 (=S:417T)+ 69/70del, 71F, 452Q, 446S, 478R, 1264L [Pango issue #840](https://github.com/cov-lineages/pango-designation/issues/840)
- BA.2.38 (=S:417T)+ 157S, 444N [Pango issue #828](https://github.com/cov-lineages/pango-designation/issues/828)


# Variant report 2022-07-20

## Dominant variants

BA.5 is dominating waves on all continents, together with BA.4 which is slightly less fit than BA.5 but with identical Spike so very similar.

BA.2.12.1 still makes up a good share in North America but getting replaced by BA.4/5. It's also present with smaller share around the world where BA.4/5 also replaces it.

BA.2\* that is not BA.2.12.1 made up 1-10% around the world at the end of June, with the notable exception of India where BA.2\* makes still up ~90% (and countries without much sequencing for which these statements are not possible to be made).

BA.1 only appears occasionally, in sequences that often show signs of persistent/chronic infection.

## Variants to watch out for

India has never had significant BA.1 circulation. Many fit BA.2* lineages are present there.

### BA.2.75 (S:K147E,S:W152R,S:F157L,S:I210V,S:G257S,S:G339H,S:N460K,S:G446S)

BA.2.75 seems able to compete with BA.5 in India. It was introduced or emerged later than BA.5 (first sequence end of May) and its frequency seems to range between 10-50% depending on state at beginning of July.

BA.2.75 has 9 Spike amino acid substitutions relative to BA.2 (including reversion to wild type at 493) compared to the 3 substitutions (including reversion 493) plus one 2 AA deletion (S:69/70del) for BA.4/5, making BA.2.75 the most diverged Omicron variant with significant circulation to appear since BA.1/BA.2/BA.3.

BA.2.75 does appear to circulate globally, albeit at such low share that it is not possible to say much about growth advantage outside of India.
Countries with clusters of BA.2.75 include: UK, US, New Zealand, Japan, Indonesia, Germany, Israel.
Countries that are known to have exported cases are: Nepal/India (for many Japanese airport surveillance cases), France (for some Israeli cases)

<https://cov-spectrum.org/explore/World/AllSamples/Past3M/variants?variantQuery=NextcladePangoLineage%3ABA.2.75>

India has many states with different sampling practices so one needs to be cautious when interpreting aggregate growth advantages.

Nonetheless, the apparent growth advantage of BA.2.75 over BA.5\* at whole country aggregate level in India is compatible with a significant growth advantage. It is important to note that the statistical uncertainty does not account for systematic errors like biased sampling. The real uncertainty is much bigger than the range 81-138%.

![picture 5](images/a0891368449cb6070ab832591937ace96d6b3ef704f7a3fa17e902a1c33ea035.png)

An up to date version of this graph can be found [here](https://cov-spectrum.org/explore/India/AllSamples/Past3M/variants?variantQuery=NextcladePangoLineage%3ABA.5*&variantQuery1=NextcladePangoLineage%3ABA.2.75&analysisMode=CompareToBaseline&)

### Selection of other interesting lineages

Many interesting BA.2 sublineages have appeared first in India. Here is a selection of some to watch. The mutations they carry are typical of BA.2 sublineages with (potential) growth advantages, in India and also globally.

#### BA.2.76 (S:R346T, S:Y248N)

<https://github.com/cov-lineages/pango-designation/issues/787>

<https://cov-spectrum.org/explore/World/AllSamples/Past3M/variants?pangoLineage=BA.2.76>

#### BA.2.38.1 (S:N417T, S:S247N, S:Y248S, S:K444N)

<https://github.com/cov-lineages/pango-designation/issues/809>

<https://cov-spectrum.org/explore/World/AllSamples/Past3M/variants?pangoLineage=BA.2.38.1>

#### BA.4.6 (S:346T)

<https://cov-spectrum.org/explore/World/AllSamples/Past6M/variants?aaMutations=S%3AR346T%2CN%3A151S%2CORF7b%3AL11F&nucMutations=12160A%2CC8140T>

## Latest developments

### South African pair of complex recombinant clusters

Two related clusters of complex Delta/BA.2 recombinants (C1 with 5 sequences and C2 with 4 sequences) have appeared in Gauteng/Limpopo (bordering region).
The Spikes are mostly identical, the rest of the genomes have multiple different breakpoints.

The Pango designation issue, with discussion about this lineage:
<https://github.com/cov-lineages/pango-designation/issues/844>

**Figure showing the recombination patterns for C1 and C2 across the genome**
![SA recombinant chart](images/601c1cdf553df68314def793e5e51ed2a4100c4499ee49663052f7b2b02c53c1.png)
(Tom Peacock, private communication)

**Figure showing how mutations in C1 compare to other variants**
![SA recombinant 1](images/715e20b73add43730e6ce86521a6891010c8897960d2ce3a99a1aa301c301dd9.png)

**Same figure but with different annotations**
![SA recombinant 2](images/2527559ee3e9c91f092f7e42447cf27a5f1a336ae7b84cf8287f0ff62253f76c.png)
(from <https://www.nicd.ac.za/wp-content/uploads/2022/07/Update-of-SA-sequencing-data-from-GISAID-15-July-2022.pdf>)

### German BA.2/BA.1/BA.2 recombinant with convergence to BA.2.75

A BA.2/BA.1/BA.2 recombinant with many mutations of interest has appeared in Germany with 27 sequences to date and spread across Europe.

First sequence beginning of June.

Spike shows the following changes compared to BA.2:

- Missing: T19I, 24-26del, 27S not there because that part is from BA.1* parent
- Donated: 69-70del convergent with many VOCs
- Additional S:R346K, convergent with BA.1.1
- Additional S:K147E, S:N460K and reverted S:493 convergent with BA.2.75

<https://github.com/cov-lineages/pango-designation/issues/823>

## Trends

There seem to be two ways in which lineages evolve:

1. Stepwise accumulation of mutations with short branches
2. "Saltation" events, where clusters attach only on long branches.

In the past, all VOCs have appeared as saltation events.
Stepwise evolution does take place and is relevant for slow sweeps.
However all fast sweeps have been caused by saltation variants.
This is maybe not surprising as any variant comes out of nowhere and long branches are a result of fast growth.
It is thus not clear which way causality goes.
Shay Fleishon and his team in Israel are analyzing the daily updated Usher tree for new long branches allowing quick detection of potentially fast growing lineages.

Many saltations seem to derive from chronic infections as opposed to fast growing lineages so the ratio of false positives is high.

## Non-exhaustive list of BA.2 mutations to watch

This is a non-exhaustive list of mutations that are appearing repeatedly in lineages with growth advantage on top of BA.2\*:

- S:64R
- S:76
- S:152
- S:153
- S:157
- S:248N/S
- S:346T/S/I
- S:354K
- S:368I
- S:417T
- S:444N/T
- S:446S
- S:449D/S/N
- S:450D
- S:452Q/M
- S:460K
- S:468
- S:478T
