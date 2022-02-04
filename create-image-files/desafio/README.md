# Desafio
Crie um arquivo chamado compute.js com o código a seguir que calcula e exibe a área de um disco usando JavaScript:

#### Computer ks

```bash
var radius = 2.0;
var area = Math.pow(radius, 2) * Math.PI;
console.log(
    `Area of a ${radius} cm disk:
    ${area} cm²`
);
```
Crie uma imagem do Docker que execute o código no arquivo compute.js usando a imagem node:11-alpine que contém o Node.JS. O comando que executa um programa JavaScript usando Node.JS é o ``` node nomde do arquivo ```.