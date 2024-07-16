# Install

## Install all dependencies
Run in workspace root:
```shell
npm ci
```

Run in a nested project folder:
```shell
npm ci --include-workspace-root
```

## Install project-specific dependencies
Run in workspace root:
```shell
npm ci -w <project-name>
```

Run in a nested project folder:
```shell
npm ci
```

# Run
Run script <script-name> in all projects:
```shell
npm run <script-name> --workspaces true --include-workspace-root
```
