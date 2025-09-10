# Exercícios - Estruturas de Dados Básicas

1. Processamento de Dados Hierárquico
Crie um sistema que processe uma lista de dicionários representando produtos com: nome, categoria, preço e tags (lista). Agrupe os produtos por categoria, calcule preço médio por categoria e liste produtos com tags específicas.

2. Análise de Texto com Múltiplas Estruturas
Processe um texto longo para:

Contar frequência de palavras usando dict

Identificar palavras únicas com set

Manter ordem de primeira ocorrência com OrderedDict

Encontrar bigramas usando tuple como chave

3. Sistema de Gestão de Relacionamentos
Implemente um grafo de relacionamentos usando dicionário de sets (amizades). Adicione funções para:

Amigos em comum entre 3 pessoas

Amigos de amigos (2º grau)

Conexões mais populares (mais amizades)

4. Processamento de Dados Transacional
Simule um sistema de transações com listas de tuplas: (id, tipo, valor, timestamp). Calcule:

Saldo final

Maior sequência de transações positivas

Média móvel dos últimos 5 valores

5. Otimização de Consultas com Sets
Dados dois grandes conjuntos de dados (10k+ elementos cada), implemente:

Interseção eficiente

Diferenças simétricas

Verificação de subconjuntos
Medindo performance com time.time()

6. Estrutura de Dados Composta Complexa
Crie uma nested structure:
lista de dicionários onde cada valor pode ser:

Lista de tuplas

Set de dicionários

Outras combinações profundas
Implemente um buscador recursivo que encontre valores em qualquer nível.

7. Manipulação Avançada de Tuplas
Dada uma lista de tuplas coordenadas (x, y, z):

Rotacione coordenadas (transformação matricial)

Agrupe pontos por quadrante

Calcule distâncias euclidianas entre todos os pares
Usando apenas compreensão de listas e tuples.

8. Sistema de Cache com OrderedDict
Implemente um sistema LRU (Least Recently Used) cache com:

Capacidade máxima

Atualização automática ao acessar

Remoção do menos usado quando cheio

Estatísticas de hit/miss

9. Processamento de Dados em Tempo Real
Simule um stream de dados usando collections.deque:

Janela deslizante de valores

Cálculos estatísticos na janela móvel

Detecção de anomalias (valores fora de 2σ)

10. Estrutura Híbrida para Gestão de Estado
Crie um sistema que combine:

Sets para usuários ativos

Dicts com defaultdict para contadores

Listas como pilhas para histórico de ações

Tuplas namedtuple para registros imutáveis
Implemente transições de estado complexas.