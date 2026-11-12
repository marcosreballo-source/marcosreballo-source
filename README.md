### Olá! Sou o Marcos Vinicius Reballo 👋

Estudante de Sistemas de Informação no **ICMC/USP**, com experiência em **P&D no Instituto Eldorado** (otimização de rotas, ML e computação quântica) e iniciação científica em grafos de conhecimento. Construo sistemas de IA aplicada de ponta a ponta: da coleta de dados ao modelo, à infraestrutura de treino e ao painel que alguém usa para decidir.

#### 🤖 IA generativa e agentes
- **[genai-content-pipeline](https://github.com/marcosreballo-source/genai-content-pipeline)**: sistema multiagente (Gemini/Antigravity) que produz relatórios, slides e LaTeX. O LLM só preenche especificações curtas, e scripts determinísticos montam e auditam o resultado. Economiza **≈ 45–55 h por semestre**.

#### 🚚 Logística e otimização de rotas
- **[delivery-graph-builder](https://github.com/marcosreballo-source/delivery-graph-builder)**: transforma a malha de ruas (OpenStreetMap) em grafo, encaixa as entregas e resolve as rotas com OR-Tools. Mostra horas ao volante e subida acumulada. **[▶ demo](https://delivery-graph-builder-canoas.streamlit.app/)**
- **[route-time-crawler](https://github.com/marcosreballo-source/route-time-crawler)**: crawler 24 h de tempos de trajeto por horário, com controle de custo de API. Foram 75,6 mil medições numa rede real de varejo.

#### ⚙️ MLOps e pesquisa
- **[sagemaker-training-launcher](https://github.com/marcosreballo-source/sagemaker-training-launcher)**: `smlaunch`, CLI que lança, acompanha e audita o custo de treinos na AWS SageMaker a partir de um YAML (29 testes).
- **[quantum-routing-research](https://github.com/marcosreballo-source/quantum-routing-research)**: QGAT (GNN híbrida quântica + RL) e QAOA multiobjetivo para roteamento.

#### 🏥 Produto
- **[vaccine-cold-chain-monitor](https://github.com/marcosreballo-source/vaccine-cold-chain-monitor)**: painel de rede de frio de vacinas para UBS, com alerta antecipado por tendência. **[▶ demo](https://vaccine-cold-chain-monitor.streamlit.app/)**

#### 📄 Publicações
- *A hybrid quantum-classical neural network for learning to route*: [arXiv:2609.00489](https://arxiv.org/abs/2609.00489), apresentado no CBCTQ 2026

  <img src="https://raw.githubusercontent.com/marcosreballo-source/quantum-routing-research/main/docs/cbctq_2026_apresentacao.jpg" alt="Apresentando o QGAT no CBCTQ 2026" width="520">
- *Quantum Approximate Multi-Objective Optimization in Routing Problems*: [arXiv:2610.00168](https://arxiv.org/abs/2610.00168)
- *Evaluating Parameter Transfer in FALQON Across Graph Families*: SBCCQ 2026, [DOI](https://doi.org/10.5753/sbccq.2026.23365)
- *Sparse Walsh-Pauli Correlation Encoding for MaxCut*: [arXiv:2609.08907](https://arxiv.org/abs/2609.08907)

**Stack:** Python · PyTorch · PennyLane/Qiskit · OR-Tools · NetworkX/OSMnx · AWS SageMaker · MLflow · Slurm/Apptainer · Streamlit · LLM agents

[ORCID](https://orcid.org/0009-0003-6396-9302) · [LinkedIn](https://www.linkedin.com/in/marcos-vinicius-reballo/)
