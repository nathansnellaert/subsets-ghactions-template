# Subsets Integration Template

A template for building data connectors powered by GitHub Actions. It handles common integration requirements like Python/Poetry setup, scheduling, and git-based data storage, allowing you to focus on writing the data collection logic. 

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

