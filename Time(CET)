#include <stdio.h>
#include <time.h>

 
// driver code
int main()
{
    time_t s;
    struct tm* current_time;
 
    // time in seconds
    s = time(NULL);
 
    // to get current time
    current_time = localtime(&s);
 
    /* print time in minutes,
     hours and seconds */
    printf("%02d:%02d:%02d",
           current_time->tm_hour + 2, //Time in Central Europe
           current_time->tm_min,
           current_time->tm_sec);
 
    return 0;
}
