def value(x):
    if x == -1:
        return "0️⃣1️⃣"
    if x == -2:
        return "0️⃣2️⃣"
    if x == -3:
        return "0️⃣3️⃣"
    if x == -4:
        return "0️⃣4️⃣"
    if x == -5:
        return "0️⃣5️⃣"
    if x == -6:
        return "0️⃣6️⃣"
    if x == -7:
        return "0️⃣7️⃣"
    if x == -8:
        return "0️⃣8️⃣"
    if x == -9:
        return "0️⃣9️⃣"
    if x == -10:
        return "1️⃣0️⃣"
    if x == -11:
        return "1️⃣1️⃣"
    if x == -12:
        return "1️⃣2️⃣"
    if x == -13:
        return "1️⃣3️⃣"
    if x == -14:
        return "1️⃣4️⃣"
    if x == -15:
        return "1️⃣5️⃣"
    if x == -16:
        return"1️⃣6️⃣"
    if x == 2:
        return "⭕️"
    if x == 3:
        return "❌"

def result(sec):
    if ((sec[0] == sec[1] == sec[2] == 2) or
       (sec[4] == sec[5] == sec[6] == 2) or
       (sec[8] == sec[9] == sec[10] == 2) or
       (sec[0] == sec[4] == sec[8] == 2) or
       (sec[1] == sec[5] == sec[9] == 2) or
       (sec[2] == sec[6] == sec[10] == 2) or
       (sec[1] == sec[2] == sec[3] == 2) or
       (sec[5] == sec[6] == sec[7] == 2) or
       (sec[9] == sec[10] == sec[11] == 2) or
       (sec[12] == sec[13] == sec[14] == 2) or
       (sec[13] == sec[14] == sec[15] == 2) or
       (sec[4] == sec[8] == sec[12] == 2) or
       (sec[5] == sec[9] == sec[13] == 2) or
       (sec[6] == sec[10] == sec[14] == 2) or
       (sec[7] == sec[11] == sec[15] == 2) or
       (sec[1] == sec[6] == sec[11] == 2) or
       (sec[3] == sec[6] == sec[9] == 2) or
       (sec[4] == sec[9] == sec[14] == 2) or
       (sec[6] == sec[9] == sec[12] == 2) or
       (sec[5] == sec[10] == sec[15] == 2) or
       (sec[7] == sec[10] == sec[13] == 2) or
       (sec[3] == sec[7] == sec[11] == 2) or
       (sec[0] == sec[5] == sec[10] == 2) or
       (sec[2] == sec[5] == sec[8] == 2)):
        return ("Вы проиграли!")
    elif((sec[0] == sec[1] == sec[2] == 3) or
       (sec[4] == sec[5] == sec[6] == 3) or
       (sec[8] == sec[9] == sec[10] == 3) or
       (sec[0] == sec[4] == sec[8] == 3) or
       (sec[1] == sec[5] == sec[9] == 3) or
       (sec[2] == sec[6] == sec[10] == 3) or
       (sec[1] == sec[2] == sec[3] == 3) or
       (sec[5] == sec[6] == sec[7] == 3) or
       (sec[9] == sec[10] == sec[11] == 3) or
       (sec[12] == sec[13] == sec[14] == 3) or
       (sec[13] == sec[14] == sec[15] == 3) or
       (sec[4] == sec[8] == sec[12] == 3) or
       (sec[5] == sec[9] == sec[13] == 3) or
       (sec[6] == sec[10] == sec[14] == 3) or
       (sec[7] == sec[11] == sec[15] == 3) or
       (sec[1] == sec[6] == sec[11] == 3) or
       (sec[3] == sec[6] == sec[9] == 3) or
       (sec[4] == sec[9] == sec[14] == 3) or
       (sec[6] == sec[9] == sec[12] == 3) or
       (sec[5] == sec[10] == sec[15] == 3) or
       (sec[7] == sec[10] == sec[13] == 3) or
       (sec[3] == sec[7] == sec[11] == 3) or
       (sec[0] == sec[5] == sec[10] == 3) or
       (sec[2] == sec[5] == sec[8] == 3)):
        return ("Вы победили!")
    else:
        return ("Ничья!")

#from first_supportive_file import value

#from second_supportive_file import result

key = 0
sec = [-1, -2, -3, -4, -5, -6, -7, -8, -9, -10, -11, -12, -13, -14, -15, -16]
choice = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]
priority_move = []
priority_summ = []
w_key = 0


def nous(x):
    nous_xod = sec[x]
    sec[x] = 3
    if ((sec[0] == sec[1] == sec[2]) == True or
            (sec[4] == sec[5] == sec[6]) == True or
            (sec[8] == sec[9] == sec[10]) == True or
            (sec[0] == sec[4] == sec[8]) == True or
            (sec[1] == sec[5] == sec[9]) == True or
            (sec[2] == sec[6] == sec[10]) == True or
            (sec[0] == sec[5] == sec[10]) == True or
            (sec[2] == sec[5] == sec[8]) == True or
            (sec[1] == sec[2] == sec[3]) == True or
            (sec[5] == sec[6] == sec[7]) == True or
            (sec[9] == sec[10] == sec[11]) == True or
            (sec[3] == sec[7] == sec[11]) == True or
            (sec[1] == sec[6] == sec[11]) == True or
            (sec[3] == sec[6] == sec[9]) == True or
            (sec[12] == sec[13] == sec[14]) == True or
            (sec[4] == sec[8] == sec[12]) == True or
            (sec[5] == sec[9] == sec[13]) == True or
            (sec[6] == sec[10] == sec[14]) == True or
            (sec[4] == sec[9] == sec[14]) == True or
            (sec[6] == sec[9] == sec[12]) == True or
            (sec[13] == sec[14] == sec[15]) == True or
            (sec[7] == sec[11] == sec[15]) == True or
            (sec[5] == sec[10] == sec[15]) == True or
            (sec[7] == sec[10] == sec[13]) == True):
                sec[x] = nous_xod
                priority_move.append(x)
                priority_summ.append(9)
                return 2

    sec[x] = 2
    if ((sec[0] == sec[1] == sec[2]) == True or
            (sec[4] == sec[5] == sec[6]) == True or
            (sec[8] == sec[9] == sec[10]) == True or
            (sec[0] == sec[4] == sec[8]) == True or
            (sec[1] == sec[5] == sec[9]) == True or
            (sec[2] == sec[6] == sec[10]) == True or
            (sec[0] == sec[5] == sec[10]) == True or
            (sec[2] == sec[5] == sec[8]) == True or
            (sec[1] == sec[2] == sec[3]) == True or
            (sec[5] == sec[6] == sec[7]) == True or
            (sec[9] == sec[10] == sec[11]) == True or
            (sec[3] == sec[7] == sec[11]) == True or
            (sec[1] == sec[6] == sec[11]) == True or
            (sec[3] == sec[6] == sec[9]) == True or
            (sec[12] == sec[13] == sec[14]) == True or
            (sec[4] == sec[8] == sec[12]) == True or
            (sec[5] == sec[9] == sec[13]) == True or
            (sec[6] == sec[10] == sec[14]) == True or
            (sec[4] == sec[9] == sec[14]) == True or
            (sec[6] == sec[9] == sec[12]) == True or
            (sec[13] == sec[14] == sec[15]) == True or
            (sec[7] == sec[11] == sec[15]) == True or
            (sec[5] == sec[10] == sec[15]) == True or
            (sec[7] == sec[10] == sec[13]) == True):
                sec[x] = nous_xod
                priority_move.append(x)
                priority_summ.append(10)
                return 2
    sec[x] = nous_xod
    if x == 5 and sec[5] < 0 and choice[x] == 0:
        sum_o_cells = 0
        for k in [0, 1, 2, 4, 6, 8, 9, 10]:
            sum_o_cells += choice[k]
        priority_move.append(x)
        priority_summ.append(sum_o_cells)
        return 2
    if x == 6 and sec[6] < 0 and choice[x] == 0:
        sum_o_cells = 0
        for k in [1, 2, 3, 5, 7, 9, 10, 11]:
            sum_o_cells += choice[k]
        priority_move.append(x)
        priority_summ.append(sum_o_cells)
        return 2
    if x == 9 and sec[9] < 0 and choice[x] == 0:
        sum_o_cells = 0
        for k in [4, 5, 6, 8, 10, 12, 13, 14]:
            sum_o_cells += choice[k]
        priority_move.append(x)
        priority_summ.append(sum_o_cells)
        return 2
    if x == 10 and sec[10] < 0 and choice[x] == 0:
        sum_o_cells = 0
        for k in [5, 6, 7, 9, 11, 13, 14, 15]:
            sum_o_cells += choice[k]
        priority_move.append(x)
        priority_summ.append(sum_o_cells)
        return 2
    if sec[5] == 3 and choice[10] == 0:
        priority_move.append(10)
        priority_summ.append(3)
        return 2
    if sec[6] == 3 and choice[9] == 0:
        priority_move.append(9)
        priority_summ.append(3)
        return 2
    if sec[9] == 3 and choice[6] == 0:
        priority_move.append(6)
        priority_summ.append(3)
        return 2
    if sec[10] == 3 and choice[5] == 0:
        priority_move.append(5)
        priority_summ.append(3)
        return 2
    if x == 3 and sec[3] < 0 and choice[x] == 0:
        sum_o_cells = 0
        for j in [2, 6, 7]:
            sum_o_cells += choice[j]
        priority_move.append(x)
        priority_summ.append(sum_o_cells)
        return 2
    if x == 15 and sec[15] < 0 and choice[x] == 0:
        sum_o_cells = 0
        for j in [10, 11, 14]:
            sum_o_cells += choice[j]
        priority_move.append(x)
        priority_summ.append(sum_o_cells)
        return 2

print("||||||||||||||||||||||||||||||||||||||"
      "\n||\t ||\t  ||\t   ||\t    ||\n||",
      value(sec[0]), "||", value(sec[1]), "||", value(sec[2]), "||", value(sec[3]),
      "||\n||" "\t ||" "\t  ||" "\t   ||\t    ||\n"
      "||||||||||||||||||||||||||||||||||||||"
      "\n||\t ||\t  ||\t   ||\t    ||\n||",
      value(sec[4]), "||", value(sec[5]), "||", value(sec[6]), "||", value(sec[7]),
      "||\n||" "\t ||" "\t  ||" "\t   ||\t    ||\n"
      "||||||||||||||||||||||||||||||||||||||"
      "\n||\t ||\t  ||\t   ||\t    ||\n||",
      value(sec[8]), "||", value(sec[9]), "||", value(sec[10]), "||", value(sec[11]),
      "||\n||" "\t ||" "\t  ||" "\t   ||\t    ||\n"
      "||||||||||||||||||||||||||||||||||||||"
      "\n||\t ||\t  ||\t   ||\t    ||\n||",
      value(sec[12]), "||", value(sec[13]), "||", value(sec[14]), "||", value(sec[15]),
      "||\n||" "\t ||" "\t  ||" "\t   ||\t    ||\n"
      "||||||||||||||||||||||||||||||||||||||")

while (((sec[0] != sec[1]) or (sec[1] != sec[2])) and
       ((sec[4] != sec[5]) or (sec[5] != sec[6])) and
       ((sec[8] != sec[9]) or (sec[9] != sec[10])) and
       ((sec[0] != sec[4]) or (sec[4] != sec[8])) and
       ((sec[1] != sec[5]) or (sec[5] != sec[9])) and
       ((sec[2] != sec[6]) or (sec[6] != sec[10])) and
       ((sec[1] != sec[2]) or (sec[2] != sec[3])) and
       ((sec[5] != sec[6]) or (sec[6] != sec[7])) and
       ((sec[9] != sec[10]) or (sec[10] != sec[11])) and
       ((sec[12] != sec[13]) or (sec[13] != sec[14])) and
       ((sec[13] != sec[14]) or (sec[14] != sec[15])) and
       ((sec[4] != sec[8]) or (sec[8] != sec[12])) and
       ((sec[5] != sec[9]) or (sec[9] != sec[13])) and
       ((sec[6] != sec[10]) or (sec[10] != sec[14])) and
       ((sec[7] != sec[11]) or (sec[11] != sec[15])) and
       ((sec[1] != sec[6]) or (sec[6] != sec[11])) and
       ((sec[3] != sec[6]) or (sec[6] != sec[9])) and
       ((sec[4] != sec[9]) or (sec[9] != sec[14])) and
       ((sec[6] != sec[9]) or (sec[9] != sec[12])) and
       ((sec[5] != sec[10]) or (sec[10] != sec[15])) and
       ((sec[7] != sec[10]) or (sec[10] != sec[13])) and
       ((sec[3] != sec[7]) or (sec[7] != sec[11])) and
       ((sec[0] != sec[5]) or (sec[5] != sec[10])) and
       ((sec[2] != sec[5]) or (sec[5] != sec[8])) and key == 0):

    while w_key == 0:
        print("Введите номер ячейки для хода: ")
        move = int(input()) - 1
        if move in [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]:
            if choice[move] == 0:
                sec[move] = 3
                choice[move] = 1
                w_key = 1
    i = -1
    key = 0
    w_key = 0

    while key == 0 and i < 15:
        i += 1
        if choice[i] == 0:
            nous(i)
    if 0 in choice:
        max_value = max(priority_summ)
        max_index = priority_summ.index(max_value)
        sec[priority_move[max_index]] = 2
        choice[priority_move[max_index]] = 1
        print(i, sec, choice, priority_move, priority_summ)
        priority_move.clear()
        priority_summ.clear()
    else:
        key = 1
    print("||||||||||||||||||||||||||||||||||||||||||||||||||"
          "\n||\t\t\t||\t\t\t||\t\t\t||\t\t\t||\n||\t",
          value(sec[0]), "\t||\t", value(sec[1]), "\t||\t", value(sec[2]), "\t||\t", value(sec[3]),
          "\t||\n||\t\t" "\t||\t\t" "\t||\t\t" "\t||\t\t\t||\n"
          "||||||||||||||||||||||||||||||||||||||||||||||||||"
          "\n||\t\t\t||\t\t\t||\t\t\t||\t\t\t||\n||\t",
          value(sec[4]), "\t||\t", value(sec[5]), "\t||\t", value(sec[6]), "\t||\t", value(sec[7]),
          "\t||\n||\t\t" "\t||\t\t" "\t||\t\t" "\t||\t\t\t||\n"
          "||||||||||||||||||||||||||||||||||||||||||||||||||"
          "\n||\t\t\t||\t\t\t||\t\t\t||\t\t\t||\n||\t",
          value(sec[8]), "\t||\t", value(sec[9]), "\t||\t", value(sec[10]), "\t||\t", value(sec[11]),
          "\t||\n||\t\t" "\t||\t\t" "\t||\t\t" "\t||\t\t\t||\n"
          "||||||||||||||||||||||||||||||||||||||||||||||||||"
          "\n||\t\t\t||\t\t\t||\t\t\t||\t\t\t||\n||\t",
          value(sec[12]), "\t||\t", value(sec[13]), "\t||\t", value(sec[14]), "\t||\t", value(sec[15]),
          "\t||\n||\t\t" "\t||\t\t" "\t||\t\t" "\t||\t\t\t||\n"
          "||||||||||||||||||||||||||||||||||||||||||||||||||")

print(result(sec))
