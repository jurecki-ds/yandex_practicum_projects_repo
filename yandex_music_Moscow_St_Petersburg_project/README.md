# Yandex_music_Moscow_St_Petersburg project description


## Research objectives (problem statement)

Compare the behavior (musical preferences) of the two capitals users (living in Moscow and St. Petersburg) based on the data of Yandex Music. Compare listening on Monday, Wednesday and Friday by city, as well as compare the genres that users listen to on Monday morning and Friday evening in Moscow and St. Petersburg.


## Initial data

The following data (from dataset) on listening to tracks in the Yandex.Music service was available:
- user identificator;
- name of the track;
- artist;
- genre of the track;
- city of listening;
- day of listening;
- listening time.


## Research points

The following steps were taken to achieve the research objectives: 
1. Data review (to get the first view of the Yandex.Music data) 
2. Data preprocessing:
    - correcting table column names according to "snake_case"
    - filling in missing values in a table
    - removing explicit and implicit duplicates in a data table
3. Testing hypothesis:
    - comparing of Moscow and St. Petersburg users behavior on listening music depending on the day of the week;
    - preferred music genres at the beginning and the end of the week depending on the city;
    - genre preferences in Moscow and St. Petersburg.
4. Results of the research (conclusions about the consistency of the hypotheses and about the research as a whole)


## Used tools and libraries

*Jupyter Notebook*, *pandas*