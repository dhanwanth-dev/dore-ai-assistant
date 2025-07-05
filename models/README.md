# Models Directory

This directory contains the Vosk speech recognition models required for DORE-AI.

## Required Models

### vosk-model-en-in-0.5
- **Purpose**: Primary English-Indian speech recognition model
- **Size**: ~1.5GB
- **Download**: [Vosk Models](https://alphacephei.com/vosk/models)
- **URL**: https://alphacephei.com/vosk/models/vosk-model-en-in-0.5.zip

### vosk-model-small-en-in-0.4 (Optional)
- **Purpose**: Smaller, faster model for limited resources
- **Size**: ~40MB
- **Download**: [Vosk Models](https://alphacephei.com/vosk/models)
- **URL**: https://alphacephei.com/vosk/models/vosk-model-small-en-in-0.4.zip

## Installation Instructions

1. Download the required model(s) from the links above
2. Extract the downloaded zip file
3. Place the extracted folder in this `models/` directory
4. Ensure the folder structure matches:
   ```
   models/
   ├── vosk-model-en-in-0.5/
   │   ├── am/
   │   ├── conf/
   │   ├── graph/
   │   ├── ivector/
   │   ├── rescore/
   │   └── README
   └── vosk-model-small-en-in-0.4/ (optional)
   ```

## Note

The models are not included in the repository due to their large size. You must download them separately for the application to work properly.
