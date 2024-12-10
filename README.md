## Connection Detection in Wikipedia Article Network of Chameleon

## Abstract
This assignment focuses on analyzing the Wikipedia Article Network related to the Chameleon topic. It employs page-to-page networks, where each article is a node, and the connections between them are edges representing relationships. Information networks are crucial for decision-making, knowledge discovery, and understanding complex data interconnections. The study compares methodologies from two other research projects on Amazon's Co-Purchasing Network and GitHub user interactions. By implementing the Louvain algorithm, the research identifies community structures and influential nodes within the Chameleon dataset. The analysis includes network graph visualization, exploration of network characteristics, and centrality measures and community detection. The results reveal a complex and decentralized structure, highlighting well-defined communities and influential nodes in the dataset. Future work is addressed encompassing additional datasets, subset visualization, link prediction, and k-core cliques analysis. In conclusion, the study enhances our understanding of the Chameleon dataset's network dynamics, influential communities, robust structures, and potential applications in broader network analysis research.

To make the important sections bold in your GitHub README, use Markdown syntax for bold text (`**` or `__`). Below is the modified version of your provided text, with key terms and headings bolded for clarity:

---

# **Discussion and Interpretation of Results**

## **Network Graph Visualization**
Visualized three types of graphs to present the graph in a better way. In **Figure 1**, the nodes are in very cluster form because of a large number of datasets. Using **Erdős-Rényi** and **Watts-Strogatz** models helped overcome the challenges of visualizing a large network of chameleon datasets. Though **Erdős-Rényi** and **Watts-Strogatz** models have different purposes, the analysis has been done on the original graph to understand the nature of the network.

## **Network Characteristics**
- The **mean degree** of 2.99 of the original network represents a moderate level of connectivity in the network, showing that, on average, each node is connected to approximately 2.99 other nodes. These findings are important for understanding the normal connectivity patterns in the dataset.
- The **density** of 0.0025 suggests **Centrality Measures**:
  - The **degree centrality** distribution shows that **Node 1976** has the maximum degree value of 0.0376, indicating **Node 1976** has the most connections in the network.
  - **Node 2249** has the maximum **Closeness centrality** value compared to all other nodes in the network.
  - The highest **betweenness centrality** value node is **2249**. Identifying these three measures could enable us to understand the nature of the chameleon network.

## **Community Detection using the Louvain Algorithm**
- To detect the communities within the network, the best algorithm, **Louvain algorithm**, is used as it has various advantages like effectiveness, efficiency, etc.
- By applying the **Louvain algorithm**, 105 communities have been found in the chameleon network. **Community 6** has the largest nodes and also achieved the highest **modularity value** of 0.778. **Table 1** indicates that the “**Understanding the User Interactions on GitHub: A Social Network Perspective**” [2] has achieved the modularity value of **0.467**. Compared to this value, the chameleon dataset has achieved a modularity of **0.778**, which indicates our analysis has a strong and well-defined structure.

| **Application** | **Modularity value** |
|-----------------|----------------------|
| GitHub [2]      | 0.467                |
| Chameleon Network | 0.778                |

After filtering weak nodes with a **degree centrality** maximum value of 0.01, the analysis focuses on 14 influential communities found in the network. The density of **2.4571** suggests increased connectivity within the filtered network. The **modularity value** is **0.4524**, suggesting a well-structured network. The **Lavender color communities** have the highest number of nodes. The degree and closeness of betweenness show the quality of the network.

## **Overall Observations**
- The obtained results suggest that the **Chameleon dataset** shows a **complex** and **decentralized structure**, with influential nodes and well-defined communities.
- Analyzing the **centrality measures** reveals main nodes that play crucial roles in information flow and network connectivity.

## **Future Work**
### **Additional Dataset**
Performing analysis without processing the **Chameleon dataset** can identify more communities as it has a larger number of nodes (**2,277**) and edges (**31,421**).

### **Subset Visualization**
**Link Prediction** [8] is a possible task for analyzing the **Chameleon dataset**. **Link prediction**, also known as **link forecasting**, is a crucial task in network analysis that helps to identify important links (edges) that may form between nodes. By applying this method in the **Chameleon dataset**, it will find the important mutual article (edge) in the network. The prediction is done by following approaches: **Similarity-based methods**, **Maximum likelihood methods**, and **Probabilistic methods**.

### **K-Core Cliques**
Working on **k-core cliques** in the future will make our analysis worthwhile and help us understand how the network works. **K-core cliques** are like tightly-knit groups within the larger network, and understanding them can tell us more about how different parts of the network are strongly connected. This method will help us understand how different parts of the network impact the entire network.

## **Conclusion**
The current analysis provides helpful information about the **Chameleon dataset**'s **network structure**, characteristics, and community organization. Finding influential communities within the **Chameleon network** helps understand **information flow** and enhances the robustness of the network. This strength is important because it helps the network handle different ways information moves around without getting easily affected. Especially the application of the **Louvain algorithm**, which not only contributes to the understanding of the **Chameleon dataset** but also provides insights applicable to **real-world scenarios**. Understanding natural groupings and influential nodes has implications for various fields such as **social network analysis**, **information retrieval**, and **content recommendation systems**. The high **modularity values** obtained through the **Louvain algorithm** and **community filtering** signify a well-structured network. Further exploration with additional datasets and detailed subset visualizations could enhance the understanding of target communities in network dynamics and contribute to broader applications in network analysis research.

## **References**
[1] Jebabli, Malek, Cherifi, Hocine, Cherifi, Chantal, & Hamouda, Atef. (November 2015). "Overlapping Community Detection Versus Ground-Truth in the Amazon Co-Purchasing Network." A Conference Paper.  
[2] Fu, Erzheng, Zhang, Jiayun, & Chen, Yang. (May 2021). "Understanding the User Interactions on GitHub: A Social Network Perspective." A Conference Paper.  
[3] Rozemberczki, B., Allen, C., & Sarkar, R. (2019). "Multi-scale Attributed Node Embedding." arXiv preprint arXiv:1909.13021.  
[4] Newman, M. (2018). "Oxford University Press."  
[5] Watts, Duncan J., & Strogatz, Steven H. (1998). "Collective dynamics of 'small-world' networks."  
[6] Estrada, Ernesto. (2012). "Complex Networks: An Introduction."  
[7] Hidalgo, Cesar. (2015). "Introduction to Network Science."  
[8] Adamic, Lada A., & Huberman, Bernardo A. (2005). "Link prediction in social networks."

