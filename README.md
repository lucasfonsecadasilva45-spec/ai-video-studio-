# AI Video Studio — Projeto Completo

Este pacote organiza o projeto inteiro em ordem para acelerar a criação do site.

## Ordem de execução
01. Criar contas e chaves
02. Configurar Supabase
03. Configurar variáveis de ambiente
04. Instalar dependências
05. Rodar o frontend/backend
06. Conectar geração de vídeo
07. Conectar imagem → vídeo
08. Salvar projetos e vídeos
09. Sistema de créditos
10. Pagamentos
11. Segurança/moderação
12. Painel administrativo
13. Testes
14. Deploy
15. Domínio e lançamento

## Arquitetura

Usuário → Frontend → Backend → Runway
                         ↓
                    Supabase Auth
                         ↓
                    PostgreSQL
                         ↓
                   Supabase Storage

A chave da API de vídeo fica exclusivamente no backend.

## Observação
A plataforma não será "sem regras": o site pode oferecer uma experiência flexível, mas deve respeitar as políticas da API escolhida, leis aplicáveis e mecanismos de segurança.
