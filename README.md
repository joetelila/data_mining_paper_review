# Paper review
I will  be presenting a paper entitled "[A data mining-based framework for the identification of daily electricity
usage patterns and anomaly detection in building electricity
consumption data](https://www.sciencedirect.com/science/article/abs/pii/S0378778820333879)" Liu et al. 

# Abstract [copied from the paper]

> With the development of advanced information techniques, smart energy meters have made a considerable amount of real-time electricityconsumption data available. These data provide a promising way to understand energy usage patterns and improve building energy management. However, previous studies have paid more attention to methodologies for the identification of energy usage patterns and are limited
in the interpretability and applications of the patterns. In this context, this paper proposes a general data
mining-based framework that can extract typical electricity load patterns (TELPs) and discover insightful
information hidden in the patterns. The framework integrates multiple data mining techniques and
mainly consists of three phases: data preparation, identification of TELPs and knowledge discovery in
the patterns. A new clustering method with a two-step clustering analysis is proposed to identify the
TELPs at the individual building level. Before clustering, five statistical features that represent the shapes
of electricity load profiles are first defined to reduce the dimensions of daily electricity load profiles. The
first clustering step aims at detecting outliers of daily electricity load profiles (DELPs) by using the
density-based spatial clustering application with noise (DBSCAN) algorithm clustering technique, which
addresses the data quality issues for electricity consumption data derived from energy consumption
monitoring platforms (ECMPs). The second clustering step aims at grouping similar DELPs by means of
the k-means algorithm to extract TELPs. The effectiveness of the proposed clustering method is demonstrated by a comparison with two single-step clustering techniques. Furthermore, a classification and
regression tree (CART) algorithm is employed to discover insightful knowledge on TELPs and improve
the interpretability of clustering results, namely, to explain the relations between dynamic influencing
factors related to electricity consumption and TELPs. The proposed framework is applied to analyze
the time-series electricity consumption data of three practical office buildings in Chongqing, and its effectiveness has been confirmed. A potential application of discovered knowledge is presented: early fault
detection of anomalous electricity load profiles. The proposed framework can provide building managers
with an efficient way to understand the characteristics of building electricity usage patterns and detect
anomalies therein.

