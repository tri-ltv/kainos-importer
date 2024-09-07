# 🛠️ API Request App - Quick Guide
## How to Use
### 1. 🔑 Enter Login Credentials & URL

- Email: Input your email.
- Password: Enter your password.
- URL: Specify the POST request URL (default: https://api-dev.hnv.vvnst.com/api/common/v1/common-messages/import).
- Click "Save to LocalStorage" to store these details for future use.

### 2. 📋 Switch Tabs

- **Tab 1** - `Key-Value Importer`:
    - Add key-value pairs. New rows will appear automatically.
    - Click "Submit Key-Value Data" to convert these pairs into JSON and submit.

- **Tab 2** - `JSON Importer`:
    - Paste or type your JSON object.
    - Click "Submit JSON Data" to send the JSON data.

### 3. 🚀 Submit Data
The app logs in using your email and password, retrieves a Bearer token, formats your data, and sends it to the specified URL.

### 4. 📥 Check Response
The server's response will appear below the form.
If errors occur, you'll see appropriate error messages.