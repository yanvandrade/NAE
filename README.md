# NAE — protótipo acadêmico

Painel web demonstrativo para organizar acolhimentos do NAE, inspirado nas telas e nos requisitos levantados para o projeto de estágio.

## Executar localmente

Requer Node.js instalado.

```powershell
npm.cmd install
npm.cmd run dev
```

Abra `http://localhost:5173`. O React/Vite atende a interface e o Express disponibiliza a API local em `http://localhost:3001/api`.

## Telas disponíveis

- Visão geral com agenda do dia e encaminhamentos demonstrativos.
- Agenda com busca, filtro, cadastro de atendimento e atualização de status.
- Estudantes com busca, filtro por curso, ficha e cadastro.
- Encaminhamentos com consulta de histórico e mudança de status demonstrativa.
- Relatórios simples de atendimentos e estudantes por curso.

Os registros do protótipo ficam em `server/data.json`, criado no primeiro início. Remover esse arquivo reinicializa os dados de demonstração.

## Limites desta versão

Esta é uma demonstração acadêmica: os nomes e registros iniciais são fictícios; não há autenticação, integração institucional, envio de e-mail/WhatsApp ou compartilhamento real com coordenações e professores. Não inserir dados pessoais reais, laudos, CID ou diagnósticos. Antes de uso institucional, faltam validação de requisitos, autenticação e autorização por perfil, armazenamento adequado, política de retenção e análise de segurança/LGPD.
