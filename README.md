
# Flask MongoDB Application

This is a simple Flask application that connects to a MongoDB Atlas cluster and allows users to submit their information through a form. The submitted data is then stored in the MongoDB database.

## Features

- User can submit their name, email, and password through a form.
- The data is stored in a MongoDB database.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your local machine.
- MongoDB Atlas account with a cluster and database set up.
- Internet connection to connect to the MongoDB Atlas cluster.

## Installation

1. **Clone the repository:**

```sh
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

2. **Create and activate a virtual environment:**

```sh
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. **Install the required packages:**

```sh
pip install -r requirements.txt
```

4. **Set up the environment variable for MongoDB URI:**

```sh
export MONGODB_URI="mongodb+srv://yourusername:yourpassword@cluster0.mongodb.net/?retryWrites=true&w=majority&appName=yourAppName"
```

On Windows, use:

```sh
set MONGODB_URI="mongodb+srv://yourusername:yourpassword@cluster0.mongodb.net/?retryWrites=true&w=majority&appName=yourAppName"
```

## Running the Application

To run the application, execute the following command:

```sh
python mongo.py
```

The application will be accessible at `http://localhost:5000`.

## Project Structure

```plaintext
.
├── static
│   └── styles.css          # Your static files (CSS, JS, images)
├── templates
│   ├── index.html          # The form for user input
│   └── response.html       # The response page after form submission
├── mongo.py                # The main application file
├── test.py                 # The MongoDB connection test file
├── requirements.txt        # Python dependencies
└── README.md               # This file
```

## Usage

1. Navigate to `http://localhost:5000`.
2. Fill out the form with your name, email, and password.
3. Click the submit button.
4. If all fields are filled out correctly, you will be redirected to the response page.

## Contributing

To contribute to this project, please follow these steps:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the original branch: `git push origin feature/your-feature-name`.
5. Create a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

If you want to contact me, you can reach me at [achanandhi.m@gmail.com](mailto:achanandhi.m@gmail.com).
```

### Instructions

1. **Replace placeholders** such as `yourusername`, `your-repo-name`, `yourpassword`, `yourAppName`, and `your-email@example.com` with your actual information.
2. **Create a `requirements.txt` file** by running `pip freeze > requirements.txt` in your virtual environment.
3. **Push to GitHub**:

```sh
git add .
git commit -m "Initial commit"
git push origin main
```

