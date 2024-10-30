# Анализ вакансий HH.ru

## Цель работы
Выявить различия в предлагаемых вакансиях для Аналитиков данных и Системных аналитиков.
Данные были получены с использованием API HH.ru.

## Основные шаги выполнения
- Загрузка данных
- Предобработка данных: подготовка данных для дальнейшего анализа, включая очистку и преобразование.
- Исследовательский анализ данных:
  - Анализ грейдов специалистов: определение уровня квалификации (грейда) специалистов на основе названий вакансий и требований к опыту работы. Выделение доли грейдов Junior, Junior+, Middle, Senior среди вакансий "Аналитик данных" и "Системный аналитик".
  - Анализ типичного места работы: исследование типичных условий работы для аналитиков данных и системных аналитиков по следующим параметрам: ТОП-работодатели, зарплата, тип занятости и график работы. Анализ проводится отдельно для каждого грейда (Junior, Junior+, Middle, Senior).
  - Анализ навыков: сравнение востребованности твёрдых (hard) и мягких (soft) навыков, определение их связи с уровнем квалификации и специальностью. Выявление, какие навыки более важны для каждого грейда и для каждой из профессий. Определение желаемого кандидата: анализ наиболее востребованных кандидатов на позиции "Аналитик данных" и "Системный аналитик" по ключевым hard и soft навыкам. Проведение анализа отдельно для каждого уровня квалификации.
- Формулирование выводов и рекомендаций: выводы на основе полученных результатов и разработка рекомендаций по улучшению стратегии поиска работы для кандидатов.

## Используемые библиотеки
*pandas*<br>
*numpy*<br>
*matplotlib*<br>
*seaborn*
