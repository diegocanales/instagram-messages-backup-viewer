# Instagram Messages Backup Viewer

This is a simple backup viewer for Instagram messages. It allows you to visualize and explore your Instagram message backups on your local machine.

## Project Structure

The project expects the following structure for the Instagram message backup files:

```
├── followers_and_following
├── ...
└── messages
    ├── broadcast
    ├── inbox
    ├── message_requests
    └── secret_conversations.json
```

Ensure that your backup files are organized according to this structure before running the viewer.

## Usage

1. Place the backup files in the root directory of the project, following the provided structure.

2. Start a local server to run the viewer. You can use Python's built-in HTTP server with the following command:

   ```shell
   python3 -m http.server 8000
   ```

3. This will start a server on http://localhost:8000.

4. Open your web browser and navigate to http://localhost:8000/chat.html to access the Instagram Messages Backup Viewer.

5. Use the provided input field to enter the path of the JSON file you want to load, or leave it empty to load the default file.

6. Click the "Load" button to load and display the conversation.

### Important Note

Make sure to keep the structure of the backup files intact and follow the instructions mentioned above to ensure the proper functioning of the Instagram Messages Backup Viewer.

Feel free to customize and enhance the viewer as per your requirements.

Happy exploring!
