## Estruturas de Repetição :repeat:

fun main(){
   letters()
    }

fun downTo(){
    for(i in 20 downTo 0){
       println("$i ")
    }
}

fun until(){
    for(i in 1 until 10){
        println("$i")
    }
}

fun step(num:Int){
    for(i in 0..10 step num){
        println("$i")
    }
}

fun letters(){
    var array = "string"
    for(l in array){
        print(l.toUpperCase())
    }
}



