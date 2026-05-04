// --- C++ ---
for (int i = 0, j = 17; i < n; i++, j--) sum += i * j + 3;

// --- C# ---
for (int i = 0, j = 17; i < n; i++, j--) sum += i * j + 3;

// --- JAVASCRIPT ---
for (let i = 0, j = 17; i < n; i++, j--) sum += i * j + 3;

// --- GO ---
for i, j := 0, 17; i < n; i, j = i+1, j-1 {
    sum += i * j + 3
}

--- PYTHON ---
for i, j in zip(range(n), range(17, 17 - n, -1)):
    sum += i * j + 3
