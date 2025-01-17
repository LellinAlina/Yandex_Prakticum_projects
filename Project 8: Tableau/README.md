# Проект "Построение дашборда в Tableau"

## Описание проекта

Данный проект посвящён анализу данных о выступлениях на конференциях TED и визуализации полученных результатов в виде интерактивного дашборда с использованием Tableau. Конференции TED охватывают темы из областей технологий, образования и дизайна, а также других актуальных направлений. На мероприятиях выступают специалисты мирового уровня, включая учёных, предпринимателей, спортсменов и новаторов. 

Визуализация позволяет исследовать различные аспекты выступлений, такие как популярность лекций, активность аудитории, профессиональные области авторов и статистику конференций.

## Данные проекта

Проект использует три основных набора данных:

1. **Данные о выступлениях:**
   - Файлы: `tableau_project_data_1.csv`, `tableau_project_data_2.csv`, `tableau_project_data_3.csv`.
   - Описание столбцов:
     - `talk_id` — уникальный идентификатор выступления.
     - `url` — ссылка на запись выступления.
     - `title` — название выступления.
     - `description` — краткое описание выступления.
     - `film_date` — дата записи выступления.
     - `duration` — длительность выступления (в секундах).
     - `views` — количество просмотров.
     - `main_tag` — основная категория выступления.
     - `speaker_id` — уникальный идентификатор автора.
     - `laughter_count` — количество случаев смеха аудитории.
     - `applause_count` — количество аплодисментов.
     - `language` — язык выступления.
     - `event_id` — уникальный идентификатор конференции.

2. **Справочник конференций:**
   - Файл: `tableau_project_event_dict.csv`.
   - Описание столбцов:
     - `conf_id` — уникальный идентификатор конференции.
     - `event` — название конференции.
     - `country` — страна проведения.

3. **Справочник авторов:**
   - Файл: `tableau_project_speakers_dict.csv`.
   - Описание столбцов:
     - `author_id` — уникальный идентификатор автора.
     - `speaker_name` — имя автора.
     - `speaker_occupation` — профессиональная область автора.
     - `speaker_description` — описание профессиональной деятельности.

### Особенности данных

Данные для проекта были собраны с сайта TED с помощью специализированной программы и адаптированы для целей визуализации. 

## Цели проекта

1. Построить интерактивный дашборд в Tableau для анализа данных о выступлениях и конференциях TED.
2. Изучить статистику выступлений, включая:
   - Популярность лекций (количество просмотров, длительность и др.).
   - Активность аудитории (смех, аплодисменты).
   - Распределение выступлений по категориям и профессиональной деятельности авторов.
3. Проанализировать географическое распределение и динамику конференций.

## Ссылка на дашборд

[Посмотреть дашборд в Tableau](https://public.tableau.com/views/_17228628365170/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Результаты проекта

- Создан интерактивный дашборд, позволяющий исследовать ключевые показатели выступлений.
- Выявлены наиболее популярные темы и категории.
- Проведён анализ вовлечённости аудитории через показатели смеха и аплодисментов.
- Представлена статистика конференций, включая географическое распределение и список стран проведения.

## Используемые инструменты

- **Tableau Public** для построения дашборда.
- **Python** для предварительной обработки и анализа данных.

## Заключение

Проект предоставляет удобный инструмент для анализа выступлений TED, который может быть полезен исследователям, организаторам мероприятий и поклонникам конференций.

