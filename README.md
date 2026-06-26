# Анализ увольнения сотрудников (IBM HR Analytics)

Классификация и анализ факторов увольнения сотрудников на основе HR-данных. 

## Задача


По разным параметрам сделать классификатор уволится человек с работы или нет (переменная attrition).

**Источник**: http://youtube.com/post/UgkxkWrWdtolNABTSccXjfBazSK4Il_BiG8C?si=voYDI8KcaXHhJSnv


## Данные

Источник: [IBM HR Analytics Employee Attrition (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Размер:** 1470 сотрудников, 35 признаков
- **Целевая переменная:** `Attrition` (уволился / остался)
- **Особенность:** классы несбалансированы — уволившихся всего ~16%

## Стек


`Python`, `pandas`, `numpy`, `scikit-learn` (RandomForest), `matplotlib`, `seaborn`


## Как запустить

```bash
# создать и активировать виртуальное окружение
python -m venv venv
source venv/bin/activate        

# установить зависимости
pip install -r requirements.txt

# запустить
jupyter notebook hr_attrition_analysis.ipynb
```
