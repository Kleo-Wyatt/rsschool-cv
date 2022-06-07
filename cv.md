# VICTORIA ILCHENKO
___

## Contacts
- Phone: +79037739321
- E-mail: kleo.wyatt@gmail.com

## About Me
I have been playing online poker professionally since 2012. 
In 2018, I saw an advertisement for a programming school from Sberbank "School 21" and became interested. I decided to try to pass the qualifying stage in this school, but at the end of the qualifying stage I was refused. At that moment, I decided that it was not for me, so I returned to my usual occupation. 
About a year ago I heard about RSschool and this project seemed very interesting to me. I want to try again to learn a new skill and become a front-end developer.

## Skills
- C (basic knowledge)
- HTML (basic knowledge)
- CSS (basic knowledge)

## Code examples

```
#include <unistd.h>

int main(int ac, char **av)
{
    int i = 0;
    
    if (ac == 2)
    {
        while (av[1][i])
            i++;
        i--;
    
        if (av[1][i] == ' ' || av[1][i] == '\t')
        {
            while (av[1][i] == ' ' || av[1][i] == '\t')
                {
                    i--;
                }
            i++;
            av[1][i] = '\0';
        }
        
        i = 0;
        while (av[1][i])
            {
                while (av[1][i] == ' ' || av[1][i] == '\t')
                    i++;
                while (av[1][i] != ' ' && av[1][i] != '\t' && av[1][i] != '\0')
                    {
                        write(1, &av[1][i], 1);
                        i++;
                    }
                while (av[1][i] == ' ' || av[1][i] == '\t')
                    {
                        write(1, " ", 3);
                        break;
                    }
                }
            }
    write(1, "\n", 1);
    return (0);
}

```

## Work experience
I have been playing online poker professionally since 2012.

## Education and courses
RSSchool currently

## Language
English level - A2