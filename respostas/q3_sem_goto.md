j = -3;
int continuar = 1; 
for (i = 0; i < 3 && continuar; i++) {
    int cond = j + 2;
    
    if (cond == 3 || cond == 2) {
        j--;
    } else if (cond == 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j > 0) {
        continuar = 0; 
    } else {
        j = 3 - i;
    }
}
