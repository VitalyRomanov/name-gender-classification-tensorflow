Implements a character level model in tensorflow that performs name gender classification.

### Data

Two datasets are provided. 

`train_eng.csv` and `test_eng.csv` is the data with English names and associated genders.

`train_rus.csv` and `test_rus.csv` contain similar data for with Russian names.

### Architecture

The script implements a simple model with one layer LSTM followed by a single dense layer. On English Names data the model achieves accuracy of 80%. There is a noticeable reduction in accuracy for shoeter names.

### Running the Training Script

Model only works in training mode. To run the training excecute

```bash
python main.py train_eng.csv test_eng.csv
```

