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

## Final View of Project

#### 1. Home Page
![Screenshot (4144)](https://user-images.githubusercontent.com/82352524/132102507-d964f557-0734-4780-9cd3-e06c645c577e.png)
![Screenshot (4149)](https://user-images.githubusercontent.com/82352524/132102630-7c983132-d212-4643-a443-b8ead1efa2c0.png)
![Screenshot (4151)](https://user-images.githubusercontent.com/82352524/132102742-cb66e706-8a60-4a6d-a0ff-d61969d4f3b4.png)
![Screenshot (4155)](https://user-images.githubusercontent.com/82352524/132102856-8e9caa06-e12b-4009-a72c-0b7bfbfaee0f.png)
![Screenshot (4157)](https://user-images.githubusercontent.com/82352524/132102901-cfb6e90f-6dc4-4175-a68b-edb49f30c5eb.png)

#### 2. Chat
![Screenshot (4183)](https://user-images.githubusercontent.com/82352524/132103470-deb24170-fade-45d0-b2c7-c82607bc891b.png)
![Screenshot (4185)](https://user-images.githubusercontent.com/82352524/132103501-c107d53e-2fcc-4c9e-af8b-a2f6aab0bc6d.png)
![Screenshot (4186)](https://user-images.githubusercontent.com/82352524/132103534-d65a41c6-05e5-41ee-bc5f-bfe0b0afe818.png)
![Screenshot (4187)](https://user-images.githubusercontent.com/82352524/132103553-a92ddced-0b37-45ed-8ee5-9832992f8ff0.png)
![Screenshot (4188)](https://user-images.githubusercontent.com/82352524/132103572-4f5a98c7-60b7-4943-bb75-cc45d9444581.png)
![Screenshot (4189)](https://user-images.githubusercontent.com/82352524/132103587-d3920ba8-9992-46ab-9cce-50596772b399.png)
![Screenshot (4190)](https://user-images.githubusercontent.com/82352524/132103606-cb6b5536-0a21-45b6-a7aa-59ded03edfe7.png)
![Screenshot (4191)](https://user-images.githubusercontent.com/82352524/132103631-c184faa0-0be6-4757-a976-c34deac2bba9.png)

#### 3. Review
![Screenshot (4195)](https://user-images.githubusercontent.com/82352524/132103673-75a01819-5780-4029-8000-65cb31a68771.png)
![Screenshot (4197)](https://user-images.githubusercontent.com/82352524/132103697-67d01cb9-a307-4916-a54e-ca701c192560.png)
![Screenshot (4201)](https://user-images.githubusercontent.com/82352524/132103739-49e7d128-8473-4b94-b867-6c8d4356476a.png)
![Screenshot (4204)](https://user-images.githubusercontent.com/82352524/132103804-c71037f2-572b-418d-8e4d-6b553fd016fa.png)

#### 4. About Us
![Screenshot (4220)](https://user-images.githubusercontent.com/82352524/132104014-d75e0b6b-bc92-4b96-b82c-df7b7598734c.png)
![Screenshot (4222)](https://user-images.githubusercontent.com/82352524/132104030-0799ae8e-cd5c-466e-b99f-9b9097367c57.png)
![image](https://user-images.githubusercontent.com/82352524/132104141-895898a7-e970-4269-8b9e-c8f2e92e1060.png)





