# TicTacToe - README
To prosto skonstruowany skrypt w JS, który umożliwia grę w kółko i krzyżyk dla dwóch osób na planszy 3x3.

## Jak z niego korzystać?
Po uruchomieniu skryptu ujawi się plansza 3x3 ( 9 pól ). Gracze na zmianę ustawiają swoje znaki ( X lub O ),
a w przypadku wygranej gra informuje o tym zwracając komunikat kto jest zwycięzcą oraz stawia czerwoną linię na polach, na których zostały spełnione wymogi wygranej.

## Jakie funkcje występują w tym skrypcie?
- **createBoard()** - Tworzy planszę, na której toczy się rozgrywka w formacie 3x3
- **handleCellClick(event)** - Obsługue kliknięcie w pole. Na klikniętym polu jest umieszczany odpowiedni znak gracza ( tego, do którego należy tura ). Sprawdza też wygraną, remis oraz zmiane gracza.
- **checkWin()** - Sprawdza, czy któryś z graczy spełnił warunki wygranej, porównując czy któraś z kombinacji wygranej się zgadza.
- **drawWinningLine()** - Rysuje linię na planszy wzdłuż pól, które spełniły wymogi wygranej.
- **resetGame()** - Czyści planszę i ustawia wszystko od nowa, aby rozpocząć rozgrywkę ponownie.

## Jakie zmienne globalne występują w tym skrypcie?
- __*board*__ - Element HTML, w którym znajduję się plansza.
- __*messageTur*__ - Element HTML, w którym jest plansza.
- __*resertBtn*__ - Element HTML, w którym jest przycisk resetowania gry.
- __*currentPlayer*__ - Zmienna, która wyznacza danego gracza.
- __*gameBoard*__ - Tablica, która przechowuje aktualny stan planszy.
- __*winningCombo*__ - Tablica, która zawiera zwycięzkie kombinacje.
- __*gameOver*__ - Zmienna, która określa kiedy występuje zakończenie rozgrywki.
