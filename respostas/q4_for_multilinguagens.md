for (int i = 0, j = 17; i < 100; i++, j--) {
    sum += i * j + 3;
}

for (let i = 0, j = 17; i < 100; i++, j--) {
    sum += i * j + 3;
}

for i, j in zip(range(100), range(17, 17 - 100, -1)):
    sum += i * j + 3

for i, j := 0, 17; i < 100; i, j = i+1, j-1 {
    sum += i * j + 3
}

for (i, j) in (0..100).zip((0..).map(|x| 17 - x)) {
    sum += i * j + 3;
}
