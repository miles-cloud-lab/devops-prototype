# DevOps Prototype

DevOps console prototype and interaction design.

## Prototype Modules

### `pipeline-version/`

Pipeline manual run dialog with branch/tag selection.

- Unified prototype file: `pipeline-version/index.html`
- Compatibility entry: `pipeline-version/multi-branch-tag.html`
- Scope:
  单分支模式下只能选择一个分支或一个标签。
  多分支模式下支持多个分支、多个标签，以及分支和标签混选。
- Design basis:
  用户提供的 UI 规范。
  参考截图：Flux DevOps 流水线流程详情页、运行流水线弹窗。

### `pipeline-build-trace/`

Pipeline run source card and branch detail traceability.

### `image-tag-config/`

Image build task drawer with task-level image tag configuration.

### `ai-code-review/`

AI-assisted code review for pipeline code review tasks.

## Files

Each module keeps its PRD note and `index.html` prototype.
