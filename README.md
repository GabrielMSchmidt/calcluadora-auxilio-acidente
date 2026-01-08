# Calculadora de Auxílio Acidente

Calculadora web para estimar o valor líquido de Auxílio Acidente que um cliente deve receber, considerando honorários advocatícios e custos do processo.

## Estrutura do Projeto

- `index.html` - Página principal com toda a estrutura, estilos e lógica
- `Logo-BMZ.png` - Logo do escritório (adicionar manualmente)

## Como Usar

1. Abra o arquivo `index.html` em qualquer navegador moderno
2. Preencha os campos:
   - **Salário da Época (R$)**: O valor do salário de benefício na época
   - **Meses de Retroativos**: Número de meses retroativos (máximo 65 meses - 5 anos + 13º salário)
   - **Duração do Processo (meses)**: Tempo estimado de duração do processo (padrão: 18 meses)
3. Clique em "Calcular" para ver o resultado

## Regras de Cálculo

### Valor Mensal do Auxílio
- O Auxílio Acidente corresponde a **50% do salário de benefício**
- **Regra especial**: Se o salário da época for menor que o salário mínimo atual (R$ 1.518,00), será usado 50% do salário mínimo no cálculo.

## Tecnologias

- HTML5
- CSS (Tailwind CSS via CDN)
- JavaScript Vanilla
- Lucide Icons

**Desenvolvido por BMZ - Belin, Medeiros e Zaiats**