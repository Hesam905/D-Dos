# D-Dos
#import datetime
import time
import random



odds = [1,  3,  4,  5,  7,  9,  11,  13,  15,  17,  19,  21,  23,  25,
        27,  29,  31,  33,  35,  37,  39,  41,  43,  45,  47,
        49,  51,  53,  55,   57,  59,]

right_this_minute = datetime.today().minute
#right_this_minute = datetime.datetime.today().minute

#time_now = datetime.today()
#right_this_minute = time_now.minute                              __________________________________________________________________________________
                                                                  _______________________________("hesam_905_oo")___________________________________
for i in range(10):                                               __________________________________________________________________________________
    right_this_minute = datetime.today().minute                        
    if right_this_minute in odds:
        print("Odd minute")
    else:
        print("Not an odd minute")
    wait_time = random.randint(1, 5)
    time.sleep(wait_time)
print("010101011001010101010101010101010101010101010101010101001010101
       010101010101010100101010101010101010101010101010101010101010101
       011010101010101010101010101010101010101010101010101010101010101
       010101010101010101010101010101010110101010101010101010101010101
       010101010101010101010101010101010101010101010101010101010101010
       000000000000000000000000000000000000000000000000000000000000000")
       
       #include <graphics.h>
      

int main( )
{
    initwindow(400, 300, "First Sample");
    circle(100, 50, 40);
    while (!kbhit( ))
    {
        delay(200);
    }
    return 0;
}
