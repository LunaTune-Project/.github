# .github
Official LunaTune organization profile and shared community guidelines.

## Shared repository conventions

Keep each project independently buildable and avoid runtime dependencies on another repository solely to share constants.

- This repository owns public organization branding and organization-wide presentation.
- [LunaTune-Community](https://github.com/LunaTune-Project/LunaTune-Community) owns the public community website and published policies.
- Application-specific assets, configuration, and implementation remain in the application repositories. Reuse canonical assets and definitions within each project; link to the public source of truth instead of duplicating policy text.
- Keep shared documentation concise, remove verified unused files, and preserve historical recovery checkpoints. Never alter backup repositories or backup branches without explicit owner authorization.
- Keep private development, operational and security information in its authorized repositories.
