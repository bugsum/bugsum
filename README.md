/**
 * @file readme.c
 * @author Samarth Sharma (devinsane.79@gmail.com)
 * @brief Who is bugsum? answer below...
 * @version 0.1
 * @date 2022-09-10
 *
 * @copyright Copyright (c) 2022
 *
 */

#include <stdio.h>

struct data
{
      char my_name[50];
      int my_age;
      char known_programming_languages[70];
      char my_current_project[50];
};

int main()
{
      struct data about_me = {
          "Samarth Sharma",
          18,
          "Python,JavaScript, Java, C, C#, C++, Kotlin, Go, MATLAB & PHP",
          "a Minecraft Hack Client made with FabricMC."
      };

      printf("============================================================\n");
      printf("> Hi User,\n");
      printf("> I am %s,\n", about_me.my_name);
      printf("> I am %d years old,\n", about_me.my_age);
      printf("> Programming Languages i know: %s!\n", about_me.known_programming_languages);
      printf("> I am currently working on %s.\n", about_me.my_current_project);
      printf("============================================================\n");

      return 0;
}
