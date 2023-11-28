# David M. Groppe, PhD
Human Neuro-Data Scientist, Epilepsy Researcher, Software Developer<br>
* [Google Scholar Profile](https://scholar.google.com/citations?user=M-rNJg0AAAAJ&hl=en)<br>
* [GitHub Profile](https://github.com/dmgroppe)<br>
* [LinkedIn](https://ca.linkedin.com/in/david-groppe-1105bb19)<br>
* [Twitter/X](https://twitter.com/dmgroppe)
* [Neglected Blog](https://dgroppedotcom.wordpress.com/)

## Data Sharing in Epilepsy Research
Historically, scientists have shared their data analyses but sharing the data itself was impractical. Now, however, it is quite feasible to share digital scientific data and there is increasing momentum to make data sharing a routine part of publicly funded research. This is because sharing data:
* increases the reliability of scientific findings by enabling replication and increasing statistical power
* increases efficiency by enabling data-reuse
* promotes collaboration
* can be necessary for studying rare conditions
* facilitates acquiring diverse samples that are representative of our diverse patient populations and clinical cultures
* democratizes science by improving data access
* promotes commercial innovation (if the data are licensed for commercial use)

Sharing data does have some potential challenges such as:
* the need to protect the privacy of the individuals who provided the data
* the cost of organizing and sharing the data
* data generators not getting rewarded/credit for sharing
* establishing standard data formats that facilitate data discovery and re-use
* potentially enabling other researchers to “scoop” the data generators (i.e., other researchers might make discoveries using the data before the data generators have a chance to perform those analyses)

While the scientific community has been actively working to tackle those challenges,  I think it is by far still the norm for researchers to not share their data. To get a sense of the state and trajectory of data sharing in the epilepsy research community, I tried to catalog all available public datasets of intracranial electroencephalogram (iEEG) data. I also created this survey to help other iEEG researchers find these data. There is not yet a PubMed or Google Scholar for scientific data and since datasets are spread across multiple repositories in multiple formats, it can be challenging to find the data you need. Finally, I hope this survey helps researchers identify data repositories where they might share their own data or look for other types of data.

Note, I chose iEEG data, because it is the data type I am most familiar with. If you work with other types of epilepsy data, please email me with links to public databases of such data. I am providing links to those resources at the bottom of this page as well.
<br/><br/>

## iEEG Public Datasets
I searched the following repositories for iEEG Data:
* [Epilepsiae](http://www.epilepsiae.eu/project_outputs/european_database_on_epilepsy)<br>
* [IEEG.ORG](https://www.ieeg.org/)<br>
* [Epilepsy Ecosystem](https://www.epilepsyecosystem.org/)<br>
* [Open Neuro](https://openneuro.org/)<br>
* [Physionet](https://physionet.org/)<br>
* [Kaggle](https://www.kaggle.com/)<br>
* [Pennsieve](https://app.pennsieve.io/)<br>
* [figshare](https://figshare.com/)<br>
* [Brain-CODE](https://www.braincode.ca/)<br>
* [SWEC-ETHZ iEEG Database and Algorithms](http://ieeg-swez.ethz.ch/)<br>
* [Distributed Archive for Neurophysiological Data Integration (DANDI)](https://www.dandiarchive.org/)<br>
* [Data Archive for the Brain Initiative (DABI)](https://dabi.loni.usc.edu/)<br>
* [Neuroimaging Informatics Tools and Resources Collaboratory (NITRC)](https://www.nitrc.org/)<br>
* [Collaborative Research in Computational Neuroscience (CRCNS)](https://crcns.org/)<br>
* [Nightingale Open Science](https://www.ngsci.org/)<br>

In addition, I was unable to access the following repositories because I either could not figure out how to access the data or my one request to access them went unanswered. I am listing them here for completeness and am sure that with a bit more effort you could access the data for reasonable purposes:
* [Michael Kahana Laboratory](https://memory.psych.upenn.edu/Data)<br>
* [Mayo Clinic Bioelectronics Neurophysiology and Engineering Lab](https://www.mayo.edu/research/labs/bioelectronics-neurophysiology-engineering/data-code-sharing)<br>
* [Multicenter iEEG Sleep Atlas](https://ieegatlas.loris.ca/)<br>
* [MNI Open iEEG Atlas](https://mni-open-ieegatlas.research.mcgill.ca/)<br>

Finally, the [Open Science Framework](https://osf.io/) and [Dryad](https://datadryad.org) have a few iEEG datasets as well, but I have not yet had time to add them to the table.

Some of those repositories did not have any iEEG data and there were some DABI datasets I was unable to access because I was not granted permission. For each dataset, I tried to determine:
* the amount of data
* data format
* presence of associated neuroimaging data
* patient demographic data
* data license

Those traits are summarized in the table below. If I have made any errors, please let me know so I can correct them.
| DATASET | YEAR_PUBLISHED | URL | n PATIENTS | RAW IEEG AVAILABLE | DURATION | IMAGING | SURGICAL OUTCOMES | LICENSE | LICENSED FOR COMMERCIAL USE | FORMAT | ACCESS | AGE | ETHNICITY | SEX | HANDEDNESS | SOCIOECONOMIC STATUS |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SWEC-ETHZ long term iEEG database | 2018 | http://ieeg-swez.ethz.ch/ | 18 | No | mean 6.1 days/patient | No | No | Custom | No | Custom | public | No | No | No | No | No |
| SWEC-ETHZ short term iEEG database | 2018 | http://ieeg-swez.ethz.ch/ | 16 | No | seizures +/- 3 minutes | No | No | Custom | No | Custom | public | No | No | No | No | No |
| Dataset Clinical Epilepsy iEEG to BIDS-RESPect_longterm_iEEG | 2021 | https://openneuro.org/datasets/ds003848/versions/1.0.3 | 6 | Yes | 3-4 hours/patient | Yes: Preimplant MRI | No | CC0 | Yes | iEEG BIDS | public | Yes | No | Yes | No | No |
| ieeg.org | 2012 | https://ieeg.org | 155 | Yes? | variable, typically days | Sometimes | Sometimes? | Custom | Yes | Custom | public (though you need to request access) | Yes | Sometimes | Sometimes | Sometimes | No |
| Epilepsiae | 2012 | http://www.epilepsiae.eu/project_outputs/european_database_on_epilepsy | 30 | Yes? | multi-day | No | Yes | Custom | Yes | Custom | fee | Yes | No | Yes | Yes | No |
| Epilepsy iEEG Multicenter Dataset | 2022 | https://openneuro.org/datasets/ds003029/versions/1.0.5 | 35 | Yes? | a few minutes per patient? | No | Yes | CC0 | Yes | iEEG BIDS | public (though you need to get permission from the Cleveland Clinic for most of the data) | Yes | Yes | Yes | Yes | No |
| Epilepsy iEEG Interictal Multicenter Dataset | 2023 | https://openneuro.org/datasets/ds003876/versions/1.0.2 | 39 | Yes? | a few minutes per patient, one intericatl files was 40 min long | No | Yes | CC0 | Yes | iEEG BIDS | public | Yes | Yes | Yes | Yes | No |
| HUP iEEG Epilepsy Dataset | 2022 | https://openneuro.org/datasets/ds004100/versions/1.1.1 | 58 | Yes? | ~3 hours per patient? | No | Yes | CC0 | Yes | iEEG BIDS | public | Yes | No | Yes | Yes | No |
| Dataset Clinical Epilepsy iEEG to BIDS-RESPect_intraoperative_iEEG | 2021 | https://openneuro.org/datasets/ds003844/versions/1.0.3 | 6 | Yes? | probably minutes (data are in Brain Vision format) | No | No | CC0 | Yes | iEEG BIDS | public | No | No | Yes | No | No |
| Delayed Free Recall of Word Lists | 2023 | https://openneuro.org/datasets/ds004789/versions/1.0.0 | 107 | Yes? | minutes? | No | No | CC0 | Yes | iEEG BIDS | public | Yes | No | Yes | Yes | No |
| Michigan High Res EEG-Patient 18 | 2022 | https://discover.pennsieve.io/datasets/255 | 1 | Yes? | 4 days | No | Yes | CC-BY-4.0 | Yes | Custom | fee | Yes | No | Yes | No | No |
| Network Dynamics of HFOs | 2022 | https://discover.pennsieve.io/datasets/280 | 2 | No | minutes | No | nan | CC- BY-SA 4.0 | Yes | Custom | fee | No | No | No | No | No |
| Intracranial EEG Epilepsy Study 6 | 2019 | https://discover.pennsieve.io/datasets/15 | 1 | Yes | days? | No | nan | CC0 | Yes | Custom | fee | Yes | No | Yes | Yes | No |
| Intracranial EEG Epilepsy Study 3 | 2019 | https://discover.pennsieve.io/datasets/14 | 1 | Yes | days? | No | No? | CC0 | Yes | Custom | fee | Yes | No | Yes | Yes | No |
| Intracranial EEG Epilepsy Study 5 | 2019 | https://discover.pennsieve.io/datasets/13 | 1 | Yes | days? | No | Yes | CC0 | Yes | Custom | fee | Yes | No | Yes | Yes | No |
| HUP Interictal iEEG Atlas | 2023 | https://discover.pennsieve.io/datasets/179 | 166 | No | 1 minute | No | Yes | ODC-BY | Yes | Custom | fee | Yes | No | Yes | No | No |
| Seizure severity score | 2023 | https://discover.pennsieve.io/datasets/326 | 54 | Yes | minutes | No | No | ODC-BY | Yes | Custom | fee | No | No | No | No | No |
| Epilepsy Ecosystem | 2018 | https://www.epilepsyecosystem.org/ | 3 | Yes | hours | No | nan | Creative Commons license with conditions on ATTRIBUTION, NON-COMMERCIAL use and SHARE-ALIKE | No | Custom? | public (though you need to request access) | No | No | No | No | No |
| ieeg-1 | 2017 | https://crcns.org/data-sets/methods/ieeg-1/about-ieeg-1 | 20 | No | 30-90 min? | No | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | Yes | No |
| MNI Open iEEG Atlas | 2018 | https://mni-open-ieegatlas.research.mcgill.ca/ | 106 | No | 1 minute | No | No? | Custom | No | Custom? | public (though you need to request access) | Yes | No | Yes | No | No |
| Multicenter intracranial EEG dataset for classification of graphoelements and artifactual signals | 2020 | https://figshare.com/search?q=nejedly&itemTypes=3 | 39 | No | 3 sec segements | No | No | CC0 | Yes | IEEG BIDS | public | No | No | No | No | No |
| A library of human electrocorticographic data and analyses | 2016 | https://purl.stanford.edu/zk881ps0522 | 34 | No | minutes | No | No | CC BY-SA | Yes | Custom | public | No | No | No | No | No |
| UPenn and Mayo Clinic's Seizure Detection Challenge | 2014 | https://www.kaggle.com/competitions/seizure-detection | 8 | Yes | minutes | No | No | Custom | No | Custom | public | Yes | No | Yes | No | No |
| American Epilepsy Society Seizure Prediction Challenge | 2014 | https://www.kaggle.com/competitions/seizure-prediction/overview | 2 | Yes | 10 minute clips | No | No | Custom | No | Custom | public | Yes | No | Yes | No | No |
| Dataset of neurons and intracranial EEG from human amygdala during aversive dynamic visual stimulation | 2023 | https://dandiarchive.org/dandiset/000576 | 9 | Yes? | minutes? | No | No | CC-BY-4.0 | Yes | NWB | public | No? | No? | No? | No? | No? |
| Dataset of human medial temporal lobe neurons, scalp and intracranial EEG during a verbal working memory task | 2023 | https://dandiarchive.org/dandiset/000574 | 9 | Yes? | minutes? | No | No | CC-BY-4.0 | Yes | NWB | public | No? | No? | No? | No? | No? |
| AJILE12: Long-term naturalistic human intracranial neural recordings and pose | 2022 | https://dandiarchive.org/dandiset/000055 | 12 | Yes? | multi-day | No | No | CC-BY-4.0 | Yes | NWB | public | No? | No? | No? | No? | No? |
| Human ECoG speaking consonant-vowel syllables | 2022 | https://dandiarchive.org/dandiset/000019 | 4 | Yes? | minutes? | No | No | CC-BY-4.0 | Yes | NWB | public | No? | No? | No? | No? | No? |
| Multimodal Visual Consciousness Study Dataset | 2022 | https://bmvp.projects.nitrc.org/ | 7 | Yes? | minutes | No | No | CC-BY-4.0 | Yes | Custom | public | No | No | No | No | No |
| Local and distant cortical responses to single pulse intracranial stimulation in the human brain are differentially modulated by specific stimulation parameter | 2022 | https://dabi.loni.usc.edu/dsi/W4SNQ7HR49RL | 52 | Yes | minutes | Yes: Pre- and post-implant | No | PDDL | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| Technology development for closed-loop deep brain stimulation to treat refractory neuropathic pain | 2023 | https://dabi.loni.usc.edu/dsi/1UH3NS109556 | 4 | Yes? | minutes | No | nan | Custom | Yes? | Custom | public | No? | No? | No? | No? | No? |
| Invasive Approach to Model Human Cortex-Basal Ganglia Action-Regulating Networks | 2021 | https://dabi.loni.usc.edu/dsi/1U01NS098961 | 146 | Yes? | minutes | Yes: Pre- and post-implant & fluoro | nan | Custom | Yes? | Custom | public | No? | No? | No? | No? | No? |
| iEEG on children during gameplay | 2023 | https://openneuro.org/datasets/ds004770/versions/1.0.0 | 10 | Yes? | minutes | No | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | Yes | No |
| Dataset of intracranial EEG, scalp EEG and beamforming sources from human epilepsy patients performing a verbal working memory tas | 2023 | https://openneuro.org/datasets/ds004752/versions/1.0.1 | 15 | Yes | minutes | No | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | Yes | No |
| sEEG Passive listening to natural speech | 2023 | https://openneuro.org/datasets/ds004703/versions/1.1.0 | 10 | Yes | minutes | Yes | No | Contradictory CC0 but says not for commercial use | No | IEEG BIDS | public | Yes | No | Yes | Yes | No |
| HAPwave_bids | 2023 | https://openneuro.org/datasets/ds004696/versions/1.0.0 | 8 | Yes | minutes | No | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| Intraoperative recordings of medianus stimulation with low and high impedance ECoG | 2023 | https://openneuro.org/datasets/ds004642/versions/1.0.1 | 10 | Yes? | minutes | No | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| Intracranial recordings using BCI2000 and the CorTec BrainInterchange | 2023 | https://openneuro.org/datasets/ds004624/versions/1.0.1 | 1 | Yes | minutes? | Yes | No | CC0 | Yes | IEEG BIDS | public | No | No | Yes | No | No |
| iEEG on children during slow wave sleep | 2023 | https://openneuro.org/datasets/ds004551/versions/1.0.6 | 114 | Yes | minutes data from one subject was 30 min | No | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| sEEG Forced Two-Choice Task | 2023 | https://openneuro.org/datasets/ds004473/versions/1.0.2 | 8 | Yes | minutes | Yes | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| Electrical stimulation of temporal and limbic circuitry produces distinct responses in human ventral temporal cortex | 2023 | https://openneuro.org/datasets/ds004457/versions/1.0.2 | 5 | Yes | minutes | No | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| Visual ECoG dataset | 2022 | https://openneuro.org/datasets/ds004194/versions/1.0.1 | 11 | Yes | minutes | Yes MRI | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| CCEP ECoG dataset across age 4-51 | 2022 | https://openneuro.org/datasets/ds004080/versions/1.2.4 | 74 | Yes | minutes | No | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| Conscious-SEEG-Dataset | 2021 | https://openneuro.org/datasets/ds003754/versions/1.0.2 | 44 | Yes | minutes | Yes MRI and CT | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | No | No |
| Basis profile curve identification to understand electrical stimulation effects in human brain networks | 2021 | https://openneuro.org/datasets/ds003708/versions/1.0.4 | 1 | Yes? | minutes | No | No | CC0 | Yes | IEEG BIDS | public | No | No | No | No | No |
| Open multimodal iEEG-fMRI dataset from naturalistic stimulation with a short audiovisual film | 2021 | https://openneuro.org/datasets/ds003688/versions/1.0.7 | 63 | Yes | minutes | Yes MRI | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | Yes | No |
| Dataset of neurons and intracranial EEG from human amygdala during aversive dynamic visual stimulation | 2020 | https://openneuro.org/datasets/ds003374/versions/1.1.1 | 9 | Yes | minutes | No | No | CC0 | Yes | IEEG BIDS & NIX | public | Yes | No | Yes | No | No |
| PROBE iEEG | 2020 | https://openneuro.org/datasets/ds003078/versions/1.0.0 | 6 | Yes | minutes | Yes pre & post MRI | No | CC0 | Yes | IEEG BIDS | public | No | No | No | No | No |
| Human es-fMRI Resource: Concurrent deep-brain stimulation and whole-brain functional MRI | 2020 | https://openneuro.org/datasets/ds002799/versions/1.0.4 | 26 | Yes | minutes | Yes T1, T2, fMRI (pre and post-imp MRI) | No | CC0 | Yes | IEEG BIDS | public | Yes | No | Yes | Yes | No |


## Public Non-iEEG Epilepsy Datasets:
Below are links to epilepsy datasets with other types of data. If you know of any others, please email me with links.

### Scalp EEG Data:
* [Temple University EEG Corpus](https://isip.piconepress.com/projects/tuh_eeg/)<br>
* [CHB-MIT Scalp EEG Database](https://physionet.org/content/chbmit/1.0.0/)<br>
* [Epilepsiae](http://www.epilepsiae.eu/project_outputs/european_database_on_epilepsy)<br>
* [Siena Scalp EEG Database](https://physionet.org/content/siena-scalp-eeg/1.0.0/)<br>
* [EEGNet](https://eegnet.org/)<br>
* [Neonatal Seizure Recordings](https://zenodo.org/records/4940267)<br>
* [Open Neuro](https://openneuro.org/)<br>

### Imaging Data:
* [ENIGMA](https://enigma.ini.usc.edu/ongoing/enigma-epilepsy/)<br>
* [Open Neuro](https://openneuro.org/)<br>

