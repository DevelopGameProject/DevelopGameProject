#Сапер

1. При нажатии левой кнопкой мыши на закрытую клетку она открывается. a. Если там мина, конец игры (проигрыш). b. Если мины нет, но вокруг клетки есть мины, отображается цифра, обозначающая количество мин вокруг c. Если мин вокруг нет, отображается пустая открытая клетка и открываются все клетки вокруг нее. Если вокруг нее есть другие пустые клетки, открываем все соседние для каждой пустой и так далее.
2. При нажатии правой кнопкой мыши на закрытую клетку, она помечается флажком. Если на ней уже есть флажок, он убирается.
3. При нажатии левой кнопкой мыши на клетку с флажком ничего не происходит.
4. Если открыты все клетки без мин, конец игры (выигрыш)
5. В интерфейсе отображается количество оставшихся мин (рассчитывается как реальное количество мин минус количество поставленных флажков)
6. При нажатии колесиком на открытую клетку с цифрой открываются все клетки вокруг нее, при условии, что вокруг этой клетки стоит столько флажков, какая цифра на клетке. Алгоритм открытия соседних клеток такой же, как в пункте 1. Вместо колесика такой же эффект должно производить нажатие на левую и правую кнопку одновременно – в качестве усложнения, если останется время.
7. Размер поля и количество мин можно изменить. По умолчанию поле размером 9x9 количество мин 10.

![This is an image](https://github.com/DevelopGameProject/DevelopGameProject/blob/main/docs/project.png)
