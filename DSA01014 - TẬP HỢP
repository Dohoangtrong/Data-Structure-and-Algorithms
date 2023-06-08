#include <iostream>
using namespace std;
 
int count = 0;
int n, k, s;
void dequy_ql (int x, int d, int S)
{
	if (S>s) return;
	if (d==0)
	{
		if (S==s) count++;
	}
	else
	{
		for (int i=x+1; i<=n; i++)
		{
			dequy_ql (i, d-1, S+i);
		}
	}
}
 
int main ()
{
	while (1)
	{
		cin>>n>>k>>s;
		if (n==0 && k==0 && s==0) break;
		count=0;
		dequy_ql (0, k, 0);
		cout<<count<<endl;
	}
	return 0;
}
