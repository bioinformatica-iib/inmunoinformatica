---
layout: page
title: T-Cell Epitopes
subtitle: Class 2
permalink: classes/class-2/
comments: false
menubar_toc: true
hide_hero: True
published: False
---

## T-Cell Epitopes

### Lecture: Prediction of MHC peptide binding (Part 1) 

- [Slides [PDF]](http://www.cbs.dtu.dk/courses/27685.imm/presentations/MHCbinding_2020_part1.pdf) & [Recording [MP4]](http://www.cbs.dtu.dk/courses/27685.imm/recordings/MHC_part1.mp4).
- [Logo handout [PDF]](http://www.cbs.dtu.dk/courses/27685.imm/presentations/Ex_Logo.pdf).
- [Answer Logo handout Logo handout [PDF]](http://www.cbs.dtu.dk/courses/27685.imm/presentations/Ex_Logo_ans.pdf) & [Recording [MP4]](http://www.cbs.dtu.dk/courses/27685.imm/recordings/Ex_Logo.mp4)

### Lecture: Prediction of MHC peptide binding (Part 2)

- [Slides [PDF]](http://www.cbs.dtu.dk/courses/27685.imm/presentations/MHCbinding_2020_part2.pdf) & [Recording: [MP4]](http://www.cbs.dtu.dk/courses/27685.imm/recordings/MHC_part2.mp4).
- [NN handout [PDF]](http://www.cbs.dtu.dk/courses/27685.imm/presentations/NN_handout.pdf) & [Recording [MP4]](http://www.cbs.dtu.dk/courses/27685.imm/recordings/Ex_NN.mp4).

### Lecture: Prediction of MHC peptide binding (Part 3)

- [Slides [PDF]](http://www.cbs.dtu.dk/courses/27685.imm/presentations/MHCbinding_2020_part3.pdf) & [Recording [MP4]](http://www.cbs.dtu.dk/courses/27685.imm/recordings/MHC_part3.mp4).

### Performance measures

- [Slides [PDF]](http://www.cbs.dtu.dk/courses/ILRI_workshop/presentations/Performance_measure.pdf) & [Recording [MP4]](http://www.cbs.dtu.dk/courses/22125/recordings/Performance_measure.mp4).

## Learning Resources

### Required

- [Book: Immuno. Bioinfo. Ch. 13](https://teaching.healthtech.dtu.dk/22145/images/a/aa/Lund_et_al_immunological_bioinformatics_2005_chapter_13.pdf)
- [Book: Immuno. Bioinfo. Ch. 14](https://teaching.healthtech.dtu.dk/22145/images/b/ba/Lund_et_al_immunological_bioinformatics_2005_chapter_14.pdf)
- [Paper: T Cell Epitope Predictions](https://www.annualreviews.org/doi/10.1146/annurev-immunol-082119-124838)

### Optional
- [Paper: Simultaneous alignment and clustering of peptide data using a Gibbs sampling approach](https://www.ncbi.nlm.nih.gov/pubmed/23097419)
- [Paper: A Quantitative Analysis of the Variables Affecting the Repertoire of T Cell Specificities Recognized after Vaccinia Virus Infection](http://www.jimmunol.org/content/178/12/7890.long)
- [Paper: Identification and HLA-tetramer-validation of human CD4+ and CD8+ T cell responses against HCMV proteins IE1 and IE2](https://www.ncbi.nlm.nih.gov/pubmed/24760079)

{% if page.comments %}

## Forum

<div id="disqus_thread"></div>
<script>

    var disqus_config = function () {
      this.page.url = '{{ page.url | absolute_url }}';
      this.page.identifier = '{{ page.disqus_id }}';
    };

    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://inmunoinformatics.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();

</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

<script id="dsq-count-scr" src="//inmunoinformatics.disqus.com/count.js" async></script>
{% endif %}