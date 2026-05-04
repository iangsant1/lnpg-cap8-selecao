--- PYTHON ---
k = (j + 13) // 27
while k <= 10:
    k += 1
    i = 3 * k - 1

// --- JAVA ---
int k = (j + 13) / 27;
while (k <= 10) {
    k++;
    int i = 3 * k - 1;
}

// --- SWIFT ---
var k = (j + 13) / 27
while k <= 10 {
    k += 1
    let i = 3 * k - 1
}

-- --- HASKELL ---
let loop k 
      | k <= 10   = let nextK = k + 1
                        nextI = 3 * nextK - 1
                    in loop nextK
      | otherwise = k

// --- SWIFT ---
var k = (j + 13) / 27
while k <= 10 {
    k += 1
    i = 3 * k - 1
}
