# IMPACT
Artifact for ACM TOSEM Submission: IMPACT

# IMPACT: _I_dentifying and Classifying _M_ulti_p_le Sourced and Categorized Self-_A_dmitted Te_c_hnical Deb_t_s

# I. Introduction
IMPACT is an SATD identification and classification framework. It comprises two main components: 
(1) A ChatGPT-based data augmentation method, which utilizes a multi-turn prompt guiding ChatGPT to generate rephrased SATD texts to expand the data scale and balance the data categories. 
(2) A pipeline with two language models of different parameter sizes to handle the SATD identification and classification tasks separately.

To evaluate the effectiveness of IMPACT, we leverage IMPACT's data augmentation method to construct an augmented dataset and fine-tune the pipeline of IMPACT and five baselines on this augmented dataset to compare their capabilities of SATD classification.
To further explore the generalizability of IMPACT on unseen projects data, we evaluate IMPACT on a newly constructed benchmark.

# II. Project Structure

# III. Environment
Python==3.9

torch==2.4.0

transformers==4.43.3

sentence-transformers==3.0.1

# IV. Usage
The dataset and the benchmark are in the floder 




