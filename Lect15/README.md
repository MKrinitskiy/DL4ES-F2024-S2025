## DL4ES, Лекция 15

#### Функции активации: часть 1.



Лекция посвящена обучению нейронных сетей и функциям активации, таким как сигмоид, гиперболический тангенс и ReLU. В ней обсуждаются их влияние на обучение и связанные проблемы. Функции активации, как сигмоид, могут вызывать исчезающие градиенты, особенно в глубоких сетях, что затрудняет обучение. Гиперболический тангенс также может вызывать затухание градиентов. ReLU решает проблему затухающих градиентов, но может привести к появлению "мертвых нейронов". Кроме того, использование ReLU может вызывать снижение дисперсии активаций и смещение среднего от нуля, что частично решается с помощью пакетной нормализации. В лекции предлагаются инженерные решения, такие как пакетная нормализация и изменение скорости обучения для разных слоев, чтобы справиться с проблемами функций активации.



нейронные сети, функции активации, сигмоид, гиперболический тангенс, relu, исчезающие градиенты, мертвые нейроны, пакетная нормализация