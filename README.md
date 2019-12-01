# A general model for household-structured population dynamics: presenting the first component for a model of Indus Civilisation settlements in Haryana, NW India
Presentation for the International Network -Historical and osteoarchaeological Past Populations Exploration (IN-HOPPE) workshop in Nice (5-6 December 2019)

IN-HOPPE Network home page: https://in-hoppe.site.ined.fr/fr/
Workshop programme & book of abstracts: 

Prepared with *reveal.js* (see https://revealjs.com/)

Slides: https://andros-spica.github.io/IN-HOPPE-Angourakis-et-al-2019/

**Authors**  
Angourakis, Andreas

Bates, Jennifer

Baudouin, Jean-Phillipe

Giesche, Alena

Walker, Joanna

Ustunkaya, M. Cemre 

Wright, Nathan

Singh, Ravindra N. 

Petrie, Cameron A.

For more information on authors and project: https://www.arch.cam.ac.uk/research/projects/two-rains

**Abstract**  
We present the current state of an agent-based model addressing the potential diversity of agricultural strategies adopted by Indus settlements in different socio-ecological scenarios in Haryana, NW India. This work is part of the multi-disciplinary TwoRains project and brings together research on material culture, settlement distribution, food production and consumption, vegetation, and paleoenvironmental conditions. The model aims to assess the implications of different food production strategies for the sustainability of urban population and the resilience of these in the face of changes in the intensity and variability of winter and summer water availability.  
As the first step in creating this model, we designed a general demographic model that generate population dynamics mediated by a household structure. Individuals are explicitly represented, not as separate agents, but as values (e.g., age, sex) in lists kept by household agents. Even though specifying individual-level properties and processes, individual decisions are not explicitly represented. Instead, we integrate three parametric equation-based models to define age and sex-specific probabilities for individuals to form a couple (nuptiality), give birth (fertility), and die (mortality). The fertility and nuptiality models correspond to the simplest parametric models presented in Peristera and Kostaki (2009, 2015). The mortality model is the Coale-Demeny Life Tables Model, available in the demoR package in R (Jones, 2007). Additionally, we implement two residence rules (‘matrilocal-matrilineal’ and ’patrilocal-patrilineal’) and a taboo on nuptials within lineages. Although created by couples, households in the model are not necessarily ´nuclear´; they can vary from single individuals to several couples and their children.  
We present the results of the explorations of this general demographic model, highlighting its capacity to generate more insights into the population dynamics in the past than traditional approaches. The potential utility of this model goes beyond the goals of our project. We believe it could serve as a reference or template for the modelling community in history and archaeology.

**Keywords**  
agent-based modelling; fertility; nuptiality; mortality; household
