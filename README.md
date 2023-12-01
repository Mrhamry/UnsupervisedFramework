
# Redefining Privacy Policy Summarisation: A Contextualised Sentence Embedding Approach

In this project, we suggest the use of an unsupervised approach to identify the privacy practices in privacy policies. We developed a framework utilizing state-of-the-art AI models along with other processing methods.

Overview of our proposed framework
![Framework Overview](https://github.com/Mrhamry/UnsupervisedFramework/assets/31767656/14b1dd88-7383-4185-8636-281d2cc33869)


We introduce **Policy-Oriented BERT**, a privacy policy-specific BERT model that is pre-trained from scratch on a large corpus containing over 451K privacy policy documents.

**Resources:**
- **Policy-Oriented BERT (Pytorch)(Weights):** Download from [here](https://livewarwickac-my.sharepoint.com/:u:/g/personal/u1490553_live_warwick_ac_uk/ES2bD0dh6f5Cra65oNMbZMQBvPqP3J4XAY4Yx_fBU0Kc4Q?e=joJVjY).

  <!--- - **451K Privacy Policy Corpus:** Used for pretraining our custom Policy-Oriented BERT, downloadable from [here](insert-link).              -->

As stated in our paper, we implemented MEAN-strategy pooling with the Policy-Oriented BERT model to produce superior results when generating sentence embeddings.

**Resources:**
- **One Million privacy policy sentences (Pickles):** Available [here](https://livewarwickac-my.sharepoint.com/:u:/g/personal/u1490553_live_warwick_ac_uk/Ee4i-7Q1GJ9JrWssCkHafGgBDZWi3xvCnHxX2cnxx_ev1g?e=BNGLwf).
- **Extracted Sentence Embeddings (Pickles):** Downloadable from [here](https://livewarwickac-my.sharepoint.com/:u:/g/personal/u1490553_live_warwick_ac_uk/ETR1hz0PTQ5JqvjY_LxMrJABfXt1m9mrZdFm6wfkawXOJA?e=lYc6li).
- **Clustered sentences:** Available [here](https://livewarwickac-my.sharepoint.com/:u:/g/personal/u1490553_live_warwick_ac_uk/Ed1u9ofbwT9GkCXdf_kSrmcBjr2DXHFXZq9ZmaV5vIMxHg?e=6hN08Y).

 Additionally, our framework has enabled us to produce a privacy practice corpus, which can be beneficial in training supervised models.

**Resources:**

- **Privacy Practice Corpus (Pickles):** Downloadable from [here](https://livewarwickac-my.sharepoint.com/:u:/g/personal/u1490553_live_warwick_ac_uk/ERAuTvIKVWtKkYcs33pWnv0BPy3IrqDY43s06Rmu3oKLJQ?e=06bWVy).
