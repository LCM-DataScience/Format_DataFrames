🟢🟡Formatação de cores e textos em DataFrames🔵⚪️


Este é um exemplo prático de como podemos utilizar a biblioteca Pandas para formatar e estilizar DataFrames, tornando nossas análises mais compreensíveis e visualmente atraentes.

Foi usado o método "set_table_styles" que é um objeto 'Styler' do Pandas. Ele permite aplicar estilos 'CSS' específicos às células de um DataFrame formatado. Essa função é usada para definir estilos adicionais para a tabela gerada pelo 'Pandas Styler', como a cor do texto, fundo, alinhamento e tamanho da fonte para diferentes tipos de células na tabela, como células de dados (td), cabeçalhos de coluna (th), cabeçalho de índice (th.index_name) e títulos de linha (th.row_heading).

Esta análise foi feita com dados da 'WEGE3' extraídos do Yahoo Finance:

▶️Filtragem de Dados: extraídos a partir de maio de 2024

▶️Cálculo de Resultado Percentual: variação percentual entre o preço de abertura e fechamento para cada registro.

▶️Formatação Visual: aplicadas cores distintas para destacar variações positivas e negativas, facilitando a interpretação.

Também utilizei a biblioteca IPython.display. Ela permite a exibição de HTML diretamente no notebook, perfeita para este exemplo, onde é utilizada para exibir HTML diretamente no Jupyter Notebook, permitindo exibir as diferenças dos Dataframes em um mesmo resultado.

Dependendo do tipo de análise, pode ser mais útil e ágil do que escolher gráficos mais complexos como o Matplotlib ou Seaborn. A formatação direta em DataFrames permite uma visualização rápida e eficiente dos dados tabulares, sem a necessidade de lidar com a sintaxe mais complexa das bibliotecas de visualização. Isso torna essa abordagem uma opção acessível e eficaz para análises rápidas e comunicação de resultados, especialmente em situações onde a interpretação rápida dos dados é crucial.


