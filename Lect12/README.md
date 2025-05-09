## DL4ES, Лекция 12

#### Пакетная нормализация карт активаций.

Обсуждение сосредоточено на различных методах инициализации нейронных сетей, в частности, на методах, предложенных Kaiming He и Xavier Glorot. Подчеркивается важность правильной инициализации, так как она влияет на дисперсию активаций через слои, что существенно сказывается на процессе обучения. Лекция демонстрирует практическую реализацию этих методов инициализации с использованием фреймворка PyTorch. Обсуждается влияние разных методов инициализации на дисперсию весов и активаций, особенно акцентируется внимание на дисперсии активаций по слоям. Указывается, что правильная инициализация необходима для предотвращения схлопывания дисперсии активаций в ноль, что может привести к неэффективному обучению сети. Подчеркивается, что инициализация Kaiming He более подходит для сетей с функцией активации ReLU по сравнению с инициализацией Xavier Glorot.

Далее обсуждается пакетная нормализация, техника, стабилизирующая и ускоряющая обучение путем нормализации входов слоев. Объясняется, как пакетная нормализация работает, вычисляя среднее и дисперсию для каждой особенности по батчу и стандартируя их. Это помогает поддерживать стабильные распределения активаций, что важно для эффективного обучения. Лектор также затрагивает практическую реализацию пакетной нормализации в PyTorch и подчеркивает важность учета скользящих средних значений и дисперсии во время обучения для обеспечения стабильной работы во время вывода. Также упоминаются инструменты, такие как TensorBoard, для мониторинга процессов обучения и визуализации распределений, что может помочь в отладке и оптимизации обучения сетей.



инициализация, нейронные сети, Kaiming He, Xavier Glorot, Pytorch, дисперсия, активации, пакетная нормализация, обучение, tensorboard