##AVVAI - AI integrated Voice Bot  
The Voice Assistant Program is a Python application that utilizes the OpenAI API, speech recognition, and text-to-speech capabilities to create a simple voice-controlled assistant. This program allows you to have a text-based conversation with an AI assistant using voice input and output. The assistant can respond to your voice commands, answer questions, and engage in natural language conversations. <br><br>
#FEATURES:
Real-time voice input and output using the `speech_recognition` and `pyttsx3` libraries. <br>
Integration with the OpenAI API for generating AI responses using the GPT-3.5 Turbo model. <br>
User-friendly graphical user interface (GUI) using the `tkinter` library. <br>
Responsive conversation display with automatic scrolling as the chat continues. <br>
Ability to start and stop the voice conversation using buttons in the GUI. <br><br>
#PREREQUISTES: <br>
Obtain an API key from OpenAI and replace "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" with your actual API key in the code. <br>
Install the required Python libraries using the following command:  	pip install openai speech_recognition pyttsx3  <br>
Ensure you have a microphone connected to your system for voice input. <br><br>
#USAGE: <br>
1. Run the program by executing the Python script: python voice_assistant.py <br>
2. The GUI window will open, displaying the voice assistant interface. <br>
3. Click the "Start" button to begin the voice conversation with the assistant. You can speak your commands or questions. <br>
4. Click the "Stop" button to pause the voice conversation. You can resume by clicking the "Start" button again. <br>
5. The assistant will generate responses to your voice input and display the conversation in the text area. <br>
6. To end the conversation, you can say one of the predefined stop phrases (e.g., "bye bye gpt") or use the "Stop" button. The program will display a message indicating that listening has been stopped. <br><br>
#LIMITATIONS: <br>
The accuracy of voice recognition depends on the clarity of your speech and the quality of your microphone. <br>
The assistant's responses are generated based on the GPT-3.5 Turbo model and may not always provide accurate or relevant answers. <br>
#CREDITS: <br><br>
This program was developed using the OpenAI API for natural language processing. <br>
The `speech_recognition` library was used for voice recognition. <br>
The `pyttsx3` library was used for text-to-speech output. <br>
The `tkinter` library was used for the graphical user interface. <br>
