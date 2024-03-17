### Quick Sort Algorithm

#### Steps:
1. Choose a pivot element from the array. Typically, you can select the last element in the array.
2. Partition the array into two sub-arrays: elements less than the pivot and elements greater than the pivot.
3. Recursively apply the above steps to the sub-arrays.
4. Combine the sorted sub-arrays to obtain the final sorted array.

#### Pseudocode:

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
