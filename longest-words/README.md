Escreva um programa que retorne a maior palavra de uma sentença. Se houver mais do que uma palavra na frase com o mesmo número de letras, você deve retornar ambas. Você não pode retornar palavras duplicadas, devem ser ignorados alterações de caixa. exemplo:

console.log(longestWords("You are just an old antidisestablishmentarian")); // => ["antidisestablishmentarian"]
console.log(longestWords("I gave a present to my parents")); // => ["present", "parents"]
console.log(longestWords("Buffalo buffalo Buffalo buffalo buffalo buffalo Buffalo buffalo")); // => ["buffalo"]
console.log(longestWords("mais mais tipo tipo tudo tudo")); // => ["mais", "tipo", "tudo"]