# Music&me Chatbot Song Recommender System

<p align="center">
    <img src="https://user-images.githubusercontent.com/82326026/132090844-b7567cf9-2080-407a-8e1c-28700eb7b339.png" alt="Logo" width="250" height="80">
</p>
<p align="center">
Music&me Chatbot Song Recommender System
</p>  
  
  
  <details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>
  
  
  ## About The Project
In this era of technological advancements, music recommendation based on mood is much needed at it will help humans relieve stress and listen  to soothing music according to their mood.
  
In this project, we would be combining multiple services and open-source tools to make a chatbot(Alex) that recommends songs based on the tone of the conservation which the user is having with the Chatbot(Alex).
  
  ![Screenshot 2021-09-04 162623](https://user-images.githubusercontent.com/82326026/132092168-c92b50f5-2a07-4cbe-8ffa-283570f7250d.png)
  
  ![Screenshot 2021-09-04 162856](https://user-images.githubusercontent.com/82326026/132092181-6e56fa4e-a40f-4f45-b03a-4920df1aeeda.png)


 OBJECTIVES

* User starts the conservation with the Chatbot(Alex).
* Emotional Analysis of the conversation is done using the **[IBM Tone Analyzer API](https://tone-analyzer-demo.ng.bluemix.net/)**.
* Get the reply to the conservation from the Chatbot(Alex).
* Based on the Emotion which the app perceives ,top songs are retrieved using **[Last.fm songs API](https://www.last.fm/)**.
* Vibe along with the songs! 

YOUTUBE LINK OF THE PROJECT 

https://www.youtube.com/watch?v=aMF5vDRghFo


### Built With
  
* User Interface  - **[ANVIL Framework](https://anvil.works/)**
* Emotional Analysis - **[IBM Tone Analyzer API](https://tone-analyzer-demo.ng.bluemix.net/)**  
* Songs Recommendation - **[Last.fm songs API](https://www.last.fm/)**
  
## Getting Started
Fork and clone this repository in your local system.
 ```sh
git clone https://github.com/Srishti20022/Music-me-Chatbot_song_recommendor_system-.git
 ```
### Installation
1. Create an account on [IBM Cloud](https://cloud.ibm.com/) (It's free)
2. Enable the Tone Analyzer Service for your account from [here](https://cloud.ibm.com/catalog/services/tone-analyzer).
3. Try running the Python code for analyzing the conversation from [here](https://cloud.ibm.com/apidocs/tone-analyzer?code=python#tone) and don't forget to replace {apikey} and {url} with the apikey and url you received by enabling Tone Analyser Service for your account.
4. Create API account on [Last.fm songs API](https://www.last.fm/) and get the API_KEY.
5. Get top tracks using your API_KEY.

![ME_ME_PROJECT_CHATBOT_PYTHON_MODULE_ME_PROJECT_CHATBOT_PYTHON_MODULE_CHATBOT_PYTHON_GetTopTrack](https://user-images.githubusercontent.com/82326026/132092824-5b8a7cd3-0099-49fd-acdb-743bec7a9635.png)

## Usage

Chatbot(Alex) is one of the most important advancements of AI technology. This project successfully combines this technology with the humans need for entertainment in the form of  music suggestions.

In this age and time of technology, such an application would serve the purpose of helping humans relax and relieve their stress .The application is implemented as a desktop application, thereby being available to the user whenever required.

We can use it to swing our mood/emotion. We can also enhance this project for future work.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request.

## Contact
- [Komal Sangwan](https://github.com/KomalSangwan): Frontend Developer
   
   LinkedIn - https://www.linkedin.com/in/komal-sangwan-27a054208/
- [Riya Chaudhary](https://github.com/RiyaGit06): Backend Developer
    
    LinkedIn - https://www.linkedin.com/in/riya-chaudhary-a13884216/
- [Srishti Gupta](https://github.com/Srishti20022): Backend Developer
    
    LinkedIn - https://www.linkedin.com/in/srishti-gupta-7250b8203/
    
## Acknowledgements

* [CRIO PROJECTS](https://www.crio.do/projects/)
* [ALYSSAM GOULD](https://github.com/alyssamgould/chatbot/blob/master/intents.json)
* [IBM](https://cloud.ibm.com/)
* [LAST.FM SONGS](https://www.last.fm/)
* [ANVIL FRAMEWORK](https://anvil.works/)
