# FifaTournaments


## Tournament
```
{
  id: 213-31231-31dasd1-23ads31
  name: champions league
  start_date: 2018-10-15
  end_date: 2018-10-22
  winner: player2
  players: [player1, player2, player3...]
  teams: [real madrid, barcelona, man united, liverpool]
  match_results: [
      {
        id: 32der53-351nsa-juh84
        match_date: 2018-10-22
        tournament: tournamentId
        players: [player1, player2]
        score: {
            player1: 2
            player2: 5
        }
        result: result decided 
        winner: undecided 
      }
  ]
}
```

GET /tournaments  
POST /tournaments  
GET /tournaments/{tournament_id}  
UPDATE /tournaments/{tournament_id}  
DELETE /tournaments/{tournament_id}  


## Match result
```
{
  id: 32der53-351nsa-juh84
  match_date: 2018-10-22
  tournament: tournamentId
  players: [player1, player2]
  score: {
      player1: 2
      player2: 2
  }
  result: result decided 
  winner: undecided 
}
```

GET /match_results?tournament_id={tournament_id}  
POST /match_result  
GET /match_result/{match_result_id}  
UPDATE /match_result/{match_result_id}  
DELETE /match_result/{match_result_id}  

## Player
```
{
  id: 123asd9
  name: happymojo_
  date_joined: 2018-10-22
  home_team: real madrid
}
```
