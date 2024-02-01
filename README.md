# Data-driven Commercial Urban Building Energy Use Intensity (C-UBEUI) Classification Model in Hong Kong
This is the python code and sample data for the published paper titled "**_Use of publicly available data to create a dataset for data-driven urban commercial building energy intensity classification: Model accuracy, interpretation, and implications of an open data framework in Hong Kong_**", which has been published in **_[Sustainable Cities and Society](https://www.sciencedirect.com/science/article/pii/S221067072300673X)_**, Elsevier, in January 2024.

## Abstract
Previous studies relied on structured databases containing energy use intensity (EUI) and building features to develop data-driven urban building energy models (D-UBEMs). However, such databases are not available in most cities. In Hong Kong, energy audit is required for commercial buildings, but only EUI is publicly released without any building information. We assessed the adequacy of input features collected and integrated from public sources to develop a precise D-UBEM. We separated Hong Kong commercial building samples into “below-median” and “above-median” EUI categories based on the bimodal distribution of log10EUI and developed a data-driven binary classifier to predict the category. Using publicly available input features, the average classification accuracy is 78.73%. We used the D-UBEM to reveal the association of “above-median” EUI category with input features, and spatially visualize floor areas of Hong Kong commercial buildings belonging to the “above-median” EUI category. In the discussion, we examined the causes of misclassified buildings and highlighted the limitations of our database from public sources in developing accurate and useful D-UBEMs. We suggested an open-data policy framework for releasing building information alongside EUI data and establishing a central database that contains more precise values for building geometries, usage, and thermal performance in Hong Kong.

## Keywords
Urban building energy modeling; Public data; Database construction; Data-driven methods; Model interpretation; Spatial visualization

## Framework
The below figure displays the workflow of using publicly available data to create and integrate a Hong Kong commercial building database, developing the D-UBEM, and applying the D-UBEM to interpret and visualize the EUI.

![Framework](https://github.com/hkust-suscity/Commercial-Building-Energy-Use-Intensity-Modelling/blob/main/02_Sample-Data/Framework.jpg)

## Declaration of Competing Interest
The authors declare that they have no known competing financial interests or personal relationships that could have appeared to influence the work reported in this paper.

## Acknowledgement 
This project was supported by the Hong Kong University of Science and Technology startup, the Guangdong Basic and Applied Basic Research Foundation (2019A1515010828 and 2023A1515030256), and the Strategic Topics Grant from Hong Kong Research Grants Council (STG2/E-605/23-N). The authors would like to thank Dr. Ren Chao for providing the climate data, Mr. Mingolla Stefano for suggestions, and Mr. Jiwei Li for initial exploration. The authors would also like to thank the anonymous reviewers for their valuable comments and suggestions. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author and do not necessarily reflect the views of the funding agencies in any form.
