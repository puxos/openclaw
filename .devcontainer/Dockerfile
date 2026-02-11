FROM mcr.microsoft.com/devcontainers/javascript-node:22-bookworm

# Install Bun (required for build scripts)
RUN curl -fsSL https://bun.sh/install | bash
# ENV PATH="/root/.bun/bin:${PATH}"

RUN corepack enable

# WORKDIR /workspace/
# Install dependencies
# RUN pnpm install --frozen-lockfile

# # Build
# RUN OPENCLAW_A2UI_SKIP_MISSING=1 pnpm build
# # Force pnpm for UI build (Bun may fail on ARM/Synology architectures)
# RUN npm_config_script_shell=bash pnpm ui:install
# RUN npm_config_script_shell=bash pnpm ui:build