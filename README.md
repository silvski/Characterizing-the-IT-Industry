# Characterizing the Philippines' IT Industry
This project attempts to characterize the IT industry of the Philippines by analyzing IT related job posts scraped from different websites. The repository contains the notebook detailing the process, visualizations and insights gained. <font color='blue'>The data used in this project will not be made publicly available as the owner did not allow it.</font>

Codes used for scraping other job posting sites (along with the subsequent analysis) will be published on a later date.

## Executive Summary
The IT field is a very wide and fast paced industry with new technologies popping up almost every year. This makes it difficult for fresh graduates and career shifters to develop their skill set, let alone land their dream jobs. Furthermore, each company has their own unique set of job titles which can make it all the more confusing for both applicants and recruiters alike.

This notebook aims to address this problem through the use of topic modelling (LDA). The idea is that job posts can be grouped together according to their required skills and technologies. Thus reconciling the job titles as well as highlighting skills that go together. Results show that LDA was capable of coming up with meaningful groupings (sub-industries) wherein the team was able to identify 8 general clusters. These results can further be used for downstream tasks such as item set mining (to find skill and tech pairings per sub-industry) and semi-supervised learning for classification and sequence to sequence modeling.

## Topic Cluster Sample Visualization

<img src=https://github.com/silvski/Characterizing-the-Philippines-IT-Industry/blob/master/results/3.JPG?raw=true>
