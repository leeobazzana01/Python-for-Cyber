# Exercícios Funções
1. Closure com Estado Persistente
Crie uma função contador_factory() que retorna funções closure. Cada closure deve manter seu próprio estado interno e contar: total de chamadas, tempo desde a última chamada, e valor anterior.

2. Decorador com Parâmetros Dinâmicos
Implemente um decorador @limitar_chamadas(max_tentativas, periodo_segundos) que:

Limita chamadas da função decorada

Armazena tentativas por usuário (usando closure)

Levanta exceção personalizada se exceder o limite

3. Função de Alta Ordem com Múltiplos Níveis
Crie uma função compor(*funcoes) que retorna uma nova função composta. A função deve:

Aceitar funções com diferentes assinaturas

Manipular escopo para passar resultados parciais

Permitir composição de funções com diferentes números de argumentos

4. Factory de Funções com Escopo Dinâmico
Implemente uma função criar_manipulador(tipo, **config) que retorna funções personalizadas:

Cada função deve ter assinatura dinâmica baseada na configuração

Usar closure para capturar configurações específicas

Manipular escopo para criar variáveis privadas

5. Gerenciador de Contexto com Estado Complexo
Crie um gerenciador de contexto @contextmanager que:

Controla nested contextos

Mantém estado entre entradas e saídas

Gerencia recursos com rollback automático em caso de erro

6. Função Recursiva com Memoização Otimizada
Implemente uma função fibonacci(n) com:

Memoization usando closure

Cache limitado (LRU)

Controle de profundidade recursiva

Estatísticas de uso do cache

7. Dispatch Table com Escopo Dinâmico
Crie um sistema de dispatch onde:

Funções são registradas dinamicamente

Escopo é compartilhado entre funções do dispatch

Herança de comportamentos através de closure chains

8. Callback System com Closure Aninhado
Implemente um sistema de event handlers onde:

Callbacks mantêm estado entre chamadas

Handlers podem ser pausados/retomados

Escopo é preservado entre execuções assíncronas

9. Decorador para Injection de Dependências
Crie um decorador @inject(**dependencies) que:

Injeta dependências no escopo da função

Resolve dependências circularmente

Mantém instâncias singleton via closure

10. Função com Nonlocal e Global Complexos
Implemente uma função que demonstre:

Manipulação de 3 níveis de escopo: local, nonlocal, global

Shadowing intentional de variáveis

Modificação segura de escopos externos

Preservação de estado entre chamadas