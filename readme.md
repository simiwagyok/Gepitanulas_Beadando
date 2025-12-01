Gépi tanulás beadandó (2025 évi hitelbírálat USA & Canada)

Ez a projekt egy neurális hálót valósít meg, amely képes eldönteni egy hitelkérelemről, hogy azt jóváhagyják-e vagy sem. A modell a Kaggle "Realistic Loan Approval Dataset" adatait használja.

Felhasznált technológiák:
- Python 3.x
- Pandas, Numpy (Adatfeldolgozás)
- Scikit-learn (Preprocessing)
- TensorFlow / Keras (Neurális háló)

A modell felépítése:
- Inputban 10+ feature van.
- Preprocessing: Hiányzó adatok és outlierek kiszűrése, One-Hot Encoding, StandardScaler.
- Architektúra: Neurális háló 5 rejtett réteggel (Dense).
- Regularizáció: Dropout réteg és Early Stopping alkalmazása a overfitting elkerülésére.


A modell a teszt adathalmazon 90% feletti pontosságot ért el.