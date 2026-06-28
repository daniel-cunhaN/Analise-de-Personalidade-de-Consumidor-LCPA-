# Contexto
Bases de CRM no varejo frequentemente sofrem com cadastros corrompidos, valores ausentes e falta de padronização, o que impossibilita análises precisas de marketing e vendas. O objetivo deste projeto foi auditar e higienizar uma base bruta de 2.240 clientes, preparando-a para alimentar dashboards corporativos.
Ação:
Desenvolvi um pipeline de tratamento de dados em Python, estruturado em 4 etapas:
1. Auditoria: Identificação de valores nulos, duplicatas e outliers de idade (clientes nascidos antes de 1940).
2. Tratamento (Limpeza): Eliminação de registros inconsistentes, imputação de dados ausentes utilizando a mediana e padronização de variáveis categóricas complexas (como a unificação de múltiplos status civis).
3. Engenharia de Atributos: Criação de novas métricas de valor para o negócio, como Idade atualizada, Gasto_Total (consolidando múltiplos canais de consumo), Total_Filhos e Anos_de_Loja (tempo de relacionamento).
4. Otimização: Descarte de colunas obsoletas, reordenação estratégica das variáveis e exportação do arquivo final no formato .csv.
# Resultado
Uma base de dados 100% limpa, consistente e enriquecida, reduzida de 29 colunas brutas para 22 atributos de alto valor analítico. O arquivo final foi compactado e otimizado para consultas rápidas em ferramentas de BI (como Power BI ou Tableau), eliminando erros de interpretação de dados de clientes em futuras campanhas de marketing.
## Antes
<img width="1920" height="874" alt="image" src="https://github.com/user-attachments/assets/2ab07669-d051-495e-af37-61e0a39dd51d" />
## Depois
<img width="1920" height="877" alt="image" src="https://github.com/user-attachments/assets/f2cf94c4-5e7f-44b4-b21f-0c9e52fae83c" />
