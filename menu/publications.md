---
layout: page
title: Publications
---

<script type="text/javascript">
   function toggleVisibility(block_id) {
       var e = document.getElementById(block_id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
    function copyToClip(element) {
        var str = document.getElementById(element).innerHTML;
        function listener(e) {
            e.clipboardData.setData("text/html", str);
            e.clipboardData.setData("text/plain", str);
            e.preventDefault();
        }
        document.addEventListener("copy", listener);
        document.execCommand("copy");
        document.removeEventListener("copy", listener);
};
</script>

#### 2021

* Marianna Apidianaki and **Aina Garí Soler** (2021). ALL Dolphins Are Intelligent and SOME Are Friendly: Probing BERT for Nouns’ Semantic Properties and their Prototypicality. To appear in _Proceedings of the Fourth BlackBoxNLP Workshop on Analyzing and Interpreting Neural Networks for NLP, Punta Cana, Dominican Republic and Online, November, 11._ 

* **Aina Garí Soler** and Marianna Apidianaki (2021). [Let's Play Mono-Poly: BERT Can Reveal Words’ Polysemy Level and Partitionability into Senses](https://arxiv.org/abs/2104.14694). In _Transactions of the Association for Computational Linguistics (TACL)._ <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_monopoly2021');">[BibTeX]</a>
<div id="bib_monopoly2021" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_monopoly2021');">Copy</a>
<div class="highlighter-rouge"><pre id="bib_monopoly2021" class="highlight">
@article{gari-soler-apidianaki-2021-monopoly,
    author = {Garí Soler, Aina and Apidianaki, Marianna},
    title = "{Let’s Play Mono-Poly: BERT Can Reveal Words’ Polysemy Level and Partitionability into Senses}",
    journal = {Transactions of the Association for Computational Linguistics},
    volume = {9},
    pages = {825-844},
    year = {2021},
    month = {08},   
    issn = {2307-387X},
    doi = {10.1162/tacl_a_00400},
    url = {https://doi.org/10.1162/tacl\_a\_00400},
    eprint = {https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl\_a\_00400/1955204/tacl\_a\_00400.pdf},
}
</pre></div></small>
</div>

* **Aina Garí Soler** and Marianna Apidianaki (2021). [Scalar Adjective Identification and Multilingual Ranking](https://arxiv.org/abs/2105.01180). In _Proceedings of the 2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL-HLT 2021), Mexico City, Mexico, June 6-11._ 
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_scalar2021');">[BibTeX]</a>
<div id="bib_scalar2021" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_scalar2021');">Copy</a>
<div class="highlighter-rouge"><pre id="bib_scalar2021" class="highlight">
@inproceedings{gari-soler-apidianaki-2021-scalar,
    title = "{S}calar {A}djective {I}dentification and {M}ultilingual {R}anking",
    author = "Gar{\'\i} Soler, Aina  and
      Apidianaki, Marianna",
    booktitle = "Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.naacl-main.370",
    doi = "10.18653/v1/2021.naacl-main.370",
    pages = "4653--4660",  
}
</pre></div></small>
</div>


#### 2020

* **Aina Garí Soler** and Marianna Apidianaki (2020). [BERT Knows Punta Cana is not just _beautiful_, it's _gorgeous_: Ranking Scalar Adjectives with Contextualised Representations](https://www.aclweb.org/anthology/2020.emnlp-main.598/). In _Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP), Nov 16-20._ <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_scalar2020');">[BibTeX]</a>
<div id="bib_scalar2020" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_scalar2020');">Copy</a>
<div class="highlighter-rouge"><pre id="bib_scalar2020" class="highlight">
@inproceedings{gari-soler-apidianaki-2020-bert,
    title = "{BERT} {K}nows {P}unta {C}ana is not just beautiful, it{'}s gorgeous: {R}anking {S}calar {A}djectives with {C}ontextualised {R}epresentations",
    author = "Gar{\'\i} Soler, Aina  and
      Apidianaki, Marianna",
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2020.emnlp-main.598",
    doi = "10.18653/v1/2020.emnlp-main.598",
    pages = "7371--7385",
}
</pre></div></small>
</div>

* **Aina Garí Soler** and Marianna Apidianaki (2020). [MULTISEM at SemEval-2020 Task 3: Fine-tuning BERT for Lexical Meaning](https://www.aclweb.org/anthology/2020.semeval-1.18/). In _Proceedings of the 14th International Workshop on Semantic Evaluation, Dec 12-13, Barcelona, Spain._ <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_semeval2020');">[BibTeX]</a>
<div id="bib_semeval2020" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_semeval2020');">Copy</a>
<div class="highlighter-rouge"><pre id="bib_semeval2020" class="highlight">
@inproceedings{gari-soler-apidianaki-2020-multisem,
    title = "{MULTISEM} at {S}em{E}val-2020 {T}ask 3: {F}ine-tuning {BERT} for {L}exical {M}eaning",
    author = "Gar{\'\i} Soler, Aina  and
      Apidianaki, Marianna",
    booktitle = "Proceedings of the Fourteenth Workshop on Semantic Evaluation",
    month = dec,
    year = "2020",
    address = "Barcelona (online)",
    publisher = "International Committee for Computational Linguistics",
    url = "https://aclanthology.org/2020.semeval-1.18",
    pages = "158--165",
}
</pre></div></small>
</div>

#### 2019

* **Aina Garí Soler**, Marianna Apidianaki and Alexandre Allauzen (2019). [LIMSI-MultiSem at the IJCAI SemDeep-5 WiC Challenge: Context Representations for Word Usage Similarity Estimation](http://www.dfki.de/~declerck/semdeep-5/papers/wic_SemDeep-5_paper_4.pdf). In _5th Workshop on Semantic Deep Learning (SemDeep-5)._  <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_semdeep2019');">[BibTeX]</a>
<div id="bib_semdeep2019" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_semdeep2019');">Copy</a>
<div class="highlighter-rouge"><pre id="bib_semdeep2019" class="highlight">
@inproceedings{gari-soler-etal-2019-limsi,
    title = "{LIMSI-MULTISEM} at the {IJCAI} {S}em{D}eep-5 {W}i{C} {C}hallenge: {C}ontext {R}epresentations for {W}ord {U}sage {S}imilarity {E}stimation",
    author = "Gar{\'\i} Soler, Aina  and
      Apidianaki, Marianna  and
      Allauzen, Alexandre",
    booktitle = "Proceedings of the 5th Workshop on Semantic Deep Learning (SemDeep-5)",
    month = aug,
    year = "2019",
    address = "Macau, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/W19-5802",
    pages = "6--11",
}
</pre></div></small>
</div>

* **Aina Garí Soler**, Marianna Apidianaki and Alexandre Allauzen (2019). [Word Usage Similarity Estimation with Sentence Representations and Automatic Substitutes](https://www.aclweb.org/anthology/S19-1002). In *Proceedings of the 8th Joint Conference on Lexical and Computational Semantics (STARSEM2019), Jun 6-7, Minneapolis, USA.* `Accepted at ACL 2019`
 <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_usim2019');">[BibTeX]</a>
<div id="bib_usim2019" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_usim2019');">Copy</a>
<div class="highlighter-rouge"><pre id="bib_usim2019" class="highlight">
@inproceedings{gari-soler-etal-2019-word,
    title = "{W}ord {U}sage {S}imilarity {E}stimation with {S}entence {R}epresentations and {A}utomatic {S}ubstitutes",
    author = "Gar{\'\i} Soler, Aina  and
      Apidianaki, Marianna  and
      Allauzen, Alexandre",
    booktitle = "Proceedings of the Eighth Joint Conference on Lexical and Computational Semantics (*{SEM} 2019)",
    month = jun,
    year = "2019",
    address = "Minneapolis, Minnesota",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/S19-1002",
    doi = "10.18653/v1/S19-1002",
    pages = "9--21",   
}
</pre></div></small>
</div>


* Syrielle Montariol, **Aina Garí Soler** and Alexandre Allauzen (2019). [Exploring sentence informativeness](https://arxiv.org/pdf/1907.08469.pdf). In  _Proceedings of TALN, Jul 1-5, Toulouse, France._ 
 <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_informativeness2019');">[BibTeX]</a>
<div id="bib_informativeness2019" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_informativeness2019');">Copy</a>
<div class="highlighter-rouge"><pre id="bib_informativeness2019" class="highlight">
@inproceedings{montariol-etal-2019-exploring,
    title = "{E}xploring sentence informativeness",
    author = "Montariol, Syrielle  and
      Gar{\'\i} Soler, Aina  and
      Allauzen, Alexandre",
    booktitle = "Actes de la Conf{\'e}rence sur le Traitement Automatique des Langues Naturelles (TALN) PFIA 2019. Volume II : Articles courts",
    month = "7",
    year = "2019",
    address = "Toulouse, France",
    publisher = "ATALA",
    url = "https://aclanthology.org/2019.jeptalnrecital-court.16",
    pages = "303--312", 
}
</pre></div></small>
</div>


* **Aina Garí Soler**, Anne Cocos, Marianna Apidianaki and Chris Callison-Burch (2019). [A Comparison of Context-sensitive Models for Lexical Substitution](https://www.aclweb.org/anthology/W19-0423). In _Proceedings of the 13th International Conference on Computational Semantics (IWCS 2019), 23-27 May, Gothenburg, Sweden._  <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_lexsub2019');">[BibTeX]</a>
<div id="bib_lexsub2019" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_lexsub2019');">Copy</a>
<div class="highlighter-rouge"><pre id="bib_lexsub2019" class="highlight">
@inproceedings{gari-soler-etal-2019-comparison,
    title = "{A} {C}omparison of {C}ontext-sensitive {M}odels for {L}exical {S}ubstitution",
    author = "Gar{\'\i} Soler, Aina  and
      Cocos, Anne  and
      Apidianaki, Marianna  and
      Callison-Burch, Chris",
    booktitle = "Proceedings of the 13th International Conference on Computational Semantics - Long Papers",
    month = may,
    year = "2019",
    address = "Gothenburg, Sweden",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/W19-0423",
    doi = "10.18653/v1/W19-0423",
    pages = "271--282",   
}
</pre></div></small>
</div>


* Antonia Tovar, **Aina Garí Soler**, Jesús Ruiz-Idiago, Celia Mareca Viladrich, Edith Pomarol-Clotet, Joana Rosselló, Wolfram Hinzen. 2019. [Language disintegration in spontaneous speech in Huntington’s disease: a more fine-grained analysis](https://doi.org/10.1016/j.jcomdis.2019.105970). In _Journal of Communication Disorders, in press._

* Antonia Tovar Torres, Wolfgang Sebastian Schmeisser Nieto, **Aina Garí Soler**, Catalina Morey Matamalas, Wolfram Hinzen (2019). [Language disintegration under conditions of severe formal thought disorder.](https://www.glossa-journal.org/article/10.5334/gjgl.720/) In _Glossa: A Journal of General Linguistics, 4(1), 134._

#### Older

* **Aina Garí**, Marianna Apidianaki and Alexandre Allauzen (2018). [A comparative study of word embeddings and other features for lexical complexity detection in French](https://www.semanticscholar.org/paper/A-comparative-study-of-word-embeddings-and-other-in-Soler-Apidianaki/19329470f1ec5a3f7a4b817e3bc912aa82d9b7f2?p2df). In  _Proceedings of TALN, May 14-18, Rennes, France._

* Mariona Taulé, M. Antònia Martí, Ann Bies, **Aina Garí**, Montserrat Nofre, Zhiyi Song, Stephanie Strassel and Joe Ellis (2015). [Spanish Treebank Annotation of Informal Non-Standard Web Text](https://www.ldc.upenn.edu/sites/www.ldc.upenn.edu/files/nlpit2015-spanish-treebank-annotation.pdf). In _Daniel, F. and Díaz O. (Eds.) Proceedings of ICWE-2015, Lecture Notes in Computer Science. Springer Verlag. ISSN 0302-9743._

* Muntsa Padró, Núria Bel and **Aina Garí** (2013). [Verb SCF extraction for Spanish with dependency parsing](https://pdfs.semanticscholar.org/0505/8e6c6e9f2851570b64fb1cce1374071908e5.pdf?_ga=2.240515524.617673213.1562600575-496965568.1562600575). In _Procesamiento del Lenguaje Natural 51, 93-100. September 2013._

