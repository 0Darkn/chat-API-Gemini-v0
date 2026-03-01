# Gemini Chat API

## Gemini API with a simple chat interface.

It includes:

* **Text input** for the user's question.
* **Text output** for the Gemini API response.
* **Menu** for additional options.
* **Buttons** to send the question and exit.

---

### 📌 **Install Dependencies**

Before running the code, install the library to access the Gemini API:

```sh
pip install google-generativeai
```

### 🔍 **Code Explanation**

1. **Importing libraries**

   * `tkinter`: Creates the graphical interface.
   * `google.generativeai`: Enables communication with the Gemini API.

2. **Gemini API Configuration**

   * The program configures the API with a key [(API_KEY).](https://github.com/0joseDark/chat-API-Gemini/blob/main/API_KEY.md)

3. **Function `send_question()`**

   * Reads the text from the input box.
   * Sends the question to the Gemini API.
   * Displays the response in the output box.
   * Shows an error message if the API fails.

4. **Graphical Interface (Tkinter)**

   * **Main window** with fixed title and size.
   * **Menu** with an exit option.
   * **Input and output boxes** using `ScrolledText` for scrolling.
   * **Buttons** to send the question and close the program.

---

### ✅ **Testing the Program**

1. Insert your Gemini API key into the `API_KEY` variable.
2. Run the script.
3. Type a question and click **"Send"**.
4. The program will send the question to the Gemini API and display the response.
5. To exit, click the **"Exit"** button or the **"Options → Exit"** menu.

---
