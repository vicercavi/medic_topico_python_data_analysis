Aquí tienes los conceptos detallados con ejemplos prácticos para la **Semana 1: Introducción a Python**.  

---

## **Semana 1: Introducción a Python**  

### **1️⃣ Instalación de Python y uso de Google Colab/Jupyter Notebook**  
#### 🔹 **Conceptos clave**  
- **Python** es un lenguaje de programación de alto nivel, ideal para análisis de datos e inteligencia artificial.  
- **Google Colab** y **Jupyter Notebook** permiten ejecutar código Python en celdas, facilitando la exploración de datos.  

#### 🔹 **Ejemplo práctico**  
1. **Ejecutar código en Google Colab**  
   - Abre Google Colab ([https://colab.research.google.com](https://colab.research.google.com))  
   - Crea un nuevo cuaderno y escribe:  
   ```python
   print("¡Hola, mundo!")
   ```
   - Presiona **Shift + Enter** para ejecutar.  

2. **Instalar bibliotecas en Google Colab**  
   ```python
   !pip install numpy pandas matplotlib
   ```

---

### **2️⃣ Variables y Tipos de Datos**  
#### 🔹 **Conceptos clave**  
- Una **variable** es un contenedor para almacenar valores.  
- Python tiene varios **tipos de datos**, como:  
  - `int` (números enteros)  
  - `float` (números decimales)  
  - `str` (cadenas de texto)  
  - `bool` (valores booleanos: `True` o `False`)  

#### 🔹 **Ejemplo práctico**  
```python
nombre = "Juan"
edad = 30
peso = 72.5
es_paciente_diabetico = True

print(f"Paciente: {nombre}, Edad: {edad}, Peso: {peso} kg, ¿Diabético?: {es_paciente_diabetico}")
```
💡 *Este código almacena información de un paciente y la muestra en pantalla.*  

---

### **3️⃣ Estructuras de Control (if, for, while)**  
#### 🔹 **Conceptos clave**  
- **Condicionales (`if`)** permiten ejecutar código solo si una condición se cumple.  
- **Bucles (`for` y `while`)** se usan para repetir código múltiples veces.  

#### 🔹 **Ejemplo práctico: Uso de `if` para verificar IMC**  
```python
imc = 28

if imc < 18.5:
    print("Bajo peso")
elif 18.5 <= imc < 24.9:
    print("Peso normal")
else:
    print("Sobrepeso o obesidad")
```

#### 🔹 **Ejemplo práctico: Uso de `for` para iterar sobre una lista de pacientes**  
```python
pacientes = ["Ana", "Carlos", "María"]

for paciente in pacientes:
    print(f"Atendiendo a {paciente}")
```

#### 🔹 **Ejemplo práctico: Uso de `while` para contar pulsaciones**  
```python
pulsaciones = 80

while pulsaciones > 60:
    print(f"Pulsaciones: {pulsaciones}")
    pulsaciones -= 5  # Simula la reducción del ritmo cardíaco
```

---

### **4️⃣ Listas, Diccionarios y Tuplas**  
#### 🔹 **Conceptos clave**  
- **Listas (`list`)**: Conjunto de elementos modificables.  
- **Diccionarios (`dict`)**: Almacenan datos en pares clave-valor.  
- **Tuplas (`tuple`)**: Similares a las listas, pero inmutables (no se pueden modificar).  

#### 🔹 **Ejemplo práctico: Lista de edades de pacientes**  
```python
edades = [25, 34, 50, 29]
print("Edad del primer paciente:", edades[0])
```

#### 🔹 **Ejemplo práctico: Diccionario con datos de un paciente**  
```python
paciente = {"nombre": "Luis", "edad": 40, "peso": 75.2}
print(f"{paciente['nombre']} tiene {paciente['edad']} años y pesa {paciente['peso']} kg")
```

#### 🔹 **Ejemplo práctico: Tupla con tipos de sangre**  
```python
tipos_sangre = ("A", "B", "AB", "O")
print("Tipos de sangre disponibles:", tipos_sangre)
```

---

### **📝 Ejercicio Final: Script para calcular el IMC de pacientes**  
#### 🔹 **Objetivo**  
- Crear un programa en Python que solicite el peso y la altura de un paciente y calcule su IMC.  
- El programa debe indicar si el paciente tiene **bajo peso, peso normal, sobrepeso o obesidad**.  

#### 🔹 **Código base**  
```python
# Solicitar datos al usuario
peso = float(input("Ingrese su peso en kg: "))
altura = float(input("Ingrese su altura en metros: "))

# Calcular IMC
imc = peso / (altura ** 2)

# Clasificación del IMC
if imc < 18.5:
    categoria = "Bajo peso"
elif 18.5 <= imc < 24.9:
    categoria = "Peso normal"
elif 25 <= imc < 29.9:
    categoria = "Sobrepeso"
else:
    categoria = "Obesidad"

# Mostrar resultado
print(f"Su IMC es {imc:.2f}, categoría: {categoria}")
```
💡 *Este script interactivo permite ingresar peso y altura, calcula el IMC y clasifica al paciente según su índice.*  

---

### **🔹 Resumen de lo aprendido esta semana:**  
✅ Instalación y uso de Python en Google Colab.  
✅ Declaración de variables y tipos de datos.  
✅ Uso de estructuras de control (`if`, `for`, `while`).  
✅ Manejo de listas, diccionarios y tuplas.  
✅ Desarrollo de un script para calcular el IMC.  

---

🚀 **¿Te gustaría agregar más ejemplos o hacer ejercicios adicionales?**
