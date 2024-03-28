This repository shows codes and the files that were used to derive results of the thesis. 

Files Chapter 3 (Data Selection):
* 'AllInOneCSV' (Excel CSV) that shows all scraped news from newsrooms of companies suggested by literature
* Finding_Announcements_with_keywords' (Python Code File) for keeping news that contain partnership relevant keywords
* 'Clustering AV company descriptions' (Python Code File) for recreating the clustering on basis of company descriptions


Files Chapter 4 (Result gathering):
* 'Manual Labeling' (Excel File) showing manual labels into typology of Barnes et al.
* 231203_CB_selected descriptions (Excel File) for collecting data on all companies mentioned from Crunchbase
* 'Spearman Correlation' (Python Code) for efficiently calculating five correlations: one for each use case, and a correlation where all companies and their announcement labelings are correlated jointly
* 'DualCircular' (Gephi file) that shows visually the partnering companies per use case (visualizing answer to the WHO question)
* 'Announcement Network by purpose' (Gephi file) showing visually the partnering companies and the type of purpose (i.e. reason) and structure (commitment level of partnership) per partnership
* 'LDA model for 179 titles' (Python Code) for preprocessing and running LDA model on 179 keyword matching news articles
* 'lda_visualization_t=5' (HTML file that shows the pyvis visualization for making sense of the LDA at t=5). The final LDA model, that has the best perplexity / coherence and human judgement scores
  
Abstract: 
This thesis investigates 179 announcements of 39 predefined companies from shared autonomous vehicles (SAV), and autonomous transport vehicles (ATV) with respect to the involved companies, and motives for partnering up. Studying partnerships is getting more relevant due to increasing specialization of companies within their respective value chain segments (components of the final product) making vertical integration within autonomous mobility business chains more inefficient. Simultaneously high transaction costs, production costs and unsafe returns in uncertain businesses, favor partnerships as a middle ground to gain access to complementary resources instead of traditional purchase agreements.
Answers on who the companies are, will be provided in terms of industry and layer membership. Answers on why companies enter agreements will be given in terms of announcement structures, and their purposes, as labeled manually into typologies suggested by alliance research. Attempts to offer standardized labels through LDA with a ideal topic size of 13 topics, turned out to be too ambiguous for reliable analysis. 
To offer more general descriptive insights into what type of companies enter partnerships, company metrics like funding, headcount and public status are correlated with the manually labeled partnership variables.
The correlation analysis revealed that highly funded and staffed companies are generally observed with lower partnership frequencies, consistent with resource based view arguing that partnerships are especially relevant to small companies for gaining complementary resources. Also correlations revealed that public companies co-occur with higher count of customer relevant partnerships, which is consistent with some findings on motives of public companies to report customer orientation. 
A lower product orientation of ATV companies and higher focus on partnerships with customers (grocery stores and restaurants) argues for a high (product) self-sufficiency of LM companies. Also from observing that RP and LM companies tend to engage in short-term partnerships, the study provides reasons to hypothesize and study in future research if the RP and LM industry are less advanced and mature compared to Ridehailing and trucking respectively which show highest level of committed partnerships involving equity. 
The contribution of the thesis is to broaden the literature on SAV and ATV beyond traditionally high technology and behavioral orientation and work for a better understanding of with whom, and for what reasons companies organize their business processes through partnerships. Also, the contribution are two landscape visualizations of the AV industry. First, through network visualization of all 179 announcements with gephi. This also revealed that off the 39 companies under review, 17 companies were forming a more dense cluster, connected either through shared partner companies or relationships between scope companies. Secondly, through clustering company descriptions of 2400 AD companies with BERtopic, claiming to belong to the AD industry it was shown that AD is becoming a buzzword, that comes with a risk of companies falsely proclaiming to be AD relevant. 
