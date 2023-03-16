# Cálculo diferencial

## Contenido

## Reglas de Diferenciación

### Fórmulas Generales

1. La derivada de una constante es cero.
   $${{d}\over{dx}}(c)=0$$

    Ejemplo: $f(x)=5$

    Solución: $f'(x)=0$
2. La derivada de la variable es 1.

   $${{d}\over{dx}}(x)=1$$

3. La derivada de la variable expuesta a un exponente.

   $${{d}\over{dx}}(x^n)=nx^{n-1}$$

   Ejemplo: $f(x)=x^2$

   Solución:

   $${d\over{dx}}x^2=2x^{2-1}$$
   $$=2x$$

4. La derivada de una constante por una función es igual a la constante por la derivada de la función:
   $${{d}\over{dx}}[cf(x)]=c {d\over{dx}}f(x)$$

   Ejemplo: $g(x)=3x^2$

   Solución:

   Si $c=3$ y $f(x)=x^2$, entonces $g(x)=3f(x)$ y su derivada será:

   $${{d}\over{dx}}g(x)=3{d\over{dx}}f(x)$$

   sustituyendo:

   $${{d}\over{dx}}3x^2=3{d\over{dx}}x^2$$

   Utilizando la fórmula 3:

   $$=3(2x^{2-1})$$
   $$=6x^{1}$$
   $$=6x$$

5. La derivada de una suma o resta de funciones es igual a la suma o resta de las derivadas.

   $${{d}\over{dx}}[f(x)(+/-){g(x)}]=f'(x)(+/-){g(x)}$$

   Ejemplo: $p(x)=3x^2+5x$

   Solución:

   Si $f(x)=3x^2$ y $g(x)=5x$, entonces $p(x)=f(x)+g(x)$ y su derivada será:

    $${d\over{dx}}p(x)={d\over{dx}}f(x)+{d\over{dx}}g(x)$$

    Sustituyendo:

    $${d\over{dx}}(3x^2+5x)={d\over{dx}}3x^2+{d\over{dx}}5x$$

    Utilizando la fórmula 4:

    $$=3{d\over{dx}}x^2+5{d\over{dx}}x$$

    Finalmente aplicar la fórmula 3 para solucionar.

    $$=3(2x^{2-1})+5(1x^{1-1})$$
    $$=6x^{1}+5x^{0}$$
    $$=6x+5$$

6. Derivada del producto de 2 funciones es igual a la suma de los conjugados de las funciones y sus derivadas.

   $${{d}\over{dx}}[f(x){g(x)}]=f(x){d\over{dx}}g(x)+g(x){d\over{dx}}f(x)$$
    (Regla del producto)

    Ejemplo: $p(x)=3x(x^2-5)$

    Si $f(x)=3x$ y $g(x)=x^2-5$ que son los que se están multiplicando, $p(x)=f(x)g(x)$ y su derivada será:

    $${{d}\over{dx}}[f(x){g(x)}]=f(x){d\over{dx}}g(x)+g(x){d\over{dx}}f(x)$$

    Sustituyendo:

    $${{d}\over{dx}}3x(x^2-5)$$
    $$=3x{{d}\over{dx}}(x^2-5)+(x^2-5){{d}\over{dx}}3x$$

    Aplicando la fórmula 5 en la primera derivada tenemos:

    $$=3x({d\over{dx}}x^2-{{d}\over{dx}}5)+(x^2-5){d\over{dx}}3x$$

    Aplicando la fórmula 3 en la segunda derivada:

    $$=3x({d\over{dx}}x^2-{{d}\over{dx}}5)+(x^2-5)(3{d\over{dx}}x)$$

    Resolvemos:

    $$=3x(2x-0)+(x^2-5)[3(1)]$$
    $$=6x^2+(x^2-5)(3)$$
    $$=6x^2+3x^2-15$$
    $$=9x^2-15$$

7. La derivada de una fracción de funciones.

   $${{d}\over{dx}}[{f(x)\over{g(x)}}]={{g(x)f'(x)-f(x)g'(x)}\over{[g(x)]^2}}$$
   (Regla del cociente)

   Ejemplo:
   $$p(x)={{x^2-3}\over{2x+1}}$$

   Solución:

   Si $f(x)=x^2-3$ y $g(x)=2x+1$ entonces la derivada es:

   $${{d}\over{dx}}{{x^2-3}\over{2x+1}}$$
   $$={{(2x+1){{d}\over{dx}}(x^2-3)-(x^2-3){{d}\over{dx}}(2x+1)}\over{(2x+1)^2}}$$

   $$={{(2x+1)(2x-0)-(x^2-3)(2+0)}\over{(2x+1)^2}}$$
   $$={{(2x+1)(2x)-(x^2-3)(2)}\over{(2x+1)^2}}$$
   $$={{(4x^2+2x)-(2x^2-6)}\over{(2x+1)^2}}$$
   $$={{4x^2+2x-2x^2+6}\over{(2x+1)^2}}$$
   $$={{2x^2+2x+6}\over{(2x+1)^2}}$$

8. Derivada de una función contenida en otra función.
   $${{d}\over{dx}}f(g(x))=f'(g(x))g'(x)$$
   (Regla de la cadena)

   Ejemplo: $f(x)=(x^4+3x)^3$

   Solución:

   Si $g(x)=x^4+3x$ entonces se cumple que $f(g(x))=(x^4+3x)^3$ y se deriva:

   $$f'(g(x))=3(x^4+3x)^{3-1}$$
   $$=f'(g(x))=3(x^4+3x)^{2}$$

   Obteniendo $g'(x)$:

   $$g'(x)={{d}\over{dx}}x^4+{{d}\over{dx}}3x$$
   $$=4x^3+3$$

   Sustituyendo en la fórmula

   $${{d}\over{dx}}f(g(x))=f'(g(x))g'(x)$$

   tenemos:

   $$=3(x^4+3x)^2(4x^3+3)$$

> Abre la tabla completa de derivadas, descargala e imprimela para que la tengas de formulario :point_right: [reglas de diferenciación](img/formulas_dif.png).

## Tarea

Comprueba las siguientes derivadas utilizando el formulario de derivadas.

1. $f(x)=3x^5+2x^3-1, f'(x)=15x^4+6x^2$
2. $f(x)=8x^2+\tan{x}, f'(x)=16x+\sec^2{x}$
3. $f(x)={{2x+3}\over{x-1}}, f'(x)=-{{5}\over{(x-1)^2}}$
