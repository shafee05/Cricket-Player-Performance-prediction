## Model Training
Models such as Decision Tree and LightGBM can be trained using the notebook provided in `/notebooks/`.
To keep the repository lightweight and secure, pre-trained `.pkl` files are not included.

You can generate your own using:

```python
import joblib
joblib.dump(model, 'decision_tree_model.pkl')
