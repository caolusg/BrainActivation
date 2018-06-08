# Predicting Brain Activation with WordNet Embeddings

The task of taking a semantic representation of a noun and predicting the brain activity triggered by it in terms of fMRI spatial patterns was pioneered by *Mitchell et al.*.
That seminal work used word co-occurrence features to represent the meaning of the nouns. Even though the task does not impose any specific type of semantic representation, the vast majority of subsequent approaches resort to feature-based models or to semantic spaces (aka word embeddings).
We address this task, with competitive results, by using instead a semantic network to encode lexical semantics, thus providing further evidence for the cognitive plausibility of this approach to model lexical meaning.

**Article**

*João Rodrigues, Ruben Branco, João Silva and António Branco, 2018, [Predicting Brain Activation with WordNet Embeddings](https://sites.google.com/view/cognitivews2018/accepted-papers), To appear in ACL 2018 Workshop on Cognitive Aspects of Computational Language Learning and Processing*

**Semantic network (wnet2vec)**

The wnet2vec model referred in the article is available for [download](http://lxcenter.di.fc.ul.pt/wnet2vec_brain.tar.gz).
The model was obtained resorting to 60,000 words using Princeton WordNet 3.0, the training of the model is described in *Chakaveh Saedi, António Branco, João Rodrigues and João Silva, 2018, [Wordnet embeddings](https://sites.google.com/site/repl4nlp2018/accepted-papers), In Proceedings of the ACL2018 3rd Workshop on Representation Learning for Natural Language Processing (RepL4NLP)*. 

**Evaluation and scripts**

The [evaluation folder](https://github.com/nlx-group/Semantic-Brain-Activation/tree/master/evaluations) contains the log files for the wnet2vec model (Table 1).

The [scripts folder](https://github.com/nlx-group/Semantic-Brain-Activation/tree/master/scripts) contains the plotting scripts of the fMRI activation patterns (Figure 1). 

The Mitchell et al. model is described in *Tom M. Mitchell, Svetlana V. Shinkareva, Andrew Carlson, Kai-Min Chang, Vicente L. Malave, Robert A. Mason and Marcel Adam Just, 2008, Predicting human brain activity associated with the meanings of nouns, Science, 320(5880):1191-1195*.

The training system is provided at the [Samira Abnar repository](https://github.com/samiraabnar/NeuroSemantics/) and described in *Abnar, Samira, Rasyan Ahmed, Max Mijnheer and Willem Zuidema, 2018, Experiential, distributional and dependency-based word embeddings have complementary roles in decoding brain activity, In Proceedings of the 8th Workshop on Cognitive Modeling and Computational Linguistics (CMCL 2018)*.

![Table with evaluation of model](https://github.com/nlx-group/Semantic-Brain-Activation/blob/master/fmri_table.png)

