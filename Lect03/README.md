## DL4ES, Лекция 3

#### Введение в машинное обучение в науках о Земле.



В этой лекции занятии обсуждались различные аспекты градиентного спуска и его модификации. Основные темы включали:

1. **Градиентная оптимизация**: Обсуждались основы градиентного спуска, включая определение функции потерь и ее зависимость от параметров и данных (x, y). Было подчеркнуто, что оптимизация происходит на пространстве параметров, и цель состоит в минимизации функции потерь.

2. **Регуляризация**: Рассматривалась проблема коррелированных признаков, которая приводит к высокой неопределенности в параметрах. Для решения этой проблемы предлагается использование регуляризации. Были обсуждены L2 и L1 регуляризации и их влияние на ландшафт функции потерь.

3. **Стахастический градиентный спуск (SGD)**: Представлен концепт стахастического градиентного спуска, где оценки функции потерь и градиента вычисляются на подмножестве данных (batch), а не на всей выборке. Это ускоряет вычисления и делает процесс оптимизации более эффективным, особенно при больших объемах данных. Обсуждалась важность размера batch и его влияние на точность оценки градиента.

4. **Эпохи и генераторы данных**: Объяснялось понятие эпохи в контексте итерационной тренировки моделей. Также обсуждались стратегии сэмплирования данных для формирования батчей и их влияние на процесс обучения.

5. **Работа с большими данными**: Подчеркивалось, что при работе с большими данными, обучение может быть распределенным, что позволяет использовать параллельные вычисления для повышения эффективности.



градиентный спуск, функция потерь, регуляризация, корреляция признаков, стахастический градиентный спуск, batch, эпоха, генератор данных, распределенное обучение, нейросети