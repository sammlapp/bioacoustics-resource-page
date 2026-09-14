# **Bioacoustics & Passive Acoustic Monitoring (PAM) Resources**

A curated list of software (e.g., Dipper, OpenSoundscape, BirdNET, Chirpity, etc), machine learning classifiers (e.g. BirdNET, HawkEars, Perch), datasets, ARU hardware guides (e.g. AudioMoth), courses, and community forums for bioacoustics and passive acoustic monitoring (PAM) research — curated by [Sam Lapp](https://samlapp.com) and the [Kitzes Lab](https://kitzeslab.org).

hint: bookmark this page :) 

contributing: email Sam or open an issue or PR on [GitHub](https://github.com/sammlapp/bioacoustics-resource-page)

### **Desktop PAM Analysis Software**
* [Dipper](https://github.com/sammlapp/dipper): a desktop app for applying classifiers and rapidly verifying detections
* [HawkEars GUI](https://github.com/jhuus/HawkEars/blob/main/GUI.md): a desktop app for running the HawkEars North American regional classifier and reviewing detections
* [Chirpity](https://chirpity.net/): a desktop app for analyzing recordings with BirdNET or nocturnal flight calls and reviewing detections
* [BirdNET Analyzer](https://birdnet.cornell.edu/analyzer/): a desktop app for analyzing recordings with BirdNET, developing custom classifiers, extracting embeddings, and reviewing detections
* [Raven Intelligence](https://www.ravensoundsoftware.com/software/raven-workbench/raven-intelligence/): a new desktop app under development by Cornell for applying classifiers

### **Bioacoustics workshops & guides**

* [Bioacoustics Classifier Bootcamp: Course Materials](https://docs.google.com/document/d/1snKiwX0t5NyBaN5WaBC9u89V52JBKmDsGa6hjnGc1_o/edit?tab=t.lypwr6ml9wvo)  
  * 10-week course on developing machine learning classifiers for PAM  
  * resources, assignments, and links to slides, recordings, and summaries  
* [Classifiers 101 guide](https://opensoundscape.org/en/latest/classifier_guide/guide.html) \- machine learning classification for bioacoustics, for beginners  
* [GitHub \- leabouffaut/bioacoustics](https://github.com/leabouffaut/bioacoustics_python) Helpful code examples for bioacoustics in Python  
* [Bioacoustic Cookbook](https://github.com/kitzeslab/bioacoustics-cookbook): example scripts, notebooks, and templates for common tasks  
* Conference workshops on Passive Acoustic Monitoring  
  * [ESA 2023 - Bioacoustic Monitoring Workshop](https://docs.google.com/presentation/d/1pXRd1GXL2KUsdj4D115wQOH-9mP2mSV2QW5tyeqC1TQ/edit#slide=id.p)  
  * [ESA 2024 - Automated Bioacoustic Surveys 1: Recorder preparation, field deployments, and introductory analysis and inference](https://docs.google.com/presentation/d/1wGuI42jwjS7b09Y9DhiuQO8C2mi-Rgi2syfyj4w7h08/edit#slide=id.g2ecb6126971_0_5)  
  * [ESA 2024 - Automated Bioacoustic Surveys 2: Machine learning classifiers, advanced statistics, and sound source localization](https://docs.google.com/presentation/d/1621aSKsDpa4VbcE7GmttRSzd0MckWxsygUtMn7pr7jM/edit#slide=id.p)  
  * [AOS workshop - advanced bioacoustic monitoring](https://docs.google.com/presentation/d/1DuiX-_93NAdF6wAHABdWKtvaY0f77Y2u-mchChMpC-0/edit?usp=sharing)  
    * associated [resources, notebooks, q\&a](https://bit.ly/aos-pam-workshop) google doc

### **Other bioacoustics educational materials**

* [BioacousTalks](https://www.birds.cornell.edu/ccb/bioacoustalks/) \- biweekly lectures by bioacoustics researchers (recordings on YouTube\!)  
* [Lecture series from Computer Vision for Ecology](https://www.youtube.com/@cv4ecology/playlists) workshop \- YouTube  
  * [Computer Vision 4 Ecology: Glossary](https://docs.google.com/document/d/1ye7i-34_NcFhtOVKAeN7HFcZAAk5EoTcc1JvoDX-TRA/edit#heading=h.wkgjy1b6yx3a)   
  * [AI Coding for Effective Science](https://docs.google.com/document/d/10He_kR8JPwrqs8j_qQz2e9b8_nzsipipsEavVCXh3rk/edit?tab=t.0#heading=h.g9pud4cxllo2)  
* [Review paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC8944344/) on computational bioacoustics with deep learning by Dan Stowell  
* [Kaggle](https://www.google.com/search?q=kaggle+birdclef&rlz=1C5GCCM_en&oq=kaggle+birdclef&gs_lcrp=EgZjaHJvbWUyBggAEEUYOdIBCDgxNTVqMGoxqAIAsAIA&sourceid=chrome&ie=UTF-8) \- examples of how people solved ML bioacoustics tasks (e.g. blog posts)

  ### **General data science lessons**

* [Data science & computing cheat sheet](https://docs.google.com/document/d/1YbOYnDZpRu6Jo1mpfg8m_zGeyY34NGECyxk2rNkH5eo/edit?tab=t.0) \- an informal guide to the “hidden curriculum” of tools needed to do computational ecology, plus our favorite commands   
* [Data Science Lessons](http://datasci.kitzes.com/) – materials for two-day introductory data science workshops  
  * see in particular the \~2-hour self-paced [tutorial on git and GitHub](http://datasci.kitzes.com/lessons/git/)  
* [Software Carpentry lessons](https://software-carpentry.org/lessons/) – introductory tutorials on computing and data science  
* [The Practice of Reproducible Research](http://www.practicereproducibleresearch.org/) – online version of book edited by Justin Kitzes on reproducibility, see in particular the [Basic Reproducible Workflow Template](http://www.practicereproducibleresearch.org/core-chapters/3-basic.html) chapter

  ### **Data and Software Compilations**

* [Github Bioacoustics datasets list](https://bioacoustic-ai.github.io/bioacoustics-datasets/) (open-source, the most complete list)  
  * Spreadsheet of [annotated bird sound datasets](https://docs.google.com/spreadsheets/d/1KrmCB0vvSK7V3znJfycO-eOMZJKP2F-Ih6neRYPz1Xc/edit#gid=0)  
  * Another list of [annotated bioacoustics datasets](https://lila.science/otherdatasets#bioacoustics) from [Lila.bc](http://Lila.bc)  
* Benchmark datasets (for comparing machine learning model performance):
  * [WABAD](https://zenodo.org/records/14191524) worldwide annotated PAM dataset collection
  * [BEANS](https://github.com/earthspecies/beans) detection and classification benchmark  
  * [BirdSET](https://github.com/DBD-research-group/BirdSet) bird classification benchmark
* [Bioacoustics software list](https://github.com/rhine3/bioacoustics-software): current software for a wide variety of bioacoustics tasks


### **Community Forums**

* [WILDLABS.net](https://wildlabs.net/) – large online community with ecology/conservation tech discussions, including an [acoustics-specific group](https://wildlabs.net/groups/acoustics)  
* [Bioacoustics Stack Exchange](https://bioacoustics.stackexchange.com/) \- Q\&A with the bioacoustics community  
* AI for Conservation Slack \- an active and welcoming community. To join, email [aiforconservation@gmail.com](mailto:aiforconservation@gmail.com)  
* [Bioacoustics feed](https://bsky.app/profile/daryllmarie.bsky.social/feed/aaaivfksmfg3o) on Bluesky

### **OpenSoundscape**
  The Kitzes lab’s open-source package for bioacoustic analysis

* [Documentation and tutorials](https://opensoundscape.org)  
* [Classifiers 101 guide](https://opensoundscape.org/en/latest/classifier_guide/guide.html)  
* [GitHub](https://github.com/kitzeslab/opensoundscape) open-source code base  
* [Bioacoustic Cookbook](https://github.com/kitzeslab/bioacoustics-cookbook): example scripts, notebooks, and templates for common tasks  
* [Bioacoustics Model Zoo](https://github.com/kitzeslab/bioacoustics-model-zoo): pretrained ML models compatible with OpenSoundscape  
* [Google Colab](https://colab.research.google.com/): run Python notebooks on the cloud  

#### **Examples: real-world applications of OpenSoundscape** 

* [Underwater vocalizations of the endangered Sierra Nevada Yellow-legged frog](https://github.com/kitzeslab/rana-sierrae-cnn)   
* [Canada Warbler breeding habitat use](https://onlinelibrary.wiley.com/doi/full/10.1002/wll2.12052)   
* [Predictors of Great Horned Owl habitat use and successful reproduction](https://nsojournals.onlinelibrary.wiley.com/doi/full/10.1111/ecog.06940)  
* [Eastern whip-poor-will occupancy across forest management regimes](https://www.sciencedirect.com/science/article/pii/S0301479724017729?casa_token=7vqaXrY2uEoAAAAA:1tvk54oV3LBLZqlzHEKIeT-h-3LlaJwWEgmcaagw8k-ayDMmEJIg1I-OgaAhdhO7Z2qSwX9px1t8%20)   
* [Evaluating unmarked abundance models with machine-learning classification of PAM data](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1002/ecs2.4954)  
* [Detecting Ruffed Grouse drumming](https://github.com/kitzeslab/ruffed_grouse_manuscript_2022)  
* [RIBBIT: a method for detecting calls with repeated elements](https://github.com/kitzeslab/ribbit_manuscript_notebooks)   
* [Automated detection of gunshots in tropical forests using convolutional neural networks](https://www.sciencedirect.com/science/article/pii/S1470160X22006008)


### **Field deployment guidelines**

* [Terrestrial ABMI Autonomous Recording Unit (ARU) and Remote Camera Trap Protocols](https://abmi.ca/publication/565.html)	  
* [a2o \- deployment manual for solar powered acoustic sensors](https://acousticobservatory.org/wp-content/uploads/2019/06/a2o_deployment-manual_052019_v25.pdf)  
* [Passive acoustic monitoring in ecology and conservation](https://www.wwf.org.uk/sites/default/files/2019-04/Acousticmonitoring-WWF-guidelines.pdf) (WWF)

### **ARUs and other hardware**

* [AudioMoth guide](https://github.com/rhine3/audiomoth-guide): detailed guide for all steps of preparing and deploying AudioMoth recorders for acoustic monitoring, written by Tessa Rhinehart in our lab (Open Acoustic Devices now has a shorter guide based on this material on their website)  
* [AudioMoth and Song Meter Micro Battery Testing](https://github.com/kitzeslab/ARU_battery_longevity) – information on the expected battery life of these two recorders for a variety of sample rates, gain settings, device temperatures, and battery types, written by Nick Stahlman in our lab  
* [AudioMoth Performance Testing](https://github.com/kitzeslab/audiomoth-performance/blob/main/report.md) – information on the acoustic performance of AudioMoth recorders in different orientations and housing options, written by Sam Lapp in our lab  
* [Open Acoustic Devices](https://www.openacousticdevices.info/) : maker of the AudioMoth field recorder   
  * AudioMoth info page \- [AudioMoth | Open Acoustic Devices](https://www.openacousticdevices.info/audiomoth)   
  * [Open Acoustic Devices GroupGets page](https://groupgets.com/manufacturers/open-acoustic-devices/products/audiomoth): group purchases for AudioMoths are posted regularly; recent component shortages mean they are harder to get  
  * see also the [Hill et al 2018](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12955) paper  
  * [AudioMoth configuration and flash apps](https://www.openacousticdevices.info/applications)  
* [GitHub for Raspberry Pi SD card aggregators (Swallows)](https://github.com/kitzeslab/swallow)

### **Annotation**
* [Dipper](https://github.com/sammlapp/dipper): a desktop app for rapid clip verification
* [Audacity](https://www.audacityteam.org/download/): a desktop program for listening to audio data and viewing spectrograms  
* [Kitzes Lab’s Annotation Guide](https://docs.google.com/document/d/14WmQz3oBJUPTkPq2Q9BPToQ1F97wUqn_XCTNwrE7mRU/edit#heading=h.nlo85n1esrhc) step-by-step guide for annotating audio in Raven Pro/Lite  
* [Raven Pro](https://ravensoundsoftware.com/software/raven-pro/) subscription-based annotation software   
* [Raven Lite](https://ravensoundsoftware.com/software/raven-lite/) free version of Raven Pro but with somewhat limited functionality,  
  * e.g., can only use one free text entry column for annotations in an annotation table  
* [Whombat](https://github.com/mbsantiago/whombat?tab=readme-ov-file) an open-source annotation tool currently under development

### **Classification / Analysis packages**

* [Classifiers 101 guide](https://opensoundscape.org/en/latest/classifier_guide/guide.html): step-by-step guide on developing machine learning recognizers for biological sounds  
* [OpenSoundscape](http://opensoundscape.org/): our lab’s Python package for bioacoustic analyses and recognizer development  
* [Bioacoustics Model Zoo](https://github.com/kitzeslab/bioacoustics-model-zoo): suite of pretrained ML models compatible with OpenSoundscape  
* [Batdetect2](https://github.com/macaodha/batdetect2/tree/main/batdetect2): bat detection and classification toolkit  
* [Koogu](https://github.com/shyamblast/Koogu/tree/master/koogu/model): toolkit for training bioacoustic classifiers with PyTorch  
* [BirdNET](https://github.com/kahst/BirdNET-Analyzer): global bird classification model by the Cornell Lab of Ornithology  
* [Perch](https://www.kaggle.com/models/google/bird-vocalization-classifier): Google global bird vocalization classifier; see variants for [coral reefs](https://www.kaggle.com/models/google/surfperch) and [whales](https://research.google/blog/whistles-songs-boings-and-biotwangs-recognizing-whale-vocalizations-with-ai/)  
* [Kaleidoscope Pro](https://www.wildlifeacoustics.com/products/kaleidoscope): pre-trained classifier for bats; other classification methods available. Pricey/paid software  
* [https://github.com/kitzeslab/r-ribbit](https://github.com/kitzeslab/r-ribbit) Implementation of the RIBBIT method (identify calls with repeated structure) for R (Note: we don’t update it, so we recommend using Python & OpenSoundscape)   
* [Agile modeling tutorial notebook](https://colab.research.google.com/drive/1gPBu2fyw6aoT-zxXFk15I2GObfMRNHUq?authuser=1#scrollTo=wxJv5CgoD-sM) resources for quickly creating a classifier, including using embedding search to find training samples, see also [readme](https://github.com/google-research/perch?tab=readme-ov-file#agile-modeling)  
  * Note: this functionality is being ported to the perch-hoplite [repo](https://github.com/google-research/perch-hoplite?tab=readme-ov-file)


### **Occupancy modeling**

* [Continuous-score occupancy model](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.13905) \- a new approach for interpretation of deep learning model outputs  
* [From species identification to occupancy modeling](https://ecoforecast.org/workshops/statistical-methods-seminar-series/#ai-python) \- a workflow and demonstration of how to run a machine learning classifier (here for camera traps) and incorporate the results into an occupancy model

### **Other resources**

* [Graphic Design for Ecology resources](https://docs.google.com/document/d/15n8lyXn0Z7WoQee6U4Z1b1G_Zv5UEjui24k0OnPYRuM/edit)  
* [Sound Calculator](https://docs.google.com/spreadsheets/d/1G3N5z7Xr8qbO7_Yx1a4qhmFpzZ1hMZ48kcT96v0Hoko/edit?gid=0#gid=0) decibel, voltage, and distance conversions

### **Demos**

* [A2O embedding Search demo](https://search.acousticobservatory.org/)  
  * [demo search](https://search.acousticobservatory.org/search/index.html?q=https://api.search.acousticobservatory.org/api/v1/a2o/audio_recordings/download/flac/519200?start_offset%3D25%26end_offset%3D30) for Eastern Whipbird

	
