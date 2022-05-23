# pattern-in-c-
#include <iostream>
#include <string>
using namespace std;
void a(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == num - j + 1)
          {
               cout << "A";
          }
          else if (i >= num - j + 1 && i == num / 2)
          {
               cout << "A";
          }

          else
          {
               cout << " ";
          }
     }
     for (int j = 2; j <= num; j++)
     {
          if (i == j)
          {
               cout << "A";
          }
          else if (i >= j && i == num / 2)
          {
               cout << "A";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void b(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if ((i == 1 && j == num) || (i == num / 2 && j == num) || (i == num & j == num))
          {
               cout << " ";
          }
          else if (i == 1 || j == 1 || i == num / 2 || i == num || j == num)
          {
               cout << "B";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void c(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if ((i == 1 && j == 1) || (i == num && j == 1))
          {
               cout << " ";
          }
          else if (i == 1 || j == 1 || i == num)
          {
               cout << "C";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void d(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == num && (i == 1 || i == num))
          {
               cout << " ";
          }
          else if (i == 1 || j == 1 || i == num || j == num)
          {
               cout << "D";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void e(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == 1 || i == 1 || i == num / 2 || i == num)
          {
               cout << "E";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void f(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == 1 || i == 1 || i == num / 2)
          {
               cout << "F";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void g(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if ((i == 1 && j == num) || (i == num && j == num) || (i == 1 && j == 1) || (i == num && j == 1))
          {
               cout << " ";
          }
          else if (i == 1 || j == 1 || i == num || ((j == num) && i >= num - num / 3) || ((i == num - num / 3) && (j >= num - num / 3)))
          {
               cout << "G";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void h(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == num / 2 || j == 1 || j == num)
          {
               cout << "H";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void kk(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j > num / 2 + 1)
          {
               /* code */
          }

          else if (j == 1)
          {
               cout << "K";
          }
          else if (i == num - j - num / 2 + 2 || j == i - num / 2 + 1)
          {
               cout << "K";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void j(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == 1 && i == num)
          {
               cout << " ";
          }
          else if (i == num || (i >= (num - num / 3) && j == 1) || j == num)
          {
               cout << "J";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void l(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == 1 || i == num)
          {
               cout << "L";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void m(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == 1 || j == num)
          {
               cout << "M";
          }
          else if (i == j && j <= num / 2)
          {
               cout << "M";
          }
          else if (j == num - i + 1 && j > num / 2)
          {
               cout << "M";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void n(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == 1 || j == num)
          {
               cout << "N";
          }
          else if (i == j)
          {
               cout << "N";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void o(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if ((i == 1 && (j == 1 || j == num)) || (i == num && (j == 1 || j == num)))
          {
               cout << " ";
          }
          else if (i == 1 || j == 1 || j == num || i == num)
          {
               cout << "O";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void p(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == 1 || i == 1 || i == num / 2 || (j == num && i < num / 2))
          {
               cout << "P";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void q(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if ((i == 1 && (j == 1 || j == num)) || (i == num && (j == 1)))
          {
               cout << " ";
          }
          else if (i == 1 || j == 1 || j == num || i == num)
          {
               cout << "Q";
          }
          else if (i == j && j >= (num - num / 3))
          {
               cout << "Q";
          }

          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void r(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j > num / 2)
          {
          }

          else if (i == 1 || j == 1 || i == num / 2)
          {
               cout << "R";
          }
          else if (i <= num / 2 && j == num / 2)
          {
               cout << "R";
          }
          else if (i == j + num / 2 - 1)
          {
               cout << "R";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void s(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == 1 || i == num / 2 || i == num)
          {
               cout << "S";
          }
          else if (i <= num / 2 && j == 1)
          {
               cout << "S";
          }
          else if (i >= num / 2 && j == num)
          {
               cout << "S";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void t(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == 1 || j == num / 2)
          {
               cout << "T";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void u(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == num || j == 1 || j == num)
          {
               cout << "U";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void v(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == j)
          {
               cout << "V";
          }
          else
          {
               cout << " ";
          }
     }
     for (int j = 1; j <= num; j++)
     {
          if (i == num - j + 1)
          {
               cout << "V";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void w(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (j == 1 || j == num)
          {
               cout << "W";
          }
          else if (i == j && j >= num / 2 + 1)
          {
               cout << "W";
          }
          else if (i == num - j + 1 && j <= num / 2)
          {
               cout << "W";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void x(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == j || i == num - j + 1)
          {
               cout << "X";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void y(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == j && j <= num / 2)
          {
               cout << "Y";
          }
          else if (i == num - j + 1)
          {
               cout << "Y";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
void z(int i)
{
     int num = 10;
     for (int j = 1; j <= num; j++)
     {
          if (i == 1 || i == num || i == num - j + 1)
          {
               cout << "Z";
          }
          else
          {
               cout << " ";
          }
     }
     cout << "  ";
}
int main()
{
     cout<<"Write the name you want pattern for(use small letters only) : ";
     string str;
     getline(cin, str);
     cout<<endl;
     for (int i = 1; i <= 10; i++)
     {
          for (int k = 0; k < str.length(); k++)
          {
               switch (str[k])
               {
               case 'a':
                    a(i);
                    break;
               case 'b':
                    b(i);
                    break;
               case 'c':
                    c(i);
                    break;
               case 'd':
                    d(i);
                    break;
               case 'e':
                    e(i);
                    break;
               case 'f':
                    f(i);
                    break;
               case 'g':
                    g(i);
                    break;
               case 'h':
                    h(i);
                    break;
               case 'i':
                    cout << "I";
                    cout << "  ";
                    break;
               case 'j':
                    j(i);
                    break;
               case 'k':
                    kk(i);
                    break;
               case 'l':
                    l(i);
                    break;
               case 'm':
                    m(i);
                    break;
               case 'n':
                    n(i);
                    break;
               case 'o':
                    o(i);
                    break;
               case 'p':
                    p(i);
                    break;
               case 'q':
                    q(i);
                    break;
               case 'r':
                    r(i);
                    break;
               case 's':
                    s(i);
                    break;
               case 't':
                    t(i);
                    break;
               case 'u':
                    u(i);
                    break;
               case 'v':
                    v(i);
                    break;
               case 'w':
                    w(i);
                    break;
               case 'x':
                    x(i);
                    break;
               case 'y':
                    y(i);
                    break;
               case 'z':
                    z(i);
                    break;
               case ' ' :
                    cout<<"      ";
                    break;
               default:
                    break;
               }
          }
          cout << endl;
     }

     return 0;
}
