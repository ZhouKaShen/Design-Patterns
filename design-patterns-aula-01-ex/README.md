# Atividade

Que tal refletirmos um pouco sobre o que acontece com esse código quando novos requisitos são adicionados?

---

## 🎯 Objetivo da Atividade

Altere o código da classe PlanetasPrinter que os planetas também possam ser impresso. 
Tente fazer isso com o menor esforço possível.

Verifique a classe [br.pucpr.Planet](https://github.com/ViniGodoy/design-patterns/blob/aula-01-ex/src/main/java/br/pucpr/planet/Planet.java)

O formato de impressão da tabela (bordas, temas) deve ser exatamente igual ao da tabela de usuários.

Quanto aos dados:
1. Devem ser impressas as seguintes colunas "Nome", "Diâmetro", "Dist. sol (km)", "Dist. sol (ua)", e "Tipo". Observação uma unidade astronomica (UA) é equivalente à distância da Terra ao Sol.
2. O diametro do planeta deve ser impresso com 1 casa decimal e separadores de milhar.
3. A distância até o sol em km deve ser impressa em um número inteiro com separadores de milhar.  
4. Já a distância em UA deve ser impressa com duas casas decimais com separadores de milhar.
5. O tipo deve ser impresso como "Rochoso", "Gososo", "Gelado", "Anão"

## 📋 Reflexão final

Ao final da implementação reflita:

1. Sua solução ficou com muito código duplicado?
2. O que aconteceria se uma terceira classe tivesse que ser adicionada?

---

## 🛠️ Requisitos para Execução

* **Linguagem:** Java 17 ou superior

### Como Executar

```bash
javac PlanetasPrinter.java
java PlanetasPrinter
```


## Dificuldades encontradas

Durante o desenvolvimento da atividade, algumas dificuldades acabaram impactando o andamento do projeto:

**Requisitos pouco detalhados:** algumas partes da atividade não deixavam claro como determinados casos deveriam ser tratados, principalmente na impressão dos planetas, como valores nulos, alinhamento, unidades e formato dos dados.

**Falta de exemplos de saída:** não havia muitos exemplos pra comparar o resultado final. Isso dificultou a validação de detalhes como bordas, casas decimais, separadores e formatação.

**Organização do projeto:** foi necessário analisar a estrutura dos pacotes e das classes pra entender onde cada funcionalidade deveria ser implementada, principalmente na parte de impressão e formatação dos dados.

**Evitar código duplicado:** um dos pontos que exigiu mais atenção foi decidir como compartilhar a lógica de formatação entre as classes sem simplesmente copiar e colar o mesmo código.

**Algumas decisões de implementação:** em alguns casos foi necessário escolher uma forma de implementar o requisito por não haver uma especificação mais detalhada. Um exemplo foi a definição dos nomes utilizados para os tipos de planetas, como "Rochoso", "Gasoso", "Gelado" e "Anão".

**Validação:** algumas partes precisaram ser verificadas manualmente durante o desenvolvimento, já que não havia uma suíte de testes automatizados ou exemplos completos de saída pra fazer a comparação.

No geral, as principais dificuldades ficaram relacionadas a interpretação dos requisitos, a organização do código e a validação do resultado final.
