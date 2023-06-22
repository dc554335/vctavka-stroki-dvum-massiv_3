#include<iostream>

using namespace std;


cin >> k; //вводим номер строки для добавления
if (k < 0, k > n - 1, n +1 > n2)
cout << "error";
else
{
   for (int i = n; i > k; --i) //выполняем сдвиг строки
  a[i] = a[i - 1];
  ++n; //Увелиличиваем текущее строк в массиве
  a[k] =
  //выделяем память под новую строку массива и заполняем ее 
  new int[m];
  for (int j = 0; j < m; ++j)
  {
  cout << "a [" << k << "] [" << j << "] = ";
  cin >> a [k] [j];
  }
  print (a, n, m); //выводим измененный массив
}
deleteMas(a, n);
return 0;
