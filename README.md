# TIC-TAC-TOE-GAME
TIC TAC TOE GAME
Import random
def_init_(Self):
    self.board = []
def create_board(self):
  for i in range(3):
      row = []
      for j in range(3):
        row.append('-')
          self.board.append(row)
def get_random_first_player(self):
    return random.randint(0,1)
def fix_spot(Self, row, col, player):
    self.board[row][col] = player
def is_player_win(self, player):
    win = none

  n = len(self.board)

  for in in range(n):
      win = True
      for j in range(n):
          if self.bboard[j][i] != player:
                  win = False
                  break
          if win:
            return win
win = true
for i in range(n):
