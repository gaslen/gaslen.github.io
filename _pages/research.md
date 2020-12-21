---
layout: "single"
title: ""
permalink: "/research/"
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

# Publications

![disca](/images/disca.png){: style="float: left; margin-right: 1em;height: 100px; margin-top: 1.5em;width: 130px"} 
### Interactive Learning for Semantic Segmentation in Earth Observation
*G. Lenczner, A. Chan Hon Tong, N. Luminari, B. Le Saux, G. Le Besnerais*  
ECML-PKDD 2020, MACLEAN Workshop.
<span style="color:#e49b0f">*Best Student Paper Award.*</span>
<!-- <normal> -->
<!-- <p style="text-align: right;"> -->
<br />
    <a href="http://ceur-ws.org/Vol-2766/paper1.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://github.com/delair-ai/DISCA" style="color:page.header.overlay_color">[GitHub]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bibtex_disca');">[BibTeX]</a>
<!-- </p> -->
<!-- </normal> -->
<div id="bibtex_disca" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_disca');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_disca" class="highlight">
@inproceedings{lenczner2020interactive,
author = {Lenczner, G. and Chan-Hon-Tong, A. and Luminari, N. and Le Saux, B. and Le Besnerais, G.},
title = {Interactive Learning for Semantic Segmentation in Earth Observation},
booktitle = {ECML-PKDD MACLEAN Workshop},
year = {2020},
}
</pre></div></small>
</div>


![disir](/images/disir.png){: style="float: left; margin-right: 1em;height: 100px; margin-top: 1.5em;width: 130px"}
### DISIR: Deep Interactive Segmentation with Interactive Refinements
*G. Lenczner, B. Le Saux, N. Luminari, A. Chan Hon Tong, G. Le Besnerais*  
ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, 2020
<br />
    <a href="https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/V-2-2020/877/2020/isprs-annals-V-2-2020-877-2020.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://youtu.be/SOhylBJJTjY" style="color:page.header.overlay_color">[video]</a>
    <a href="https://github.com/delair-ai/DISIR" style="color:page.header.overlay_color">[GitHub]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bibtex_disir');">[BibTeX]</a>
<div id="bibtex_disir" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_disir');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_disir" class="highlight">
@Article{isprs-annals-V-2-2020-877-2020,
AUTHOR = {Lenczner, G. and Le Saux, B. and Luminari, N. and Chan-Hon-Tong, A. and Le Besnerais, G.},
TITLE = {DISIR: DEEP IMAGE SEGMENTATION WITH INTERACTIVE REFINEMENT},
JOURNAL = {ISPRS Annals of Photogrammetry, Remote Sensing and Spatial Information Sciences},
VOLUME = {V-2-2020},
YEAR = {2020},
PAGES = {877--884},
URL = {https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/V-2-2020/877/2020/},
DOI = {10.5194/isprs-annals-V-2-2020-877-2020}
}
</pre></div></small>
</div>

![rfiap](/images/rfiap.png){: style="float: left; margin-right: 1em;height: 120px; margin-top: 1.5em;width: 130px"}
### Segmentation sémantique d’images aériennes avec améliorations interactives
*G. Lenczner, B. Le Saux, N. Luminari, A. Chan Hon Tong, G. Le Besnerais*  
Reconnaissance des Formes, Image, Apprentissage et Perception (RFIAP), 2020
<br />
    <a href="https://cap-rfiap2020.sciencesconf.org/data/RFIAP_2020_paper_10.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://youtu.be/i-sOE6Q_aR8" style="color:page.header.overlay_color">[video]</a>
    <a href="https://drive.google.com/file/d/1wD8Ccuf-ZIGQLhEy250P89Id1FNJI_PX/view" style="color:page.header.overlay_color">[slides]</a>

------


# Talks

### Guided AI for interactive semantic segmentation.
*ESA EO Φ-Week*, September 2020 <a href="https://www.youtube.com/watch?v=txN8L2mHYrM" style="color:page.header.overlay_color">[video]</a>

### Semantic segmentation of remote sensing images with interactive refinements.
 *AI4Geo web-seminary*, July 2020 <a href="https://drive.google.com/file/d/1ZIX_f4JynthwssQsQUnmcsHD5fXdMSbK/view?usp=sharing" style="color:page.header.overlay_color">[slides]</a>

<!-- ------

# Technical reviews -->