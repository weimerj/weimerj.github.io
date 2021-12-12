---
layout: page
permalink: /research/
---

![James Weimer](images/weimer-small.png  "James Weimer"){: style="float: right; margin-left: 1em; height=300;"}


My research aims to develop techniques and tools for the design and analysis of learning-enabled cyber-physical
systems (LE-CPS) with thin data primarily targeting applications in the internet-of-medical-things (IoMT)
and autonomous vehicles (AVs). These systems present a unique combination of challenges stemming from the
intersection of data science, embedded systems, and cyber-physical security in healthcare and autonomy
applications -- challenges that are not well handled by existing robust engineering paradigms. To address these
challenges, my research aims to develop novel design and analysis techniques for (i) interoperable IoT devices,
(ii) actionable decision support, and (iii) safe learning-enabled control. Maximizing the impact of my research
requires an interdisciplinary approach - thus, I openly collaborate with medical professionals and industry to
transition my research into practice. 


Q: What are the technical challenges of LE-CPS?  

A: Traditional cyber-physical systems (CPS) are safety-critical embedded systems that feature tight coupling
between communication and computation used to control complex, dynamic, and uncertain physical/physiological plants.
Learning-enabled CPS (LE-CPS) additionally incorporate components whose behavior is driven by "background knowledge"
acquired and updated through a "learning process". The design and analysis of LE-CPS presents multiple technical
challenges. First, the data collection process requires identifying and collecting the right data for learning.
Second, assuring safety necessitates the ability to provide actionable feedback to clinicans/human operators in
situations where confidence in learning degrades. Third, closing-the-loop with learning-enabled components presents
challenges for safety and security assurance. 

Q: What is "thin data"?

A: While empirical data is often a significant source of this background knowledge in LE-CPS, it can also be limited,
sparse, or "thin" due to unmodeled variability, dataset shifts, anomalies, and sensing constraints. Consequently,
providing safety guarantees and predictable performance in learning-enabled CPS with thin data is challenging. My
research addresses the challenges of thin data by incorporating additional sources of background knowledge including
physical/physiological models and contextual information. In healthcare, my work utilizes new sensing modalities
as well as physiological and contextual information to overcome thin data challenges stemming from inter/intra-patient
variability, constrained sensing and actuation capabilities, limited and protected patient populations, and uncertain
models of multi-system physiology. Similarly in autonomy, my research utilizes physical models to enable operation in
time-varying, uncertain, unstructured, and adversarial environments.



There is a growing recognition of the importance of robustness in machine learning stemming from the discovery 
and prevalence of adversarial examples. Consequently, monitoring and analysis of adversarial examples in machine 
learning has received much interest recently. While much of the work is focused on small perturbations to input 
images, even children would not be fooled by these adversarial examples due to the robustness of their concepts.  
Thus, this proposal aims to re-think robust and adaptive machine learning to unlock the key to generative and 
flexible learning by understanding how very young children approach the world.  Our goal is to advent truly 
robust and adaptive learning tools that benefit---as children do---from experiences and interactions in the world.
