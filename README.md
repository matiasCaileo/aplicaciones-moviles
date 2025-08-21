fun main() {
    // 1. VARIABLES Y OPERADORES
    val numeroEntero: Int = 10
    val numeroDecimal: Double = 4.5

    val suma = numeroEntero + numeroDecimal
    val resta = numeroEntero - numeroDecimal
    val multiplicacion = numeroEntero * numeroDecimal
    val division = numeroEntero / numeroDecimal

    println("La suma es: $suma")
    println("La resta es: $resta")
    println("La multiplicación es: $multiplicacion")
    println("La división es: $division")

    // 2. SEGURIDAD ANTE NULOS
    var texto: String? = "Hola Kotlin"
    println("Longitud del texto: ${texto?.length}")

    texto = null
    println("Longitud después de asignar null: ${texto?.length}")
    
    // 3. LÓGICA CONDICIONAL CON WHEN
    val numeroDia: Int = 3
    val dia = when (numeroDia) {
        1 -> "Lunes"
        2 -> "Martes"
        3 -> "Miércoles"
        4 -> "Jueves"
        5 -> "Viernes"
        6 -> "Sábado"
        7 -> "Domingo"
        else -> "Número no válido"
    }
    println("El día correspondiente es: $dia")

    
}
