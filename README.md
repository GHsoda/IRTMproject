# IRTMproject
# # file list
- **preprocessing.ipynb** contains the data extraction, and NLTK entity extraction effort.
- **NER_proj.ipynb contains** the code that uses BERT and FlairNLP for the NER tasks.
- **entities_from_BERT.pkl** is the entity extraction from BERT model.
- **entities_from_FlairNLP.json** is the entity list extracted from FlairNLP. I renamed it for easier recognization.
- **json_process.ipynb** contains the code that refine the entity list and save them in a json file for further use.
- **entities_for_streamgraph.json** is processed based on entities_from_FlairNLP.json, generated by json_process.ipynb. I renamed it for easier recognization.
- **streamgraph.ipynb** contains the code that generated the final version of the stream graph.
- **area_chart.html** is the stream graph generated from streamgraph.ipynb.
- **BERTopic.ipynb** contains the code that use BERTopic and LDA.
- **lda_topic_16_visualization.html** is the topic modeling graph generated from BERTopic.ipynb
