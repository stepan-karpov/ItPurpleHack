внимание - немного нечитаемый код :)

# IT Purple Hack

## Проблематика

Наши исследования и разработки в рамках кейса Альфа-Банка направлены на решение важной задачи: по пакету услуг, выбранному клиентом, и данным об операциях предсказать его предпочтения через год. Это позволит предлагать клиентам более актуальные продукты, что приведет к увеличению продаж.

## Конкурентный анализ

Мы провели анализ конкурентов, таких как Тинькофф, Сбербанк, и ВТБ, и обнаружили, что многие мобильные приложения банков имеют разделы с персонализированными предложениями и отправляют пуш-уведомления с актуальными услугами. Улучшение качества предсказаний позволит Альфа-Банку повысить релевантность своих предложений.

## Предлагаемое решение

Наше решение состоит из стекинга трех моделей: solution_tema, solution_vitya и solution_andrew. Эти модели разработаны на основе глубокого анализа данных клиентов и операций, проведенного с применением передовых алгоритмов, таких как LDA для понижения размерности и генетические алгоритмы для извлечения важных признаков. Помимо этого, мы использовали метод оптимизации Optuna для эффективного подбора гиперпараметров, что позволило добиться высокого качества предсказаний.

Трехступенчатая модель, предложенная нами, отличается от классических подходов тем, что не только учитывает предыдущие предсказания, но и интегрирует их с имеющимися данными, учитывая их специфику. Это приводит к увеличению точности предсказаний и повышению качества обслуживания клиентов. Кроме того, применение кластеризации данных позитивно сказывается на стабильности модели и ее способности к обобщению.

## Уникальность решения

Наша трехступенчатая модель не только учитывает предыдущие предсказания, но и соединяет их с имеющимися данными, что является нетипичным подходом и приводит к повышению метрик качества модели. Мы также применили кластеризацию данных, что дало положительный эффект на качество предсказаний.

## Масштабируемость

Наше решение легко воспроизводится и масштабируется как вертикально, так и горизонтально. Это возможно благодаря использованию градиентного бустинга на очищенных данных в каждой из трех моделей. Мы также обрабатываем данные на входе моделей, что позволяет предсказывать пропущенные данные и использовать oversampling.

## Запуск

Для запуска итоговой модели следует последовательно выполнить ноутбуки solution_tema, solution_vitya и solution_andrew, а затем запустить файл solution.

---
