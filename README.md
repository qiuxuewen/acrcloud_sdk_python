# acrcloud_sdk_python
create "ACRCloud Fingerprint" by Audio/Video file, and use "ACRCloud Fingerprint" to recognize metainfos by "ACRCloud webapi".

# Overview
This module can recognize ACRCloud by most of audio/video file.
      Audio: mp3, wav, m4a, flac, aac, amr, ape, ogg ...
      Video: mp4, mkv, wmv, flv, ts, avi ...
      
# Functions
Introduction all API.
## recognizer.py
```python
class ACRCloudRecognizer:
    def recognize_by_file(self, file_path, start_seconds)
      #@param file_path : query file path
      #@param start_seconds : skip (start_seconds) seconds from from the beginning of (filePath)
      #@return result metainfos
      
    def recognize_by_filebuffer(self, file_buffer, start_seconds)
      #@param file_buffer : file_path query buffer
      #@param start_seconds : skip (start_seconds) seconds from from the beginning of (filePath)
      #@return result metainfos
      
    def recognize(self, wav_audio_buffer):
      #@param wav_audio_buffer : query buffer(RIFF (little-endian) data, WAVE audio, Microsoft PCM, 16 bit, mono 8000 Hz)
      #@return result metainfos
```

