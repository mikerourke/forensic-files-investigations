# Forensic Files Investigations

This contains transcripts, speech-to-text recognitions, and entity analyses for (almost) all the Forensic Files episodes.
I'm using it for my [Forensic Files API project](https://github.com/mikerourke/forensic-files-api).
I originally had the data in the same repo, but in the interest of slimming things down and having a separate spot to dump data, I created this repo.

## Contents

Each directory contains sub-directories for corresponding seasons.

- `/recognitions`
  - JSON files containing the speech-to-text results pulled from the episode MP3's.
- `/transcripts`
  - Plain text transcripts, that are maybe 85% accurate. They are text versions of the corresponding `recognition` file. 
- `/gcp-analyses`
  - Entity analyses pulled from GCP's Natural Language Processing service.
- `/ibm-analyses`
  - Entity analyses pulled from IBM Clouds's Natural Language Understanding service.
