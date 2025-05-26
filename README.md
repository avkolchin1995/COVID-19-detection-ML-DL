# COVID-19-detection-ML-DL
 Детектирование наличия COVID-19 либо вирусной пневмонии на рентгеновских снимках легких с помощью алгоритмов машинного и глубокого обучения
## Оглавление
1) Загрузка необходимых библиотек и инструментов:
- os,
- cv2,
- scikit-image,
- numpy,
- scikit-learn,
- torch.
2) Создание отдельных функций:
- загрузки изображений,
- выделения LBP-признаков,
- разметки примеров.
3) Загрузка и предобработка датасета:
- загрузка изображений,
- выделение LBP-признаков,
- разметка примеров.
4) Построение и оценка моделей на основе классических алгоритмов машинного обучения:
- KNearestNeiborghs,
- DecisionTree,
- RandomForestTree,
- GradientBoostingClassifier.
5) Построение и оценка моделей на основе классических алгоритмов глубокого обучения:
- Многослойный персептрон (Scikit-Learn),
- Многослойный персептрон (Torch; в процессе разработки).
6) Результаты
<table>
  <tr><th>Алгоритм</th><th>Средняя точность, %</th></tr>
  <tr><td>K-Nearest Neighbours</td><td>61</td></tr>
  <tr><td>Decision Tree</td><td>77</td></tr>
  <tr><td>Random Forest Tree</td><td>79</td></tr>
  <tr><td>Gradient Boosting</td><td>79</td></tr>
  <tr><td>Multilayer Perceptron (scikit-learn)</td><td>61</td></tr>
</table>
