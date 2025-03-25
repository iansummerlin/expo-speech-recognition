# 🎙️ expo-speech-recognition (with reset)

Forked from https://github.com/jamsch/expo-speech-recognition (fantastic package)

Needed a way to reset result event emitted from the useSpeechRecognition hook in the original package. Web not supported.

## Usage

```typescript
// import
import { ExpoSpeechRecognitionModule } from "expo-speech-recognition";

// execute
ExpoSpeechRecognitionModule.reset();
```
