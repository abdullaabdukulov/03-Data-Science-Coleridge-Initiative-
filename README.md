# 03-Data-Science-Coleridge-Initiative

<div class="row">
<div class="col tab-content">
<div class="tab-pane active show" id="subject" role="tabpanel">
<div class="row">
<div class="col-md-12 col-xl-12">
<div class="markdown-body">
<p class="text-muted m-b-15">
</p><h2>Coleridge Initiative</h2>
<table>
<thead>
<tr>
<th>Technical details</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td>Submit files</td>
<td>dataset_analysis.ipynb - presentation.txt - coleridge_initiative_model.ipynb</td>
</tr>
<tr>
<td>Languages</td>
<td>It needs to be completed in the language you are working on right now. If you are doing Bootcamp Javascript, then javascript (file extension will be .js). If you are doing Bootcamp Ruby, then Ruby (file extension will be .rb). It goes the same for Python, Java, C++, Rust, ...</td>
</tr>
</tbody>
</table>
<hr>
<img src="https://storage.googleapis.com/qwasar-public/track-ds/Business_application.png" width="500px">
<p>NLP-based Automated Dataset Discovery in Scientific Publications
The primary objective of this project is to utilize Natural Language Processing (NLP) and deep learning to uncover how scientific datasets are referenced in a range of academic articles. This project will explore three different models: two Recurrent Neural Networks (RNNs), specifically Bidirectional Long Short-Term Memory (BiLSTM) and Gated Recurrent Unit (GRU), and one Convolutional Neural Network (CNN), specifically sep-CNN.</p>
<h2>Data Source</h2>
<p>The project leverages data from the Kaggle competition named "Coleridge Initiative". The purpose of this competition is to uncover how public data is being used in the scientific community and provide insight for governments to make more informed and transparent public investments. The competition also aims to automate the process of identifying what datasets are used in problem-solving, the metrics generated, and the leading researchers in the field.</p>
<p>The dataset consists of the full text of scientific articles from various research domains, sourced from CHORUS publisher members and other venues. The task is to identify the datasets that the authors of these publications have utilized in their work.</p>
<h2>Methodology</h2>
<p>The focus of this project is not just to detect known dataset strings but to generalize the capability to identify new, unseen datasets. To achieve this, a multi-faceted approach will be used:</p>
<ul>
<li>N-gram models: To identify patterns and correlations in word sequences in scientific texts.</li>
<li>RNN Models: Implementation of two RNN models, Bidirectional LSTM and GRU, to capture sequential information in the text and classify them appropriately.</li>
<li>CNN Model: Deployment of a sep-CNN model to identify localized features in the text which could indicate a dataset mention.</li>
<li>spaCy NER: Use of the Named Entity Recognition (NER) feature in spaCy to tag and identify dataset mentions as named entities.</li>
</ul>
<p>It should be noted that this project does not provide a solution for the Kaggle competition but rather serves as an exploration of different NLP and deep learning methodologies for text processing and sequence labeling in the context of scientific articles. This project will provide insights into how to process raw text data, identify relevant scientific articles, and classify them with predefined labels.</p>
<h2>Expected Outcome</h2>
<p>By the end of this project, we expect to demonstrate the effectiveness of NLP and deep learning techniques in automating the process of dataset identification in scientific texts. We also aim to uncover which of the applied models is the most effective in generalizing and identifying new, unseen datasets. The findings will contribute to the body of knowledge in the field and provide valuable insights for future research and applications.</p>
<h2>Deliverables</h2>
<p>We would like you to complete the following:</p>
<ul>
<li>An analysis of the dataset.</li>
<li>A prediction model. (jupyter notebook)</li>
<li>A presentation reports comparing the model's performance against traditional traffic prediction methods.</li>
</ul>

<p></p>
</div>

</div>
</div>
</div>
<div class="tab-pane" id="resources" role="tabpanel">
</div>
</div>
</div>
