# SpeechCommandNet

## Speech Command Recognition with 96.4% Accuracy

Deep learning model for recognizing spoken commands from 1-second audio clips.

## Commands Recognized
yes, no, up, down, left, right, on, off, stop, go

## Results
| Metric | Value |
|--------|-------|
| Test Accuracy | 96.4% |
| Model Size | 1.88 MB |
| Training Samples | 78,392 |

## Quick Start

```python
from tensorflow import keras
model = keras.models.load_model("SpeechCommandNet.keras")
```

## License
MIT
