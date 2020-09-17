procedure Absmax(a) Size:(n, m) Result:(y) Subscripts:(i, k);
    value n, m; array a; integer n, m, i, k; real y;
comment Наибольший элемент матрицы a, размера n на m 
 передаётся в виде результата в y, а его индексы — в параметры i и k;
begin integer p, q;
    y := 0; i := k := 1;
    for p:=1 step 1 until n do
      for q:=1 step 1 until m do
        if abs(a[p, q]) > y then
        begin y := abs(a[p, q]);
          i := p; k := q
        end
end Absmax
