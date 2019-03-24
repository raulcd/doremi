# DOREMI

Test app to say do speech to text recognition for musical notes.

Following the tutorial on [realpython](https://realpython.com/python-speech-recognition/)

## Issues found

No matter the language is set to spanish, `do` gets recognised as `dog`.
Some sounds like `fa` seem to extend the mic capture for a really long time, should look into close capture after some time.

# Other things to check:

- https://github.com/GoogleCloudPlatform/python-docs-samples/tree/master/speech/microphone
- https://cloud.google.com/speech-to-text/docs/streaming-recognize#speech-streaming-mic-recognize-python
