# WhatsApp Chat Analyzer

WhatsApp Chat Analysis is a web application that provides in-depth insights into WhatsApp conversations. By uploading an exported chat file, users can receive detailed analytics, including message counts, media sharing, activity trends, and more. This project can analyze both personal chats and group conversations.

## Features

- **Total Messages and Words**: Displays the total number of messages and words exchanged.
- **Media and Links Shared**: Counts the total media files and links shared in the chat.
- **Monthly Timeline**: Graph showing monthly activity trends.
- **Daily Timeline**: Graph showing daily message exchange trends.
- **Activity Map**:
  - **Most Busy Day**: Identifies the day with the highest activity.
  - **Most Busy Month**: Identifies the month with the highest activity.
- **Weekly Activity Heatmap**: Heatmap of hourly activity for each day of the week.
- **Most Active Users** (for group chats): Graph of message counts per user.
- **Commonly Used Words**: Visualization of the most frequently used words.
- **Emoji Analysis**: Pie chart showing the most commonly used emojis.

## Project Structure

- **app.py**: Main Flask application file that runs the server.
- **helper.py**: Contains utility functions to support data processing and analysis.
- **preprocessor.py**: Handles preprocessing of the WhatsApp chat data.
- **Procfile**: Defines process types for deployment on platforms like Heroku.
- **requirements.txt**: Lists the dependencies required to run the project.
- **setup.sh**: Script for setting up environment configurations.
- **stop_hinglish.txt**: Contains stop words for "Hinglish" (Hindi-English) text filtering.

## Getting Started

To set up and run the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Moksh91119/whatsapp-chat-analyzer.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd whatsapp-chat-analyzer
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    python app.py
    ```

5. **Access the application**:
    Open your browser and go to `http://localhost:5000` to start using the WhatsApp Chat Analysis app.

## Usage

1. **Export and Download WhatsApp Chat**: Export the WhatsApp chat (either individual or group) in `.txt` format.
2. **Upload Chat File**: Upload the `.txt` file on the app's homepage.
3. **Analyze**:
   - For group chats, select the group members you want to analyze.
   - Click "Show Analysis" to view the statistics, graphs, and insights.

## Contact

If you have any questions or need further assistance, feel free to contact me:

- **Email**: [jainmoksh03@gmail.com](mailto:jainmoksh03@gmail.com)
- **Portfolio**: [itsmemoksh.in](https://itsmemoksh.in/) - Explore my other projects!

---

Contributions and feedback are welcome! Feel free to open issues or submit pull requests.
