# Soru 1
[7,5,1,8,3,6,0,9,4,2] -> dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

# Cevap 1
- Root = 3
- 7 sayısı 3 ten büyük olduğu için sağ tarafa

                                                        3
                                                         \
                                                          7

- 5 sayısı 3 ten büyük olduğu için sağ tarafa, 7 den küçük olduğu için sol tarafa

                                                        3
                                                          \
                                                           7
                                                          /
                                                         5
- 1 sayısı 3 ten küçük olduğu için sol tarafa

                                                        3
                                                      /   \
                                                     1     7
                                                          /
                                                         5

- 8 sayısı 3 ten büyük olduğu için sağ tarafa, 7 den büyük olduğu için sağ tarafa

                                                        3
                                                      /   \
                                                     1     7
                                                          / \
                                                         5   8

- 6 sayısı 3 ten büyük olduğu için sağ tarafa, 1 den büyük olduğu için sağ tafa

                                                        3
                                                      /   \
                                                     1      7
                                                      \    / \
                                                       6  5   8

- 0 sayısı 3 ten küçük olduğu için sol tarafa, 1 den küçük olduğu için sol tarafa

                                                        3
                                                      /    \
                                                     1       7
                                                    /  \    / \
                                                   0    6  5   8

- 9 sayısı 3 ten büyük olduğu için sağ tarafa, 7 den büyük olduğu için sağ tarafa, 8 den büyük olduğu için sağ tarafa

                                                        3
                                                      /    \
                                                     1       7
                                                    /  \    / \
                                                   0    6  5   8
                                                                \
                                                                 9

- 4 sayısı 3 ten büyük olduğu için sağ tarafa, 7 den küçük olduğu için sol tarafa, 5 ten küçük olduğu için sol tarafa

                                                        3
                                                      /    \
                                                     1       7
                                                    /  \    / \
                                                   0    6  5   8
                                                          /     \
                                                         4       9

- 2 sayısı 3 ten küçük olduğu için sol tarafa, 1 den büyük olduğu için sağ tarafa, 6 dan küçük olduğu için sol tarafa

                                                         3
                                                      /     \
                                                     1        7
                                                    /  \     / \
                                                   0    6   5   8
                                                       /   /     \
                                                      2   4       9

# Patika Profilim
- [Abdullah Taş - Patika](https://app.patika.dev/AbdullahTas123)