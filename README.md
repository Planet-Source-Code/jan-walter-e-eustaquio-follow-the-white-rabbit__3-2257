<div align="center">

## Follow the white rabbit\.


</div>

### Description

This is just a modification of the source code of the original author. I fixed it so it will look CLOSER to the 1st scene in the THE MATRIX movie, where NEO first appears. This demonstrates the use of DELAY() func... BEST RUN ON FULL SCREEN MODE... note for the author: forgive me for modifying ur code... wel i just corrected it!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jan Walter E\. Eustaquio](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jan-walter-e-eustaquio.md)
**Level**          |Beginner
**User Rating**    |3.0 (12 globes from 4 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jan-walter-e-eustaquio-follow-the-white-rabbit__3-2257/archive/master.zip)





### Source Code

```
//mtrixneo.cpp - simulates the scene in the matrix movie where in
//neo wakes up and see characters typed in his PC... best run in FULL SCREEN
#include <iostream.h>
#include <stdlib.h>
#include <conio.h>
#include <time.h>
void wait(float seconds);
int main()
{
char MATRIX[]="wake up, Neo... The Matrix has you... Follow the white rabbit. Knock, knock, Neo.";
int i=0;
textcolor(10);
clrscr();
textcolor(10);
while(i!=5){wait(.3); cprintf("%c", MATRIX[i]); i++; }
while(i!=10){wait(.2); cprintf("%c", MATRIX[i]); i++; }
while(i!=13){wait(.2); cprintf("%c", MATRIX[i]); i++; }
while(i!=16){wait(.3); cprintf("%c", MATRIX[i]); i++; }
wait(2);
clrscr();
while(i!=22){wait(.3); cprintf("%c", MATRIX[i]); i++; }
while(i!=28){wait(.2); cprintf("%c", MATRIX[i]); i++; }
while(i!=33){wait(.1); cprintf("%c", MATRIX[i]); i++; }
while(i!=38){wait(.3); cprintf("%c", MATRIX[i]); i++; }
wait(2);
clrscr();
while(i!=43){wait(.3); cprintf("%c", MATRIX[i]); i++; }
while(i!=52){wait(.2); cprintf("%c", MATRIX[i]); i++; }
while(i!=60){wait(.3); cprintf("%c", MATRIX[i]); i++; }
while(i!=63){wait(.2); cprintf("%c", MATRIX[i]); i++; }
wait(2.3);
clrscr();
cprintf("Knock, knock, Neo.");
wait(3);
return 0;
}
void wait(float seconds)
{
clock_t endwait;
endwait = clock () + seconds * CLK_TCK ;
while (clock() < endwait)
{;}
}
```

