# gines-ota

Manifesto e bundles web do app GINES para atualização remota (OTA), publicados pelo workflow `ota.yml` do repositório `gines-ai/gines-client`. Servido pelo GitHub Pages em `https://gines-ai.github.io/gines-ota/`.

- `manifest.json` — qual bundle está publicado (commit, seq, build, arquivo, checksum).
- `bundle-<sha>.zip` — o bundle web daquele commit.

Não edite à mão: o pipeline reescreve tudo a cada publicação.
