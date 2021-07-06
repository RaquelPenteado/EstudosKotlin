## Kotlin :mobile_phone_off:

_Operador in_

const val MIN_AGE = 16
const val MAX_AGE = 68
fun main() {
    var idade = (10..100).random()
    println(idade)
    println(idade in MIN_AGE..MAX_AGE) //operador in que facilita e minimiza o programa
    println(idade >= MIN_AGE && idade <= MAX_AGE)
}

