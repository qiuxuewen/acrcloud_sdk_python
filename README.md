# acrcloud_sdk_python
create "ACRCloud Fingerprint" by Audio/Video file, and use "ACRCloud Fingerprint" to recognize metainfos by "ACRCloud webapi".

# Overview
This module can recognize ACRCloud by most of audio/video file.
      Audio: mp3, wav, m4a, flac, aac, amr, ape, ogg ...
      Video: mp4, mkv, wmv, flv, ts, avi ...
      
# Functions
recognizer.py
1. recognize_by_file(file_path, start_seconds)
      @param file_path : query file path
      @param start_seconds : skip (start_seconds) seconds from from the beginning of (filePath)
      @return result metainfos

