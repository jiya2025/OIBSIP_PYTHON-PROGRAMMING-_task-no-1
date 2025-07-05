# OIBSIP_PYTHON-PROGRAMMING-_task-no-1


 🎯 **Objective:**

To develop a **basic voice assistant** using Python that can perform simple tasks like greeting the user, telling the current time/date, opening websites, searching on Google or Wikipedia, and responding to basic voice commands.

 🛠️ **Tools & Libraries Used:**

| Tool / Library       | Purpose                                |
| -------------------- | -------------------------------------- |
| `speech_recognition` | Converts speech into text              |
| `pyttsx3`            | Converts text into speech (TTS)        |
| `datetime`           | To get the current time and date       |
| `webbrowser`         | Opens websites in the browser          |
| `wikipedia`          | Fetches short summaries from Wikipedia |
| `os` / `subprocess`  | Opens system apps or files (optional)  |

> Install these via:

```bash
pip install speechrecognition pyttsx3 wikipedia
```
 📋 **Steps Performed:**

1. **Initialize the Text-to-Speech Engine**
   → The assistant greets the user with speech using `pyttsx3`.

2. **Listen to Voice Commands**
   → Using the `speech_recognition` library and microphone, it listens for user input.

3. **Convert Voice to Text**
   → The speech is recognized and converted into text.

4. **Process the Command**
   → Based on keywords in the text, it decides what action to take:

   * If the user says "Wikipedia", it searches and reads a summary.
   * If the user says "open YouTube" or "open Google", it opens the site.
   * If the user asks for the time or date, it responds appropriately.

5. **Respond with Voice Output**
   → The assistant gives a spoken response using `pyttsx3`.

 ✅ **Outcome:**

* The user can interact with the assistant **hands-free** using just voice.
* The assistant **responds intelligently** and **performs useful tasks** like:

  * Answering general knowledge questions.
  * Telling the current time/date.
  * Opening websites or searching Google/Wikipedia.
* It introduces beginners to concepts of **AI-powered voice interaction**, making it a stepping stone for more advanced projects like Alexa/Google Assistant clones.
