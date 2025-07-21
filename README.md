# ✅ Concluí o módulo "Projetar uma Solução de Aprendizado de Máquina" com foco prático no Azure Machine Learning.
Neste projeto, explorei o ciclo completo de desenvolvimento de uma solução de Machine Learning utilizando os recursos do Azure Machine Learning:

# Configuração e uso de Workspaces

📂 Configuração e Uso de Workspaces no Azure Machine Learning
O Workspace é o ambiente central no Azure Machine Learning onde todos os recursos e experimentos são organizados e gerenciados. Ele permite:

- Centralizar experimentos, datasets, modelos, pipelines e endpoints.
- Gerenciar recursos computacionais e ambientes de execução.
- Controlar o acesso com permissões baseadas em funções do Azure (RBAC).
- Integrar ferramentas como o Azure CLI, SDK (Python), Visual Studio Code e o portal web.
Criar e configurar um workspace envolve selecionar uma assinatura, grupo de recursos, região e definir o nome do workspace. Após criado, ele serve como base para todo o ciclo de vida do machine learning.

# Uso de ferramentas de desenvolvedor (CLI, SDK, portal)
🛠️ Ferramentas de Desenvolvedor no Azure Machine Learning
- O Azure ML oferece várias ferramentas para interação com o workspace e automação de tarefas:
- Azure Portal: Interface gráfica para criar, visualizar e gerenciar recursos do ML de forma intuitiva.
- Azure CLI: Linha de comando para executar ações como criar workspaces, registrar modelos, iniciar experimentos e gerenciar recursos.
- Python SDK (Azure ML SDK): Biblioteca poderosa para desenvolvimento programático de soluções de ML, incluindo preparação de dados, configuração de experimentos, uso de AutoML e implantação de modelos.

Essas ferramentas permitem flexibilidade no desenvolvimento, desde tarefas manuais até automações e integrações em pipelines de CI/CD.

# Disponibilização e manipulação de dados para experimentos
📊 Disponibilização e Manipulação de Dados no Azure Machine Learning
- Upload de dados para o workspace via portal, SDK ou CLI.
- Armazenamento em DataStores, como Azure Blob Storage ou Data Lake.
- Criação de Datasets (tabulares ou de arquivos), que facilitam o versionamento, reutilização e rastreamento dos dados.
- Integração com experimentos e pipelines, garantindo que os dados estejam disponíveis para treinamento de forma escalável e reproduzível.

Essas práticas promovem organização, controle e rastreabilidade no ciclo de vida do machine learning.

# Criação e gerenciamento de ambientes de execução
🧪 Criação e Gerenciamento de Ambientes no Azure Machine Learning
- Os Ambientes no Azure ML definem o contexto de execução dos experimentos, garantindo que todos os pacotes, dependências e configurações estejam padronizados e reproduzíveis. Eles permitem:
- Especificar dependências com conda.yaml ou diretamente via código.
- Usar ambientes pré-configurados da Microsoft ou criar ambientes personalizados.
- Controlar versões de ambientes para facilitar a repetição de experimentos.
- Reutilizar ambientes em diferentes experimentos, pipelines e endpoints de inferência.

Ambientes bem gerenciados evitam erros de compatibilidade e garantem consistência entre desenvolvimento local e em nuvem.

# Execução de experimentos com Machine Learning Automatizado (AutoML)
🤖 Execução de Experimentos com Machine Learning Automatizado (AutoML)
- O AutoML no Azure ML permite automatizar o processo de seleção, treinamento e ajuste de modelos de machine learning, ideal para tarefas como classificação, regressão e séries temporais. Com ele, é possível:
- Fornecer dados rotulados e definir a métrica de avaliação.
- Deixar o Azure ML testar automaticamente diferentes algoritmos e configurações (modelos + hiperparâmetros).
- Acompanhar os experimentos em tempo real pelo portal ou SDK.
- Identificar e registrar o melhor modelo com base nos resultados.
- Facilitar a implantação do modelo vencedor como endpoint.

AutoML acelera o desenvolvimento e ajuda a obter modelos de alta performance mesmo com pouca experiência em tuning manual.

# Identificação do melhor modelo de classificação

🏆 Identificação do Melhor Modelo de Classificação com AutoML
- Após a execução de um experimento com Machine Learning Automatizado (AutoML) no Azure ML, a plataforma:
- Avalia dezenas de modelos de classificação com diferentes algoritmos e combinações de hiperparâmetros.
- Usa métricas como Acurácia, AUC, Precisão, Recall ou F1-score (definidas pelo usuário) para comparar os resultados.
- Classifica os modelos automaticamente, destacando o que teve o melhor desempenho.
- Permite registrar o modelo vencedor no workspace e implantá-lo com facilidade como serviço em nuvem (endpoint).

Esse processo otimiza o tempo e entrega modelos prontos para produção com base em evidência e desempenho real.

# Essa experiência reforçou meus conhecimentos em MLOps, automação de experimentos e boas práticas na construção de soluções escaláveis de machine learning em nuvem.
