Znak rozdzielający = " , "

Każdy wiersz zawiera 33 wartości.
Pierwsze 32 wartości każdego wiersza to współrzędne (x,y) kolejnych punktów charakterystycznych.

Punkty charakterystyczne to:
czubek_głowy, górny_odcinek_szyi, prawy_bark, prawy_łokieć,
prawy_nadgarstek, tułów, lewy_bark, lewy_łokieć, lewy_nadgarstek,
miednica, prawe_biodro, prawe_kolano, prawa_kostka, lewe_biodro,
lewe_kolano, lewa_kostka

Więc każdy wiersz zawiera:
(x,y) czubka głowy, (x,y) górnego odcinka szyi, (x,y) prawego barku .....

Współrzędne są znormalizowane do zakresu [-1,1], ale nie są znormalizowane przez odjęcie
wartości średnich i podzielenie przez odchylenia standardowe.

33-cia wartość w każdym wierszu to identyfikator asany:
0 - pozycja drzewa
1 - pozycja wojownika I
2 - pozycja psa z głową w dół
3 - pozycja góry
4 - pozycja wojownika II
5 - pozycja łuku
6 - pozycja wielbłąda
7 - pozycja deski
8 - pozycja krzesła
9 - pozycja girlandy
10 - pozycja nieznana

----------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------

delimiter = " , "

Each row contains 33 values.
First 32 values in each row are (x,y) coordinates for all keypoints.

Keypoints are: 
body_parts = ['head_top', 'upper_neck', 'right_shoulder', 'right_elbow',
              'right_wrist', 'thorax', 'left_shoulder', 'left_elbow', 'left_wrist',
              'pelvis', 'right_hip', 'right_knee', 'right_ankle', 'left_hip', 'left_knee', 'left_ankle']

so each row is:
(x,y) for head_top, (x,y) for upper_neck, (x,y) for right_shoulder .....

Coordinates are normalized to [-1,1], but they are not normalized by subtracting mean value and 
dividing by standard deviation.

The 33rd value in each row is yoga pose id:
0 - tree pose
1 - warrior I pose
2 - downward dog pose
3 - mountain pose
4 - warrior II pose
5 - bow pose pose
6 - camel pose
7 - plank pose
8 - chair pose
9 - garland pose
10 - unknown pose
