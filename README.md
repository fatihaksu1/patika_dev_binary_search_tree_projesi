# patika_dev_binary_search_tree_projesi

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root 7'dir. 5, 7'den küçük olduğu için soluna gider.

```
      7
     /
    5
```

1 sayısı 7 ve 5'ten küçük olduğu için en sola gider.

```
          7
         /
        5
       /
      1
```
8 sayısı, 7 sayısından büyük olduğu için sağına gider.
```
          7
         / \
        5   8
       /
      1
```
3 sayısı, 7 sayısından küçük olduğu için soluna; 5 sayısından küçük olduğu için soluna ve 1 sayısından büyük olduğu için sağına yazılır.
```
          7
         / \
        5   8
       / 
      1
       \
        3
```

6 sayısı, 7 sayısından küçük olduğu için soluna; 5 sayısından büyük olduğu için sağına yazılır.
```
          7
         / \
        5   8
       / \
      1   6
       \
        3
```
0 sayısı, en küçük olduğu için rootun en soluna yazılır.
```
          7
         / \
        5   8
       / \
      1   6
     / \
    0   3
```
9 sayısı, 7'den ve 8'den büyük olduğu için rootun en sağına yazılır.
```
          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
```
4 sayısı, 7 sayısından küçük olduğu için soluna; 5 sayısından küçük olduğu için soluna; 1 sayısından büyük olduğu için sağına; 3 sayısından büyük olduğu için sağına yazılır.
```
          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
         \
          4
```
2 sayısı, 7'den küçük olduğu için soluna; 5'ten küçük olduğu için soluna; 1'den büyük olduğu için sağına; 3'ten küçük olduğu için soluna yazılır.
```
          7 ------> Root
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
       / \
      2   4
```
#### Böylece binary search tree tamamnlanmış olur.
[Patika dev'e gitmek için](https://www.patika.dev/tr)
[Profilime gitmek için](https://app.patika.dev/fatihaksu)


