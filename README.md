# Calculo-de-IMC
const nome = 'Luiz'
const peso = 76
const altura = 1.70

const imc = peso / (altura * altura)

console.log(imc)

if (imc >= 30) {
  console.log(`${nome} está acima do peso`)

}else 
  console.log(`${nome} não está acima do peso`)
