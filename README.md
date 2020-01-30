# magres
MAS-based group recommendation: MAGRES

This repository contains information about the main characteristics of the proposed group recommendation approach and the experimental evaluation of MAGRES for recommending POIs for group of users. 

![Proposed Approach]approach.jpg)


The content of the repository is the following:

- Information about the dataset used: https://www.yelp.com/dataset/challenge
- Figure 1 (approach.jpg): Magres approach for POIs group recommendation
- Figure 2 (poi example.jpg): Example of group members movement areas
- Figure 3 (): MCP negotiation example over POIs
- Figure 4 (mcp.jpg): MCP protocol
- Table 1 (Neighborhood_Parameterizations.jpg): Neighborhood selection strategies parametrization
- Table 2 (Approaches_ParametersTable.jpg): Parameters for each evaluates approach (Magres and baselines)
For NN selection strategy
- Table 3 (GS_NN.jpg): Average group satisfaction per approach and neighborhood size. The best result per line is underlined
- Table 4 (MSD_NN.jpg): Average MSD per approach and neighborhood size
- Table 5 (Fairness_NN.jpg): Average fairness per approacho and neighborhood size
For NNUZ selection strategy
- Table 6 (GS_NNUZ.jpg): Average group satisfaction per approach and neighborhood size. The best result per line is underlined
- Table 7 (MSD_NNUZ.jpg): Average MSD per approach and neighborhood size
- Table 8 (Fairness_NNUZ.jpg): Average fairness per approacho and neighborhood size
Impact of LBSN information
- Table 9 (EffectiveRecs_NN+NNUZ.jpg): LBSN data impact on the amount of items recommended
- Table 10 (Fairness_Improvement_NN+NNUZ.jpg): Fairness changes: NNUZ with respect to NN
- Table 11 (MAE&RMSE_AllNeighborhoodSizes.jpg): MAE and RMSE for all the neighborhood sizes
- Table 12 (NeighborsPerUser_NN+NNUZ.jpg): Neighbors per user for all the neighborhood sizes
