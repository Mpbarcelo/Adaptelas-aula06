# Atividade Prática 6 - Fundamentos do JavaScript

Esta atividade contém 6 exercícios práticos para aplicar os conceitos ensinados na aula 06 de Fundamentos do JavaScript, parte do curso Adaptelas oferecido pela Adapti.

## Instruções da Atividade

### Criação dos Arquivos

1. Abra o VS Code.
2. Para cada problema apresentado, crie um arquivo JavaScript separado.
3. Nomeie os arquivos de acordo com o número da atividade:
   - `scripts_1.js` para o problema 1
   - `scripts_2.js` para o problema 2
   - `scripts_3.js` para o problema 3
   - `scripts_4.js` para o problema 4
   - `scripts_5.js` para o problema 5
   - `scripts_6.js` para o problema 6

### Orientações

- Siga as diretrizes fornecidas na aula ou consulte a documentação disponível no Notion para garantir que você está operando corretamente em JavaScript.
- Crie um repositório no GitHub contendo as soluções de cada problema.
- Anexe o link do repositório na atividade do Classroom para a avaliação.

### Dicas Adicionais

- Teste seus scripts para garantir que estão funcionando conforme o esperado antes de entregar.
- Mantenha uma estrutura clara em seus arquivos, definindo nomes de variáveis e funções que façam sentido e reflitam o propósito para o qual estão sendo usadas.

## Ex: Exercícios

### Problema 1: Verificação de Habilidade para Dirigir

Crie uma função com dois parâmetros, um inteiro e um booleano (True ou False), que determina se uma pessoa pode dirigir com base na idade e se ela tem ou não carteira de motorista.

```javascript
// scripts_1.js
function podeDirigir(idade, temCarteira) {
    if (idade >= 18 && temCarteira) {
        console.log("Você está apto(a) a dirigir.");
    } else {
        console.log("Você não está apto(a) a dirigir.");
    }
}

// Teste da função
podeDirigir(20, true);  // "Você está apto(a) a dirigir."
podeDirigir(20, false); // "Você não está apto(a) a dirigir."
podeDirigir(16, false); // "Você não está apto(a) a dirigir."


## Obrigada por visitar esse repositório!