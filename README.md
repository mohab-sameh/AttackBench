![OS](https://img.shields.io/badge/OS-Windows/Mac/Ubuntu-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a) ![Language](https://img.shields.io/badge/Language-Python-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a) ![IDE](https://img.shields.io/badge/IDE-VSCode-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a) ![Platform](https://img.shields.io/badge/Platform-Streamlit-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a) ![Models](https://img.shields.io/badge/Models-Sklearn/Tensorflow-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)

<h1 align='center'> AttackBench 🔍</h1>

![image](https://user-images.githubusercontent.com/37941642/233388228-a15d5d47-c7d0-4cf1-914a-bce094a33ac7.png)

<p align='center'>AttackBench is a workbench for the research and development of Anomaly-Based Intrusion Detection Systems.</p>
<br />



<h2>Quick Look 👀</h2>
<img src="https://github.com/mohab-sameh/AttackBench/blob/main/assets/demo.gif" align="center">

<br />


<h2>Some Features 📋</h2>

* Easily develop complete & usable machine learning and deep learning pipelines 🧠
* Utilize 3rd Party Datasets (such as NSL-KDD, KDD-99, ISCX-NBXX) 📊
* Connect and import CSV datasets through your AWS S3 buckets 🗃️
* Perform Live Packet Capture & predict network attacks using your developed ML/DL Model! ☢️🔍
* Export comparative Metrics of executed pipelines 📑
* Simple and Intuitive GUI 🖥️
* Cloud-Deployable ☁️
* Tons of Data exploration, preprocessing, machine learning, and deep learning tools! 💻
* Cross-Platform usability 💻📱🖥️

<br />

<h2>Demo</h2>

Want to see AttackBench in action?

<a href="https://attackbench.streamlit.app/" target="_blank">

![AttackBench | Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)

</a>


<br />

<h2>Tested Platforms 🖥️</h2>

* Deployed on Windows 10 (20H2), Mac OS 10.14, Ubuntu 18.04/20.04
* Access through any device with your browser of choice (tested on Firefox, Safari, MS Edge, Chrome, Opera).




<br />

<h2>Installation 📜</h2>

* Install requirements:
```
pip install requirements.txt
```




<br />
<h2>Usage⌨️</h2>

* Run app:
```
streamlit run app.py
```
* Use through your browser of choice. 

* Or Try a ready cloud-deployed instance [here]([https://share.streamlit.io/mohab-sameh/anomaly-based-ids-workbench/main/Implementation/app-files/app.py](https://attackbench.streamlit.app/))




<br />
<h2>Packet Capture Dependencies 🔍</h2>

* Libpcap:
```
pip install libpcap-dev
```
* GCC ([installation instructions](https://linuxize.com/post/how-to-install-gcc-compiler-on-ubuntu-18-04/))
* KDD Feature extractor ([repo](https://github.com/AI-IDS/kdd99_feature_extractor) or use my [prebuilt repo](https://github.com/mohab-sameh/Kdd99-Feature-Extractor-Prebuilt))

> Note: please make sure the KDD Feature extractor is in the root directory (ex: ~/Kdd99-Feature-Extractor-Prebuilt/kdd99_feature_extractor-master)



<br />



<h2> 
  Published literature:
</h2>

[M. S. Abdel-Wahab, A. M. Neil and A. Atia, "A Comparative Study of Machine Learning and Deep Learning in Network Anomaly-Based Intrusion Detection Systems," 2020 15th International Conference on Computer Engineering and Systems (ICCES), 2020, pp. 1-6, doi: 10.1109/ICCES51560.2020.9334553.](https://ieeexplore.ieee.org/document/9334553)


