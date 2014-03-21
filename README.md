Greetings,

    So you want to use this pomodoro technique do ya? Well, if'n you do,
and if'n you've got your bash terminal there just laying open looking at
the sun, well do I have the ticket for you. I've got a script here that's
gonna fix up your ol' gut.

usage: pomodoro [-hstc] [-m time] [-w time] [-b time] [-r time] [-W number]
where:
    -h  show this help text
    -s  silence bells
    -t  ticking enabled
    -c  run in clock mode
    -m  set length of base time unit        (default: 60 seconds)
    -w  set length of work period           (default: 25 base units)
    -b  set length of break period          (default: 5 base units)
    -r  set length of rest period           (default: 25 base units)
    -W  set number of work periods per rest (default: 4)

You can install the bells and whistles or whathaveya's just about wherever
you please if you update the $path_to_sounds variable. And then you can do
just about the same thing with the music player if you go at the $music_player
variable.

