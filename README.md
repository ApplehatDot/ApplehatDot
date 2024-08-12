Hello, welcome to my Github profile 👋🍎
```c
// About Me
#include <stdlib.h>
#include <string.h>

// About Me
#include <stdlib.h>
#include <string.h>

typedef struct {
    nickname[70];
    pronouns[10];
    interests[100];
} AboutMe;

void Display_AboutMe(AboutMe person) {
    printf("Nickname: %s\n", person.nickname);
    printf("Pronouns: %s\n", person.pronouns);
    printf("Interests: %s\n", person.interests);
}

int main(){
    AboutMe me;

    strcpy(me.nickname, "ApplehatDot (ApplehatDoesStuff)");
    strcpy(me.pronouns, "he/him");
    strcpy(me.interests, "old hardware and software, programming, using various OS' (...)")
    Display_AboutMe(&me);

    return 0;
}

```
