![FEVER logo](images/Logo_blue.png)

# Fact Extraction and VERification

This is the main repository for the dataset and experiments presented in our NAACL2018 paper: [FEVER: A large-scale dataset for Fact Extraction and VERification.](https://arxiv.org/abs/1803.05355)

> Unlike other tasks and despite recent interest, research in textual claim verification has been hindered by the lack of large-scale manually annotated datasets. In this paper we introduce a new publicly available dataset for verification against textual sources, FEVER: Fact Extraction and VERification. It consists of 185,441 claims generated by altering sentences extracted from Wikipedia and subsequently verified without knowledge of the sentence they were derived from. The claims are classified as Supported, Refuted or NotEnoughInfo by annotators achieving 0.6841 in Fleiss κ. For the first two classes, the annotators also recorded the sentence(s) forming the necessary evidence for their judgment. To characterize the challenge of the dataset presented, we develop a pipeline approach using both baseline and state-of-the-art components and compare it to suitably designed oracles. The best accuracy we achieve on labeling a claim accompanied by the correct evidence is 31.87%, while if we ignore the evidence we achieve 50.91%. Thus we believe that FEVER is a challenging testbed that will help stimulate progress on claim verification against textual sources

This repository contains the baseline experiments, the scorer as submodules as well as the code used to generate and prepare the dataset.


## Get Started

```
git clone https://github.com/awslabs/fever.git
cd fever
git submodule init
git submodule update
```


## Download the Data

Visit [http://fever.ai](http://fever.ai) to download the data and find out more about the shared task. 
    


## Run the Code

 * [Baseline Experiments](https://github.com/sheffieldnlp/fever-baselines)
 * [Scorer](https://github.com/sheffieldnlp/fever-scorer)
 * [Dataset Preparation](fever-annotations-platform/)

    
