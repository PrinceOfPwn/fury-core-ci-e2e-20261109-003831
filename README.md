# fury-core-ci E2E validation

Repositorio desechable para validar el comportamiento de `issue_comment` + `#tag` del snapshot `9a6d067` de `fury-core-ci`.

- `action/` contiene el bundle auditado (`dist/index.js`) y su `action.yml` sin modificaciones.
- `tagging.yml` ejecuta la acción en el repo base con `contents: write`, `actions: write` y `pull-requests: read`.
- `build.yml` existe sólo para recibir el dispatch de `trigger-build`.

No contiene secretos ni datos reales. Se puede borrar después de recoger la evidencia.
