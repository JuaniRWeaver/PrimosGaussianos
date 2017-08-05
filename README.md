# PrimosGaussianos
Punto 2, tarea 1
x=1;
y=1;
z=x^2 + y^2;
  if isprime(z)
    D=[x,y];
    disp(D)
  end
for i=1:10
  y=1+i;
    if isprime(z)
      for j=1:10
        x=j+1;
          if isprime(z)
            disp(D)
          end
      end
    end
end
