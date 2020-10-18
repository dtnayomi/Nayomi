### Table of Contents

1. [Speech Cognitive Services](https://github.com/dtnayomi/Nayomi/new/main#using-speech-services-for-translation)

# Using Speech Services for Translation

```python
recognizer = tl.TranslationRecognizer(translation_config=speech_config)
```

And then use it to tanslate between different languages:

```python
print("Say something in English to be translated into Spanish and German:")

result = recognizer.recognize_once()
```

[**Visit the repository here for more**](https://github.com/LaloCo/SpeechCognitiveService_Translate)
