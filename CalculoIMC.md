algoritmo "CalculoIMC"
var
     m, a, imc: real
inicio
      escreva ("Massa (KG): ")
      leia (m)
      escreva ("Altura (M): ")
      leia (a)

      imc <- m / (a ^ 2)

      escreval ("IMC: ", imc:5:2)

      se (imc < 17) e (imc <= 18.5) entao
         escreva ("Abaixo do Peso")
      senao
          se (imc >18.5) e (imc<=25) entao
             escreva ("Peso Ideal")
      senao
           se (imc >25) e (imc <=30) entao
              escreva ("Sobrepeso")
      senao
           se (imc >30) e (imc <=35) entao
              escreva ("Obesidade")
      senao
           se (imc >35) e (imc <=40) entao
              escreva ("Obesidade Severa")
      senao
              escreva ("Obesidade Morbida")
              FimSe
            Fimse
          Fimse
        FimSe
     FimsE
fimalgoritmo