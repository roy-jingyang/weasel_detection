# Mining Weasel Patterns from Event Logs

This repository holds implementations and experiment results related to our
paper submitted to the International Conference on Process Mining (ICPM) 2024:

Yang, J., Leyer, M., ter Hofstede, A. H. M., & Syed, R. (2024). Mining Weasel
Patterns from Event Logs: Framework and Methods. *Paper submitted to ICPM 2024
(under review)*

## Jupyter Notebooks

There are, in total, 13 weasel behavioral patterns[^Leyer2023], categorized into
three groups: Rerouting-related, performance-related, and social-related
patterns.

For each of them, we provide a Jupyter Notebook that contains an implementation
of the designed detection method and the related visualization. All
implementations are done in Python (version 3.12.1). Specifically, interactive
visualizations are built using Python-Altair[^VanderPlas2018]. 

The implemented methods are evaluated on a proprietary event log dataset as
indicated in the paper. The evaluation results can be found in the corresponding
notebook. 

## Viewing the results

Note that the GitHub preview functionality may not render Altair visualizations
properly. It means that you may not be able to see the figures as they are shown
in the paper. In order to view the results properly, you may choose to render
those notebooks yourself, or to download and view the exported HTML documents
under folder https://github.com/roy-jingyang/weasel_detection/tree/main/exported 

To assist with reproducibility, an environment file (`.yml`) is made available
at: https://github.com/roy-jingyang/weasel_detection/blob/main/environment.yml

### References

[^Leyer2023]: Leyer, M., ter Hofstede, A. H. M., & Syed, R. (2023). Detecting
    Weasels at Work: A Theory-Driven Behavioural Process Mining Approach.
    Business Process Management Forum - BPM Forum 2023, 337–354.

[^VanderPlas2018]: VanderPlas, J., Granger, B., Heer, J., Moritz, D.,
    Wongsuphasawat, K., Satyanarayan, A., Lees, E., Timofeev, I., Welsh, B., &
    Sievert, S. (2018). Altair: Interactive statistical visualizations for
    python. Journal of Open Source Software, 3(32), 1057.

