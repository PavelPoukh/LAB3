# LAB3 

## 1 PART

На первом этапе обучали самодельную сеть VGG16

**1. BATCH_SIZE = 8, lr=0.000001**
![Image alt](https://github.com/PavelPoukh/LAB3/blob/master/1.1.png)

**2. BATCH_SIZE = 8, lr=0.00001**
![Image alt](https://github.com/PavelPoukh/LAB3/blob/master/1.2.png)

**2 PART**

На втором этапе мы проводили обучение классификатора на предобученной на image.net сети VGG16. В данной сети были заморожены свёрточные слои и производилось обучение классификатора с последующим сохранением весовых коэффициентов.

**1. BATCH_SIZE = 8, lr=0.00001**
![Image alt](https://github.com/PavelPoukh/LAB3/blob/master/2.1.png)

**2. BATCH_SIZE = 8, lr=0.0001**
![Image alt](https://github.com/PavelPoukh/LAB3/blob/master/2.2.png)

**3. BATCH_SIZE = 8, lr=0.000001**
![Image alt](https://github.com/PavelPoukh/LAB3/blob/master/2.3.png)

**3 PART**

На третьем этапе были разморожены сверточные слои и использованы весовые коэффициенты из предыдущей попытки.

**BATCH_SIZE = 8, lr=0.000001**
![Image alt](https://github.com/PavelPoukh/LAB3/blob/master/3.1.png)
