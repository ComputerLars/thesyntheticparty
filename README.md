# thesyntheticparty
Repo for _The Synthetic Party (Det Syntetiske Parti)_, made by party secretary _Computer Lars_.

## **Overview**

This GitHub repository accompanies the exposition of ["The Synthetic Party as Techno-Social Sculpture"](https://www.researchcatalogue.net/view/2370287/2370288/731) as submitted to _The Journal of Artistic Research_. It hosts an extensive collection of datasets and theoretical references, emotion and Valence-Arousal-Dominance (VAD) classifications, visualizations, analyses, and supplementary materials used to represent The Synthetic Party of Denmark. The project challenges traditional notions of political representation by leveraging machine learning to interpret and articulate constituency sentiments. The repository of The Synthetic Party's data material should be of interest to those working in the intersection of political theory, artificial intelligence, and artistic research.

**Contents**
- References and Materials
  1. List of literature and theory
  2. Texts from scripts
  3. Videos of scripts
  4. Visual miscellaneous

- Datasets
  1. Clean datasets
  2. Emotion and VAD Classifications
  3. Analysis and Visualizations
  
- Usage
  1. Contributing
  2. License
  3. Contact

## **References and materials**

1. _Literature references_: List of references for theory included in the exposition.
2. _Textual Basis for Scripts__: Detailed written material explaining the concept and operations of The Synthetic Party.
3. _Multimedia Files_: Audiovisual materials used in the exposition, including presentations, videos, and interactive media.
4. _File dump_ of web scraped visual and video material used in the exposition scripts.

## **Datasets**

The datasets included in this repository are comprehensive collections of data pertaining to The Synthetic Party's operation. These datasets include but are not limited to:

- _Historical and Theoretical Data_: Insights into the philosophical and political underpinnings of The Synthetic Party.
- _Training Data_: The data used to train the AI models, including textual data from 200+ Danish micro-parties as found within their founding documents, online deliberations, websites, and media coverage.
- _AI Party Program_: The text-generated party program of The Synthetic Party which is based on the training data. Inferred from the party's publications on [Medium](https://medium.com/@ComputerLars).
- _Online Deliberation Records_: Transcriptions and records of online discussions and deliberations taking place on The Synthetic Party's [Discord](https://discord.com/invite/Hmy6tKf8yf)-server.
- _News Media Coverage_: A curated collection of international media coverage of The Synthetic Party, highlighting its societal impact and public reception.

**Emotion and VAD Classification**

This section contains datasets classified according to various basic emotions and VAD (Valence, Arousal, and Dominance) models. These classifications provide insights into the affective and emotional dimensions of the data, offering an understanding of public sentiment within  discourse. The classification is executed through several models, each lending a perspective on the data:

- _Text2Emotion_: A [PyPi Library](https://pypi.org/project/text2emotion/). Uses a lexical bag-of-words approach to infer six basic emotions from text, such as happiness, sadness, anger, etc.
- _BERT Danish_: [Large language model](https://huggingface.co/alexandrainst/da-emotion-classification-base) fine-tuned on Danish SoMe material, which classifies to eight basic emotions.
- _GPT 3.5_: Large language model that provides the VAD analysis, mapping data onto the valence-arousal-dominance spectrum, and correlates with new emotion classificaiton.

**Analysis and Visualizations**

This section presents a range of analyses performed on the datasets, including:

- _Sentiment Analysis_: Evaluating the emotional content within the political discourse.
- _Thematic Analysis_: Exploring recurrent themes and topics in the data.
- _Comparative Analysis_: Juxtaposing different data sets to uncover underlying patterns and relationships.

A series of visualizations are included to offer interpretative insights into the datasets, including but not limited to:

- _Sentiment Bars_: Illustrating the shifts in public sentiment.
- _Emotion Bar Graphs_: Visualizing the emotional spectre of various datasets.
- _VAD Cubes_: Displaying the distribution of data across the valence-arousal-dominance spectrum.
- _Network Diagrams_: Showing the interconnections between different elements within the datasets.
- _Keywords maps_: Showing themes and topical debates

These are all created by **Matplotlib**, where:
- 1. The _matplotlib.pyplot.bar_ function creates the bar graphs illustrating the categorical aspect of emotions.
- 2. The _mpl_toolkits.mplot3d_ toolkit is utilized for dimensional representation to generate 3D cubes depicting valence, arousal, and dominance.

## **Usage**

This repository is intended for researchers, political theorists, data scientists, and artists interested in the intersection of AI, democracy, and art. To use the datasets and materials:

_Clone the Repository_: Use Git or checkout with SVN using the web URL: git clone https://github.com/YourRepository/thesyntheticparty.git
_Explore the Contents_: Navigate through the directories to find datasets, visualizations, and analyses.
_Read the Documentation_: Each dataset and visualization is accompanied by comprehensive documentation explaining its context and usage.

**Contributing**

Contributions to this project are welcome. To contribute:

  1. Fork the Repository_
  2. Create your Feature Branch (git checkout -b feature/YourFeature)
  3. Commit your Changes (git commit -m 'Add some YourFeature')
  4. Push to the Branch (git push origin feature/YourFeature)
  5. Open a Pull Request

**License**

This project is licensed under the [Creative Commons](https://github.com/askerbryld/thesyntheticparty/blob/main/LICENSE) - see the LICENSE.md file for details.

## **Contact**

For inquiries related to The Synthetic Party, please contact artist-researcher [Asker Bryld Staunæs](mailto:abs@cc.au.dk) or party secretary [Computer Lars](mailto:computerlars@mindfuture.com).

1. [Research Profile: Asker Bryld Staunæs](https://pure.au.dk/portal/da/persons/abs%40cc.au.dk)

2. [Blog: Computer Lars](https://computerlars.com)

3. [Official website: The Synthetic Party](https://detsyntetiskeparti.org)


