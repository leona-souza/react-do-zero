# Semana 2
(30/ago à 03/set)

---
### Dia 3
---

- JSX pode conter "html" (não exatamente) e é convertido em funções JS quando compilado
- Não é recomendável passar uma arrow function em um 'onClick' (por exemplo)
  - [Referência](https://pt-br.reactjs.org/docs/handling-events.html)
- Podemos utilizar condições para renderizar componentes

##### Dúvidas:
- Como são os bugs relacionados com ; automáticos
  - [Referência](https://stackoverflow.com/questions/2846283/what-are-the-rules-for-javascripts-automatic-semicolon-insertion-asi)
  
##### Sugestões de leitura:
- [bind em componentes de classe](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_objects/Function/bind)

---
### Dia 4
---

- Ao usar map para iterar um array, não é recomendável usar o índice do array como chave única
- Inputs tipo text, textarea e select podem ser manipulados através de this.state.value
- Tomar cuidado com componentes controlados em formulários (definir state inicial)


##### Sugestões de leitura:
- [index as key](https://robinpokorny.medium.com/index-as-a-key-is-an-anti-pattern-e0349aece318)
 