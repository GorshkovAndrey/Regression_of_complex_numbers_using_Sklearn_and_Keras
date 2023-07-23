### Regression_of_complex_numbers
### Горшков Андрей Вячеславович
### Обучение модели регрессии для переменных, содержащих комплексные числа, с использованием алгоритмов scikit-learn
------------------------------------------

Алгоритмы scikit-learn не поддерживают работу с комплексными числами, что не позволяет построить модели регрессии для данных, содержащих комплексные числа.

Разработан метод преобразования исходного датасета размером M×N с комплексными числами в датасет размером 2M×(2N-1) с вещественными числами, что позволяет использовать для построения <достоверной> модели регрессии комплексных чисел стандартные модели регрессоров scikit-learn.
