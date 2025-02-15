# Subsets Integration Template

WIP Template action that subsets uses for github-action based data integrations. 

## Usage

```yaml
jobs:
  integration:
    uses: subsets-dev/integration-template@v0.1
    with:
      run_command: ./run.sh
    secrets:
      SUBSETS_API_KEY: ${{ secrets.SUBSETS_API_KEY }}
```

