k = (j + 13) // 27  # Divisão inteira
while k <= 10:
    k += 1
    i = 3 * k - 1


k=10
i=0
k = (j + 13) // 27  
while k <= 10:
    k += 1
    i = 3 * k - 1  

let kInit = (j + 13) `div` 27
let loop k | k > 10    = (k, i) -- 'i' dependeria do contexto anterior
           | otherwise = let nextK = k + 1
                             nextI = 3 * nextK - 1
                         in loop nextK

var k = (j + 13) / 27
while k <= 10 {
    k += 1
    i = 3 * k - 1
}  