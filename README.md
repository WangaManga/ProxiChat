# ProxiChat

**ProxiChat** is a location-based social application that allows users to connect with others who share similar interests in their proximity. Utilizing GPS tracking, ProxiChat helps users discover people nearby with common hobbies and goals, encouraging meaningful interactions. The app includes customizable profiles, privacy settings and live feeds for enhanced user experiences.

## Features

- **User Profiles**: Create a customizable profile with details like age, ethnicity, workplace, education, and interests.
- **Interest-Based Matchmaking**: Users can find others with similar interests based on the number of shared tags.
- **Privacy Controls**: Users have control over their location visibility.
- **GPS Integration**: The app leverages GPS to show users on a map with location updates in real-time.

## Technology Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript, Leaflet.js for map rendering
- **Database**: MySQL
- **Version Control**: GitHub

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/WangaManga/ProxiChat.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ProxiChat
   ```

3. Set up a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Set up the MySQL database:
   - Create a database named `proxichat` using your MySQL client.
   - Configure the `db_config` in `proxichat.py` to match your MySQL credentials.

6. Run the Flask application:
   ```bash
   python proxichat.py
   ```

7. Open your browser and go to `http://127.0.0.1:5000/`.

## Usage

- **Profile**: Users can create and edit profiles with personal information and interests.
- **Find Users**: Users can search for others nearby who share common interests by setting filters.
- **Map**: View users on a map based on their location, with markers for those who match your interests.
- **Requests**: Interact with users through chat requests and manage communication.

## Contributing

We welcome contributions! Please feel free to fork the repository, submit issues, or open pull requests.

## License

This project is licensed under the MIT License.

---

Feel free to modify the content as per your project needs or specifics.
