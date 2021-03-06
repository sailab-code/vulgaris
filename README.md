# Vulgaris
Project to analyze Italian Diachronic Language Varieties.

Have a look at the project page - [Vulgaris for more details](https://sailab.diism.unisi.it/vulgaris/).

[Technical report here](https://arxiv.org/abs/2010.05993) - accepted at [VarDial2020](https://sites.google.com/view/vardial2020/home) Workshop, co-located with [COLING 2020](https://coling2020.org/).

## Cite

```
@inproceedings{zugarini2020vulgaris,
  title={Vulgaris: Analysis of a Corpus for Middle-Age Varieties of Italian Language},
  author={Zugarini, Andrea and Tiezzi, Matteo and Maggini, Marco},
  booktitle={Proceedings of the 7th Workshop on NLP for Similar Languages, Varieties and Dialects},
  pages={150--159},
  year={2020}
}
```

## Download Script



*Disclaimer:* we retrieved and analyzed the data from Biblioteca Italiana solely for personal and academic non-commercial purposes.
To replicate our analyzes and ease the diachronic language research,
we provide the following script that retrieves and organizes the corpus in a convenient structure.


To install all the required dependencies:

```
pip install -r download_requirements.txt
```
Then, run the script:

```
python vulgaris_project.py
```

By running that script, you declare to respect the following copyright of Biblioteca Italiana:
[Creative Common License](http://creativecommons.org/licenses/by-nc-nd/2.0/it/)
[![Creative Commons](https://i.creativecommons.org/l/by-nc-nd/2.0/it/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/2.0/it/)

## Perplexity-based Analysis
First you should retrieve the data.

```
python char_diachronic_lm_exp.py path/to/vulgaris.csv
```