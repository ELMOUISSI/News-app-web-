# Flask News Application

This is a Flask-based web application that uses the NewsAPI to fetch and display news articles from various sources. The application provides multiple pages, including a main news page, category-based news pages, and a detailed view for individual articles.

---

## Features

1. **Main News Page**:
   - Displays top headlines from Al Jazeera English.
   - Includes titles, descriptions, and images of the articles.

2. **Detailed News View**:
   - Clicking on a news article redirects to a detailed page showing the full article information.

3. **Category-Based Pages**:
   - `BBC` and `Tech` pages that display news based on predefined sources and topics.

4. **Dynamic Routing**:
   - Allows navigating to individual articles using `/news/<index>`.

5. **Responsive Design**:
   - Built with Bootstrap to ensure responsiveness across devices.

---

## Prerequisites

1. **Python**: Ensure Python 3.8 or higher is installed on your system.
2. **Flask**: Install Flask and related dependencies.
3. **NewsAPI Key**: Obtain an API key from [NewsAPI](https://newsapi.org/).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/flask-news-app.git
   cd flask-news-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file for the API key:
   ```env
   NEWS_API_KEY=your_api_key_here
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open your browser and visit:
   ```
   http://127.0.0.1:5000/
   ```

---

## Project Structure

```
flask-news-app/
├── templates/
│   ├── index.html          # Main page template
│   ├── bbc.html            # BBC news page template
│   ├── news_detail.html    # Individual news detail template
├── static/
│   └── css/                # CSS files (optional for custom styles)
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## Routes

1. `/`:
   - Displays top headlines from Al Jazeera English.
2. `/news/<int:index>`:
   - Shows detailed information for a selected article.
3. `/bbc`:
   - Displays BBC news headlines.
4. `/tech`:
   - Displays technology-related news headlines.

---

## Screenshots

1. **Main Page**
   - Displays a list of articles with titles, descriptions, and images.

2. **Detailed View**
   - Shows the full details of a specific article.

---

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature.
3. Submit a pull request.

---

## Acknowledgments

- [Flask](https://flask.palletsprojects.com/) - Web framework used.
- [NewsAPI](https://newsapi.org/) - News data provider.
- [Bootstrap](https://getbootstrap.com/) - Frontend framework for styling.

