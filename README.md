Скрипт запускатся так же, как и бейзлановое решение:
```python hack_train.py --name "baseline" --data "PATH_TO_DATA" [--gpu]```
Я просто в бейзлановом решение поменял resnet18 на resnet152.
Такое простое решение на удивление получила хороший скор. Обучал 15 эпох, 
что в сумме заняло примерно 10 часов. Не успел достигнуть переобучения, в связи с чем не 
попробовал использовать аугментации. Возможно стоило поднять learning_rate.
К сожалению модели, лучшие чем эта, я не смог построить.

Прилагаю скриншот

![Score](best_score.png)
