# LeetmusQL

LeetmusQL is a software platform designed to deliver Computer-Based Tests (CBT) for a wide range of subjects, courses, and professions. It empowers administrators to create, manage, and deploy assessments seamlessly, facilitating a standardized and efficient testing experience.

### Target Audience

* Independent Testers & Assessment Developers
* Educational Institutions (Schools, Universities)
* Professional Training & Certification Bodies
* Corporate Learning & Development Departments

### Key Features

#### Flexible Test Creation:

* Admins can design tests with various question formats (multiple choice, true/false, essay, etc.).
* Build question banks categorized by subject, topic, or difficulty level.

#### Streamlined Test Delivery:

* Secure platform ensures test integrity with features like time limits, question randomization etc.
* Intuitive user interface for test takers to navigate the assessment smoothly.
* Responsive design and compatibility with various devices (desktops, laptops, tablets) for accessibility.

#### Detailed Reporting & Analytics:

* Generate comprehensive reports on individual and group test performance.
* Visualize results with charts and graphs for clear insights.
* Analyze data to identify strengths, weaknesses, and knowledge gaps.

### Tech Stack:

* **Backend:** Python (with Flask framework)
* **Frontend:** JavaScript (with Bootstrap library)
* **Database:** SQLite & SQLAlchemy (form)

View the project via this [link](https://leetmusql.onrender.com/)

### Getting Started

#### Prerequisites

* Python: [Python Installation](https://www.python.org/downloads/)
* Flask: [Flask installation](https://flask.palletsprojects.com/en/2.0.x/installation/)

#### Installation 

```bash
# clone this repo
$ git clone https://github.com/ginjardev/LeetmusQL.git

# go to the directory
$ cd LeetmusQL

# use virtual env if you want
$ python3 -m venv env && source env/bin/activate

# generate static project
$ pip install -r requirements.txt

# run flask app 
$ python3 run.py 
# or using gunicorn
$ gunicorn run:app
```
#### Usage
This project MVP can be set up and used by schools and other educational organisations.

#### Contributing
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

# Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
Distributed under the MIT License. See LICENSE for more information

