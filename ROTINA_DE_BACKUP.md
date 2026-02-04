# Rotina de Backup (Shirley) — Regras & Operação

> Objetivo: você conseguir retomar o trabalho **do ponto atual** caso precise trocar/reiniciar a assistente.
> Atualizado em: 2026-02-03

## 1) Regras de comportamento (prioridade alta)

### 1.1 “Shirley, deixa comigo”
- Quando o usuário disser **“Shirley, deixa comigo”** em um chat, a assistente **para de responder naquele chat específico**.
- Pode continuar em outros chats.
- Só volta a responder naquele chat quando o usuário liberar **ou** após **15 min sem mensagens**.

### 1.2 Conferência antes de enviar
- Antes de enviar mensagens, **confirmar mentalmente**: contato/número + assunto, para não misturar conversas.

### 1.3 Não falar com contatos bloqueados pelo usuário
- Se o usuário mandar “pare de falar com X”, **não responder mais** a X até segunda ordem.
- Exemplo ativo: **Financeiro AppTreinamento** → não falar até ordem.
- Exemplo ativo: “Parar de falar com Manoel” (se o usuário reiterar, obedecer).

### 1.4 Dra. Pricila / Dra. Robéria
- **Mesma pessoa**.
- Quando ela falar primeiro: **repassar o recado ao Galvão antes de responder**.
- Resposta padrão para ela: “Recebido, já repassei ao Galvão.”

### 1.5 Síndicos = clientes
- Se o **nome exibido** contiver “**síndico/síndica**” (ou vier da lista de síndicos), tratar como **cliente**.
- Responder: **“Vou falar com o Galvão e já retorno.”**
- Antes de retornar ao síndico, perguntar ao Galvão o **contexto/situação**.

### 1.6 Estilo
- Atendimento a clientes: **sucinto, sintético, objetivo e humano**.
- Sempre perguntar **dia e horário** para retornar.

## 2) Regra de WhatsApp: “tirar o 9”
- Ao enviar mensagem/ligar: tentar primeiro **sem o 9**.
- Se não funcionar, tentar **com 9**.

## 3) Escritório — contatos principais

### 3.1 Estagiários (lista oficial confirmada)
**Extrajudicial**
- Lays (Wanderley) — +55 81 99786-2945
- Wemelly (Freitas) — +55 81 97337-9900

**Processos / Contencioso**
- Ewerton — +55 81 98453-5207
- Rainer — +55 81 9833-7712

**Cobrança**
- Henri Oliveira — +55 81 9999-3743

### 3.2 Chefias / Cobrança
- Dra. Priscila (chefe Extrajudicial) — +55 81 99651-7524
- Anna Santa Cruz (chefe Processos/Contencioso) — +55 81 99227-3616
- Sheila Leite (ADM Sólida) — +55 81 98872-6658
- Robéria Morais (Cobrança) — +55 81 97313-4776

## 4) Água do escritório (rotina)
- Estagiários solicitam ao Galvão.
- Galvão pede ao Depósito da Esquina e paga via Pix (enviar comprovante).
- Fornecedor: **Depósito da Esquina** +55 81 8358-7968
- Modelo:
  "Oi! Um pedido da Shirley/Galvão:

  💧 2 garrafões de Cristalina
  📍 Endereço: Empresarial Business Beach - Av. Eng. Domingos Ferreira, 2160, Sala 904 - Boa Viagem
  💳 Pagamento: Via PIX (o Galvão envia o comprovante).

  Obrigada!"

## 5) Cursos (Polo Recife Estratégia Educação)

### 5.1 Grupo do Polo (cursos)
- Nome: Polo Recife Estratégia Educação
- JID: **120363369341436636@g.us**

### 5.2 Regra: pedir por escrito
- Pedir orientações **por texto**, não áudio.

### 5.3 Listagens e documentos (referência)
- Resumo por categoria + documentações: `/root/.openclaw/workspace/cursos_resumo_por_categoria_2026-02-03.md`
- Portfólio Lista 1 (versão 2026): `/root/.openclaw/workspace/portfolio_cursos_2026_lista1.pdf`

### 5.4 Administração Estratégica
- Conforme orientation do Polo: **Profissionalizante – Listagem 2 (80h)**.

### 5.5 Cobrança (profissionalizantes)
- **Nunca revelar** ao Polo o valor que o aluno paga, e nunca revelar ao aluno o valor interno do Polo.
- Opções de pagamento ao aluno (profissionalizantes):
  1) **Pix (CNPJ): 51.835.261/0001-62** (Estratégia Consultoria e Educação)
  2) **Cartão (link)**: https://checkout.nubank.com.br/LWzYEyR9MLgfxa3r  (não mencionar “Nubank” no texto)
- Texto padrão (cartão):
  “Acesse o link abaixo para pagar R$ 97,90 no cartão:
  https://checkout.nubank.com.br/LWzYEyR9MLgfxa3r”

### 5.6 Fluxo de matrícula (exemplo Taciana)
- Aluno paga **R$ 97,90** ao Galvão.
- Galvão paga **R$ 39,00** ao Polo (contato@apptreinamentos.com.br) **após** receber dados completos + comprovante do aluno.
- Só então o Polo faz matrícula e envia acesso.

## 6) Grupos de síndicos (envios automáticos)

### 6.1 JIDs cadastrados (síndicos)
- Síndicos Grande Recife — 120363315092704263@g.us
- Síndicos Prof. UCR — 558196727208-1472489898@g.us
- Síndicos Prof. UCR 1 — 558196282680-1446925793@g.us
- Gestores e VivaBem Condomínio (Grupo Caruaru) — 120363302000341426@g.us
- Prestação de Serviços #1 — 558196282680-1495160395@g.us
- COOPERH Escritório Virtual Networking — 120363298795315428@g.us

### 6.2 Rotina (cron)
- **Segunda 09:00 Recife**: enviar “COMBO Excel + Finanças” para todos os grupos de síndicos.
- **Terça 09:00 Recife**: enviar “Administração Estratégica” para todos os grupos de síndicos.
- Qualquer **novo grupo de síndicos** adicionado deve entrar nos envios.

## 7) Termo de acordo (Cobrança)
- Quando a Sheila mandar termo de acordo: avisar o Galvão **imediatamente** para assinatura GOV.
- Após assinatura, enviar o PDF assinado de volta para a Sheila.

## 8) Família / cadastros
- Mãe: Mary C. C. Chaves — +55 81 9206-2323 / +55 81 8373-0727
- Sogra: D. Rosa — +55 81 9862-8685 (cuida do João e Marcos; pode pedir água para a casa)
- Esposa: Robéria Priscila — +55 81 9651-7524 (pode pedir água casa/escritório)

## 9) Observações técnicas
- Não consigo ouvir áudios automaticamente; pedir texto quando necessário.
- Vídeos: orientar roteiro/edição (CapCut), mas sem processamento local.