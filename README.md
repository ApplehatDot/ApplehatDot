Hello, welcome to my Github profile 👋🍎
```c
// About Me
#include <stdlib.h>
#include <string.h>

typedef struct {
    nickname[70];
    pronouns[10];
    country[30];
    interests[100];
    repositories[100];
} AboutMe;

void Display_AboutMe(AboutMe person) {
    printf("Nickname: %s\n", person.nickname);
    printf("Pronouns: %s\n", person.pronouns);
    printf("Country: %s\n", person.country);
    printf("Interests: %s\n", person.interests);
    printf("Repositories: %s\n", person.repositories);
}

int main(){
    AboutMe me;

    strcpy(me.nickname, "ApplehatDot (ApplehatDoesStuff)");
    strcpy(me.pronouns, "he/him");
    strcpy(me.country, "Poland");
    strcpy(me.interests, "old hardware and software, programming, using various OS' (...)");
    strcpy(me.repositories, "DVD_GL, SNEK_GL and OpenGLHeart");

    Display_AboutMe(&me);

    return 0;
}

```
