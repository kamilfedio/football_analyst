### Data Description

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/davidcariboo/player-scores). It includes information about football player scores, including appearances, competitions, games, player valuations, and player details.

#### Files Used:

1. **appearances.csv**:
   - Columns: appearance_id, game_id, player_id, player_club_id, player_current_club_id, date, player_name, competition_id, yellow_cards, red_cards, goals, assists, minutes_played

2. **competitions.csv**:
   - Columns: competition_id, competition_code, name, sub_type, type, country_id, country_name, domestic_league_code, confederation, url

3. **games.csv**:
   - Columns: game_id, competition_id, season, round, date, home_club_id, away_club_id, home_club_goals, away_club_goals, home_club_position, away_club_position, home_club_manager_name, away_club_manager_name, stadium, attendance, referee, url, home_club_formation, away_club_formation, home_club_name, away_club_name, aggregate, competition_type

4. **player_valuations.csv**:
   - Columns: player_id, date, market_value_in_eur, current_club_id, player_club_domestic_competition_id

5. **players.csv**:
   - Columns: player_id, first_name, last_name, name, last_season, current_club_id, player_code, country_of_birth, city_of_birth, country_of_citizenship, date_of_birth, sub_position, position, foot, height_in_cm, contract_expiration_date, agent_name, image_url, url, current_club_domestic_competition_id, current_club_name, market_value_in_eur, highest_market_value_in_eur

These data provide a comprehensive view of player performances, competitions, games, valuations, and player details over time, which can be leveraged for data analysis and machine learning tasks.

Please note that the data is subject to Kaggle's terms of use and may require appropriate permissions for usage in commercial projects. Before using the dataset in your project, make sure to review the licensing terms.