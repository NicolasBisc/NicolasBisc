# Nicolas Biscaia

Estudante de Engenharia de Software e Aprendiz em Tecnologia na **Koube
Química do Brasil**. Transformo processos manuais da fábrica em software que
funciona no dia a dia: hoje mantenho um sistema de produção e manutenção que
substituiu um conjunto de planilhas e está **em operação interna desde agosto
de 2026**.

Busco oportunidade como **Desenvolvedor Júnior** ou **Estágio em
Desenvolvimento de Software**.

📍 Araucária-PR · [nicolasbiscaia.dev](https://nicolasbiscaia.dev) ·
[LinkedIn](https://www.linkedin.com/in/nicolasbiscaia/)

---

## Projetos em destaque

### [Sistema de Gestão de Produção e Manutenção](https://github.com/NicolasBisc/Sistema-de-Producao-Koube)
**Em produção na Koube** · [ver interface](https://koube-producao.vercel.app/)

Centraliza programação de produção, manutenção preventiva e corretiva,
colaboradores, férias, auditoria e indicadores, antes espalhados em planilhas
paralelas com numeração duplicada e cálculos feitos à mão.

- Backend em **FastAPI** com 41 endpoints, 16 tabelas e validação
  **Pydantic** em todas as rotas de escrita
- O vencimento e o status das preventivas são **calculados** a partir da
  última execução, sem campo de status para alguém esquecer de atualizar
- **Segurança:** autenticação JWT, senhas com bcrypt, permissão por módulo,
  rate limit e bloqueio após tentativas de login
- **Auditoria completa:** toda alteração guarda autor, ação e os valores
  antes e depois
- **Operação:** Docker, migrações SQL idempotentes, backup diário com
  retenção de 30 dias e testes de interface com Playwright
- Base com 44 equipamentos, 255 atividades preventivas e cerca de 790 ordens
  de serviço. O repositório público usa uma cópia sem dados pessoais.

`Python` `FastAPI` `PostgreSQL` `JavaScript` `HTML/CSS` `Docker` `Playwright`

### [Koube-Analise-Envase](https://github.com/NicolasBisc/Koube-Analise-Envase)

Automatiza os relatórios do setor de Envase: lê a planilha de programação do
mês e gera em Word o dashboard semanal de programado vs. realizado e o
progresso acumulado da meta.

- Reescrevi os scripts originais como um pacote organizado, com CLI e testes
  das regras de cálculo
- Os dois relatórios passaram a sair da mesma fonte, o que acabou com a
  digitação em dobro e as divergências entre eles
- Corrigi bugs que geravam números errados nos relatórios: sinal negativo
  sumindo, data de emissão quebrada e média diária calculada sobre o divisor
  errado
- A leitura de dados ficou isolada, então os relatórios podem passar a usar
  o sistema de produção sem reescrita

`Python` `python-docx` `Matplotlib` `unittest`

---

## Experiência

**Koube Química do Brasil**, Aprendiz em Tecnologia / Auxiliar Administrativo
_Fev 2026 – presente_

- Desenvolvi e coloquei em operação o sistema de gestão de produção e
  manutenção descrito acima
- Automatizei relatórios e análises de dados com Python, substituindo
  tarefas manuais
- Criei um treinamento interativo sobre a metodologia 5S em HTML e CSS
- Atuo no TOTVS ERP com requisições e dashboards em Excel avançado
- Organizei e centralizei o acervo digital da empresa no SharePoint

## Tecnologias

**Uso no dia a dia:** Python · FastAPI · PostgreSQL / SQL · JavaScript ·
HTML · CSS · Docker · Git · Excel avançado
**Estudando:** Java · modelagem de banco de dados · testes automatizados
**Processos:** BPMN · casos de uso · jornada do usuário · usabilidade

## Formação

**Universidade Positivo**, Bacharelado em Engenharia de Software
_Mar 2026 – presente_

## Certificados

- Python para Dados, Alura
- Desenvolvimento Back End com Java, Alura
- Excel do Básico ao Avançado, Fundação Bradesco
- Inteligência Emocional, Fundação Bradesco
- Atendimento ao Público, Fundação Bradesco
