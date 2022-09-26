# MEAHNE
mirna-disease potential association prediction
#Heterogeneous Neural Network
#semantic attention aggregation + semantic information fusion
#Multi-metapath semantic fusion

#The data is placed in the DATA folder
#The reproduction method is: execute the jupyter files in order

#Advantages of our model: Propose a semantic-level attention mechanism on heterogeneous networks, 
instead of simply treating metapath edges as equivalent.

#Abstract: Correct prediction of potential miRNA-disease pairs is able to greatly accelerate the experimental process in biomedical research. However, many methods cannot effectively learn the complex information in the multi-source data, and limits the performance of the prediction model. A heterogeneous network prediction model (MEAHNE) is proposed to make full use of the complex information in multi-source data. To fully mine the potential relationship between miRNA and disease, we collected multi-source data and constructed a heterogeneous network. After completing the network, we mine potential associations in the network through a designed heterogeneous network framework (MEAHNE). MEAHNE first learns the semantic information of the metapath instances, then uses the attention mechanism to encode the semantic information as attention weights and aggregates nodes of the same type using the attention weights. The semantic information is also integrated into the node. MEAHNE optimizes parameters through end-to-end training. MEAHNE is compared with other state-of-the-art heterogeneous graph neural network methods. The values of area under precision-recall curve and receiver operating characteristic curve show the superiority of MEAHNE. In addition, MEAHNE predicted 20 miRNAs each for breast cancer and nasopharyngeal cancer, and verified 18 miRNAs related to breast cancer and 14 miRNAs related to nasopharyngeal cancer by consulting related databases.