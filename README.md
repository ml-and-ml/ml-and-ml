# Hassan Muhammad
I'm a writer and computational cancer scientist with expertise in computer vision, machine learning, and big data. I leverage computational pathology to better understand the biological mechanisms which inform disease prognosis. I encourage you to test the models below on your own datasets or expand upon them with your own creativity! Feel free to contact me for implementation assistance.

You can find a complete list of my publications on [Google Scholar](https://scholar.google.com/citations?user=yc8l1kcAAAAJ&hl=en).


<img align="left" alt="Python" width="26px" src="https://raw.githubusercontent.com/jmnote/z-icons/master/svg/python.svg" />
<img align="left" alt="PyTorch" height="26px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/PyTorch_logo_icon.svg/512px-PyTorch_logo_icon.svg.png" />
<img align="left" alt="R" height="26px" src="https://raw.githubusercontent.com/jmnote/z-icons/master/svg/r.svg" />
<img align="left" alt="Terminal" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" />
<img align="left" alt="LaTeX" width="26px" src="https://upload.wikimedia.org/wikipedia/commons/9/95/TeXShop_icon.png" />


<br />
<br />



## 🔬💻 Selected Computational Pathology Projects

### ◼️ End-to-End Survival Modelling for Whole Slide Images | [[Paper]](https://2021.midl.io/proceedings/muhammad21.pdf) [[Code]](https://github.com/ml-and-ml/EPIC-Survival)
Due to hardware limitations and because of the massive size of a whole slide image (WSI), survival modelling on WSI datasets is typically done using a two-stage approach: encoding and aggregation. First, a model is trained on WSI tiles or patches, and then a second method is used to aggregate information generated from the output of the first stage to output a final prediction. EPIC-Survival bridges encoding and aggregation into an end-to-end survival modelling approach, while introducing a new loss term, _stratification boosting_, to encourage the model also to discriminate between risk groups for subtyping.

### ◼️ Deep Clustering using a Convolutional Autoencoder | [[Paper]](https://link.springer.com/content/pdf/10.1007%2F978-3-030-32239-7_67.pdf) [[Code]](https://github.com/ml-and-ml/Deep-Clustering-Convolutional-Autoencoder)
Before the rise of self-supervised learning, convolutional autoencoders were the standard for converting WSIs into low-dimensional feature vectors. However, a simple MSE-loss does not encourage the model to group together similar features in the embedding space. This model combines a clustering loss with MSE. When applied to WSIs, each cluster produced within the embedding space can be interpretted as a morpholical feature of histology phenotypes across a dataset. These features can then be used as covariates in downstream prognostic modelling tasks with success.

## 📃✒️ Selected Writing
* [A Mental Health Crisis Among Graduate Students: Uncovering the Root Cause](https://regenerationmag.org/a-mental-health-crisis-among-graduate-students/)

* [Humans Have Struggled to Understand Rare Cancers, Let’s Give Artificial Intelligence a Turn.](https://towardsdatascience.com/humans-have-struggled-to-understand-rare-cancers-lets-give-artificial-intelligence-a-turn-d9b180b29805?sk=024ab6b557a43bd4c1909e1b4d43a042)

