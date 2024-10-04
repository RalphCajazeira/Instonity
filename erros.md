### Cadastro de Materiais

- **Campo de Margem de Lucro:**
  - A margem de lucro está limitada de 0 a 100. Precisa ser um campo livre para aceitar qualquer valor.

- **Edição de Variantes:**
  - Não é possível editar as variantes cadastradas no momento. É necessário permitir a edição para ajustar as informações conforme necessário.

---

### Cadastro de Beneficiamento

- **Pesquisa de Insumo:**
  - A pesquisa de insumo não permite buscar pelo nome. É necessário rolar a barra para encontrar o insumo, o que dificulta o processo de seleção.

- **Exibição de Total por Custo:**
  - O total por custo dos insumos com base na capacidade produtiva não está sendo exibido. Adicionar essa funcionalidade para facilitar a visualização do custo total.

- **Edição Direta na Tabela:**
  - Não é possível alterar os dados dos insumos diretamente na tabela de beneficiamento. Permitir a edição inline para facilitar a atualização das informações.

- **Reorganização de Insumos:**
  - Não é possível movimentar a ordem dos insumos cadastrados no beneficiamento. Incluir funcionalidade para reorganizar os insumos conforme necessário.

- **Exibição de Tempo Total de Produção:**
  - Não está sendo exibido o tempo total de produção, que deve ser calculado como a soma dos tempos de cada insumo inserido. Adicionar essa informação para facilitar o acompanhamento do tempo total.

- **Ordem dos Insumos:**
  - A ordem dos insumos no cadastro de beneficiamento não está sendo mantida conforme a sequência original do cadastro. Manter a ordem conforme inserida.

---

### Cadastro de Produtos para Revenda

- **Campos de Margem de Lucro e Preço de Venda:**
  - No cadastro de Produtos para Revenda estão faltando os campos de margem de lucro e preço de venda. Adicionar esses campos para completar as informações.

---

### Orçamentos

- **Erro ao Adicionar Subproduto:**
  - O erro ocorre devido ao uso do padrão americano para números fracionados, que utiliza o ponto decimal ("."), enquanto o padrão brasileiro utiliza a vírgula (","). Isso impede que o subproduto seja adicionado corretamente.

- **Listagem de Orçamentos:**
  - A listagem de orçamentos não está visível. Deve ser adicionada para permitir a visualização de todos os orçamentos cadastrados.

- **Adicionar Beneficiamento:**
  - Na parte de adicionar beneficiamento ao orçamento, deve ser possível apenas pesquisar pelo nome e inserir a quantidade desejada. O tipo de unidade (m, m² ou unidade) já é definido no cadastro de beneficiamento.
  - Adicionar informações como preço unitário e preço total conforme a quantidade inserida para facilitar a visualização e cálculo do valor total do beneficiamento no orçamento.

- **Erro ao Editar Subproduto:**
  - Ao editar um subproduto no orçamento, o campo de comprimento está mudando automaticamente para o valor 2, sem intervenção do usuário.

- **Ordem das Colunas ao Lançar Subproduto:**
  - A ordem das colunas está invertida ao lançar um subproduto. A coluna de largura está aparecendo antes da coluna de comprimento.