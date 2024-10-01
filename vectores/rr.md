# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4

* uno
* dos
* *tres

1. punto 1
2. punto 2
3. punto 3

***negrita***
_italika_
***negrita italika***

```c++
#include <iostream>
#include <vector>
using namespace std;
void imprime(vector<int> v)
{
	system("pause");
	system("cls");
	for (auto elemento : v)
	{
		cout << elemento << ", ";
	}
	cout << endl;
}
int main()
{
	/*vector <int> v;
	//llenar el vector con 0, cinco veces
	v.assign(5, 0);
	imprime(v);
	//inserta 15 en la ultima posicion
	v.push_back(15);
	imprime(v);
	// quitar el ultimo elemento
	v.pop_back();
	imprime(v);
	//inserta el principio un 5 en el vector
	v.insert(v.begin(), 5);
	imprime(v);
	v.erase(v.begin());
	imprime(v);
	//emplace() inserta 25 al principio
	v.emplace(v.begin(), 25);
	imprime(v);
	// emplace_back() insert 20 al final
	v.emplace_back(20);
	//borrar completamente al vector
	v.clear();
	imprime(v);

	//swap entre dos vectores
	*/
	vector <int> v1, v2;
	v1.push_back(1);
	v1.push_back(2);

	v2.push_back(3);
	v2.push_back(4);
	v1.swap(v2);
	imprime(v1);
	imprime(v2);

}
```

![Imagen](https://p325k7wa.twic.pics/high/gundam/gundam-breaker-4/00-page-setup/GB4-header-mobile.png?twic=v1/step=10/quality=80/max=760.jpg)
