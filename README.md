# 📋 Pipeline AI Templates

Collection of pre-built CI/CD pipeline templates for various use cases.

## Templates

### GitHub Actions

| Template | Description |
|----------|-------------|
| `nodejs-basic` | Node.js with build, test, deploy |
| `nodejs-monorepo` | Node.js monorepo with Turborepo |
| `python-basic` | Python with pytest |
| `python-ml` | Python ML with MLflow |
| `go-basic` | Go with test coverage |
| `docker-build` | Docker build and push |
| `kubernetes-deploy` | K8s deployment |

### GitLab CI

| Template | Description |
|----------|-------------|
| `nodejs-gitlab` | Node.js for GitLab |
| `python-gitlab` | Python for GitLab |

## Usage

Simply copy the template you need:

```bash
# Node.js GitHub Actions
cp templates/github-actions/nodejs-basic.yml .github/workflows/ci-cd.yml
```

## Structure

```
templates/
├── github-actions/
│   ├── nodejs-basic.yml
│   ├── nodejs-monorepo.yml
│   ├── python-basic.yml
│   ├── python-ml.yml
│   ├── go-basic.yml
│   ├── docker-build.yml
│   └── kubernetes-deploy.yml
└── gitlab-ci/
    ├── nodejs.yml
    └── python.yml
```

## Contributing

Add your templates to the appropriate folder!

## License

MIT
