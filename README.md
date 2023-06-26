# Network Analysis

A pipeline designed to take fungal OTU data from the pecan phyllosphere and visualize it in a network utilizing NetCoMi.

Samples were acquired from the E.V. Smith research center's Plant Breeding Unit located in Tallassee, AL. Samples occurred during the 2021 and 2022 growth seasons.

Input for NetCoMi is the following [file](https://github.com/Beatrice-Severance/Network_Analysis/blob/main/21-22-fungi-phyloseq-clean.rds). The [network creation](https://github.com/Beatrice-Severance/Network_Analysis/blob/main/Network_Creation.Rmd) script uses NetCoMi to generate a network and visualize it. Edits can be made to this step before moving to the statistics portion.

The [network statistics](https://github.com/Beatrice-Severance/Network_Analysis/blob/main/Network_Statistics.Rmd) script utilizes the generated network in order to determine whether the network created is not random. This script is computationally intense, and requires a respectable amount of cores and memory in order to complete. 