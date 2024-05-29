# IEEE-TAI_FedCI_GAT

**Federated Multi-task Learning for Complaint Identification using Graph Attention Network**

Automatic complaint identification is crucial to organizations as they provide insights to meet the customers' requirements, including handling and addressing the complaints. Unlike standard technologies developed using data stored in the cloud, a federated learning model allows businesses to learn complaint detection models without sharing their training data spread on their local databases with third-party cloud services. In this work, we propose a GAT-based sentiment-aided complaint identification in federated learning settings. The proposed FedComb algorithm integrates local and global model optimization, making it efficient compared to existing federated algorithms. 

**Dataset**
We used two datasets for the evaluation of the models:

The Twitter-based \emph{ComplaintS} dataset (https://github.com/danielpreotiuc/complaints-social-media), which includes 1,232 samples of the complaint class and 2,217 samples of the non-complaint class. This dataset has been further categorized into high-level domains to validate the analysis of complaints by domain based on distinct industry types and areas of activity.

The Hinglish language-based \emph{Product Review} dataset (https://github.com/MrRaghav/), which is a collection of product reviews posted on the retail website Amazon India and in the YouTube comment section. This dataset consists of 3,711 data samples, subdivided into multiple domains.

For sentiment label annotation, we utilized a pseudo-labeling approach by generating the sentiment labels using the pre-trained classifier VADER.

**Software**
The resource file consists of the proposed FedComb model and implementation files for other baseline models in both IID and NIID settings.

**Cite**
@article{singh2023federated,
  title={Federated multi-task learning for complaint identification using graph attention network},
  author={Singh, Apoorva and Chandrasekar, Siddarth and Sen, Tanmay and Saha, Sriparna},
  journal={IEEE Transactions on Artificial Intelligence},
  year={2023},
  publisher={IEEE}
}

