# Defective_Tires
Classifying Defective Tires and Good Tires by using CNN and TL(MobileNetV2)

| Metrics     | TL   | CNN  |
|-------------|------|------|
| Precision   | 0.90 | 0.59 |
| Recall      | 0.88 | 0.58 |
| F1-Score    | 0.88 | 0.58 |
| Accuracy    | 0.88 | 0.56 |


<br>for using .h5 
```python
from keras.models import model_from_json
with open("name.json") as json_file:
    model = model_from_json(json_file.read())
    model.load_weights("name.h5")
