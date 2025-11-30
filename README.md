
#instructions
turn_on, turn_off, toggle
#Grid: 1000 * 1000
#Top left corner = 0,0 - bottom left corner = 0,999 - bottom right corner = 999.999 - top right corner = 999,0
#Lights_off = False

grid = [[FALSE for in range(1000)] for in range(1000*1000)]

instructions = [
"turn on 887,9 through 959,629",
"turn on 454,398 through 844,448",
"turn off 539,243 through 559,965",
"turn off 370,819 through 676,868",
"turn off 145,40 through 370,997",
"turn off 301,3 through 808,453",
"turn on 351,678 through 951,908",
"toggle 720,196 through 897,994",
"toggle 831,394 through 904,860",
]

for line, in instructions
