# Implementaion
```c++

#include <bits/stdc++.h>

using namespace std;
class Solution
{
private:
    int testCases, n;

public:
    Solution()
    {
        cin >> testCases;
    }

    void solveAll()
    {
        while (testCases--)
        {
            takeInput();
            ans();
        }
    }

private:
    void takeInput()
    {
        cin >> n;
    }
    void ans()
    {
        if (n % 2 != 0)
        {
            cout << "NO" << endl;
            return;
        }
        cout << "YES" << endl;
        for (int i = 1; i <= n / 2; i++)
        {
            cout << ((i % 2 == 0) ? "BB" : "AA");
        }
        cout << endl;
    }
};

int main()
{
    Solution solution = Solution();
    solution.solveAll();
    return 0;
}


```
