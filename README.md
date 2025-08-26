# Programación Básica C++

🧩 Módulo 1: Paradigmas de Programación en C++

🎯 Objetivos del módulo:
Comprender qué es un paradigma de programación.
Reconocer los principales paradigmas compatibles con C++.
Aplicar un ejemplo básico de programación estructurada y otro de programación orientada a objetos.

📘 Teoría: ¿Qué es un paradigma de programación?
Un paradigma de programación es un estilo o enfoque para resolver problemas a través del código. Cada paradigma propone una manera distinta de estructurar los programas. C++ es un lenguaje multiparadigma, lo que significa que permite programar en diferentes estilos:

✅ Principales paradigmas en C++:
Paradigma estructurado (procedural):
Organiza el código en funciones.
Usa estructuras de control como if, for, while.
Es el estilo clásico del lenguaje C.
Paradigma orientado a objetos (POO):
Utiliza clases y objetos.
Se basa en los conceptos de encapsulamiento, herencia y polimorfismo.
C++ fue uno de los primeros lenguajes en combinar programación estructurada y POO.
(Opcionalmente: funcional y genérico):
Con C++ moderno (C++11 en adelante), también se pueden aplicar elementos de programación funcional (como lambda) y genérica (con plantillas).

🧪 Ejemplo 1: Programación Estructurada en C++
// Ejemplo de programación estructurada: calcular el área de un rectángulo
#include <iostream>
using namespace std;
float calcularArea(float base, float altura) {
    return base * altura;
}

int main() {
    float base = 5.0;
    float altura = 3.0;
    float area = calcularArea(base, altura);

    cout << "El área del rectángulo es: " << area << endl;
    return 0;
}

🧪 Ejemplo 2: Programación Orientada a Objetos en C++
// Ejemplo de POO: clase Rectangulo con método para calcular el área
#include <iostream>
using namespace std;

class Rectangulo {
private:
    float base;
    float altura;

public:
    Rectangulo(float b, float h) {
        base = b;
        altura = h;
    }

    float calcularArea() {
        return base * altura;
    }
};

int main() {
    Rectangulo r(5.0, 3.0);
    cout << "El área del rectángulo es: " << r.calcularArea() << endl;
    return 0;
}

🧠 Preguntas de reflexión:

¿Qué diferencias observas entre los dos estilos de programación?

¿Cuál te parece más fácil de entender y mantener?

¿Cuándo convendría usar uno sobre el otro?

✅ Tareas sugeridas:

Investiga qué otros lenguajes son multiparadigma como C++.
