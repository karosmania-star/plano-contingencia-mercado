# 🛒 Plano de Contingência Digital: Continuidade de Negócios para Supermercados

Este repositório apresenta um **Plano de Contingência Digital** focado em infraestrutura de TI e governança operacional, desenvolvido para mitigar os impactos da indisponibilidade de internet nos pontos de venda (caixas/PDV) de um mercado local. 

O objetivo central é garantir a resiliência do negócio, mantendo o foco absoluto em **salvar a venda** e garantir a **continuidade do atendimento** sem causar gargalos na operação.

---

## 🎯 Pilares Estratégicos do Plano

O projeto foi estruturado visual e operacionalmente em três fluxos simultâneos de resposta a incidentes:

### 1. Salvar a Venda e Manter o Atendimento
Ações focadas na experiência do cliente e na saúde financeira do estabelecimento durante a falha:
* **Priorização do Pedido:** Foco máximo em fechar a venda rapidamente usando métodos alternativos de pagamento.
* **Alternativas de Pagamento:** Disponibilização e oferta ativa de cartões, dinheiro ou agendamento para pagamento futuro.
* **Transparência e Comunicação:** Informar o cliente sobre a situação operacional de forma clara e transparente, mantendo a confiança.
* **Auditoria de TI (Registro do Ocorrido):** Anotação exata do horário da falha para posterior relatório de Incident Management (Gerenciamento de Incidentes).

### 2. Restabelecimento Rápido da Conexão do Caixa (Procedimento Operacional)
Passo a passo visual e técnico para ativação de redundância local via dados móveis:
* **Ativação de Hotspot Móvel:** Ativação dos dados móveis e do roteador Wi-Fi do smartphone corporativo do balcão.
* **Conexão do PDV:** Vinculação do computador do caixa à nova rede compartilhada disponível.
* **Ciclo de Energia (Reboot):** Reinicialização da maquininha de cartão.
* **Provisionamento de Nova Rede:** Conexão da maquininha ao sinal de internet alternativo via Wi-Fi móvel.

### 3. Gerenciamento de Crise e Suporte Técnico
Diretrizes para o operador enquanto a conexão principal não é restabelecida:
* **Escalação de Chamados:** Acionamento imediato do suporte técnico caso a conexão principal não retorne em tempo hábil.
* **Registro de Logs de Indisponibilidade:** Análise pós-incidente através do registro detalhado de datas e horários da falha.
* **Segurança da Informação:** Processo rigoroso de confirmação de aprovação de pagamentos antes da liberação física de qualquer produto do mercado.

---

## 📂 Estrutura de Arquivos no Repositório

* `README.md`: Esta documentação com a visão geral do projeto.
* `/assets/plano-contingencia-digital.pdf`: O panfleto visual completo contendo o guia rápido passo a passo para os operadores de caixa.
* `/video/treinamento-operacional.mp4`: Vídeo institucional e explicativo demonstrando a execução prática dos procedimentos em tempo real.

---

## 🎓 Contexto do Projeto
Este material foi idealizado e construído como um projeto prático para o curso superior de **Gestão da Tecnologia da Informação**. O projeto simula com precisão a aplicação de frameworks de governança (alinhados a conceitos de ITIL e Gerenciamento de Serviços de TI) para o comércio de bairro, provando que soluções de alta disponibilidade podem ser aplicadas de forma enxuta e barata.
