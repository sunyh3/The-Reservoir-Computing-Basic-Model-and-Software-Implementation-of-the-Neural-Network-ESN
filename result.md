   via      | Синтезированные данные <br>  (sklearn.datasets)  | Реальные данные <br> (Heart Disease UCI dataset from kaggle.com)
:------: | :----: | :----: 
XGboost | <img src="pics/xgcnfSynth.png"> | <img src="pics/xgcnfReal.png">

##       Таблица зависимости объекта __ClassificationESN__ от темпорализации  (изменения порядка признаков в наборе данных )

Темпорализация <br> (порядок features) |Синтезированные данные <br>  (sklearn.datasets)  | Реальные данные <br> (Heart Disease UCI dataset from kaggle.com)
:------: | :----: | :----: 
Без изменений  | <img src="pics/cnfSynth.png"> <img src="pics/notempoSynth.png">|  <img src="pics/cnfReal.png"> <img src="pics/notempoReal.png">
Два первые признака по *importance*  |<img src="pics/1st2ndcnfSynth.png"> <img src="pics/1st2ndSynth.png">|<img src="pics/1st2ndcnfReal.png"> <img src="pics/1st2ndReal.png">
Первый и последний признак по *importance*  |<img src="pics/1stEndcnfSynth.png"> <img src="pics/1stEndSynth.png"> |<img src="pics/1stEndcnfReal.png"> <img src="pics/1stEndReal.png">
В порядке *importance* |<img src="pics/ordcnfSynth.png"> <img src="pics/ordSynth.png"> |<img src="pics/ordcnfReal.png"> <img src="pics/ordReal.png">
В обратном порядке *importance*|<img src="pics/nonordcnfSynth.png"> <img src="pics/nonordSynth.png"> |<img src="pics/nonordcnfReal.png"> <img src="pics/nonordReal.png">
Все признаки в случайном порядке|<img src="pics/shuffcnfSynth.png"> <img src="pics/shuffSynth.png"> |<img src="pics/shuffcnfReal.png"> <img src="pics/shuffReal.png">


