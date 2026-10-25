# Página reserva da SMI Academy

Plano B da Black 2026 (decisão do Esley em 25/10/2026).

- `index.html`: a página que abre em **reserva.treinamentosmi.com.br** quando o site
  da academy cai. Fica no GitHub Pages, fora do servidor do site. Mostra o recado,
  o WhatsApp da campanha e, a partir de 22/11, os links de pagamento das ofertas
  da Black (que liberam o acesso sozinhos quando pagos).
- `.github/workflows/vigia.yml`: confere o site a cada 5 minutos e avisa no celular
  (ntfy) quando ele cai e quando volta. O canal fica no segredo `NTFY_TOPICO`.

Nada aqui tem dado de cliente, senha ou chave: o repositório é público para o
GitHub Pages ser gratuito.
