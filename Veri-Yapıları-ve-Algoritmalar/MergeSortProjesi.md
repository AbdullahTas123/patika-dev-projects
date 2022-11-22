# Soru 1
[16,21,11,8,12,22] -> Merge Sort

Soru 1.1 Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Soru 1.2 Big-O gösterimini yazınız.

# Cevap 1
## Cevap 1.1 Aşamalar

                                               [16,21,11,8,12,22] 
                                                  /          \
                                                 /            \
                                            [16,21,11]      [8,12,22]
                                               / \             /  \
                                              /   \           /    \
                                         [16,21]   [11]    [8,12]  [22]
                                            / \     \        / \      \
                                           /   \     \      /   \      \
                                        [16]   [21]  [11]  [8]   [12]  [22]
                                          \      /    /      \     /    / 
                                           \    /    /        \   /    /
                                           [11,16,21]         [8,12,22]
                                               \                  /
                                                \                /
                                                [8,11,12,16,21,22]

## Cevap 1.2 Big-O
n, n/2, n,4 ... -> 2^x = n -> O(nlogn)