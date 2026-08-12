# 06 — Geração

Fluxo:
1. Usuário envia prompt.
2. Backend valida usuário e créditos.
3. Backend cria registro `projects`.
4. Backend chama Runway.
5. Salva `provider_task_id`.
6. Worker/cron consulta o status.
7. Quando concluído, baixa/arquiva o resultado no Storage.
8. Atualiza `status=SUCCEEDED` e `video_path`.
9. Frontend atualiza a biblioteca.

A API da Runway atualmente documenta text-to-video, image-to-video e video-to-video. O projeto deve tratar a geração como tarefa assíncrona.
