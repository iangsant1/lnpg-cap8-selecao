 --- PYTHON  ---
j, i = -3, 0
while i < 3 and j <= 0:
    val = j + 2
    if val == 3 or val == 2: j -= 1
    elif val == 0: j += 2
    else: j = 0
    if j <= 0:
        j = 3 - i
        i += 1

// --- JAVA  ---
int j = -3;
for (int i = 0; i < 3 && j <= 0; i++) {
    if (j + 2 == 3 || j + 2 == 2) {
        j--;
    } else if (j + 2 == 0) {
        j += 2;
    } else {
        j = 0;
    }
    if (j <= 0) j = 3 - i;
}

// --- JAVASCRIPT  ---
let j = -3;
for (let i = 0; i < 3 && j <= 0; i++) {
    const val = j + 2;
    if ([2, 3].includes(val)) j--;
    else if (val === 0) j += 2;
    else j = 0;
    if (j <= 0) j = 3 - i;
}
