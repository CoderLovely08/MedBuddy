# MedBuddy

## Prerequisites

- Python (version ^3.6)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/CoderLovely08/MedBuddy.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd medbuddy
   ```

3. **Create and activate a virtual environment (optional):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   .\venv\Scripts\activate   # For Windows
   ```

4. **Install project dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Database Migration

1. **Initialize the database migration:**

   ```bash
   flask db init
   ```

2. **Create an initial migration script:**

   ```bash
   flask db migrate -m "Initial migration"
   ```

3. **Apply the migration to create the database tables:**

   ```bash
   flask db upgrade
   ```

## Running the Application

1. **Start the Flask development server:**

   ```bash
   flask run
   ```

2. **Open your browser and navigate to [http://localhost:5000](http://localhost:5000).**