---
layout: single
permalink: /featured-studies/
title: "Featured studies"
author_profile: true
excerpt: "Human brain organoids keep developmental time for years in a dish, and four more studies on how cells acquire, arrange and hold an identity."
og_image: "og-organoids.jpg"
og_image_alt: "Human brain organoids from six months to five years in culture, beside an epigenetic clock that tracks their age from time in culture"
---

<!-- Faded specimens behind the page. Positions and opacity live in
     _includes/head/custom.html. All figures on this page are now hosted in this
     repo, so nothing here depends on the WordPress site. -->
<div class="backdrop backdrop--tl" style="--backdrop-img: url('/images/bd-zygote.jpg')"></div>
<div class="backdrop backdrop--br" style="--backdrop-img: url('/images/bd-somite.jpg')"></div>


An embryo begins with an inheritance it has to mostly erase. A few marks are shielded, and [leaving a single one unprotected is enough to stop development](#trim28). What stays buried matters as much, because [ancient retroviruses, once awake, compete for the machinery that transcribes genes](#erv), and the pluripotent cells are the ones that pay. From the first decisions onward, cells are specified and then refined into finer identities, [less by instruction than by restriction](#gastrulation). Being the right kind of cell is not enough. It has to be in the right place, which is how organs take shape, and why [we rebuilt whole embryos in three dimensions](#atlas) to see where each state sits. Development is a problem of space and time. So when tissue is grown outside an embryo, does it still keep time? [Human brain organoids do](#organoids), for years, all on their own in a dish.

## What a cell inherits

Fertilization does not start from nothing. The egg arrives stocked with proteins and with marks laid down in the germline, and the embryo erases most of that inheritance while protecting a small part of it. What survives the erasure, and what stays buried, sets the terms for every decision that follows.

### Loss of maternal Trim28 causes male-predominant early embryonic lethality · *Genes & Development* 2017
{: #trim28 }

**Protection from reprogramming reaches beyond imprinting, and a single unprotected gene on the Y chromosome is enough to halt development in male embryos.**

![Maternal Trim28 loss causes developmental arrest and a strong loss of male embryos after implantation](/images/fs-trim28.jpg)

*Without maternal Trim28, most embryos arrest. Among those that survive implantation, few are male.*

After fertilization the embryo strips away most of the DNA methylation it inherits, shielding only a handful of sites: the imprints that keep maternal and paternal copies of certain genes distinguishable. In embryos that develop without maternal TRIM28, development stops around implantation, and not evenly between the sexes. Males are lost. The reason sits on the Y chromosome. *Rbmy1a1* is heavily methylated in sperm and holds that methylation through reprogramming because TRIM28 protects it. Without that protection the promoter loses its methylation, the gene switches on where it should be silent, and the embryos carrying it fail.

[Paper](https://genesdev.cshlp.org/content/31/1/12) · [Research highlight](https://www.nature.com/articles/nrm.2017.13)

### Hijacking of transcriptional condensates by endogenous retroviruses · *Nature Genetics* 2022
{: #erv }

**Ancient retroviruses are dangerous not because they can move, but because they compete, draining the transcriptional machinery away from the genes that need it.**

![Transcriptional condensates leave pluripotency super-enhancers and reassemble at endogenous retroviral loci after TRIM28 degradation](/images/fs-erv-condensates.jpg)

Much of the mammalian genome is sequence left behind by transposable elements, among them retroviruses that entered the germline long ago. Almost none of them can still copy themselves, yet embryos that fail to keep them silent do not survive. We degraded TRIM28, the adaptor protein that holds them shut, in mouse embryonic stem cells, and followed the transcriptional machinery. RNA polymerase II and Mediator normally collect in condensates, droplet-like assemblies that concentrate at the super-enhancers driving pluripotency genes. With TRIM28 gone, those condensates left the super-enhancers and gathered at the retroviral loci that had just switched on. Removing the retroviral RNAs, or supplying more of the factors that hold condensates at super-enhancers, brought them back. Reading *Trim28* mutant embryos one cell at a time shows where the cost is paid: the pluripotent lineages are the ones depleted.

[Paper](https://www.nature.com/articles/s41588-022-01132-w) · [Research highlight](https://www.nature.com/articles/s41588-022-01111-1)

## How an identity is assigned

Silencing sets the starting point. The next problem is choice. From one sheet of epiblast come the three germ layers and then every organ, in the right proportion and in the right place, embryo after embryo.

### Epigenetic regulator function through mouse gastrulation · *Nature* 2020
{: #gastrulation }

**Without Polycomb, the epiblast fills with extraembryonic mesoderm and germ cells, the lineages of one corner of the embryo, at the expense of everything else.**

![A wild type mouse embryo beside RNF2 and EED knockout embryos, with primordial germ cells labelled in green and greatly expanded in the EED knockout](/images/fs-gastrulation.jpg){: .plain}

*Wild type, RNF2 knockout and EED knockout embryos. Green marks primordial germ cells, few and confined in the wild type, spread through the EED mutant that has lost PRC2.*

Remove a chromatin regulator and development usually arrests. That establishes the regulator was essential, which is not the same as knowing what it did. We removed ten essential epigenetic regulators, one at a time, and read the consequences in mutant embryos cell by cell.

The Polycomb mutants were hit hardest, and losing PRC2 made the point most plainly. Those embryos overproduce extraembryonic mesoderm and primordial germ cells, lineages that normally arise from one small region of the epiblast, and they do it at the cost of the lineages that should have formed elsewhere. It is as though cells adopt an identity belonging to a position they never occupied.

A cell's fate rests as much on the options it is denied as on the instructions it is given.

[Paper](https://www.nature.com/articles/s41586-020-2552-x) · [Research highlight](https://www.nature.com/articles/s41576-020-00282-z)

### Spatiotemporal transcriptomic maps of whole mouse embryos at the onset of organogenesis · *Nature Genetics* 2023
{: #atlas }

**An embryo is not a collection of cell states. It is an arrangement of them, and the arrangement can now be read.**

<!-- Rotating 3D reconstruction. Muted and inline so phones will play it without
     a tap; the poster frame stands in wherever autoplay is blocked. -->
<video class="plain" autoplay loop muted playsinline preload="metadata"
       poster="/images/spatial-embryo-3d.jpg"
       aria-label="A three-dimensional reconstruction of an E8.5 mouse embryo rotating, with brain, heart, somites and neuromesodermal progenitors highlighted in turn">
  <source src="/images/spatial-embryo-3d.mp4" type="video/mp4">
  <img class="plain" src="/images/spatial-embryo-3d.jpg"
       alt="Three-dimensional reconstruction of an E8.5 mouse embryo with brain, heart, somites and neuromesodermal progenitors labelled">
</video>

*A reconstructed embryo, turning. Brain, heart, somites and neuromesodermal progenitors, each in its own place.*

To read cells one at a time, you first have to take the embryo apart. That gives you every state present and throws away the one thing organogenesis is about: position. A heart progenitor is a heart progenitor because of where it is. So we put position back. Whole mouse embryos, sectioned, measured, and rebuilt in three dimensions with sc3D, a tool we made for reading them. Ask for a gene and see where it is switched on. Ask for a tissue and see what it lies against. Ask what a mutation did and see which tissue ended up in the wrong place.

[Paper](https://www.nature.com/articles/s41588-023-01435-6) · [Interactive data explorer](https://cellxgene.cziscience.com/collections/d74b6979-efba-47cd-990a-9d80ccf29055) · [3D embryo viewer](https://github.com/GuignardLab/napari-sc3D-viewer)

I presented this work as an invited talk, *Spatiotemporal architecture of mouse embryogenesis at single-cell resolution*, in the Takara Bio spatial genomics webinar series. [Watch the webinar](https://www.takarabio.com/learning-centers/spatial-omics/library/webinars)
## Keeping time in a dish
{: #organoids }

### Human brain organoids record the passage of time over multiple years · *Nature* 2026

**Can cells measure time on their own?**

In an embryo, developmental time is easy to hand to the surroundings. Signals arrive on a schedule, and every tissue is paced by the ones beside it. Human brain organoids have none of that, and they keep time anyway.

We followed human brain organoids for up to five years, far longer than these cultures are usually kept, and asked whether development stalls once the early programs are done. It does not.

The clearest record is in the epigenome. Continuous culture tends to drift, wandering away from the state the cells started in. These organoids hold their ground: global DNA methylation stays stable across years. What changes is specific. Methylation shifts at defined regions of the genome, and those regions sit at programs used to build the brain. The methylome is not eroding, it is moving where development would move it.

One change is hard to account for any other way. CpA methylation, a non-canonical form found mainly in neurons after birth, begins to accumulate from around nine months in culture. A postnatal program comes on in a dish, with no birth, no sensory input, and no body to cue it.

Epigenetic clocks read all of this as age. They are sets of methylation sites whose state shifts so predictably with age that a person's age can be estimated from a blood sample, and applied here they read the years in culture: predicted age climbs across five years at close to the expected rate.

Human brain development is slow. Much of what makes it distinctive takes months and years, and that stretch has been the hardest to study in culture. Cells that keep their own time for years are a way into it.

If time is tracked with no brain around the cells to track it for them, then part of the developmental schedule is carried by the cells themselves.

![Human brain organoids from six months to five years in culture, and an epigenetic clock predicting organoid age from time in culture](/images/fs-organoid-time.jpg)

*Organoids from six months to five years in culture, and predicted epigenetic age tracking time in culture.*

[Paper](https://www.nature.com/articles/s41586-026-10877-x)
