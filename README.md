An elegant solution that operates seamlessly across any window or application can be invaluable, particularly when artificial intelligence tools, such as instant messaging, are restricted due to corporate privacy requirements.

Overview: The process operates on my Windows 11 computer as follows:

1. A key press on my mouse is programmed with a hotkey.
2. This hotkey triggers a MacroExpress macro to copy any highlighted text.
3. The copied text is then passed to a Golang script, which completes the API call to ChatGPT.
4. The returned text is received by the Golang script and passed back to the macro, which then pastes the text.

If implementing this, make sure to change the "role", as that is the prompt your heading the the text with. 
