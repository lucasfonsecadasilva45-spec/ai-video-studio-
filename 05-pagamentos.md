# 05 — Pagamentos

Criar planos, por exemplo:
- Starter: 100 créditos
- Creator: 500 créditos
- Pro: 1500 créditos

Fluxo:
Pagamento confirmado → webhook → backend valida assinatura → adiciona créditos → registra transação.

Nunca libere créditos apenas porque o navegador informou que o pagamento foi concluído.
