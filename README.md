# Sign_Langugage_Detection_ML_project2
###
Undergraduate Thesis Project 
###
Those who are deaf or hard of hearing primarily use sign language as a means of communication. People may readily express ideas and thoughts using this sort of gesture-based language, which removes obstacles brought on by challenges with hearing.

The fact that the vast majority of people on earth do not speak the language is a huge problem with this simple means of communication. Learning Sign Language requires a lot of time and work, just like learning any other language, which deters the general public from doing so.


Yet, the fields of machine learning and image detection have a clear solution to this problem. A type of real-time captioning for virtual reality can be made by utilizing predictive model technology to automatically classify Sign Language signals.

This project is a solution for this problem. I have used custom dataset for training this model.
###
## Steps to run on Windows

- Prerequisites: [Python 3.9](https://www.python.org/downloads/) (ensure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)) + [Git](https://www.markdownguide.org/basic-syntax/) Client
- Open GIT CMD >> navigate to working directory >> Clone this Github Repo

      https://github.com/AvijitChowdhury/Sign_Langugage_Detection_ML_project2.git

- Open Windows Powershell >> navigate to new working directory (cloned repo folder)
- Create a virtual environment

  - install virtual environment

        pip install virtualenv

  - create virtual environment by the name venv
         
         virtualenv venv
  - activate ENV

        .\venv\Scripts\activate

- Install project dependencies

      pip install -r .\requirements.txt

- Run the project

      python app1.py

- Look for the local host address on Powershell screen, something like: 127.0.0.1:5000 >> Type it on your Web Browser >> Project shall load
- Try out your Amazon Alexa test reviews and look for results
- To close >> Go back to Powershell & type `ctrl+c` >> Deactivate Virtual Environment ENV

      deactivate

### Steps to run on Mac

- Prerequisites: [Python 3.9](https://www.python.org/downloads/)
- Open Terminal >> navigate to working directory >> Clone this Github Repo

      git clone https://github.com/AvijitChowdhury/Sign_Langugage_Detection_ML_project2.git

- Navigate to new working directory (cloned repo folder)
- Create a virtual environment

  - install virtual environment

        pip install virtualenv

  - create virtual environment by the name ENV

        virtualenv ENV

  - activate ENV
  
        source ENV/bin/activate

- Install project dependencies

      pip install -r requirements.txt

- Run the project

      python app.py

- Look for the local host address on Terminal screen, something like: 127.0.0.1:5000 >> Type it on your Web Browser >> Project shall load
- Try out your Amazon Alexa test reviews and look for results
- To close >> Go back to Terminal & type `ctrl+c` >> Deactivate Virtual Environment ENV

      deactivate

<h1>Libraries Used: </h1>
<ul>
<li>Numpy</li>
<li>Pandas</li>
<li>Matplotlib</li>
<li>tensorflow</li>
<li>keras</li>
<li>tkinter</li>
      <li>hunspell</li>
      <li>strings</li>
      <li>openCV</li>
</ul>
<h1><b>WorkFlow</b></h1>

<ol>
<li>Data Preprocessing</li>
<li>Rescale & assign categorical designs</li>
<li>CNN Model</li>
<li>Splitting Data Into Training and Test Set</li>
<li>Visulazing Dataset and Determining Training Loss</li>
</ol>


