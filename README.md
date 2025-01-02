# Enhanced adjuvanticity of a personal neoantigen vaccine generates potent immunity in melanoma
<p align="justify">
  Eryn Blass*, Derin B. Keskin*, Chloe R. Tu, Cleo Forman, Allison Vanasse, Haley E. Sax, Bohoon Shim, Vipheaviny Chea, Nawoo Kim, Isabel Carulli, Jackson Southard, Haoxiang Lyu, Wesley Lu, Micah Rickles-Young, Alexander B. Afeyan, Oriol Olive, Ambica Mehndiratta, Haley Greenslade, Keerthi Shetty, Joanna Baginska, Ilana Gomez-Diaz, Allison Nau, Kathleen L. Pfaff, Andrew Gans, Elizabeth I Buchbinder, Tamara A. Sussman, Megan L Insco, Charles H. Yoon, Scott J. Rodig, Sachet A. Shukla, Shuqiang Li, Jon C. Aster, David A. Braun, Carrie Cibulskis, Nir Hacohen, Donna S. Neuberg, A Giobbie-Hurder, Kenneth J. Livak, Edward F. Fritsch, Giacomo Oliveira, Jeremy M. Simon, Catherine J. Wu, Patrick A. Ott
</p>

## Abstract
<p align="justify">
  Personalized neoantigen-targeting vaccines have great promise, but current delivery strategies are suboptimal. Since antigen availability and effective T cell priming are critical for maximal immunogenicity, we tested a synthetic long peptide vaccine formulated with Montanide, poly-ICLC, and locally administered ipilimumab in addition to systemic nivolumab in 10 patients with melanoma. These personalized vaccines generated de novo ex vivo T cell responses against the majority of immunizing neoepitopes in all 9 fully vaccinated patients, and ex vivo CD8+ T cell responses in 6 of 9. Vaccination induced hundreds of circulating and intratumoral T cell receptor (TCR) clonotypes that were distinct from those arising after PD-1 inhibition. By linking the vaccine neoantigen specificity of T cell clonotypes with single cell phenotypes in tumors, we demonstrate remodeling of the intratumoral T cell repertoire following vaccination. These observations show that multi-pronged immune adjuvanticity can boost T cell responses to neoantigen-targeting vaccines
</p>

# Contents
<p align="justify">

  This repository contains all code to reproduce figures related to analyses of single-cell data associated with Blass & Keskin, _et al_ (2025, _under review_)

  Included and linked here are books rendered via `Quarto`, one for each stage of the analysis:

  * Analysis of IFNg-stimulated T cells [available here](https://jeremymsimon.github.io/BlassKeskin_Melanoma_NeoVax/IFNg_book/)
  * Analysis of Tumor biopsies [available here](https://jeremymsimon.github.io/BlassKeskin_Melanoma_NeoVax/Tumor_book/)
  * Analysis of Skin vaccine-site biopsies [available here](https://jeremymsimon.github.io/BlassKeskin_Melanoma_NeoVax/Skin_book/)
  * Analysis of bulk TCR clonotypes and dynamics (_coming soon_)
  * Analysis of single-cell TCR clonotypes and integrative analyses with scRNA data (_coming soon_)

  Additionally, source quarto markdown documents (`*.qmd`) are supplied here under each book's subdirectory, e.g.:
  https://github.com/jeremymsimon/BlassKeskin_Melanoma_NeoVax/tree/main/IFNg_book/source

</p>

# Note
<p align="justify">
While all code supplied here is identical, these books were rendered after final manuscript figures were generated and thus minor differences may arise, particularly for steps that are non-deterministic or rely on random number generators.
</p>
