# Caixa Explica

> Assistente de literacia financeira para jovens (14 a 25 anos), em português de Portugal.

Desenvolvido para o **AInnovation Hackathon 2026**, onde recebeu o **1.º lugar**. O prémio foi um estágio na Caixa Geral de Depósitos.

## O problema

Muitos jovens chegam à vida adulta sem saber fazer um orçamento, poupar para um objetivo, perceber juros e crédito, ou reconhecer uma burla. O Caixa Explica tenta tornar esses temas simples e práticos.

## A solução

Um agente conversacional que:

- ajuda a montar um orçamento e a definir objetivos de poupança;
- explica juros e crédito com exemplos concretos;
- reconhece sinais de burla e explica como os evitar;
- educa, sem recomendar produtos financeiros.

Princípio de base: **as contas são feitas por ferramentas testadas; o modelo de linguagem explica o resultado.** Assim, os números não dependem de alucinações do modelo.

## Arquitetura (resumo)

- **Backend** (Python): API com recuperação de informação (RAG) sobre uma base de conhecimento própria e calculadoras determinísticas.
- **Frontend** (Next.js): interface com dois modos, Utilizador e Verboso.
- **Execução**: Docker Compose para desenvolvimento local; API e front publicados em serviços cloud.

## Ecrãs

Capturas a acrescentar em `screens/` após aprovação da equipa.


## Equipa

- Luís Lamy
- Alessandro Nascimento (Aless Saints)

## Estado

Protótipo desenvolvido durante o hackathon. Esta vitrine resume o projeto e não inclui chaves de API, ficheiros de ambiente nem dados pessoais da equipa.
