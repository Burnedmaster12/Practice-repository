# Practice-repository
To practice all the programs from march 14-31
1. Write a program to find the distance between two points
void input(float *x1, float *y1, float *x2, float *y2);
void find_distance(float x1, float y1, float x2, float y2, float *area);
void output(float x1, float y1,float x2, float y2, float area);
input:
1 1 2 2
output:
the distance between point (1.000000,1.000000) and (2.000000,2.000000) is with 1.4142


2. Write a program to find whether the three lines form a triangle.
void input_line(float *x1, float *y1);
int is_triangle(float x1, float y1, float x2, float y2,float x3, float y3)
void output(float x1, float y1, float x2, float y2,float x3, float y3, int istriangle)


3. Write a program find whether a given number is a prime number.
int input_number();
int is_prime(int n);
void output(int n, int is_prime);
input:
3
output:
3 is a prime number.


4. Write a program to find nth number in fibonacci sequence.
Fibonacci sequence consists of 0,1,1,2,3,5,8,13,21........
int input();
int find_fibo(int n);
void output(int n, int fibo);


5. Write a program to find all the prime numbers between erotosthenes sieve method.
int input_array_size();
void init_array(int n, int a[n];
void erotosthenes_sieve(int n, int a[n]);
void out_put(int n, int a[n]);
input:
100
output:
2,3,7,11,13,19,23,29,31,...


6. Write a program to find the index of a substring of a string.
void input_string(char *a);
int str_reverse(char *string, char *substring);
void output(char *string, char *substring, int index);
input:
helloworldhello
world
output:
The index of world in helloworldhello is 5


7. Write a program to find the length of a line.
struct _point {
float x,y;
};
typedef struct _point Point;
struct _line
{
Point p1,p2;
float distance;
};
typedef struct _line Line
Point input_point();
Line input_line();
void find_length(Line *l);
void output(Line l);


8. Write a program to find the permeter of a polygon
struct _point {
float x,y;
};
typedef struct _point Point;
struct _line
{
Point p1,p2;
float distance;
};
struct _line Line;
struct _polygon {
int n;
Line l[100];
float perimenter;
}
int input_n();
int input_polygon( int n, Polygon *p);
Line input_line();
void input_n_lines(int n, Line l[n]);
void find_perimeter(Polygon *p);
void output(Polygon p);





                     SET 3

9. Write a program to find sum of two fractions
void input(int *num1, int *den1, int *num2, int *den2);
void add(int num1,int den1, int num2, int den2, int *num3, int *den3);
void output(int num1, int den1, int num2, int den2, int num3, int den3);
input:
1 4
1 2
output:
1/2 + 1/4 = 3/4


10. Write a program to find the smallest of three fractions.
struct _fraction
{
int num,den;
};
typedef _fraction Fraction
Fraction input_fraction();
Fraction Largest_fraction(Fraction f1, Fraction f2, Fraction f3)
void output(Fraction f1, Fraction f2, Fraction f3, Fraction largest)


11. Write a program find the nCr given n and r.
int input_n_and_r(int *n, int *r)
int ncr(int n, int r);
void output(int n, int r, int result);


12. Write a program to evaluate a polynomial at a given point using horners method.
int input_degree();
float input_x();
void input_coefficients(int n, float a[n]);
float evaluate_polynomial(int n, float a[n], float x);
void out_put(int n, float a[n], float x, float result);
input:
1 1 1
output:
1+1*x + 1*x^2 at 1.000000 is 1.000000


13. write a program to find the index of the largest number in an array.
int input_size();
void input_array(int n, int a[n]);
int find_largest(int n, int a[n]);
void out_put(int n, int a[n], int largest);


14. Write a program to count the number of words in a string using strtok ( string.h)
void input_string(char *a);
int count_words(char *string);
void output(char *string, int no_words);
input:
hello world hello

output:
3


15. Write a program to add two fractions.
struct _fraction
{
int num,den;
};
typedef _fraction Fraction;
int find_gcd(int a, int b);
Fraction input_fraction();
Fraction add_fractions(Fraction f1, Fraction f2)
void output(Fraction f1, Fraction f2, Fraction f3, Fraction sum)


16. Write program to add n fractions
struct _fraction
{
int num,den;
};
typedef _fraction Fraction;
int find_gcd(int a, int b);
Fraction input_fraction();
void input_in_fractions(int n, Fraction f[n]);
Fraction add_fractions(Fraction f1, Fraction f2);
Fraction add_n_fractions(int n,Fraction f[n]);
void output(int n, Fraction f[n], Fraction sum);


                  SET 4
    17. Write a program to find the weight of the camel given height, length and stomach radius. weight = pi * stomach_raduius^3 * sqrt(height * length). using four functions and following function signatures.


float input_radius();
float input_heigth();
float input_length();
float find_weight(float radius, float height, float length);
void output(float radius, float height, float length, float weight);
and int main()


18. Write a program to find the weight of the camel given height, length and stomach radius. weight = pi * stomach_raduius^3 * sqrt(height * length). using four functions and following function signatures.
struct camel {
float radius, height, length, weight;
};
typedef struct camel Camel;
Camel input(); /* do not take weight as input from the user */
void find_weight(Camel *c); /*passing address variable */
void output(Camel c);
and int main()


19. When a camel is
a) sick its stomach_radius is less than height and less than length.
b) happy its height is less than length and less than stomach_radius.
c) tense its length is less than height and stomach_radius.
Write a program to find whether a camel is sick, happy, or tense with functions and structure.
struct camel {
float radius, height, length, weight;
int mood; /* sick = 0, happy = 1, tense = 2 */
};


typedef struct camel Camel;
Camel input(); /* do not take weight and mood as input from the user */
void find_weight(Camel *c); /*passing address variable */
void find_mood(Camel *c);
void output(Camel c);
and int main()


20. Write a program to find borga^x given x.
The formula for finding borga^x


1 + x/3! + x^2/5! + x^3/7! .....
stop when the next term is less 0.000001 With four functions.


21. Write a program to sort a an array using bubble sort.
use following function prototypes.
void input(int n, int a[n]);
void bubble_sort(int n, int a[n]);
void output_array(int n, int a[n]); /* print all the elements of the array */
and main.


22. Write a program to search for an element using binary search.
use following function prototypes.
void input(int n, int a[n]);
void sort(int n, int a[n]);
int bin_search(int n, int a[n], int key);
void print_position(int n, int a[n], int key, int position);
and main.


23. Write a program to find if a name is a nice name.
A name is nice if it has at least 2 vowels and 2 consonants in it.
with four functions.


void input_name(char *s);
int is_name_nice(char *s);
void print_name(char *s, int is_nice);
and
main().


Array of Structures


24. Write program to find the weight of a truck load of n camels.
Take input
a) truck weight and
b) height, radius and length of n camels
and compute the total truck weight. ( Truck weight + weight of the camels)
With functions.


Call functions from earlier programs where required.
float input_truck_weight();
int input_no_camels();
void input_camel_details(int n, Camel c[n]);
float comput_total_weight(int n, Camel c[n], float truck_weight);
void ouput(float total_truck_weight);
and
int main()