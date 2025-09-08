#Monitor Smartflux

## Sobre o app
O **Monitor Smartflux** é um app simples voltado para o setor agrícola.  
A ideia é conectar o celular a um sistema de GPS agrícola e à plantadeira/semeadeira para mostrar em tempo real se as linhas de adubo e sementes estão funcionando.  

O objetivo é ajudar o agricultor a perceber rápido quando alguma linha falhar (seja entupida ou parada), evitando prejuízo no plantio.

**Observação importante:** nesta versão do projeto, **todos os dados serão simulados** (GPS, status das linhas e quantidade por área). A ideia é mostrar o funcionamento do app mesmo sem o hardware real conectado.

### Funcionalidades (MVP)
- [ ] Simular conexão com leitor GPS agrícola
- [ ] Mostrar posição no mapa em tempo real (com dados simulados)
- [ ] Simular funcionamento das linhas de adubo
- [ ] Simular funcionamento das linhas de sementes
- [ ] Alertar falhas simuladas em tempo real (linha parada ou entupida)

### Funcionalidades adicionais (para o futuro)
- [ ] Histórico de plantio por talhão
- [ ] Relatórios de eficiência
- [ ] Monitorar quantidade aplicada por alqueire (adubo/semente)
- [ ] Exportar dados em PDF/CSV
- [ ] Integração com softwares de gestão agrícola
- [ ] Conexão real com GPS e sensores da plantadeira

---

## Telas
Protótipos sendo feitos no Figma.  
Ainda estou aprendendo a mexer na ferramenta, então por enquanto está em andamento.  

_Status atual: Em andamento._

---

## Modelagem do banco
O banco vai guardar (dados simulados por enquanto):
- Usuário (login/cadastro)
- Leituras do GPS (coordenadas, velocidade, área percorrida)
- Status de cada linha da plantadeira (adubo/semente, ok ou falhou)
- Histórico de falhas
- Quantidade aplicada por área (sementes/adubo por alqueire)

_Modelagem em andamento._

---

## Planejamento de Sprints

| Sprint | Semana | O que fazer |
|--------|---------|-------------|
| 1 | Semana 1-2 | Pensar no escopo do app, levantar requisitos básicos e criar o repositório no GitHub. |
| 2 | Semana 3-4 | Fazer os protótipos de tela no Figma, desenhar a modelagem do banco e começar a organizar o README. |
| 3 | Semana 5-6 | Criar tela de login/cadastro, configurar a navegação básica no app e mostrar o mapa com posição do GPS (simulado). |
| 4 | Semana 7-8 | Implementar monitoramento das linhas da plantadeira (simulado) e fazer o sistema de alertas quando uma linha falhar. |
| 5 | Semana 9-10 | Salvar os dados simulados no banco/API (status das linhas, falhas, quantidade aplicada) e testar se a integração funciona. |
| 6 | Semana 11 | Fazer ajustes finais: corrigir bugs, melhorar a interface, organizar o README e preparar para a entrega final. |

---

##Observações
- Projeto feito em **React Native** com **Expo**  
- Figma e modelagem do banco estão sendo montados ainda  
- Todos os dados (GPS, linhas, quantidade aplicada) serão **simulados nessa versão**
