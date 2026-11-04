# NOSSAS FINANÇAS

App de finanças do casal: lançamentos, acerto de quem deve a quem, orçamento por categoria, metas e dívidas.

- Login e dados em tempo real pelo Firebase (Authentication + Firestore).
- Publicado pelo GitHub Pages a cada push na branch `main`.
- No iPhone: abra no Safari → Compartilhar → **Adicionar à Tela de Início**.

O acesso aos dados é controlado pelas regras do Firestore (só os e-mails autorizados leem e escrevem). A configuração do Firebase no `index.html` é pública por design e não dá acesso sozinha.
