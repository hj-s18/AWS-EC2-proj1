# Mood Journal Project

A mood journal application built with Flask that allows users to write diary entries with mood selection, share entries with friends or family, and manage privacy settings.

## Getting Started

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd mood_journal_project

2. Environment Setup
Create a .env file in the root directory and add the following configuration:
   ```bash
   DB_HOST=proj-rds-db.c0k8gjmf4fb9.us-east-2.rds.amazonaws.com
   DB_USER=admin
   DB_PASSWORD=test1234!
   DB_NAME=proj_database
   DB_CHARSET=utf8

3. Installation
Install the required dependencies:

   ```bash
   pip install -r requirements.txt

4. Running the Server
   ```bash
   python run.py
The application will be available at http://3.143.22.51:5000
