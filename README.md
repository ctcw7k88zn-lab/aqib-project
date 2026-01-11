<p><small>Best View in <a href="https://github.com/settings/appearance">Light Mode</a> and Desktop Site (Recommended)</small></p><br/>

![AI-Resume-Analyzer](https://socialify.git.ci/deepakpadhi986/AI-Resume-Analyzer/image?description=1&descriptionEditable=AI-Powered%20Resume%20Analysis%20Tool%20with%20Skill%20Recommendations%20and%20Career%20Insights&font=Raleway&language=1&pattern=Plus&theme=Light)

<div align="center">
  <h1>🌴 AI RESUME ANALYZER 🌴</h1>
  <p>A Comprehensive AI-Powered Tool for Resume Analysis, Career Predictions, and Personalized Recommendations</p>
  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/github/last-commit/deepakpadhi986/AI-Resume-Analyzer" alt="last update" />
    <img src="https://badges.frapsoft.com/os/v2/open-source.svg?v=103" alt="open source" />
    <img src="https://img.shields.io/github/languages/top/deepakpadhi986/AI-Resume-Analyzer?color=red" alt="language" />
    <img src="https://img.shields.io/github/languages/code-size/deepakpadhi986/AI-Resume-Analyzer?color=informational" alt="code size" />
    <img src="https://img.shields.io/github/license/deepakpadhi986/AI-Resume-Analyzer.svg?color=yellow" alt="license" />
    <img src="https://img.shields.io/badge/Python-3.9.12-blue" alt="python version" />
    <img src="https://img.shields.io/badge/Framework-Streamlit-red" alt="framework" />
  </p>
  
  <!--links-->
  <h4>
    <a href="#-table-of-contents">Table of Contents</a>
    <span> · </span>
    <a href="#-preview">Preview</a>
    <span> · </span>
    <a href="#-setup--installation">Installation</a>
    <span> · </span>
    <a href="#-features">Features</a>
    <span> · </span>
    <a href="#-contributing">Contributing</a>
  </h4>
  <p>
    <small align="justify">
      Built with 🤍 by 
      <a href="https://dnoobnerd.netlify.app/">Deepak Padhi</a> through 
      <a href="https://www.linkedin.com/in/mrbriit/">Dr Bright --(Data Scientist)</a>
     </small>
  </p>
  <small align="justify">🚀 A Project Submitted for the partial fulfilment of the degree B.sc CS at 
    <a href="https://kirticollege.edu.in/">Kirti College</a> during academic year 2022-23
  </small>
</div><br/><br/>

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Project Architecture](#-project-architecture)
- [Database Schema](#-database-schema)
- [Installation Guide](#-installation-guide)
- [Usage Instructions](#-usage-instructions)
- [Project Structure](#-project-structure)
- [How It Works](#-how-it-works)
- [API Documentation](#-api-documentation)
- [Features in Detail](#-features-in-detail)
- [Scope and Applications](#-scope-and-applications)
- [Troubleshooting](#-troubleshooting)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [Preview](#-preview)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 About the Project

<div align="center">
    <br/><img src="https://raw.githubusercontent.com/deepakpadhi986/AI-Resume-Analyzer/main/screenshots/RESUME.png" alt="screenshot" /><br/><br/>
    <p align="justify"> 
      <strong>AI Resume Analyzer</strong> is an intelligent, comprehensive tool that leverages Natural Language Processing (NLP) and Machine Learning techniques to analyze resumes in PDF format. The application extracts key information, identifies skills, predicts job roles, and provides personalized recommendations to help users improve their resumes and career prospects.
    </p>
    <p align="justify">
      This tool parses information from resumes using advanced NLP techniques, identifies keywords and skills, clusters them into relevant sectors, and provides intelligent predictions, recommendations, and analytics for both applicants and recruiters. It serves as a bridge between job seekers and their ideal career paths by offering data-driven insights.
    </p>
</div>

### What Makes This Project Unique?

- **🤖 AI-Powered Analysis**: Uses advanced NLP and machine learning to extract and analyze resume content
- **📊 Comprehensive Analytics**: Provides detailed analytics for both users and administrators
- **🎯 Skill-Based Recommendations**: Intelligent skill recommendations based on industry standards
- **📈 Resume Scoring**: Automated resume scoring system to help users improve their resumes
- **🌍 Location Intelligence**: Geographic analytics to understand user distribution
- **💼 Multi-Domain Support**: Supports Data Science, Web Development, Android/iOS Development, and UI/UX Design

---

## ✨ Key Features

### 👤 User Features

#### **Resume Upload & Parsing**
- Upload resumes in PDF format
- Automatic extraction of personal information (name, email, contact, degree)
- Skill extraction and keyword identification
- Page count and document structure analysis

#### **Intelligent Analysis**
- **Experience Level Prediction**: Automatically classifies users as Fresher, Intermediate, or Experienced
- **Job Role Prediction**: Predicts the most suitable job role based on skills
- **Resume Scoring**: Calculates a comprehensive score (0-100) based on resume completeness
- **Geographic Data**: Captures and analyzes user location data (city, state, country)

#### **Personalized Recommendations**
- **Skill Recommendations**: Suggests relevant skills based on predicted job role
- **Course Recommendations**: Provides curated course suggestions for skill development
- **Resume Tips**: Actionable tips to improve resume quality
- **Video Resources**: Resume writing and interview preparation videos

#### **Resume Scoring Criteria**
The application evaluates resumes based on the following criteria:
- **Objective/Summary** (6 points): Career objective or professional summary
- **Education** (12 points): Educational background and qualifications
- **Experience** (16 points): Work experience and professional history
- **Internships** (6 points): Internship experiences
- **Skills** (7 points): Technical and soft skills listed
- **Hobbies** (4 points): Personal hobbies and interests
- **Interests** (5 points): Professional interests
- **Achievements** (13 points): Awards, recognitions, and accomplishments
- **Certifications** (12 points): Professional certifications
- **Projects** (19 points): Personal or professional projects

**Total Maximum Score: 100 points**

### 👨‍💼 Admin Features

#### **User Management**
- View all user data in tabular format
- Download user data as CSV files for analytics
- Access uploaded PDF files from the Uploaded_Resumes folder
- Comprehensive user activity tracking

#### **Analytics Dashboard**
Interactive pie charts and visualizations for:
- **User Ratings**: Distribution of user feedback ratings (1-5)
- **Predicted Fields/Roles**: Job role distribution analysis
- **Experience Levels**: User experience level breakdown
- **Resume Scores**: Score distribution across all users
- **User Count**: Usage statistics based on IP addresses
- **Geographic Analytics**: 
  - City-wise user distribution
  - State-wise user distribution
  - Country-wise user distribution

#### **Feedback Management**
- View all user feedback and comments
- Analyze user satisfaction through ratings
- Track feedback history over time

### 💬 Feedback System

- **Feedback Form**: Easy-to-use feedback submission form
- **Rating System**: 5-star rating system (1-5 scale)
- **Comment History**: Historical feedback and comments display
- **Analytics**: Overall ratings visualization with pie charts

---

## 🛠 Technology Stack

### Frontend Technologies

| Technology | Purpose | Version |
|------------|---------|---------|
| **Streamlit** | Web application framework | 1.12.2 |
| **HTML/CSS** | Styling and markup | - |
| **JavaScript** | Interactive components | - |

**Why Streamlit?**
Streamlit is a Python framework that allows rapid development of interactive web applications. It's perfect for data science projects as it provides built-in widgets, data visualization capabilities, and automatic reruns for seamless user experience.

### Backend Technologies

| Technology | Purpose | Version |
|------------|---------|---------|
| **Python** | Core programming language | 3.9.12 |
| **Streamlit** | Backend framework | 1.12.2 |

**Python 3.9.12**: This version was chosen for stability and compatibility with all required libraries.

### Database

| Technology | Purpose | Version |
|------------|---------|---------|
| **MySQL** | Relational database management | Latest |

**Why MySQL?**
MySQL provides robust data storage, excellent performance for structured data, and is widely supported. It's perfect for storing user data, feedback, and analytics information.

### Core Libraries & Modules

#### **Data Processing & Analysis**
- **pandas** (1.4.4): Data manipulation and analysis
- **numpy** (1.23.2): Numerical computing

#### **Resume Parsing**
- **pyresparser** (1.0.6): Advanced resume parsing library
- **pdfminer3** (2018.12.3.0): PDF text extraction
- **pdfminer.six** (20220524): Alternative PDF processing

#### **Natural Language Processing**
- **NLTK** (3.7): Natural language processing toolkit
- **spacy** (2.3.5): Advanced NLP library
- **en_core_web_sm**: English language model for spaCy

#### **Visualization**
- **Plotly** (5.10.0): Interactive data visualization
- **matplotlib** (3.5.3): Static plotting library

#### **Database Connectivity**
- **PyMySQL** (1.0.2): MySQL database connector

#### **Geographic Data**
- **geocoder** (1.38.1): Geocoding library
- **geopy** (2.2.0): Python geocoding library

#### **Other Utilities**
- **streamlit-tags** (1.2.8): Tag input components
- **Pillow** (9.2.0): Image processing
- **docx2txt** (0.8): Document text extraction

---

## 🏗 Project Architecture

### System Architecture Overview

```
┌─────────────────────────────────────────────────────────────┐
│                    User Interface (Streamlit)                │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐   │
│  │   User   │  │ Feedback │  │   About  │  │  Admin   │   │
│  │  Module  │  │  Module  │  │  Module  │  │  Module  │   │
│  └──────────┘  └──────────┘  └──────────┘  └──────────┘   │
└────────────────────┬────────────────────────────────────────┘
                     │
        ┌────────────┼────────────┐
        │            │            │
┌───────▼─────┐ ┌───▼────┐ ┌─────▼──────┐
│  Resume     │ │  NLP   │ │  Analytics │
│  Parser     │ │ Engine │ │  Engine    │
│  (pyresparser)│ │ (NLTK/spaCy)│ │ (pandas/plotly)│
└───────┬─────┘ └───┬────┘ └─────┬──────┘
        │            │            │
        └────────────┼────────────┘
                     │
        ┌────────────▼────────────┐
        │    MySQL Database       │
        │  ┌────────┐ ┌────────┐ │
        │  │user_data││feedback│ │
        │  └────────┘ └────────┘ │
        └─────────────────────────┘
```

### Data Flow

1. **User Upload**: User uploads PDF resume through Streamlit interface
2. **PDF Processing**: PDF is saved to `Uploaded_Resumes/` folder and processed using pdfminer3
3. **Resume Parsing**: pyresparser extracts structured data (name, email, skills, etc.)
4. **NLP Analysis**: NLTK and spaCy analyze text for keywords, skills, and experience level
5. **Role Prediction**: ML-based algorithm predicts job role based on skills
6. **Recommendations**: System generates skill recommendations and course suggestions
7. **Scoring**: Resume is scored based on predefined criteria
8. **Data Storage**: All data is stored in MySQL database
9. **Visualization**: Results are displayed with interactive charts and tables

---

## 💾 Database Schema

### Table: `user_data`

Stores comprehensive user information and resume analysis results.

| Column Name | Data Type | Description | Constraints |
|------------|-----------|-------------|-------------|
| ID | INT | Primary key, auto-increment | PRIMARY KEY, AUTO_INCREMENT |
| sec_token | VARCHAR(20) | Security token for user session | NOT NULL |
| ip_add | VARCHAR(50) | User's IP address | NULL |
| host_name | VARCHAR(50) | Host name | NULL |
| dev_user | VARCHAR(50) | Device user | NULL |
| os_name_ver | VARCHAR(50) | Operating system name and version | NULL |
| latlong | VARCHAR(50) | Latitude and longitude | NULL |
| city | VARCHAR(50) | User's city | NULL |
| state | VARCHAR(50) | User's state | NULL |
| country | VARCHAR(50) | User's country | NULL |
| act_name | VARCHAR(50) | Actual user name | NOT NULL |
| act_mail | VARCHAR(50) | Actual user email | NOT NULL |
| act_mob | VARCHAR(20) | Actual user mobile number | NOT NULL |
| Name | VARCHAR(500) | Parsed name from resume | NOT NULL |
| Email_ID | VARCHAR(500) | Parsed email from resume | NOT NULL |
| resume_score | VARCHAR(8) | Calculated resume score | NOT NULL |
| Timestamp | VARCHAR(50) | Analysis timestamp | NOT NULL |
| Page_no | VARCHAR(5) | Number of pages in resume | NOT NULL |
| Predicted_Field | BLOB | Predicted job field/role | NOT NULL |
| User_level | BLOB | User experience level | NOT NULL |
| Actual_skills | BLOB | Extracted skills from resume | NOT NULL |
| Recommended_skills | BLOB | Recommended skills | NOT NULL |
| Recommended_courses | BLOB | Recommended courses | NOT NULL |
| pdf_name | VARCHAR(50) | Uploaded PDF filename | NOT NULL |

### Table: `user_feedback`

Stores user feedback and ratings.

| Column Name | Data Type | Description | Constraints |
|------------|-----------|-------------|-------------|
| ID | INT | Primary key, auto-increment | PRIMARY KEY, AUTO_INCREMENT |
| feed_name | VARCHAR(50) | Feedback provider name | NOT NULL |
| feed_email | VARCHAR(50) | Feedback provider email | NOT NULL |
| feed_score | VARCHAR(5) | Rating score (1-5) | NOT NULL |
| comments | VARCHAR(100) | Feedback comments | NULL |
| Timestamp | VARCHAR(50) | Feedback timestamp | NOT NULL |

---

## 📥 Installation Guide

### Prerequisites

Before installing the project, ensure you have the following software installed:

1. **Python 3.9.12**
   - Download from: https://www.python.org/downloads/release/python-3912/
   - During installation, check "Add Python to PATH"

2. **MySQL**
   - Download from: https://www.mysql.com/downloads/
   - Install MySQL Server and MySQL Workbench

3. **Visual Studio Code** (Recommended)
   - Download from: https://code.visualstudio.com/Download
   - Install Python extension for better development experience

4. **Visual Studio Build Tools** (For Windows)
   - Required for compiling some Python packages
   - Download from: https://aka.ms/vs/17/release/vs_BuildTools.exe
   - Select "C++ build tools" during installation

### Step-by-Step Installation

#### Step 1: Clone the Repository

```bash
git clone https://github.com/ctcw7k88zn-lab/aqib-project.git
cd aqib-project/deepakpadhi986-AI-Resume-Analyzer-456b271
```

#### Step 2: Create Virtual Environment

Creating a virtual environment is recommended to avoid conflicts with other Python projects.

**For Windows:**
```bash
python -m venv venvapp
cd venvapp\Scripts
activate
cd ..\..
```

**For macOS/Linux:**
```bash
python3 -m venv venvapp
source venvapp/bin/activate
```

After activation, you should see `(venvapp)` in your command prompt.

#### Step 3: Install Dependencies

Navigate to the App directory and install required packages:

```bash
cd App
pip install -r requirements.txt
```

This will install all required packages. The installation may take several minutes.

#### Step 4: Download spaCy Language Model

The application requires the English language model for spaCy:

```bash
python -m spacy download en_core_web_sm
```

#### Step 5: Setup MySQL Database

1. **Start MySQL Server**
   - On Windows: Start MySQL service from Services
   - On macOS: `brew services start mysql`
   - On Linux: `sudo systemctl start mysql`

2. **Create Database**
   ```sql
   CREATE DATABASE cv;
   ```

3. **Configure Database Connection**

   The application automatically creates tables on first run. However, you need to configure database credentials.
   
   **Option 1: Environment Variables (Recommended)**
   
   Create a `.env` file in the App directory:
   ```env
   RESUME_DB_HOST=localhost
   RESUME_DB_USER=root
   RESUME_DB_PASSWORD=your_password
   RESUME_DB_NAME=cv
   RESUME_DB_ENABLED=1
   ```
   
   **Option 2: Edit App.py directly**
   
   Open `App/App.py` and modify the database connection (around line 121-126):
   ```python
   connection = pymysql.connect(
       host=os.getenv("RESUME_DB_HOST", "localhost"),
       user=os.getenv("RESUME_DB_USER", "root"),
       password=os.getenv("RESUME_DB_PASSWORD", "your_mysql_password"),
       db=os.getenv("RESUME_DB_NAME", "cv"),
   )
   ```

#### Step 6: Replace pyresparser File (Important!)

The project includes a custom `resume_parser.py` file that needs to be copied to the pyresparser package:

**For Windows:**
```bash
copy pyresparser\resume_parser.py venvapp\Lib\site-packages\pyresparser\resume_parser.py
```

**For macOS/Linux:**
```bash
cp pyresparser/resume_parser.py venvapp/lib/python3.9/site-packages/pyresparser/resume_parser.py
```

**Note:** Replace `python3.9` with your Python version if different.

#### Step 7: Verify Installation

Ensure you're in the App directory with the virtual environment activated, then run:

```bash
streamlit run App.py
```

The application should start and open in your default web browser at `http://localhost:8501`.

---

## 🚀 Usage Instructions

### For Users

1. **Access the Application**
   - Open your browser and navigate to `http://localhost:8501`
   - Select "User" from the sidebar

2. **Fill Personal Information**
   - Enter your name (required)
   - Enter your email (required)
   - Enter your mobile number (required)

3. **Upload Resume**
   - Click "Choose your Resume" button
   - Select a PDF file from your computer
   - Wait for the analysis to complete (usually 4-5 seconds)

4. **View Results**
   - **Basic Info**: Your extracted personal information
   - **Experience Level**: Your predicted experience level
   - **Skills**: Current skills detected in your resume
   - **Skill Recommendations**: Suggested skills to improve
   - **Course Recommendations**: Relevant courses for skill development
   - **Resume Tips**: Actionable tips to improve your resume
   - **Resume Score**: Your overall resume score (0-100)
   - **Videos**: Resume writing and interview preparation videos

5. **Use Recommendations**
   - Review recommended skills and consider adding them
   - Explore suggested courses for skill development
   - Implement resume tips to improve your score
   - Re-upload your updated resume to track improvements

### For Administrators

1. **Login**
   - Select "Admin" from the sidebar
   - Username: `admin`
   - Password: `admin@resume-analyzer`

2. **View User Data**
   - Access comprehensive user data table
   - View all uploaded resumes and analysis results
   - Download data as CSV for external analysis

3. **Analytics Dashboard**
   - Explore interactive pie charts for:
     - User ratings distribution
     - Predicted job fields
     - Experience levels
     - Resume scores
     - Geographic distribution (city, state, country)
     - User activity

4. **Feedback Management**
   - View all user feedback
   - Analyze user satisfaction
   - Export feedback data

### For Feedback Submission

1. **Submit Feedback**
   - Select "Feedback" from the sidebar
   - Fill in your name and email
   - Rate the application (1-5 stars)
   - Add comments (optional)
   - Click "Submit"

2. **View Analytics**
   - See overall ratings distribution
   - View past user comments
   - Analyze feedback trends

---

## 📁 Project Structure

```
AI-Resume-Analyzer/
│
├── App/                          # Main application directory
│   ├── App.py                    # Main application file
│   ├── Courses.py                # Course recommendations data
│   ├── requirements.txt          # Python dependencies
│   ├── Logo/                     # Application logos
│   │   ├── RESUM.png
│   │   └── recommend.png
│   ├── Uploaded_Resumes/         # User uploaded resumes storage
│   │   └── Analyzer Test Resume .pdf
│   └── .venv/                    # Virtual environment (gitignored)
│
├── pyresparser/                  # Custom pyresparser module
│   └── resume_parser.py           # Custom resume parser implementation
│
├── screenshots/                  # Application screenshots
│   ├── admin/                    # Admin interface screenshots
│   ├── feedback/                 # Feedback module screenshots
│   ├── user/                     # User interface screenshots
│   └── RESUME.png                # Main screenshot
│
├── README.md                     # This file
├── LICENSE                       # License file
└── RESUME ANALYSER SYNOPSIS.pdf  # Project synopsis document
```

### Key Files Explanation

- **App.py**: Main application file containing all Streamlit logic, database operations, and UI components
- **Courses.py**: Contains curated lists of courses for different domains (Data Science, Web Development, Android, iOS, UI/UX)
- **requirements.txt**: Lists all Python packages required for the project
- **resume_parser.py**: Custom implementation of resume parsing logic
- **Uploaded_Resumes/**: Directory where user-uploaded PDF files are stored

---

## 🔧 How It Works

### Resume Processing Pipeline

1. **PDF Upload**
   - User uploads PDF file through Streamlit file uploader
   - File is saved to `Uploaded_Resumes/` directory
   - PDF is displayed in an embedded viewer

2. **Text Extraction**
   - PDF is processed using pdfminer3
   - Text content is extracted from all pages
   - Document structure is analyzed

3. **Resume Parsing**
   - pyresparser analyzes the extracted text
   - Uses NLP techniques to identify:
     - Personal information (name, email, phone)
     - Education details
     - Skills and keywords
     - Work experience indicators
     - Projects and achievements

4. **Skill Analysis**
   - Extracted skills are compared against predefined keyword lists:
     - **Data Science**: tensorflow, keras, pytorch, machine learning, etc.
     - **Web Development**: react, django, node.js, php, laravel, etc.
     - **Android Development**: android, flutter, kotlin, xml, etc.
     - **iOS Development**: ios, swift, xcode, objective-c, etc.
     - **UI/UX Design**: figma, adobe xd, wireframes, prototyping, etc.

5. **Role Prediction**
   - System matches user skills against domain keywords
   - Predicts the most suitable job role
   - Determines experience level (Fresher/Intermediate/Experienced)

6. **Recommendation Generation**
   - **Skills**: Suggests relevant skills based on predicted role
   - **Courses**: Recommends courses from curated lists in Courses.py
   - **Tips**: Provides actionable resume improvement suggestions

7. **Resume Scoring**
   - Analyzes resume for key sections
   - Calculates score based on presence of:
     - Objective/Summary
     - Education
     - Experience
     - Internships
     - Skills
     - Hobbies/Interests
     - Achievements
     - Certifications
     - Projects

8. **Data Storage**
   - All analysis results are stored in MySQL database
   - Geographic data is captured using geocoding APIs
   - System information is logged for analytics

9. **Visualization**
   - Results are displayed using Streamlit components
   - Interactive charts are generated using Plotly
   - Data tables are displayed using pandas DataFrames

---

## 📚 API Documentation

### Core Functions

#### `pdf_reader(file)`
Extracts text content from PDF file.

**Parameters:**
- `file` (str): Path to PDF file

**Returns:**
- `text` (str): Extracted text content

**Usage:**
```python
text = pdf_reader('path/to/resume.pdf')
```

#### `show_pdf(file_path)`
Displays PDF in Streamlit interface.

**Parameters:**
- `file_path` (str): Path to PDF file

**Returns:**
- HTML iframe for PDF display

#### `insert_data(...)`
Inserts user data into MySQL database.

**Parameters:**
- Multiple parameters including user info, resume data, predictions, recommendations

**Returns:**
- None (commits to database)

#### `insertf_data(...)`
Inserts feedback data into MySQL database.

**Parameters:**
- `feed_name` (str): Feedback provider name
- `feed_email` (str): Feedback provider email
- `feed_score` (str): Rating (1-5)
- `comments` (str): Feedback comments
- `Timestamp` (str): Timestamp

#### `course_recommender(course_list)`
Recommends courses based on user's predicted role.

**Parameters:**
- `course_list` (list): List of courses for specific domain

**Returns:**
- `rec_course` (list): Recommended courses

#### `get_csv_download_link(df, filename, text)`
Generates download link for CSV file.

**Parameters:**
- `df` (DataFrame): pandas DataFrame
- `filename` (str): CSV filename
- `text` (str): Link text

**Returns:**
- HTML download link

---

## 🎯 Features in Detail

### User Module Features

#### 1. Resume Upload & Display
- **File Format Support**: PDF only (most common resume format)
- **File Size**: Handles standard resume PDFs (typically 1-5 pages)
- **Preview**: Embedded PDF viewer for immediate preview
- **Storage**: Automatic storage in `Uploaded_Resumes/` directory

#### 2. Information Extraction
- **Personal Details**: Name, email, contact number
- **Education**: Degree information
- **Skills**: Technical and soft skills identification
- **Experience Indicators**: Detects work experience mentions
- **Page Count**: Automatic page counting

#### 3. Experience Level Prediction
The system classifies users into three categories:
- **Fresher**: No experience or internship mentioned
- **Intermediate**: Internship experience mentioned
- **Experienced**: Work experience or professional experience mentioned

**Algorithm:**
```python
if 'INTERNSHIP' in resume_text:
    level = "Intermediate"
elif 'EXPERIENCE' in resume_text or 'WORK EXPERIENCE' in resume_text:
    level = "Experienced"
else:
    level = "Fresher"
```

#### 4. Job Role Prediction
Supported job roles:
- **Data Science**: Machine Learning, Data Analysis, AI
- **Web Development**: Full-stack, Frontend, Backend
- **Android Development**: Mobile app development (Android)
- **iOS Development**: Mobile app development (iOS)
- **UI/UX Development**: User interface and user experience design

**Prediction Algorithm:**
- Matches user skills against predefined keyword lists for each domain
- Returns the first matching domain based on skill priority
- Provides domain-specific recommendations

#### 5. Skill Recommendations
For each domain, the system suggests industry-relevant skills:

**Data Science:**
- Data Visualization, Predictive Analysis, Statistical Modeling
- Data Mining, Clustering & Classification, Data Analytics
- ML Algorithms, Keras, Pytorch, Tensorflow, Flask, Streamlit

**Web Development:**
- React, Django, Node JS, PHP, Laravel, Magento
- WordPress, Javascript, Angular JS, Flask, SDK

**Android Development:**
- Android, Flutter, Kotlin, XML, Java, Kivy, GIT, SDK, SQLite

**iOS Development:**
- IOS, Swift, Cocoa, Xcode, Objective-C, SQLite
- Plist, StoreKit, UI-Kit, AV Foundation, Auto-Layout

**UI/UX Development:**
- UI, User Experience, Adobe XD, Figma, Zeplin
- Balsamiq, Prototyping, Wireframes, Adobe Photoshop
- Illustrator, After Effects, Premier Pro, User Research

#### 6. Course Recommendations
- **Curated Lists**: Pre-selected high-quality courses for each domain
- **Multiple Sources**: Courses from Udemy, Coursera, YouTube, LinkedIn Learning
- **Customizable Count**: Users can select number of recommendations (1-10)
- **Randomized**: Courses are shuffled for variety

#### 7. Resume Scoring System
Detailed scoring breakdown:

| Section | Points | Importance |
|---------|--------|------------|
| Projects | 19 | High |
| Experience | 16 | High |
| Achievements | 13 | Medium-High |
| Education | 12 | Medium-High |
| Certifications | 12 | Medium-High |
| Skills | 7 | Medium |
| Objective/Summary | 6 | Medium |
| Internships | 6 | Medium |
| Interests | 5 | Low-Medium |
| Hobbies | 4 | Low |

**Scoring Algorithm:**
- Checks for presence of each section in resume text
- Uses case-insensitive matching
- Accumulates points for each found section
- Displays progress bar and final score

#### 8. Video Recommendations
- **Resume Writing Videos**: Curated YouTube videos on resume writing
- **Interview Preparation**: Videos on interview tips and techniques
- **Random Selection**: Different videos shown on each analysis

#### 9. Geographic Data Collection
- **IP-based Location**: Uses geocoder library
- **Reverse Geocoding**: Converts coordinates to address
- **Data Captured**: City, State, Country, Latitude/Longitude
- **Privacy**: Only general location, not exact address

### Admin Module Features

#### 1. User Data Management
- **Comprehensive Table**: All user data in searchable table
- **Columns Included**:
  - User identification (ID, Token, IP Address)
  - Personal information (Name, Email, Mobile)
  - Resume data (Score, Pages, File Name)
  - Predictions (Field, Level, Skills)
  - Recommendations (Skills, Courses)
  - Geographic data (City, State, Country)
  - System information (OS, Hostname)

#### 2. Data Export
- **CSV Download**: One-click download of all user data
- **Format**: Standard CSV format compatible with Excel
- **Use Cases**: External analysis, reporting, data science projects

#### 3. Analytics Visualizations
Interactive pie charts for:
- **Ratings Distribution**: User satisfaction analysis
- **Predicted Fields**: Most popular job roles
- **Experience Levels**: User experience breakdown
- **Resume Scores**: Score distribution analysis
- **Geographic Distribution**: User location analytics
- **Activity Tracking**: Usage patterns by IP address

#### 4. Feedback Analytics
- **Rating Charts**: Visual representation of feedback ratings
- **Comment History**: All user comments in tabular format
- **Trend Analysis**: Track feedback over time

### Feedback Module Features

#### 1. Feedback Form
- **Simple Interface**: Easy-to-use form
- **Required Fields**: Name, Email, Rating
- **Optional Fields**: Comments
- **Validation**: Basic input validation

#### 2. Rating System
- **Scale**: 1-5 stars
- **Slider Input**: Intuitive slider for rating selection
- **Storage**: Ratings stored in database for analytics

#### 3. Feedback Analytics
- **Pie Chart**: Visual distribution of ratings
- **Comment Display**: All comments in tabular format
- **Historical Data**: Track feedback trends

---

## 🌍 Scope and Applications

### Use Cases

1. **For Job Seekers**
   - Improve resume quality
   - Identify skill gaps
   - Get personalized career recommendations
   - Track resume improvement over time

2. **For Educational Institutions**
   - Pre-placement resume analysis
   - Student skill assessment
   - Career counseling support
   - Placement preparation

3. **For Recruiters/HR**
   - Resume screening support
   - Candidate skill assessment
   - Analytics on job market trends
   - Understanding candidate distribution

4. **For Career Counselors**
   - Resume quality assessment
   - Skill gap identification
   - Career path recommendations
   - Student progress tracking

5. **For Organizations**
   - Applicant data analytics
   - Skill trend analysis
   - Geographic distribution insights
   - Resume quality benchmarking

### Business Applications

- **Recruitment Agencies**: Automated resume screening
- **Corporate HR**: Candidate assessment tools
- **Educational Platforms**: Student career guidance
- **Training Institutes**: Skill gap analysis
- **Government Agencies**: Employment analytics

### Future Scope

- Support for more job domains (DevOps, Cloud, Blockchain, etc.)
- Multi-language resume support
- Integration with job portals
- Advanced ML models for better predictions
- Mobile app development
- API development for third-party integrations

---

## 🔍 Troubleshooting

### Common Issues and Solutions

#### 1. **MySQL Connection Error**

**Error:**
```
pymysql.err.OperationalError: (2003, "Can't connect to MySQL server")
```

**Solutions:**
- Ensure MySQL server is running
- Check database credentials in App.py
- Verify database 'cv' exists
- Check firewall settings
- Try connecting with MySQL Workbench first

#### 2. **GeocoderUnavailable Error**

**Error:**
```
geocoder.exceptions.GeocoderUnavailable: Service unavailable
```

**Solutions:**
- Check internet connection
- Wait and retry (API rate limits)
- The application will continue without location data
- This is not a critical error

#### 3. **spaCy Model Not Found**

**Error:**
```
OSError: Can't find model 'en_core_web_sm'
```

**Solutions:**
```bash
python -m spacy download en_core_web_sm
```
If this doesn't work:
```bash
python -m spacy download en_core_web_sm --user
```

#### 4. **PDF Parsing Errors**

**Error:**
```
Error parsing PDF or extracting text
```

**Solutions:**
- Ensure PDF is not password-protected
- Check if PDF contains selectable text (not just images)
- Try with a different PDF
- Verify PDF is not corrupted

#### 5. **Module Import Errors**

**Error:**
```
ModuleNotFoundError: No module named 'X'
```

**Solutions:**
- Ensure virtual environment is activated
- Reinstall requirements: `pip install -r requirements.txt`
- Check Python version (should be 3.9.12)
- Verify all dependencies are installed

#### 6. **Port Already in Use**

**Error:**
```
Port 8501 is already in use
```

**Solutions:**
- Close other Streamlit applications
- Use different port: `streamlit run App.py --server.port 8502`
- Kill process using port 8501

#### 7. **Database Table Creation Errors**

**Error:**
```
Table creation failed
```

**Solutions:**
- Check database user permissions
- Verify database connection
- Ensure database 'cv' exists
- Check MySQL server logs

#### 8. **Windows Path Issues**

**Error:**
```
Path-related errors on Windows
```

**Solutions:**
- Use forward slashes in paths: `App/Logo/image.png`
- Or use raw strings: `r"C:\path\to\file"`
- Check file permissions

### Performance Optimization

1. **Slow Resume Processing**
   - Reduce PDF file size
   - Limit number of pages
   - Close other applications

2. **Database Query Slow**
   - Add indexes to frequently queried columns
   - Limit data retrieval
   - Use pagination for large datasets

3. **Memory Issues**
   - Close unused applications
   - Increase system RAM if possible
   - Process resumes one at a time

### Getting Help

If you encounter issues not covered here:
1. Check the [GitHub Issues](https://github.com/deepakpadhi986/AI-Resume-Analyzer/issues)
2. Review the installation video: [Installation Guide](https://youtu.be/WFruijLC1Nc)
3. Email for support: [dnoobnerd@gmail.com](mailto:dnoobnerd@gmail.com)

---

## 🗺 Roadmap

### Completed Features ✅
- [x] Resume parsing and text extraction
- [x] Experience level prediction
- [x] Job role prediction (5 domains)
- [x] Skill recommendations system
- [x] Course recommendations
- [x] Resume scoring algorithm
- [x] Database integration
- [x] Admin dashboard with analytics
- [x] Feedback system
- [x] Geographic data collection
- [x] CSV export functionality
- [x] Video recommendations

### Planned Features 🚧
- [ ] Support for more job domains (DevOps, Cloud, Data Engineering, etc.)
- [ ] Individual user profile view
- [ ] Resume comparison feature
- [ ] ATS (Applicant Tracking System) optimization
- [ ] Multi-language resume support
- [ ] Enhanced ML models for better predictions
- [ ] Real-time collaboration features
- [ ] Mobile app version
- [ ] REST API development
- [ ] Integration with job portals
- [ ] Advanced analytics dashboard
- [ ] Resume templates library
- [ ] Automated resume generation
- [ ] Email notifications
- [ ] User authentication system

### Future Enhancements 🔮
- Machine Learning model improvements
- Natural Language Generation for resume writing
- Integration with LinkedIn API
- AI-powered interview preparation
- Career path prediction
- Salary estimation based on skills
- Skill demand analysis
- Industry trend insights

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Contribution Guidelines

1. **Fork the Repository**
   ```bash
   git clone https://github.com/ctcw7k88zn-lab/aqib-project.git
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **Make Your Changes**
   - Follow the existing code style
   - Add comments for complex logic
   - Update documentation if needed
   - Test your changes thoroughly

4. **Commit Your Changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

5. **Push to Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```

6. **Open a Pull Request**
   - Describe your changes clearly
   - Reference any related issues
   - Include screenshots if UI changes

### Areas for Contribution

- **New Features**: Add support for more job domains
- **Bug Fixes**: Fix existing issues
- **Documentation**: Improve README, add code comments
- **Testing**: Add unit tests and integration tests
- **UI/UX**: Improve user interface and experience
- **Performance**: Optimize code and database queries
- **Security**: Improve security measures

### Code Style

- Follow PEP 8 Python style guide
- Use meaningful variable names
- Add docstrings to functions
- Keep functions focused and small
- Comment complex algorithms

---

## 📸 Preview

### Client Side

**Main Screen**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/1-main-screen.png?raw=true)

**Resume Analysis**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/2-analysis.jpg?raw=true)

**Skill Recommendation**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/3-recom.png?raw=true)

**Course Recommendation**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/4-recom.png?raw=true)

**Tips and Overall Score**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/5-tipsscore.png?raw=true)

**Video Recommendation**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/6-recom.png?raw=true)

### Feedback

**Feedback Form**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/feedback/1-form.png?raw=true)

**Overall Rating Analysis and Comment History**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/feedback/2-analytics.png?raw=true)

### Admin

**Login**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/1-main-screen.png?raw=true)

**User Count and Data**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/2-user-data.png?raw=true)

**Exported CSV File**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/3-user-datacsv.png?raw=true)

**Feedback Data**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/4-feed-data.png?raw=true)

**Pie Chart Analytical Representation**
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/5-pieexp.png?raw=true)
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/6-piescre.jpg?raw=true)
![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/7-pielocation.png?raw=true)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

### Inspiration and Learning Resources

- **[Dr Bright](https://www.linkedin.com/in/mrbriit/)** - [The Full Stack Data Scientist BootCamp](https://www.udemy.com/course/the-full-stack-data-scientist-bootcamp/)
- **[Resume Parser with Natural Language Processing](https://www.academia.edu/32543544/Resume_Parser_with_Natural_Language_Processing)** - Research paper that inspired this project
- **[pyresparser](https://github.com/OmkarPathak/pyresparser)** - Excellent resume parsing library by Omkar Pathak

### Libraries and Tools

- **Streamlit** - For the amazing web framework
- **pandas** - For data manipulation
- **Plotly** - For beautiful visualizations
- **NLTK & spaCy** - For NLP capabilities
- **PyMySQL** - For database connectivity
- **pdfminer3** - For PDF processing

### Contributors

- **[Deepak Padhi](https://dnoobnerd.netlify.app/)** - Project Creator and Maintainer
- All contributors who have helped improve this project

---

## 📞 Contact and Support

### Project Maintainer
- **Name**: Deepak Padhi
- **Website**: [dnoobnerd.netlify.app](https://dnoobnerd.netlify.app/)
- **Email**: [dnoobnerd@gmail.com](mailto:dnoobnerd@gmail.com)

### Support
- **Issues**: [GitHub Issues](https://github.com/deepakpadhi986/AI-Resume-Analyzer/issues)
- **Installation Video**: [YouTube Tutorial](https://youtu.be/WFruijLC1Nc)
- **Project Report**: Email for the complete project report

### Academic Information
- **Institution**: Kirti M. Doongursee College
- **Course**: B.Sc Computer Science
- **Academic Year**: 2022-23
- **Project Type**: Final Year Project (5th Semester)

---

<div align="center">

### ⭐ Star this repository if you found it helpful! ⭐

**Built with 🤍 by [Deepak Padhi](https://dnoobnerd.netlify.app/)**

[![GitHub stars](https://img.shields.io/github/stars/deepakpadhi986/AI-Resume-Analyzer.svg?style=social&label=Star)](https://github.com/deepakpadhi986/AI-Resume-Analyzer)
[![GitHub forks](https://img.shields.io/github/forks/deepakpadhi986/AI-Resume-Analyzer.svg?style=social&label=Fork)](https://github.com/deepakpadhi986/AI-Resume-Analyzer/fork)

</div>
