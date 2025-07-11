# Phishing Simulator Tool

This project is a phishing simulator tool built using Python and Flask. It is designed to educate employees about phishing attacks by simulating realistic phishing email campaigns. The tool includes features for tracking user interactions and providing feedback to improve awareness.

## Features

- Generate realistic phishing emails for educational purposes.
- Track who clicked on the phishing links and gather feedback on why they clicked.
- Display reports on user interactions with the phishing emails.
- Provide suggestions for improving awareness and preventing phishing attacks.

## Project Structure

```
phishing-simulator
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── models.py
│   ├── templates
│   │   ├── index.html
│   │   ├── report.html
│   └── static
│       ├── css
│       │   └── style.css
│       └── js
│           └── script.js
├── instance
│   └── config.py
├── requirements.txt
├── run.py
└── README.md
```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/phishing-simulator.git
   cd phishing-simulator
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Configure the application settings in `instance/config.py`.
2. Run the application:
   ```
   python run.py
   ```
3. Open your web browser and navigate to `http://127.0.0.1:5000` to access the phishing simulator tool.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.