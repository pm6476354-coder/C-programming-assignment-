Skip to content
Navigation Menu
Assignment-1

Code
Issues
Pull requests
 0 stars
 0 forks
 0 watching
 1 Branch
 0 Tags
 Activity
Public repository
nimeshprajapati987-web/Assignment-1
Name	
nimeshprajapati987-web
nimeshprajapati987-web
13 hours ago
Assignment 1
last week
README.md
13 hours ago
Repository files navigation
README
// What do you mean by Structures? // Answer #include <stdio.h>

struct Student { int roll; char name[50]; float marks; };

int main() { struct Student s = {1, "Virat", 95.5}; printf("%d %s %.2f", s.roll, s.name, s.marks); return 0; } // output 1 Virat 95.50 // What do you mean by array and pointer array? // Answer #include <stdio.h>

int main() { int a[3] = {10, 20, 30}; int *p[3] = {a, a+1, a+2};

printf("%d %d %d\n", a[0], a[1], a[2]);
printf("%d %d %d", *p[0], *p[1], *p[2]);

return 0;
} // Output 10 20 30 10 20 30 //compare two structures variables by using the comparison operator (not equal and equal) // Answer #include <stdio.h> #include <string.h>

struct Student { int roll; char name[20]; };

int main() { struct Student s1 = {1, "Virat"}, s2 = {1, "Virat"};

if (s1.roll == s2.roll && strcmp(s1.name, s2.name) == 0)
    printf("Equal");
else
    printf("Not Equal");

return 0;
} //Output Equal //perform an arithmetic operations on structures //Answer #include <stdio.h>

struct Numbers { int a, b; };

int main() { struct Numbers n = {10, 5}; printf("Addition = %d\n", n.a + n.b); printf("Subtraction = %d\n", n.a - n.b); printf("Multiplication = %d\n", n.a * n.b); printf("Division = %d\n", n.a / n.b); return 0; } // Output Addition = 15 Subtraction = 5 Multiplication = 50 Division = 2

Releases
No releases published
Packages
No packages published
Footer
© 2025 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Community
Docs
Contact
Manage cookies
Do not share my personal information
