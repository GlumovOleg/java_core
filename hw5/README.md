## Task homework:

1. Написать функцию, создающую резервную копию всех файлов в директории(без поддиректорий) во вновь созданную папку ./backup
2. Предположить, что числа в исходном массиве из 9 элементов имеют диапазон[0, 3], и представляют собой, например, состояния ячеек поля для игры в крестики-нолики, где 0 – это пустое поле, 1 – это поле с крестиком, 2 – это поле с ноликом, 3 – резервное значение. Такое предположение позволит хранить в одном числе типа int всё поле 3х3. Записать в файл 9 значений так, чтобы они заняли три байта.
3. (*) - В продолжение 2 дописать "разворачивание" поля игры крестики-нолики из сохраненного в файле состояния (распарсить файл, в зависимости от значений (0-3) нарисовать поле со значками 'х' 'о' '.').