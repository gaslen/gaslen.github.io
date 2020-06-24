---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
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


## DISIR: Deep Interactive Segmentation with Interactive Refinements
*G. Lenczner, B. Le Saux, N. Luminari, A. Chan Hon Tong, G. Le Besnerais*  
ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, 2020
<normal>
    <a href="https://arxiv.org/abs/2003.14200" style="color:page.header.overlay_color">[preprint]</a>
    <a href="https://github.com/delair-ai/DISIR" style="color:page.header.overlay_color">[GitHub]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bibtex_disir');">[BibTeX]</a>
</normal>
<div id="bibtex_disir" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_disir');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_disir" class="highlight">
@article{lenczner_disir_2020,
    title={DISIR: Deep Image Segmentation with Interactive Refinement},
    author={Lenczner, Gaston and {Le Saux}, Bertrand and Luminari, Nicola and {Chan Hon Tong}, Adrien and {Le Besnerais}, Guy},
    journal={ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences},
    year = {2020},
    publisher={Copernicus GmbH}
}
</pre></div></small>
</div>

## Segmentation sémantique d’images aériennes avec améliorations interactives
*G. Lenczner, B. Le Saux, N. Luminari, A. Chan Hon Tong, G. Le Besnerais*  
Reconnaissance des Formes, Image, Apprentissage et Perception (RFIAP), 2020
<normal>
    <a href="https://cap-rfiap2020.sciencesconf.org/data/RFIAP_2020_paper_10.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://youtu.be/i-sOE6Q_aR8" style="color:page.header.overlay_color">[video]</a>
    <a href="https://drive.google.com/file/d/1wD8Ccuf-ZIGQLhEy250P89Id1FNJI_PX/view" style="color:page.header.overlay_color">[slides]</a>
</normal>
