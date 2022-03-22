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
