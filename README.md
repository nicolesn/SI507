# SI507
This is a NBA player's name research system. To get the same player's first or last name list.
Data soruce: NBA_API(regex_pattern)
Data structure:
player = {
    'id': player_id,
    'full_name': full_name,
    'first_name': first_name,
    'last_name': last_name,
    'is_active': True or False
}
Data URL: https://github.com/swar/nba_api
Data describtion:
nba_api is an API Client for www.nba.com. This package intends to make the APIs of NBA.com easily accessible and provide extensive documentation about them.

Question in system:
1. Do you have a NBA player in your mind?
    the answer could be: yes/ no/ not sure

2. Gimme the first letter of player's last name
    the answer could be: A-Z

3. Or maybe you know the first name first letter?
    the answer could be: A-Z
    
4. If the user do not have player in their mind, it will be Micheal Jordan as their answer.


The purpose of this package is to access player information without having to submit requests.
This a protected function that will parse a player list row into a friendly dictionary.

find_players_by_full_name(regex_pattern)
Returns a list of players where full names match the provided regex pattern.

find_players_by_first_name(regex_pattern)
Returns a list of players where first names match the provided regex pattern.

find_players_by_last_name(regex_pattern)
Returns a list of players where last names match the provided regex pattern.
