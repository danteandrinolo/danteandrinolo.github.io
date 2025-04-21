---
title: "Optimización de estimulación eléctrica transcraneal para el tratamiento de glioblastomas"
collection: publications
category: thesis
permalink: /publication/2024-03-01-ThesisUNLP
#excerpt: 'This paper is about optimizing a technique called "TTFields", used as an alternative treatment for brain tumors by applying an electric field in the tumoral region.'
date: 2024-06-11
venue: 'SEDICI - UNLP'
#slidesurl: 'http://danteandrinolo.github.io/files/TTFieldsSABI2023Presentation.pdf'
paperurl: 'http://danteandrinolo.github.io/files/Undergraduate-Thesis-UNLP-2024.pdf'
citation: 'Dante C. Andrinolo O. &quot;Optimización de estimulación eléctrica transcraneal para el tratamiento de glioblastomas.&quot; <i>Universidad Nacional de La Plata Tesis de grado</i>. UNLP 2024'
---

Abstract: Transcranial electrical stimulation (tES) is a field that investigates the effects of
applying low-intensity electrical currents to the human brain using electrodes placed on
the scalp. Tumor Treating Fields (TTFields) is one application of tES, that consists of
applying alternating electric fields (∼300KHz) to a tumoral region to arrest its growth.
The physiological principle is that tumoral cells are killed during mitosis if the fields are
aligned with the cell subdivision direction. The conventional protocol involves switching
between two ad-hoc and intuitive anterior-posterior and left-right stimulation patterns.
The problem is that these patterns do not consider the tumor location, nor the geometrical
and electrical properties of the different tissues of the brain that affect the electric
field. There are techniques to mitigate these problems and get the best possible electric
field within the tumor. This is known as optimization. However, this technique has not
been studied or applied to TTFields. The hypothesis of this work is to enhance TTFields
technique by applying optimization methods.
The first objective of this work focuses on optimizing the current injection patterns to
stimulate the tumoral region, maximizing the average electric field intensity or the average
electric field directionality inside the tumor along predefined electric field orientations.
Optimization methods such as reciprocity theorem, linearly constrained minimum variance
filter, and convex optimization software are used to optimize the current injection using
two electrode arrays: the conventional 36-electrode TTFields array called Optune, and the
64-electrode 10-20 electroencephalography array. A realistic head model, including brain
tissues and a tumor, is used to solve the forward problem of tES using the finite element
method. Performance is evaluated based on the directionality and intensity metrics of
the electric field within the tumor. The results show improved performance in terms
of directionality and intensity for the optimized patterns compared to the conventional
protocol. The proposed optimization approach has the potential to enhance efficiency of
TTFields.
A second objective of this work is to estimate the efficacy enhancement after the
intensity and directionality obtained by the previous applied methods. A statistical model
is proposed to describe the division duration of the mitosis phases that are affected by
TTFields. This model is then used to validate and calculate the probability of cancer cell
death. For this, the empirical data is taken from the available bibliography, and then the
parameters of a proposed density probability function are estimated to fit the data. The
statistical model is fully defined using the available experimental data from dish-based
(two-dimensional) in-vitro experiments, stimulating in one and two ortogonal directions.
Then, to analyze a more realistic case, this model is extrapolated to the three-dimensional
case. tES along two and three directions were simulated, enhancing the probability of
cell death. The results of both objectives validate the hypothesis through the use of
computational simulations and the assumptions of the models.