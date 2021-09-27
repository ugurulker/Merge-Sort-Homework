## [16,21,11,8,12,22] -> Merge Sort


Yukarıdaki dizinin sort türüne göre aşamalarını yazalım.

                     [16, 21, 11, 8, 12, 22]
                    /                       \
                [16, 21, 11]              [8, 12, 22]
                  /      \                  /     \
             [16, 21]    [11]            [8, 12]  [22]
              /    \       \              /   \     \
            [16]   [21]    [11]         [8]   [12]  [22]
              \      /      /             \    /     /
              [16, 21]    [11]           [8, 12]   [22]
                  \        /                 \      /
                 [11, 16, 21]               [8, 12, 22]
                     \                        /
                      \                      /
                       [8, 11, 12, 16, 21, 22]



Big-O gösterimini yazalım.

logn=x kadar bu işlemi gerçekleştirdik ve her işlemde O(n) Time Complexity gelecek buradan:

**O(nlogn)**